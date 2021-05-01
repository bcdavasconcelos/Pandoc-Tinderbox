# Pandoc-Tinderbox
Integration between Tinderbox and Pandoc.

The goal of this template is simply to provide a way to use Pandoc in Tinderbox. In it, Pandoc is relevant for two different tasks:

- Preview the Markdown text making use of Pandoc's Citeproc
- Export the text of the selected notes to files — to a single or to multiple files —  in different formats (`md`, `epub`, `pdf`, `latex`, `opml`, `wikicode`, `pptx`, etc.)

In order to do this, two things are needed: the `TbxConfig` note and an `export stamp`.

## With the stamp you can...

- Export each one of the selected notes with or without their children (as part of each file or as part of multiple individual files).

## From the `TbxConfig` note you can...

- Update the preview command in case you decide to make changes to the configuration (click on the checkbox; it will quickly go back to being unchecked and the `$HTMLPreviewCommand` will have been updated).
- Choose your export folder.
- Point to your bibliography file\*.
- Choose your bibliography style.
- Choose the Pandoc's conversion templates.
- Choose the converted file's extension.
- Activate/deactivate conversion options (e.g. table of contents, citations as links to corresponding bibliographical reference).
- Choose the fonts for the preview and Export (only for pdf conversion).
- Choose from different CSS styles available and that will be automatically used in Preview.
- Include children, if the note has any, when exporting the selected notes.
- Choose to export the *children* of the *selected notes* as individual files 

**This template assumes that all of the writing will be done using Markdown. In case you want to use something different, you my need to make a few adjustments.**

Latest version will always be here in Github repository.

* If you never used Pandocs bibliography feature, consider giving it a try. It is both useful and easy to use. Especially if you are using [Bibdesk](https://bibdesk.sourceforge.io).

## Dependencies

- [Pandoc](https://pandoc.org)
- [MacTex](http://www.tug.org/mactex/)
