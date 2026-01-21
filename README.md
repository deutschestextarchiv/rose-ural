# rose-ural

This repository provides TEI-XML sources for:

* [Gustav Rose: Reise nach dem Ural, dem Altai und dem Kaspischen Meere. Band 1. Berlin, 1837.](https://www.deutschestextarchiv.de/rose_ural01_1837)
* [Gustav Rose: Reise nach dem Ural, dem Altai und dem Kaspischen Meere. Band 2. Berlin, 1842.](https://www.deutschestextarchiv.de/rose_ural02_1842)

<p align="center">
<img width="200" height="333" alt="image" src="https://github.com/user-attachments/assets/25647bf2-dc79-463a-964d-a9ee4df24f12" />
<img width="200" height="335" alt="image" src="https://github.com/user-attachments/assets/29327b83-5f09-4aed-9085-6dee354bb9d3" />
</p>

The original text and annotation were provided to the [German Text Archive](https://www.deutschestextarchiv.de/) by the [OCR-D project](https://ocr-d.de/), with a lot of post-correction already done by several contributors.

There are still a lot of things to do:

* re-place footnotes and set their `@n` values correctly
* fix the `<table>` messes
* check dashes
* check quotation marks
* check notation of fractions ([DTABf documentation](https://deutschestextarchiv.de/doku/basisformat/trSonderzeichen.html))
* provide and check chemical formulas, using `<formula notation="TeX">` (see https://github.com/deutschestextarchiv/dtabf/issues/127)
* ...

## How to contribute

* fork and provide a pull request → [HOWTO](https://docs.github.com/de/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo)
* provide well-formed and [DTABf](https://deutschestextarchiv.de/doku/basisformat/)-compliant XML
* avoid extensive reformatting of the XML, this makes readings diffs very hard
* indentation: 2 spaces (no tabs)
* note: `<lb/>` marks *begin of line*, not *end of line*, this is in contrast to the [DTABf documentation](https://deutschestextarchiv.de/doku/basisformat/lbAllg.html): *Jeder Zeilenschluß wird durch das leere Element `<lb/>` gekennzeichnet.*

## More information

* Gustav Rose (1798–1873) on Wikipedia: [German](https://de.wikipedia.org/wiki/Gustav_Rose), [English](https://en.wikipedia.org/wiki/Gustav_Rose)
* [edition humboldt digital](https://github.com/telota/edition-humboldt-digital): [Die russisch-sibirische Reise (1829)](https://edition-humboldt.de/reisetagebuecher/index.xql?id=H0018398&l=de)

## License

This project is licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).
