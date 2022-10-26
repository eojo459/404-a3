Assignment: CSS Hell
====================

You will skin 3 project gutenberg stories with custom CSS.

You will skin 2 versions of a possible professional homepage for your
self with 2 versions of CSS.

Read requirements.org

Read this comic http://theoatmeal.com/comics/design_hell

git clone https://github.com/abramhindle/CMPUT404-assignment-css-hell.git

License/Copyright
=================

Textual content is copyright Abram Hindle (C) 2013 under the CC-BY-SA
4.0 unported license. Attribution should be a hyperlink to the
repository and (C) 2013 Abram Hindle visibile in the text.

Code is licensed under the Apache 2.0 license.

Assignment 3
============

Part 1:
1. https://www.gutenberg.org/cache/epub/394/pg394-images.html
2. https://www.gutenberg.org/cache/epub/345/pg345-images.html
3. https://www.gutenberg.org/cache/epub/1250/pg1250-images.html

HTML modifications
==================

I removed the original css that was placed in the head tags at the beginning and replaced it with a link tag to my css file <link rel="stylesheet" href="styles.css">

In the gutenberg html files I had to change each src="image/.." tag to be src="https://www.gutenberg.org/cache/epub/{id}/image/.." in order to get the images to display.
