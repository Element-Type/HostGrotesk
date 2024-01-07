## Fontbakery report

Fontbakery version: 0.8.13

<details><summary><b>[16] HostGrotesk-BlackItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.10.8 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret positioning values for these ligature glyphs:
	- fi

   [code: incomplete-caret-pos-data]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- periodcentered.loclCAT

	- periodcentered.loclCAT.case 

	- uni030C.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Eng	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni2113	Contours detected: 1	Expected: 2

	- Glyph name: Eng	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni2113	Contours detected: 1	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 518 among a set of 2 math glyphs.
The following math glyphs have a different width, though:

Width = 579:
plus

Width = 520:
notequal, equal

Width = 701:
logicalnot

Width = 617:
plusminus

Width = 509:
multiply

Width = 514:
divide

Width = 504:
minus

Width = 587:
approxequal

Width = 456:
greaterequal, lessequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* at (U+0040): X=646.0,Y=-2.0 (should be at baseline 0?)

	* S (U+0053): X=191.5,Y=2.0 (should be at baseline 0?)

	* bracketleft (U+005B): X=400.0,Y=698.0 (should be at cap-height 700?)

	* bracketleft (U+005B): X=276.0,Y=698.0 (should be at cap-height 700?)

	* bracketright (U+005D): X=257.0,Y=698.0 (should be at cap-height 700?)

	* bracketright (U+005D): X=133.0,Y=698.0 (should be at cap-height 700?)

	* g (U+0067): X=267.0,Y=-1.0 (should be at baseline 0?)

	* braceleft (U+007B): X=96.0,Y=-1.0 (should be at baseline 0?)

	* uni00B5 (U+00B5): X=152.0,Y=2.0 (should be at baseline 0?)

	* Oslash (U+00D8): X=568.0,Y=699.0 (should be at cap-height 700?)

	* eth (U+00F0): X=321.0,Y=702.0 (should be at cap-height 700?)

	* eth (U+00F0): X=447.0,Y=698.0 (should be at cap-height 700?)

	* gbreve (U+011F): X=267.0,Y=-1.0 (should be at baseline 0?)

	* gdotaccent (U+0121): X=267.0,Y=-1.0 (should be at baseline 0?)

	* uni0123 (U+0123): X=267.0,Y=-1.0 (should be at baseline 0?)

	* Sacute (U+015A): X=191.5,Y=2.0 (should be at baseline 0?)

	* Scedilla (U+015E): X=191.5,Y=2.0 (should be at baseline 0?)

	* Scaron (U+0160): X=191.5,Y=2.0 (should be at baseline 0?)

	* Uogonek (U+0172): X=360.0,Y=1.0 (should be at baseline 0?)

	* uni0218 (U+0218): X=191.5,Y=2.0 (should be at baseline 0?)

	* uni0326 (U+0326): X=53.0,Y=-1.0 (should be at baseline 0?)

	* quotedblright (U+201D): X=343.0,Y=701.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=491.0,Y=701.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=141.0,Y=701.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=289.0,Y=701.0 (should be at cap-height 700?)

	* uni20B9 (U+20B9): X=102.0,Y=701.0 (should be at cap-height 700?) 

	* uni20B9 (U+20B9): X=635.0,Y=701.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* comma (U+002C) contains a short segment L<<59.0,-27.0>--<59.0,-27.0>>

	* semicolon (U+003B) contains a short segment L<<48.0,-27.0>--<48.0,-27.0>>

	* at (U+0040) contains a short segment B<<651.0,131.5>-<660.0,115.0>-<677.0,115.0>>

	* sterling (U+00A3) contains a short segment B<<156.0,276.0>-<157.0,284.0>-<157.0,295.0>>

	* yen (U+00A5) contains a short segment L<<251.0,241.0>--<251.0,244.0>>

	* yen (U+00A5) contains a short segment L<<391.0,244.0>--<391.0,241.0>>

	* paragraph (U+00B6) contains a short segment L<<291.0,280.0>--<275.0,280.0>>

	* germandbls (U+00DF) contains a short segment L<<270.0,425.0>--<286.0,425.0>>

	* ae (U+00E6) contains a short segment L<<378.0,296.0>--<379.0,308.0>>

	* oe (U+0153) contains a short segment B<<934.0,254.0>-<933.0,247.0>-<930.5,235.0>>

	* aeacute (U+01FD) contains a short segment L<<378.0,296.0>--<379.0,308.0>>

	* Euro (U+20AC) contains a short segment B<<275.0,342.0>-<273.0,328.0>-<272.0,315.0>>

	* integral (U+222B) contains a short segment L<<-90.0,-121.0>--<-74.0,-121.0>> 

	* integral (U+222B) contains a short segment L<<393.0,814.0>--<379.0,814.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* comma (U+002C): L<<188.0,153.0>--<165.0,-7.0>> -> L<<165.0,-7.0>--<162.0,-31.0>>

	* eng (U+014B): L<<355.0,-51.0>--<389.0,184.0>> -> L<<389.0,184.0>--<401.0,268.0>> 

	* semicolon (U+003B): L<<177.0,153.0>--<154.0,-7.0>> -> L<<154.0,-7.0>--<151.0,-31.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* eng (U+014B): B<<228.5,352.5>-<189.0,315.0>-<181.0,252.0>>/L<<181.0,252.0>--<181.0,261.0>> = 7.236922025967975

	* eng (U+014B): L<<181.0,252.0>--<181.0,261.0>>/L<<181.0,261.0>--<144.0,0.0>> = 8.068626219471522

	* h (U+0068): B<<229.5,352.5>-<189.0,315.0>-<181.0,252.0>>/L<<181.0,252.0>--<181.0,259.0>> = 7.236922025967975

	* h (U+0068): L<<181.0,252.0>--<181.0,259.0>>/L<<181.0,259.0>--<144.0,0.0>> = 8.13010235415596

	* hbar (U+0127): B<<299.5,352.5>-<259.0,315.0>-<251.0,252.0>>/L<<251.0,252.0>--<251.0,259.0>> = 7.236922025967975

	* hbar (U+0127): L<<251.0,252.0>--<251.0,259.0>>/L<<251.0,259.0>--<214.0,0.0>> = 8.13010235415596

	* m (U+006D): B<<225.5,352.5>-<189.0,315.0>-<180.0,252.0>>/L<<180.0,252.0>--<180.0,253.0>> = 8.13010235415596

	* m (U+006D): L<<180.0,252.0>--<180.0,253.0>>/L<<180.0,253.0>--<144.0,0.0>> = 8.098394676422705

	* n (U+006E): B<<228.5,352.5>-<189.0,315.0>-<181.0,252.0>>/L<<181.0,252.0>--<181.0,261.0>> = 7.236922025967975

	* n (U+006E): L<<181.0,252.0>--<181.0,261.0>>/L<<181.0,261.0>--<144.0,0.0>> = 8.068626219471522

	* nacute (U+0144): B<<228.5,352.5>-<189.0,315.0>-<181.0,252.0>>/L<<181.0,252.0>--<181.0,261.0>> = 7.236922025967975

	* nacute (U+0144): L<<181.0,252.0>--<181.0,261.0>>/L<<181.0,261.0>--<144.0,0.0>> = 8.068626219471522

	* ncaron (U+0148): B<<228.5,352.5>-<189.0,315.0>-<181.0,252.0>>/L<<181.0,252.0>--<181.0,261.0>> = 7.236922025967975

	* ncaron (U+0148): L<<181.0,252.0>--<181.0,261.0>>/L<<181.0,261.0>--<144.0,0.0>> = 8.068626219471522

	* ntilde (U+00F1): B<<228.5,352.5>-<189.0,315.0>-<181.0,252.0>>/L<<181.0,252.0>--<181.0,261.0>> = 7.236922025967975

	* ntilde (U+00F1): L<<181.0,252.0>--<181.0,261.0>>/L<<181.0,261.0>--<144.0,0.0>> = 8.068626219471522

	* u (U+0075): B<<341.0,143.0>-<381.0,180.0>-<389.0,244.0>>/L<<389.0,244.0>--<389.0,241.0>> = 7.125016348901757

	* u (U+0075): L<<389.0,244.0>--<389.0,241.0>>/L<<389.0,241.0>--<425.0,496.0>> = 8.03571071053479

	* uacute (U+00FA): B<<341.0,143.0>-<381.0,180.0>-<389.0,244.0>>/L<<389.0,244.0>--<389.0,241.0>> = 7.125016348901757

	* uacute (U+00FA): L<<389.0,244.0>--<389.0,241.0>>/L<<389.0,241.0>--<425.0,496.0>> = 8.03571071053479

	* ubreve (U+016D): B<<341.0,143.0>-<381.0,180.0>-<389.0,244.0>>/L<<389.0,244.0>--<389.0,241.0>> = 7.125016348901757

	* ubreve (U+016D): L<<389.0,244.0>--<389.0,241.0>>/L<<389.0,241.0>--<425.0,496.0>> = 8.03571071053479

	* ucircumflex (U+00FB): B<<341.0,143.0>-<381.0,180.0>-<389.0,244.0>>/L<<389.0,244.0>--<389.0,241.0>> = 7.125016348901757

	* ucircumflex (U+00FB): L<<389.0,244.0>--<389.0,241.0>>/L<<389.0,241.0>--<425.0,496.0>> = 8.03571071053479

	* udieresis (U+00FC): B<<341.0,143.0>-<381.0,180.0>-<389.0,244.0>>/L<<389.0,244.0>--<389.0,241.0>> = 7.125016348901757

	* udieresis (U+00FC): L<<389.0,244.0>--<389.0,241.0>>/L<<389.0,241.0>--<425.0,496.0>> = 8.03571071053479

	* ugrave (U+00F9): B<<341.0,143.0>-<381.0,180.0>-<389.0,244.0>>/L<<389.0,244.0>--<389.0,241.0>> = 7.125016348901757

	* ugrave (U+00F9): L<<389.0,244.0>--<389.0,241.0>>/L<<389.0,241.0>--<425.0,496.0>> = 8.03571071053479

	* uhungarumlaut (U+0171): B<<341.0,143.0>-<381.0,180.0>-<389.0,244.0>>/L<<389.0,244.0>--<389.0,241.0>> = 7.125016348901757

	* uhungarumlaut (U+0171): L<<389.0,244.0>--<389.0,241.0>>/L<<389.0,241.0>--<425.0,496.0>> = 8.03571071053479

	* umacron (U+016B): B<<341.0,143.0>-<381.0,180.0>-<389.0,244.0>>/L<<389.0,244.0>--<389.0,241.0>> = 7.125016348901757

	* umacron (U+016B): L<<389.0,244.0>--<389.0,241.0>>/L<<389.0,241.0>--<425.0,496.0>> = 8.03571071053479

	* uni0146 (U+0146): B<<228.5,352.5>-<189.0,315.0>-<181.0,252.0>>/L<<181.0,252.0>--<181.0,261.0>> = 7.236922025967975

	* uni0146 (U+0146): L<<181.0,252.0>--<181.0,261.0>>/L<<181.0,261.0>--<144.0,0.0>> = 8.068626219471522

	* uogonek (U+0173): B<<341.0,143.0>-<381.0,180.0>-<389.0,244.0>>/L<<389.0,244.0>--<389.0,241.0>> = 7.125016348901757

	* uogonek (U+0173): L<<389.0,244.0>--<389.0,241.0>>/L<<389.0,241.0>--<425.0,496.0>> = 8.03571071053479

	* uring (U+016F): B<<341.0,143.0>-<381.0,180.0>-<389.0,244.0>>/L<<389.0,244.0>--<389.0,241.0>> = 7.125016348901757

	* uring (U+016F): L<<389.0,244.0>--<389.0,241.0>>/L<<389.0,241.0>--<425.0,496.0>> = 8.03571071053479

	* utilde (U+0169): B<<341.0,143.0>-<381.0,180.0>-<389.0,244.0>>/L<<389.0,244.0>--<389.0,241.0>> = 7.125016348901757 

	* utilde (U+0169): L<<389.0,244.0>--<389.0,241.0>>/L<<389.0,241.0>--<425.0,496.0>> = 8.03571071053479 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[16] HostGrotesk-BoldItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.10.8 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret positioning values for these ligature glyphs:
	- fi

   [code: incomplete-caret-pos-data]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- periodcentered.loclCAT

	- periodcentered.loclCAT.case 

	- uni030C.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Eng	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni2113	Contours detected: 1	Expected: 2

	- Glyph name: Eng	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni2113	Contours detected: 1	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 514 among a set of 3 math glyphs.
The following math glyphs have a different width, though:

Width = 579:
plus

Width = 520:
notequal, equal

Width = 701:
logicalnot

Width = 617:
plusminus

Width = 509:
multiply

Width = 504:
minus

Width = 587:
approxequal

