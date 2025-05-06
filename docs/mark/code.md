<!-- Space: TS -->
<!-- Parent: Mark Kitchen Sink -->
<!-- Title: Mark Code -->
<!-- Label: markdown -->
<!-- Label: confluence -->

<!-- Macro: :toc:
     Template: ac:toc
     Printable: 'false'
     MinLevel: 2 -->

# Code Block
```
<html>
<head>
   <script>
      console.log("Hello World");
   </script>
</head>
<body>
   <p> Please open the console before clicking "Edit & Run" button </p>
</body>
<html>
```

# Code Block - Programming Language
```xml
<html>
<head>
   <script>
      console.log("Hello World");
   </script>
</head>
<body>
   <p> Please open the console before clicking "Edit & Run" button </p>
</body>
<html>
```

# Code Block - Title
```xml title Hello World
<html>
<head>
   <script>
      console.log("Hello World");
   </script>
</head>
<body>
   <p> Please open the console before clicking "Edit & Run" button </p>
</body>
<html>
```

# Code Block - Line Numbers
```xml linenumbers true
<html>
<head>
   <script>
      console.log("Hello World");
   </script>
</head>
<body>
   <p> Please open the console before clicking "Edit & Run" button </p>
</body>
<html>
```

# Code Block - Line Numbers with Starting Number
```xml linenumbers true firstline 10
<html>
<head>
   <script>
      console.log("Hello World");
   </script>
</head>
<body>
   <p> Please open the console before clicking "Edit & Run" button </p>
</body>
<html>
```

# Mermaid Graph
```mermaid title Mermaid Graph
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

# Mermaid Graph - Collapse
```mermaid collapse title Collapsible Mermaid Graph
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```