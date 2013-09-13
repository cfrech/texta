text<sup>a</sup>
=====

text<sup>a</sup> jQuery Text Annotation Plugin

This plugin makes it easy to select and annotate text.

Requirements
=====

jQuery 1.3.2 or higher

Usage
=====

Basic usage:

<code>$('#highlight-me').texta();</code>

...where <code>$('#highlight-me')</code> is the element or elements you would like to make open to annotation.

Here's an example with several options configured:

<code>$('#highlight-me').texta({
  background: 'red',  
  footnotes: true,  
  comments: true,  
  autoedit: false
});</code>

Options
=====

This version of text<sup>a</sup> supports the following configurations:

* <code>background</code> - Sets the the color of the highlighting. Valid values are <code>'red'</code>, <code>'green'</code>, <code>'yellow'</code>, <code>'yellow2'</code>, <code>'orange'</code>, <code>'blue'</code> or <code>'none'</code>. Defaults to<code>yellow</code>.
* <code>strikeout</code> - Turns a text strikeout effect on or off. Valid values are <code>true</code> or <code>false</code>. Defaults to <code>false</code>.
* <code>footnotes</code> - Makes a set of footnotes available below the element on which the selections are applied. Valid values are <code>true</code> or <code>false</code>. Defaults to <code>false</code>.
* <code>comments</code> - Provides an interface for adding comments to the selections. Valid values are <code>true</code> or <code>false</code>. Defaults to <code>false</code>.
* <code>autoedit</code> - Determines whether, if comments are enabled, the comment box appears automatically when a selection is made or when the user clicks on an existing selection. Valid values are <code>true</code> or <code>false</code>. Defaults to <code>false</code>.

The background and strikeout properties can be changed at any time by calling the appropriate functions:

* <code>$('#highlight-me').texta.background('red');</code>
* <code>$('#highlight-me').texta.strikeout(false);</code>
