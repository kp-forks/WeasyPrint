Changelog
=========


Version 66.0
------------

Released on 2025-07-24.

Features:

* `#2475 <https://github.com/Kozea/WeasyPrint/pull/2475>`_:
  Add support for 'lh' and 'rlh' units
* `#2432 <https://github.com/Kozea/WeasyPrint/issues/2432>`_,
  `#2437 <https://github.com/Kozea/WeasyPrint/pull/2437>`_:
  Report footnotes when text overflows because of orphans, with financial support from Code & Co.
* `#2256 <https://github.com/Kozea/WeasyPrint/issues/2256>`_,
  `#2466 <https://github.com/Kozea/WeasyPrint/pull/2466>`_:
  Handle transform-origin in SVG
* `#2445 <https://github.com/Kozea/WeasyPrint/pull/2445>`_:
  Add parameter to have additional HTTP headers for url_fetcher

Bug fixes:

* `#2471 <https://github.com/Kozea/WeasyPrint/pull/2471>`_,
  `#2506 <https://github.com/Kozea/WeasyPrint/pull/2506>`_,
  `#2500 <https://github.com/Kozea/WeasyPrint/issues/2500>`_,
  `#2460 <https://github.com/Kozea/WeasyPrint/issues/2460>`_,
  `#2363 <https://github.com/Kozea/WeasyPrint/issues/2363>`_,
  `#2470 <https://github.com/Kozea/WeasyPrint/issues/2470>`_,
  `#1872 <https://github.com/Kozea/WeasyPrint/issues/1872>`_,
  `#2153 <https://github.com/Kozea/WeasyPrint/issues/2153>`_,
  `#1838 <https://github.com/Kozea/WeasyPrint/issues/1838>`_,
  `#1837 <https://github.com/Kozea/WeasyPrint/issues/1837>`_,
  `#1784 <https://github.com/Kozea/WeasyPrint/issues/1784>`_,
  `#1835 <https://github.com/Kozea/WeasyPrint/issues/1835>`_,
  `#2444 <https://github.com/Kozea/WeasyPrint/issues/2444>`_,
  `#2497 <https://github.com/Kozea/WeasyPrint/issues/2497>`_,
  `#2505 <https://github.com/Kozea/WeasyPrint/issues/2505>`_,
  `#2503 <https://github.com/Kozea/WeasyPrint/issues/2503>`_,
  `#1836 <https://github.com/Kozea/WeasyPrint/issues/1836>`_,
  `#2467 <https://github.com/Kozea/WeasyPrint/issues/2467>`_:
  Improve PDF/UA support, with financial support from NLnet
* `#2425 <https://github.com/Kozea/WeasyPrint/pull/2425>`_,
  `#1557 <https://github.com/Kozea/WeasyPrint/issues/1557>`_:
  Improve position of outside markers
* `#2409 <https://github.com/Kozea/WeasyPrint/pull/2409>`_,
  `#2265 <https://github.com/Kozea/WeasyPrint/issues/2265>`_:
  Draw circles instead of rectangles when drawing dotted borders
* `#2416 <https://github.com/Kozea/WeasyPrint/pull/2416>`_,
  `#2270 <https://github.com/Kozea/WeasyPrint/issues/2270>`_:
  Correctly split words for automatic hyphenation
* `#2439 <https://github.com/Kozea/WeasyPrint/pull/2439>`_,
  `#2426 <https://github.com/Kozea/WeasyPrint/issues/2426>`_:
  Don’t rely on URL protocols outside URL fetcher function
* `#2433 <https://github.com/Kozea/WeasyPrint/pull/2433>`_:
  Disable style for deprecated outline algorithm
* `#2447 <https://github.com/Kozea/WeasyPrint/pull/2447>`_,
  `#2441 <https://github.com/Kozea/WeasyPrint/issues/2441>`_,
  `#2448 <https://github.com/Kozea/WeasyPrint/issues/2448>`_:
  Improve min- and max-content calculation, with financial support from Menutech
* `#2454 <https://github.com/Kozea/WeasyPrint/pull/2454>`_,
  `#2442 <https://github.com/Kozea/WeasyPrint/issues/2442>`_,
  `#2449 <https://github.com/Kozea/WeasyPrint/issues/2449>`_:
  Minor fixes for flex layout
* `#2473 <https://github.com/Kozea/WeasyPrint/pull/2473>`_,
  `#2459 <https://github.com/Kozea/WeasyPrint/issues/2459>`_:
  Include out-of-flow boxes in page layout progress, with financial support from Pathfindr
* `#2458 <https://github.com/Kozea/WeasyPrint/pull/2458>`_:
  Replace deprecated warn logger function
* `#2494 <https://github.com/Kozea/WeasyPrint/pull/2494>`_,
  `#1856 <https://github.com/Kozea/WeasyPrint/issues/1856>`_:
  Fix bug with bottom margins in columns
* `#2435 <https://github.com/Kozea/WeasyPrint/issues/2435>`_:
  Make footnote calls inherit from footnotes
* `#2484 <https://github.com/Kozea/WeasyPrint/issues/2484>`_,
  `#2456 <https://github.com/Kozea/WeasyPrint/issues/2456>`_:
  Allow to avoid page breaks after table-row-group elements
* `#2450 <https://github.com/Kozea/WeasyPrint/issues/2450>`_:
  Draw background and borders for relative grid containers
* `#2453 <https://github.com/Kozea/WeasyPrint/issues/2453>`_:
  Don’t advance position_y for collapsed margins of discarded children
* `#2493 <https://github.com/Kozea/WeasyPrint/issues/2493>`_:
  Fix endless loop with CSS variables referencing each other
* `#2502 <https://github.com/Kozea/WeasyPrint/issues/2502>`_:
  Ignore bottom margin when calculating footnote overflow

Contributors:

* Guillaume Ayoub
* Lucie Anglade
* Alvaro Garcia Fernandez
* Emmanuel Ferdman
* Gabriel Corona
* Markus Mohanty
* Luca Vercelli
* Tre Huang

Backers and sponsors:

* Spacinov
* Kobalt
* Grip Angebotssoftware
* Syslifters
* Simon Sapin
* Manuel Barkhau
* Simonsoft
* Menutech
* KontextWork
* TrainingSparkle
* Healthchecks.io
* Hammerbacher
* DocRaptor
* Yanal-Yves Fargialla
* Method B
* FieldHub
* Morntag
* Xavid
* Kai DeLorenzo
* Charlie S.
* Alan Villalobos


Version 65.1
------------

Released on 2025-04-14.

Bug fixes:

* `#2414 <https://github.com/Kozea/WeasyPrint/issues/2414>`_:
  Correctly handle flex columns split between pages
* `1b24ad9 <https://github.com/Kozea/WeasyPrint/commit/1b24ad9>`_:
  Include padding in outer size of item elements
* `#2419 <https://github.com/Kozea/WeasyPrint/issues/2419>`_:
  Set main tag as block by default
* `#2415 <https://github.com/Kozea/WeasyPrint/issues/2415>`_:
  Fix support of replaced block box as flex items
* `83da2fe0 <https://github.com/Kozea/WeasyPrint/commit/83da2fe0>`_:
  Fix margins and padding for rtl lists
* `#2429 <https://github.com/Kozea/WeasyPrint/issues/2429>`_,
  `#1076 <https://github.com/Kozea/WeasyPrint/issues/1076>`_,
  `#2431 <https://github.com/Kozea/WeasyPrint/pull/2431>`_:
  Fix page groups

Contributors:

* Guillaume Ayoub

Backers and sponsors:

* Spacinov
* Kobalt
* Grip Angebotssoftware
* Syslifters
* Simon Sapin
* Manuel Barkhau
* Simonsoft
* Menutech
* KontextWork
* TrainingSparkle
* Healthchecks.io
* Hammerbacher
* DocRaptor
* Yanal-Yves Fargialla
* Method B
* FieldHub
* Morntag
* Xavid
* Kai DeLorenzo
* Charlie S.
* Alan Villalobos


Version 65.0
------------

Released on 2025-03-20.

Dependencies:

* CSSSelect2 0.8.0 is now needed

Features:

* `#1665 <https://github.com/Kozea/WeasyPrint/issues/1665>`_:
  Support gap properties in Flex layout, with financial support from NLnet
* `#378 <https://github.com/Kozea/WeasyPrint/issues/378>`_,
  `#2405 <https://github.com/Kozea/WeasyPrint/pull/2405>`_:
  Handle @font-face unicode-range
* `#2394 <https://github.com/Kozea/WeasyPrint/pull/2394>`_:
  Modernize and improve default user agent stylesheets

Bug fixes:

* `#2362 <https://github.com/Kozea/WeasyPrint/issues/2362>`_,
  `#2387 <https://github.com/Kozea/WeasyPrint/pull/2387>`_,
  `#601 <https://github.com/Kozea/WeasyPrint/issues/601>`_,
  `#1967 <https://github.com/Kozea/WeasyPrint/issues/1967>`_,
  `#1805 <https://github.com/Kozea/WeasyPrint/issues/1805>`_,
  `#2163 <https://github.com/Kozea/WeasyPrint/issues/2163>`_,
  `#2342 <https://github.com/Kozea/WeasyPrint/issues/2342>`_,
  `#2374 <https://github.com/Kozea/WeasyPrint/issues/2374>`_,
  `#1109 <https://github.com/Kozea/WeasyPrint/issues/1109>`_,
  `#1356 <https://github.com/Kozea/WeasyPrint/issues/1356>`_,
  `#1327 <https://github.com/Kozea/WeasyPrint/issues/1327>`_,
  `#1563 <https://github.com/Kozea/WeasyPrint/issues/1563>`_,
  `#1652 <https://github.com/Kozea/WeasyPrint/issues/1652>`_,
  `#2351 <https://github.com/Kozea/WeasyPrint/issues/2351>`_,
  `#2312 <https://github.com/Kozea/WeasyPrint/issues/2312>`_,
  `#2340 <https://github.com/Kozea/WeasyPrint/issues/2340>`_,
  `#1311 <https://github.com/Kozea/WeasyPrint/issues/1311>`_,
  `#2066 <https://github.com/Kozea/WeasyPrint/issues/2066>`_,
  `#2359 <https://github.com/Kozea/WeasyPrint/issues/2359>`_,
  `#2053 <https://github.com/Kozea/WeasyPrint/issues/2053>`_:
  Improve Flex layout, with financial support from NLnet.
* `#1686 <https://github.com/Kozea/WeasyPrint/issues/1686>`_,
  `#2404 <https://github.com/Kozea/WeasyPrint/pull/2404>`_:
  Fix duplicate text selection with right-to-left text
* `#2372 <https://github.com/Kozea/WeasyPrint/issues/2372>`_,
  `#2389 <https://github.com/Kozea/WeasyPrint/pull/2389>`_:
  Fix justification of right-to-left text
* `#2403 <https://github.com/Kozea/WeasyPrint/issues/2403>`_:
  Fix emoji rendering with older versions of Pango
* `#2392 <https://github.com/Kozea/WeasyPrint/issues/2392>`_:
  Fix complex cases involving nested SVG text anchors
* `#2396 <https://github.com/Kozea/WeasyPrint/issues/2396>`_,
  `#2398 <https://github.com/Kozea/WeasyPrint/pull/2398>`_:
  Fix and improve font names in PDF
* `#2269 <https://github.com/Kozea/WeasyPrint/issues/2269>`_,
  `#2390 <https://github.com/Kozea/WeasyPrint/pull/2390>`_:
  Apply justification to non-breaking spaces
* `#2362 <https://github.com/Kozea/WeasyPrint/issues/2362>`_,
  `#2387 <https://github.com/Kozea/WeasyPrint/pull/2387>`_:
  Improve Flex layout, with financial support from NLnet.

Contributors:

* Guillaume Ayoub
* Luca Vercelli

Backers and sponsors:

* Spacinov
* Kobalt
* Grip Angebotssoftware
* Syslifters
* Simon Sapin
* Manuel Barkhau
* Simonsoft
* Menutech
* KontextWork
* TrainingSparkle
* Healthchecks.io
* Hammerbacher
* DocRaptor
* Yanal-Yves Fargialla
* Method B
* FieldHub
* Morntag
* Xavid
* Kai DeLorenzo
* Charlie S.
* Alan Villalobos


Version 64.1
------------

Released on 2025-02-20.

Bug fixes:

* `#2368 <https://github.com/Kozea/WeasyPrint/issues/2368>`_:
  Fix ascent and descent font values
* `#2370 <https://github.com/Kozea/WeasyPrint/issues/2370>`_:
  Avoid endless recursion for variables in nested functions
* `#2275 <https://github.com/Kozea/WeasyPrint/issues/2275>`_:
  Use correct containing block to render waiting children
* `#2375 <https://github.com/Kozea/WeasyPrint/issues/2375>`_:
  Ensure that we handle text-anchor only on text content elements
* `#2090 <https://github.com/Kozea/WeasyPrint/issues/2090>`_:
  Only create font temporary folder when adding fonts
* `#2383 <https://github.com/Kozea/WeasyPrint/issues/2383>`_:
  Fix grid-template-areas validation and allow uppercase identifiers for grid lines

Contributors:

* Guillaume Ayoub

Backers and sponsors:

* Spacinov
* Kobalt
* Grip Angebotssoftware
* Syslifters
* Simon Sapin
* Manuel Barkhau
* Simonsoft
* Menutech
* KontextWork
* TrainingSparkle
* Healthchecks.io
* Hammerbacher
* DocRaptor
* Yanal-Yves Fargialla
* Method B
* FieldHub
* Morntag
* Xavid
* Kai DeLorenzo
* Charlie S.


Version 64.0
------------

Released on 2025-01-30.

Features:

* `#2338 <https://github.com/Kozea/WeasyPrint/pull/2338>`_:
  Allow custom RDF metadata for PDF/A and eInvoices
* `#123 <https://github.com/Kozea/WeasyPrint/issues/123>`_,
  `#2345 <https://github.com/Kozea/WeasyPrint/pull/2345>`_:
  Handle small-caps synthesis
* `#2343 <https://github.com/Kozea/WeasyPrint/issues/2343>`_:
  Support outline-offset
* `#2361 <https://github.com/Kozea/WeasyPrint/pull/2361>`_:
  Support text-underline-offset and text-decoration-thickness
* `#2296 <https://github.com/Kozea/WeasyPrint/issues/2296>`_:
  Don’t crash with tables with rounded corners split between pages

Bug fixes:

* `#2360 <https://github.com/Kozea/WeasyPrint/issues/2360>`_:
  Fix gradients with non-RGB colors
* `#2355 <https://github.com/Kozea/WeasyPrint/issues/2355>`_,
  `#2358 <https://github.com/Kozea/WeasyPrint/pull/2358>`_:
  Align png emojis to the surrounding text
* `#2353 <https://github.com/Kozea/WeasyPrint/issues/2353>`_:
  Fix alignment of SVG text with multiple nested text-anchor values
* `#2350 <https://github.com/Kozea/WeasyPrint/pull/2350>`_:
  Fix logging restoration in capture_logs
* `#2341 <https://github.com/Kozea/WeasyPrint/pull/2341>`_:
  Fix page groups
* `#2314 <https://github.com/Kozea/WeasyPrint/pulls/2314>`_:
  Use CSS 'image-rendering' attribute for images in SVGs
* `#2332 <https://github.com/Kozea/WeasyPrint/issues/2332>`_:
  Fix opacity for translated SVG elements
* `#2329 <https://github.com/Kozea/WeasyPrint/issues/2329>`_:
  Refactor text.line_break.get_log_attrs
* `#2325 <https://github.com/Kozea/WeasyPrint/issues/2325>`_,
  `#2326 <https://github.com/Kozea/WeasyPrint/pull/2326>`_:
  Fix table overflow edge cases

Performance:

* `#2347 <https://github.com/Kozea/WeasyPrint/issues/2347>`_,
  `#2364 <https://github.com/Kozea/WeasyPrint/pull/2364>`_:
  Improve rendering speed for text

Documentation:

* `#2352 <https://github.com/Kozea/WeasyPrint/pull/2352>`_:
  Add more use cases in documentation, use Furo theme

Contributors:

* Guillaume Ayoub
* Kesara Rathnayake
* Xavid Pretzer
* David Tagatac
* Ernesto Ruge
* Niko Abeler
* Noam Kushinsky

Backers and sponsors:

* Spacinov
* Kobalt
* Grip Angebotssoftware
* Syslifters
* Simon Sapin
* Manuel Barkhau
* Simonsoft
* Menutech
* KontextWork
* TrainingSparkle
* Healthchecks.io
* Hammerbacher
* DocRaptor
* Yanal-Yves Fargialla
* Method B
* FieldHub
* Morntag
* Xavid
* Kai DeLorenzo
* Charlie S.


Version 63.1
------------

Released on 2024-12-10.

Dependencies:

* `#2297 <https://github.com/Kozea/WeasyPrint/issues/2297>`_:
  Remove upper bounds for dependencies

Bug fixes:

* `#2300 <https://github.com/Kozea/WeasyPrint/pull/2300>`_,
  `#2292 <https://github.com/Kozea/WeasyPrint/issues/2292>`_:
  Don’t avoid floats for flex items
* `#2301 <https://github.com/Kozea/WeasyPrint/pull/2301>`_,
  `#2293 <https://github.com/Kozea/WeasyPrint/issues/2293>`_:
  Include floats in calculation of minimum cell height
* `#2303 <https://github.com/Kozea/WeasyPrint/pull/2303>`_,
  `#2302 <https://github.com/Kozea/WeasyPrint/issues/2302>`_:
  Set alpha even when current color channels didn’t change
* `#2306 <https://github.com/Kozea/WeasyPrint/issues/2306>`_:
  Don’t try to increase column width when there’s no extra width
* `#2304 <https://github.com/Kozea/WeasyPrint/issues/2304>`_:
  Don’t forget skip stack when drawing flex items
* `#2316 <https://github.com/Kozea/WeasyPrint/issues/2316>`_:
  Don’t crash with SVG symbols
* `#2320 <https://github.com/Kozea/WeasyPrint/issues/2320>`_:
  Fix currentcolor detection when parsing gradient color stops
* `#2322 <https://github.com/Kozea/WeasyPrint/pull/2322>`_,
  `#2289 <https://github.com/Kozea/WeasyPrint/issues/2289>`_:
  Don’t add DLL directories when using Windows executable
* `#2323 <https://github.com/Kozea/WeasyPrint/pull/2323>`_,
  `#2305 <https://github.com/Kozea/WeasyPrint/issues/2305>`_:
  Fix different rendering test

Performance:

* `#2319 <https://github.com/Kozea/WeasyPrint/issues/2319>`_:
  Fix memory leaks

Documentation:

* `#2299 <https://github.com/Kozea/WeasyPrint/pull/2299>`_:
  Update install instructions for Alpine
* `#2321 <https://github.com/Kozea/WeasyPrint/pull/2321>`_:
  Add example invocation of WeasyPrint on the "Contribute" page

Contributors:

* Guillaume Ayoub
* Jó Ágila Bitsch
* Lucie Anglade
* Alexander Gitter
* Luke Cousins

Backers and sponsors:

* Spacinov
* Kobalt
* Grip Angebotssoftware
* Syslifters
* Manuel Barkhau
* SimonSoft
* Menutech
* KontextWork
* Simon Sapin
* TrainingSparkle
* Healthchecks.io
* Hammerbacher
* Advance Insight
* Docraptor
* Method B
* FieldHub
* Yanal-Yves Fargialla
* Morntag
* Xavid


Version 63.0
------------

Released on 2024-10-29.

Dependencies:

