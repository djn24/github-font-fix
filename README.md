# github-font-fix

Chrome extension to replace the monospace font used by GitHub with one which renders extended ASCII diagrams correctly.

Many thanks to the original author, from whose repo this is forked. I've just tweaked it to work with current Chrome. Amazingly
the stylesheet seems pretty much OK as it is despite being ten years old.

**IMPORTANT: The extension by itself doesn't actually solve the problem of extended ASCII diagram rendering, at least on macOS:**

The extension changes the monospace font to "monospace", i.e. use the browser default. I then changed the monospace default in
chrome://settings/fonts to Menlo.
