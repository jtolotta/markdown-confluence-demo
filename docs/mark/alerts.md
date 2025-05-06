<!-- Space: TS -->
<!-- Parent: Mark Kitchen Sink -->
<!-- Title: Mark Alerts -->
<!-- Label: markdown -->
<!-- Label: confluence -->

<!-- Macro: :toc:
     Template: ac:toc
     Printable: 'false'
     MinLevel: 1 -->

:toc:

# Introduction

The following is a list of the Confluence Alert macros that can be rendered using Mark.

# Error

The Confluence Alert **Error Box** macro is mapped to `<!-- Warn -->` Mark syntax.

> <!-- Warn -->
>
> **ERROR:** Confluence Error Box

# Info

> <!-- Info -->
>
> **INFO:** Confluence Information Box

# Tip

> <!-- Tip -->
>
> **TIP:** Confluence Tip Box

# Warn

The Confluence Alert **Warning Box** macro is mapped to the `<!-- Note -->` Mark syntax.

> <!-- Note -->
>
> **WARNING:** Confluence Warning Box

# GitHub Alerts

GitHub Alerts are mapped to Confluence macros, however, the mapping is not correct in some circumstances.

In addition, the GitHub Alert directive is displayed on the Confluence Alert macro as a string literal.

## GitHub Note Alert

The GitHub **Note** alert is mapped to the Confluence **Info** macro.

> [!NOTE]
>
> - Note bullet 1
> - Note bullet 2

## GitHub Tip Alert

> [!TIP]
>
> - Tip 1
> - Tip 2

## GitHub Warning Alert

> [!WARNING]
>
> - Warning 1
> - Warning 2

## GitHub Important Alert

The GitHub **Important** alert is mapped to the Confluence **Info** macro.

> [!IMPORTANT]
>
> - Important 1
> - Important 2

## GitHub Caution Alert

The GitHub **Caution** alert is mapped to the Confluence **Error** macro.

> [!CAUTION]
>
> - Caution 1
> - Caution 2
