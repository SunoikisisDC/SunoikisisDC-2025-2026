## v1 (version 1)

This version includes `<place>` and `<person>` lements in the TEI header, as well as `<placeName ref="§">` and `<persName ref="§">` markup for the names of those places and persons in Vergil's text, but the markup is incomplete: attribute values are missing and the "§" sign is used as a placeholder.

## v2

In this version the "§" placeholders have been replaced with the relevant LOD URIs for elements `<person>` and `<place>` (and their children elements):

## v3

In this version the "§" placeholders have been replaced with the relevant LOD URIs for elements `<persName>` and `<placeName>` in the text (using internal links to the `xml:id` of `person` and `place` elementsin the TEI Header).
