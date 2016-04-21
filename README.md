Sassy Comments for Sublime Text 
=============================================

Commenting should be intuitive. When you comment code, you shouldn't have to type out some convoluted trigger. You should be able to use one hand to quickly access the type of comment you want, and apply it instantly.

This is what I envisioned for a Sublime package, and what I set out to create. I hope you enjoy it.

Although Sass was the reason for this package, technically these comments will work for any language that supports single line comments with `//`. (Hint: There's a lot of them.)

This package is forked from https://github.com/chrisborrowdale/Idiomatic-CSS-Comments-Snippets.

## Install

You can install via the Sublime Text Package Control (http://wbond.net/sublime_packages/package_control) and search for "Sassy Comments".

## Usage

There are several shortcuts for the different comment blocks.

### Section Comment

Enter the shortcut `////` followed by the `tab` key

``` sass
// ==========================================================================
// This is a section comment block
// ==========================================================================
```

### Sub-Section Comment

Enter the shortcut `///.` followed by the `tab` key

``` sass
//
// This is a sub-section comment block
// --------------------------------------------------------------------------
```

### Todo List Comment
Enter the shortcut `//,` followed by the `tab` key

``` sass
//
// TODO
//
// => This is a TODO comment block
```

### Long Comment

Enter the shortcut `///` followed by the `tab` key

``` sass
//
// This is a longer comment block
//
```

### Basic Comment
Since, by default, it only takes 2 keystrokes to form a basic comment, it was not necessary to have a snippet for this.
