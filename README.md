<p align="center">
  <img src="https://i.imgur.com/dV1aZjJ.png" title="Taikonauten">
</p>

<h1 align="center">Taikonauten .editorconfig</h1>

<p>&nbsp;</p>

This package provides the standardized `.editorconfig` file used at [Taikonauten](https://taikonauten.com).

## Description

The .editorconfig file defines various parameters for the configuration of your code editor or IDE, for example the maximum line length or if new lines should be present at the end of a file.  
You can read more about the .editorconfig file at [editorconfig.org](https://editorconfig.org/).

## Configuration

The following important settings are applied to all files generated or worked with at Taikonauten:

* Spaces are used for indentation. The default indent is 2 spaces.
* .js, .html, .phtml and .php files have a maximum line length of 120 characters.
* Whitespace is not removed from .markdown and .md files.
* All files must have a final newline.

## Installation

Run the following two commands in your terminal to install the package and then create a symlink to the .editorconfig file:

```bash
npm install --save-dev @taikonauten/editorconfig

ln -s node_modules/@taikonauten/editorconfig/.editorconfig .editorconfig
```

After that, make sure your editor or IDE supports the .editorconfig file. PhpStorm and Sublime work with it right out of the box.
For Atom, install the [editorconfig](https://atom.io/packages/editorconfig) plugin.
For VS Code, install the [EditorConfig](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig) plugin.

---

Made with ♡ by Taikonauten