Width = 456:
greaterequal, lessequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* S (U+0053): X=190.5,Y=2.0 (should be at baseline 0?)

	* y (U+0079): X=194.0,Y=1.0 (should be at baseline 0?)

	* braceleft (U+007B): X=102.0,Y=-1.0 (should be at baseline 0?)

	* braceleft (U+007B): X=225.0,Y=-2.0 (should be at baseline 0?)

	* section (U+00A7): X=234.0,Y=-261.0 (should be at descender -260?)

	* section (U+00A7): X=234.0,Y=-261.0 (should be at descender -260?)

	* Oslash (U+00D8): X=570.5,Y=698.5 (should be at cap-height 700?)

	* eth (U+00F0): X=324.0,Y=702.0 (should be at cap-height 700?)

	* eth (U+00F0): X=441.0,Y=698.0 (should be at cap-height 700?)

	* yacute (U+00FD): X=194.0,Y=1.0 (should be at baseline 0?)

	* ydieresis (U+00FF): X=194.0,Y=1.0 (should be at baseline 0?)

	* abreve (U+0103): X=179.0,Y=699.0 (should be at cap-height 700?)

	* abreve (U+0103): X=490.0,Y=699.0 (should be at cap-height 700?)

	* ebreve (U+0115): X=197.0,Y=699.0 (should be at cap-height 700?)

	* ebreve (U+0115): X=508.0,Y=699.0 (should be at cap-height 700?)

	* gbreve (U+011F): X=181.0,Y=699.0 (should be at cap-height 700?)

	* gbreve (U+011F): X=492.0,Y=699.0 (should be at cap-height 700?)

	* ibreve (U+012D): X=16.0,Y=699.0 (should be at cap-height 700?)

	* ibreve (U+012D): X=327.0,Y=699.0 (should be at cap-height 700?)

	* obreve (U+014F): X=190.0,Y=699.0 (should be at cap-height 700?)

	* obreve (U+014F): X=501.0,Y=699.0 (should be at cap-height 700?)

	* Sacute (U+015A): X=190.5,Y=2.0 (should be at baseline 0?)

	* Scedilla (U+015E): X=190.5,Y=2.0 (should be at baseline 0?)

	* Scaron (U+0160): X=190.5,Y=2.0 (should be at baseline 0?)

	* ubreve (U+016D): X=187.0,Y=699.0 (should be at cap-height 700?)

	* ubreve (U+016D): X=498.0,Y=699.0 (should be at cap-height 700?)

	* Uogonek (U+0172): X=358.0,Y=1.0 (should be at baseline 0?)

	* ycircumflex (U+0177): X=194.0,Y=1.0 (should be at baseline 0?)

	* uni0218 (U+0218): X=190.5,Y=2.0 (should be at baseline 0?)

	* breve (U+02D8): X=94.0,Y=699.0 (should be at cap-height 700?)

	* breve (U+02D8): X=405.0,Y=699.0 (should be at cap-height 700?)

	* uni0306 (U+0306): X=94.0,Y=699.0 (should be at cap-height 700?)

	* uni0306 (U+0306): X=405.0,Y=699.0 (should be at cap-height 700?)

	* ygrave (U+1EF3): X=194.0,Y=1.0 (should be at baseline 0?)

	* uni1EF9 (U+1EF9): X=194.0,Y=1.0 (should be at baseline 0?)

	* quotedblright (U+201D): X=344.0,Y=701.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=480.0,Y=701.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=151.0,Y=701.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=288.0,Y=701.0 (should be at cap-height 700?)

	* uni20B9 (U+20B9): X=101.0,Y=701.0 (should be at cap-height 700?) 

	* uni20B9 (U+20B9): X=636.0,Y=701.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* parenleft (U+0028) contains a short segment L<<450.0,811.0>--<450.0,797.0>>

	* comma (U+002C) contains a short segment L<<59.0,-32.0>--<59.0,-32.0>>

	* semicolon (U+003B) contains a short segment L<<50.0,-32.0>--<50.0,-32.0>>

	* at (U+0040) contains a short segment B<<647.5,121.0>-<657.0,104.0>-<675.0,104.0>>

	* yen (U+00A5) contains a short segment L<<256.0,238.0>--<258.0,249.0>>

	* yen (U+00A5) contains a short segment L<<386.0,249.0>--<384.0,238.0>>

	* paragraph (U+00B6) contains a short segment L<<298.0,283.0>--<283.0,283.0>>

	* germandbls (U+00DF) contains a short segment L<<265.0,423.0>--<286.0,423.0>>

	* ae (U+00E6) contains a short segment L<<383.0,296.0>--<384.0,307.0>>

	* aeacute (U+01FD) contains a short segment L<<383.0,296.0>--<384.0,307.0>> 

	* integral (U+222B) contains a short segment L<<392.0,821.0>--<377.0,821.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* comma (U+002C): L<<180.0,144.0>--<159.0,-7.0>> -> L<<159.0,-7.0>--<155.0,-35.0>>

	* eng (U+014B): L<<361.0,-59.0>--<397.0,194.0>> -> L<<397.0,194.0>--<408.0,271.0>> 

	* semicolon (U+003B): L<<171.0,144.0>--<150.0,-7.0>> -> L<<150.0,-7.0>--<146.0,-35.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* eng (U+014B): B<<225.5,360.5>-<184.0,321.0>-<175.0,253.0>>/L<<175.0,253.0>--<175.0,260.0>> = 7.539445139509295

	* eng (U+014B): L<<175.0,253.0>--<175.0,260.0>>/L<<175.0,260.0>--<138.0,0.0>> = 8.099248410173876

	* h (U+0068): B<<226.5,360.5>-<184.0,321.0>-<175.0,253.0>>/L<<175.0,253.0>--<175.0,259.0>> = 7.539445139509295

	* h (U+0068): L<<175.0,253.0>--<175.0,259.0>>/L<<175.0,259.0>--<138.0,0.0>> = 8.13010235415596

	* hbar (U+0127): B<<296.5,360.5>-<254.0,321.0>-<244.0,253.0>>/L<<244.0,253.0>--<244.0,259.0>> = 8.365886124032546

	* hbar (U+0127): L<<244.0,253.0>--<244.0,259.0>>/L<<244.0,259.0>--<208.0,0.0>> = 7.913191299265412

	* m (U+006D): B<<223.0,360.5>-<184.0,321.0>-<175.0,253.0>>/L<<175.0,253.0>--<175.0,254.0>> = 7.539445139509295

	* m (U+006D): B<<566.5,360.5>-<528.0,321.0>-<519.0,253.0>>/L<<519.0,253.0>--<519.0,255.0>> = 7.539445139509295

	* m (U+006D): L<<175.0,253.0>--<175.0,254.0>>/L<<175.0,254.0>--<139.0,0.0>> = 8.066931729793097

	* m (U+006D): L<<519.0,253.0>--<519.0,255.0>>/L<<519.0,255.0>--<483.0,0.0>> = 8.03571071053479

	* n (U+006E): B<<225.5,360.5>-<184.0,321.0>-<175.0,253.0>>/L<<175.0,253.0>--<175.0,260.0>> = 7.539445139509295

	* n (U+006E): L<<175.0,253.0>--<175.0,260.0>>/L<<175.0,260.0>--<138.0,0.0>> = 8.099248410173876

	* nacute (U+0144): B<<225.5,360.5>-<184.0,321.0>-<175.0,253.0>>/L<<175.0,253.0>--<175.0,260.0>> = 7.539445139509295

	* nacute (U+0144): L<<175.0,253.0>--<175.0,260.0>>/L<<175.0,260.0>--<138.0,0.0>> = 8.099248410173876

	* ncaron (U+0148): B<<225.5,360.5>-<184.0,321.0>-<175.0,253.0>>/L<<175.0,253.0>--<175.0,260.0>> = 7.539445139509295

	* ncaron (U+0148): L<<175.0,253.0>--<175.0,260.0>>/L<<175.0,260.0>--<138.0,0.0>> = 8.099248410173876

	* ntilde (U+00F1): B<<225.5,360.5>-<184.0,321.0>-<175.0,253.0>>/L<<175.0,253.0>--<175.0,260.0>> = 7.539445139509295

	* ntilde (U+00F1): L<<175.0,253.0>--<175.0,260.0>>/L<<175.0,260.0>--<138.0,0.0>> = 8.099248410173876

	* r (U+0072): B<<312.0,386.0>-<204.0,386.0>-<181.0,213.0>>/L<<181.0,213.0>--<181.0,214.0>> = 7.572948640543364

	* r (U+0072): L<<181.0,213.0>--<181.0,214.0>>/L<<181.0,214.0>--<150.0,0.0>> = 8.242520351518879

	* racute (U+0155): B<<312.0,386.0>-<204.0,386.0>-<181.0,213.0>>/L<<181.0,213.0>--<181.0,214.0>> = 7.572948640543364

	* racute (U+0155): L<<181.0,213.0>--<181.0,214.0>>/L<<181.0,214.0>--<150.0,0.0>> = 8.242520351518879

	* rcaron (U+0159): B<<312.0,386.0>-<204.0,386.0>-<181.0,213.0>>/L<<181.0,213.0>--<181.0,214.0>> = 7.572948640543364

	* rcaron (U+0159): L<<181.0,213.0>--<181.0,214.0>>/L<<181.0,214.0>--<150.0,0.0>> = 8.242520351518879

	* u (U+0075): B<<344.0,135.5>-<386.0,175.0>-<395.0,243.0>>/L<<395.0,243.0>--<395.0,241.0>> = 7.539445139509295

	* u (U+0075): L<<395.0,243.0>--<395.0,241.0>>/L<<395.0,241.0>--<431.0,496.0>> = 8.03571071053479

	* uacute (U+00FA): B<<344.0,135.5>-<386.0,175.0>-<395.0,243.0>>/L<<395.0,243.0>--<395.0,241.0>> = 7.539445139509295

	* uacute (U+00FA): L<<395.0,243.0>--<395.0,241.0>>/L<<395.0,241.0>--<431.0,496.0>> = 8.03571071053479

	* ubreve (U+016D): B<<344.0,135.5>-<386.0,175.0>-<395.0,243.0>>/L<<395.0,243.0>--<395.0,241.0>> = 7.539445139509295

	* ubreve (U+016D): L<<395.0,243.0>--<395.0,241.0>>/L<<395.0,241.0>--<431.0,496.0>> = 8.03571071053479

	* ucircumflex (U+00FB): B<<344.0,135.5>-<386.0,175.0>-<395.0,243.0>>/L<<395.0,243.0>--<395.0,241.0>> = 7.539445139509295

	* ucircumflex (U+00FB): L<<395.0,243.0>--<395.0,241.0>>/L<<395.0,241.0>--<431.0,496.0>> = 8.03571071053479

	* udieresis (U+00FC): B<<344.0,135.5>-<386.0,175.0>-<395.0,243.0>>/L<<395.0,243.0>--<395.0,241.0>> = 7.539445139509295

	* udieresis (U+00FC): L<<395.0,243.0>--<395.0,241.0>>/L<<395.0,241.0>--<431.0,496.0>> = 8.03571071053479

	* ugrave (U+00F9): B<<344.0,135.5>-<386.0,175.0>-<395.0,243.0>>/L<<395.0,243.0>--<395.0,241.0>> = 7.539445139509295

	* ugrave (U+00F9): L<<395.0,243.0>--<395.0,241.0>>/L<<395.0,241.0>--<431.0,496.0>> = 8.03571071053479

	* uhungarumlaut (U+0171): B<<344.0,135.5>-<386.0,175.0>-<395.0,243.0>>/L<<395.0,243.0>--<395.0,241.0>> = 7.539445139509295

	* uhungarumlaut (U+0171): L<<395.0,243.0>--<395.0,241.0>>/L<<395.0,241.0>--<431.0,496.0>> = 8.03571071053479

	* umacron (U+016B): B<<344.0,135.5>-<386.0,175.0>-<395.0,243.0>>/L<<395.0,243.0>--<395.0,241.0>> = 7.539445139509295

	* umacron (U+016B): L<<395.0,243.0>--<395.0,241.0>>/L<<395.0,241.0>--<431.0,496.0>> = 8.03571071053479

	* uni0146 (U+0146): B<<225.5,360.5>-<184.0,321.0>-<175.0,253.0>>/L<<175.0,253.0>--<175.0,260.0>> = 7.539445139509295

	* uni0146 (U+0146): L<<175.0,253.0>--<175.0,260.0>>/L<<175.0,260.0>--<138.0,0.0>> = 8.099248410173876

	* uni0157 (U+0157): B<<312.0,386.0>-<204.0,386.0>-<181.0,213.0>>/L<<181.0,213.0>--<181.0,214.0>> = 7.572948640543364

	* uni0157 (U+0157): L<<181.0,213.0>--<181.0,214.0>>/L<<181.0,214.0>--<150.0,0.0>> = 8.242520351518879

	* uogonek (U+0173): B<<344.0,135.5>-<386.0,175.0>-<395.0,243.0>>/L<<395.0,243.0>--<395.0,241.0>> = 7.539445139509295

	* uogonek (U+0173): L<<395.0,243.0>--<395.0,241.0>>/L<<395.0,241.0>--<431.0,496.0>> = 8.03571071053479

	* uring (U+016F): B<<344.0,135.5>-<386.0,175.0>-<395.0,243.0>>/L<<395.0,243.0>--<395.0,241.0>> = 7.539445139509295

	* uring (U+016F): L<<395.0,243.0>--<395.0,241.0>>/L<<395.0,241.0>--<431.0,496.0>> = 8.03571071053479

	* utilde (U+0169): B<<344.0,135.5>-<386.0,175.0>-<395.0,243.0>>/L<<395.0,243.0>--<395.0,241.0>> = 7.539445139509295 

	* utilde (U+0169): L<<395.0,243.0>--<395.0,241.0>>/L<<395.0,241.0>--<431.0,496.0>> = 8.03571071053479 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[17] HostGrotesk-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.10.8 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret positioning values for these ligature glyphs:
	- fi

   [code: incomplete-caret-pos-data]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- periodcentered.loclCAT

	- periodcentered.loclCAT.case 

	- uni030C.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Eng	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni2113	Contours detected: 1	Expected: 2

	- Glyph name: Eng	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni2113	Contours detected: 1	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 499 among a set of 2 math glyphs.
