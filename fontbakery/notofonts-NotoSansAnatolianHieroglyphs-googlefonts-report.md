## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[10] NotoSansAnatolianHieroglyphs-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check for presence of an ARTICLE.en_us.html file <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.description.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>This is a Noto font but it lacks an ARTICLE.en_us.html file.</p>
 [code: missing-article]



* 🔥 **FAIL** <p>This is a Noto font but it lacks a DESCRIPTION.en_us.html file.</p>
 [code: missing-description]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSansAnatolianHieroglyphs/googlefonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, tifinagh, cherokee, math</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, tai-le, coptic, canadian-aboriginal, duployan, math, hebrew, malayalam, tifinagh, todhri, syriac</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>anatolian-hieroglyphs</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Combined length of family and style must not exceed 32 characters. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.name.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Name ID 6 'NotoSansAnatolianHieroglyphs-Regular' exceeds 27 characters. This has been found to cause problems with PostScript printers, especially on Mac platforms.</p>
 [code: nameid6-too-long]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̧̀ į̧́ į̧̂ į̧̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Lugbara (Latn, 2,200,000 speakers), Mfumte (Latn, 79,000 speakers), Bafut (Latn, 158,146 speakers), Nateni (Latn, 100,000 speakers), Ma’di (Latn, 584,000 speakers), Heiltsuk (Latn, 300 speakers), Dan (Latn, 1,099,244 speakers), Makaa (Latn, 221,000 speakers), Navajo (Latn, 166,319 speakers), South Central Banda (Latn, 244,000 speakers), Basaa (Latn, 332,940 speakers), Igbo (Latn, 27,823,640 speakers), Dii (Latn, 71,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Kom (Latn, 360,685 speakers), Nzakara (Latn, 50,000 speakers), Han (Latn, 6 speakers), Ngbaka (Latn, 1,020,000 speakers), Ebira (Latn, 2,200,000 speakers), Mango (Latn, 77,000 speakers), Fur (Latn, 1,230,163 speakers), Ekpeye (Latn, 226,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Southern Kisi (Latn, 360,000 speakers), Vute (Latn, 21,000 speakers), Avokaya (Latn, 100,000 speakers), Koonzime (Latn, 40,000 speakers), Cicipu (Latn, 44,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Kaska (Latn, 125 speakers), Sar (Latn, 500,000 speakers), Yala (Latn, 200,000 speakers), Zapotec (Latn, 490,000 speakers), Mundani (Latn, 34,000 speakers), Ejagham (Latn, 120,000 speakers), Aghem (Latn, 38,843 speakers), Gulay (Latn, 250,478 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* u144DD (U+144DD): L&lt;&lt;332.0,730.0&gt;--&lt;339.0,714.0&gt;&gt; -&gt; L&lt;&lt;339.0,714.0&gt;--&lt;347.0,699.0&gt;&gt;

* u145CD (U+145CD): L&lt;&lt;135.0,179.0&gt;--&lt;150.0,155.0&gt;&gt; -&gt; L&lt;&lt;150.0,155.0&gt;--&lt;240.0,22.0&gt;&gt;

* u145F6 (U+145F6): L&lt;&lt;103.0,106.0&gt;--&lt;108.0,75.0&gt;&gt; -&gt; L&lt;&lt;108.0,75.0&gt;--&lt;111.0,60.0&gt;&gt;

* u14642 (U+14642): L&lt;&lt;678.0,56.0&gt;--&lt;678.0,53.0&gt;&gt; -&gt; L&lt;&lt;678.0,53.0&gt;--&lt;679.0,41.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* u14404 (U+14404): B&lt;&lt;363.0,497.0&gt;-&lt;363.0,491.0&gt;-&lt;362.0,489.0&gt;&gt;/B&lt;&lt;362.0,489.0&gt;-&lt;380.0,514.0&gt;-&lt;380.0,547.0&gt;&gt; = 9.188836077358738

* u1443C (U+1443C): B&lt;&lt;345.0,100.0&gt;-&lt;345.0,82.0&gt;-&lt;342.0,64.0&gt;&gt;/B&lt;&lt;342.0,64.0&gt;-&lt;366.0,125.0&gt;-&lt;376.5,194.0&gt;&gt; = 12.014468771514725

* u1443C (U+1443C): B&lt;&lt;520.5,194.0&gt;-&lt;531.0,125.0&gt;-&lt;555.0,64.0&gt;&gt;/B&lt;&lt;555.0,64.0&gt;-&lt;552.0,82.0&gt;-&lt;552.0,100.0&gt;&gt; = 12.014468771514725

* u1446D (U+1446D): B&lt;&lt;408.0,374.0&gt;-&lt;388.0,393.0&gt;-&lt;374.0,410.0&gt;&gt;/B&lt;&lt;374.0,410.0&gt;-&lt;385.0,387.0&gt;-&lt;397.0,363.5&gt;&gt; = 13.912494676519978

* u14474 (U+14474): B&lt;&lt;174.0,900.0&gt;-&lt;184.0,889.0&gt;-&lt;186.0,881.0&gt;&gt;/B&lt;&lt;186.0,881.0&gt;-&lt;186.0,908.0&gt;-&lt;200.5,931.0&gt;&gt; = 14.036243467926484

* u144C2 (U+144C2): B&lt;&lt;612.0,185.5&gt;-&lt;607.0,246.0&gt;-&lt;597.0,304.0&gt;&gt;/L&lt;&lt;597.0,304.0&gt;--&lt;597.0,0.0&gt;&gt; = 9.782407031807285

* u144C2 (U+144C2): L&lt;&lt;397.0,0.0&gt;--&lt;397.0,305.0&gt;&gt;/B&lt;&lt;397.0,305.0&gt;-&lt;387.0,246.0&gt;-&lt;382.0,185.5&gt;&gt; = 9.61972779969886

* u1450A (U+1450A): L&lt;&lt;264.0,341.0&gt;--&lt;286.0,94.0&gt;&gt;/L&lt;&lt;286.0,94.0&gt;--&lt;308.0,341.0&gt;&gt; = 10.179673018575683

* u1450A (U+1450A): L&lt;&lt;494.0,341.0&gt;--&lt;516.0,94.0&gt;&gt;/L&lt;&lt;516.0,94.0&gt;--&lt;538.0,341.0&gt;&gt; = 10.179673018575683

* u1450B (U+1450B): L&lt;&lt;249.0,510.0&gt;--&lt;286.0,94.0&gt;&gt;/L&lt;&lt;286.0,94.0&gt;--&lt;323.0,510.0&gt;&gt; = 10.16528904835857

* u1450B (U+1450B): L&lt;&lt;479.0,510.0&gt;--&lt;516.0,94.0&gt;&gt;/L&lt;&lt;516.0,94.0&gt;--&lt;553.0,510.0&gt;&gt; = 10.16528904835857

* u1450B (U+1450B): L&lt;&lt;709.0,510.0&gt;--&lt;746.0,94.0&gt;&gt;/L&lt;&lt;746.0,94.0&gt;--&lt;783.0,510.0&gt;&gt; = 10.16528904835857

* u14539 (U+14539): B&lt;&lt;195.5,406.5&gt;-&lt;208.0,435.0&gt;-&lt;224.0,458.0&gt;&gt;/B&lt;&lt;224.0,458.0&gt;-&lt;211.0,445.0&gt;-&lt;196.5,436.5&gt;&gt; = 10.175510843043194

* u1453A (U+1453A): L&lt;&lt;160.0,614.0&gt;--&lt;550.0,144.0&gt;&gt;/L&lt;&lt;550.0,144.0&gt;--&lt;298.0,670.0&gt;&gt; = 14.086958041300855

* u1454A (U+1454A): B&lt;&lt;159.0,34.5&gt;-&lt;118.0,9.0&gt;-&lt;97.0,3.0&gt;&gt;/B&lt;&lt;97.0,3.0&gt;-&lt;132.0,4.0&gt;-&lt;176.5,15.5&gt;&gt; = 14.308818859306113

* u1454C (U+1454C): B&lt;&lt;591.5,19.5&gt;-&lt;637.0,7.0&gt;-&lt;670.0,6.0&gt;&gt;/B&lt;&lt;670.0,6.0&gt;-&lt;645.0,13.0&gt;-&lt;588.5,48.5&gt;&gt; = 13.906541868280332

* u1454D (U+1454D): B&lt;&lt;769.5,19.5&gt;-&lt;815.0,7.0&gt;-&lt;848.0,6.0&gt;&gt;/B&lt;&lt;848.0,6.0&gt;-&lt;823.0,13.0&gt;-&lt;766.5,48.5&gt;&gt; = 13.906541868280332

* u1454E (U+1454E): B&lt;&lt;769.5,19.5&gt;-&lt;815.0,7.0&gt;-&lt;848.0,6.0&gt;&gt;/B&lt;&lt;848.0,6.0&gt;-&lt;823.0,13.0&gt;-&lt;766.5,48.5&gt;&gt; = 13.906541868280332

* u14553 (U+14553): L&lt;&lt;164.0,303.0&gt;--&lt;662.0,303.0&gt;&gt;/L&lt;&lt;662.0,303.0&gt;--&lt;115.0,344.0&gt;&gt; = 4.286549330297288

* u14558 (U+14558): B&lt;&lt;245.0,346.0&gt;-&lt;252.0,323.0&gt;-&lt;253.0,287.0&gt;&gt;/B&lt;&lt;253.0,287.0&gt;-&lt;255.0,322.0&gt;-&lt;261.5,345.0&gt;&gt; = 4.861628194378152

* u14558 (U+14558): B&lt;&lt;280.5,165.0&gt;-&lt;257.0,208.0&gt;-&lt;254.0,254.0&gt;&gt;/B&lt;&lt;254.0,254.0&gt;-&lt;250.0,211.0&gt;-&lt;229.0,169.0&gt;&gt; = 9.045942669105177

* u14558 (U+14558): B&lt;&lt;432.5,346.0&gt;-&lt;439.0,323.0&gt;-&lt;441.0,287.0&gt;&gt;/B&lt;&lt;441.0,287.0&gt;-&lt;443.0,322.0&gt;-&lt;449.5,345.0&gt;&gt; = 6.450318043047734

* u14558 (U+14558): B&lt;&lt;468.0,165.0&gt;-&lt;444.0,208.0&gt;-&lt;441.0,254.0&gt;&gt;/B&lt;&lt;441.0,254.0&gt;-&lt;437.0,211.0&gt;-&lt;416.5,169.0&gt;&gt; = 9.045942669105177

* u1459E (U+1459E): L&lt;&lt;687.0,301.0&gt;--&lt;854.0,367.0&gt;&gt;/L&lt;&lt;854.0,367.0&gt;--&lt;684.0,339.0&gt;&gt; = 12.211427329426295

* u145C7 (U+145C7): L&lt;&lt;285.0,241.0&gt;--&lt;285.0,324.0&gt;&gt;/L&lt;&lt;285.0,324.0&gt;--&lt;256.0,68.0&gt;&gt; = 6.462985770321906

* u145C7 (U+145C7): L&lt;&lt;443.0,68.0&gt;--&lt;411.0,350.0&gt;&gt;/L&lt;&lt;411.0,350.0&gt;--&lt;411.0,241.0&gt;&gt; = 6.473955968672304

* u14633 (U+14633): L&lt;&lt;327.0,634.0&gt;--&lt;416.0,67.0&gt;&gt;/L&lt;&lt;416.0,67.0&gt;--&lt;416.0,831.0&gt;&gt; = 8.9207282780818

* u14633 (U+14633): L&lt;&lt;446.0,831.0&gt;--&lt;446.0,67.0&gt;&gt;/L&lt;&lt;446.0,67.0&gt;--&lt;535.0,634.0&gt;&gt; = 8.9207282780818
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 1 | 9 | 117 | 6 | 118 | 0 | 
| 0% | 0% | 0% | 4% | 47% | 2% | 47% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