* Python 3.13 is now supported
* pydyf 0.11.0+ is now needed
* tinycss2 1.4.0+ is now needed
* tinyhtml5 2.0.0+ is now needed, instead of html5lib

Features:

* `#2252 <https://github.com/Kozea/WeasyPrint/pull/2252>`_,
  `#895 <https://github.com/Kozea/WeasyPrint/issues/895>`_:
  Handle page groups, with financial support from Code & Co.
* `#1630 <https://github.com/Kozea/WeasyPrint/issues/1630>`_,
  `#2286 <https://github.com/Kozea/WeasyPrint/pull/2286>`_:
  Support CSS Color Level 4
* `#2192 <https://github.com/Kozea/WeasyPrint/pull/2192>`_:
  Add PDF variant for debugging purpose
* `#2208 <https://github.com/Kozea/WeasyPrint/pull/2208>`_:
  Support submit inputs in PDF forms
* `#2139 <https://github.com/Kozea/WeasyPrint/pull/2139>`_:
  Support ``mask-border-*`` properties
* `#1831 <https://github.com/Kozea/WeasyPrint/issues/1831>`_,
  `#2143 <https://github.com/Kozea/WeasyPrint/pull/2143>`_:
  Support radio inputs in PDF forms

Bug fixes:

* `#2262 <https://github.com/Kozea/WeasyPrint/issues/2262>`_:
  Avoid integer overflows when converting units from/to doubles
* `#2260 <https://github.com/Kozea/WeasyPrint/pull/2260>`_:
  Avoid float collision with box establishing formatting context
* `#2240 <https://github.com/Kozea/WeasyPrint/issues/2240>`_,
  `#2242 <https://github.com/Kozea/WeasyPrint/pull/2242>`_:
  Handle ``svg`` tags with no size
* `#2231 <https://github.com/Kozea/WeasyPrint/pull/2231>`_,
  `#1171 <https://github.com/Kozea/WeasyPrint/issues/1171>`_,
  `#2222 <https://github.com/Kozea/WeasyPrint/issues/2222>`_,
  `#1208 <https://github.com/Kozea/WeasyPrint/issues/1208>`_:
  Fix several problems related to ``flex-direction: column``
* `#2239 <https://github.com/Kozea/WeasyPrint/issues/2239>`_:
  Don’t fail when SVG markers are undefined references
* `#2230 <https://github.com/Kozea/WeasyPrint/issues/2230>`_,
  `#2238 <https://github.com/Kozea/WeasyPrint/pull/2238>`_:
  Set explicit flags when loading DLLs on Windows
* `#2228 <https://github.com/Kozea/WeasyPrint/issues/2228>`_,
  `#1942 <https://github.com/Kozea/WeasyPrint/issues/1942>`_:
  Store original and PDF stream images in different cache slots
* `#2234 <https://github.com/Kozea/WeasyPrint/issues/2234>`_:
  Apply stylesheet and other basic operations to SVG root tag
* `#2054 <https://github.com/Kozea/WeasyPrint/issues/2054>`_,
  `#2233 <https://github.com/Kozea/WeasyPrint/pull/2233>`_:
  Keep auto margins on flex layout boxes
* `#1883 <https://github.com/Kozea/WeasyPrint/issues/1883>`_:
  Don’t crash with empty list marker strings
* `#2216 <https://github.com/Kozea/WeasyPrint/issues/2216>`_:
  Fix vertical alignment of out-of-flow elements in tables
* `#996 <https://github.com/Kozea/WeasyPrint/issues/996>`_,
  `#2219 <https://github.com/Kozea/WeasyPrint/pull/2219>`_:
  Don’t ignore absolutely positioned elements inside flex boxes
* `#2217 <https://github.com/Kozea/WeasyPrint/issues/2217>`_:
  Don’t crash with ``normal`` column gaps
* `#1817 <https://github.com/Kozea/WeasyPrint/issues/1817>`_:
  Don’t assume that lines break after spaces
* `#1868 <https://github.com/Kozea/WeasyPrint/issues/1868>`_:
  Don’t break rows with atomic cells
* `#2166 <https://github.com/Kozea/WeasyPrint/issues/2166>`_:
  Don’t display bottom border on cells in split rows
* `61852c4 <https://github.com/Kozea/WeasyPrint/commit/61852c4>`_:
  Capture fontTools logs when subsetting fonts
* `#2190 <https://github.com/Kozea/WeasyPrint/pull/2190>`_:
  Don’t use a pattern when drawing backgrounds for no-repeat background images
* `#2185 <https://github.com/Kozea/WeasyPrint/issues/2185>`_:
  Check that Harfbuzz version is at least 4.1.0 to subset fonts
* `#2180 <https://github.com/Kozea/WeasyPrint/issues/2180>`_:
  Store width for all glyphs when font is not subset
* `#2183 <https://github.com/Kozea/WeasyPrint/issues/2183>`_:
  Respect ``break-inside: avoid`` for flex items
* `#2055 <https://github.com/Kozea/WeasyPrint/issues/2055>`_,
  `#2058 <https://github.com/Kozea/WeasyPrint/pull/2058>`_:
  Fix right-to-left tables with collapsed borders
* `#2179 <https://github.com/Kozea/WeasyPrint/pull/2179>`_,
  `#1128 <https://github.com/Kozea/WeasyPrint/issues/1128>`_:
  Handle buggy Adobe Photoshop CMYK JPEGs
* `#2175 <https://github.com/Kozea/WeasyPrint/issues/2175>`_:
  Don’t compress PDF metadata for PDF/A-1
* `#2174 <https://github.com/Kozea/WeasyPrint/issues/2174>`_:
  Fix extra width distribution for auto table layout

Performance:

* `#1155 <https://github.com/Kozea/WeasyPrint/issues/1155>`_:
  Improve rendering speed for large colspan values
* `#2120 <https://github.com/Kozea/WeasyPrint/issues/2120>`_,
  `#2178 <https://github.com/Kozea/WeasyPrint/pull/2178>`_:
  Use Harfbuzz to subset fonts by default

Documentation:

* `#2282 <https://github.com/Kozea/WeasyPrint/issues/2282>`_,
  `#2284 <https://github.com/Kozea/WeasyPrint/pull/2284>`_:
  Simplify Alpine install instructions
* `#2254 <https://github.com/Kozea/WeasyPrint/issues/2254>`_:
  Add warning about antivirus false detection
* `#2220 <https://github.com/Kozea/WeasyPrint/pull/2220>`_:
  Add extra information to debug logs
* `#2211 <https://github.com/Kozea/WeasyPrint/pull/2211>`_:
  Fix link to samples
* `#2195 <https://github.com/Kozea/WeasyPrint/pull/2195>`_:
  Update cache argument documentation
* `#2105 <https://github.com/Kozea/WeasyPrint/issues/2105>`_,
  `#2151 <https://github.com/Kozea/WeasyPrint/pull/2151>`_:
  Use MSYS2 instead of GTK+3 for Windows

Contributors:

* Guillaume Ayoub
* David Huggins-Daines
* Xavid Pretzer
* Yann Trividic
* Kevin Kays
* Alejandro Avilés
* Gianluca Teti
* Gregory Goodson
* Lucie Anglade
* Roman Sirokov

Backers and sponsors:

* Spacinov
* Kobalt
* Grip Angebotssoftware
* Syslifters
* Manuel Barkhau
* SimonSoft
* Menutech
* KontextWork
* Simon Sapin
* TrainingSparkle
* Healthchecks.io
* Hammerbacher
* Advance Insight
* Docraptor
* Method B
* FieldHub
* Yanal-Yves Fargialla
* Morntag
* Xavid


Version 62.3
------------

Released on 2024-06-21.

Bug fixes:

* `#2174 <https://github.com/Kozea/WeasyPrint/issues/2174>`_:
  Fix extra width distribution for auto table layout
* `#2175 <https://github.com/Kozea/WeasyPrint/issues/2175>`_:
  Don’t compress PDF metadata for PDF/A-1
* `61f8bb3 <https://github.com/Kozea/WeasyPrint/commit/61f8bb3>`_:
  Set default PDF variant values in options before generating PDF
* `2c4351e <https://github.com/Kozea/WeasyPrint/commit/2c4351e>`_:
  Avoid PDF artifacts when drawing 0-width borders
* `d9d7f62 <https://github.com/Kozea/WeasyPrint/commit/d9d7f62>`_:
  Don’t duplicate column when container is split on multiple pages
* `4617b94 <https://github.com/Kozea/WeasyPrint/commit/4617b94>`_:
  Don’t set default Fontconfig values for unset properties
* `4c81663 <https://github.com/Kozea/WeasyPrint/commit/4c81663>`_:
  Fix layout when all footnotes are removed from the footnote area
* `#2184 <https://github.com/Kozea/WeasyPrint/issues/2184>`_:
  Make items overflowing grid wrap to the next row/column
* `#2187 <https://github.com/Kozea/WeasyPrint/issues/2187>`_:
  Don’t append useless tracks when grid elements are positioned

Contributors:

* Guillaume Ayoub

Backers and sponsors:

* Spacinov
* Kobalt
* Grip Angebotssoftware
* Manuel Barkhau
* SimonSoft
* Menutech
* KontextWork
* Simon Sapin
* René Fritz
* TrainingSparkle
* Healthchecks.io
* Hammerbacher
* Docraptor
* Yanal-Yves Fargialla
* Douwe van Loenen
* Morntag
* Xavid


Version 62.2
------------

Released on 2024-06-04.

Features:

* `#2142 <https://github.com/Kozea/WeasyPrint/issues/2142>`_,
  `#2162 <https://github.com/Kozea/WeasyPrint/pull/2162>`_:
  Support grid-auto-flow: column, with financial support from Menutech

Bug fixes:

* `#2167 <https://github.com/Kozea/WeasyPrint/issues/2167>`_:
  Fix space added by CSS gap at the end
* `#2134 <https://github.com/Kozea/WeasyPrint/issues/2134>`_:
  Remove absolute placeholders from discarded content
* `#2154 <https://github.com/Kozea/WeasyPrint/issues/2154>`_:
  Don’t crash when grid items have auto margins
* `8cdd66f <https://github.com/Kozea/WeasyPrint/commit/8cdd66f>`_:
  Fix CSS nesting for nested selectors with comma
* `3359db5 <https://github.com/Kozea/WeasyPrint/commit/3359db5>`_:
  Fix and test grid shorthand
* `82deda4 <https://github.com/Kozea/WeasyPrint/commit/82deda4>`_:
  Fix wrong resume_at for split floats
* `ff2acf1 <https://github.com/Kozea/WeasyPrint/commit/ff2acf1>`_:
  Ensure that gradient size is positive to please some PDF readers

Contributors:

* Guillaume Ayoub

Backers and sponsors:

* Spacinov
* Kobalt
* Grip Angebotssoftware
* Manuel Barkhau
* SimonSoft
* Menutech
* KontextWork
* Simon Sapin
* René Fritz
* TrainingSparkle
* Healthchecks.io
* Hammerbacher
* Docraptor
* Yanal-Yves Fargialla
* Douwe van Loenen
* Morntag
* Xavid


Version 62.1
------------

Released on 2024-05-06.

Bug fixes:

* `#2144 <https://github.com/Kozea/WeasyPrint/issues/2144>`_,
  `#2149 <https://github.com/Kozea/WeasyPrint/pull/2149>`_:
  Avoid broken fonts when generating multiple documents
* `c10c6892 <https://github.com/Kozea/WeasyPrint/commit/c10c6892>`_:
  Display at least one grid row on empty pages
* `#2146 <https://github.com/Kozea/WeasyPrint/issues/2146>`_:
  Don’t crash when flex container’s parent’s height is auto

Contributors:

* Guillaume Ayoub
* Claudius Ellsel

Backers and sponsors:

* Spacinov
* Kobalt
* Grip Angebotssoftware
* Manuel Barkhau
* SimonSoft
* Menutech
* KontextWork
* Simon Sapin
* René Fritz
* TrainingSparkle
* Healthchecks.io
* Docraptor
* Yanal-Yves Fargialla
* Douwe van Loenen
* Morntag
* Xavid


Version 62.0
------------

Released on 2024-04-30.

Dependencies:

* Python 3.9+ is now needed, Python 3.7 and 3.8 are not supported anymore
* pydyf 0.10.0+ is now needed
* tinycss2 1.3.0+ is now needed

Features:

* `#543 <https://github.com/Kozea/WeasyPrint/issues/543>`_,
  `#2121 <https://github.com/Kozea/WeasyPrint/pull/2121>`_:
  Support CSS Grid layout
* `#2124 <https://github.com/Kozea/WeasyPrint/issues/2124>`_,
  `#2125 <https://github.com/Kozea/WeasyPrint/pull/2125>`_:
  Support border-image-* properties
* `#2084 <https://github.com/Kozea/WeasyPrint/issues/2084>`_,
  `#2077 <https://github.com/Kozea/WeasyPrint/pull/2077>`_:
  Support CSS nesting
* `#2101 <https://github.com/Kozea/WeasyPrint/issues/2101>`_:
  Support HTML maxlength attribute for form fields
* `#2095 <https://github.com/Kozea/WeasyPrint/pull/2095>`_:
  Apply overflow to replaced boxes
* `245e4f5 <https://github.com/Kozea/WeasyPrint/commit/245e4f5>`_:
  Add support of PDF/A-?u

Bug fixes:

* `#2136 <https://github.com/Kozea/WeasyPrint/issues/2136>`_:
  Don’t clip aligned text in SVG
* `#2135 <https://github.com/Kozea/WeasyPrint/pull/2135>`_:
  Allow column-direction flex containers to use percentage-based heights
* `#2128 <https://github.com/Kozea/WeasyPrint/issues/2128>`_:
  Don’t crash when a FontConfig object is destroyed early
* `#2079 <https://github.com/Kozea/WeasyPrint/issues/2079>`_:
  Fix executable file for some Windows versions
* `#2131 <https://github.com/Kozea/WeasyPrint/issues/2131>`_:
  Fix alpha for images before/after transparent text
* `#2111 <https://github.com/Kozea/WeasyPrint/issues/2111>`_:
  Handle auto and none values for CSS quotes property
* `#2103 <https://github.com/Kozea/WeasyPrint/issues/2103>`_:
  Don’t crash with overconstrained columns
* `#2100 <https://github.com/Kozea/WeasyPrint/issues/2100>`_:
  Fix rounding error when detecting overflows
* `#2093 <https://github.com/Kozea/WeasyPrint/issues/2093>`_,
  `#2097 <https://github.com/Kozea/WeasyPrint/issues/2097>`_,
  `#2094 <https://github.com/Kozea/WeasyPrint/pull/2094>`_:
  Mark use of md5() and sha1() as not for security
* `#1956 <https://github.com/Kozea/WeasyPrint/issues/1956>`_,
  `#2087 <https://github.com/Kozea/WeasyPrint/pull/2087>`_:
  Use CSS table module level 3 to compute widths
* `#2086 <https://github.com/Kozea/WeasyPrint/pull/2086>`_:
  Fix selects with empty values displaying None
* `#1112 <https://github.com/Kozea/WeasyPrint/issues/1112>`_,
  `#2082 <https://github.com/Kozea/WeasyPrint/issues/2082>`_,
  `#2085 <https://github.com/Kozea/WeasyPrint/pull/2085>`_:
  Fix computation for outer min-content width for table cells
* `016bd81 <https://github.com/Kozea/WeasyPrint/commit/016bd81>`_:
  Fix many different bugs with SVG markers

Performance:

* `#2130 <https://github.com/Kozea/WeasyPrint/issues/2130>`_:
  Cache font key instead of whole font content

Documentation:

* `#2108 <https://github.com/Kozea/WeasyPrint/pull/2108>`_:
  Update documentation about CSS leader() function

Contributors:

* Guillaume Ayoub
* Lucie Anglade
* Xavid Pretzer
* kygoh
* Germain Gueutier
* Vagner José Nicolodi

Backers and sponsors:

* Spacinov
* Kobalt
* Grip Angebotssoftware
* Manuel Barkhau
* SimonSoft
* Menutech
* KontextWork
* Simon Sapin
* René Fritz
* TrainingSparkle
* Healthchecks.io
* Docraptor
* Yanal-Yves Fargialla
* Douwe van Loenen
* Morntag
* Xavid


Version 61.2
------------

Released on 2024-03-08.

**This is a security update.**

We strongly recommend to upgrade WeasyPrint to the latest version if you use
WeasyPrint 61.0 or 61.1. Older versions are not impacted.

Security:

- Always use URL fetcher for attachments

Contributors:

* Guillaume Ayoub
* Ilia Novoselov

Backers and sponsors:

* Spacinov
* Kobalt
* Grip Angebotssoftware
* Manuel Barkhau
* SimonSoft
* Menutech
* KontextWork
* René Fritz
* Simon Sapin
* Arcanite
* TrainingSparkle
* Healthchecks.io
* Hammerbacher
* Docraptor
* Yanal-Yves Fargialla
* Morntag
* NBCO


Version 61.1
------------

Released on 2024-02-26.

Bug fixes:

- `#2075 <https://github.com/Kozea/WeasyPrint/issues/2075>`_:
  Use default value when variable is not defined
- `#2070 <https://github.com/Kozea/WeasyPrint/issues/2070>`_:
  Don’t crash when rendering SVGs with non-text a children
- Don’t crash when SVG file can’t be rendered

Documentation:

- `#2067 <https://github.com/Kozea/WeasyPrint/pull/2067>`_:
  Suggest "dnf" instead of "yum" to install Fedora packages
- Improve documentation for Windows
- Fix required version of TinyCSS2

Contributors:

* Guillaume Ayoub
* Felix Schwarz
* Lucie Anglade

Backers and sponsors:

* Spacinov
* Kobalt
* Grip Angebotssoftware
* Manuel Barkhau
* SimonSoft
* Menutech
* KontextWork
* René Fritz
* Simon Sapin
* Arcanite
* TrainingSparkle
* Healthchecks.io
* Hammerbacher
* Docraptor
* Yanal-Yves Fargialla
* Morntag
* NBCO


Version 61.0
------------

Released on 2024-02-12.

Python API:

* ``DocumentMetadata.attachments`` is now a list of ``Attachment`` objects, not
  a list of ``(url, description)`` tuples.

New features:

* `#1219 <https://github.com/Kozea/WeasyPrint/issues/1219>`_,
  `#2017 <https://github.com/Kozea/WeasyPrint/pull/2017>`_:
  Support var() in shorthand and multiple-value functions
* `#1986 <https://github.com/Kozea/WeasyPrint/issues/1986>`_:
  Support percentages for opacity
* `#2050 <https://github.com/Kozea/WeasyPrint/pull/2050>`_:
  Build executable file for Windows
* `#2000 <https://github.com/Kozea/WeasyPrint/pull/2000>`_:
  Support select fields
* `#1993 <https://github.com/Kozea/WeasyPrint/issues/1993>`_:
  Handle background-attachment: fixed to cover the whole page
* `#2023 <https://github.com/Kozea/WeasyPrint/issues/2023>`_,
  `#2022 <https://github.com/Kozea/WeasyPrint/pull/2022>`_:
  Allow text-based file objects for HTML and CSS classes
* `#2014 <https://github.com/Kozea/WeasyPrint/pull/2014>`_:
  Remove warnings for PDF/A and PDF/UA compatibility

Bug fixes:

* `#2052 <https://github.com/Kozea/WeasyPrint/issues/2052>`_,
  `#1869 <https://github.com/Kozea/WeasyPrint/pull/1869>`_:
  Handle attachments for PDF/A documents
