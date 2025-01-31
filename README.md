# Snippets for Sublime Text 

Tested with Sublime Text 4

## slug.sublime-snippet
trigger: `slug`

Converts filename to a slug that can be used inside a URL. Replace spaces with dashes, convert characters to lowercase and remove file extension

```
ai-image-generation.md -> ai-image-generation
Online card payments.md -> online-card-payments
some Random FIle NAME with blah.txt -> some-random-file-name-with-blah
```

## yaml-metadata.sublime-snippet
trigger: `meta`

Generates a YAML frontmatter block. Using this for markdown notes for Hugo. Not very effective since date is not available inside snippets. The only variable that is somewhat useful is `{$TM_FILENAME}` which is being used to generate a value for _slug_ and placeholder as a value for _title_

```yaml
---
title: Based On Filename
date: 
uuid: 
slug: based-on-filename
draft: true
description: 
tags:
---
```

Title:
- replace `-` and `_` with a space
- uppercase the first character of the word
- remove file extension

Slug:
- replace spaces with `-`
- lowercase all characters
- remove file extension
