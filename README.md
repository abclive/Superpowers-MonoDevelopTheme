# Superpowers-MonoDevelopTheme
A MonoDevelop default theme port

![Preview](http://puu.sh/gzPUN/51e6c7eded.png)

### Installation

Go to the SuperPowers TypeScript editor plugin folder

    path: plugins/sparklinlabs/typescript/public/editors/script/

Copy the iris.css file here and open index.js and index.html

In index.js find this line:

    ui.editor = CodeMirror.fromTextArea(textArea, {

And add this line below:

    theme: 'iris',

Then go to index.html and add this line after the first link tag:

    <link rel="stylesheet" href="iris.css">

And you ready to go! Enjoy
