# Snippets for Sublime Text 

Tested with Sublime Text 4

trigger: `slug`
Converts filename to a slug that can be used inside a URL. Replace spaces with dashes, convert characters to lowercase and remove file extension

trigger: `meta`
Generates a YAML frontmatter block. Using this for markdown notes for Hugo. Not very effective since date is not available inside snippets. The only variable that is somewhat useful is `{$TM_FILENAME}` which is being used to generate a value for _slug_ and placeholder as a value for _title_