The following math glyphs have a different width, though:

Width = 579:
plus

Width = 520:
notequal, equal

Width = 701:
logicalnot

Width = 617:
plusminus

Width = 509:
multiply

Width = 514:
divide

Width = 504:
minus

Width = 587:
approxequal

Width = 456:
greaterequal, lessequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* i (U+0069): X=51.0,Y=701.0 (should be at cap-height 700?)

	* i (U+0069): X=160.0,Y=701.0 (should be at cap-height 700?)

	* j (U+006A): X=79.0,Y=701.0 (should be at cap-height 700?)

	* j (U+006A): X=188.0,Y=701.0 (should be at cap-height 700?)

	* dieresis (U+00A8): X=160.0,Y=701.0 (should be at cap-height 700?)

	* dieresis (U+00A8): X=264.0,Y=701.0 (should be at cap-height 700?)

	* dieresis (U+00A8): X=2.0,Y=701.0 (should be at cap-height 700?)

	* dieresis (U+00A8): X=106.0,Y=701.0 (should be at cap-height 700?)

	* Ccedilla (U+00C7): X=296.0,Y=-261.0 (should be at descender -260?)

	* Ccedilla (U+00C7): X=407.0,Y=-261.0 (should be at descender -260?)

	* adieresis (U+00E4): X=301.0,Y=701.0 (should be at cap-height 700?)

	* adieresis (U+00E4): X=405.0,Y=701.0 (should be at cap-height 700?)

	* adieresis (U+00E4): X=143.0,Y=701.0 (should be at cap-height 700?)

	* adieresis (U+00E4): X=247.0,Y=701.0 (should be at cap-height 700?)

	* ccedilla (U+00E7): X=190.0,Y=-262.0 (should be at descender -260?)

	* ccedilla (U+00E7): X=301.0,Y=-262.0 (should be at descender -260?)

	* edieresis (U+00EB): X=314.0,Y=701.0 (should be at cap-height 700?)

	* edieresis (U+00EB): X=418.0,Y=701.0 (should be at cap-height 700?)

	* edieresis (U+00EB): X=156.0,Y=701.0 (should be at cap-height 700?)

	* edieresis (U+00EB): X=260.0,Y=701.0 (should be at cap-height 700?)

	* idieresis (U+00EF): X=132.0,Y=701.0 (should be at cap-height 700?)

	* idieresis (U+00EF): X=236.0,Y=701.0 (should be at cap-height 700?)

	* idieresis (U+00EF): X=-26.0,Y=701.0 (should be at cap-height 700?)

	* idieresis (U+00EF): X=78.0,Y=701.0 (should be at cap-height 700?)

	* odieresis (U+00F6): X=309.0,Y=701.0 (should be at cap-height 700?)

	* odieresis (U+00F6): X=413.0,Y=701.0 (should be at cap-height 700?)

	* odieresis (U+00F6): X=151.0,Y=701.0 (should be at cap-height 700?)

	* odieresis (U+00F6): X=255.0,Y=701.0 (should be at cap-height 700?)

	* udieresis (U+00FC): X=304.0,Y=701.0 (should be at cap-height 700?)

	* udieresis (U+00FC): X=408.0,Y=701.0 (should be at cap-height 700?)

	* udieresis (U+00FC): X=146.0,Y=701.0 (should be at cap-height 700?)

	* udieresis (U+00FC): X=250.0,Y=701.0 (should be at cap-height 700?)

	* ydieresis (U+00FF): X=331.0,Y=701.0 (should be at cap-height 700?)

	* ydieresis (U+00FF): X=435.0,Y=701.0 (should be at cap-height 700?)

	* ydieresis (U+00FF): X=173.0,Y=701.0 (should be at cap-height 700?)

	* ydieresis (U+00FF): X=277.0,Y=701.0 (should be at cap-height 700?)

	* cdotaccent (U+010B): X=234.0,Y=702.0 (should be at cap-height 700?)

	* cdotaccent (U+010B): X=343.0,Y=702.0 (should be at cap-height 700?)

	* edotaccent (U+0117): X=233.0,Y=701.0 (should be at cap-height 700?)

	* edotaccent (U+0117): X=342.0,Y=701.0 (should be at cap-height 700?)

	* gdotaccent (U+0121): X=252.0,Y=701.0 (should be at cap-height 700?)

	* gdotaccent (U+0121): X=361.0,Y=701.0 (should be at cap-height 700?)

	* iogonek (U+012F): X=51.0,Y=701.0 (should be at cap-height 700?)

	* iogonek (U+012F): X=160.0,Y=701.0 (should be at cap-height 700?)

	* ij (U+0133): X=58.0,Y=701.0 (should be at cap-height 700?)

	* ij (U+0133): X=167.0,Y=701.0 (should be at cap-height 700?)

	* ij (U+0133): X=286.0,Y=701.0 (should be at cap-height 700?)

	* ij (U+0133): X=396.0,Y=701.0 (should be at cap-height 700?)

	* ohungarumlaut (U+0151): X=377.0,Y=701.0 (should be at cap-height 700?)

	* ohungarumlaut (U+0151): X=468.0,Y=701.0 (should be at cap-height 700?)

	* ohungarumlaut (U+0151): X=236.0,Y=701.0 (should be at cap-height 700?)

	* ohungarumlaut (U+0151): X=328.0,Y=701.0 (should be at cap-height 700?)

	* Scedilla (U+015E): X=223.0,Y=-261.0 (should be at descender -260?)

	* Scedilla (U+015E): X=334.0,Y=-261.0 (should be at descender -260?)

	* scedilla (U+015F): X=159.0,Y=-261.0 (should be at descender -260?)

	* scedilla (U+015F): X=270.0,Y=-261.0 (should be at descender -260?)

	* uni0162 (U+0162): X=196.0,Y=-261.0 (should be at descender -260?)

	* uni0162 (U+0162): X=307.0,Y=-261.0 (should be at descender -260?)

	* uni0163 (U+0163): X=148.0,Y=-261.0 (should be at descender -260?)

	* uni0163 (U+0163): X=259.0,Y=-261.0 (should be at descender -260?)

	* uhungarumlaut (U+0171): X=372.0,Y=701.0 (should be at cap-height 700?)

	* uhungarumlaut (U+0171): X=463.0,Y=701.0 (should be at cap-height 700?)

	* uhungarumlaut (U+0171): X=231.0,Y=701.0 (should be at cap-height 700?)

	* uhungarumlaut (U+0171): X=323.0,Y=701.0 (should be at cap-height 700?)

	* zdotaccent (U+017C): X=159.0,Y=701.0 (should be at cap-height 700?)

	* zdotaccent (U+017C): X=268.0,Y=701.0 (should be at cap-height 700?)

	* dotaccent (U+02D9): X=0.0,Y=701.0 (should be at cap-height 700?)

	* dotaccent (U+02D9): X=109.0,Y=701.0 (should be at cap-height 700?)

	* hungarumlaut (U+02DD): X=208.0,Y=701.0 (should be at cap-height 700?)

	* hungarumlaut (U+02DD): X=299.0,Y=701.0 (should be at cap-height 700?)

	* hungarumlaut (U+02DD): X=67.0,Y=701.0 (should be at cap-height 700?)

	* hungarumlaut (U+02DD): X=159.0,Y=701.0 (should be at cap-height 700?)

	* uni0307 (U+0307): X=0.0,Y=701.0 (should be at cap-height 700?)

	* uni0307 (U+0307): X=109.0,Y=701.0 (should be at cap-height 700?)

	* uni0308 (U+0308): X=160.0,Y=701.0 (should be at cap-height 700?)

	* uni0308 (U+0308): X=264.0,Y=701.0 (should be at cap-height 700?)

	* uni0308 (U+0308): X=2.0,Y=701.0 (should be at cap-height 700?)

	* uni0308 (U+0308): X=106.0,Y=701.0 (should be at cap-height 700?)

	* uni030B (U+030B): X=208.0,Y=701.0 (should be at cap-height 700?)

	* uni030B (U+030B): X=299.0,Y=701.0 (should be at cap-height 700?)

	* uni030B (U+030B): X=67.0,Y=701.0 (should be at cap-height 700?)

	* uni030B (U+030B): X=159.0,Y=701.0 (should be at cap-height 700?)

	* wdieresis (U+1E85): X=429.0,Y=701.0 (should be at cap-height 700?)

	* wdieresis (U+1E85): X=533.0,Y=701.0 (should be at cap-height 700?)

	* wdieresis (U+1E85): X=271.0,Y=701.0 (should be at cap-height 700?) 

	* wdieresis (U+1E85): X=375.0,Y=701.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* ampersand (U+0026) contains a short segment L<<297.0,366.0>--<294.0,366.0>>

	* parenleft (U+0028) contains a short segment L<<345.0,811.0>--<345.0,802.0>>

	* parenright (U+0029) contains a short segment L<<59.0,-145.0>--<59.0,-136.0>>

	* R (U+0052) contains a short segment L<<296.0,285.0>--<296.0,285.0>>

	* R (U+0052) contains a short segment L<<296.0,285.0>--<296.0,285.0>>

	* paragraph (U+00B6) contains a short segment L<<316.0,294.0>--<305.0,294.0>>

	* cedilla (U+00B8) contains a short segment B<<32.0,-107.0>-<32.0,-104.0>-<33.0,-101.0>>

	* Ccedilla (U+00C7) contains a short segment B<<328.0,-108.0>-<328.0,-105.0>-<329.0,-102.0>>

	* ae (U+00E6) contains a short segment L<<386.0,297.0>--<386.0,305.0>>

	* ae (U+00E6) contains a short segment B<<863.0,276.0>-<863.0,266.0>-<862.5,255.0>>

	* ccedilla (U+00E7) contains a short segment B<<222.0,-109.0>-<222.0,-106.0>-<223.0,-103.0>>

	* eng (U+014B) contains a short segment L<<420.0,0.0>--<420.0,0.0>>

	* Racute (U+0154) contains a short segment L<<296.0,285.0>--<296.0,285.0>>

	* Racute (U+0154) contains a short segment L<<296.0,285.0>--<296.0,285.0>>

	* uni0156 (U+0156) contains a short segment L<<296.0,285.0>--<296.0,285.0>>

	* uni0156 (U+0156) contains a short segment L<<296.0,285.0>--<296.0,285.0>>

	* Rcaron (U+0158) contains a short segment L<<296.0,285.0>--<296.0,285.0>>

	* Rcaron (U+0158) contains a short segment L<<296.0,285.0>--<296.0,285.0>>

	* Scedilla (U+015E) contains a short segment B<<255.0,-108.0>-<255.0,-105.0>-<256.0,-102.0>>

	* scedilla (U+015F) contains a short segment B<<191.0,-108.0>-<191.0,-105.0>-<192.0,-102.0>>

	* uni0162 (U+0162) contains a short segment B<<228.0,-108.0>-<228.0,-105.0>-<229.0,-102.0>>

	* uni0163 (U+0163) contains a short segment B<<180.0,-108.0>-<180.0,-105.0>-<181.0,-102.0>>

	* aeacute (U+01FD) contains a short segment L<<386.0,297.0>--<386.0,305.0>>

	* aeacute (U+01FD) contains a short segment B<<863.0,276.0>-<863.0,266.0>-<862.5,255.0>>

	* uni0327 (U+0327) contains a short segment B<<32.0,-107.0>-<32.0,-104.0>-<33.0,-101.0>>

	* uni20A8 (U+20A8) contains a short segment L<<322.0,285.0>--<322.0,285.0>>

	* uni20A8 (U+20A8) contains a short segment L<<322.0,285.0>--<322.0,285.0>>

	* uni20B9 (U+20B9) contains a short segment B<<361.0,524.0>-<361.0,528.0>-<361.0,534.0>> 

	* uni20B9 (U+20B9) contains a short segment B<<446.0,534.0>-<446.0,528.0>-<446.0,524.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* R (U+0052): L<<296.0,285.0>--<296.0,285.0>> -> L<<296.0,285.0>--<296.0,285.0>>

	* Racute (U+0154): L<<296.0,285.0>--<296.0,285.0>> -> L<<296.0,285.0>--<296.0,285.0>>

	* Rcaron (U+0158): L<<296.0,285.0>--<296.0,285.0>> -> L<<296.0,285.0>--<296.0,285.0>>

	* uni0156 (U+0156): L<<296.0,285.0>--<296.0,285.0>> -> L<<296.0,285.0>--<296.0,285.0>> 

	* uni20A8 (U+20A8): L<<322.0,285.0>--<322.0,285.0>> -> L<<322.0,285.0>--<322.0,285.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* partialdiff (U+2202): B<<394.0,534.0>-<431.0,511.0>-<447.0,449.0>>/B<<447.0,449.0>-<445.0,517.0>-<429.5,570.5>> = 12.785609782169606 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* trademark (U+2122): L<<128.0,348.0>--<129.0,643.0>>

	* trademark (U+2122): L<<198.0,643.0>--<199.0,348.0>> 

	* trademark (U+2122): L<<691.0,348.0>--<690.0,604.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[16] HostGrotesk-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.10.8 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret positioning values for these ligature glyphs:
	- fi

   [code: incomplete-caret-pos-data]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- periodcentered.loclCAT

	- periodcentered.loclCAT.case 

	- uni030C.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Eng	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni2113	Contours detected: 1	Expected: 2

	- Glyph name: Eng	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni2113	Contours detected: 1	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 507 among a set of 2 math glyphs.