* `#2013 <https://github.com/Kozea/WeasyPrint/issues/2013>`_,
  `#2051 <https://github.com/Kozea/WeasyPrint/pull/2051>`_:
  Apply margin to running tables
* `#1278 <https://github.com/Kozea/WeasyPrint/issues/1278>`_,
  `#1884 <https://github.com/Kozea/WeasyPrint/pull/1884>`_:
  Draw collapsed borders of running tables
* `#2029 <https://github.com/Kozea/WeasyPrint/issues/2029>`_:
  Fix page counter in non-root absolute boxes
* `#2043 <https://github.com/Kozea/WeasyPrint/pull/2043>`_:
  Fix text-anchor on SVG tspan elements
* `#1968 <https://github.com/Kozea/WeasyPrint/issues/1968>`_,
  `#2039 <https://github.com/Kozea/WeasyPrint/pull/2039>`_:
  Use cell's border-height to calculate table row height
* `#2030 <https://github.com/Kozea/WeasyPrint/issues/2030>`_:
  Ensure that bounding box is set to invisible text tags
* `#2040 <https://github.com/Kozea/WeasyPrint/issues/2040>`_,
  `#2041 <https://github.com/Kozea/WeasyPrint/pull/2041>`_:
  Don’t crash on malformed URLs
* `#2026 <https://github.com/Kozea/WeasyPrint/issues/2026>`_:
  Don’t break pages when fixed-height elements don’t overflow page
* `#2038 <https://github.com/Kozea/WeasyPrint/issues/2038>`_:
  Don’t mix original streams when drawing transparent text
* `#2016 <https://github.com/Kozea/WeasyPrint/issues/2016>`_:
  Avoid duplication when breaking out-of-flow boxes
* `#2012 <https://github.com/Kozea/WeasyPrint/issues/2012>`_:
  Don’t crash when CSS properties have no value
* `#2010 <https://github.com/Kozea/WeasyPrint/issues/2010>`_,
  `#1287 <https://github.com/Kozea/WeasyPrint/issues/1287>`_:
  Fix many corner cases with CSS variables
* `#1996 <https://github.com/Kozea/WeasyPrint/issues/1996>`_:
  Don’t crash when drawing groove/ridge collapsed borders
* `#1982 <https://github.com/Kozea/WeasyPrint/issues/1982>`_:
  Fix SVG markers size, position and drawing

Documentation:

* `#2021 <https://github.com/Kozea/WeasyPrint/issues/2021>`_,
  `#2048 <https://github.com/Kozea/WeasyPrint/pull/2048>`_:
  Replace non-virtualenv installation instructions with distribution packages

Contributors:

* Guillaume Ayoub
* kygoh
* Lucie Anglade
* Timo Ramsauer
* Alexander Gitter
* Michael Lisitsa
* Vagner José Nicolodi
* Manolis Stamatogiannakis
* Pascal de Bruijn
* Viktor Shevtsov
* Eduardo Gonzalez
* Kesara Rathnayake

Backers and sponsors:

* Spacinov
* Kobalt
* Grip Angebotssoftware
* Manuel Barkhau
* SimonSoft
* Menutech
* KontextWork
* René Fritz
* Simon Sapin
* Arcanite
* TrainingSparkle
* Healthchecks.io
* Hammerbacher
* Docraptor
* Yanal-Yves Fargialla
* Morntag
* NBCO


Version 60.2
------------

Released on 2023-12-11.

Bug fixes:

* `#1982 <https://github.com/Kozea/WeasyPrint/issues/1982>`_:
  Fix SVG markers size, position and drawing
* `23cfc775 <https://github.com/Kozea/WeasyPrint/commit/23cfc775>`_:
  Draw background behind absolutely positioned replaced boxes
* `fe2f0c69 <https://github.com/Kozea/WeasyPrint/commit/fe2f0c69>`_:
  Don’t crash with bitmap fonts with no "glyf" table
* `14605225 <https://github.com/Kozea/WeasyPrint/commit/14605225>`_:
  Improve SVG text-anchor attribute

Contributors:

* Guillaume Ayoub

Backers and sponsors:

* Spacinov
* Kobalt
* Grip Angebotssoftware
* Manuel Barkhau
* SimonSoft
* Menutech
* KontextWork
* NCC Group
* René Fritz
* Nicola Auchmuty
* Syslifters
* Hammerbacher
* TrainingSparkle
* Daniel Kucharski
* Healthchecks.io
* Yanal-Yves Fargialla
* WakaTime
* Paheko
* Synapsium
* DocRaptor


Version 60.1
------------

Released on 2023-09-29.

Bug fixes:

* `#1973 <https://github.com/Kozea/WeasyPrint/issues/1973>`_:
  Fix crash caused by wrong UTF-8 indices

Contributors:

* Guillaume Ayoub

Backers and sponsors:

* Spacinov
* Kobalt
* Grip Angebotssoftware
* Manuel Barkhau
* SimonSoft
* Menutech
* KontextWork
* NCC Group
* René Fritz
* Nicola Auchmuty
* Syslifters
* Hammerbacher
* TrainingSparkle
* Daniel Kucharski
* Healthchecks.io
* Yanal-Yves Fargialla
* WakaTime
* Paheko
* Synapsium
* DocRaptor


Version 60.0
------------

Released on 2023-09-25.

New features:

* `#1903 <https://github.com/Kozea/WeasyPrint/issues/1903>`_:
  Print form fields
* `#1922 <https://github.com/Kozea/WeasyPrint/pull/1922>`_:
  Add support for textLength and lengthAdjust in SVG text elements
* `#1965 <https://github.com/Kozea/WeasyPrint/issues/1965>`_:
  Handle <wbr> tag
* `#1970 <https://github.com/Kozea/WeasyPrint/pull/1970>`_:
  Handle y offset of glyphs
* `#1909 <https://github.com/Kozea/WeasyPrint/issues/1909>`_:
  Add a --timeout option

Bug fixes:

* `#1887 <https://github.com/Kozea/WeasyPrint/pull/1887>`_:
  Fix footnote-call displayed incorrectly for some fonts
* `#1890 <https://github.com/Kozea/WeasyPrint/pull/1890>`_:
  Fix page-margin boxes layout algorithm
* `#1908 <https://github.com/Kozea/WeasyPrint/pull/1908>`_:
  Fix IndexError when rendering PDF version 1.4
* `#1906 <https://github.com/Kozea/WeasyPrint/issues/1906>`_:
  Apply text transformations to first-letter pseudo elements
* `#1915 <https://github.com/Kozea/WeasyPrint/pull/1915>`_:
  Avoid footnote appearing before its call
* `#1934 <https://github.com/Kozea/WeasyPrint/pull/1934>`_:
  Fix balance before "column-span: all"
* `#1935 <https://github.com/Kozea/WeasyPrint/issues/1935>`_:
  Only draw required glyph with OpenType-SVG fonts
* `#1595 <https://github.com/Kozea/WeasyPrint/issues/1595>`_:
  Don’t draw clipPath when defined after reference
* `#1895 <https://github.com/Kozea/WeasyPrint/pull/1895>`_:
  Don’t ignore min-width when computing cell size
* `#1899 <https://github.com/Kozea/WeasyPrint/pull/1899>`_:
  Fix named pages inheritance
* `#1936 <https://github.com/Kozea/WeasyPrint/pull/1936>`_:
  Avoid page breaks caused by children of overflow hidden boxes
* `#1943 <https://github.com/Kozea/WeasyPrint/issues/1943>`_:
  Use bleed area for page’s painting area
* `#1946 <https://github.com/Kozea/WeasyPrint/issues/1946>`_:
  Use margin box of children to define available width for leaders

Contributors:

* Guillaume Ayoub
* Sahil Rohilla
* Azharuddin Syed
* kygoh
* Andy Lenards
* Gaurav Samudra
* Michael Wedl
* Lucie Anglade
* Obeida Shamoun
* Evgeniy Krysanov

Backers and sponsors:

* Spacinov
* Kobalt
* Grip Angebotssoftware
* Manuel Barkhau
* SimonSoft
* Menutech
* KontextWork
* NCC Group
* René Fritz
* Nicola Auchmuty
* Syslifters
* Hammerbacher
* TrainingSparkle
* Daniel Kucharski
* Healthchecks.io
* Yanal-Yves Fargialla
* WakaTime
* Paheko
* Synapsium
* DocRaptor


Version 59.0
------------

Released on 2023-05-11.

This version also includes the changes from unstable b1 version listed
below.

Bug fixes:

* `#1864 <https://github.com/Kozea/WeasyPrint/issues/1864>`_:
  Handle overflow for svg and symbol tags in SVG images
* `#1867 <https://github.com/Kozea/WeasyPrint/pull/1867>`_:
  Remove duplicate compression of attachments
* `d0ad5c1 <https://github.com/Kozea/WeasyPrint/commit/d0ad5c1>`_:
  Override use tag children instead of drawing their references
* `93df1a5 <https://github.com/Kozea/WeasyPrint/commit/93df1a5>`_:
  Don’t resize the same image twice when the --dpi option is set
* `#1874 <https://github.com/Kozea/WeasyPrint/pull/1874>`_:
  Drawn underline and overline behind text

Contributors:

* Guillaume Ayoub
* Timo Ramsauer
* Alexander Mankuta

Backers and sponsors:

* Castedo Ellerman
* Kobalt
* Spacinov
* Grip Angebotssoftware
* Crisp BV
* Manuel Barkhau
* SimonSoft
* Menutech
* KontextWork
* NCC Group
* René Fritz
* Moritz Mahringer
* Yanal-Yves Fargialla
* Piotr Horzycki
* Healthchecks.io
* TrainingSparkle
* Hammerbacher
* Synapsium


Version 59.0b1
--------------

Released on 2023-04-14.

**This version is experimental, don't use it in production. If you find bugs,
please report them!**

Command-line API:

* The ``--optimize-size`` option and its short equivalent ``-O`` have been
  deprecated. To activate or deactivate different size optimizations, you can
  now use:

  * ``--uncompressed-pdf``,
  * ``--optimize-images``,
  * ``--full-fonts``,
  * ``--hinting``,
  * ``--dpi <resolution>``, and
  * ``--jpeg-quality <quality>``.

* A new ``--cache-folder <folder>`` option has been added to store temporary
  data in the given folder on the disk instead of keeping them in memory.

Python API:

* Global rendering options are now given in ``**options`` instead of dedicated
  parameters, with slightly different names. It means that the signature of the
  ``HTML.render()``, ``HTML.write_pdf()`` and ``Document.write_pdf()`` has
  changed. Here are the steps to port your Python code to v59.0:

  1. Use named parameters for these functions, not positioned parameters.
  2. Rename some the parameters:

     * ``image_cache`` becomes ``cache`` (see below),
     * ``identifier`` becomes ``pdf_identifier``,
     * ``variant`` becomes ``pdf_variant``,
     * ``version`` becomes ``pdf_version``,
     * ``forms`` becomes ``pdf_forms``.

* The ``optimize_size`` parameter of ``HTML.render()``, ``HTML.write_pdf()``
  and ``Document()`` has been removed and will be ignored. You can now use the
  ``uncompressed_pdf``, ``full_fonts``, ``hinting``, ``dpi`` and
  ``jpeg_quality`` parameters that are included in ``**options``.

* The ``cache`` parameter can be included in ``**options`` to replace
  ``image_cache``. If it is a dictionary, this dictionary will be used to store
  temporary data in memory, and can be even shared between multiple documents.
  If it’s a folder Path or string, WeasyPrint stores temporary data in the
  given temporary folder on disk instead of keeping them in memory.

New features:

* `#1853 <https://github.com/Kozea/WeasyPrint/pull/1853>`_,
  `#1854 <https://github.com/Kozea/WeasyPrint/issues/1854>`_:
  Reduce PDF size, with financial support from Code & Co.
* `#1824 <https://github.com/Kozea/WeasyPrint/issues/1824>`_,
  `#1829 <https://github.com/Kozea/WeasyPrint/pull/1829>`_:
  Reduce memory use for images
* `#1858 <https://github.com/Kozea/WeasyPrint/issues/1858>`_:
  Add an option to keep hinting information in embedded fonts

Bug fixes:

* `#1855 <https://github.com/Kozea/WeasyPrint/issues/1855>`_:
  Fix position of emojis in justified text
* `#1852 <https://github.com/Kozea/WeasyPrint/issues/1852>`_:
  Don’t crash when line can be split before trailing spaces
* `#1843 <https://github.com/Kozea/WeasyPrint/issues/1843>`_:
  Fix syntax of dates in metadata
* `#1827 <https://github.com/Kozea/WeasyPrint/issues/1827>`_,
  `#1832 <https://github.com/Kozea/WeasyPrint/pull/1832>`_:
  Fix word-spacing problems with nested tags

Documentation:

* `#1841 <https://github.com/Kozea/WeasyPrint/issues/1841>`_:
  Add a paragraph about unsupported calc() function

Contributors:

* Guillaume Ayoub
* Lucie Anglade
* Alex Ch
* whi_ne
* Jonas Castro

Backers and sponsors:

* Castedo Ellerman
* Kobalt
* Spacinov
* Grip Angebotssoftware
* Crisp BV
* Manuel Barkhau
* SimonSoft
* Menutech
* KontextWork
* NCC Group
* René Fritz
* Moritz Mahringer
* Yanal-Yves Fargialla
* Piotr Horzycki
* Healthchecks.io
* TrainingSparkle
* Hammerbacher
* Synapsium


Version 58.1
------------

Released on 2023-03-07.

Bug fixes:

* `#1815 <https://github.com/Kozea/WeasyPrint/issues/1815>`_:
  Fix bookmarks coordinates
* `#1822 <https://github.com/Kozea/WeasyPrint/issues/1822>`_,
  `#1823 <https://github.com/Kozea/WeasyPrint/pull/1823>`_:
  Fix vertical positioning for absolute replaced elements

Documentation:

* `#1814 <https://github.com/Kozea/WeasyPrint/pull/1814>`_:
  Fix broken link pointing to samples

Contributors:

* Guillaume Ayoub
* Jonas Castro
* Lucie Anglade
* Menelaos Kotoglou

Backers and sponsors:

* Kobalt
* Grip Angebotssoftware
* Spacinov
* Crisp BV
* Castedo Ellerman
* Manuel Barkhau
* SimonSoft
* Menutech
* KontextWork
* NCC Group
* René Fritz
* Moritz Mahringer
* Yanal-Yves Fargialla
* Piotr Horzycki
* Healthchecks.io
* Hammerbacher
* TrainingSparkle
* Synapsium


Version 58.0
------------

Released on 2023-02-17.

This version also includes the changes from unstable b1 version listed
below.

Bug fixes:

* `#1807 <https://github.com/Kozea/WeasyPrint/issues/1807>`_:
  Don’t crash when out-of-flow box is split in out-of-flow parent
* `#1806 <https://github.com/Kozea/WeasyPrint/issues/1806>`_:
  Don’t crash when fixed elements aren’t displayed yet in aborted line
* `#1809 <https://github.com/Kozea/WeasyPrint/issues/1809>`_:
  Fix background drawing for out-of-the-page transformed boxes

Contributors:

* Guillaume Ayoub

Backers and sponsors:

* Kobalt
* Grip Angebotssoftware
* Crisp BV
* Spacinov
* Castedo Ellerman
* Manuel Barkhau
* SimonSoft
* Menutech
* KontextWork
* NCC Group
* René Fritz
* Moritz Mahringer
* Yanal-Yves Fargialla
* Piotr Horzycki
* Healthchecks.io


Version 58.0b1
--------------

Released on 2023-02-03.

**This version is experimental, don't use it in production. If you find bugs,
please report them!**

New features:

* `#61 <https://github.com/Kozea/WeasyPrint/issues/61>`_,
  `#1796 <https://github.com/Kozea/WeasyPrint/pull/1796>`_:
  Support PDF forms, with financial support from Personalkollen
* `#1173 <https://github.com/Kozea/WeasyPrint/issues/1173>`_:
  Add style for form fields

Bug fixes:

* `#1777 <https://github.com/Kozea/WeasyPrint/issues/1777>`_:
  Detect JPEG/MPO images as normal JPEG files
* `#1771 <https://github.com/Kozea/WeasyPrint/pull/1771>`_:
  Improve SVG gradients

Contributors:

* Guillaume Ayoub
* Lucie Anglade

Backers and sponsors:

* Kobalt
* Grip Angebotssoftware
* Crisp BV
* Spacinov
* Castedo Ellerman
* Manuel Barkhau
* SimonSoft
* Menutech
* KontextWork
* NCC Group
* René Fritz
* Moritz Mahringer
* Yanal-Yves Fargialla
* Piotr Horzycki
* Healthchecks.io


Version 57.2
------------

Released on 2022-12-23.

Bug fixes:

* `0f2e377 <https://github.com/Kozea/WeasyPrint/commit/0f2e377>`_:
  Print annotations with PDF/A
* `0e9426f <https://github.com/Kozea/WeasyPrint/commit/0e9426f>`_:
  Hide annotations with PDF/UA
* `#1764 <https://github.com/Kozea/WeasyPrint/issues/1764>`_:
  Use reference instead of stream for annotation appearance stream
* `#1783 <https://github.com/Kozea/WeasyPrint/pull/1783>`_:
  Fix multiple font weights for @font-face declarations

Contributors:

* Guillaume Ayoub

Backers and sponsors:

* Grip Angebotssoftware
* Manuel Barkhau
* Crisp BV
* SimonSoft
* Menutech
* Spacinov
* KontextWork
* René Fritz
* NCC Group
* Kobalt
* Tom Pohl
* Castedo Ellerman
* Moritz Mahringer
* Piotr Horzycki
* Gábor Nyers
* Sidharth Kapur


Version 57.1
------------

Released on 2022-11-04.

Dependencies:

* `#1754 <https://github.com/Kozea/WeasyPrint/pull/1754>`_:
  Pillow 9.1.0 is now needed

Bug fixes:

* `#1756 <https://github.com/Kozea/WeasyPrint/pull/1756>`_:
  Fix rem font size for SVG images
* `#1755 <https://github.com/Kozea/WeasyPrint/issues/1755>`_:
  Keep format when transposing images
* `#1753 <https://github.com/Kozea/WeasyPrint/issues/1753>`_:
  Don’t use deprecated ``read_text`` function when ``files`` is available
* `#1741 <https://github.com/Kozea/WeasyPrint/issues/1741>`_:
  Generate better manpage
* `#1747 <https://github.com/Kozea/WeasyPrint/issues/1747>`_:
  Correctly set target counters in pages’ absolute elements
* `#1748 <https://github.com/Kozea/WeasyPrint/issues/1748>`_:
  Always set font size when font is changed in line
* `2b05137 <https://github.com/Kozea/WeasyPrint/commit/2b05137>`_:
  Fix stability of font identifiers

Documentation:

* `#1750 <https://github.com/Kozea/WeasyPrint/pull/1750>`_:
  Fix documentation spelling

Contributors:

* Guillaume Ayoub
* Eli Schwartz
* Mikhail Anikin
* Scott Kitterman

Backers and sponsors:

* Grip Angebotssoftware
* Manuel Barkhau
* Crisp BV
* SimonSoft
* Menutech
* Spacinov
* KontextWork
* René Fritz
* NCC Group
* Kobalt
* Tom Pohl
* John R Ellis
* Castedo Ellerman
* Moritz Mahringer
* Gábor
* Piotr Horzycki


Version 57.0
------------

Released on 2022-10-18.

This version also includes the changes from unstable b1 version listed
below.

New features:

* `a4fc7a1 <https://github.com/Kozea/WeasyPrint/commit/a4fc7a1>`_:
  Support image-orientation

Bug fixes:

