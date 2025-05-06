# Markdown Confluence Demo

Publish Markdown to Confluence Demo

# Contents
- [Markdown Confluence Demo](#markdown-confluence-demo)
- [Contents](#contents)
- [Requirements](#requirements)
- [Mark Setup](#mark-setup)
  - [Docker](#docker)

# Requirements

The following is required to run each Confluence sync demo:

- Confluence Username - The specified username for updating Confluence page.
- Confluence API Token - The specified token for updating Confluence page.

# Mark Setup

[mark](https://github.com/kovetskiy/mark) is a tool for syncing your markdown documentation with Atlassian Confluence pages.

Mark reads your markdown file, creates a Confluence page if it's not found by its name, uploads attachments, translates Markdown into HTML and updates the contents of the page via REST API.

Mark uses an extended file format, which, still being valid markdown, contains several HTML-ish metadata headers, which can be used to locate page inside Confluence instance and update it accordingly.

If the page cannot be located then Mark creates a new page at the Space root-level.

## Docker
1. Install Docker
2. Run the following Docker command replacing the required parameters:

```
docker run --volume .:/app --rm -i kovetskiy/mark:latest mark --username "john.smith@example.com" --password API_TOKEN-Aa350j3KLH9j==... --base-url https://mycompany.atlassian.net/wiki --files "../app/docs/*.md" [--dry-run]
```

Replace the following parameters in the statement:
- volume: Mount the current working directory volume to the Docker app folder
- username: The Atlassian Username used to generate the API Token
- password: The Atlassian API Token
- base-url: The Atlassian Confluence URL
- files: The location of the markdown files relative to the volume app folder
- dry-run: (optional) Perform this check first before executing the command to verify the generated pages
