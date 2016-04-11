Sassy Comments for Sublime Text 
=============================================

This package is forked from https://github.com/chrisborrowdale/Idiomatic-CSS-Comments-Snippets. The reason it was created is because 
I simply did not like the amount of space left under each block that was created, and I knew there had to be a more intuitive way to choose what kind of comment you want to insert.

Eurieka! Why not simply append an extra forward slash to denote what kind of comment you want to use? Since you already hit the key twice to make a basic SASS comment, why not hit it once or twice more to change the type of comment?

## Install

You can install via the Sublime Text Package Control (http://wbond.net/sublime_packages/package_control) and search for Sassy Comments.

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

Enter the shortcut `////.` followed by the `tab` key

``` sass
//
// This is a sub-section comment block
// --------------------------------------------------------------------------
```

### Todo List Comment
Enter the shortcut `sctodo` followed by the `tab` key

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