* `#1739 <https://github.com/Kozea/WeasyPrint/issues/1739>`_:
  Set baseline on all flex containers
* `#1740 <https://github.com/Kozea/WeasyPrint/issues/1740>`_:
  Don’t crash when currentColor is set on root svg tag
* `#1718 <https://github.com/Kozea/WeasyPrint/issues/1718>`_:
  Don’t crash with empty bitmap glyphs
* `#1736 <https://github.com/Kozea/WeasyPrint/issues/1736>`_:
  Always use the font’s vector variant when possible
* `eef8b4d <https://github.com/Kozea/WeasyPrint/commit/eef8b4d>`_:
  Always set color and state before drawing
* `#1662 <https://github.com/Kozea/WeasyPrint/issues/1662>`_:
  Use a stable key to store stream fonts
* `#1733 <https://github.com/Kozea/WeasyPrint/issues/1733>`_:
  Don’t remove attachments when adding internal anchors
* `3c4fa50 <https://github.com/Kozea/WeasyPrint/commit/3c4fa50>`_,
  `c215697 <https://github.com/Kozea/WeasyPrint/commit/c215697>`_,
  `d275dac <https://github.com/Kozea/WeasyPrint/commit/d275dac>`_,
  `b04bfff <https://github.com/Kozea/WeasyPrint/commit/b04bfff>`_:
  Fix many bugs related to PDF/UA structure

Performance:

* `dfccf1b <https://github.com/Kozea/WeasyPrint/commit/dfccf1b>`_:
  Use faces as fonts dictionary keys
* `0dc12b6 <https://github.com/Kozea/WeasyPrint/commit/0dc12b6>`_:
  Cache add_font to avoid calling get_face too often
* `75e17bf <https://github.com/Kozea/WeasyPrint/commit/75e17bf>`_:
  Don’t call process_whitespace twice on many children
* `498d3e1 <https://github.com/Kozea/WeasyPrint/commit/498d3e1>`_:
  Optimize __missing__ functions

Documentation:

* `863b3d6 <https://github.com/Kozea/WeasyPrint/commit/863b3d6>`_:
  Update documentation of installation on macOS with Homebrew

Contributors:

* Guillaume Ayoub

Backers and sponsors:

* Grip Angebotssoftware
* Manuel Barkhau
* Crisp BV
* SimonSoft
* Menutech
* Spacinov
* KontextWork
* René Fritz
* NCC Group
* Kobalt
* Tom Pohl
* John R Ellis
* Castedo Ellerman
* Moritz Mahringer
* Gábor
* Piotr Horzycki


Version 57.0b1
--------------

Released on 2022-09-22.

**This version is experimental, don't use it in production. If you find bugs,
please report them!**

New features:

* `#1704 <https://github.com/Kozea/WeasyPrint/pull/1704>`_:
  Support PDF/UA, with financial support from Novareto
* `#1454 <https://github.com/Kozea/WeasyPrint/issues/1454>`_:
  Support variable fonts

Bug fixes:

* `#1058 <https://github.com/Kozea/WeasyPrint/issues/1058>`_:
  Fix bullet position after page break, with financial support from OpenZeppelin
* `#1707 <https://github.com/Kozea/WeasyPrint/issues/1707>`_:
  Fix footnote positioning in multicolumn layout, with financial support from Code & Co.
* `#1722 <https://github.com/Kozea/WeasyPrint/issues/1722>`_:
  Handle skew transformation with only one parameter
* `#1715 <https://github.com/Kozea/WeasyPrint/issues/1715>`_:
  Don’t crash when images are truncated
* `#1697 <https://github.com/Kozea/WeasyPrint/issues/1697>`_:
  Don’t crash when attr() is used in text-decoration-color
* `#1695 <https://github.com/Kozea/WeasyPrint/pull/1695>`_:
  Include language information in PDF metadata
* `#1612 <https://github.com/Kozea/WeasyPrint/issues/1612>`_:
  Don’t lowercase letters when capitalizing text
* `#1700 <https://github.com/Kozea/WeasyPrint/issues/1700>`_:
  Fix crash when rendering footnote with repagination
* `#1667 <https://github.com/Kozea/WeasyPrint/issues/1667>`_:
  Follow EXIF metadata for image rotation
* `#1669 <https://github.com/Kozea/WeasyPrint/issues/1669>`_:
  Take care of floats when remvoving placeholders
* `#1638 <https://github.com/Kozea/WeasyPrint/issues/1638>`_:
  Use the original box when breaking waiting children

Contributors:

* Guillaume Ayoub
* Konstantin Weddige
* VeteraNovis
* Lucie Anglade

Backers and sponsors:

* Grip Angebotssoftware
* Manuel Barkhau
* Crisp BV
* SimonSoft
* Menutech
* Spacinov
* KontextWork
* René Fritz
* NCC Group
* Kobalt
* Tom Pohl
* John R Ellis
* Moritz Mahringer
* Gábor
* Piotr Horzycki
* Andrew Ittner


Version 56.1
------------

Released on 2022-07-24.

Bug fixes:

* `#1674 <https://github.com/Kozea/WeasyPrint/issues/1674>`_:
  Follow max-height on footnot area, with financial support from Code & Co.
* `#1678 <https://github.com/Kozea/WeasyPrint/issues/1678>`_:
  Fix gradients with opacity set

Contributors:

* Guillaume Ayoub
* Lucie Anglade

Backers and sponsors:

* Grip Angebotssoftware
* Manuel Barkhau
* Crisp BV
* SimonSoft
* Menutech
* Spacinov
* KontextWork
* René Fritz
* NCC Group
* Kobalt
* Tom Pohl
* Moritz Mahringer
* Florian Demmer
* Yanal-Yves Fargialla
* Gábor
* Piotr Horzycki
* Andrew Ittner


Version 56.0
------------

Released on 2022-07-07.

This version also includes the changes from unstable b1 version listed
below.

New features:

* `70f9b62 <https://github.com/Kozea/WeasyPrint/commit/70f9b62>`_:
  Support format 5 for bitmap glyphs

Bug fixes:

* `#1666 <https://github.com/Kozea/WeasyPrint/issues/1666>`_
  Fix reproducible PDF generation with embedded images
* `#1668 <https://github.com/Kozea/WeasyPrint/issues/1668>`_:
  Fix @page:nth() selector
* `3bd9a8e <https://github.com/Kozea/WeasyPrint/commit/3bd9a8e>`_:
  Don’t limit the opacity groups to the original box size
* `cb9540b <https://github.com/Kozea/WeasyPrint/commit/cb9540b>`_,
  `76d174f <https://github.com/Kozea/WeasyPrint/commit/76d174f>`_,
  `9ce6547 <https://github.com/Kozea/WeasyPrint/commit/9ce6547>`_:
  Minor bugfixes for split table rows

Contributors:

* Guillaume Ayoub

Backers and sponsors:

* Grip Angebotssoftware
* Manuel Barkhau
* Crisp BV
* SimonSoft
* Menutech
* Spacinov
* KontextWork
* René Fritz
* NCC Group
* Kobalt
* Des images et des mots
* Andreas Zettl
* Tom Pohl
* Moritz Mahringer
* Florian Demmer
* Yanal-Yves Fargialla
* Gábor
* Piotr Horzycki


Version 56.0b1
--------------

Released on 2022-06-17.

**This version is experimental, don't use it in production. If you find bugs,
please report them!**

Dependencies:

* pydyf 0.2.0+ is now needed

New features:

* `#1660 <https://github.com/Kozea/WeasyPrint/pull/1660>`_:
  Support nested line-clamp, with financial support from Expert Germany
* `#1644 <https://github.com/Kozea/WeasyPrint/pull/1644>`_,
  `#1645 <https://github.com/Kozea/WeasyPrint/issues/1645>`_:
  Support bitmap fonts, with financial support from Expert Germany
* `#1651 <https://github.com/Kozea/WeasyPrint/pull/1651>`_,
  `#630 <https://github.com/Kozea/WeasyPrint/issues/630>`_:
  Support PDF/A, with financial support from Blueshoe

Bug fixes:

* `#1656 <https://github.com/Kozea/WeasyPrint/issues/1656>`_:
  Fix chained variables in the same selector block
* `#1028 <https://github.com/Kozea/WeasyPrint/issues/1028>`_:
  Fix font weight management in @font-face rules
* `#1653 <https://github.com/Kozea/WeasyPrint/issues/1653>`_:
  Don’t crash when @font-face’s src ends with a comma
* `#1650 <https://github.com/Kozea/WeasyPrint/issues/1650>`_:
  Don’t check origin when URL only contains fragment
* `e38bff8 <https://github.com/Kozea/WeasyPrint/commit/e38bff8>`_:
  Don’t crash when inherited SVG attributes are not set on the parent

Performance:

* `e6021da <https://github.com/Kozea/WeasyPrint/commit/e6021da>`_:
  Launch tests in parallel by default

Contributors:

* Guillaume Ayoub
* aschmitz
* Lucie Anglade

Backers and sponsors:

* Grip Angebotssoftware
* Manuel Barkhau
* Crisp BV
* SimonSoft
* Menutech
* Spacinov
* KontextWork
* René Fritz
* NCC Group
* Kobalt
* Des images et des mots
* Andreas Zettl
* Tom Pohl
* Moritz Mahringer
* Florian Demmer
* Yanal-Yves Fargialla
* Gábor
* Piotr Horzycki


Version 55.0
------------

Released on 2022-05-12.

This version also includes the changes from unstable b1 version listed
below.

Bug fixes:

* `#1626 <https://github.com/Kozea/WeasyPrint/issues/1626>`_,
  `3802f88 <https://github.com/Kozea/WeasyPrint/commit/3802f88>`_:
  Fix the vertical position and available height of absolute boxes
* `9641098 <https://github.com/Kozea/WeasyPrint/commit/9641098>`_,
  `e5e6b88 <https://github.com/Kozea/WeasyPrint/commit/e5e6b88>`_:
  Minor fixes for multi-column layout
* `0fcc7de <https://github.com/Kozea/WeasyPrint/commit/0fcc7de>`_:
  Don’t stop rendering SVG when CSS parsing fails
* `#1636 <https://github.com/Kozea/WeasyPrint/pull/1636>`_:
  Fix sequential footnotes that could disappear when overflowing
* `#1637 <https://github.com/Kozea/WeasyPrint/issues/1637>`_:
  Fix position of absolute boxes with right-to-left direction
* `#1641 <https://github.com/Kozea/WeasyPrint/issues/1641>`_:
  Fix relative paths for SVG files stored as data URLs

Contributors:

* Guillaume Ayoub
* aschmitz

Backers and sponsors:

* Grip Angebotssoftware
* Manuel Barkhau
* Crisp BV
* SimonSoft
* Menutech
* Spacinov
* KontextWork
* René Fritz
* NCC Group
* Kobalt
* Nathalie Gutton
* Andreas Zettl
* Tom Pohl
* Moritz Mahringer
* Florian Demmer
* Yanal-Yves Fargialla
* Gábor
* Piotr Horzycki


Version 55.0b1
--------------

Released on 2022-04-15.

**This version is experimental, don't use it in production. If you find bugs,
please report them!**

Dependencies:

* Python 3.7+ is now needed, Python 3.6 is not supported anymore

New features:

* `#1534 <https://github.com/Kozea/WeasyPrint/pull/1534>`_:
  Support ``word-break: break-all``
* `#489 <https://github.com/Kozea/WeasyPrint/issues/489>`_,
  `#1619 <https://github.com/Kozea/WeasyPrint/pull/1619>`_:
  Support column breaks
* `#1553 <https://github.com/Kozea/WeasyPrint/issues/1553>`_:
  Allow reproducible PDF generation

Bug fixes:

* `#1007 <https://github.com/Kozea/WeasyPrint/issues/1007>`_,
  `#1524 <https://github.com/Kozea/WeasyPrint/pull/1524>`_:
  Handle ``inherit`` in shorthand properties
* `#1539 <https://github.com/Kozea/WeasyPrint/issues/1539>`_,
  `#1541 <https://github.com/Kozea/WeasyPrint/pull/1541>`_:
  Space out no-repeat patterns
* `#1554 <https://github.com/Kozea/WeasyPrint/pull/1554>`_:
  Avoid invalid PDF operators when drawing SVG text
* `#1564 <https://github.com/Kozea/WeasyPrint/issues/1564>`_,
  `#1566 <https://github.com/Kozea/WeasyPrint/pull/1566>`_,
  `#1570 <https://github.com/Kozea/WeasyPrint/pull/1570>`_:
  Don’t output footnotes before their call sites
* `#1020 <https://github.com/Kozea/WeasyPrint/issues/1020>`_,
  `#1597 <https://github.com/Kozea/WeasyPrint/pull/1597>`_:
  Prevent infinite loops in multi-column layout
* `#1512 <https://github.com/Kozea/WeasyPrint/issues/1512>`_,
  `#1613 <https://github.com/Kozea/WeasyPrint/pull/1613>`_:
  Fix position of absolute boxes in right-to-left contexts
* `#1093 <https://github.com/Kozea/WeasyPrint/issues/1093>`_:
  Draw borders around absolute replaced boxes
* `#984 <https://github.com/Kozea/WeasyPrint/issues/984>`_,
  `#1604 <https://github.com/Kozea/WeasyPrint/issues/1604>`_:
  Fix skip stacks for columns
* `#1621 <https://github.com/Kozea/WeasyPrint/issues/1621>`_:
  Better support of nested ``text-decoration`` properties
* `fe1f3d9 <https://github.com/Kozea/WeasyPrint/commit/fe1f3d9>`_:
  Fix absolute blocks in lines
* `4650b70 <https://github.com/Kozea/WeasyPrint/commit/4650b70>`_:
  Clear adjoining margins when a container’s child doesn’t fit

Performance:

* `#1548 <https://github.com/Kozea/WeasyPrint/pull/1548>`_:
  Improve tests speed
* `3b0ae92 <https://github.com/Kozea/WeasyPrint/commit/3b0ae92>`_,
  `#1457 <https://github.com/Kozea/WeasyPrint/issues/1457>`_:
  Improve fonts management
* `#1597 <https://github.com/Kozea/WeasyPrint/pull/1597>`_:
  Improve column layout speed
* `#1587 <https://github.com/Kozea/WeasyPrint/pull/1587>`_,
  `#1607 <https://github.com/Kozea/WeasyPrint/pull/1607>`_,
  `#1608 <https://github.com/Kozea/WeasyPrint/pull/1608>`_:
  Cache ``ch`` and ``ex`` units calculations

Contributors:

* Guillaume Ayoub
* aschmitz
* Lucie Anglade
* Christoph Kepper
* Jack Lin
* Rian McGuire

Backers and sponsors:

* Grip Angebotssoftware
* Manuel Barkhau
* Crisp BV
* SimonSoft
* Menutech
* KontextWork
* Maykin Media
* René Fritz
* NCC Group
* Spacinov
* Nathalie Gutton
* Andreas Zettl
* Tom Pohl
* Kobalt
* Moritz Mahringer
* Florian Demmer
* Yanal-Yves Fargialla
* Gábor
* Piotr Horzycki
* DeivGuerrero


Version 54.3
------------

Released on 2022-04-04.

Bug fixes:

* `#1588 <https://github.com/Kozea/WeasyPrint/pull/1588>`_:
  Support position: absolute in footnotes
* `#1586 <https://github.com/Kozea/WeasyPrint/issues/1586>`_:
  Fix discarded text-align values

Contributors:

* aschmitz
* Guillaume Ayoub

Backers and sponsors:

* Grip Angebotssoftware
* Manuel Barkhau
* Crisp BV
* SimonSoft
* Menutech
* KontextWork
* Maykin Media
* René Fritz
* NCC Group
* Spacinov
* Nathalie Gutton
* Andreas Zettl
* Tom Pohl
* Kobalt
* Moritz Mahringer
* Florian Demmer
* Yanal-Yves Fargialla
* Gábor
* Piotr Horzycki
* DeivGuerrero


Version 54.2
------------

Released on 2022-02-27.

Bug fixes:

* `#1575 <https://github.com/Kozea/WeasyPrint/issues/1575>`_:
  Always store parent blocks children as lists
* `#1574 <https://github.com/Kozea/WeasyPrint/issues/1574>`_,
  `#1559 <https://github.com/Kozea/WeasyPrint/pull/1559>`_:
  Fix float rounding errors
* `#1571 <https://github.com/Kozea/WeasyPrint/issues/1571>`_:
  Ignore unknown glyphs
* `#1561 <https://github.com/Kozea/WeasyPrint/issues/1561>`_,
  `#1562 <https://github.com/Kozea/WeasyPrint/issues/1562>`_:
  Fix line break when breaks occur between a nbsp and an inline block
* `#1560 <https://github.com/Kozea/WeasyPrint/issues/1560>`_:
  Always set the child index
* `#1558 <https://github.com/Kozea/WeasyPrint/issues/1558>`_:
  Fix patterns with use tags

Contributors:

* Guillaume Ayoub
* Lucie Anglade
* Jack Lin
* aschmitz

Backers and sponsors:

* Grip Angebotssoftware
* Manuel Barkhau
* Crisp BV
* SimonSoft
* Menutech
* KontextWork
* Maykin Media
* René Fritz
* NCC Group
* Spacinov
* Nathalie Gutton
* Andreas Zettl
* Tom Pohl
* Kobalt
* Moritz Mahringer
* Florian Demmer
* Yanal-Yves Fargialla
* Gábor
* Piotr Horzycki
* DeivGuerrero


Version 54.1
------------

Released on 2022-01-31.

New features:

* `#1547 <https://github.com/Kozea/WeasyPrint/issues/1547>`_:
  Handle break-inside: avoid on tr tags

Bug fixes:

* `#1540 <https://github.com/Kozea/WeasyPrint/issues/1540>`_,
  `#1239 <https://github.com/Kozea/WeasyPrint/issues/1239>`_:
  Handle absolute children in running elements
* `#1538 <https://github.com/Kozea/WeasyPrint/issues/1538>`_:
  Handle invalid values in text-align
* `#1536 <https://github.com/Kozea/WeasyPrint/issues/1536>`_:
  Handle absolute flex boxes

Contirbutors:

* Guillaume Ayoub
* Lucie Anglade

Backers and sponsors:

* H-Net: Humanities and Social Sciences Online
* Grip Angebotssoftware
* Manuel Barkhau
* SimonSoft
* Menutech
* KontextWork
* Crisp BV
* Maykin Media
* René Fritz
* Simon Sapin
* NCC Group
* Nathalie Gutton
* Andreas Zettl
* Tom Pohl
* Spacinov
* Des images et des mots
* Moritz Mahringer
* Florian Demmer
* Yanal-Yves Fargialla
* Gábor
* Piotr Horzycki


Version 54.0
------------

Released on 2022-01-08.

This version also includes the changes from unstable b1 version listed
below.

Bug fixes:

* `#1531 <https://github.com/Kozea/WeasyPrint/issues/1531>`_:
  Always use absolute paths to get hrefs in SVG
* `#1523 <https://github.com/Kozea/WeasyPrint/issues/1523>`_:
  Fix many rendering problems of broken tables
* `e1aee70 <https://github.com/Kozea/WeasyPrint/commit/e1aee70>`_:
  Fix support of fonts with SVG emojis

Contirbutors:

* Guillaume Ayoub

Backers and sponsors:

* Grip Angebotssoftware
* Manuel Barkhau
* SimonSoft
* Menutech
* KontextWork
* Crisp BV
* Maykin Media
* René Fritz
* Simon Sapin
* NCC Group
* Nathalie Gutton
* Andreas Zettl
* Tom Pohl
* Des images et des mots
* Moritz Mahringer
* Florian Demmer
* Yanal-Yves Fargialla
* Gábor
* Piotr Horzycki


