Sassy Comments for Sublime Text 
=============================================

This package is forked from https://github.com/chrisborrowdale/Idiomatic-CSS-Comments-Snippets. The reason it was created is because 
I simply did not like the amount of space left under each block that was created.

## Install

You can install via the Sublime Text Package Control (http://wbond.net/sublime_packages/package_control) and search for Sassy Comments.

## Usage

There are several shortcuts for the different comment blocks.

### Basic Comment
Enter the shortcut `sc` followed by the `tab` key

``` sass
// This is a basic comment
```

### Section Comment

Enter the shortcut `scsec` followed by the `tab` key

``` sass
/* ==========================================================================
   This is a Section Comment
   ========================================================================== */
```

### Sub-Section Comment

Enter the shortcut `scsub` followed by the `tab` key

``` sass
/*
   This is a sub-section comment
   ========================================================================== */
```

### Long Comment

Enter the shortcut `sclong` followed by the `tab` key

``` sass
/**
 * Short description using Doxygen-style comment format
 *
 * The first sentence of the long description starts here and continues on this
 * line for a while finally concluding here at the end of this paragraph.
 *
 * The long description is ideal for more detailed explanations and
 * documentation. It can include example HTML, URLs, or any other information
 * that is deemed necessary or useful.
 *
 * @tag This is a tag named 'tag'
 *
 * TODO: This is a todo statement that describes an atomic task to be completed
 *   at a later date. It wraps after 80 characters and following lines are
 *   indented by 2 spaces.
 */
```

### Todo List Comment
Enter the shortcut `sctodo` followed by the `tab` key

``` sass
/**
 * TODO:
 *
 * => Write some code
 * => Make some lists
 *
 */
```
