# Astro TOC

This projects starts from an Astro template project and defines a new page for showing a simple, unstyled HTML page, built around **remarkToc** plugin.

This plugin allows to build a table of contents (TOC) reading from headings in md files.

A single `.md` file is provided under `content/remark` folder.

The plugin is run by **Vite** against each markdown file which is rendered through the `render()` method. Whenever such files present a header section specifically named "Table of Contents", the plugin inspects all the headings of the page, and modifies the current file adding a table of contents below the heading aforementioned.