Version 54.0b1
--------------

Released on 2021-12-13.

**This version is experimental, don't use it in production. If you find bugs,
please report them!**

Dependencies:

* html5lib 1.1+ is now needed.

New features:

* `#1509 <https://github.com/Kozea/WeasyPrint/pull/1509>`_:
  Support footnotes, with financial support from Code & Co.
* `#36 <https://github.com/Kozea/WeasyPrint/issues/36>`_:
  Handle parallel flows for floats, absolutes, table-cells
* `#1389 <https://github.com/Kozea/WeasyPrint/pull/1389>`_:
  Support ``text-align-last`` and ``text-align-all`` properties
* `#1434 <https://github.com/Kozea/WeasyPrint/pull/1434>`_:
  Draw SVG and PNG emojis
* `#1520 <https://github.com/Kozea/WeasyPrint/pull/1520>`_:
  Support ``overflow-wrap: anywhere``
* `#1435 <https://github.com/Kozea/WeasyPrint/issues/1435>`_:
  Add environment variable to set DLL folder on Windows

Performance:

* `#1439 <https://github.com/Kozea/WeasyPrint/issues/1439>`_:
  Cache SVG ``use`` tags
* `#1481 <https://github.com/Kozea/WeasyPrint/pull/1481>`_:
  Encode non-JPEG images as PNGs instead of JPEG2000s

Bug fixes:

* `#137 <https://github.com/Kozea/WeasyPrint/issues/137>`_:
  Don’t use ``text-transform`` text for content-based uses
* `#1443 <https://github.com/Kozea/WeasyPrint/issues/1443>`_:
  Don’t serialize and parse again inline SVG files
* `#607 <https://github.com/Kozea/WeasyPrint/issues/607>`_:
  Correctly handle whitespaces in bookmark labels
* `#1094 <https://github.com/Kozea/WeasyPrint/issues/1094>`_:
  Fix column height with ``column-span`` content
* `#1473 <https://github.com/Kozea/WeasyPrint/issues/1473>`_:
  Fix absolutely positioned boxes in duplicated pages
* `#1491 <https://github.com/Kozea/WeasyPrint/issues/1491>`_:
  Fix ``target-counter`` attribute in flex items
* `#1515 <https://github.com/Kozea/WeasyPrint/issues/1515>`_,
  `#1508 <https://github.com/Kozea/WeasyPrint/issues/1508>`_:
  Don’t draw empty glyphs
* `#1499 <https://github.com/Kozea/WeasyPrint/issues/1499>`_:
  Don’t crash when font size is really small

Documentation:

* `#1519 <https://github.com/Kozea/WeasyPrint/issues/1519>`_:
  Fix typo

Packaging:

* The source package does not include a ``setup.py`` file anymore. You can find
  more information about this in
  `issue #1410 <https://github.com/Kozea/WeasyPrint/issues/1410>`_.

Contirbutors:

* Guillaume Ayoub
* Lucie Anglade
* Colin Kinloch
* aschmitz
* Pablo González
* Rian McGuire

Backers and sponsors:

* Grip Angebotssoftware
* Manuel Barkhau
* SimonSoft
* Menutech
* KontextWork
* Crisp BV
* Maykin Media
* René Fritz
* Simon Sapin
* NCC Group
* Nathalie Gutton
* Andreas Zettl
* Tom Pohl
* Des images et des mots
* Moritz Mahringer
* Florian Demmer
* Yanal-Yves Fargialla
* Gábor
* Piotr Horzycki


Version 53.4
------------

Released on 2021-11-14.

Bug fixes:

* `#1446 <https://github.com/Kozea/WeasyPrint/issues/1446>`_:
  Fix background on pages with a bleed property
* `#1455 <https://github.com/Kozea/WeasyPrint/issues/1455>`_:
  Use SVG width/height as inner size when no viewBox is given
* `#1469 <https://github.com/Kozea/WeasyPrint/issues/1469>`_:
  Only enable letter- and word-spacing when needed
* `#1471 <https://github.com/Kozea/WeasyPrint/issues/1471>`_:
  Don’t display inputs with "hidden" type
* `#1485 <https://github.com/Kozea/WeasyPrint/issues/1485>`_:
  Allow quotes in url() syntax for SVG,
  Use better approximations for font ascent and descent values in SVG
* `#1486 <https://github.com/Kozea/WeasyPrint/issues/1486>`_:
  Fix images embedded from multiple pages
* `#1489 <https://github.com/Kozea/WeasyPrint/issues/1489>`_:
  Use a better hash for fonts to avoid collisions
* `abd54c4 <https://github.com/Kozea/WeasyPrint/commit/abd54c4>`_:
  Set SVG ratio when width and height are 0

Contributors:

* Guillaume Ayoub
* Lucie Anglade

Backers and sponsors:

* Grip Angebotssoftware
* SimonSoft
* Menutech
* Manuel Barkhau
* Simon Sapin
* KontextWork
* René Fritz
* Maykin Media
* NCC Group
* Crisp BV
* Des images et des mots
* Andreas Zettl
* Nathalie Gutton
* Tom Pohl
* Moritz Mahringer
* Florian Demmer
* Yanal-Yves Fargialla
* G. Allard
* Gábor


Version 53.3
------------

Released on 2021-09-10.

Bug fixes:

* `#1431 <https://github.com/Kozea/WeasyPrint/issues/1431>`_,
  `#1440 <https://github.com/Kozea/WeasyPrint/issues/1440>`_:
  Fix crashes and malformed PDF files
* `#1430 <https://github.com/Kozea/WeasyPrint/issues/1430>`_:
  Handle cx and cy in SVG rotations
* `#1436 <https://github.com/Kozea/WeasyPrint/pull/1436>`_:
  Fix marker-start being drawn on mid vertices

Contributors:

* Guillaume Ayoub
* Rian McGuire
* Lucie Anglade

Backers and sponsors:

* Grip Angebotssoftware
* SimonSoft
* Menutech
* Manuel Barkhau
* Simon Sapin
* KontextWork
* René Fritz
* Maykin Media
* NCC Group
* Des images et des mots
* Andreas Zettl
* Nathalie Gutton
* Tom Pohl
* Moritz Mahringer
* Florian Demmer
* Yanal-Yves Fargialla


Version 53.2
------------

Released on 2021-08-27.

New features:

* `#1428 <https://github.com/Kozea/WeasyPrint/issues/1428>`_:
  Re-add the ``make_bookmark_tree()`` method

Bug fixes:

* `#1429 <https://github.com/Kozea/WeasyPrint/issues/1429>`_:
  Fix package deployed on PyPI

Contributors:

* Guillaume Ayoub

Backers and sponsors:

* Grip Angebotssoftware
* PDF Blocks
* SimonSoft
* Menutech
* Manuel Barkhau
* Simon Sapin
* KontextWork
* René Fritz
* Maykin Media
* NCC Group
* Des images et des mots
* Andreas Zettl
* Nathalie Gutton
* Tom Pohl
* Moritz Mahringer
* Florian Demmer
* Yanal-Yves Fargialla


Version 53.1
------------

Released on 2021-08-22.

Bug fixes:

* `#1409 <https://github.com/Kozea/WeasyPrint/issues/1409>`_:
  Don’t crash when leaders are in floats
* `#1414 <https://github.com/Kozea/WeasyPrint/issues/1414>`_:
  Embed images once
* `#1417 <https://github.com/Kozea/WeasyPrint/issues/1417>`_:
  Fix crash with SVG intrinsic ratio

Documentation:

* `#1422 <https://github.com/Kozea/WeasyPrint/issues/1422>`_:
  Include ``weasyprint.tools`` removal in documentation

Contributors:

* Guillaume Ayoub

Backers and sponsors:

* Grip Angebotssoftware
* PDF Blocks
* SimonSoft
* Menutech
* Manuel Barkhau
* Simon Sapin
* KontextWork
* René Fritz
* Maykin Media
* NCC Group
* Des images et des mots
* Andreas Zettl
* Nathalie Gutton
* Tom Pohl
* Moritz Mahringer
* Florian Demmer
* Yanal-Yves Fargialla


Version 53.0
------------

Released on 2021-07-31.

This version also includes the changes from unstable b1 and b2 versions listed
below.

Dependencies:

* Pango 1.44.0+ is now needed.
* pydyf 0.0.3+ is now needed.
* fontTools 4.0.0+ is now needed.
* html5lib 1.0.1+ is now needed.

API changes:

* ``FontConfiguration`` is now in the ``weasyprint.text.fonts`` module.
* ``--format`` and ``--resolution`` options have been deprecated, PDF is the
  only output format supported.
* ``--optimize-images`` option has been deprecated and replaced by
  ``--optimize-size``, allowing ``images``, ``fonts``, ``all`` and ``none``
  values.
* ``weasyprint.tools`` have been removed.
* ``Document.resolve_links``, ``Document.make_bookmark_tree`` and
  ``Document.add_hyperlinks`` have been removed.

Performance:

* Improve image management

New features:

* `#1374 <https://github.com/Kozea/WeasyPrint/issues/1374>`_:
  Support basic "clipPath" in SVG

Bug fixes:

* `#1369 <https://github.com/Kozea/WeasyPrint/issues/1369>`_:
  Render use path in SVG
* `#1370 <https://github.com/Kozea/WeasyPrint/issues/1370>`_:
  Fix fill color on use path in SVG
* `#1371 <https://github.com/Kozea/WeasyPrint/issues/1371>`_:
  Handle stroke-opacity and fill-opacity
* `#1378 <https://github.com/Kozea/WeasyPrint/issues/1378>`_:
  Fix crash with borders whose widths are in em
* `#1394 <https://github.com/Kozea/WeasyPrint/issues/1394>`_:
  Fix crash on draw_pattern
* `#880 <https://github.com/Kozea/WeasyPrint/issues/880>`_:
  Handle stacking contexts put in contexts by previous generations
* `#1386 <https://github.com/Kozea/WeasyPrint/issues/1386>`_:
  Catch font subsetting errors
* `#1403 <https://github.com/Kozea/WeasyPrint/issues/1403>`_:
  Fix how x and y attributes are handled in SVG
* `#1399 <https://github.com/Kozea/WeasyPrint/issues/1399>`_,
  `#1401 <https://github.com/Kozea/WeasyPrint/pull/1401>`_:
  Don’t crash when use tags reference non-existing element
* `#1393 <https://github.com/Kozea/WeasyPrint/issues/1393>`_:
  Handle font collections
* `#1408 <https://github.com/Kozea/WeasyPrint/issues/1408>`_:
  Handle x and y attributes in use tags

Documentation:

* `#1391 <https://github.com/Kozea/WeasyPrint/issues/1391>`_,
  `#1405 <https://github.com/Kozea/WeasyPrint/pull/1405>`_:
  Add documentation for installation

Contributors:

* Guillaume Ayoub
* Lucie Anglade
* Pelle Bo Regener
* aschmitz
* John Jackson
* Felix Schwarz
* Syrus Dark
* Christoph Päper

Backers and sponsors:

* OpenEdition
* Grip Angebotssoftware
* Simonsoft
* PDF Blocks
* Menutech
* Manuel Barkhau
* print-css.rocks
* Simon Sapin
* KontextWork
* René Fritz
* Maykin Media
* Nathalie Gutton
* Andreas Zettl
* Tom Pohl
* NCC Group
* Moritz Mahringer
* Florian Demmer
* Des images et des mots
* Mohammed Y. Alnajdi
* Yanal-Yves Fargialla
* Yevhenii Hyzyla


Version 53.0b2
--------------

Released on 2021-05-30.

**This version is experimental, don't use it in production. If you find bugs,
please report them!**

New features:

* `#359 <https://github.com/Kozea/WeasyPrint/issues/359>`_:
  Embed full sets of fonts in PDF

Bug fixes:

* `#1345 <https://github.com/Kozea/WeasyPrint/issues/1345>`_:
  Fix position of SVG use tags
* `#1346 <https://github.com/Kozea/WeasyPrint/pull/1346>`_:
  Handle "stroke-dasharray: none"
* `#1352 <https://github.com/Kozea/WeasyPrint/issues/1352>`_,
  `#1358 <https://github.com/Kozea/WeasyPrint/pull/1358>`_:
  Sort link target identifiers
* `#1357 <https://github.com/Kozea/WeasyPrint/issues/1357>`_:
  Fix font information
* `#1362 <https://github.com/Kozea/WeasyPrint/issues/1362>`_:
  Handle visibility and display properties in SVG
* `#1365 <https://github.com/Kozea/WeasyPrint/issues/1365>`_:
  Cascade inherited attributes for use tags
* `#1366 <https://github.com/Kozea/WeasyPrint/issues/1366>`_:
  Correctly handle style attributes in SVG
* `#1367 <https://github.com/Kozea/WeasyPrint/issues/1367>`_:
  Include line stroke in box bounding

Documentation:

* `#1341 <https://github.com/Kozea/WeasyPrint/pull/1341>`_:
  Fix typos

Contributors:

* Guillaume Ayoub
* aschmitz
* John Jackson
* Lucie Anglade
* Pelle Bo Regener

Backers and sponsors:

* OpenEdition
* print-css.rocks
* Simonsoft
* PDF Blocks
* Menutech
* Manuel Barkhau
* Simon Sapin
* Grip Angebotssoftware
* KontextWork
* René Fritz
* Nathalie Gutton
* Andreas Zettl
* Tom Pohl
* Maykin Media
* Moritz Mahringer
* Florian Demmer
* Mohammed Y. Alnajdi
* NCC Group
* Des images et des mots
* Yanal-Yves Fargialla
* Yevhenii Hyzyla


Version 53.0b1
--------------

Released on 2021-04-22.

**This version is experimental, don't use it in production. If you find bugs,
please report them!**

Dependencies:

* This version uses its own PDF generator instead of Cairo. Rendering may be
  different for text, gradients, SVG images…
* Packaging is now done with Flit.

New features:

* `#1328 <https://github.com/Kozea/WeasyPrint/pull/1328>`_:
  Add ISO and JIS paper sizes
* `#1309 <https://github.com/Kozea/WeasyPrint/pull/1309>`_:
  Leader support, with financial support from Simonsoft

Bug fixes:

* `#504 <https://github.com/Kozea/WeasyPrint/issues/504>`_:
  Fix rendering bugs with PDF gradients
* `#606 <https://github.com/Kozea/WeasyPrint/issues/606>`_:
  Fix rounding errors on PDF dimensions
* `#1264 <https://github.com/Kozea/WeasyPrint/issues/1264>`_:
  Include witdh/height when calculating auto margins of absolute boxes
* `#1191 <https://github.com/Kozea/WeasyPrint/issues/1191>`_:
  Don’t try to get an earlier page break between columns
* `#1235 <https://github.com/Kozea/WeasyPrint/issues/1235>`_:
  Include padding, border, padding when calculating inline-block width
* `#1199 <https://github.com/Kozea/WeasyPrint/issues/1199>`_:
  Fix kerning issues with small fonts

Documentation:

* `#1298 <https://github.com/Kozea/WeasyPrint/pull/1298>`_:
  Rewrite documentation

Contributors:

* Guillaume Ayoub
* Lucie Anglade
* Felix Schwarz
* Syrus Dark
* Christoph Päper

Backers and sponsors:

* Simonsoft
* PDF Blocks
* Menutech
* Manuel Barkhau
* Simon Sapin
* Nathalie Gutton
* Andreas Zettl
* René Fritz
* Tom Pohl
* KontextWork
* Moritz Mahringer
* Florian Demmer
* Maykin Media
* Yanal-Yves Fargialla
* Des images et des mots
* Yevhenii Hyzyla


Version 52.5
------------

Released on 2021-04-17.

Bug fixes:

* `#1336 <https://github.com/Kozea/WeasyPrint/issues/1336>`_:
  Fix text breaking exception
* `#1318 <https://github.com/Kozea/WeasyPrint/issues/1318>`_:
  Fix @font-face rules with Pango 1.48.3+

Contributors:

* Guillaume Ayoub

Backers and sponsors:

* Simonsoft
* PDF Blocks
* Menutech
* Manuel Barkhau
* Simon Sapin
* Nathalie Gutton
* Andreas Zettl
* René Fritz
* Tom Pohl
* KontextWork
* Moritz Mahringer
* Florian Demmer
* Maykin Media
* Yanal-Yves Fargialla
* Des images et des mots
* Yevhenii Hyzyla


Version 52.4
------------

Released on 2021-03-11.

Bug fixes:

* `#1304 <https://github.com/Kozea/WeasyPrint/issues/1304>`_:
  Don’t try to draw SVG files with no size
* `ece5f066 <https://github.com/Kozea/WeasyPrint/commit/ece5f066>`_:
  Avoid crash on last word detection
* `4ee42e48 <https://github.com/Kozea/WeasyPrint/commit/4ee42e48>`_:
  Remove last word before ellipses when hyphenated

Contributors:

* Guillaume Ayoub

Backers and sponsors:

* PDF Blocks
* Simonsoft
* Menutech
* Simon Sapin
* Manuel Barkhau
* Andreas Zettl
* Nathalie Gutton
* Tom Pohl
* René Fritz
* Moritz Mahringer
* Florian Demmer
* KontextWork
* Michele Mostarda


Version 52.3
------------

Released on 2021-03-02.

Bug fixes:

* `#1299 <https://github.com/Kozea/WeasyPrint/issues/1299>`_:
  Fix imports with url() and quotes

New features:

* `#1300 <https://github.com/Kozea/WeasyPrint/pull/1300>`_:
  Add support of line-clamp, with financial support from
  expert Germany

Contributors:

* Guillaume Ayoub
* Lucie Anglade

Backers and sponsors:

* PDF Blocks
* Simonsoft
* Menutech
* Simon Sapin
* Manuel Barkhau
* Andreas Zettl
* Nathalie Gutton
* Tom Pohl
* Moritz Mahringer
* Florian Demmer
* KontextWork
* Michele Mostarda


Version 52.2
------------

Released on 2020-12-06.

Bug fixes:

* `238e214 <https://github.com/Kozea/WeasyPrint/commit/238e214>`_:
  Fix URL handling with tinycss2
* `#1248 <https://github.com/Kozea/WeasyPrint/issues/1248>`_:
  Include missing test data
* `#1254 <https://github.com/Kozea/WeasyPrint/issues/1254>`_:
  Top margins removed from children when tables are displayed on multiple pages
* `#1250 <https://github.com/Kozea/WeasyPrint/issues/1250>`_:
  Correctly draw borders on the last line of split tables
* `a6f9c80 <https://github.com/Kozea/WeasyPrint/commit/a6f9c80>`_:
  Add a nice gif to please gdk-pixbuf 2.42.0

Contributors:

* Guillaume Ayoub
* Lucie Anglade
* Felix Schwarz

Backers and sponsors:

* PDF Blocks
* Simonsoft
* Menutech
* Simon Sapin
* Nathalie Gutton
* Andreas Zetti
* Tom Pohl
* Florian Demmer
* Moritz Mahringer


Version 52.1
------------

Released on 2020-11-02.

Bug fixes:

* `238e214 <https://github.com/Kozea/WeasyPrint/commit/238e214>`_:
  Fix URL handling with tinycss2

Contributors:

* Guillaume Ayoub

Backers and sponsors:

* Simonsoft
* Simon Sapin
* Nathalie Gutton
* Andreas Zettl
* Florian Demmer
* Moritz Mahringer


Version 52
----------

Released on 2020-10-29.

Dependencies:

* Python 3.6+ is now needed, Python 3.5 is not supported anymore
* WeasyPrint now depends on Pillow

