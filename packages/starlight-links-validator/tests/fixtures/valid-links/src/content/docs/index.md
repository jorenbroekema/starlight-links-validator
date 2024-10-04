---
title: Index
---

# Some links

- [External link](https://starlight.astro.build/)

- [Home page](/)

- [Test page](/test)
- [Test page](/test/)

- [Test page with hash](/test#title)
- [Test page with hash](/test/#title)

- [Test page with duplicated hash](/test#title-1)

- [An MDX nested page](/guides/example)
- [An MDX nested page](/guides/example/)

# More links

- [Link to hash in this page](#some-links)
- [Link to hash in another MDX page](/guides/example/#some-links)
- [Link to an asset](/favicon.svg)
- [Link to another asset](/guidelines/dummy.pdf)

## A more `complex` heading

- [Link to more complex hash](#a-more-complex-heading)

## Links with references

- [ref]
- [Link reference][ref]
- [Link reference with hash in this page][ref-with-hash-internal]
- [Link reference with hash in another page][ref-with-hash-external]

[ref]: /test
[ref-with-hash-internal]: #some-links
[ref-with-hash-external]: /test#title

## Link to page with custom slug

- [A page with custom slug](/release/@pkg/v0.1.0)

## Query strings

- [Home page with query string](/?query=string)

- [Test page with query string](/test?query=string)
- [Test page with query string](/test/?query=string)

- [Test page with query string and hash](/test?query=string#title)
- [Test page with query string and hash](/test/?query=string#title)

- [Link to hash in this page with query string](?query=string#some-links)

- [Link to an asset with query string](/favicon.svg?query=string)
- [Link to another asset with query string](/guidelines/dummy.pdf?query=string)

- [ref-with-query-string]
- [Link reference with query string][ref-with-query-string]
- [Link reference with query string and hash in this page][ref-with-query-string-and-hash-internal]
- [Link reference with query string and hash in another page][ref-with-query-string-and-hash-external]

[ref-with-query-string]: /test?query=string
[ref-with-query-string-and-hash-internal]: ?query=string#some-links
[ref-with-query-string-and-hash-external]: /test?query=string#title