The following math glyphs have a different width, though:

Width = 579:
plus

Width = 520:
notequal, equal

Width = 701:
logicalnot

Width = 617:
plusminus

Width = 509:
multiply

Width = 514:
divide

Width = 504:
minus

Width = 587:
approxequal

Width = 456:
greaterequal, lessequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* S (U+0053): X=402.5,Y=1.5 (should be at baseline 0?)

	* braceleft (U+007B): X=255.5,Y=700.5 (should be at cap-height 700?)

	* braceright (U+007D): X=149.5,Y=700.5 (should be at cap-height 700?)

	* cedilla (U+00B8): X=0.0,Y=-261.0 (should be at descender -260?)

	* cedilla (U+00B8): X=121.0,Y=-261.0 (should be at descender -260?)

	* Sacute (U+015A): X=402.5,Y=1.5 (should be at baseline 0?)

	* Scedilla (U+015E): X=402.5,Y=1.5 (should be at baseline 0?)

	* Scaron (U+0160): X=402.5,Y=1.5 (should be at baseline 0?)

	* tcaron (U+0165): X=361.0,Y=699.0 (should be at cap-height 700?)

	* tcaron (U+0165): X=308.0,Y=699.0 (should be at cap-height 700?)

	* tcaron (U+0165): X=423.0,Y=702.0 (should be at cap-height 700?)

	* Uogonek (U+0172): X=390.0,Y=1.0 (should be at baseline 0?)

	* uni0218 (U+0218): X=402.5,Y=1.5 (should be at baseline 0?)

	* uni0327 (U+0327): X=0.0,Y=-261.0 (should be at descender -260?)

	* uni0327 (U+0327): X=121.0,Y=-261.0 (should be at descender -260?)

	* quotedblright (U+201D): X=287.0,Y=701.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=405.0,Y=701.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=92.0,Y=701.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=210.0,Y=701.0 (should be at cap-height 700?)

	* dagger (U+2020): X=250.0,Y=-261.0 (should be at descender -260?)

	* dagger (U+2020): X=359.0,Y=-261.0 (should be at descender -260?)

	* daggerdbl (U+2021): X=252.0,Y=-261.0 (should be at descender -260?)

	* daggerdbl (U+2021): X=362.0,Y=-261.0 (should be at descender -260?)

	* uni20B9 (U+20B9): X=35.0,Y=701.0 (should be at cap-height 700?) 

	* uni20B9 (U+20B9): X=574.0,Y=701.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* parenleft (U+0028) contains a short segment L<<359.0,811.0>--<359.0,801.0>>

	* parenright (U+0029) contains a short segment L<<45.0,-145.0>--<45.0,-135.0>>

	* at (U+0040) contains a short segment B<<660.5,104.0>-<671.0,88.0>-<690.0,88.0>>

	* R (U+0052) contains a short segment L<<304.0,277.0>--<304.0,277.0>>

	* R (U+0052) contains a short segment L<<304.0,277.0>--<303.0,277.0>>

	* yen (U+00A5) contains a short segment L<<265.0,234.0>--<265.0,256.0>>

	* yen (U+00A5) contains a short segment L<<375.0,256.0>--<375.0,234.0>>

	* paragraph (U+00B6) contains a short segment L<<311.0,288.0>--<296.0,288.0>>

	* ae (U+00E6) contains a short segment L<<379.0,296.0>--<379.0,305.0>>

	* eng (U+014B) contains a short segment L<<410.0,0.0>--<409.0,0.0>>

	* Racute (U+0154) contains a short segment L<<304.0,277.0>--<304.0,277.0>>

	* Racute (U+0154) contains a short segment L<<304.0,277.0>--<303.0,277.0>>

	* uni0156 (U+0156) contains a short segment L<<304.0,277.0>--<304.0,277.0>>

	* uni0156 (U+0156) contains a short segment L<<304.0,277.0>--<303.0,277.0>>

	* Rcaron (U+0158) contains a short segment L<<304.0,277.0>--<304.0,277.0>>

	* Rcaron (U+0158) contains a short segment L<<304.0,277.0>--<303.0,277.0>>

	* aeacute (U+01FD) contains a short segment L<<379.0,296.0>--<379.0,305.0>>

	* uni20A8 (U+20A8) contains a short segment L<<321.0,277.0>--<321.0,277.0>> 

	* uni20A8 (U+20A8) contains a short segment L<<321.0,277.0>--<320.0,277.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* R (U+0052): L<<304.0,277.0>--<303.0,277.0>> -> L<<303.0,277.0>--<170.0,277.0>>

	* Racute (U+0154): L<<304.0,277.0>--<303.0,277.0>> -> L<<303.0,277.0>--<170.0,277.0>>

	* Rcaron (U+0158): L<<304.0,277.0>--<303.0,277.0>> -> L<<303.0,277.0>--<170.0,277.0>>

	* uni0156 (U+0156): L<<304.0,277.0>--<303.0,277.0>> -> L<<303.0,277.0>--<170.0,277.0>> 

	* uni20A8 (U+20A8): L<<321.0,277.0>--<320.0,277.0>> -> L<<320.0,277.0>--<187.0,277.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* summation (U+2211): L<<37.0,573.0>--<38.0,700.0>>

	* trademark (U+2122): L<<114.0,349.0>--<115.0,633.0>>

	* trademark (U+2122): L<<197.0,633.0>--<198.0,349.0>> 

	* trademark (U+2122): L<<689.0,349.0>--<687.0,591.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[16] HostGrotesk-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.10.8 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret positioning values for these ligature glyphs:
	- fi

   [code: incomplete-caret-pos-data]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- periodcentered.loclCAT

	- periodcentered.loclCAT.case 

	- uni030C.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Eng	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni2113	Contours detected: 1	Expected: 2

	- Glyph name: Eng	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni2113	Contours detected: 1	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 518 among a set of 2 math glyphs.
The following math glyphs have a different width, though:

Width = 579:
plus

Width = 520:
notequal, equal

Width = 701:
logicalnot

Width = 617:
plusminus

Width = 509:
multiply

Width = 514:
divide

Width = 504:
minus

Width = 587:
approxequal

Width = 456:
greaterequal, lessequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* at (U+0040): X=687.0,Y=-2.0 (should be at baseline 0?)

	* S (U+0053): X=213.0,Y=1.5 (should be at baseline 0?)

	* bracketleft (U+005B): X=322.0,Y=698.0 (should be at cap-height 700?)

	* bracketleft (U+005B): X=198.0,Y=698.0 (should be at cap-height 700?)

	* bracketright (U+005D): X=191.0,Y=698.0 (should be at cap-height 700?)

	* bracketright (U+005D): X=67.0,Y=698.0 (should be at cap-height 700?)

	* g (U+0067): X=294.0,Y=-1.0 (should be at baseline 0?)

	* Oslash (U+00D8): X=506.5,Y=699.0 (should be at cap-height 700?)

	* gbreve (U+011F): X=294.0,Y=-1.0 (should be at baseline 0?)

	* gdotaccent (U+0121): X=294.0,Y=-1.0 (should be at baseline 0?)

	* uni0123 (U+0123): X=294.0,Y=-1.0 (should be at baseline 0?)

	* Sacute (U+015A): X=213.0,Y=1.5 (should be at baseline 0?)

	* Scedilla (U+015E): X=213.0,Y=1.5 (should be at baseline 0?)

	* Scaron (U+0160): X=213.0,Y=1.5 (should be at baseline 0?)

	* Uogonek (U+0172): X=394.0,Y=1.0 (should be at baseline 0?)

	* uni0218 (U+0218): X=213.0,Y=1.5 (should be at baseline 0?)

	* uni0326 (U+0326): X=108.0,Y=-1.0 (should be at baseline 0?)

	* quotedblright (U+201D): X=274.0,Y=701.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=420.0,Y=701.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=72.0,Y=701.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=218.0,Y=701.0 (should be at cap-height 700?)

	* uni20B9 (U+20B9): X=38.0,Y=701.0 (should be at cap-height 700?) 

	* uni20B9 (U+20B9): X=572.0,Y=701.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* parenleft (U+0028) contains a short segment L<<379.0,811.0>--<379.0,798.0>>

	* parenright (U+0029) contains a short segment L<<25.0,-145.0>--<25.0,-132.0>>

	* at (U+0040) contains a short segment B<<667.0,129.5>-<675.0,115.0>-<690.0,115.0>>

	* R (U+0052) contains a short segment L<<315.0,265.0>--<315.0,265.0>>

	* R (U+0052) contains a short segment L<<315.0,265.0>--<314.0,265.0>>

	* yen (U+00A5) contains a short segment L<<250.0,241.0>--<250.0,244.0>>

	* yen (U+00A5) contains a short segment L<<390.0,244.0>--<390.0,241.0>>

	* paragraph (U+00B6) contains a short segment L<<303.0,280.0>--<284.0,280.0>>

	* germandbls (U+00DF) contains a short segment L<<249.0,425.0>--<265.0,425.0>>

	* ae (U+00E6) contains a short segment L<<367.0,296.0>--<367.0,305.0>>

	* eng (U+014B) contains a short segment L<<394.0,0.0>--<393.0,0.0>>

	* Racute (U+0154) contains a short segment L<<315.0,265.0>--<315.0,265.0>>

	* Racute (U+0154) contains a short segment L<<315.0,265.0>--<314.0,265.0>>

	* uni0156 (U+0156) contains a short segment L<<315.0,265.0>--<315.0,265.0>>

	* uni0156 (U+0156) contains a short segment L<<315.0,265.0>--<314.0,265.0>>

	* Rcaron (U+0158) contains a short segment L<<315.0,265.0>--<315.0,265.0>>

	* Rcaron (U+0158) contains a short segment L<<315.0,265.0>--<314.0,265.0>>

	* aeacute (U+01FD) contains a short segment L<<367.0,296.0>--<367.0,305.0>>

	* uni20A8 (U+20A8) contains a short segment L<<320.0,265.0>--<320.0,265.0>> 

	* uni20A8 (U+20A8) contains a short segment L<<320.0,265.0>--<319.0,265.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* R (U+0052): L<<315.0,265.0>--<314.0,265.0>> -> L<<314.0,265.0>--<187.0,265.0>>

	* Racute (U+0154): L<<315.0,265.0>--<314.0,265.0>> -> L<<314.0,265.0>--<187.0,265.0>>

	* Rcaron (U+0158): L<<315.0,265.0>--<314.0,265.0>> -> L<<314.0,265.0>--<187.0,265.0>>

	* uni0156 (U+0156): L<<315.0,265.0>--<314.0,265.0>> -> L<<314.0,265.0>--<187.0,265.0>> 

	* uni20A8 (U+20A8): L<<320.0,265.0>--<319.0,265.0>> -> L<<319.0,265.0>--<192.0,265.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* eng (U+014B): L<<294.0,-220.0>--<295.0,-101.0>>

	* summation (U+2211): L<<26.0,-50.0>--<27.0,113.0>>

	* summation (U+2211): L<<27.0,538.0>--<28.0,700.0>>

	* trademark (U+2122): L<<197.0,617.0>--<198.0,349.0>> 

	* trademark (U+2122): L<<94.0,349.0>--<95.0,617.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[16] HostGrotesk-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.10.8 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret positioning values for these ligature glyphs:
	- fi

   [code: incomplete-caret-pos-data]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- periodcentered.loclCAT

	- periodcentered.loclCAT.case 

	- uni030C.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Eng	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni2113	Contours detected: 1	Expected: 2

	- Glyph name: Eng	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni2113	Contours detected: 1	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 514 among a set of 3 math glyphs.