New features:

* `#1019 <https://github.com/Kozea/WeasyPrint/issues/1019>`_:
  Implement ``counter-set``
* `#1080 <https://github.com/Kozea/WeasyPrint/issues/1080>`_:
  Don’t display ``template`` tags
* `#1210 <https://github.com/Kozea/WeasyPrint/pull/1210>`_:
  Use ``download`` attribute in ``a`` tags for attachment's filename
* `#1206 <https://github.com/Kozea/WeasyPrint/issues/1206>`_:
  Handle strings in ``list-style-type``
* `#1165 <https://github.com/Kozea/WeasyPrint/pull/1165>`_:
  Add support for concatenating ``var()`` functions in ``content`` declarations
* `c56b96b <https://github.com/Kozea/WeasyPrint/commit/c56b96b>`_:
  Add an option to optimize embedded images size, with financial support from
  Hashbang
* `#969 <https://github.com/Kozea/WeasyPrint/issues/969>`_:
  Add an image cache that can be shared between documents, with financial
  support from Hashbang

Bug fixes:

* `#1141 <https://github.com/Kozea/WeasyPrint/pull/1141>`_:
  Don’t clip page margins on account of ``body`` overflow
* `#1000 <https://github.com/Kozea/WeasyPrint/issues/1000>`_:
  Don’t apply ``text-indent`` twice on inline blocks
* `#1051 <https://github.com/Kozea/WeasyPrint/issues/1051>`_:
  Avoid random line breaks
* `#1120 <https://github.com/Kozea/WeasyPrint/pull/1120>`_:
  Gather target counters in page margins
* `#1110 <https://github.com/Kozea/WeasyPrint/issues/1110>`_:
  Handle most cases for boxes avoiding floats in rtl containers, with financial
  support from Innovative Software
* `#1111 <https://github.com/Kozea/WeasyPrint/issues/1111>`_:
  Fix horizontal position of last rtl line, with financial support from
  Innovative Software
* `#1114 <https://github.com/Kozea/WeasyPrint/issues/1114>`_:
  Fix bug with transparent borders in tables
* `#1146 <https://github.com/Kozea/WeasyPrint/pull/1146>`_:
  Don’t gather bookmarks twice for blocks that are displayed on two pages
* `#1237 <https://github.com/Kozea/WeasyPrint/issues/1237>`_:
  Use fallback fonts on unsupported WOFF2 and WOFF fonts
* `#1025 <https://github.com/Kozea/WeasyPrint/issues/1025>`_:
  Don’t insert the same layout attributes multiple times
* `#1027 <https://github.com/Kozea/WeasyPrint/issues/1027>`_:
  Don’t try to break tables after the header or before the footer
* `#1050 <https://github.com/Kozea/WeasyPrint/issues/1050>`_:
  Don’t crash on absolute SVG files with no intrinsic size
* `#1204 <https://github.com/Kozea/WeasyPrint/issues/1204>`_:
  Fix a crash with a flexbox corner case
* `#1030 <https://github.com/Kozea/WeasyPrint/pull/1030>`_:
  Fix frozen builds
* `#1089 <https://github.com/Kozea/WeasyPrint/pull/1089>`_:
  Fix Pyinstaller builds
* `#1216 <https://github.com/Kozea/WeasyPrint/pull/1213>`_:
  Fix embedded files
* `#1225 <https://github.com/Kozea/WeasyPrint/pull/1225>`_:
  Initial support of RTL direction in flexbox layout

Documentation:

* `#1149 <https://github.com/Kozea/WeasyPrint/issues/1149>`_:
  Add the ``--quiet`` CLI option in the documentation
* `#1061 <https://github.com/Kozea/WeasyPrint/pull/1061>`_:
  Update install instructions on Windows

Tests:

* `#1209 <https://github.com/Kozea/WeasyPrint/pull/1209>`_:
  Use GitHub Actions instead of Travis

Contributors:

* Guillaume Ayoub
* Lucie Anglade
* Tontyna
* Mohammed Y. Alnajdi
* Mike Voets
* Bjarni Þórisson
* Balázs Dukai
* Bart Broere
* Endalkachew
* Felix Schwarz
* Julien Sanchez
* Konstantin Alekseev
* Nicolas Hart
* Nikolaus Schlemm
* Thomas J. Lampoltshammer
* mPyth
* nempoBu4
* saddy001

Backers and sponsors:

* Hashbang
* Innovative Software
* Screenbreak
* Simon Sapin
* Lisa Warshaw
* Nathalie Gutton
* Andreas Zettl
* Florian Demmer
* Moritz Mahringer


Version 51
----------

Released on 2019-12-23.

Dependencies:

* Pyphen 0.9.1+ is now needed

New features:

* `#882 <https://github.com/Kozea/WeasyPrint/pull/882>`_:
  Add support of ``element()`` and ``running()``
* `#972 <https://github.com/Kozea/WeasyPrint/pull/972>`_:
  Add HTML element to Box class
* `7a4d6f8 <https://github.com/Kozea/WeasyPrint/commit/7a4d6f8>`_:
  Support ``larger`` and ``smaller`` values for ``font-size``

Bug fixes:

* `#960 <https://github.com/Kozea/WeasyPrint/pull/960>`_:
  Fix how fonts used for macOS tests are installed
* `#956 <https://github.com/Kozea/WeasyPrint/pull/956>`_:
  Fix various crashes due to line breaking bugs
* `#983 <https://github.com/Kozea/WeasyPrint/issues/983>`_:
  Fix typo in variable name
* `#975 <https://github.com/Kozea/WeasyPrint/pull/975>`_:
  Don’t crash when ``string-set`` is set to ``none``
* `#998 <https://github.com/Kozea/WeasyPrint/pull/998>`_:
  Keep font attributes when text lines are modified
* `#1005 <https://github.com/Kozea/WeasyPrint/issues/1005>`_:
  Don’t let presentational hints add decorations on tables with no borders
* `#974 <https://github.com/Kozea/WeasyPrint/pull/974>`_:
  Don’t crash on improper ``var()`` values
* `#1012 <https://github.com/Kozea/WeasyPrint/pull/1012>`_:
  Fix rendering of header and footer for empty tables
* `#1013 <https://github.com/Kozea/WeasyPrint/issues/1013>`_:
  Avoid quadratic time relative to tree depth when setting page names

Contributors:

- Lucie Anglade
- Guillaume Ayoub
- Guillermo Bonvehí
- Holger Brunn
- Felix Schwarz
- Tontyna


Version 50
----------

Released on 2019-09-19.

New features:

* `#209 <https://github.com/Kozea/WeasyPrint/issues/209>`_:
  Make ``break-*`` properties work inside tables
* `#661 <https://github.com/Kozea/WeasyPrint/issues/661>`_:
  Make blocks with ``overflow: auto`` grow to include floating children

Bug fixes:

* `#945 <https://github.com/Kozea/WeasyPrint/issues/945>`_:
  Don't break pages between a list item and its marker
* `#727 <https://github.com/Kozea/WeasyPrint/issues/727>`_:
  Avoid tables lost between pages
* `#831 <https://github.com/Kozea/WeasyPrint/issues/831>`_:
  Ignore auto margins on flex containers
* `#923 <https://github.com/Kozea/WeasyPrint/issues/923>`_:
  Fix a couple of crashes when splitting a line twice
* `#896 <https://github.com/Kozea/WeasyPrint/issues/896>`_:
  Fix skip stack order when using a reverse flex direction

Contributors:

- Lucie Anglade
- Guillaume Ayoub


Version 49
----------

Released on 2019-09-11.

Performance:

* Speed and memory use have been largely improved.

New features:

* `#700 <https://github.com/Kozea/WeasyPrint/issues/700>`_:
  Handle ``::marker`` pseudo-selector
* `135dc06c <https://github.com/Kozea/WeasyPrint/commit/135dc06c>`_:
  Handle ``recto`` and ``verso`` parameters for page breaks
* `#907 <https://github.com/Kozea/WeasyPrint/pull/907>`_:
  Provide a clean way to build layout contexts

Bug fixes:

* `#937 <https://github.com/Kozea/WeasyPrint/issues/937>`_:
  Fix rendering of tables with empty lines and rowspans
* `#897 <https://github.com/Kozea/WeasyPrint/issues/897>`_:
  Don't crash when small columns are wrapped in absolute blocks
* `#913 <https://github.com/Kozea/WeasyPrint/issues/913>`_:
  Fix a test about gradient colors
* `#924 <https://github.com/Kozea/WeasyPrint/pull/924>`_:
  Fix title for document with attachments
* `#917 <https://github.com/Kozea/WeasyPrint/issues/917>`_:
  Fix tests with Pango 1.44
* `#919 <https://github.com/Kozea/WeasyPrint/issues/919>`_:
  Fix padding and margin management for column flex boxes
* `#901 <https://github.com/Kozea/WeasyPrint/issues/901>`_:
  Fix width of replaced boxes with no intrinsic width
* `#906 <https://github.com/Kozea/WeasyPrint/issues/906>`_:
  Don't respect table cell width when content doesn't fit
* `#927 <https://github.com/Kozea/WeasyPrint/pull/927>`_:
  Don't use deprecated ``logger.warn`` anymore
* `a8662794 <https://github.com/Kozea/WeasyPrint/commit/a8662794>`_:
  Fix margin collapsing between caption and table wrapper
* `87d9e84f <https://github.com/Kozea/WeasyPrint/commit/87d9e84f>`_:
  Avoid infinite loops when rendering columns
* `789b80e6 <https://github.com/Kozea/WeasyPrint/commit/789b80e6>`_:
  Only use in flow children to set columns height
* `615e298a <https://github.com/Kozea/WeasyPrint/commit/615e298a>`_:
  Don't include floating elements each time we try to render a column
* `48d8632e <https://github.com/Kozea/WeasyPrint/commit/48d8632e>`_:
  Avoid not in flow children to compute column height
* `e7c452ce <https://github.com/Kozea/WeasyPrint/commit/e7c452ce>`_:
  Fix collapsing margins for columns
* `fb0887cf <https://github.com/Kozea/WeasyPrint/commit/fb0887cf>`_:
  Fix crash when using currentColor in gradients
* `f66df067 <https://github.com/Kozea/WeasyPrint/commit/f66df067>`_:
  Don't crash when using ex units in word-spacing in letter-spacing
* `c790ff20 <https://github.com/Kozea/WeasyPrint/commit/c790ff20>`_:
  Don't crash when properties needing base URL use var functions
* `d63eac31 <https://github.com/Kozea/WeasyPrint/commit/d63eac31>`_:
  Don't crash with object-fit: non images with no intrinsic size

Documentation:

* `#900 <https://github.com/Kozea/WeasyPrint/issues/900>`_:
  Add documentation about semantic versioning
* `#692 <https://github.com/Kozea/WeasyPrint/issues/692>`_:
  Add a snippet about PDF magnification
* `#899 <https://github.com/Kozea/WeasyPrint/pull/899>`_:
  Add .NET wrapper link
* `#893 <https://github.com/Kozea/WeasyPrint/pull/893>`_:
  Fixed wrong nested list comprehension example
* `#902 <https://github.com/Kozea/WeasyPrint/pull/902>`_:
  Add ``state`` to the ``make_bookmark_tree`` documentation
* `#921 <https://github.com/Kozea/WeasyPrint/pull/921>`_:
  Fix typos in the documentation
* `#328 <https://github.com/Kozea/WeasyPrint/issues/328>`_:
  Add CSS sample for forms

Contributors:

- Lucie Anglade
- Guillaume Ayoub
- Raphael Gaschignard
- Stani
- Szmen
- Thomas Dexter
- Tontyna


Version 48
----------

Released on 2019-07-08.

Dependencies:

* CairoSVG 2.4.0+ is now needed

New features:

* `#891 <https://github.com/Kozea/WeasyPrint/pull/891>`_:
  Handle ``text-overflow``
* `#878 <https://github.com/Kozea/WeasyPrint/pull/878>`_:
  Handle ``column-span``
* `#855 <https://github.com/Kozea/WeasyPrint/pull/855>`_:
  Handle all the ``text-decoration`` features
* `#238 <https://github.com/Kozea/WeasyPrint/issues/238>`_:
  Don't repeat background images when it's not needed
* `#875 <https://github.com/Kozea/WeasyPrint/issues/875>`_:
  Handle ``object-fit`` and ``object-position``
* `#870 <https://github.com/Kozea/WeasyPrint/issues/870>`_:
  Handle ``bookmark-state``

Bug fixes:

* `#686 <https://github.com/Kozea/WeasyPrint/issues/686>`_:
  Fix column balance when children are not inline
* `#885 <https://github.com/Kozea/WeasyPrint/issues/885>`_:
  Actually use the content box to resolve flex items percentages
* `#867 <https://github.com/Kozea/WeasyPrint/issues/867>`_:
  Fix rendering of KaTeX output, including (1) set row baseline of tables when
  no cells are baseline-aligned, (2) set baseline for inline tables, (3) don't
  align lines larger than their parents, (4) force CairoSVG to respect image
  size defined by CSS.
* `#873 <https://github.com/Kozea/WeasyPrint/issues/873>`_:
  Set a minimum height for empty list elements with outside marker
* `#811 <https://github.com/Kozea/WeasyPrint/issues/811>`_:
  Don't use translations to align flex items
* `#851 <https://github.com/Kozea/WeasyPrint/issues/851>`_,
  `#860 <https://github.com/Kozea/WeasyPrint/issues/860>`_:
  Don't cut pages when content overflows a very little bit
* `#862 <https://github.com/Kozea/WeasyPrint/issues/862>`_:
  Don't crash when using UTC dates in metadata

Documentation:

* `#854 <https://github.com/Kozea/WeasyPrint/issues/854>`_:
  Add a "Tips & Tricks" section

Contributors:

- Gabriel Corona
- Guillaume Ayoub
- Manuel Barkhau
- Nathan de Maestri
- Lucie Anglade
- theopeek


Version 47
----------

Released on 2019-04-12.

New features:

* `#843 <https://github.com/Kozea/WeasyPrint/pull/843>`_:
  Handle CSS variables
* `#846 <https://github.com/Kozea/WeasyPrint/pull/846>`_:
  Handle ``:nth()`` page selector
* `#847 <https://github.com/Kozea/WeasyPrint/pull/847>`_:
  Allow users to use a custom SSL context for HTTP requests

Bug fixes:

* `#797 <https://github.com/Kozea/WeasyPrint/issues/797>`_:
  Fix underlined justified text
* `#836 <https://github.com/Kozea/WeasyPrint/issues/836>`_:
  Fix crash when flex items are replaced boxes
* `#835 <https://github.com/Kozea/WeasyPrint/issues/835>`_:
  Fix ``margin-break: auto``


Version 46
----------

Released on 2019-03-20.

New features:

* `#771 <https://github.com/Kozea/WeasyPrint/issues/771>`_:
  Handle ``box-decoration-break``
* `#115 <https://github.com/Kozea/WeasyPrint/issues/115>`_:
  Handle ``margin-break``
* `#821 <https://github.com/Kozea/WeasyPrint/issues/821>`_:
  Continuous integration includes tests on Windows

Bug fixes:

* `#765 <https://github.com/Kozea/WeasyPrint/issues/765>`_,
  `#754 <https://github.com/Kozea/WeasyPrint/issues/754>`_,
  `#800 <https://github.com/Kozea/WeasyPrint/issues/800>`_:
  Fix many crashes related to the flex layout
* `#783 <https://github.com/Kozea/WeasyPrint/issues/783>`_:
  Fix a couple of crashes with strange texts
* `#827 <https://github.com/Kozea/WeasyPrint/pull/827>`_:
  Named strings and counters are case-sensitive
* `#823 <https://github.com/Kozea/WeasyPrint/pull/823>`_:
  Shrink min/max-height/width according to box-sizing
* `#728 <https://github.com/Kozea/WeasyPrint/issues/728>`_,
  `#171 <https://github.com/Kozea/WeasyPrint/issues/171>`_:
  Don't crash when fixed boxes are nested
* `#610 <https://github.com/Kozea/WeasyPrint/issues/610>`_,
  `#828 <https://github.com/Kozea/WeasyPrint/issues/828>`_:
  Don't crash when preformatted text lines end with a space
* `#808 <https://github.com/Kozea/WeasyPrint/issues/808>`_,
  `#387 <https://github.com/Kozea/WeasyPrint/issues/387>`_:
  Fix position of some images
* `#813 <https://github.com/Kozea/WeasyPrint/issues/813>`_:
  Don't crash when long preformatted text lines end with ``\n``

Documentation:

* `#815 <https://github.com/Kozea/WeasyPrint/pull/815>`_:
  Add documentation about custom ``url_fetcher``


Version 45
----------

Released on 2019-02-20.

WeasyPrint now has a `code of conduct
<https://github.com/Kozea/WeasyPrint/blob/master/CODE_OF_CONDUCT.rst>`_.

A new website has been launched, with beautiful and useful graphs about speed
and memory use across versions: check `WeasyPerf
<https://kozea.github.io/WeasyPerf/index.html>`_.

Dependencies:

* Python 3.5+ is now needed, Python 3.4 is not supported anymore

Bug fixes:

* `#798 <https://github.com/Kozea/WeasyPrint/pull/798>`_:
  Prevent endless loop and index out of range in pagination
* `#767 <https://github.com/Kozea/WeasyPrint/issues/767>`_:
  Add a ``--quiet`` CLI parameter
* `#784 <https://github.com/Kozea/WeasyPrint/pull/784>`_:
  Fix library loading on Alpine
* `#791 <https://github.com/Kozea/WeasyPrint/pull/791>`_:
  Use path2url in tests for Windows
* `#789 <https://github.com/Kozea/WeasyPrint/pull/789>`_:
  Add LICENSE file to distributed sources
* `#788 <https://github.com/Kozea/WeasyPrint/pull/788>`_:
  Fix pending references
* `#780 <https://github.com/Kozea/WeasyPrint/issues/780>`_:
  Don't draw patterns for empty page backgrounds
* `#774 <https://github.com/Kozea/WeasyPrint/issues/774>`_:
  Don't crash when links include quotes
* `#637 <https://github.com/Kozea/WeasyPrint/issues/637>`_:
  Fix a problem with justified text
* `#763 <https://github.com/Kozea/WeasyPrint/pull/763>`_:
  Launch tests with Python 3.7
* `#704 <https://github.com/Kozea/WeasyPrint/issues/704>`_:
  Fix a corner case with tables
* `#804 <https://github.com/Kozea/WeasyPrint/pull/804>`_:
  Don't logger handlers defined before importing WeasyPrint
* `#109 <https://github.com/Kozea/WeasyPrint/issues/109>`_,
  `#748 <https://github.com/Kozea/WeasyPrint/issues/748>`_:
  Don't include punctuation for hyphenation
* `#770 <https://github.com/Kozea/WeasyPrint/issues/770>`_:
  Don't crash when people use uppercase words from old-fashioned Microsoft
  fonts in tables, especially when there's an 5th column
* Use a `separate logger
  <https://weasyprint.readthedocs.io/en/latest/tutorial.html#logging>`_ to
  report the rendering process
* Add a ``--debug`` CLI parameter and set debug level for unknown prefixed CSS
  properties
* Define minimal versions of Python and setuptools in setup.cfg

Documentation:

* `#796 <https://github.com/Kozea/WeasyPrint/pull/796>`_:
  Fix a small typo in the tutorial
* `#792 <https://github.com/Kozea/WeasyPrint/pull/792>`_:
  Document no alignment character support
* `#773 <https://github.com/Kozea/WeasyPrint/pull/773>`_:
  Fix phrasing in Hacking section
