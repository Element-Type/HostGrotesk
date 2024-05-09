## Fontbakery report

Fontbakery version: 0.8.13

<details><summary><b>[15] HostGrotesk-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 372, but got 277 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.12.5 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ [code: soft-dotted]
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


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni030C.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Eng	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Eng	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* at (U+0040): X=195.5,Y=2.0 (should be at baseline 0?)

	* S (U+0053): X=211.0,Y=1.5 (should be at baseline 0?)

	* S (U+0053): X=403.0,Y=2.0 (should be at baseline 0?)

	* y (U+0079): X=229.0,Y=-2.0 (should be at baseline 0?)

	* braceleft (U+007B): X=236.0,Y=2.0 (should be at baseline 0?)

	* braceright (U+007D): X=149.0,Y=2.0 (should be at baseline 0?)

	* Aring (U+00C5): X=337.0,Y=975.0 (should be at ascender 977?)

	* Oslash (U+00D8): X=278.5,Y=1.5 (should be at baseline 0?)

	* yacute (U+00FD): X=229.0,Y=-2.0 (should be at baseline 0?)

	* ydieresis (U+00FF): X=229.0,Y=-2.0 (should be at baseline 0?)

	* Sacute (U+015A): X=211.0,Y=1.5 (should be at baseline 0?)

	* Sacute (U+015A): X=403.0,Y=2.0 (should be at baseline 0?)

	* Scedilla (U+015E): X=211.0,Y=1.5 (should be at baseline 0?)

	* Scedilla (U+015E): X=403.0,Y=2.0 (should be at baseline 0?)

	* Scaron (U+0160): X=211.0,Y=1.5 (should be at baseline 0?)

	* Scaron (U+0160): X=403.0,Y=2.0 (should be at baseline 0?)

	* Uring (U+016E): X=317.0,Y=975.0 (should be at ascender 977?)

	* Uogonek (U+0172): X=393.0,Y=1.0 (should be at baseline 0?)

	* ycircumflex (U+0177): X=229.0,Y=-2.0 (should be at baseline 0?)

	* uni0218 (U+0218): X=211.0,Y=1.5 (should be at baseline 0?)

	* uni0218 (U+0218): X=403.0,Y=2.0 (should be at baseline 0?)

	* ygrave (U+1EF3): X=229.0,Y=-2.0 (should be at baseline 0?)

	* uni1EF9 (U+1EF9): X=229.0,Y=-2.0 (should be at baseline 0?)

	* quotedblright (U+201D): X=279.0,Y=701.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=414.0,Y=701.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=80.0,Y=701.0 (should be at cap-height 700?) 

	* quotedblright (U+201D): X=215.0,Y=701.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* at (U+0040) contains a short segment B<<664.0,119.0>-<673.0,104.0>-<690.0,104.0>>

	* R (U+0052) contains a short segment L<<344.0,270.0>--<344.0,270.0>>

	* R (U+0052) contains a short segment L<<344.0,270.0>--<343.0,270.0>>

	* yen (U+00A5) contains a short segment L<<261.0,238.0>--<261.0,249.0>>

	* yen (U+00A5) contains a short segment L<<389.0,249.0>--<389.0,238.0>>

	* paragraph (U+00B6) contains a short segment L<<306.0,283.0>--<289.0,283.0>>

	* germandbls (U+00DF) contains a short segment L<<230.0,423.0>--<251.0,423.0>>

	* ae (U+00E6) contains a short segment L<<367.0,296.0>--<367.0,305.0>>

	* eng (U+014B) contains a short segment L<<400.0,0.0>--<400.0,0.0>>

	* Racute (U+0154) contains a short segment L<<344.0,270.0>--<344.0,270.0>>

	* Racute (U+0154) contains a short segment L<<344.0,270.0>--<343.0,270.0>>

	* uni0156 (U+0156) contains a short segment L<<344.0,270.0>--<344.0,270.0>>

	* uni0156 (U+0156) contains a short segment L<<344.0,270.0>--<343.0,270.0>>

	* Rcaron (U+0158) contains a short segment L<<344.0,270.0>--<344.0,270.0>>

	* Rcaron (U+0158) contains a short segment L<<344.0,270.0>--<343.0,270.0>> 

	* aeacute (U+01FD) contains a short segment L<<367.0,296.0>--<367.0,305.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* R (U+0052): L<<344.0,270.0>--<343.0,270.0>> -> L<<343.0,270.0>--<180.0,270.0>>

	* Racute (U+0154): L<<344.0,270.0>--<343.0,270.0>> -> L<<343.0,270.0>--<180.0,270.0>>

	* Rcaron (U+0158): L<<344.0,270.0>--<343.0,270.0>> -> L<<343.0,270.0>--<180.0,270.0>> 

	* uni0156 (U+0156): L<<344.0,270.0>--<343.0,270.0>> -> L<<343.0,270.0>--<180.0,270.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* summation (U+2211): L<<30.0,-50.0>--<31.0,99.0>>

	* summation (U+2211): L<<31.0,552.0>--<32.0,700.0>>

	* trademark (U+2122): L<<102.0,349.0>--<103.0,623.0>> 

	* trademark (U+2122): L<<197.0,623.0>--<198.0,349.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[15] HostGrotesk-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 372, but got 277 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.12.5 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ [code: soft-dotted]
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


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni030C.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Eng	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Eng	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* cdotaccent (U+010B): X=230.0,Y=701.0 (should be at cap-height 700?)

	* cdotaccent (U+010B): X=330.0,Y=701.0 (should be at cap-height 700?)

	* uni0123 (U+0123): X=287.5,Y=702.0 (should be at cap-height 700?)

	* uni0312 (U+0312): X=-6.5,Y=702.0 (should be at cap-height 700?)

	* fi (U+FB01): X=393.0,Y=702.0 (should be at cap-height 700?) 

	* fi (U+FB01): X=495.0,Y=702.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* G (U+0047) contains a short segment L<<691.0,371.0>--<691.0,346.0>>

	* a (U+0061) contains a short segment L<<519.0,0.0>--<504.0,0.0>>

	* paragraph (U+00B6) contains a short segment L<<321.0,299.0>--<313.0,299.0>>

	* cedilla (U+00B8) contains a short segment B<<125.0,-106.0>-<125.0,-103.0>-<126.0,-101.0>>

	* Ccedilla (U+00C7) contains a short segment B<<299.0,-106.0>-<299.0,-103.0>-<300.0,-101.0>>

	* agrave (U+00E0) contains a short segment L<<519.0,0.0>--<504.0,0.0>>

	* aacute (U+00E1) contains a short segment L<<519.0,0.0>--<504.0,0.0>>

	* acircumflex (U+00E2) contains a short segment L<<519.0,0.0>--<504.0,0.0>>

	* atilde (U+00E3) contains a short segment L<<519.0,0.0>--<504.0,0.0>>

	* adieresis (U+00E4) contains a short segment L<<519.0,0.0>--<504.0,0.0>>

	* aring (U+00E5) contains a short segment L<<519.0,0.0>--<504.0,0.0>>

	* ae (U+00E6) contains a short segment L<<387.0,297.0>--<387.0,305.0>>

	* ae (U+00E6) contains a short segment B<<849.0,283.0>-<849.0,273.0>-<849.0,262.0>>

	* ccedilla (U+00E7) contains a short segment B<<211.0,-107.0>-<211.0,-104.0>-<212.0,-102.0>>

	* amacron (U+0101) contains a short segment L<<519.0,0.0>--<504.0,0.0>>

	* abreve (U+0103) contains a short segment L<<519.0,0.0>--<504.0,0.0>>

	* aogonek (U+0105) contains a short segment L<<519.0,0.0>--<504.0,0.0>>

	* Gbreve (U+011E) contains a short segment L<<691.0,371.0>--<691.0,346.0>>

	* Gdotaccent (U+0120) contains a short segment L<<691.0,371.0>--<691.0,346.0>>

	* uni0122 (U+0122) contains a short segment L<<691.0,371.0>--<691.0,346.0>>

	* Scedilla (U+015E) contains a short segment B<<256.0,-106.0>-<256.0,-103.0>-<257.0,-101.0>>

	* scedilla (U+015F) contains a short segment B<<187.0,-106.0>-<187.0,-103.0>-<188.0,-101.0>>

	* uni0162 (U+0162) contains a short segment B<<224.0,-106.0>-<224.0,-103.0>-<225.0,-101.0>>

	* uni0163 (U+0163) contains a short segment B<<137.0,-106.0>-<137.0,-103.0>-<138.0,-101.0>>

	* uni018F (U+018F) contains a short segment L<<118.0,306.0>--<118.0,305.0>>

	* uni01CE (U+01CE) contains a short segment L<<519.0,0.0>--<504.0,0.0>>

	* aeacute (U+01FD) contains a short segment L<<387.0,297.0>--<387.0,305.0>>

	* aeacute (U+01FD) contains a short segment B<<849.0,283.0>-<849.0,273.0>-<849.0,262.0>> 

	* uni0327 (U+0327) contains a short segment B<<-75.0,-106.0>-<-75.0,-103.0>-<-74.0,-101.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* eth (U+00F0): B<<391.5,487.0>-<444.0,466.0>-<477.0,415.0>>/B<<477.0,415.0>-<460.0,465.0>-<433.5,511.5>> = 14.127209700542345 

	* partialdiff (U+2202): B<<406.0,530.0>-<445.0,504.0>-<460.0,432.0>>/B<<460.0,432.0>-<460.0,507.0>-<444.5,567.0>> = 11.768288932020628 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* asterisk (U+002A): L<<182.0,520.0>--<47.0,519.0>>

	* asterisk (U+002A): L<<280.0,574.0>--<415.0,575.0>>

	* asterisk (U+002A): L<<415.0,519.0>--<280.0,520.0>>

	* asterisk (U+002A): L<<47.0,575.0>--<182.0,574.0>>

	* trademark (U+2122): L<<141.0,348.0>--<142.0,654.0>>

	* trademark (U+2122): L<<198.0,654.0>--<199.0,348.0>> 

	* trademark (U+2122): L<<694.0,348.0>--<693.0,617.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[15] HostGrotesk-LightItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 372, but got 277 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.12.5 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
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


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
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

	- uni01CE.ss02 

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

	- Glyph name: Eng	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* cdotaccent (U+010B): X=294.0,Y=701.0 (should be at cap-height 700?)

	* cdotaccent (U+010B): X=395.0,Y=701.0 (should be at cap-height 700?)

	* uni0123 (U+0123): X=399.0,Y=702.0 (should be at cap-height 700?)

	* Iogonek (U+012E): X=118.0,Y=1.0 (should be at baseline 0?)

	* uni0312 (U+0312): X=235.0,Y=702.0 (should be at cap-height 700?)

	* fi (U+FB01): X=458.0,Y=702.0 (should be at cap-height 700?) 

	* fi (U+FB01): X=560.0,Y=702.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* G (U+0047) contains a short segment L<<708.0,371.0>--<705.0,346.0>>

	* a (U+0061) contains a short segment L<<490.0,0.0>--<475.0,0.0>>

	* m (U+006D) contains a short segment L<<487.0,257.0>--<487.0,257.0>>

	* m (U+006D) contains a short segment L<<145.0,257.0>--<145.0,257.0>>

	* n (U+006E) contains a short segment L<<145.0,257.0>--<145.0,257.0>>

	* r (U+0072) contains a short segment L<<144.0,247.0>--<144.0,247.0>>

	* paragraph (U+00B6) contains a short segment L<<331.0,299.0>--<323.0,299.0>>

	* cedilla (U+00B8) contains a short segment B<<76.0,-106.0>-<76.0,-103.0>-<77.0,-101.0>>

	* Ccedilla (U+00C7) contains a short segment B<<268.0,-106.0>-<268.0,-103.0>-<269.0,-101.0>>

	* agrave (U+00E0) contains a short segment L<<490.0,0.0>--<475.0,0.0>>

	* aacute (U+00E1) contains a short segment L<<490.0,0.0>--<475.0,0.0>>

	* acircumflex (U+00E2) contains a short segment L<<490.0,0.0>--<475.0,0.0>>

	* atilde (U+00E3) contains a short segment L<<490.0,0.0>--<475.0,0.0>>

	* adieresis (U+00E4) contains a short segment L<<490.0,0.0>--<475.0,0.0>>

	* aring (U+00E5) contains a short segment L<<490.0,0.0>--<475.0,0.0>>

	* ae (U+00E6) contains a short segment L<<406.0,297.0>--<407.0,305.0>>

	* ae (U+00E6) contains a short segment B<<866.0,283.0>-<865.0,273.0>-<863.0,262.0>>

	* ccedilla (U+00E7) contains a short segment B<<174.0,-107.0>-<174.0,-104.0>-<175.0,-102.0>>

	* ntilde (U+00F1) contains a short segment L<<145.0,257.0>--<145.0,257.0>>

	* amacron (U+0101) contains a short segment L<<490.0,0.0>--<475.0,0.0>>

	* abreve (U+0103) contains a short segment L<<490.0,0.0>--<475.0,0.0>>

	* aogonek (U+0105) contains a short segment L<<490.0,0.0>--<475.0,0.0>>

	* Gbreve (U+011E) contains a short segment L<<708.0,371.0>--<705.0,346.0>>

	* Gdotaccent (U+0120) contains a short segment L<<708.0,371.0>--<705.0,346.0>>

	* uni0122 (U+0122) contains a short segment L<<708.0,371.0>--<705.0,346.0>>

	* nacute (U+0144) contains a short segment L<<145.0,257.0>--<145.0,257.0>>

	* uni0146 (U+0146) contains a short segment L<<145.0,257.0>--<145.0,257.0>>

	* ncaron (U+0148) contains a short segment L<<145.0,257.0>--<145.0,257.0>>

	* eng (U+014B) contains a short segment L<<402.0,0.0>--<401.0,0.0>>

	* eng (U+014B) contains a short segment L<<145.0,257.0>--<145.0,257.0>>

	* racute (U+0155) contains a short segment L<<144.0,247.0>--<144.0,247.0>>

	* uni0157 (U+0157) contains a short segment L<<144.0,247.0>--<144.0,247.0>>

	* rcaron (U+0159) contains a short segment L<<144.0,247.0>--<144.0,247.0>>

	* Scedilla (U+015E) contains a short segment B<<197.0,-105.0>-<197.0,-102.0>-<198.0,-100.0>>

	* scedilla (U+015F) contains a short segment B<<142.0,-106.0>-<142.0,-103.0>-<143.0,-101.0>>

	* uni0162 (U+0162) contains a short segment B<<190.0,-106.0>-<190.0,-103.0>-<191.0,-101.0>>

	* uni0163 (U+0163) contains a short segment B<<117.0,-106.0>-<117.0,-103.0>-<118.0,-101.0>>

	* uni01CE (U+01CE) contains a short segment L<<490.0,0.0>--<475.0,0.0>>

	* aeacute (U+01FD) contains a short segment L<<406.0,297.0>--<407.0,305.0>>

	* aeacute (U+01FD) contains a short segment B<<866.0,283.0>-<865.0,273.0>-<863.0,262.0>> 

	* uni0327 (U+0327) contains a short segment B<<14.0,-106.0>-<14.0,-103.0>-<15.0,-101.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* partialdiff (U+2202): B<<442.0,530.0>-<478.0,504.0>-<482.0,432.0>>/B<<482.0,432.0>-<492.0,507.0>-<485.0,567.0>> = 10.774473488455637 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[16] HostGrotesk-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 372, but got 277 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.12.5 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ [code: soft-dotted]
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


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni030C.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Eng	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Eng	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* S (U+0053): X=402.5,Y=1.5 (should be at baseline 0?)

	* Sacute (U+015A): X=402.5,Y=1.5 (should be at baseline 0?)

	* Scedilla (U+015E): X=402.5,Y=1.5 (should be at baseline 0?)

	* Scaron (U+0160): X=402.5,Y=1.5 (should be at baseline 0?)

	* tcaron (U+0165): X=335.0,Y=698.0 (should be at cap-height 700?)

	* tcaron (U+0165): X=282.0,Y=698.0 (should be at cap-height 700?)

	* Uogonek (U+0172): X=390.0,Y=1.0 (should be at baseline 0?)

	* uni0218 (U+0218): X=402.5,Y=1.5 (should be at baseline 0?)

	* quotedblright (U+201D): X=287.0,Y=701.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=405.0,Y=701.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=92.0,Y=701.0 (should be at cap-height 700?) 

	* quotedblright (U+201D): X=210.0,Y=701.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* at (U+0040) contains a short segment B<<660.5,104.0>-<671.0,88.0>-<690.0,88.0>>

	* R (U+0052) contains a short segment L<<343.0,277.0>--<343.0,277.0>>

	* R (U+0052) contains a short segment L<<343.0,277.0>--<343.0,277.0>>

	* yen (U+00A5) contains a short segment L<<270.0,234.0>--<270.0,256.0>>

	* yen (U+00A5) contains a short segment L<<380.0,256.0>--<380.0,234.0>>

	* paragraph (U+00B6) contains a short segment L<<311.0,288.0>--<296.0,288.0>>

	* cedilla (U+00B8) contains a short segment B<<108.0,-107.0>-<108.0,-104.0>-<109.0,-100.0>>

	* Ccedilla (U+00C7) contains a short segment B<<285.0,-109.0>-<285.0,-106.0>-<286.0,-102.0>>

	* ae (U+00E6) contains a short segment L<<373.0,296.0>--<373.0,305.0>>

	* ccedilla (U+00E7) contains a short segment B<<193.0,-109.0>-<193.0,-106.0>-<194.0,-102.0>>

	* eng (U+014B) contains a short segment L<<410.0,0.0>--<409.0,0.0>>

	* Racute (U+0154) contains a short segment L<<343.0,277.0>--<343.0,277.0>>

	* Racute (U+0154) contains a short segment L<<343.0,277.0>--<343.0,277.0>>

	* uni0156 (U+0156) contains a short segment L<<343.0,277.0>--<343.0,277.0>>

	* uni0156 (U+0156) contains a short segment L<<343.0,277.0>--<343.0,277.0>>

	* Rcaron (U+0158) contains a short segment L<<343.0,277.0>--<343.0,277.0>>

	* Rcaron (U+0158) contains a short segment L<<343.0,277.0>--<343.0,277.0>>

	* Scedilla (U+015E) contains a short segment B<<229.0,-109.0>-<229.0,-106.0>-<230.0,-102.0>>

	* scedilla (U+015F) contains a short segment B<<163.0,-109.0>-<163.0,-106.0>-<164.0,-102.0>>

	* uni0162 (U+0162) contains a short segment B<<207.0,-109.0>-<207.0,-106.0>-<208.0,-102.0>>

	* uni0163 (U+0163) contains a short segment B<<132.0,-109.0>-<132.0,-106.0>-<133.0,-102.0>>

	* aeacute (U+01FD) contains a short segment L<<373.0,296.0>--<373.0,305.0>> 

	* uni0327 (U+0327) contains a short segment B<<-92.0,-107.0>-<-92.0,-104.0>-<-91.0,-100.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* R (U+0052): L<<343.0,277.0>--<343.0,277.0>> -> L<<343.0,277.0>--<343.0,277.0>>

	* Racute (U+0154): L<<343.0,277.0>--<343.0,277.0>> -> L<<343.0,277.0>--<343.0,277.0>>

	* Rcaron (U+0158): L<<343.0,277.0>--<343.0,277.0>> -> L<<343.0,277.0>--<343.0,277.0>> 

	* uni0156 (U+0156): L<<343.0,277.0>--<343.0,277.0>> -> L<<343.0,277.0>--<343.0,277.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* greaterequal (U+2265): L<<122.0,428.0>--<77.0,437.0>>/L<<77.0,437.0>--<147.0,438.0>> = 12.128387935708812 

	* lessequal (U+2264): L<<443.0,438.0>--<513.0,437.0>>/L<<513.0,437.0>--<468.0,428.0>> = 12.128387935708812 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* asterisk (U+002A): L<<160.0,510.0>--<45.0,509.0>>

	* asterisk (U+002A): L<<417.0,509.0>--<302.0,510.0>>

	* greaterequal (U+2265): L<<266.0,439.0>--<147.0,438.0>>

	* lessequal (U+2264): L<<443.0,438.0>--<324.0,439.0>>

	* summation (U+2211): L<<37.0,573.0>--<38.0,700.0>>

	* trademark (U+2122): L<<114.0,349.0>--<115.0,633.0>>

	* trademark (U+2122): L<<197.0,633.0>--<198.0,349.0>> 

	* trademark (U+2122): L<<689.0,349.0>--<687.0,591.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[16] HostGrotesk-BoldItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 372, but got 277 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.12.5 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
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


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
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

	- uni01CE.ss02 

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

	- Glyph name: Eng	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* y (U+0079): X=180.0,Y=1.0 (should be at baseline 0?)

	* braceleft (U+007B): X=193.0,Y=2.0 (should be at baseline 0?)

	* braceright (U+007D): X=122.0,Y=2.0 (should be at baseline 0?)

	* Aring (U+00C5): X=438.0,Y=975.0 (should be at ascender 977?)

	* eth (U+00F0): X=323.0,Y=702.0 (should be at cap-height 700?)

	* eth (U+00F0): X=439.0,Y=698.0 (should be at cap-height 700?)

	* yacute (U+00FD): X=180.0,Y=1.0 (should be at baseline 0?)

	* ydieresis (U+00FF): X=180.0,Y=1.0 (should be at baseline 0?)

	* abreve (U+0103): X=168.0,Y=699.0 (should be at cap-height 700?)

	* abreve (U+0103): X=480.0,Y=699.0 (should be at cap-height 700?)

	* ebreve (U+0115): X=188.0,Y=699.0 (should be at cap-height 700?)

	* ebreve (U+0115): X=500.0,Y=699.0 (should be at cap-height 700?)

	* gbreve (U+011F): X=166.0,Y=699.0 (should be at cap-height 700?)

	* gbreve (U+011F): X=478.0,Y=699.0 (should be at cap-height 700?)

	* ibreve (U+012D): X=15.0,Y=699.0 (should be at cap-height 700?)

	* ibreve (U+012D): X=327.0,Y=699.0 (should be at cap-height 700?)

	* lacute (U+013A): X=384.0,Y=975.0 (should be at ascender 977?)

	* obreve (U+014F): X=196.0,Y=699.0 (should be at cap-height 700?)

	* obreve (U+014F): X=508.0,Y=699.0 (should be at cap-height 700?)

	* ubreve (U+016D): X=176.0,Y=699.0 (should be at cap-height 700?)

	* ubreve (U+016D): X=488.0,Y=699.0 (should be at cap-height 700?)

	* Uring (U+016E): X=419.0,Y=975.0 (should be at ascender 977?)

	* Uogonek (U+0172): X=358.0,Y=1.0 (should be at baseline 0?)

	* ycircumflex (U+0177): X=180.0,Y=1.0 (should be at baseline 0?)

	* breve (U+02D8): X=108.0,Y=699.0 (should be at cap-height 700?)

	* breve (U+02D8): X=420.0,Y=699.0 (should be at cap-height 700?)

	* uni0306 (U+0306): X=-64.0,Y=699.0 (should be at cap-height 700?)

	* uni0306 (U+0306): X=248.0,Y=699.0 (should be at cap-height 700?)

	* ygrave (U+1EF3): X=180.0,Y=1.0 (should be at baseline 0?)

	* uni1EF9 (U+1EF9): X=180.0,Y=1.0 (should be at baseline 0?)

	* quotedblright (U+201D): X=344.0,Y=701.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=480.0,Y=701.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=151.0,Y=701.0 (should be at cap-height 700?) 

	* quotedblright (U+201D): X=288.0,Y=701.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* at (U+0040) contains a short segment B<<647.5,121.0>-<657.0,104.0>-<675.0,104.0>>

	* yen (U+00A5) contains a short segment L<<260.0,238.0>--<262.0,249.0>>

	* yen (U+00A5) contains a short segment L<<390.0,249.0>--<388.0,238.0>>

	* paragraph (U+00B6) contains a short segment L<<298.0,283.0>--<283.0,283.0>>

	* germandbls (U+00DF) contains a short segment L<<263.0,423.0>--<283.0,423.0>>

	* ae (U+00E6) contains a short segment L<<381.0,296.0>--<382.0,307.0>>

	* eng (U+014B) contains a short segment L<<535.0,276.0>--<535.0,276.0>>

	* aeacute (U+01FD) contains a short segment L<<381.0,296.0>--<382.0,307.0>>

	* uni20B9 (U+20B9) contains a short segment L<<113.0,596.0>--<114.0,603.0>>

	* uni20B9 (U+20B9) contains a short segment L<<114.0,603.0>--<113.0,603.0>> 

	* integral (U+222B) contains a short segment L<<392.0,821.0>--<377.0,821.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* eng (U+014B): L<<361.0,-59.0>--<388.0,129.0>> -> L<<388.0,129.0>--<408.0,271.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* eng (U+014B): B<<225.5,360.5>-<184.0,321.0>-<175.0,253.0>>/L<<175.0,253.0>--<175.0,260.0>> = 7.539445139509295

	* eng (U+014B): L<<175.0,253.0>--<175.0,260.0>>/L<<175.0,260.0>--<138.0,0.0>> = 8.099248410173876

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

	* u (U+0075): B<<333.0,135.5>-<375.0,175.0>-<384.0,243.0>>/L<<384.0,243.0>--<384.0,241.0>> = 7.539445139509295

	* u (U+0075): L<<384.0,243.0>--<384.0,241.0>>/L<<384.0,241.0>--<420.0,496.0>> = 8.03571071053479

	* uacute (U+00FA): B<<333.0,135.5>-<375.0,175.0>-<384.0,243.0>>/L<<384.0,243.0>--<384.0,241.0>> = 7.539445139509295

	* uacute (U+00FA): L<<384.0,243.0>--<384.0,241.0>>/L<<384.0,241.0>--<420.0,496.0>> = 8.03571071053479

	* ubreve (U+016D): B<<333.0,135.5>-<375.0,175.0>-<384.0,243.0>>/L<<384.0,243.0>--<384.0,241.0>> = 7.539445139509295

	* ubreve (U+016D): L<<384.0,243.0>--<384.0,241.0>>/L<<384.0,241.0>--<420.0,496.0>> = 8.03571071053479

	* ucircumflex (U+00FB): B<<333.0,135.5>-<375.0,175.0>-<384.0,243.0>>/L<<384.0,243.0>--<384.0,241.0>> = 7.539445139509295

	* ucircumflex (U+00FB): L<<384.0,243.0>--<384.0,241.0>>/L<<384.0,241.0>--<420.0,496.0>> = 8.03571071053479

	* udieresis (U+00FC): B<<333.0,135.5>-<375.0,175.0>-<384.0,243.0>>/L<<384.0,243.0>--<384.0,241.0>> = 7.539445139509295

	* udieresis (U+00FC): L<<384.0,243.0>--<384.0,241.0>>/L<<384.0,241.0>--<420.0,496.0>> = 8.03571071053479

	* ugrave (U+00F9): B<<333.0,135.5>-<375.0,175.0>-<384.0,243.0>>/L<<384.0,243.0>--<384.0,241.0>> = 7.539445139509295

	* ugrave (U+00F9): L<<384.0,243.0>--<384.0,241.0>>/L<<384.0,241.0>--<420.0,496.0>> = 8.03571071053479

	* uhungarumlaut (U+0171): B<<333.0,135.5>-<375.0,175.0>-<384.0,243.0>>/L<<384.0,243.0>--<384.0,241.0>> = 7.539445139509295

	* uhungarumlaut (U+0171): L<<384.0,243.0>--<384.0,241.0>>/L<<384.0,241.0>--<420.0,496.0>> = 8.03571071053479

	* umacron (U+016B): B<<333.0,135.5>-<375.0,175.0>-<384.0,243.0>>/L<<384.0,243.0>--<384.0,241.0>> = 7.539445139509295

	* umacron (U+016B): L<<384.0,243.0>--<384.0,241.0>>/L<<384.0,241.0>--<420.0,496.0>> = 8.03571071053479

	* uni0146 (U+0146): B<<225.5,360.5>-<184.0,321.0>-<175.0,253.0>>/L<<175.0,253.0>--<175.0,260.0>> = 7.539445139509295

	* uni0146 (U+0146): L<<175.0,253.0>--<175.0,260.0>>/L<<175.0,260.0>--<138.0,0.0>> = 8.099248410173876

	* uogonek (U+0173): B<<333.0,135.5>-<375.0,175.0>-<384.0,243.0>>/L<<384.0,243.0>--<384.0,241.0>> = 7.539445139509295

	* uogonek (U+0173): L<<384.0,243.0>--<384.0,241.0>>/L<<384.0,241.0>--<420.0,496.0>> = 8.03571071053479

	* uring (U+016F): B<<333.0,135.5>-<375.0,175.0>-<384.0,243.0>>/L<<384.0,243.0>--<384.0,241.0>> = 7.539445139509295

	* uring (U+016F): L<<384.0,243.0>--<384.0,241.0>>/L<<384.0,241.0>--<420.0,496.0>> = 8.03571071053479

	* utilde (U+0169): B<<333.0,135.5>-<375.0,175.0>-<384.0,243.0>>/L<<384.0,243.0>--<384.0,241.0>> = 7.539445139509295 

	* utilde (U+0169): L<<384.0,243.0>--<384.0,241.0>>/L<<384.0,241.0>--<420.0,496.0>> = 8.03571071053479 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[15] HostGrotesk-Italic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 372, but got 277 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.12.5 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
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


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
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

	- uni01CE.ss02 

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

	- Glyph name: lessequal	Contours detected: 3	Expected: 2

	- Glyph name: greaterequal	Contours detected: 3	Expected: 2

	- Glyph name: Eng	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: greaterequal	Contours detected: 3	Expected: 2

	- Glyph name: lessequal	Contours detected: 3	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* dieresis (U+00A8): X=291.0,Y=701.0 (should be at cap-height 700?)

	* dieresis (U+00A8): X=395.0,Y=701.0 (should be at cap-height 700?)

	* dieresis (U+00A8): X=132.0,Y=701.0 (should be at cap-height 700?)

	* dieresis (U+00A8): X=236.0,Y=701.0 (should be at cap-height 700?)

	* adieresis (U+00E4): X=349.0,Y=701.0 (should be at cap-height 700?)

	* adieresis (U+00E4): X=453.0,Y=701.0 (should be at cap-height 700?)

	* adieresis (U+00E4): X=190.0,Y=701.0 (should be at cap-height 700?)

	* adieresis (U+00E4): X=294.0,Y=701.0 (should be at cap-height 700?)

	* edieresis (U+00EB): X=367.0,Y=701.0 (should be at cap-height 700?)

	* edieresis (U+00EB): X=471.0,Y=701.0 (should be at cap-height 700?)

	* edieresis (U+00EB): X=208.0,Y=701.0 (should be at cap-height 700?)

	* edieresis (U+00EB): X=312.0,Y=701.0 (should be at cap-height 700?)

	* idieresis (U+00EF): X=196.0,Y=701.0 (should be at cap-height 700?)

	* idieresis (U+00EF): X=300.0,Y=701.0 (should be at cap-height 700?)

	* idieresis (U+00EF): X=37.0,Y=701.0 (should be at cap-height 700?)

	* idieresis (U+00EF): X=141.0,Y=701.0 (should be at cap-height 700?)

	* eth (U+00F0): X=331.0,Y=701.0 (should be at cap-height 700?)

	* eth (U+00F0): X=417.0,Y=699.0 (should be at cap-height 700?)

	* odieresis (U+00F6): X=378.0,Y=701.0 (should be at cap-height 700?)

	* odieresis (U+00F6): X=482.0,Y=701.0 (should be at cap-height 700?)

	* odieresis (U+00F6): X=219.0,Y=701.0 (should be at cap-height 700?)

	* odieresis (U+00F6): X=323.0,Y=701.0 (should be at cap-height 700?)

	* udieresis (U+00FC): X=349.0,Y=701.0 (should be at cap-height 700?)

	* udieresis (U+00FC): X=453.0,Y=701.0 (should be at cap-height 700?)

	* udieresis (U+00FC): X=190.0,Y=701.0 (should be at cap-height 700?)

	* udieresis (U+00FC): X=294.0,Y=701.0 (should be at cap-height 700?)

	* ydieresis (U+00FF): X=379.0,Y=701.0 (should be at cap-height 700?)

	* ydieresis (U+00FF): X=483.0,Y=701.0 (should be at cap-height 700?)

	* ydieresis (U+00FF): X=220.0,Y=701.0 (should be at cap-height 700?)

	* ydieresis (U+00FF): X=324.0,Y=701.0 (should be at cap-height 700?)

	* cdotaccent (U+010B): X=290.0,Y=702.0 (should be at cap-height 700?)

	* cdotaccent (U+010B): X=400.0,Y=702.0 (should be at cap-height 700?)

	* edotaccent (U+0117): X=285.0,Y=701.0 (should be at cap-height 700?)

	* edotaccent (U+0117): X=395.0,Y=701.0 (should be at cap-height 700?)

	* gdotaccent (U+0121): X=262.0,Y=701.0 (should be at cap-height 700?)

	* gdotaccent (U+0121): X=372.0,Y=701.0 (should be at cap-height 700?)

	* Iogonek (U+012E): X=127.0,Y=1.0 (should be at baseline 0?)

	* iogonek (U+012F): X=113.0,Y=701.0 (should be at cap-height 700?)

	* iogonek (U+012F): X=223.0,Y=701.0 (should be at cap-height 700?)

	* ohungarumlaut (U+0151): X=446.0,Y=701.0 (should be at cap-height 700?)

	* ohungarumlaut (U+0151): X=538.0,Y=701.0 (should be at cap-height 700?)

	* ohungarumlaut (U+0151): X=305.0,Y=701.0 (should be at cap-height 700?)

	* ohungarumlaut (U+0151): X=397.0,Y=701.0 (should be at cap-height 700?)

	* uhungarumlaut (U+0171): X=417.0,Y=701.0 (should be at cap-height 700?)

	* uhungarumlaut (U+0171): X=509.0,Y=701.0 (should be at cap-height 700?)

	* uhungarumlaut (U+0171): X=276.0,Y=701.0 (should be at cap-height 700?)

	* uhungarumlaut (U+0171): X=368.0,Y=701.0 (should be at cap-height 700?)

	* zdotaccent (U+017C): X=239.0,Y=701.0 (should be at cap-height 700?)

	* zdotaccent (U+017C): X=349.0,Y=701.0 (should be at cap-height 700?)

	* dotaccent (U+02D9): X=209.0,Y=701.0 (should be at cap-height 700?)

	* dotaccent (U+02D9): X=319.0,Y=701.0 (should be at cap-height 700?)

	* hungarumlaut (U+02DD): X=322.0,Y=701.0 (should be at cap-height 700?)

	* hungarumlaut (U+02DD): X=414.0,Y=701.0 (should be at cap-height 700?)

	* hungarumlaut (U+02DD): X=181.0,Y=701.0 (should be at cap-height 700?)

	* hungarumlaut (U+02DD): X=273.0,Y=701.0 (should be at cap-height 700?)

	* uni0307 (U+0307): X=67.0,Y=701.0 (should be at cap-height 700?)

	* uni0307 (U+0307): X=177.0,Y=701.0 (should be at cap-height 700?)

	* uni0308 (U+0308): X=200.0,Y=701.0 (should be at cap-height 700?)

	* uni0308 (U+0308): X=304.0,Y=701.0 (should be at cap-height 700?)

	* uni0308 (U+0308): X=41.0,Y=701.0 (should be at cap-height 700?)

	* uni0308 (U+0308): X=145.0,Y=701.0 (should be at cap-height 700?)

	* uni030B (U+030B): X=253.0,Y=701.0 (should be at cap-height 700?)

	* uni030B (U+030B): X=345.0,Y=701.0 (should be at cap-height 700?)

	* uni030B (U+030B): X=112.0,Y=701.0 (should be at cap-height 700?)

	* uni030B (U+030B): X=204.0,Y=701.0 (should be at cap-height 700?)

	* wdieresis (U+1E85): X=490.0,Y=701.0 (should be at cap-height 700?)

	* wdieresis (U+1E85): X=594.0,Y=701.0 (should be at cap-height 700?)

	* wdieresis (U+1E85): X=331.0,Y=701.0 (should be at cap-height 700?) 

	* wdieresis (U+1E85): X=435.0,Y=701.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* ampersand (U+0026) contains a short segment L<<326.0,366.0>--<323.0,366.0>>

	* m (U+006D) contains a short segment L<<498.0,256.0>--<498.0,256.0>>

	* m (U+006D) contains a short segment L<<155.0,256.0>--<155.0,256.0>>

	* paragraph (U+00B6) contains a short segment L<<320.0,294.0>--<309.0,294.0>>

	* cedilla (U+00B8) contains a short segment B<<67.0,-107.0>-<67.0,-104.0>-<68.0,-101.0>>

	* Ccedilla (U+00C7) contains a short segment B<<259.0,-108.0>-<259.0,-105.0>-<260.0,-102.0>>

	* ae (U+00E6) contains a short segment L<<397.0,297.0>--<398.0,306.0>>

	* ae (U+00E6) contains a short segment B<<870.0,274.0>-<869.0,265.0>-<867.0,254.0>>

	* ccedilla (U+00E7) contains a short segment B<<166.0,-109.0>-<166.0,-106.0>-<167.0,-103.0>>

	* eng (U+014B) contains a short segment L<<391.0,0.0>--<390.0,0.0>>

	* Scedilla (U+015E) contains a short segment B<<191.0,-107.0>-<191.0,-104.0>-<192.0,-101.0>>

	* scedilla (U+015F) contains a short segment B<<134.0,-108.0>-<134.0,-105.0>-<135.0,-102.0>>

	* uni0162 (U+0162) contains a short segment B<<182.0,-108.0>-<182.0,-105.0>-<183.0,-102.0>>

	* uni0163 (U+0163) contains a short segment B<<108.0,-108.0>-<108.0,-105.0>-<109.0,-102.0>>

	* aeacute (U+01FD) contains a short segment L<<397.0,297.0>--<398.0,306.0>>

	* aeacute (U+01FD) contains a short segment B<<870.0,274.0>-<869.0,265.0>-<867.0,254.0>>

	* uni0327 (U+0327) contains a short segment B<<-27.0,-107.0>-<-27.0,-104.0>-<-26.0,-101.0>>

	* uni20B9 (U+20B9) contains a short segment L<<117.0,630.0>--<118.0,632.0>> 

	* uni20B9 (U+20B9) contains a short segment L<<118.0,632.0>--<118.0,632.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* eng (U+014B): B<<215.5,385.0>-<167.0,339.0>-<155.0,256.0>>/L<<155.0,256.0>--<155.0,258.0>> = 8.226722464108152

	* eng (U+014B): L<<155.0,256.0>--<155.0,258.0>>/L<<155.0,258.0>--<119.0,0.0>> = 7.943471810590413

	* greaterequal (U+2265): L<<223.0,337.0>--<93.0,329.0>>/L<<93.0,329.0>--<285.0,377.0>> = 10.514790091004233

	* greaterequal (U+2265): L<<320.0,359.0>--<502.0,400.0>>/L<<502.0,400.0>--<364.0,337.0>> = 11.842363738004835

	* lessequal (U+2264): L<<341.0,377.0>--<519.0,329.0>>/L<<519.0,329.0>--<392.0,337.0>> = 11.487152139419168

	* n (U+006E): B<<215.5,385.0>-<167.0,339.0>-<155.0,256.0>>/L<<155.0,256.0>--<155.0,258.0>> = 8.226722464108152

	* n (U+006E): L<<155.0,256.0>--<155.0,258.0>>/L<<155.0,258.0>--<119.0,0.0>> = 7.943471810590413

	* nacute (U+0144): B<<215.5,385.0>-<167.0,339.0>-<155.0,256.0>>/L<<155.0,256.0>--<155.0,258.0>> = 8.226722464108152

	* nacute (U+0144): L<<155.0,256.0>--<155.0,258.0>>/L<<155.0,258.0>--<119.0,0.0>> = 7.943471810590413

	* ncaron (U+0148): B<<215.5,385.0>-<167.0,339.0>-<155.0,256.0>>/L<<155.0,256.0>--<155.0,258.0>> = 8.226722464108152

	* ncaron (U+0148): L<<155.0,256.0>--<155.0,258.0>>/L<<155.0,258.0>--<119.0,0.0>> = 7.943471810590413

	* ntilde (U+00F1): B<<215.5,385.0>-<167.0,339.0>-<155.0,256.0>>/L<<155.0,256.0>--<155.0,258.0>> = 8.226722464108152

	* ntilde (U+00F1): L<<155.0,256.0>--<155.0,258.0>>/L<<155.0,258.0>--<119.0,0.0>> = 7.943471810590413

	* partialdiff (U+2202): B<<431.0,534.0>-<465.0,511.0>-<472.0,449.0>>/B<<472.0,449.0>-<480.0,517.0>-<472.0,570.5>> = 13.151436907091933

	* r (U+0072): B<<202.0,374.0>-<166.0,332.0>-<153.0,235.0>>/L<<153.0,235.0>--<153.0,236.0>> = 7.633330587231263

	* r (U+0072): L<<153.0,235.0>--<153.0,236.0>>/L<<153.0,236.0>--<119.0,0.0>> = 8.198068846016264

	* racute (U+0155): B<<202.0,374.0>-<166.0,332.0>-<153.0,235.0>>/L<<153.0,235.0>--<153.0,236.0>> = 7.633330587231263

	* racute (U+0155): L<<153.0,235.0>--<153.0,236.0>>/L<<153.0,236.0>--<119.0,0.0>> = 8.198068846016264

	* rcaron (U+0159): B<<202.0,374.0>-<166.0,332.0>-<153.0,235.0>>/L<<153.0,235.0>--<153.0,236.0>> = 7.633330587231263

	* rcaron (U+0159): L<<153.0,235.0>--<153.0,236.0>>/L<<153.0,236.0>--<119.0,0.0>> = 8.198068846016264

	* uni0146 (U+0146): B<<215.5,385.0>-<167.0,339.0>-<155.0,256.0>>/L<<155.0,256.0>--<155.0,258.0>> = 8.226722464108152

	* uni0146 (U+0146): L<<155.0,256.0>--<155.0,258.0>>/L<<155.0,258.0>--<119.0,0.0>> = 7.943471810590413

	* uni0157 (U+0157): B<<202.0,374.0>-<166.0,332.0>-<153.0,235.0>>/L<<153.0,235.0>--<153.0,236.0>> = 7.633330587231263 

	* uni0157 (U+0157): L<<153.0,235.0>--<153.0,236.0>>/L<<153.0,236.0>--<119.0,0.0>> = 8.198068846016264 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[15] HostGrotesk-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 372, but got 277 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.12.5 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ [code: soft-dotted]
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


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni030C.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Eng	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Eng	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* at (U+0040): X=687.0,Y=-2.0 (should be at baseline 0?)

	* S (U+0053): X=213.0,Y=1.5 (should be at baseline 0?)

	* bracketleft (U+005B): X=339.0,Y=698.0 (should be at cap-height 700?)

	* bracketleft (U+005B): X=188.0,Y=698.0 (should be at cap-height 700?)

	* bracketright (U+005D): X=197.0,Y=698.0 (should be at cap-height 700?)

	* bracketright (U+005D): X=46.0,Y=698.0 (should be at cap-height 700?)

	* g (U+0067): X=278.0,Y=-1.0 (should be at baseline 0?)

	* braceleft (U+007B): X=352.0,Y=699.0 (should be at cap-height 700?)

	* braceleft (U+007B): X=313.0,Y=699.0 (should be at cap-height 700?)

	* braceright (U+007D): X=72.0,Y=699.0 (should be at cap-height 700?)

	* braceright (U+007D): X=33.0,Y=699.0 (should be at cap-height 700?)

	* ordfeminine (U+00AA): X=268.5,Y=699.0 (should be at cap-height 700?)

	* Oslash (U+00D8): X=281.5,Y=0.5 (should be at baseline 0?)

	* gbreve (U+011F): X=278.0,Y=-1.0 (should be at baseline 0?)

	* gdotaccent (U+0121): X=278.0,Y=-1.0 (should be at baseline 0?)

	* uni0123 (U+0123): X=278.0,Y=-1.0 (should be at baseline 0?)

	* Sacute (U+015A): X=213.0,Y=1.5 (should be at baseline 0?)

	* Scedilla (U+015E): X=213.0,Y=1.5 (should be at baseline 0?)

	* Scaron (U+0160): X=213.0,Y=1.5 (should be at baseline 0?)

	* Uogonek (U+0172): X=394.0,Y=1.0 (should be at baseline 0?)

	* uni0218 (U+0218): X=213.0,Y=1.5 (should be at baseline 0?)

	* uni0326 (U+0326): X=-7.0,Y=-1.0 (should be at baseline 0?)

	* quotedblright (U+201D): X=274.0,Y=701.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=420.0,Y=701.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=72.0,Y=701.0 (should be at cap-height 700?) 

	* quotedblright (U+201D): X=218.0,Y=701.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* at (U+0040) contains a short segment B<<667.0,129.5>-<675.0,115.0>-<690.0,115.0>>

	* R (U+0052) contains a short segment L<<345.0,265.0>--<345.0,265.0>>

	* R (U+0052) contains a short segment L<<345.0,265.0>--<344.0,265.0>>

	* sterling (U+00A3) contains a short segment B<<303.0,295.0>-<304.0,285.0>-<304.0,276.0>>

	* yen (U+00A5) contains a short segment L<<255.0,241.0>--<255.0,244.0>>

	* yen (U+00A5) contains a short segment L<<395.0,244.0>--<395.0,241.0>>

	* paragraph (U+00B6) contains a short segment L<<303.0,280.0>--<284.0,280.0>>

	* germandbls (U+00DF) contains a short segment L<<233.0,425.0>--<249.0,425.0>>

	* ae (U+00E6) contains a short segment L<<363.0,296.0>--<363.0,305.0>>

	* eng (U+014B) contains a short segment L<<394.0,0.0>--<393.0,0.0>>

	* Racute (U+0154) contains a short segment L<<345.0,265.0>--<345.0,265.0>>

	* Racute (U+0154) contains a short segment L<<345.0,265.0>--<344.0,265.0>>

	* uni0156 (U+0156) contains a short segment L<<345.0,265.0>--<345.0,265.0>>

	* uni0156 (U+0156) contains a short segment L<<345.0,265.0>--<344.0,265.0>>

	* Rcaron (U+0158) contains a short segment L<<345.0,265.0>--<345.0,265.0>>

	* Rcaron (U+0158) contains a short segment L<<345.0,265.0>--<344.0,265.0>> 

	* aeacute (U+01FD) contains a short segment L<<363.0,296.0>--<363.0,305.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* R (U+0052): L<<345.0,265.0>--<344.0,265.0>> -> L<<344.0,265.0>--<187.0,265.0>>

	* Racute (U+0154): L<<345.0,265.0>--<344.0,265.0>> -> L<<344.0,265.0>--<187.0,265.0>>

	* Rcaron (U+0158): L<<345.0,265.0>--<344.0,265.0>> -> L<<344.0,265.0>--<187.0,265.0>> 

	* uni0156 (U+0156): L<<345.0,265.0>--<344.0,265.0>> -> L<<344.0,265.0>--<187.0,265.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* eng (U+014B): L<<294.0,-220.0>--<295.0,-101.0>>

	* summation (U+2211): L<<26.0,-50.0>--<27.0,113.0>>

	* summation (U+2211): L<<27.0,538.0>--<28.0,700.0>>

	* trademark (U+2122): L<<197.0,617.0>--<198.0,349.0>> 

	* trademark (U+2122): L<<94.0,349.0>--<95.0,617.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[16] HostGrotesk-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 372, but got 277 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.12.5 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ [code: soft-dotted]
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


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni030C.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Eng	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: lessequal	Contours detected: 3	Expected: 2

	- Glyph name: greaterequal	Contours detected: 3	Expected: 2

	- Glyph name: Eng	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: greaterequal	Contours detected: 3	Expected: 2

	- Glyph name: lessequal	Contours detected: 3	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* i (U+0069): X=52.0,Y=701.0 (should be at cap-height 700?)

	* i (U+0069): X=161.0,Y=701.0 (should be at cap-height 700?)

	* j (U+006A): X=47.0,Y=701.0 (should be at cap-height 700?)

	* j (U+006A): X=156.0,Y=701.0 (should be at cap-height 700?)

	* dieresis (U+00A8): X=228.0,Y=701.0 (should be at cap-height 700?)

	* dieresis (U+00A8): X=332.0,Y=701.0 (should be at cap-height 700?)

	* dieresis (U+00A8): X=69.0,Y=701.0 (should be at cap-height 700?)

	* dieresis (U+00A8): X=173.0,Y=701.0 (should be at cap-height 700?)

	* adieresis (U+00E4): X=286.0,Y=701.0 (should be at cap-height 700?)

	* adieresis (U+00E4): X=390.0,Y=701.0 (should be at cap-height 700?)

	* adieresis (U+00E4): X=127.0,Y=701.0 (should be at cap-height 700?)

	* adieresis (U+00E4): X=231.0,Y=701.0 (should be at cap-height 700?)

	* edieresis (U+00EB): X=309.0,Y=701.0 (should be at cap-height 700?)

	* edieresis (U+00EB): X=413.0,Y=701.0 (should be at cap-height 700?)

	* edieresis (U+00EB): X=150.0,Y=701.0 (should be at cap-height 700?)

	* edieresis (U+00EB): X=254.0,Y=701.0 (should be at cap-height 700?)

	* idieresis (U+00EF): X=133.0,Y=701.0 (should be at cap-height 700?)

	* idieresis (U+00EF): X=237.0,Y=701.0 (should be at cap-height 700?)

	* idieresis (U+00EF): X=-26.0,Y=701.0 (should be at cap-height 700?)

	* idieresis (U+00EF): X=78.0,Y=701.0 (should be at cap-height 700?)

	* odieresis (U+00F6): X=315.0,Y=701.0 (should be at cap-height 700?)

	* odieresis (U+00F6): X=419.0,Y=701.0 (should be at cap-height 700?)

	* odieresis (U+00F6): X=156.0,Y=701.0 (should be at cap-height 700?)

	* odieresis (U+00F6): X=260.0,Y=701.0 (should be at cap-height 700?)

	* udieresis (U+00FC): X=302.0,Y=701.0 (should be at cap-height 700?)

	* udieresis (U+00FC): X=406.0,Y=701.0 (should be at cap-height 700?)

	* udieresis (U+00FC): X=143.0,Y=701.0 (should be at cap-height 700?)

	* udieresis (U+00FC): X=247.0,Y=701.0 (should be at cap-height 700?)

	* ydieresis (U+00FF): X=332.0,Y=701.0 (should be at cap-height 700?)

	* ydieresis (U+00FF): X=436.0,Y=701.0 (should be at cap-height 700?)

	* ydieresis (U+00FF): X=173.0,Y=701.0 (should be at cap-height 700?)

	* ydieresis (U+00FF): X=277.0,Y=701.0 (should be at cap-height 700?)

	* cdotaccent (U+010B): X=227.0,Y=702.0 (should be at cap-height 700?)

	* cdotaccent (U+010B): X=335.0,Y=702.0 (should be at cap-height 700?)

	* edotaccent (U+0117): X=227.0,Y=701.0 (should be at cap-height 700?)

	* edotaccent (U+0117): X=335.0,Y=701.0 (should be at cap-height 700?)

	* gdotaccent (U+0121): X=237.0,Y=701.0 (should be at cap-height 700?)

	* gdotaccent (U+0121): X=345.0,Y=701.0 (should be at cap-height 700?)

	* iogonek (U+012F): X=51.0,Y=701.0 (should be at cap-height 700?)

	* iogonek (U+012F): X=159.0,Y=701.0 (should be at cap-height 700?)

	* ij (U+0133): X=57.0,Y=701.0 (should be at cap-height 700?)

	* ij (U+0133): X=166.0,Y=701.0 (should be at cap-height 700?)

	* ij (U+0133): X=284.0,Y=701.0 (should be at cap-height 700?)

	* ij (U+0133): X=394.0,Y=701.0 (should be at cap-height 700?)

	* ohungarumlaut (U+0151): X=382.0,Y=701.0 (should be at cap-height 700?)

	* ohungarumlaut (U+0151): X=473.0,Y=701.0 (should be at cap-height 700?)

	* ohungarumlaut (U+0151): X=241.0,Y=701.0 (should be at cap-height 700?)

	* ohungarumlaut (U+0151): X=333.0,Y=701.0 (should be at cap-height 700?)

	* uhungarumlaut (U+0171): X=369.0,Y=701.0 (should be at cap-height 700?)

	* uhungarumlaut (U+0171): X=460.0,Y=701.0 (should be at cap-height 700?)

	* uhungarumlaut (U+0171): X=228.0,Y=701.0 (should be at cap-height 700?)

	* uhungarumlaut (U+0171): X=320.0,Y=701.0 (should be at cap-height 700?)

	* zdotaccent (U+017C): X=159.0,Y=701.0 (should be at cap-height 700?)

	* zdotaccent (U+017C): X=267.0,Y=701.0 (should be at cap-height 700?)

	* dotaccent (U+02D9): X=146.0,Y=701.0 (should be at cap-height 700?)

	* dotaccent (U+02D9): X=254.0,Y=701.0 (should be at cap-height 700?)

	* hungarumlaut (U+02DD): X=258.0,Y=701.0 (should be at cap-height 700?)

	* hungarumlaut (U+02DD): X=349.0,Y=701.0 (should be at cap-height 700?)

	* hungarumlaut (U+02DD): X=117.0,Y=701.0 (should be at cap-height 700?)

	* hungarumlaut (U+02DD): X=209.0,Y=701.0 (should be at cap-height 700?)

	* uni0307 (U+0307): X=-54.0,Y=701.0 (should be at cap-height 700?)

	* uni0307 (U+0307): X=54.0,Y=701.0 (should be at cap-height 700?)

	* uni0308 (U+0308): X=28.0,Y=701.0 (should be at cap-height 700?)

	* uni0308 (U+0308): X=132.0,Y=701.0 (should be at cap-height 700?)

	* uni0308 (U+0308): X=-131.0,Y=701.0 (should be at cap-height 700?)

	* uni0308 (U+0308): X=-27.0,Y=701.0 (should be at cap-height 700?)

	* uni030B (U+030B): X=94.0,Y=701.0 (should be at cap-height 700?)

	* uni030B (U+030B): X=185.0,Y=701.0 (should be at cap-height 700?)

	* uni030B (U+030B): X=-47.0,Y=701.0 (should be at cap-height 700?)

	* uni030B (U+030B): X=45.0,Y=701.0 (should be at cap-height 700?)

	* wdieresis (U+1E85): X=430.0,Y=701.0 (should be at cap-height 700?)

	* wdieresis (U+1E85): X=534.0,Y=701.0 (should be at cap-height 700?)

	* wdieresis (U+1E85): X=271.0,Y=701.0 (should be at cap-height 700?) 

	* wdieresis (U+1E85): X=375.0,Y=701.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* ampersand (U+0026) contains a short segment L<<297.0,366.0>--<294.0,366.0>>

	* R (U+0052) contains a short segment L<<342.0,285.0>--<342.0,285.0>>

	* R (U+0052) contains a short segment L<<342.0,285.0>--<342.0,285.0>>

	* paragraph (U+00B6) contains a short segment L<<316.0,294.0>--<305.0,294.0>>

	* cedilla (U+00B8) contains a short segment B<<116.0,-107.0>-<116.0,-104.0>-<118.0,-101.0>>

	* Ccedilla (U+00C7) contains a short segment B<<292.0,-108.0>-<292.0,-105.0>-<294.0,-102.0>>

	* ae (U+00E6) contains a short segment L<<380.0,297.0>--<380.0,305.0>>

	* ae (U+00E6) contains a short segment B<<856.0,276.0>-<856.0,266.0>-<856.0,255.0>>

	* ccedilla (U+00E7) contains a short segment B<<202.0,-109.0>-<202.0,-106.0>-<204.0,-103.0>>

	* eng (U+014B) contains a short segment L<<420.0,0.0>--<420.0,0.0>>

	* Racute (U+0154) contains a short segment L<<342.0,285.0>--<342.0,285.0>>

	* Racute (U+0154) contains a short segment L<<342.0,285.0>--<342.0,285.0>>

	* uni0156 (U+0156) contains a short segment L<<342.0,285.0>--<342.0,285.0>>

	* uni0156 (U+0156) contains a short segment L<<342.0,285.0>--<342.0,285.0>>

	* Rcaron (U+0158) contains a short segment L<<342.0,285.0>--<342.0,285.0>>

	* Rcaron (U+0158) contains a short segment L<<342.0,285.0>--<342.0,285.0>>

	* Scedilla (U+015E) contains a short segment B<<242.0,-108.0>-<242.0,-105.0>-<244.0,-102.0>>

	* scedilla (U+015F) contains a short segment B<<174.0,-108.0>-<174.0,-105.0>-<176.0,-102.0>>

	* uni0162 (U+0162) contains a short segment B<<215.0,-108.0>-<215.0,-105.0>-<217.0,-102.0>>

	* uni0163 (U+0163) contains a short segment B<<134.0,-108.0>-<134.0,-105.0>-<136.0,-102.0>>

	* uni018F (U+018F) contains a short segment L<<134.0,301.0>--<134.0,300.0>>

	* aeacute (U+01FD) contains a short segment L<<380.0,297.0>--<380.0,305.0>>

	* aeacute (U+01FD) contains a short segment B<<856.0,276.0>-<856.0,266.0>-<856.0,255.0>> 

	* uni0327 (U+0327) contains a short segment B<<-84.0,-107.0>-<-84.0,-104.0>-<-82.0,-101.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* R (U+0052): L<<342.0,285.0>--<342.0,285.0>> -> L<<342.0,285.0>--<342.0,285.0>>

	* Racute (U+0154): L<<342.0,285.0>--<342.0,285.0>> -> L<<342.0,285.0>--<342.0,285.0>>

	* Rcaron (U+0158): L<<342.0,285.0>--<342.0,285.0>> -> L<<342.0,285.0>--<342.0,285.0>> 

	* uni0156 (U+0156): L<<342.0,285.0>--<342.0,285.0>> -> L<<342.0,285.0>--<342.0,285.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* greaterequal (U+2265): L<<208.0,337.0>--<79.0,329.0>>/L<<79.0,329.0>--<264.0,377.0>> = 10.996520767269896

	* greaterequal (U+2265): L<<302.0,359.0>--<478.0,400.0>>/L<<478.0,400.0>--<349.0,337.0>> = 12.916153961656756

	* lessequal (U+2264): L<<241.0,337.0>--<112.0,400.0>>/L<<112.0,400.0>--<288.0,359.0>> = 12.916153961656756

	* lessequal (U+2264): L<<326.0,377.0>--<511.0,329.0>>/L<<511.0,329.0>--<382.0,337.0>> = 10.996520767269896 

	* partialdiff (U+2202): B<<394.0,534.0>-<431.0,511.0>-<447.0,449.0>>/B<<447.0,449.0>-<445.0,517.0>-<429.5,570.5>> = 12.785609782169606 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* asterisk (U+002A): L<<171.0,515.0>--<46.0,514.0>>

	* asterisk (U+002A): L<<291.0,580.0>--<416.0,581.0>>

	* asterisk (U+002A): L<<416.0,514.0>--<291.0,515.0>>

	* asterisk (U+002A): L<<46.0,581.0>--<171.0,580.0>>

	* trademark (U+2122): L<<128.0,348.0>--<129.0,643.0>>

	* trademark (U+2122): L<<198.0,643.0>--<199.0,348.0>> 

	* trademark (U+2122): L<<691.0,348.0>--<690.0,604.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[15] HostGrotesk-MediumItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 372, but got 277 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.12.5 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
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


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
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

	- uni01CE.ss02 

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

	- Glyph name: Eng	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* eth (U+00F0): X=326.0,Y=701.0 (should be at cap-height 700?)

	* eth (U+00F0): X=429.0,Y=699.0 (should be at cap-height 700?)

	* abreve (U+0103): X=174.0,Y=698.0 (should be at cap-height 700?)

	* abreve (U+0103): X=473.0,Y=698.0 (should be at cap-height 700?)

	* ebreve (U+0115): X=193.0,Y=698.0 (should be at cap-height 700?)

	* ebreve (U+0115): X=492.0,Y=698.0 (should be at cap-height 700?)

	* gbreve (U+011F): X=170.0,Y=698.0 (should be at cap-height 700?)

	* gbreve (U+011F): X=469.0,Y=698.0 (should be at cap-height 700?)

	* ibreve (U+012D): X=21.0,Y=698.0 (should be at cap-height 700?)

	* ibreve (U+012D): X=320.0,Y=698.0 (should be at cap-height 700?)

	* obreve (U+014F): X=202.0,Y=698.0 (should be at cap-height 700?)

	* obreve (U+014F): X=501.0,Y=698.0 (should be at cap-height 700?)

	* tcaron (U+0165): X=396.0,Y=698.0 (should be at cap-height 700?)

	* tcaron (U+0165): X=343.0,Y=698.0 (should be at cap-height 700?)

	* ubreve (U+016D): X=178.0,Y=698.0 (should be at cap-height 700?)

	* ubreve (U+016D): X=477.0,Y=698.0 (should be at cap-height 700?)

	* Uogonek (U+0172): X=356.0,Y=1.0 (should be at baseline 0?)

	* breve (U+02D8): X=114.0,Y=698.0 (should be at cap-height 700?)

	* breve (U+02D8): X=413.0,Y=698.0 (should be at cap-height 700?)

	* uni0306 (U+0306): X=-15.0,Y=698.0 (should be at cap-height 700?)

	* uni0306 (U+0306): X=284.0,Y=698.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=344.0,Y=701.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=463.0,Y=701.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=166.0,Y=701.0 (should be at cap-height 700?) 

	* quotedblright (U+201D): X=286.0,Y=701.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* yen (U+00A5) contains a short segment L<<269.0,234.0>--<272.0,256.0>>

	* yen (U+00A5) contains a short segment L<<382.0,256.0>--<379.0,234.0>>

	* paragraph (U+00B6) contains a short segment L<<308.0,288.0>--<296.0,288.0>>

	* ae (U+00E6) contains a short segment L<<389.0,296.0>--<390.0,307.0>>

	* ae (U+00E6) contains a short segment B<<875.0,265.0>-<874.0,257.0>-<872.0,245.5>>

	* eng (U+014B) contains a short segment L<<528.0,282.0>--<528.0,282.0>>

	* eng (U+014B) contains a short segment L<<379.0,0.0>--<379.0,0.0>>

	* aeacute (U+01FD) contains a short segment L<<389.0,296.0>--<390.0,307.0>>

	* aeacute (U+01FD) contains a short segment B<<875.0,265.0>-<874.0,257.0>-<872.0,245.5>>

	* uni20B9 (U+20B9) contains a short segment L<<115.0,612.0>--<116.0,617.0>>

	* uni20B9 (U+20B9) contains a short segment L<<116.0,617.0>--<115.0,617.0>> 

	* integral (U+222B) contains a short segment L<<391.0,830.0>--<375.0,830.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* greaterequal (U+2265): L<<149.0,428.0>--<105.0,437.0>>/L<<105.0,437.0>--<175.0,438.0>> = 12.378586255906386

	* lessequal (U+2264): L<<468.0,438.0>--<538.0,437.0>>/L<<538.0,437.0>--<492.0,428.0>> = 11.888658039627998

	* m (U+006D): B<<561.0,372.0>-<519.0,330.0>-<509.0,254.0>>/L<<509.0,254.0>--<509.0,255.0>> = 7.495857639729836

	* m (U+006D): L<<509.0,254.0>--<509.0,255.0>>/L<<509.0,255.0>--<473.0,0.0>> = 8.03571071053479

	* u (U+0075): B<<335.0,124.0>-<380.0,166.0>-<390.0,242.0>>/L<<390.0,242.0>--<390.0,241.0>> = 7.495857639729836

	* u (U+0075): L<<390.0,242.0>--<390.0,241.0>>/L<<390.0,241.0>--<426.0,496.0>> = 8.03571071053479

	* uacute (U+00FA): B<<335.0,124.0>-<380.0,166.0>-<390.0,242.0>>/L<<390.0,242.0>--<390.0,241.0>> = 7.495857639729836

	* uacute (U+00FA): L<<390.0,242.0>--<390.0,241.0>>/L<<390.0,241.0>--<426.0,496.0>> = 8.03571071053479

	* ubreve (U+016D): B<<335.0,124.0>-<380.0,166.0>-<390.0,242.0>>/L<<390.0,242.0>--<390.0,241.0>> = 7.495857639729836

	* ubreve (U+016D): L<<390.0,242.0>--<390.0,241.0>>/L<<390.0,241.0>--<426.0,496.0>> = 8.03571071053479

	* ucircumflex (U+00FB): B<<335.0,124.0>-<380.0,166.0>-<390.0,242.0>>/L<<390.0,242.0>--<390.0,241.0>> = 7.495857639729836

	* ucircumflex (U+00FB): L<<390.0,242.0>--<390.0,241.0>>/L<<390.0,241.0>--<426.0,496.0>> = 8.03571071053479

	* udieresis (U+00FC): B<<335.0,124.0>-<380.0,166.0>-<390.0,242.0>>/L<<390.0,242.0>--<390.0,241.0>> = 7.495857639729836

	* udieresis (U+00FC): L<<390.0,242.0>--<390.0,241.0>>/L<<390.0,241.0>--<426.0,496.0>> = 8.03571071053479

	* ugrave (U+00F9): B<<335.0,124.0>-<380.0,166.0>-<390.0,242.0>>/L<<390.0,242.0>--<390.0,241.0>> = 7.495857639729836

	* ugrave (U+00F9): L<<390.0,242.0>--<390.0,241.0>>/L<<390.0,241.0>--<426.0,496.0>> = 8.03571071053479

	* uhungarumlaut (U+0171): B<<335.0,124.0>-<380.0,166.0>-<390.0,242.0>>/L<<390.0,242.0>--<390.0,241.0>> = 7.495857639729836

	* uhungarumlaut (U+0171): L<<390.0,242.0>--<390.0,241.0>>/L<<390.0,241.0>--<426.0,496.0>> = 8.03571071053479

	* umacron (U+016B): B<<335.0,124.0>-<380.0,166.0>-<390.0,242.0>>/L<<390.0,242.0>--<390.0,241.0>> = 7.495857639729836

	* umacron (U+016B): L<<390.0,242.0>--<390.0,241.0>>/L<<390.0,241.0>--<426.0,496.0>> = 8.03571071053479

	* uogonek (U+0173): B<<335.0,124.0>-<380.0,166.0>-<390.0,242.0>>/L<<390.0,242.0>--<390.0,241.0>> = 7.495857639729836

	* uogonek (U+0173): L<<390.0,242.0>--<390.0,241.0>>/L<<390.0,241.0>--<426.0,496.0>> = 8.03571071053479

	* uring (U+016F): B<<335.0,124.0>-<380.0,166.0>-<390.0,242.0>>/L<<390.0,242.0>--<390.0,241.0>> = 7.495857639729836

	* uring (U+016F): L<<390.0,242.0>--<390.0,241.0>>/L<<390.0,241.0>--<426.0,496.0>> = 8.03571071053479

	* utilde (U+0169): B<<335.0,124.0>-<380.0,166.0>-<390.0,242.0>>/L<<390.0,242.0>--<390.0,241.0>> = 7.495857639729836 

	* utilde (U+0169): L<<390.0,242.0>--<390.0,241.0>>/L<<390.0,241.0>--<426.0,496.0>> = 8.03571071053479 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[16] HostGrotesk-BlackItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 372, but got 277 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.12.5 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
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


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
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

	- uni01CE.ss02 

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

	- Glyph name: Eng	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* at (U+0040): X=646.0,Y=-2.0 (should be at baseline 0?)

	* bracketleft (U+005B): X=392.0,Y=698.0 (should be at cap-height 700?)

	* bracketleft (U+005B): X=241.0,Y=698.0 (should be at cap-height 700?)

	* bracketright (U+005D): X=74.0,Y=698.0 (should be at cap-height 700?)

	* bracketright (U+005D): X=-77.0,Y=698.0 (should be at cap-height 700?)

	* g (U+0067): X=250.0,Y=-1.0 (should be at baseline 0?)

	* braceleft (U+007B): X=406.0,Y=699.0 (should be at cap-height 700?)

	* braceleft (U+007B): X=367.0,Y=699.0 (should be at cap-height 700?)

	* braceright (U+007D): X=-52.0,Y=699.0 (should be at cap-height 700?)

	* braceright (U+007D): X=-91.0,Y=699.0 (should be at cap-height 700?)

	* ordfeminine (U+00AA): X=332.0,Y=698.5 (should be at cap-height 700?)

	* uni00B5 (U+00B5): X=152.0,Y=2.0 (should be at baseline 0?)

	* eth (U+00F0): X=320.0,Y=702.0 (should be at cap-height 700?)

	* eth (U+00F0): X=446.0,Y=698.0 (should be at cap-height 700?)

	* gbreve (U+011F): X=250.0,Y=-1.0 (should be at baseline 0?)

	* gdotaccent (U+0121): X=250.0,Y=-1.0 (should be at baseline 0?)

	* uni0123 (U+0123): X=250.0,Y=-1.0 (should be at baseline 0?)

	* Uogonek (U+0172): X=360.0,Y=1.0 (should be at baseline 0?)

	* uni0326 (U+0326): X=-44.0,Y=-1.0 (should be at baseline 0?)

	* quotedblright (U+201D): X=343.0,Y=701.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=491.0,Y=701.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=141.0,Y=701.0 (should be at cap-height 700?) 

	* quotedblright (U+201D): X=289.0,Y=701.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* at (U+0040) contains a short segment B<<651.0,131.5>-<660.0,115.0>-<677.0,115.0>>

	* sterling (U+00A3) contains a short segment B<<310.0,295.0>-<310.0,285.0>-<309.0,276.0>>

	* yen (U+00A5) contains a short segment L<<255.0,241.0>--<255.0,244.0>>

	* yen (U+00A5) contains a short segment L<<395.0,244.0>--<395.0,241.0>>

	* paragraph (U+00B6) contains a short segment L<<291.0,280.0>--<275.0,280.0>>

	* germandbls (U+00DF) contains a short segment L<<267.0,425.0>--<283.0,425.0>>

	* ae (U+00E6) contains a short segment L<<376.0,296.0>--<377.0,308.0>>

	* aeacute (U+01FD) contains a short segment L<<376.0,296.0>--<377.0,308.0>>

	* uni20B9 (U+20B9) contains a short segment L<<111.0,586.0>--<112.0,594.0>>

	* uni20B9 (U+20B9) contains a short segment L<<112.0,594.0>--<112.0,594.0>>

	* integral (U+222B) contains a short segment L<<-90.0,-121.0>--<-74.0,-121.0>> 

	* integral (U+222B) contains a short segment L<<393.0,814.0>--<379.0,814.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* eng (U+014B): L<<355.0,-51.0>--<389.0,184.0>> -> L<<389.0,184.0>--<401.0,268.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* eng (U+014B): B<<228.5,352.5>-<189.0,315.0>-<181.0,252.0>>/L<<181.0,252.0>--<181.0,261.0>> = 7.236922025967975

	* eng (U+014B): L<<181.0,252.0>--<181.0,261.0>>/L<<181.0,261.0>--<144.0,0.0>> = 8.068626219471522

	* m (U+006D): B<<226.5,352.5>-<190.0,315.0>-<181.0,252.0>>/L<<181.0,252.0>--<181.0,253.0>> = 8.13010235415596

	* m (U+006D): L<<181.0,252.0>--<181.0,253.0>>/L<<181.0,253.0>--<145.0,0.0>> = 8.098394676422705

	* n (U+006E): B<<228.5,352.5>-<189.0,315.0>-<181.0,252.0>>/L<<181.0,252.0>--<181.0,261.0>> = 7.236922025967975

	* n (U+006E): L<<181.0,252.0>--<181.0,261.0>>/L<<181.0,261.0>--<144.0,0.0>> = 8.068626219471522

	* nacute (U+0144): B<<228.5,352.5>-<189.0,315.0>-<181.0,252.0>>/L<<181.0,252.0>--<181.0,261.0>> = 7.236922025967975

	* nacute (U+0144): L<<181.0,252.0>--<181.0,261.0>>/L<<181.0,261.0>--<144.0,0.0>> = 8.068626219471522

	* ncaron (U+0148): B<<228.5,352.5>-<189.0,315.0>-<181.0,252.0>>/L<<181.0,252.0>--<181.0,261.0>> = 7.236922025967975

	* ncaron (U+0148): L<<181.0,252.0>--<181.0,261.0>>/L<<181.0,261.0>--<144.0,0.0>> = 8.068626219471522

	* ntilde (U+00F1): B<<228.5,352.5>-<189.0,315.0>-<181.0,252.0>>/L<<181.0,252.0>--<181.0,261.0>> = 7.236922025967975

	* ntilde (U+00F1): L<<181.0,252.0>--<181.0,261.0>>/L<<181.0,261.0>--<144.0,0.0>> = 8.068626219471522

	* u (U+0075): B<<332.0,143.0>-<372.0,180.0>-<380.0,244.0>>/L<<380.0,244.0>--<380.0,241.0>> = 7.125016348901757

	* u (U+0075): L<<380.0,244.0>--<380.0,241.0>>/L<<380.0,241.0>--<416.0,496.0>> = 8.03571071053479

	* uacute (U+00FA): B<<332.0,143.0>-<372.0,180.0>-<380.0,244.0>>/L<<380.0,244.0>--<380.0,241.0>> = 7.125016348901757

	* uacute (U+00FA): L<<380.0,244.0>--<380.0,241.0>>/L<<380.0,241.0>--<416.0,496.0>> = 8.03571071053479

	* ubreve (U+016D): B<<332.0,143.0>-<372.0,180.0>-<380.0,244.0>>/L<<380.0,244.0>--<380.0,241.0>> = 7.125016348901757

	* ubreve (U+016D): L<<380.0,244.0>--<380.0,241.0>>/L<<380.0,241.0>--<416.0,496.0>> = 8.03571071053479

	* ucircumflex (U+00FB): B<<332.0,143.0>-<372.0,180.0>-<380.0,244.0>>/L<<380.0,244.0>--<380.0,241.0>> = 7.125016348901757

	* ucircumflex (U+00FB): L<<380.0,244.0>--<380.0,241.0>>/L<<380.0,241.0>--<416.0,496.0>> = 8.03571071053479

	* udieresis (U+00FC): B<<332.0,143.0>-<372.0,180.0>-<380.0,244.0>>/L<<380.0,244.0>--<380.0,241.0>> = 7.125016348901757

	* udieresis (U+00FC): L<<380.0,244.0>--<380.0,241.0>>/L<<380.0,241.0>--<416.0,496.0>> = 8.03571071053479

	* ugrave (U+00F9): B<<332.0,143.0>-<372.0,180.0>-<380.0,244.0>>/L<<380.0,244.0>--<380.0,241.0>> = 7.125016348901757

	* ugrave (U+00F9): L<<380.0,244.0>--<380.0,241.0>>/L<<380.0,241.0>--<416.0,496.0>> = 8.03571071053479

	* uhungarumlaut (U+0171): B<<332.0,143.0>-<372.0,180.0>-<380.0,244.0>>/L<<380.0,244.0>--<380.0,241.0>> = 7.125016348901757

	* uhungarumlaut (U+0171): L<<380.0,244.0>--<380.0,241.0>>/L<<380.0,241.0>--<416.0,496.0>> = 8.03571071053479

	* umacron (U+016B): B<<332.0,143.0>-<372.0,180.0>-<380.0,244.0>>/L<<380.0,244.0>--<380.0,241.0>> = 7.125016348901757

	* umacron (U+016B): L<<380.0,244.0>--<380.0,241.0>>/L<<380.0,241.0>--<416.0,496.0>> = 8.03571071053479

	* uni0146 (U+0146): B<<228.5,352.5>-<189.0,315.0>-<181.0,252.0>>/L<<181.0,252.0>--<181.0,261.0>> = 7.236922025967975

	* uni0146 (U+0146): L<<181.0,252.0>--<181.0,261.0>>/L<<181.0,261.0>--<144.0,0.0>> = 8.068626219471522

	* uogonek (U+0173): B<<332.0,143.0>-<372.0,180.0>-<380.0,244.0>>/L<<380.0,244.0>--<380.0,241.0>> = 7.125016348901757

	* uogonek (U+0173): L<<380.0,244.0>--<380.0,241.0>>/L<<380.0,241.0>--<416.0,496.0>> = 8.03571071053479

	* uring (U+016F): B<<332.0,143.0>-<372.0,180.0>-<380.0,244.0>>/L<<380.0,244.0>--<380.0,241.0>> = 7.125016348901757

	* uring (U+016F): L<<380.0,244.0>--<380.0,241.0>>/L<<380.0,241.0>--<416.0,496.0>> = 8.03571071053479

	* utilde (U+0169): B<<332.0,143.0>-<372.0,180.0>-<380.0,244.0>>/L<<380.0,244.0>--<380.0,241.0>> = 7.125016348901757 

	* utilde (U+0169): L<<380.0,244.0>--<380.0,241.0>>/L<<380.0,241.0>--<416.0,496.0>> = 8.03571071053479 [code: found-jaggy-segments]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 30 | 124 | 1172 | 61 | 920 | 0 |
| 0% | 1% | 5% | 51% | 3% | 40% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
