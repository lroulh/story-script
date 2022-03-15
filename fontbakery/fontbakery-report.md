## Fontbakery report

Fontbakery version: 0.8.7

<details><summary><b>[25] StoryScript-Regular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check METADATA.pb includes production subsets.</summary><div>
* [com.google.fonts/check/metadata/includes_production_subsets](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/includes_production_subsets)

* 💔 **ERROR** The condition <FontBakeryCondition:production_metadata> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Version number has increased since previous release on Google Fonts?</summary><div>
* [com.google.fonts/check/version_bump](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/version_bump)

* 💔 **ERROR** The condition <FontBakeryCondition:api_gfonts_ttFont> had an error: FailedConditionError: The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Glyphs are similiar to Google Fonts version?</summary><div>
* [com.google.fonts/check/production_glyphs_similarity](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity)

* 💔 **ERROR** The condition <FontBakeryCondition:api_gfonts_ttFont> had an error: FailedConditionError: The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts.</summary><div>
* [com.google.fonts/check/vertical_metrics_regressions](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions)

* 💔 **ERROR** The condition <FontBakeryCondition:regular_remote_style> had an error: FailedConditionError: The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Check font follows the Google Fonts CJK vertical metric schema</summary><div>
* [com.google.fonts/check/cjk_vertical_metrics](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/cjk_vertical_metrics)

* 💔 **ERROR** The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>💔 <b>ERROR:</b> Check if the vertical metrics of a CJK family are similar to the same family hosted on Google Fonts.</summary><div>
* [com.google.fonts/check/cjk_vertical_metrics_regressions](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/cjk_vertical_metrics_regressions)

* 💔 **ERROR** The condition <FontBakeryCondition:regular_remote_style> had an error: FailedConditionError: The condition <FontBakeryCondition:remote_styles> had an error: JSONDecodeError: Expecting value: line 1 column 1 (char 0)
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 fsType does not impose restrictions.</summary><div>
* [com.google.fonts/check/fstype](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fstype)

* 🔥 **FAIL** In this font fsType is set to 8 meaning that:
The font may be embedded but must only be installed temporarily on other systems.

No such DRM restrictions can be enabled on the Google Fonts collection, so the fsType field must be set to zero (Installable Embedding) instead. [code: drm]
</div></details><details><summary>🔥 <b>FAIL:</b> Check `Google Fonts Latin Core` glyph coverage.</summary><div>
* [com.google.fonts/check/glyph_coverage](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage)

* 🔥 **FAIL** Missing required codepoints:

	- 0x00AD (SOFT HYPHEN)
 
	- And 0x2215 (DIVISION SLASH)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string.</summary><div>
* [com.google.fonts/check/license/OFL_copyright](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright)

* 🔥 **FAIL** First line in license file does not match expected format: "copyright 2022 story script (https://github.com/lroulh/story-script)"
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file.</summary><div>
* [com.google.fonts/check/name/license](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license)

* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Version format is correct in 'name' table?</summary><div>
* [com.google.fonts/check/name/version_format](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/version_format)

* 🔥 **FAIL** The NameID.VERSION_STRING (nameID=5) value must follow the pattern "Version X.Y" with X.Y greater than or equal to 1.000. Current version string is: "Version 0.500; ttfautohint (v1.8.4.7-5d5b)" [code: bad-version-strings]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts.</summary><div>
* [com.google.fonts/check/os2/use_typo_metrics](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics)

* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/ttf/StoryScript-Regular.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent.</summary><div>
* [com.google.fonts/check/family/win_ascent_and_descent](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent)

* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1022, but got 988 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 363, but got 212 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics.</summary><div>
* [com.google.fonts/check/os2_metrics_match_hhea](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea)

* 🔥 **FAIL** OS/2 sTypoAscender (688) and hhea ascent (988) must be equal. [code: ascender]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID.</summary><div>
* [com.google.fonts/check/vendor_id](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id)

* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature?</summary><div>
* [com.google.fonts/check/ligature_carets](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets)

* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences?</summary><div>
* [com.google.fonts/check/kerning_for_non_ligated_sequences](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences)

* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:
	- f + f
	- f + i
	- i + f
	- f + l
	- l + f
	- i + l

   [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description.</summary><div>
* [com.google.fonts/check/stylisticset_description](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description)

* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table.</summary><div>
* [com.google.fonts/check/meta/script_lang_tags](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags)

* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs</summary><div>
* [com.google.fonts/check/unreachable_glyphs](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs)

* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:
	- five.lf
	- nine.lf
	- uniE000
	- four.lf
	- one.lf
	- seven.lf
	- six.lf
	- two.lf
	- zero.lf
	- three.lf 
	- And eight.lf
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours.</summary><div>
* [com.google.fonts/check/contour_count](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count)

* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Y	Contours detected: 2	Expected: 1
	- Glyph name: a	Contours detected: 1	Expected: 2
	- Glyph name: b	Contours detected: 1	Expected: 2
	- Glyph name: d	Contours detected: 1	Expected: 2
	- Glyph name: p	Contours detected: 1	Expected: 2
	- Glyph name: q	Contours detected: 1	Expected: 2
	- Glyph name: ordfeminine	Contours detected: 1	Expected: 2 or 3
	- Glyph name: Yacute	Contours detected: 3	Expected: 2
	- Glyph name: agrave	Contours detected: 2	Expected: 3
	- Glyph name: aacute	Contours detected: 2	Expected: 3 
	- And 123 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks.</summary><div>
* [com.google.fonts/check/dotted_circle](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle)

* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps.</summary><div>
* [com.google.fonts/check/linegaps](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/hhea.html#com.google.fonts/check/linegaps)

* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors?</summary><div>
* [com.google.fonts/check/outline_colinear_vectors](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors)

* ⚠ **WARN** The following glyphs have colinear vectors:
	* Eng (U+014A): L<<625.0,589.0>--<467.0,177.0>> -> L<<467.0,177.0>--<415.0,42.0>>
	* arrowboth (U+2194): L<<619.0,243.0>--<151.0,243.0>> -> L<<151.0,243.0>--<149.0,243.0>>
	* arrowleft (U+2190): L<<589.0,243.0>--<151.0,243.0>> -> L<<151.0,243.0>--<149.0,243.0>>
	* currency (U+00A4): L<<418.0,127.0>--<421.0,123.0>> -> L<<421.0,123.0>--<457.0,65.0>>
	* onequarter (U+00BC): L<<569.0,74.0>--<483.0,74.0>> -> L<<483.0,74.0>--<482.0,74.0>>
	* threequarters (U+00BE): L<<599.0,74.0>--<513.0,74.0>> -> L<<513.0,74.0>--<512.0,74.0>>
	* uni01C5 (U+01C5): L<<960.0,405.0>--<959.0,404.0>> -> L<<959.0,404.0>--<570.0,35.0>>
	* uni01C6 (U+01C6): L<<961.0,405.0>--<960.0,404.0>> -> L<<960.0,404.0>--<571.0,35.0>>
	* uni2074 (U+2074): L<<250.0,426.0>--<164.0,426.0>> -> L<<164.0,426.0>--<163.0,426.0>>
	* uni20AD (U+20AD): L<<273.0,276.0>--<274.0,274.0>> -> L<<274.0,274.0>--<413.0,-16.0>> and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments?</summary><div>
* [com.google.fonts/check/outline_jaggy_segments](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments)

* ⚠ **WARN** The following glyphs have jaggy segments:
	* nine (U+0039): B<<297.0,139.0>-<366.0,207.0>-<407.0,276.0>>/B<<407.0,276.0>-<356.0,214.0>-<293.0,173.5>> = 8.72114847266126
	* r (U+0072): L<<207.0,410.0>--<150.0,255.0>>/B<<150.0,255.0>-<195.0,324.0>-<247.0,381.0>> = 12.92075033583156
	* racute (U+0155): L<<207.0,410.0>--<150.0,255.0>>/B<<150.0,255.0>-<195.0,324.0>-<247.0,381.0>> = 12.92075033583156
	* rcaron (U+0159): L<<207.0,410.0>--<150.0,255.0>>/B<<150.0,255.0>-<195.0,324.0>-<247.0,381.0>> = 12.92075033583156
	* six (U+0036): B<<295.0,473.5>-<226.0,406.0>-<185.0,337.0>>/B<<185.0,337.0>-<234.0,394.0>-<294.0,426.5>> = 9.965068216105157
	* uni0157 (U+0157): L<<207.0,410.0>--<150.0,255.0>>/B<<150.0,255.0>-<195.0,324.0>-<247.0,381.0>> = 12.92075033583156
	* uni0211 (U+0211): L<<207.0,410.0>--<150.0,255.0>>/B<<150.0,255.0>-<195.0,324.0>-<247.0,381.0>> = 12.92075033583156 and uni0213 (U+0213): L<<207.0,410.0>--<150.0,255.0>>/B<<150.0,255.0>-<195.0,324.0>-<247.0,381.0>> = 12.92075033583156 [code: found-jaggy-segments]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 6 | 8 | 11 | 101 | 7 | 90 | 0 |
| 3% | 4% | 5% | 45% | 3% | 40% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