* `#402 <https://github.com/Kozea/WeasyPrint/issues/402>`_:
  Add a paragraph about fontconfig error
* `#764 <https://github.com/Kozea/WeasyPrint/pull/764>`_:
  Fix list of dependencies for Alpine
* Fix API documentation of HTML and CSS classes


Version 44
----------

Released on 2018-12-29.

Bug fixes:

* `#742 <https://github.com/Kozea/WeasyPrint/issues/742>`_:
  Don't crash during PDF generation when locale uses commas as decimal separator
* `#746 <https://github.com/Kozea/WeasyPrint/issues/746>`_:
  Close file when reading VERSION
* Improve speed and memory usage for long texts.

Documentation:

* `#733 <https://github.com/Kozea/WeasyPrint/pull/733>`_:
  Small documentation fixes
* `#735 <https://github.com/Kozea/WeasyPrint/pull/735>`_:
  Fix broken links in NEWS.rst


Version 43
----------

Released on 2018-11-09.

Bug fixes:

* `#726 <https://github.com/Kozea/WeasyPrint/issues/726>`_:
  Make empty strings clear previous values of named strings
* `#729 <https://github.com/Kozea/WeasyPrint/issues/729>`_:
  Include tools in packaging

This version also includes the changes from unstable rc1 and rc2 versions
listed below.


Version 43rc2
-------------

Released on 2018-11-02.

**This version is experimental, don't use it in production. If you find bugs,
please report them!**

Bug fixes:

* `#706 <https://github.com/Kozea/WeasyPrint/issues/706>`_:
  Fix text-indent at the beginning of a page
* `#687 <https://github.com/Kozea/WeasyPrint/issues/687>`_:
  Allow query strings in file:// URIs
* `#720 <https://github.com/Kozea/WeasyPrint/issues/720>`_:
  Optimize minimum size calculation of long inline elements
* `#717 <https://github.com/Kozea/WeasyPrint/issues/717>`_:
  Display <details> tags as blocks
* `#691 <https://github.com/Kozea/WeasyPrint/issues/691>`_:
  Don't recalculate max content widths when distributing extra space for tables
* `#722 <https://github.com/Kozea/WeasyPrint/issues/722>`_:
  Fix bookmarks and strings set on images
* `#723 <https://github.com/Kozea/WeasyPrint/issues/723>`_:
  Warn users when string() is not used in page margin


Version 43rc1
-------------

Released on 2018-10-15.

**This version is experimental, don't use it in production. If you find bugs,
please report them!**

Dependencies:

* Python 3.4+ is now needed, Python 2.x is not supported anymore
* Cairo 1.15.4+ is now needed, but 1.10+ should work with missing features
  (such as links, outlines and metadata)
* Pdfrw is not needed anymore

New features:

* `Beautiful website <https://weasyprint.org>`_
* `#579 <https://github.com/Kozea/WeasyPrint/issues/579>`_:
  Initial support of flexbox
* `#592 <https://github.com/Kozea/WeasyPrint/pull/592>`_:
  Support @font-face on Windows
* `#306 <https://github.com/Kozea/WeasyPrint/issues/306>`_:
  Add a timeout parameter to the URL fetcher functions
* `#594 <https://github.com/Kozea/WeasyPrint/pull/594>`_:
  Split tests using modern pytest features
* `#599 <https://github.com/Kozea/WeasyPrint/pull/599>`_:
  Make tests pass on Windows
* `#604 <https://github.com/Kozea/WeasyPrint/pull/604>`_:
  Handle target counters and target texts
* `#631 <https://github.com/Kozea/WeasyPrint/pull/631>`_:
  Enable counter-increment and counter-reset in page context
* `#622 <https://github.com/Kozea/WeasyPrint/issues/622>`_:
  Allow pathlib.Path objects for HTML, CSS and Attachment classes
* `#674 <https://github.com/Kozea/WeasyPrint/issues/674>`_:
  Add extensive installation instructions for Windows

Bug fixes:

* `#558 <https://github.com/Kozea/WeasyPrint/issues/558>`_:
  Fix attachments
* `#565 <https://github.com/Kozea/WeasyPrint/issues/565>`_,
  `#596 <https://github.com/Kozea/WeasyPrint/issues/596>`_,
  `#539 <https://github.com/Kozea/WeasyPrint/issues/539>`_:
  Fix many PDF rendering, printing and compatibility problems
* `#614 <https://github.com/Kozea/WeasyPrint/issues/614>`_:
  Avoid crashes and endless loops caused by a Pango bug
* `#662 <https://github.com/Kozea/WeasyPrint/pull/662>`_:
  Fix warnings and errors when generating documentation
* `#666 <https://github.com/Kozea/WeasyPrint/issues/666>`_,
  `#685 <https://github.com/Kozea/WeasyPrint/issues/685>`_:
  Fix many table layout rendering problems
* `#680 <https://github.com/Kozea/WeasyPrint/pull/680>`_:
  Don't crash when there's no font available
* `#662 <https://github.com/Kozea/WeasyPrint/pull/662>`_:
  Fix support of some align values in tables


Version 0.42.3
--------------

Released on 2018-03-27.

Bug fixes:

* `#583 <https://github.com/Kozea/WeasyPrint/issues/583>`_:
  Fix floating-point number error to fix floating box layout
* `#586 <https://github.com/Kozea/WeasyPrint/issues/586>`_:
  Don't optimize resume_at when splitting lines with trailing spaces
* `#582 <https://github.com/Kozea/WeasyPrint/issues/582>`_:
  Fix table layout with no overflow
* `#580 <https://github.com/Kozea/WeasyPrint/issues/580>`_:
  Fix inline box breaking function
* `#576 <https://github.com/Kozea/WeasyPrint/issues/576>`_:
  Split replaced_min_content_width and replaced_max_content_width
* `#574 <https://github.com/Kozea/WeasyPrint/issues/574>`_:
  Respect text direction and don't translate rtl columns twice
* `#569 <https://github.com/Kozea/WeasyPrint/issues/569>`_:
  Get only first line's width of inline children to get linebox width


Version 0.42.2
--------------

Released on 2018-02-04.

Bug fixes:

* `#560 <https://github.com/Kozea/WeasyPrint/issues/560>`_:
  Fix a couple of crashes and endless loops when breaking lines.


Version 0.42.1
--------------

Released on 2018-02-01.

Bug fixes:

* `#566 <https://github.com/Kozea/WeasyPrint/issues/566>`_:
  Don't crash when using @font-config.
* `#567 <https://github.com/Kozea/WeasyPrint/issues/567>`_:
  Fix text-indent with text-align: justify.
* `#465 <https://github.com/Kozea/WeasyPrint/issues/465>`_:
  Fix string(\*, start).
* `#562 <https://github.com/Kozea/WeasyPrint/issues/562>`_:
  Handle named pages with pseudo-class.
* `#507 <https://github.com/Kozea/WeasyPrint/issues/507>`_:
  Fix running headers.
* `#557 <https://github.com/Kozea/WeasyPrint/issues/557>`_:
  Avoid infinite loops in inline_line_width.
* `#555 <https://github.com/Kozea/WeasyPrint/issues/555>`_:
  Fix margins, borders and padding in column layouts.


Version 0.42
------------

Released on 2017-12-26.

WeasyPrint is not tested with (end-of-life) Python 3.3 anymore.

**This release is probably the last version of the 0.x series.**

Next version may include big changes:

- end of Python 2.7 support,
- initial support of bidirectional text,
- initial support of flexbox,
- improvements for speed and memory usage.

New features:

* `#532 <https://github.com/Kozea/WeasyPrint/issues/532>`_:
  Support relative file URIs when using CLI.

Bug fixes:

* `#553 <https://github.com/Kozea/WeasyPrint/issues/553>`_:
  Fix slow performance for pre-formatted boxes with a lot of children.
* `#409 <https://github.com/Kozea/WeasyPrint/issues/409>`_:
  Don't crash when rendering some tables.
* `#39 <https://github.com/Kozea/WeasyPrint/issues/39>`_:
  Fix rendering of floats in inlines.
* `#301 <https://github.com/Kozea/WeasyPrint/issues/301>`_:
  Split lines carefully.
* `#530 <https://github.com/Kozea/WeasyPrint/issues/530>`_:
  Fix root when frozen with Pyinstaller.
* `#534 <https://github.com/Kozea/WeasyPrint/issues/534>`_:
  Handle SVGs containing images embedded as data URIs.
* `#360 <https://github.com/Kozea/WeasyPrint/issues/360>`_:
  Fix border-radius rendering problem with some PDF readers.
* `#525 <https://github.com/Kozea/WeasyPrint/issues/525>`_:
  Fix pipenv support.
* `#227 <https://github.com/Kozea/WeasyPrint/issues/227>`_:
  Smartly handle replaced boxes with percentage width in auto-width parents.
* `#520 <https://github.com/Kozea/WeasyPrint/issues/520>`_:
  Don't ignore CSS @page rules that are imported by an @import rule.


Version 0.41
------------

Released on 2017-10-05.

WeasyPrint now depends on pdfrw >= 0.4.

New features:

* `#471 <https://github.com/Kozea/WeasyPrint/issues/471>`_:
  Support page marks and bleed.

Bug fixes:

* `#513 <https://github.com/Kozea/WeasyPrint/issues/513>`_:
  Don't crash on unsupported image-resolution values.
* `#506 <https://github.com/Kozea/WeasyPrint/issues/506>`_:
  Fix @font-face use with write_* methods.
* `#500 <https://github.com/Kozea/WeasyPrint/pull/500>`_:
  Improve readability of _select_source function.
* `#498 <https://github.com/Kozea/WeasyPrint/issues/498>`_:
  Use CSS prefixes as recommended by the CSSWG.
* `#441 <https://github.com/Kozea/WeasyPrint/issues/441>`_:
  Fix rendering problems and crashes when using @font-face.
* `bb3a4db <https://github.com/Kozea/WeasyPrint/commit/bb3a4db>`_:
  Try to break pages after a block before trying to break inside it.
* `1d1654c <https://github.com/Kozea/WeasyPrint/commit/1d1654c>`_:
  Fix and test corner cases about named pages.

Documentation:

* `#508 <https://github.com/Kozea/WeasyPrint/pull/508>`_:
  Add missing libpangocairo dependency for Debian and Ubuntu.
* `a7b17fb <https://github.com/Kozea/WeasyPrint/commit/a7b17fb>`_:
  Add documentation on logged rendering steps.


Version 0.40
------------

Released on 2017-08-17.

WeasyPrint now depends on cssselect2 instead of cssselect and lxml.

New features:

* `#57 <https://github.com/Kozea/WeasyPrint/issues/57>`_:
  Named pages.
* Unprefix properties, see
  `#498 <https://github.com/Kozea/WeasyPrint/issues/498>`_.
* Add a "verbose" option logging the document generation steps.

Bug fixes:

* `#483 <https://github.com/Kozea/WeasyPrint/issues/483>`_:
  Fix slow performance with long pre-formatted texts.
* `#70 <https://github.com/Kozea/WeasyPrint/issues/70>`_:
  Improve speed and memory usage for long documents.
* `#487 <https://github.com/Kozea/WeasyPrint/issues/487>`_:
  Don't crash on local() fonts with a space and no quotes.


Version 0.39
------------

Released on 2017-06-24.

Bug fixes:

* Fix the use of WeasyPrint's URL fetcher with CairoSVG.


Version 0.38
------------

Released on 2017-06-16.

Bug fixes:

* `#477 <https://github.com/Kozea/WeasyPrint/issues/477>`_:
  Don't crash on font-face's src attributes with local functions.


Version 0.37
------------

Released on 2017-06-15.

WeasyPrint now depends on tinycss2 instead of tinycss.

New features:

* `#437 <https://github.com/Kozea/WeasyPrint/issues/437>`_:
  Support local links in generated PDFs.

Bug fixes:

* `#412 <https://github.com/Kozea/WeasyPrint/issues/412>`_:
  Use a NullHandler log handler when WeasyPrint is used as a library.
* `#417 <https://github.com/Kozea/WeasyPrint/issues/417>`_,
  `#472 <https://github.com/Kozea/WeasyPrint/issues/472>`_:
  Don't crash on some line breaks.
* `#327 <https://github.com/Kozea/WeasyPrint/issues/327>`_:
  Don't crash with replaced elements with height set in percentages.
* `#467 <https://github.com/Kozea/WeasyPrint/issues/467>`_:
  Remove incorrect line breaks.
* `#446 <https://github.com/Kozea/WeasyPrint/pull/446>`_:
  Let the logging module do the string interpolation.


Version 0.36
------------

Released on 2017-02-25.

New features:

* `#407 <https://github.com/Kozea/WeasyPrint/pull/407>`_:
  Handle ::first-letter.
* `#423 <https://github.com/Kozea/WeasyPrint/pull/423>`_:
  Warn user about broken cairo versions.

Bug fixes:

* `#411 <https://github.com/Kozea/WeasyPrint/pull/411>`_:
  Typos fixed in command-line help.


Version 0.35
------------

Released on 2017-02-25.

Bug fixes:

* `#410 <https://github.com/Kozea/WeasyPrint/pull/410>`_:
  Fix AssertionError in split_text_box.


Version 0.34
------------

Released on 2016-12-21.

Bug fixes:

* `#398 <https://github.com/Kozea/WeasyPrint/issues/398>`_:
  Honor the presentational_hints option for PDFs.
* `#399 <https://github.com/Kozea/WeasyPrint/pull/399>`_:
  Avoid CairoSVG-2.0.0rc* on Python 2.
* `#396 <https://github.com/Kozea/WeasyPrint/issues/396>`_:
  Correctly close files open by mkstemp.
* `#403 <https://github.com/Kozea/WeasyPrint/issues/403>`_:
  Cast the number of columns into int.
* Fix multi-page multi-columns and add related tests.


Version 0.33
------------

Released on 2016-11-28.

New features:

* `#393 <https://github.com/Kozea/WeasyPrint/issues/393>`_:
  Add tests on MacOS.
* `#370 <https://github.com/Kozea/WeasyPrint/issues/370>`_:
  Enable @font-face on MacOS.

Bug fixes:

* `#389 <https://github.com/Kozea/WeasyPrint/issues/389>`_:
  Always update resume_at when splitting lines.
* `#394 <https://github.com/Kozea/WeasyPrint/issues/394>`_:
  Don't build universal wheels.
* `#388 <https://github.com/Kozea/WeasyPrint/issues/388>`_:
  Fix logic when finishing block formatting context.


Version 0.32
------------

Released on 2016-11-17.

New features:

* `#28 <https://github.com/Kozea/WeasyPrint/issues/28>`_:
  Support @font-face on Linux.
* Support CSS fonts level 3 almost entirely, including OpenType features.
* `#253 <https://github.com/Kozea/WeasyPrint/issues/253>`_:
  Support presentational hints (optional).
* Support break-after, break-before and break-inside for pages and columns.
* `#384 <https://github.com/Kozea/WeasyPrint/issues/384>`_:
  Major performance boost.

Bux fixes:

* `#368 <https://github.com/Kozea/WeasyPrint/issues/368>`_:
  Respect white-space for shrink-to-fit.
* `#382 <https://github.com/Kozea/WeasyPrint/issues/382>`_:
  Fix the preferred width for column groups.
* Handle relative boxes in column-layout boxes.

Documentation:

* Add more and more documentation about Windows installation.
* `#355 <https://github.com/Kozea/WeasyPrint/issues/355>`_:
  Add fonts requirements for tests.


Version 0.31
------------

Released on 2016-08-28.

New features:

* `#124 <https://github.com/Kozea/WeasyPrint/issues/124>`_:
  Add MIME sniffing for images.
* `#60 <https://github.com/Kozea/WeasyPrint/issues/60>`_:
  CSS Multi-column Layout.
* `#197 <https://github.com/Kozea/WeasyPrint/pull/197>`_:
  Add hyphens at line breaks activated by a soft hyphen.

Bux fixes:

* `#132 <https://github.com/Kozea/WeasyPrint/pull/132>`_:
  Fix Python 3 compatibility on Windows.

Documentation:

* `#329 <https://github.com/Kozea/WeasyPrint/issues/329>`_:
  Add documentation about installation on Windows.


Version 0.30
------------

Released on 2016-07-18.

WeasyPrint now depends on html5lib-0.999999999.

Bux fixes:

* Fix Acid2
* `#325 <https://github.com/Kozea/WeasyPrint/issues/325>`_:
  Cutting lines is broken in page margin boxes.
* `#334 <https://github.com/Kozea/WeasyPrint/issues/334>`_:
  Newest html5lib 0.999999999 breaks rendering.


Version 0.29
------------

Released on 2016-06-17.

Bug fixes:

* `#263 <https://github.com/Kozea/WeasyPrint/pull/263>`_:
  Don't crash with floats with percents in positions.
* `#323 <https://github.com/Kozea/WeasyPrint/pull/323>`_:
  Fix CairoSVG 2.0 pre-release dependency in Python 2.x.


Version 0.28
------------

Released on 2016-05-16.

Bug fixes:

* `#189 <https://github.com/Kozea/WeasyPrint/issues/189>`_:
  ``white-space: nowrap`` still wraps on hyphens
* `#305 <https://github.com/Kozea/WeasyPrint/issues/305>`_:
  Fix crashes on some tables
* Don't crash when transform matrix isn't invertible
* Don't crash when rendering ratio-only SVG images
* Fix margins and borders on some tables


Version 0.27
------------

Released on 2016-04-08.

New features:

* `#295 <https://github.com/Kozea/WeasyPrint/pull/295>`_:
  Support the 'rem' unit.
* `#299 <https://github.com/Kozea/WeasyPrint/pull/299>`_:
  Enhance the support of SVG images.

Bug fixes:

* `#307 <https://github.com/Kozea/WeasyPrint/issues/307>`_:
  Fix the layout of cells larger than their tables.

Documentation:

* The website is now on GitHub Pages, the documentation is on Read the Docs.
* `#297 <https://github.com/Kozea/WeasyPrint/issues/297>`_:
  Rewrite the CSS chapter of the documentation.


Version 0.26
------------

Released on 2016-01-29.

New features:

* Support the `empty-cells` attribute.
* Respect table, column and cell widths.

Bug fixes:

* `#172 <https://github.com/Kozea/WeasyPrint/issues/172>`_:
  Unable to set table column width on tables td's.
* `#151 <https://github.com/Kozea/WeasyPrint/issues/151>`_:
  Table background colour bleeds beyond table cell boundaries.
* `#260 <https://github.com/Kozea/WeasyPrint/issues/260>`_:
  TypeError: unsupported operand type(s) for +: 'float' and 'str'.
* `#288 <https://github.com/Kozea/WeasyPrint/issues/288>`_:
  Unwanted line-breaks in bold text.
* `#286 <https://github.com/Kozea/WeasyPrint/issues/286>`_:
  AttributeError: 'Namespace' object has no attribute 'attachments'.


Version 0.25
------------

Released on 2015-12-17.

New features:

* Support the 'q' unit.

Bug fixes:

* `#285 <https://github.com/Kozea/WeasyPrint/issues/285>`_:
  Fix a crash happening when splitting lines.
* `#284 <https://github.com/Kozea/WeasyPrint/issues/284>`_:
  Escape parenthesis in PDF links.
* `#280 <https://github.com/Kozea/WeasyPrint/pull/280>`_:
  Replace utf8 with utf-8 for gettext/django compatibility.
* `#269 <https://github.com/Kozea/WeasyPrint/pull/269>`_:
  Add support for use when frozen.
