## Fontbakery report

Fontbakery version: 0.8.10

<details><summary><b>[7] NotoSansAnatolianHieroglyphs-Regular.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Anatolian Hieroglyphs' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* u144DD (U+144DD): L<<332.0,730.0>--<339.0,714.0>> -> L<<339.0,714.0>--<347.0,699.0>>

	* u145CD (U+145CD): L<<135.0,179.0>--<150.0,155.0>> -> L<<150.0,155.0>--<240.0,22.0>>

	* u145F6 (U+145F6): L<<103.0,106.0>--<108.0,75.0>> -> L<<108.0,75.0>--<111.0,60.0>> 

	* And u14642 (U+14642): L<<678.0,56.0>--<678.0,53.0>> -> L<<678.0,53.0>--<679.0,41.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* u14404 (U+14404): B<<363.0,497.0>-<363.0,491.0>-<362.0,489.0>>/B<<362.0,489.0>-<380.0,514.0>-<380.0,547.0>> = 9.188836077358738

	* u1443C (U+1443C): B<<345.0,100.0>-<345.0,82.0>-<342.0,64.0>>/B<<342.0,64.0>-<366.0,125.0>-<376.5,194.0>> = 12.014468771514725

	* u1443C (U+1443C): B<<520.5,194.0>-<531.0,125.0>-<555.0,64.0>>/B<<555.0,64.0>-<552.0,82.0>-<552.0,100.0>> = 12.014468771514725

	* u1446D (U+1446D): B<<408.0,374.0>-<388.0,393.0>-<374.0,410.0>>/B<<374.0,410.0>-<385.0,387.0>-<397.0,363.5>> = 13.912494676519978

	* u14474 (U+14474): B<<174.0,900.0>-<184.0,889.0>-<186.0,881.0>>/B<<186.0,881.0>-<186.0,908.0>-<200.5,931.0>> = 14.036243467926484

	* u144C2 (U+144C2): B<<612.0,185.5>-<607.0,246.0>-<597.0,304.0>>/L<<597.0,304.0>--<597.0,0.0>> = 9.782407031807285

	* u144C2 (U+144C2): L<<397.0,0.0>--<397.0,305.0>>/B<<397.0,305.0>-<387.0,246.0>-<382.0,185.5>> = 9.61972779969886

	* u1450A (U+1450A): L<<264.0,341.0>--<286.0,94.0>>/L<<286.0,94.0>--<308.0,341.0>> = 10.179673018575683

	* u1450A (U+1450A): L<<494.0,341.0>--<516.0,94.0>>/L<<516.0,94.0>--<538.0,341.0>> = 10.179673018575683

	* u1450B (U+1450B): L<<249.0,510.0>--<286.0,94.0>>/L<<286.0,94.0>--<323.0,510.0>> = 10.16528904835857 

	* And 18 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 0 | 7 | 111 | 7 | 102 | 0 |
| 0% | 0% | 3% | 49% | 3% | 45% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
