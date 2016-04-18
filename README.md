Sassy Comments for Sublime Text 
=============================================

Commenting should be intuitive. When you comment code, you shouldn't have to type out some convoluted trigger. You should be able to use one hand to quickly access the type of comment you want, and apply it instantly.

This is what I envisioned for a Sublime package, and what I set out to create. I hope you enjoy it.

This package is forked from https://github.com/chrisborrowdale/Idiomatic-CSS-Comments-Snippets. I created this package because 1) I didn't want to type out some long string to form a comment, and 2) I didn't like the amount of extra space the package put between where I inserted comments and my code.

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
