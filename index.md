---
layout: default
---

Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](./another-page.html).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# Header 1

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

```
The final element.
```
<title>textBoxes.html</title>
 <script type = "text/javascript">
  // from textBoxes.html
  function sayHi(){
  var txtName = document.getElementById("txtName");
  var txtOutput = document.getElementById("txtOutput");
  var name = txtName.value;
  txtOutput.value = "Hi there, " + name + "!"
  } // end sayHi
 </script>
 <link rel = "stylesheet"
   type = "text/css"
   href = "textBoxes.css" />
 </head>
 <body>
 <h1>Text Box Input and Output</h1>
 <form action = ">
  <fieldset>
  <label>Type your name: </label>
  <input type = "text"
    id = "txtName" />
  <input type = "button"
    value = "click me"
    onclick = "sayHi()"/>
  <input type = "text"
    id = "txtOutput" />
  </fieldset>
 </form>
 </body>