The following math glyphs have a different width, though:

Width = 579:
plus

Width = 520:
notequal, equal

Width = 701:
logicalnot

Width = 617:
plusminus

Width = 509:
multiply

Width = 504:
minus

Width = 587:
approxequal

Width = 456:
greaterequal, lessequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* at (U+0040): X=195.5,Y=2.0 (should be at baseline 0?)

	* S (U+0053): X=211.0,Y=1.5 (should be at baseline 0?)

	* S (U+0053): X=403.0,Y=2.0 (should be at baseline 0?)

	* y (U+0079): X=229.0,Y=-2.0 (should be at baseline 0?)

	* cent (U+00A2): X=364.0,Y=-2.0 (should be at baseline 0?)

	* section (U+00A7): X=308.0,Y=-261.0 (should be at descender -260?)

	* section (U+00A7): X=308.0,Y=-261.0 (should be at descender -260?)

	* Oslash (U+00D8): X=508.5,Y=698.0 (should be at cap-height 700?)

	* yacute (U+00FD): X=229.0,Y=-2.0 (should be at baseline 0?)

	* ydieresis (U+00FF): X=229.0,Y=-2.0 (should be at baseline 0?)

	* Sacute (U+015A): X=211.0,Y=1.5 (should be at baseline 0?)

	* Sacute (U+015A): X=403.0,Y=2.0 (should be at baseline 0?)

	* Scedilla (U+015E): X=211.0,Y=1.5 (should be at baseline 0?)

	* Scedilla (U+015E): X=403.0,Y=2.0 (should be at baseline 0?)

	* Scaron (U+0160): X=211.0,Y=1.5 (should be at baseline 0?)

	* Scaron (U+0160): X=403.0,Y=2.0 (should be at baseline 0?)

	* Uogonek (U+0172): X=392.0,Y=1.0 (should be at baseline 0?)

	* ycircumflex (U+0177): X=229.0,Y=-2.0 (should be at baseline 0?)

	* uni0218 (U+0218): X=211.0,Y=1.5 (should be at baseline 0?)

	* uni0218 (U+0218): X=403.0,Y=2.0 (should be at baseline 0?)

	* ygrave (U+1EF3): X=229.0,Y=-2.0 (should be at baseline 0?)

	* uni1EF9 (U+1EF9): X=229.0,Y=-2.0 (should be at baseline 0?)

	* quotedblright (U+201D): X=279.0,Y=701.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=414.0,Y=701.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=80.0,Y=701.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=215.0,Y=701.0 (should be at cap-height 700?)

	* uni20B9 (U+20B9): X=37.0,Y=701.0 (should be at cap-height 700?) 

	* uni20B9 (U+20B9): X=573.0,Y=701.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* parenleft (U+0028) contains a short segment L<<371.0,811.0>--<371.0,799.0>>

	* parenright (U+0029) contains a short segment L<<33.0,-145.0>--<33.0,-133.0>>

	* at (U+0040) contains a short segment B<<664.0,119.0>-<673.0,104.0>-<690.0,104.0>>

	* R (U+0052) contains a short segment L<<311.0,270.0>--<311.0,270.0>>

	* R (U+0052) contains a short segment L<<311.0,270.0>--<310.0,270.0>>

	* yen (U+00A5) contains a short segment L<<256.0,238.0>--<256.0,249.0>>

	* yen (U+00A5) contains a short segment L<<384.0,249.0>--<384.0,238.0>>

	* paragraph (U+00B6) contains a short segment L<<306.0,283.0>--<289.0,283.0>>

	* germandbls (U+00DF) contains a short segment L<<246.0,423.0>--<267.0,423.0>>

	* ae (U+00E6) contains a short segment L<<372.0,296.0>--<372.0,305.0>>

	* eng (U+014B) contains a short segment L<<400.0,0.0>--<400.0,0.0>>

	* Racute (U+0154) contains a short segment L<<311.0,270.0>--<311.0,270.0>>

	* Racute (U+0154) contains a short segment L<<311.0,270.0>--<310.0,270.0>>

	* uni0156 (U+0156) contains a short segment L<<311.0,270.0>--<311.0,270.0>>

	* uni0156 (U+0156) contains a short segment L<<311.0,270.0>--<310.0,270.0>>

	* Rcaron (U+0158) contains a short segment L<<311.0,270.0>--<311.0,270.0>>

	* Rcaron (U+0158) contains a short segment L<<311.0,270.0>--<310.0,270.0>>

	* aeacute (U+01FD) contains a short segment L<<372.0,296.0>--<372.0,305.0>>

	* uni20A8 (U+20A8) contains a short segment L<<321.0,270.0>--<321.0,270.0>> 

	* uni20A8 (U+20A8) contains a short segment L<<321.0,270.0>--<320.0,270.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* R (U+0052): L<<311.0,270.0>--<310.0,270.0>> -> L<<310.0,270.0>--<180.0,270.0>>

	* Racute (U+0154): L<<311.0,270.0>--<310.0,270.0>> -> L<<310.0,270.0>--<180.0,270.0>>

	* Rcaron (U+0158): L<<311.0,270.0>--<310.0,270.0>> -> L<<310.0,270.0>--<180.0,270.0>>

	* uni0156 (U+0156): L<<311.0,270.0>--<310.0,270.0>> -> L<<310.0,270.0>--<180.0,270.0>> 

	* uni20A8 (U+20A8): L<<321.0,270.0>--<320.0,270.0>> -> L<<320.0,270.0>--<190.0,270.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* daggerdbl (U+2021): L<<257.0,-30.0>--<57.0,-31.0>>

	* daggerdbl (U+2021): L<<257.0,455.0>--<57.0,454.0>>

	* daggerdbl (U+2021): L<<359.0,67.0>--<558.0,68.0>>

	* daggerdbl (U+2021): L<<558.0,-31.0>--<359.0,-30.0>>

	* daggerdbl (U+2021): L<<558.0,454.0>--<359.0,455.0>>

	* daggerdbl (U+2021): L<<57.0,68.0>--<257.0,67.0>>

	* summation (U+2211): L<<30.0,-50.0>--<31.0,99.0>>

	* summation (U+2211): L<<31.0,552.0>--<32.0,700.0>>

	* trademark (U+2122): L<<102.0,349.0>--<103.0,623.0>> 

	* trademark (U+2122): L<<197.0,623.0>--<198.0,349.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[16] HostGrotesk-Italic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.10.8 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret positioning values for these ligature glyphs:
	- fi

   [code: incomplete-caret-pos-data]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- periodcentered.loclCAT

	- periodcentered.loclCAT.case 

	- uni030C.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Eng	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni2113	Contours detected: 1	Expected: 2

	- Glyph name: Eng	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni2113	Contours detected: 1	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 499 among a set of 2 math glyphs.
The following math glyphs have a different width, though:

Width = 579:
plus

Width = 520:
notequal, equal

Width = 701:
logicalnot

Width = 617:
plusminus

Width = 509:
multiply

Width = 514:
divide

Width = 504:
minus

Width = 587:
approxequal

