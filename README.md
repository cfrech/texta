texta
=====

textA jQuery Text Annotation Pugin

This plugins makes it easy to select and annotate text.

Usage
=====

Basic usage:

$('#highlight-me').texta();

...where $('#highlight-me') is the element or elements you would like to make open to annotation.

Options
=======

This version of textA supports the following configurations:

* background - Sets the the color of the highlighting. Valid values are red, gree, yellow, yellow2, orange, blue or none.
* strikeout - Turns a text strikeout effect on or off. Valid values are true or false.
* footnotes - Makes a set of footnotes available below the element on which the selections are applied. Valid values are true or **false**.
* comments - Provides an interface for adding comments to the selections. Valid values are true or false.
* autoedit - Determines whether, if comments are enabled, the comment box appears automatically when a selection is made or when the user clicks on an existing selection. Valid values are **tru** or **false**.

The background and strikeout properties can be changed at any time by calling the appropriate functions:

$('#highlight-me').texta.background('red');

and

$('#highlight-me').texta.strikeout('false');

...for example.
