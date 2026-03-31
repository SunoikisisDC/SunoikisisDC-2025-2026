## v0 (version 0)

File [aen_v0.xml](aen_v0.xml). This is the original version downloaded from the [GitHub repository of the Perseus Digital Library](https://github.com/PerseusDL).

## v1

I trimmed (shortened) the text and kept only the verses I am interested in (the *incipit*); no LOD markup yet.

## v2

I added markup (but without URLs, using "§" as a placeholder) for `person` and `place` in the TEI header.

## v3

I added markup (but without attribute values, using § as a placeholder) for `<persName ref="§">` and `<placeName ref="§">`.

## v4

I filled in the values (replacing the § placeholders) of `<person>` and `<place>` in the TEI header (using LOD URIs).

## v5

I filled in the values (replacing the § placeholders) of `<persName>` and `<placeName>` in the text (using internal links to the `person` and `place` elements).