Width = 456:
greaterequal, lessequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* dieresis (U+00A8): X=253.0,Y=701.0 (should be at cap-height 700?)

	* dieresis (U+00A8): X=357.0,Y=701.0 (should be at cap-height 700?)

	* dieresis (U+00A8): X=94.0,Y=701.0 (should be at cap-height 700?)

	* dieresis (U+00A8): X=198.0,Y=701.0 (should be at cap-height 700?)

	* Ccedilla (U+00C7): X=228.0,Y=-261.0 (should be at descender -260?)

	* Ccedilla (U+00C7): X=338.0,Y=-261.0 (should be at descender -260?)

	* adieresis (U+00E4): X=362.0,Y=701.0 (should be at cap-height 700?)

	* adieresis (U+00E4): X=466.0,Y=701.0 (should be at cap-height 700?)

	* adieresis (U+00E4): X=203.0,Y=701.0 (should be at cap-height 700?)

	* adieresis (U+00E4): X=307.0,Y=701.0 (should be at cap-height 700?)

	* ccedilla (U+00E7): X=122.0,Y=-262.0 (should be at descender -260?)

	* ccedilla (U+00E7): X=232.0,Y=-262.0 (should be at descender -260?)

	* edieresis (U+00EB): X=379.0,Y=701.0 (should be at cap-height 700?)

	* edieresis (U+00EB): X=483.0,Y=701.0 (should be at cap-height 700?)

	* edieresis (U+00EB): X=220.0,Y=701.0 (should be at cap-height 700?)

	* edieresis (U+00EB): X=324.0,Y=701.0 (should be at cap-height 700?)

	* idieresis (U+00EF): X=196.0,Y=701.0 (should be at cap-height 700?)

	* idieresis (U+00EF): X=300.0,Y=701.0 (should be at cap-height 700?)

	* idieresis (U+00EF): X=37.0,Y=701.0 (should be at cap-height 700?)

	* idieresis (U+00EF): X=141.0,Y=701.0 (should be at cap-height 700?)

	* eth (U+00F0): X=335.0,Y=701.0 (should be at cap-height 700?)

	* eth (U+00F0): X=422.0,Y=699.0 (should be at cap-height 700?)

	* odieresis (U+00F6): X=373.0,Y=701.0 (should be at cap-height 700?)

	* odieresis (U+00F6): X=477.0,Y=701.0 (should be at cap-height 700?)

	* odieresis (U+00F6): X=214.0,Y=701.0 (should be at cap-height 700?)

	* odieresis (U+00F6): X=318.0,Y=701.0 (should be at cap-height 700?)

	* udieresis (U+00FC): X=366.0,Y=701.0 (should be at cap-height 700?)

	* udieresis (U+00FC): X=470.0,Y=701.0 (should be at cap-height 700?)

	* udieresis (U+00FC): X=207.0,Y=701.0 (should be at cap-height 700?)

	* udieresis (U+00FC): X=311.0,Y=701.0 (should be at cap-height 700?)

	* ydieresis (U+00FF): X=391.0,Y=701.0 (should be at cap-height 700?)

	* ydieresis (U+00FF): X=495.0,Y=701.0 (should be at cap-height 700?)

	* ydieresis (U+00FF): X=232.0,Y=701.0 (should be at cap-height 700?)

	* ydieresis (U+00FF): X=336.0,Y=701.0 (should be at cap-height 700?)

	* cdotaccent (U+010B): X=301.0,Y=702.0 (should be at cap-height 700?)

	* cdotaccent (U+010B): X=410.0,Y=702.0 (should be at cap-height 700?)

	* edotaccent (U+0117): X=297.0,Y=701.0 (should be at cap-height 700?)

	* edotaccent (U+0117): X=406.0,Y=701.0 (should be at cap-height 700?)

	* gdotaccent (U+0121): X=269.0,Y=701.0 (should be at cap-height 700?)

	* gdotaccent (U+0121): X=378.0,Y=701.0 (should be at cap-height 700?)

	* Iogonek (U+012E): X=128.0,Y=1.0 (should be at baseline 0?)

	* iogonek (U+012F): X=114.0,Y=701.0 (should be at cap-height 700?)

	* iogonek (U+012F): X=223.0,Y=701.0 (should be at cap-height 700?)

	* ohungarumlaut (U+0151): X=440.0,Y=701.0 (should be at cap-height 700?)

	* ohungarumlaut (U+0151): X=532.0,Y=701.0 (should be at cap-height 700?)

	* ohungarumlaut (U+0151): X=299.0,Y=701.0 (should be at cap-height 700?)

	* ohungarumlaut (U+0151): X=391.0,Y=701.0 (should be at cap-height 700?)

	* Scedilla (U+015E): X=146.0,Y=-261.0 (should be at descender -260?)

	* Scedilla (U+015E): X=256.0,Y=-261.0 (should be at descender -260?)

	* scedilla (U+015F): X=82.0,Y=-261.0 (should be at descender -260?)

	* scedilla (U+015F): X=192.0,Y=-261.0 (should be at descender -260?)

	* uni0162 (U+0162): X=128.0,Y=-261.0 (should be at descender -260?)

	* uni0162 (U+0162): X=238.0,Y=-261.0 (should be at descender -260?)

	* uni0163 (U+0163): X=87.0,Y=-261.0 (should be at descender -260?)

	* uni0163 (U+0163): X=197.0,Y=-261.0 (should be at descender -260?)

	* uhungarumlaut (U+0171): X=433.0,Y=701.0 (should be at cap-height 700?)

	* uhungarumlaut (U+0171): X=525.0,Y=701.0 (should be at cap-height 700?)

	* uhungarumlaut (U+0171): X=292.0,Y=701.0 (should be at cap-height 700?)

	* uhungarumlaut (U+0171): X=384.0,Y=701.0 (should be at cap-height 700?)

	* zdotaccent (U+017C): X=239.0,Y=701.0 (should be at cap-height 700?)

	* zdotaccent (U+017C): X=348.0,Y=701.0 (should be at cap-height 700?)

	* dotaccent (U+02D9): X=94.0,Y=701.0 (should be at cap-height 700?)

	* dotaccent (U+02D9): X=203.0,Y=701.0 (should be at cap-height 700?)

	* hungarumlaut (U+02DD): X=302.0,Y=701.0 (should be at cap-height 700?)

	* hungarumlaut (U+02DD): X=394.0,Y=701.0 (should be at cap-height 700?)

	* hungarumlaut (U+02DD): X=161.0,Y=701.0 (should be at cap-height 700?)

	* hungarumlaut (U+02DD): X=253.0,Y=701.0 (should be at cap-height 700?)

	* uni0307 (U+0307): X=94.0,Y=701.0 (should be at cap-height 700?)

	* uni0307 (U+0307): X=203.0,Y=701.0 (should be at cap-height 700?)

	* uni0308 (U+0308): X=253.0,Y=701.0 (should be at cap-height 700?)

	* uni0308 (U+0308): X=357.0,Y=701.0 (should be at cap-height 700?)

	* uni0308 (U+0308): X=94.0,Y=701.0 (should be at cap-height 700?)

	* uni0308 (U+0308): X=198.0,Y=701.0 (should be at cap-height 700?)

	* uni030B (U+030B): X=302.0,Y=701.0 (should be at cap-height 700?)

	* uni030B (U+030B): X=394.0,Y=701.0 (should be at cap-height 700?)

	* uni030B (U+030B): X=161.0,Y=701.0 (should be at cap-height 700?)

	* uni030B (U+030B): X=253.0,Y=701.0 (should be at cap-height 700?)

	* wdieresis (U+1E85): X=493.0,Y=701.0 (should be at cap-height 700?)

	* wdieresis (U+1E85): X=597.0,Y=701.0 (should be at cap-height 700?)

	* wdieresis (U+1E85): X=334.0,Y=701.0 (should be at cap-height 700?) 

	* wdieresis (U+1E85): X=438.0,Y=701.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* ampersand (U+0026) contains a short segment L<<326.0,366.0>--<323.0,366.0>>

	* parenleft (U+0028) contains a short segment L<<432.0,811.0>--<432.0,801.0>>

	* parenright (U+0029) contains a short segment L<<-4.0,-145.0>--<-3.0,-135.0>>

	* comma (U+002C) contains a short segment L<<58.0,-47.0>--<58.0,-47.0>>

	* semicolon (U+003B) contains a short segment L<<57.0,-47.0>--<57.0,-47.0>>

	* m (U+006D) contains a short segment L<<501.0,256.0>--<501.0,256.0>>

	* m (U+006D) contains a short segment L<<159.0,256.0>--<159.0,256.0>>

	* paragraph (U+00B6) contains a short segment L<<320.0,294.0>--<309.0,294.0>>

	* cedilla (U+00B8) contains a short segment B<<13.0,-107.0>-<13.0,-104.0>-<14.0,-101.0>>

	* Ccedilla (U+00C7) contains a short segment B<<282.0,-108.0>-<282.0,-105.0>-<283.0,-102.0>>

	* ae (U+00E6) contains a short segment L<<399.0,297.0>--<400.0,306.0>>

	* ae (U+00E6) contains a short segment B<<872.0,274.0>-<870.0,265.0>-<868.5,254.0>>

	* ccedilla (U+00E7) contains a short segment B<<176.0,-109.0>-<176.0,-106.0>-<177.0,-103.0>>

	* Scedilla (U+015E) contains a short segment B<<200.0,-108.0>-<200.0,-105.0>-<201.0,-102.0>>

	* scedilla (U+015F) contains a short segment B<<136.0,-108.0>-<136.0,-105.0>-<137.0,-102.0>>

	* uni0162 (U+0162) contains a short segment B<<182.0,-108.0>-<182.0,-105.0>-<183.0,-102.0>>

	* uni0163 (U+0163) contains a short segment B<<141.0,-108.0>-<141.0,-105.0>-<142.0,-102.0>>

	* aeacute (U+01FD) contains a short segment L<<399.0,297.0>--<400.0,306.0>>

	* aeacute (U+01FD) contains a short segment B<<872.0,274.0>-<870.0,265.0>-<868.5,254.0>>

	* uni0327 (U+0327) contains a short segment B<<13.0,-107.0>-<13.0,-104.0>-<14.0,-101.0>>

	* uni20B9 (U+20B9) contains a short segment B<<401.0,524.0>-<402.0,529.0>-<402.0,535.0>> 

	* uni20B9 (U+20B9) contains a short segment B<<487.0,533.0>-<486.0,528.0>-<485.0,524.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* comma (U+002C): L<<157.0,114.0>--<140.0,-6.0>> -> L<<140.0,-6.0>--<133.0,-48.0>> 

	* semicolon (U+003B): L<<156.0,114.0>--<139.0,-6.0>> -> L<<139.0,-6.0>--<132.0,-48.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* eng (U+014B): B<<215.5,385.0>-<167.0,339.0>-<156.0,256.0>>/L<<156.0,256.0>--<156.0,258.0>> = 7.549421768263246

	* eng (U+014B): L<<156.0,256.0>--<156.0,258.0>>/L<<156.0,258.0>--<120.0,0.0>> = 7.943471810590413

	* h (U+0068): B<<217.0,385.0>-<167.0,339.0>-<156.0,256.0>>/L<<156.0,256.0>--<156.0,257.0>> = 7.549421768263246

	* h (U+0068): L<<156.0,256.0>--<156.0,257.0>>/L<<156.0,257.0>--<120.0,0.0>> = 7.973983450297689

	* hbar (U+0127): B<<285.0,385.0>-<235.0,339.0>-<224.0,256.0>>/L<<224.0,256.0>--<224.0,257.0>> = 7.549421768263246

	* hbar (U+0127): L<<224.0,256.0>--<224.0,257.0>>/L<<224.0,257.0>--<188.0,0.0>> = 7.973983450297689

	* n (U+006E): B<<215.5,385.0>-<167.0,339.0>-<156.0,256.0>>/L<<156.0,256.0>--<156.0,258.0>> = 7.549421768263246

	* n (U+006E): L<<156.0,256.0>--<156.0,258.0>>/L<<156.0,258.0>--<120.0,0.0>> = 7.943471810590413

	* nacute (U+0144): B<<215.5,385.0>-<167.0,339.0>-<156.0,256.0>>/L<<156.0,256.0>--<156.0,258.0>> = 7.549421768263246

	* nacute (U+0144): L<<156.0,256.0>--<156.0,258.0>>/L<<156.0,258.0>--<120.0,0.0>> = 7.943471810590413

	* ncaron (U+0148): B<<215.5,385.0>-<167.0,339.0>-<156.0,256.0>>/L<<156.0,256.0>--<156.0,258.0>> = 7.549421768263246

	* ncaron (U+0148): L<<156.0,256.0>--<156.0,258.0>>/L<<156.0,258.0>--<120.0,0.0>> = 7.943471810590413

	* ntilde (U+00F1): B<<215.5,385.0>-<167.0,339.0>-<156.0,256.0>>/L<<156.0,256.0>--<156.0,258.0>> = 7.549421768263246

	* ntilde (U+00F1): L<<156.0,256.0>--<156.0,258.0>>/L<<156.0,258.0>--<120.0,0.0>> = 7.943471810590413

	* partialdiff (U+2202): B<<431.0,534.0>-<465.0,511.0>-<472.0,449.0>>/B<<472.0,449.0>-<480.0,517.0>-<472.0,570.5>> = 13.151436907091933

	* r (U+0072): B<<213.0,374.0>-<177.0,332.0>-<163.0,235.0>>/L<<163.0,235.0>--<163.0,236.0>> = 8.212780189285867

	* r (U+0072): L<<163.0,235.0>--<163.0,236.0>>/L<<163.0,236.0>--<130.0,0.0>> = 7.960085703275638

	* racute (U+0155): B<<213.0,374.0>-<177.0,332.0>-<163.0,235.0>>/L<<163.0,235.0>--<163.0,236.0>> = 8.212780189285867

	* racute (U+0155): L<<163.0,235.0>--<163.0,236.0>>/L<<163.0,236.0>--<130.0,0.0>> = 7.960085703275638

	* rcaron (U+0159): B<<213.0,374.0>-<177.0,332.0>-<163.0,235.0>>/L<<163.0,235.0>--<163.0,236.0>> = 8.212780189285867

	* rcaron (U+0159): L<<163.0,235.0>--<163.0,236.0>>/L<<163.0,236.0>--<130.0,0.0>> = 7.960085703275638

	* uni0146 (U+0146): B<<215.5,385.0>-<167.0,339.0>-<156.0,256.0>>/L<<156.0,256.0>--<156.0,258.0>> = 7.549421768263246

	* uni0146 (U+0146): L<<156.0,256.0>--<156.0,258.0>>/L<<156.0,258.0>--<120.0,0.0>> = 7.943471810590413

	* uni0157 (U+0157): B<<213.0,374.0>-<177.0,332.0>-<163.0,235.0>>/L<<163.0,235.0>--<163.0,236.0>> = 8.212780189285867 

	* uni0157 (U+0157): L<<163.0,235.0>--<163.0,236.0>>/L<<163.0,236.0>--<130.0,0.0>> = 7.960085703275638 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[16] HostGrotesk-MediumItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.10.8 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret positioning values for these ligature glyphs:
	- fi

   [code: incomplete-caret-pos-data]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- periodcentered.loclCAT

	- periodcentered.loclCAT.case 

	- uni030C.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Eng	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni2113	Contours detected: 1	Expected: 2

	- Glyph name: Eng	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni2113	Contours detected: 1	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 507 among a set of 2 math glyphs.
The following math glyphs have a different width, though:

Width = 579:
plus

Width = 520:
notequal, equal

Width = 701:
logicalnot

Width = 617:
plusminus

Width = 509:
multiply

Width = 514:
divide

Width = 504:
minus

Width = 587:
approxequal