* `#250 <https://github.com/Kozea/WeasyPrint/issues/250>`_:
  Don't crash when attachments are not available.


Version 0.24
------------

Released on 2015-08-04.

New features:

* `#174 <https://github.com/Kozea/WeasyPrint/issues/174>`_:
  Basic support for Named strings.

Bug fixes:

* `#207 <https://github.com/Kozea/WeasyPrint/issues/207>`_:
  Draw rounded corners on replaced boxes.
* `#224 <https://github.com/Kozea/WeasyPrint/pull/224>`_:
  Rely on the font size for rounding bug workaround.
* `#31 <https://github.com/Kozea/WeasyPrint/issues/31>`_:
  Honor the vertical-align property in fixed-height cells.
* `#202 <https://github.com/Kozea/WeasyPrint/issues/202>`_:
  Remove unreachable area/border at bottom of page.
* `#225 <https://github.com/Kozea/WeasyPrint/issues/225>`_:
  Don't allow unknown units during line-height validation.
* Fix some wrong conflict resolutions for table borders with inset
  and outset styles.


Version 0.23
------------

Released on 2014-09-16.

Bug fixes:

* `#196 <https://github.com/Kozea/WeasyPrint/issues/196>`_:
  Use the default image sizing algorithm for images’s preferred size.
* `#194 <https://github.com/Kozea/WeasyPrint/pull/194>`_:
  Try more library aliases with ``dlopen()``.
* `#201 <https://github.com/Kozea/WeasyPrint/pull/201>`_:
  Consider ``page-break-after-avoid`` when pushing floats to the next page.
* `#217 <https://github.com/Kozea/WeasyPrint/issues/217>`_:
  Avoid a crash on zero-sized background images.

Release process:

* Start testing on Python 3.4 on Travis-CI.


Version 0.22
------------

Released on 2014-05-05.

New features:

* `#86 <https://github.com/Kozea/WeasyPrint/pull/86>`_:
  Support gzip and deflate encoding in HTTP responses
* `#177 <https://github.com/Kozea/WeasyPrint/pull/177>`_:
  Support for PDF attachments.

Bug fixes:

* `#169 <https://github.com/Kozea/WeasyPrint/issues/169>`_:
  Fix a crash on percentage-width columns in an auto-width table.
* `#168 <https://github.com/Kozea/WeasyPrint/issues/168>`_:
  Make ``<fieldset>`` a block in the user-agent stylesheet.
* `#175 <https://github.com/Kozea/WeasyPrint/issues/175>`_:
  Fix some ``dlopen()`` library loading issues on OS X.
* `#183 <https://github.com/Kozea/WeasyPrint/issues/183>`_:
  Break to the next page before a float that would overflow the page.
  (It might still overflow if it’s bigger than the page.)
* `#188 <https://github.com/Kozea/WeasyPrint/issues/188>`_:
  Require a recent enough version of Pyphen

Release process:

* Drop Python 3.1 support.
* Set up [Travis CI](https://travis-ci.org/)
  to automatically test all pushes and pull requests.
* Start testing on Python 3.4 locally. (Travis does not support 3.4 yet.)


Version 0.21
------------

Released on 2014-01-11.

New features:

* Add the `overflow-wrap <https://drafts.csswg.org/css-text/#overflow-wrap>`_
  property, allowing line breaks inside otherwise-unbreakable words.
  Thanks Frédérick Deslandes!
* Add the `image-resolution
  <https://drafts.csswg.org/css-images-3/#the-image-resolution>`_ property,
  allowing images to be sized proportionally to their intrinsic size
  at a resolution other than 96 image pixels per CSS ``in``
  (ie. one image pixel per CSS ``px``)

Bug fixes:

* `#145 <https://github.com/Kozea/WeasyPrint/issues/145>`_:
  Fix parsing HTML from an HTTP URL on Python 3.x
* `#40 <https://github.com/Kozea/WeasyPrint/issues/40>`_:
  Use more general hyphenation dictionaries for specific document languages.
  (E.g. use ``hyph_fr.dic`` for ``lang="fr_FR"``.)
* `#26 <https://github.com/Kozea/WeasyPrint/issues/26>`_:
  Fix ``min-width`` and ``max-width`` on floats.
* `#100 <https://github.com/Kozea/WeasyPrint/issues/100>`_:
  Fix a crash on trailing whitespace with ``font-size: 0``
* `#82 <https://github.com/Kozea/WeasyPrint/issues/82>`_:
  Borders on tables with ``border-collapse: collapse`` were sometimes
  drawn at an incorrect position.
* `#30 <https://github.com/Kozea/WeasyPrint/issues/30>`_:
  Fix positioning of images with ``position: absolute``.
* `#118 <https://github.com/Kozea/WeasyPrint/issues/118>`_:
  Fix a crash when using ``position: absolute``
  inside a ``position: relative`` element.
* Fix ``visibility: collapse`` to behave like ``visibility: hidden``
  on elements other than table rows and table columns.
* `#147 <https://github.com/Kozea/WeasyPrint/issues/147>`_ and
  `#153 <https://github.com/Kozea/WeasyPrint/issues/153>`_:
  Fix dependencies to require lxml 3.0 or a more recent version.
  Thanks gizmonerd and Thomas Grainger!
* `#152 <https://github.com/Kozea/WeasyPrint/issues/152>`_:
  Fix a crash on percentage-sized table cells in auto-sized tables.
  Thanks Johannes Duschl!


Version 0.20.2
--------------

Released on 2013-12-18.

* Fix `#146 <https://github.com/Kozea/WeasyPrint/issues/146>`_: don't crash
  when drawing really small boxes with dotted/dashed borders


Version 0.20.1
--------------

Released on 2013-12-16.

* Depend on html5lib >= 0.99 instead of 1.0b3 to fix pip 1.4 support.
* Fix `#74 <https://github.com/Kozea/WeasyPrint/issues/74>`_: don't crash on
  space followed by dot at line break.
* Fix `#78 <https://github.com/Kozea/WeasyPrint/issues/78>`_: nicer colors for
  border-style: ridge/groove/inset/outset.


Version 0.20
------------

Released on 2013-12-14.

* Add support for ``border-radius``.
* Feature `#77 <https://github.com/Kozea/WeasyPrint/issues/77>`_: Add PDF
  metadata from HTML.
* Feature `#12 <https://github.com/Kozea/WeasyPrint/pull/12>`_: Use html5lib.
* Tables: handle percentages for column groups, columns and cells, and values
  for row height.
* Bug fixes:

  * Fix `#84 <https://github.com/Kozea/WeasyPrint/pull/84>`_: don't crash when
    stylesheets are not available.
  * Fix `#101 <https://github.com/Kozea/WeasyPrint/issues/101>`_: use page ids
    instead of page numbers in PDF bookmarks.
  * Use ``logger.warning`` instead of deprecated ``logger.warn``.
  * Add 'font-stretch' in the 'font' shorthand.


Version 0.19.2
--------------

Released on 2013-06-18.

Bug fix release:

* Fix `#88 <https://github.com/Kozea/WeasyPrint/issues/88>`_:
  ``text-decoration: overline`` not being drawn above the text
* Bug fix: Actually draw multiple lines when multiple values are given
  to ``text-decoration``.
* Use the font metrics for text decoration positioning.
* Bug fix: Don't clip the border with ``overflow: hidden``.
* Fix `#99 <https://github.com/Kozea/WeasyPrint/issues/99>`_:
  Regression: JPEG images not loading with cairo 1.8.x.


Version 0.19.1
--------------

Released on 2013-04-30.

Bug fix release:

* Fix incorrect intrinsic width calculation
  leading to unnecessary line breaks in floats, tables, etc.
* Tweak border painting to look better
* Fix unnecessary page break before big tables.
* Fix table row overflowing at the bottom of the page
  when there are margins above the table.
* Fix ``position: fixed`` to actually repeat on every page.
* Fix `#76 <https://github.com/Kozea/WeasyPrint/issues/76>`_:
  repeat ``<thead>`` and ``<tfoot>`` elements on every page,
  even with table border collapsing.


Version 0.19
------------

Released on 2013-04-18.

* Add support for ``linear-gradient()`` and ``radial-gradient``
  in background images.
* Add support for the ``ex`` and ``ch`` length units.
  (``1ex`` is based on the font instead of being always ``0.5em`` as before.)
* Add experimental support for Level 4 hyphenation properties.
* Drop support for CFFI < 0.6 and cairocffi < 0.4.
* Many bug fixes, including:

 * Fix `#54 <https://github.com/Kozea/WeasyPrint/issues/54>`_:
   min/max-width/height on block-level images.
 * Fix `#71 <https://github.com/Kozea/WeasyPrint/issues/71>`_:
   Crash when parsing nested functional notation.


Version 0.18
------------

Released on 2013-03-30.

* Add support for Level 3 backgrounds,
  including multiple background layers per element/box.
* Forward-compatibility with (future releases of) cairocffi 0.4+ and CFFI 0.6+.
* Bug fixes:

  * Avoid some unnecessary line breaks
    for elements sized based on their content (aka. “shrink-to-fit”)
    such as floats and page headers.
  * Allow page breaks between empty blocks.
  * Fix `#66 <https://github.com/Kozea/WeasyPrint/issues/66>`_:
    Resolve images’ auto width from non-auto height and intrinsic ratio.
  * Fix `#21 <https://github.com/Kozea/WeasyPrint/issues/21>`_:
    The ``data:`` URL scheme is case-insensitive.
  * Fix `#53 <https://github.com/Kozea/WeasyPrint/issues/53>`_:
    Crash when backtracking for ``break-before/after: avoid``.


Version 0.17.1
--------------

Released on 2013-03-18.

Bug fixes:

* Fix `#41 <https://github.com/Kozea/WeasyPrint/issues/41>`_:
  GObject initialization when GDK-PixBuf is not installed.
* Fix `#42 <https://github.com/Kozea/WeasyPrint/issues/42>`_:
  absolute URLs without a base URL (ie. document parsed from a string.)
* Fix some whitespace collapsing bugs.
* Fix absolutely-positioned elements inside inline elements.
* Fix URL escaping of image references from CSS.
* Fix `#49 <https://github.com/Kozea/WeasyPrint/issues/49>`_:
  Division by 0 on dashed or dotted border smaller than one dot/dash.
* Fix `#44 <https://github.com/Kozea/WeasyPrint/issues/44>`_:
  bad interaction of ``page-break-before/after: avoid`` and floats.


Version 0.17
------------

Released on 2013-02-27.

* Added `text hyphenation`_ with the ``-weasy-hyphens`` property.
* When a document includes JPEG images, embed them as JPEG in the PDF output.
  This often results in smaller PDF file size
  compared to the default *deflate* compression.
* Switched to using CFFI instead of PyGTK or PyGObject-introspection.
* Layout bug fixes:

  - Correctly trim whitespace at the end of lines.
  - Fix some cases with floats within inline content.

.. _text hyphenation: https://weasyprint.readthedocs.io/en/latest/features.html#css-text-module-level-3-4


Version 0.16
------------

Released on 2012-12-13.

* Add the ``zoom`` parameter to ``HTML.write_pdf`` and
  ``Document.write_pdf() <weasyprint.document.Document.write_pdf>``
* Fix compatibility with old (and buggy) pycairo versions.
  WeasyPrint is now tested on 1.8.8 in addition to the latest.
* Fix layout bugs related to line trailing spaces.


Version 0.15
------------

Released on 2012-10-09.

* Add a low-level API that enables painting pages individually on any
  cairo surface.
* **Backward-incompatible change**: remove the ``HTML.get_png_pages``
  method. The new low-level API covers this functionality and more.
* Add support for the ``font-stretch`` property.
* Add support for ``@page:blank`` to select blank pages.
* New Sphinx-based and improved docs
* Bug fixes:

  - Importing Pango in some PyGTK installations.
  - Layout of inline-blocks with `vertical-align: top` or `bottom`.
  - Do not repeat a block’s margin-top or padding-top after a page break.
  - Performance problem with large tables split across many pages.
  - Anchors and hyperlinks areas now follow CSS transforms.
    Since PDF links have to be axis-aligned rectangles, the bounding box
    is used. This may be larger than expected with rotations that are
    not a multiple of 90 degrees.


Version 0.14
------------

Released on 2012-08-03.

* Add a public API to choose media type used for @media.
  (It still defaults to ``print``). Thanks Chung Lu!
* Add ``--base-url`` and ``--resolution`` to the command-line API, making it
  as complete as the Python one.
* Add support for the ``<base href="...">`` element in HTML.
* Add support for CSS outlines
* Switch to gdk-pixbuf instead of Pystacia for loading raster images.
* Bug fixes:

  - Handling of filenames and URLs on Windows
  - Unicode filenames with older version of py2cairo
  - ``base_url`` now behaves as expected when set to a directory name.
  - Make some tests more robust


Version 0.13
------------

Released on 2012-07-23.

* Add support for PyGTK, as an alternative to PyGObject + introspection.
  This should make WeasyPrint easier to run on platforms that not not have
  packages for PyGObject 3.x yet.
* Bug fix: crash in PDF outlines for some malformed HTML documents


Version 0.12
------------

Released on 2012-07-19.

* Add support for collapsed borders on tables. This is currently incompatible
  with repeating header and footer row groups on each page: headers and footers
  are treated as normal row groups on table with ``border-collapse: collapse``.
* Add ``url_fetcher`` to the public API. This enables users to hook into
  WeasyPrint for fetching linked stylesheets or images, eg. to generate them
  on the fly without going through the network.
  This enables the creation of `Flask-WeasyPrint
  <https://packages.python.org/Flask-WeasyPrint/>`_.


Version 0.11
------------

Released on 2012-07-04.

* Add support for floats and clear.
  Together with various bug fixes, this enables WeasyPrint to pass the Acid2
  test! Acid2 is now part of our automated test suite.
* Add support for the width, min-width, max-width, height, min-height and
  max-height properties in @page. The size property is now the size of the
  page’s containing block.
* Switch the Variable Dimension rules to `the new proposal
  <https://github.com/SimonSapin/css/blob/master/margin-boxes-variable-dimension>`_.
  The previous implementation was broken in many cases.
* The ``image-rendering``, ``transform``, ``transform-origin`` and ``size``
  properties are now unprefixed. The prefixed form (eg. -weasy-size) is ignored
  but gives a specific warning.


Version 0.10
------------

Released on 2012-06-25.

* Add ``get_png_pages()`` to the public API. It returns each page as
  a separate PNG image.
* Add a ``resolution`` parameter for PNG.
* Add *WeasyPrint Navigator*, a web application that shows WeasyPrint’s
  output with clickable links. Yes, that’s a browser in your browser.
  Start it with ``python -m weasyprint.navigator``
* Add support for `vertical-align: top` and `vertical-align: bottom`
* Add support for `page-break-before: avoid` and `page-break-after: avoid`
* Bug fixes


Version 0.9
-----------

Released on 2012-06-04.

* Relative, absolute and fixed positioning
* Proper painting order (z-index)
* In PDF: support for internal and external hyperlinks as well as bookmarks.
* Added the ``tree`` parameter to the ``HTML`` class: accepts a parsed lxml
  object.
* Bug fixes, including many crashes.

Bookmarks can be controlled by the ``-weasy-bookmark-level`` and
``-weasy-bookmark-label`` properties, as described in `CSS Generated Content
for Paged Media Module <https://drafts.csswg.org/css-gcpm-3/#bookmarks>`_.

The default UA stylesheet sets a matching bookmark level on all ``<h1>``
to ``<h6>`` elements.


Version 0.8
-----------

Released on 2012-05-07.

* Switch from cssutils to tinycss_ as the CSS parser.
* Switch to the new cssselect_, almost all level 3 selectors are supported now.
* Support for inline blocks and inline tables
* Automatic table layout (column widths)
* Support for the ``min-width``, ``max-width``, ``min-height`` and
  ``max-height`` properties, except on table-related and page-related boxes.
* Speed improvements on big stylesheets / small documents thanks to tinycss.
* Many bug fixes

.. _tinycss: https://packages.python.org/tinycss/
.. _cssselect: https://packages.python.org/cssselect/


Version 0.7.1
-------------

Released on 2012-03-21.

Change the license from AGPL to BSD.


Version 0.7
-----------

Released on 2012-03-21.

* Support page breaks between table rows
* Support for the ``orphans`` and ``widows`` properties.
* Support for ``page-break-inside: avoid``
* Bug fixes

Only avoiding page breaks before/after an element is still missing.


Version 0.6.1
-------------

Released on 2012-03-01.

Fix a packaging bug. (Remove use_2to3 in setup.py. We use the same
codebase for Python 2 and 3.)


Version 0.6
-----------

Released on 2012-02-29.

* *Backward incompatible*: completely change the Python API. See the
  documentation:
  https://weasyprint.readthedocs.io/en/latest/tutorial.html#as-a-python-library
* *Backward incompatible*: Proper margin collapsing.
  This changes how blocks are rendered: adjoining margins "collapse"
  (their maximum is used) instead of accumulating.
* Support images in ``embed`` or ``object`` elements.
* Switch to pystacia instead of PIL for raster images
* Add compatibility with CPython 2.6 and 3.2. (Previously only 2.7
  was supported)
* Many bug fixes


Version 0.5
-----------

Released on 2012-02-08.

* Support for the ``overflow`` and ``clip`` properties.
* Support for the ``opacity`` property from CSS3 Colors.
* Support for CSS 2D Transforms. These are prefixed, so you need to use
  ``-weasy-transform`` and ``-weasy-transform-origin``.


Version 0.4
-----------

Released on 2012-02-07.

* Support ``text-align: justify``, ``word-spacing`` and ``letter-spacing``.
* Partial support for CSS3 Paged Media: page size and margin boxes with
  page-based counters.
* All CSS 2.1 border styles
* Fix SVG images with non-pixel units. Requires CairoSVG 0.3
* Support for ``page-break-before`` and ``page-break-after``, except for
  the value ``avoid``.
* Support for the ``background-clip``, ``background-origin`` and
  ``background-size`` from CSS3 (but still with a single background
  per element)
* Support for the ``image-rendering`` from SVG. This one is prefixed,
  use ``-weasy-image-rendering``. It only has an effect on PNG output.


Version 0.3.1
-------------

Released on 2011-12-14.

Compatibility with CairoSVG 0.1.2


Version 0.3
-----------

Released on 2011-12-13.

* **Backward-incompatible change:** the 'size' property is now prefixed (since
  it is in an experimental specification). Use '-weasy-size' instead.
* cssutils 0.9.8 or higher is now required.
* Support SVG images with CairoSVG
* Support generated content: the ``:before`` and ``:after`` pseudo-elements,
  the ``content``, ``quotes`` and ``counter-*`` properties.
* Support ordered lists: all CSS 2.1 values of the ``list-style-type`` property.
* New user-agent stylesheet with HTML 5 elements and automatic quotes for many
  languages. Thanks Peter Moulder!
* Disable cssutils validation warnings, they are redundant with WeasyPrint’s.
* Add ``--version`` to the command-line script.
* Various bug fixes


Version 0.2
-----------

Released on 2011-11-25.

* Support for tables.
* Support the `box-sizing` property from CSS 3 Basic User Interface
* Support all values of vertical-align except top and bottom. They are
  interpreted as text-top and text-bottom.
* Minor bug fixes

Tables have some limitations:
Only the fixed layout and separate border model are supported.
There are also no page break inside tables so a table higher
than a page will overflow.


Version 0.1
-----------

Released on 2011-10-28.

First packaged release. Supports "simple" CSS 2.1 pages: there is no
support for floats, tables, or absolute positioning. Other than that
most of CSS 2.1 is supported, as well as CSS 3 Colors and Selectors.
