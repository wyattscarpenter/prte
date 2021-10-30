# prte
Poor Richard's Text Editor: a design document for a rich plain text editor

This document is a vague reminder to myself to investigate the concept of a rich plain text editor. What does that mean? Well, a text editor that has most of the features of a rich text format. How?

1. Smart detection of text structures. For instance, the text editor would detect that this is the first item in a list and automatically create the second item when you hit enter at the end of this line.
2. Unicode cheating: using the italic, bold, strikethrough, superscript, etc Unicode characters to approximate rich text italics, etc.

The most efficient way for me to implement this would probably be as a plug-in to existing text editor. However, it would need to support full unicode. The least machine-resource efficient (and funniest) way for me to do this, and also probably the most convenient way, would be a web app that works in the web browser (but only lets you edit a plain text entry field).