Width = 456:
greaterequal, lessequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* S (U+0053): X=190.0,Y=2.0 (should be at baseline 0?)

	* braceleft (U+007B): X=111.0,Y=-1.0 (should be at baseline 0?)

	* braceright (U+007D): X=200.0,Y=702.0 (should be at cap-height 700?)

	* cedilla (U+00B8): X=-42.0,Y=-261.0 (should be at descender -260?)

	* cedilla (U+00B8): X=80.0,Y=-261.0 (should be at descender -260?)

	* eth (U+00F0): X=330.0,Y=701.0 (should be at cap-height 700?)

	* eth (U+00F0): X=432.0,Y=699.0 (should be at cap-height 700?)

	* abreve (U+0103): X=186.0,Y=698.0 (should be at cap-height 700?)

	* abreve (U+0103): X=485.0,Y=698.0 (should be at cap-height 700?)

	* ebreve (U+0115): X=203.0,Y=698.0 (should be at cap-height 700?)

	* ebreve (U+0115): X=502.0,Y=698.0 (should be at cap-height 700?)

	* gbreve (U+011F): X=181.0,Y=698.0 (should be at cap-height 700?)

	* gbreve (U+011F): X=480.0,Y=698.0 (should be at cap-height 700?)

	* ibreve (U+012D): X=21.0,Y=698.0 (should be at cap-height 700?)

	* ibreve (U+012D): X=320.0,Y=698.0 (should be at cap-height 700?)

	* obreve (U+014F): X=197.0,Y=698.0 (should be at cap-height 700?)

	* obreve (U+014F): X=496.0,Y=698.0 (should be at cap-height 700?)

	* Sacute (U+015A): X=190.0,Y=2.0 (should be at baseline 0?)

	* Scedilla (U+015E): X=190.0,Y=2.0 (should be at baseline 0?)

	* Scaron (U+0160): X=190.0,Y=2.0 (should be at baseline 0?)

	* ubreve (U+016D): X=192.0,Y=698.0 (should be at cap-height 700?)

	* ubreve (U+016D): X=491.0,Y=698.0 (should be at cap-height 700?)

	* Uogonek (U+0172): X=355.0,Y=1.0 (should be at baseline 0?)

	* uni0218 (U+0218): X=190.0,Y=2.0 (should be at baseline 0?)

	* breve (U+02D8): X=94.0,Y=698.0 (should be at cap-height 700?)

	* breve (U+02D8): X=393.0,Y=698.0 (should be at cap-height 700?)

	* uni0306 (U+0306): X=94.0,Y=698.0 (should be at cap-height 700?)

	* uni0306 (U+0306): X=393.0,Y=698.0 (should be at cap-height 700?)

	* uni0327 (U+0327): X=-42.0,Y=-261.0 (should be at descender -260?)

	* uni0327 (U+0327): X=80.0,Y=-261.0 (should be at descender -260?)

	* quotedblright (U+201D): X=344.0,Y=701.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=463.0,Y=701.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=166.0,Y=701.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=286.0,Y=701.0 (should be at cap-height 700?)

	* dagger (U+2020): X=182.0,Y=-261.0 (should be at descender -260?)

	* dagger (U+2020): X=292.0,Y=-261.0 (should be at descender -260?)

	* daggerdbl (U+2021): X=181.0,Y=-261.0 (should be at descender -260?)

	* daggerdbl (U+2021): X=292.0,Y=-261.0 (should be at descender -260?)

	* uni20B9 (U+20B9): X=100.0,Y=701.0 (should be at cap-height 700?) 

	* uni20B9 (U+20B9): X=638.0,Y=701.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* parenleft (U+0028) contains a short segment L<<442.0,811.0>--<441.0,799.0>>

	* parenright (U+0029) contains a short segment L<<-13.0,-145.0>--<-13.0,-132.0>>

	* comma (U+002C) contains a short segment L<<58.0,-39.0>--<58.0,-39.0>>

	* semicolon (U+003B) contains a short segment L<<53.0,-39.0>--<53.0,-39.0>>

	* Q (U+0051) contains a short segment B<<677.0,105.0>-<683.0,99.0>-<689.5,97.5>>

	* yen (U+00A5) contains a short segment L<<265.0,234.0>--<268.0,256.0>>

	* yen (U+00A5) contains a short segment L<<378.0,256.0>--<375.0,234.0>>

	* paragraph (U+00B6) contains a short segment L<<308.0,288.0>--<296.0,288.0>>

	* ae (U+00E6) contains a short segment L<<390.0,296.0>--<391.0,307.0>>

	* ae (U+00E6) contains a short segment B<<876.0,265.0>-<875.0,257.0>-<873.0,245.5>>

	* aeacute (U+01FD) contains a short segment L<<390.0,296.0>--<391.0,307.0>>

	* aeacute (U+01FD) contains a short segment B<<876.0,265.0>-<875.0,257.0>-<873.0,245.5>>

	* uni20B9 (U+20B9) contains a short segment L<<392.0,525.0>--<392.0,526.0>> 

	* integral (U+222B) contains a short segment L<<391.0,830.0>--<375.0,830.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* comma (U+002C): L<<169.0,129.0>--<150.0,-6.0>> -> L<<150.0,-6.0>--<145.0,-41.0>>

	* eng (U+014B): L<<369.0,-71.0>--<411.0,220.0>> -> L<<411.0,220.0>--<419.0,275.0>> 

	* semicolon (U+003B): L<<164.0,129.0>--<145.0,-6.0>> -> L<<145.0,-6.0>--<140.0,-41.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* eng (U+014B): B<<221.0,372.0>-<176.0,330.0>-<166.0,254.0>>/L<<166.0,254.0>--<166.0,259.0>> = 7.495857639729836

	* eng (U+014B): L<<166.0,254.0>--<166.0,259.0>>/L<<166.0,259.0>--<129.0,0.0>> = 8.13010235415596

	* h (U+0068): B<<222.0,372.0>-<176.0,330.0>-<166.0,254.0>>/L<<166.0,254.0>--<166.0,258.0>> = 7.495857639729836

	* h (U+0068): L<<166.0,254.0>--<166.0,258.0>>/L<<166.0,258.0>--<129.0,0.0>> = 8.161190674226654

	* hbar (U+0127): B<<291.0,372.0>-<245.0,330.0>-<235.0,254.0>>/L<<235.0,254.0>--<235.0,258.0>> = 7.495857639729836

	* hbar (U+0127): L<<235.0,254.0>--<235.0,258.0>>/L<<235.0,258.0>--<198.0,0.0>> = 8.161190674226654

	* m (U+006D): B<<219.5,372.0>-<178.0,330.0>-<167.0,254.0>>/L<<167.0,254.0>--<167.0,255.0>> = 8.235619324209488

	* m (U+006D): L<<167.0,254.0>--<167.0,255.0>>/L<<167.0,255.0>--<131.0,0.0>> = 8.03571071053479

	* n (U+006E): B<<221.0,372.0>-<176.0,330.0>-<166.0,254.0>>/L<<166.0,254.0>--<166.0,259.0>> = 7.495857639729836

	* n (U+006E): L<<166.0,254.0>--<166.0,259.0>>/L<<166.0,259.0>--<129.0,0.0>> = 8.13010235415596

	* nacute (U+0144): B<<221.0,372.0>-<176.0,330.0>-<166.0,254.0>>/L<<166.0,254.0>--<166.0,259.0>> = 7.495857639729836

	* nacute (U+0144): L<<166.0,254.0>--<166.0,259.0>>/L<<166.0,259.0>--<129.0,0.0>> = 8.13010235415596

	* ncaron (U+0148): B<<221.0,372.0>-<176.0,330.0>-<166.0,254.0>>/L<<166.0,254.0>--<166.0,259.0>> = 7.495857639729836

	* ncaron (U+0148): L<<166.0,254.0>--<166.0,259.0>>/L<<166.0,259.0>--<129.0,0.0>> = 8.13010235415596

	* ntilde (U+00F1): B<<221.0,372.0>-<176.0,330.0>-<166.0,254.0>>/L<<166.0,254.0>--<166.0,259.0>> = 7.495857639729836

	* ntilde (U+00F1): L<<166.0,254.0>--<166.0,259.0>>/L<<166.0,259.0>--<129.0,0.0>> = 8.13010235415596

	* u (U+0075): B<<348.0,124.0>-<393.0,166.0>-<404.0,242.0>>/L<<404.0,242.0>--<404.0,241.0>> = 8.235619324209488

	* u (U+0075): L<<404.0,242.0>--<404.0,241.0>>/L<<404.0,241.0>--<440.0,496.0>> = 8.03571071053479

	* uacute (U+00FA): B<<348.0,124.0>-<393.0,166.0>-<404.0,242.0>>/L<<404.0,242.0>--<404.0,241.0>> = 8.235619324209488

	* uacute (U+00FA): L<<404.0,242.0>--<404.0,241.0>>/L<<404.0,241.0>--<440.0,496.0>> = 8.03571071053479

	* ubreve (U+016D): B<<348.0,124.0>-<393.0,166.0>-<404.0,242.0>>/L<<404.0,242.0>--<404.0,241.0>> = 8.235619324209488

	* ubreve (U+016D): L<<404.0,242.0>--<404.0,241.0>>/L<<404.0,241.0>--<440.0,496.0>> = 8.03571071053479

	* ucircumflex (U+00FB): B<<348.0,124.0>-<393.0,166.0>-<404.0,242.0>>/L<<404.0,242.0>--<404.0,241.0>> = 8.235619324209488

	* ucircumflex (U+00FB): L<<404.0,242.0>--<404.0,241.0>>/L<<404.0,241.0>--<440.0,496.0>> = 8.03571071053479

	* udieresis (U+00FC): B<<348.0,124.0>-<393.0,166.0>-<404.0,242.0>>/L<<404.0,242.0>--<404.0,241.0>> = 8.235619324209488

	* udieresis (U+00FC): L<<404.0,242.0>--<404.0,241.0>>/L<<404.0,241.0>--<440.0,496.0>> = 8.03571071053479

	* ugrave (U+00F9): B<<348.0,124.0>-<393.0,166.0>-<404.0,242.0>>/L<<404.0,242.0>--<404.0,241.0>> = 8.235619324209488

	* ugrave (U+00F9): L<<404.0,242.0>--<404.0,241.0>>/L<<404.0,241.0>--<440.0,496.0>> = 8.03571071053479

	* uhungarumlaut (U+0171): B<<348.0,124.0>-<393.0,166.0>-<404.0,242.0>>/L<<404.0,242.0>--<404.0,241.0>> = 8.235619324209488

	* uhungarumlaut (U+0171): L<<404.0,242.0>--<404.0,241.0>>/L<<404.0,241.0>--<440.0,496.0>> = 8.03571071053479

	* umacron (U+016B): B<<348.0,124.0>-<393.0,166.0>-<404.0,242.0>>/L<<404.0,242.0>--<404.0,241.0>> = 8.235619324209488

	* umacron (U+016B): L<<404.0,242.0>--<404.0,241.0>>/L<<404.0,241.0>--<440.0,496.0>> = 8.03571071053479

	* uni0146 (U+0146): B<<221.0,372.0>-<176.0,330.0>-<166.0,254.0>>/L<<166.0,254.0>--<166.0,259.0>> = 7.495857639729836

	* uni0146 (U+0146): L<<166.0,254.0>--<166.0,259.0>>/L<<166.0,259.0>--<129.0,0.0>> = 8.13010235415596

	* uogonek (U+0173): B<<348.0,124.0>-<393.0,166.0>-<404.0,242.0>>/L<<404.0,242.0>--<404.0,241.0>> = 8.235619324209488

	* uogonek (U+0173): L<<404.0,242.0>--<404.0,241.0>>/L<<404.0,241.0>--<440.0,496.0>> = 8.03571071053479

	* uring (U+016F): B<<348.0,124.0>-<393.0,166.0>-<404.0,242.0>>/L<<404.0,242.0>--<404.0,241.0>> = 8.235619324209488

	* uring (U+016F): L<<404.0,242.0>--<404.0,241.0>>/L<<404.0,241.0>--<440.0,496.0>> = 8.03571071053479

	* utilde (U+0169): B<<348.0,124.0>-<393.0,166.0>-<404.0,242.0>>/L<<404.0,242.0>--<404.0,241.0>> = 8.235619324209488 

	* utilde (U+0169): L<<404.0,242.0>--<404.0,241.0>>/L<<404.0,241.0>--<440.0,496.0>> = 8.03571071053479 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[16] HostGrotesk-LightItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.10.8 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret positioning values for these ligature glyphs:
	- fi

   [code: incomplete-caret-pos-data]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- periodcentered.loclCAT

	- periodcentered.loclCAT.case 

	- uni030C.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Eng	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni2113	Contours detected: 1	Expected: 2

	- Glyph name: Eng	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni2113	Contours detected: 1	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 492 among a set of 2 math glyphs.
The following math glyphs have a different width, though:

Width = 579:
plus

Width = 520:
notequal, equal

Width = 701:
logicalnot

Width = 617:
plusminus

Width = 509:
multiply

Width = 514:
divide

Width = 504:
minus

Width = 587:
approxequal

Width = 456:
greaterequal, lessequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* cedilla (U+00B8): X=-41.0,Y=-258.0 (should be at descender -260?)

	* cedilla (U+00B8): X=59.0,Y=-258.0 (should be at descender -260?)

	* Ccedilla (U+00C7): X=236.0,Y=-258.0 (should be at descender -260?)

	* Ccedilla (U+00C7): X=336.0,Y=-258.0 (should be at descender -260?)

	* ccedilla (U+00E7): X=130.0,Y=-259.0 (should be at descender -260?)

	* ccedilla (U+00E7): X=230.0,Y=-259.0 (should be at descender -260?)

	* cdotaccent (U+010B): X=305.0,Y=701.0 (should be at cap-height 700?)

	* cdotaccent (U+010B): X=406.0,Y=701.0 (should be at cap-height 700?)

	* uni0123 (U+0123): X=401.0,Y=702.0 (should be at cap-height 700?)

	* Iogonek (U+012E): X=118.0,Y=1.0 (should be at baseline 0?)

	* Scedilla (U+015E): X=156.0,Y=-258.0 (should be at descender -260?)

	* Scedilla (U+015E): X=256.0,Y=-258.0 (should be at descender -260?)

	* scedilla (U+015F): X=90.0,Y=-258.0 (should be at descender -260?)

	* scedilla (U+015F): X=190.0,Y=-258.0 (should be at descender -260?)

	* uni0162 (U+0162): X=135.0,Y=-258.0 (should be at descender -260?)

	* uni0162 (U+0162): X=235.0,Y=-258.0 (should be at descender -260?)

	* uni0163 (U+0163): X=100.0,Y=-258.0 (should be at descender -260?)

	* uni0163 (U+0163): X=200.0,Y=-258.0 (should be at descender -260?)

	* uni0312 (U+0312): X=235.0,Y=702.0 (should be at cap-height 700?)

	* uni0327 (U+0327): X=-41.0,Y=-258.0 (should be at descender -260?)

	* uni0327 (U+0327): X=59.0,Y=-258.0 (should be at descender -260?)

	* dagger (U+2020): X=203.0,Y=-258.0 (should be at descender -260?)

	* dagger (U+2020): X=272.0,Y=-258.0 (should be at descender -260?)

	* daggerdbl (U+2021): X=202.0,Y=-258.0 (should be at descender -260?)

	* daggerdbl (U+2021): X=271.0,Y=-258.0 (should be at descender -260?)

	* uni20BA (U+20BA): X=271.0,Y=702.0 (should be at cap-height 700?)

	* uni20BA (U+20BA): X=343.0,Y=702.0 (should be at cap-height 700?)

	* uni20BA (U+20BA): X=172.0,Y=-1.0 (should be at baseline 0?)

	* fi (U+FB01): X=475.0,Y=702.0 (should be at cap-height 700?) 

	* fi (U+FB01): X=577.0,Y=702.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* parenleft (U+0028) contains a short segment L<<423.0,811.0>--<422.0,804.0>>

	* parenright (U+0029) contains a short segment L<<5.0,-145.0>--<6.0,-137.0>>

	* G (U+0047) contains a short segment L<<734.0,371.0>--<731.0,346.0>>

	* a (U+0061) contains a short segment L<<504.0,0.0>--<489.0,0.0>>

	* m (U+006D) contains a short segment L<<492.0,257.0>--<492.0,257.0>>

	* m (U+006D) contains a short segment L<<150.0,257.0>--<150.0,257.0>>

	* n (U+006E) contains a short segment L<<146.0,257.0>--<146.0,257.0>>

	* r (U+0072) contains a short segment L<<154.0,247.0>--<154.0,247.0>>

	* paragraph (U+00B6) contains a short segment L<<331.0,299.0>--<323.0,299.0>>

	* cedilla (U+00B8) contains a short segment B<<14.0,-106.0>-<14.0,-103.0>-<15.0,-101.0>>

	* Ccedilla (U+00C7) contains a short segment B<<291.0,-106.0>-<291.0,-103.0>-<292.0,-101.0>>

	* agrave (U+00E0) contains a short segment L<<504.0,0.0>--<489.0,0.0>>

	* aacute (U+00E1) contains a short segment L<<504.0,0.0>--<489.0,0.0>>

	* acircumflex (U+00E2) contains a short segment L<<504.0,0.0>--<489.0,0.0>>

	* atilde (U+00E3) contains a short segment L<<504.0,0.0>--<489.0,0.0>>

	* adieresis (U+00E4) contains a short segment L<<504.0,0.0>--<489.0,0.0>>

	* aring (U+00E5) contains a short segment L<<504.0,0.0>--<489.0,0.0>>

	* ae (U+00E6) contains a short segment L<<407.0,297.0>--<408.0,305.0>>

	* ae (U+00E6) contains a short segment B<<867.0,283.0>-<866.0,273.0>-<864.0,262.0>>

	* ccedilla (U+00E7) contains a short segment B<<185.0,-107.0>-<185.0,-104.0>-<186.0,-102.0>>

	* ntilde (U+00F1) contains a short segment L<<146.0,257.0>--<146.0,257.0>>

	* amacron (U+0101) contains a short segment L<<504.0,0.0>--<489.0,0.0>>

	* abreve (U+0103) contains a short segment L<<504.0,0.0>--<489.0,0.0>>

	* aogonek (U+0105) contains a short segment L<<504.0,0.0>--<489.0,0.0>>

	* Gbreve (U+011E) contains a short segment L<<734.0,371.0>--<731.0,346.0>>

	* Gdotaccent (U+0120) contains a short segment L<<734.0,371.0>--<731.0,346.0>>

	* uni0122 (U+0122) contains a short segment L<<734.0,371.0>--<731.0,346.0>>

	* nacute (U+0144) contains a short segment L<<146.0,257.0>--<146.0,257.0>>

	* uni0146 (U+0146) contains a short segment L<<146.0,257.0>--<146.0,257.0>>

	* ncaron (U+0148) contains a short segment L<<146.0,257.0>--<146.0,257.0>>

	* eng (U+014B) contains a short segment L<<146.0,257.0>--<146.0,257.0>>

	* racute (U+0155) contains a short segment L<<154.0,247.0>--<154.0,247.0>>

	* uni0157 (U+0157) contains a short segment L<<154.0,247.0>--<154.0,247.0>>

	* rcaron (U+0159) contains a short segment L<<154.0,247.0>--<154.0,247.0>>

	* Scedilla (U+015E) contains a short segment B<<211.0,-106.0>-<211.0,-103.0>-<212.0,-101.0>>

	* scedilla (U+015F) contains a short segment B<<145.0,-106.0>-<145.0,-103.0>-<146.0,-101.0>>

	* uni0162 (U+0162) contains a short segment B<<190.0,-106.0>-<190.0,-103.0>-<191.0,-101.0>>

	* uni0163 (U+0163) contains a short segment B<<155.0,-106.0>-<155.0,-103.0>-<156.0,-101.0>>

	* aeacute (U+01FD) contains a short segment L<<407.0,297.0>--<408.0,305.0>>

	* aeacute (U+01FD) contains a short segment B<<867.0,283.0>-<866.0,273.0>-<864.0,262.0>>

	* uni0327 (U+0327) contains a short segment B<<14.0,-106.0>-<14.0,-103.0>-<15.0,-101.0>>

	* uni20B9 (U+20B9) contains a short segment B<<410.0,523.0>-<411.0,533.0>-<413.0,544.0>> 

	* uni20B9 (U+20B9) contains a short segment B<<479.0,543.0>-<478.0,533.0>-<476.0,523.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* comma (U+002C): L<<144.0,98.0>--<130.0,-5.0>> -> L<<130.0,-5.0>--<122.0,-55.0>> 

	* semicolon (U+003B): L<<147.0,98.0>--<133.0,-5.0>> -> L<<133.0,-5.0>--<125.0,-55.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* partialdiff (U+2202): B<<442.0,530.0>-<478.0,504.0>-<482.0,432.0>>/B<<482.0,432.0>-<492.0,507.0>-<485.0,567.0>> = 10.774473488455637 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[16] HostGrotesk-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.10.8 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret positioning values for these ligature glyphs:
	- fi

   [code: incomplete-caret-pos-data]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- periodcentered.loclCAT

	- periodcentered.loclCAT.case 

	- uni030C.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Eng	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni2113	Contours detected: 1	Expected: 2

	- Glyph name: Eng	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni2113	Contours detected: 1	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 492 among a set of 2 math glyphs.
The following math glyphs have a different width, though:

Width = 579:
plus

Width = 520:
notequal, equal

Width = 701:
logicalnot

Width = 617:
plusminus

Width = 509:
multiply

Width = 514:
divide

Width = 504:
minus

Width = 587:
approxequal

Width = 456:
greaterequal, lessequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* cedilla (U+00B8): X=0.0,Y=-258.0 (should be at descender -260?)

	* cedilla (U+00B8): X=100.0,Y=-258.0 (should be at descender -260?)

	* Ccedilla (U+00C7): X=303.0,Y=-258.0 (should be at descender -260?)

	* Ccedilla (U+00C7): X=403.0,Y=-258.0 (should be at descender -260?)

	* ccedilla (U+00E7): X=197.0,Y=-259.0 (should be at descender -260?)

	* ccedilla (U+00E7): X=297.0,Y=-259.0 (should be at descender -260?)

	* cdotaccent (U+010B): X=237.0,Y=701.0 (should be at cap-height 700?)

	* cdotaccent (U+010B): X=338.0,Y=701.0 (should be at cap-height 700?)

	* uni0123 (U+0123): X=319.5,Y=702.0 (should be at cap-height 700?)

	* lacute (U+013A): X=253.0,Y=961.0 (should be at ascender 960?)

	* Scedilla (U+015E): X=235.0,Y=-258.0 (should be at descender -260?)

	* Scedilla (U+015E): X=335.0,Y=-258.0 (should be at descender -260?)

	* scedilla (U+015F): X=168.0,Y=-258.0 (should be at descender -260?)

	* scedilla (U+015F): X=268.0,Y=-258.0 (should be at descender -260?)

	* uni0162 (U+0162): X=203.0,Y=-258.0 (should be at descender -260?)

	* uni0162 (U+0162): X=303.0,Y=-258.0 (should be at descender -260?)

	* uni0163 (U+0163): X=153.0,Y=-258.0 (should be at descender -260?)

	* uni0163 (U+0163): X=253.0,Y=-258.0 (should be at descender -260?)

	* uni0312 (U+0312): X=126.5,Y=702.0 (should be at cap-height 700?)

	* uni0327 (U+0327): X=0.0,Y=-258.0 (should be at descender -260?)

	* uni0327 (U+0327): X=100.0,Y=-258.0 (should be at descender -260?)

	* dagger (U+2020): X=265.0,Y=-258.0 (should be at descender -260?)

	* dagger (U+2020): X=334.0,Y=-258.0 (should be at descender -260?)

	* daggerdbl (U+2021): X=271.0,Y=-258.0 (should be at descender -260?)

	* daggerdbl (U+2021): X=340.0,Y=-258.0 (should be at descender -260?)

	* uni20BA (U+20BA): X=228.0,Y=702.0 (should be at cap-height 700?)

	* uni20BA (U+20BA): X=300.0,Y=702.0 (should be at cap-height 700?)

	* uni20BA (U+20BA): X=228.0,Y=-1.0 (should be at baseline 0?)

	* fi (U+FB01): X=418.0,Y=702.0 (should be at cap-height 700?) 

	* fi (U+FB01): X=520.0,Y=702.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* parenleft (U+0028) contains a short segment L<<332.0,811.0>--<332.0,804.0>>

	* parenright (U+0029) contains a short segment L<<72.0,-145.0>--<72.0,-138.0>>

	* G (U+0047) contains a short segment L<<717.0,371.0>--<717.0,346.0>>

	* a (U+0061) contains a short segment L<<537.0,0.0>--<522.0,0.0>>

	* paragraph (U+00B6) contains a short segment L<<321.0,299.0>--<313.0,299.0>>

	* cedilla (U+00B8) contains a short segment B<<33.0,-106.0>-<33.0,-103.0>-<34.0,-101.0>>

	* Ccedilla (U+00C7) contains a short segment B<<336.0,-106.0>-<336.0,-103.0>-<337.0,-101.0>>

	* agrave (U+00E0) contains a short segment L<<537.0,0.0>--<522.0,0.0>>

	* aacute (U+00E1) contains a short segment L<<537.0,0.0>--<522.0,0.0>>

	* acircumflex (U+00E2) contains a short segment L<<537.0,0.0>--<522.0,0.0>>

	* atilde (U+00E3) contains a short segment L<<537.0,0.0>--<522.0,0.0>>

	* adieresis (U+00E4) contains a short segment L<<537.0,0.0>--<522.0,0.0>>

	* aring (U+00E5) contains a short segment L<<537.0,0.0>--<522.0,0.0>>

	* ae (U+00E6) contains a short segment L<<394.0,297.0>--<394.0,305.0>>

	* ae (U+00E6) contains a short segment B<<856.0,283.0>-<856.0,273.0>-<856.0,262.0>>

	* ccedilla (U+00E7) contains a short segment B<<230.0,-107.0>-<230.0,-104.0>-<231.0,-102.0>>

	* amacron (U+0101) contains a short segment L<<537.0,0.0>--<522.0,0.0>>

	* abreve (U+0103) contains a short segment L<<537.0,0.0>--<522.0,0.0>>

	* aogonek (U+0105) contains a short segment L<<537.0,0.0>--<522.0,0.0>>

	* Gbreve (U+011E) contains a short segment L<<717.0,371.0>--<717.0,346.0>>

	* Gdotaccent (U+0120) contains a short segment L<<717.0,371.0>--<717.0,346.0>>

	* uni0122 (U+0122) contains a short segment L<<717.0,371.0>--<717.0,346.0>>

	* Scedilla (U+015E) contains a short segment B<<268.0,-106.0>-<268.0,-103.0>-<269.0,-101.0>>

	* scedilla (U+015F) contains a short segment B<<201.0,-106.0>-<201.0,-103.0>-<202.0,-101.0>>

	* uni0162 (U+0162) contains a short segment B<<236.0,-106.0>-<236.0,-103.0>-<237.0,-101.0>>

	* uni0163 (U+0163) contains a short segment B<<186.0,-106.0>-<186.0,-103.0>-<187.0,-101.0>>

	* aeacute (U+01FD) contains a short segment L<<394.0,297.0>--<394.0,305.0>>

	* aeacute (U+01FD) contains a short segment B<<856.0,283.0>-<856.0,273.0>-<856.0,262.0>>

	* uni0327 (U+0327) contains a short segment B<<33.0,-106.0>-<33.0,-103.0>-<34.0,-101.0>>

	* uni20B9 (U+20B9) contains a short segment B<<370.0,523.0>-<370.0,533.0>-<370.0,544.0>> 

	* uni20B9 (U+20B9) contains a short segment B<<436.0,543.0>-<436.0,533.0>-<436.0,523.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* eth (U+00F0): B<<401.5,487.0>-<454.0,466.0>-<487.0,415.0>>/B<<487.0,415.0>-<470.0,465.0>-<443.5,511.5>> = 14.127209700542345 

	* partialdiff (U+2202): B<<406.0,530.0>-<445.0,504.0>-<460.0,432.0>>/B<<460.0,432.0>-<460.0,507.0>-<444.5,567.0>> = 11.768288932020628 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* trademark (U+2122): L<<141.0,348.0>--<142.0,654.0>>

	* trademark (U+2122): L<<198.0,654.0>--<199.0,348.0>> 

	* trademark (U+2122): L<<694.0,348.0>--<693.0,617.0>> [code: found-semi-vertical]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 20 | 141 | 1172 | 61 | 913 | 0 |
| 0% | 1% | 6% | 51% | 3% | 40% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
