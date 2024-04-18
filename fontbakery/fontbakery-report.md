## FontBakery report

fontbakery version: 0.12.2



## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] MiriamLibre[wght].ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Validate location, size and resolution of article images. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/variable does not have an article.</p>
 [code: lacks-article]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[9] MiriamLibre[wght].ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Check accent of Lcaron, dcaron, lcaron, tcaron <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>









* ⚠️ **WARN** <p>Lcaron is decomposed and therefore could not be checked. Please check manually.</p>
 [code: decomposed-outline]



* ⚠️ **WARN** <p>lcaron is decomposed and therefore could not be checked. Please check manually.</p>
 [code: decomposed-outline]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 626 among a set of 6 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 549:
less, greaterequal, greater, lessequal</p>
<p>Width = 586:
plusminus</p>
<p>Width = 517:
multiply</p>
<p>Width = 612:
approxequal</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have on-curve points which have potentially incorrect y coordinates:</p>
<pre><code>* dollar (U+0024): X=157.5,Y=1.0 (should be at baseline 0?)

* dollar (U+0024): X=380.5,Y=694.5 (should be at cap-height 695?)

* percent (U+0025): X=642.0,Y=696.0 (should be at cap-height 695?)

* asterisk (U+002A): X=115.0,Y=693.0 (should be at cap-height 695?)

* asterisk (U+002A): X=363.0,Y=693.0 (should be at cap-height 695?)

* asterisk (U+002A): X=368.0,Y=694.5 (should be at cap-height 695?)

* one (U+0031): X=261.0,Y=694.0 (should be at cap-height 695?)

* two (U+0032): X=162.0,Y=693.5 (should be at cap-height 695?)

* five (U+0035): X=345.5,Y=1.5 (should be at baseline 0?)

* at (U+0040): X=469.0,Y=694.0 (should be at cap-height 695?)

* S (U+0053): X=147.5,Y=1.0 (should be at baseline 0?)

* S (U+0053): X=370.5,Y=694.5 (should be at cap-height 695?)

* d (U+0064): X=354.5,Y=564.0 (should be at x-height 566?)

* g (U+0067): X=417.5,Y=1.5 (should be at baseline 0?)

* n (U+006E): X=104.0,Y=1.0 (should be at baseline 0?)

* n (U+006E): X=505.0,Y=1.0 (should be at baseline 0?)

* n (U+006E): X=455.0,Y=1.0 (should be at baseline 0?)

* n (U+006E): X=154.0,Y=1.0 (should be at baseline 0?)

* p (U+0070): X=235.5,Y=2.0 (should be at baseline 0?)

* r (U+0072): X=429.5,Y=568.0 (should be at x-height 566?)

* s (U+0073): X=136.5,Y=2.0 (should be at baseline 0?)

* s (U+0073): X=321.0,Y=567.0 (should be at x-height 566?)

* sterling (U+00A3): X=486.0,Y=694.0 (should be at cap-height 695?)

* copyright (U+00A9): X=484.0,Y=694.0 (should be at cap-height 695?)

* ordfeminine (U+00AA): X=126.5,Y=696.0 (should be at cap-height 695?)

* registered (U+00AE): X=484.0,Y=694.0 (should be at cap-height 695?)

* uni00B3 (U+00B3): X=236.5,Y=694.0 (should be at cap-height 695?)

* ordmasculine (U+00BA): X=136.0,Y=694.5 (should be at cap-height 695?)

* ordmasculine (U+00BA): X=260.0,Y=694.5 (should be at cap-height 695?)

* onequarter (U+00BC): X=82.0,Y=-2.0 (should be at baseline 0?)

* onequarter (U+00BC): X=645.0,Y=696.0 (should be at cap-height 695?)

* onehalf (U+00BD): X=90.0,Y=-2.0 (should be at baseline 0?)

* onehalf (U+00BD): X=653.0,Y=696.0 (should be at cap-height 695?)

* threequarters (U+00BE): X=256.5,Y=694.0 (should be at cap-height 695?)

* threequarters (U+00BE): X=98.0,Y=-2.0 (should be at baseline 0?)

* threequarters (U+00BE): X=661.0,Y=696.0 (should be at cap-height 695?)

* ntilde (U+00F1): X=104.0,Y=1.0 (should be at baseline 0?)

* ntilde (U+00F1): X=505.0,Y=1.0 (should be at baseline 0?)

* ntilde (U+00F1): X=455.0,Y=1.0 (should be at baseline 0?)

* ntilde (U+00F1): X=154.0,Y=1.0 (should be at baseline 0?)

* abreve (U+0103): X=150.0,Y=697.0 (should be at cap-height 695?)

* abreve (U+0103): X=402.0,Y=697.0 (should be at cap-height 695?)

* gbreve (U+011F): X=417.5,Y=1.5 (should be at baseline 0?)

* gbreve (U+011F): X=151.0,Y=697.0 (should be at cap-height 695?)

* gbreve (U+011F): X=403.0,Y=697.0 (should be at cap-height 695?)

* gdotaccent (U+0121): X=417.5,Y=1.5 (should be at baseline 0?)

* uni0123 (U+0123): X=417.5,Y=1.5 (should be at baseline 0?)

* nacute (U+0144): X=104.0,Y=1.0 (should be at baseline 0?)

* nacute (U+0144): X=505.0,Y=1.0 (should be at baseline 0?)

* nacute (U+0144): X=455.0,Y=1.0 (should be at baseline 0?)

* nacute (U+0144): X=154.0,Y=1.0 (should be at baseline 0?)

* uni0146 (U+0146): X=104.0,Y=1.0 (should be at baseline 0?)

* uni0146 (U+0146): X=505.0,Y=1.0 (should be at baseline 0?)

* uni0146 (U+0146): X=455.0,Y=1.0 (should be at baseline 0?)

* uni0146 (U+0146): X=154.0,Y=1.0 (should be at baseline 0?)

* ncaron (U+0148): X=104.0,Y=1.0 (should be at baseline 0?)

* ncaron (U+0148): X=505.0,Y=1.0 (should be at baseline 0?)

* ncaron (U+0148): X=455.0,Y=1.0 (should be at baseline 0?)

* ncaron (U+0148): X=154.0,Y=1.0 (should be at baseline 0?)

* Eng (U+014A): X=508.0,Y=-1.0 (should be at baseline 0?)

* eng (U+014B): X=154.0,Y=1.0 (should be at baseline 0?)

* eng (U+014B): X=104.0,Y=1.0 (should be at baseline 0?)

* Sacute (U+015A): X=147.5,Y=1.0 (should be at baseline 0?)

* Sacute (U+015A): X=370.5,Y=694.5 (should be at cap-height 695?)

* sacute (U+015B): X=136.5,Y=2.0 (should be at baseline 0?)

* Scedilla (U+015E): X=147.5,Y=1.0 (should be at baseline 0?)

* Scedilla (U+015E): X=370.5,Y=694.5 (should be at cap-height 695?)

* scedilla (U+015F): X=136.5,Y=2.0 (should be at baseline 0?)

* Scaron (U+0160): X=147.5,Y=1.0 (should be at baseline 0?)

* Scaron (U+0160): X=370.5,Y=694.5 (should be at cap-height 695?)

* scaron (U+0161): X=136.5,Y=2.0 (should be at baseline 0?)

* uni0218 (U+0218): X=147.5,Y=1.0 (should be at baseline 0?)

* uni0218 (U+0218): X=370.5,Y=694.5 (should be at cap-height 695?)

* uni0219 (U+0219): X=136.5,Y=2.0 (should be at baseline 0?)

* breve (U+02D8): X=175.0,Y=697.0 (should be at cap-height 695?)

* breve (U+02D8): X=427.0,Y=697.0 (should be at cap-height 695?)

* uni0306 (U+0306): X=126.0,Y=697.0 (should be at cap-height 695?)

* uni0306 (U+0306): X=378.0,Y=697.0 (should be at cap-height 695?)

* pi (U+03C0): X=703.0,Y=-1.0 (should be at baseline 0?)

* perthousand (U+2030): X=628.0,Y=696.0 (should be at cap-height 695?)

* fraction (U+2044): X=20.0,Y=-2.0 (should be at baseline 0?)

* fraction (U+2044): X=583.0,Y=696.0 (should be at cap-height 695?)

* estimated (U+212E): X=234.5,Y=693.0 (should be at cap-height 695?)

* estimated (U+212E): X=437.0,Y=693.0 (should be at cap-height 695?)

* uni2206 (U+2206): X=324.0,Y=697.0 (should be at cap-height 695?)

* uni2206 (U+2206): X=410.0,Y=697.0 (should be at cap-height 695?)

* product (U+220F): X=45.0,Y=696.0 (should be at cap-height 695?)

* product (U+220F): X=827.0,Y=696.0 (should be at cap-height 695?)

* summation (U+2211): X=626.0,Y=696.0 (should be at cap-height 695?)
</code></pre>
 [code: found-misalignments]



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
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02C7 CARON: try adding one of: yi, tifinagh, canadian-aboriginal</li>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, cherokee, coptic</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, syriac, tifinagh, coptic, math, canadian-aboriginal, malayalam, old-permic</li>
<li>U+030A COMBINING RING ABOVE: try adding syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition</li>
<li>U+0326 COMBINING COMMA BELOW: not included in any glyphset definition</li>
<li>U+0327 COMBINING CEDILLA: not included in any glyphset definition</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition</li>
<li>U+0336 COMBINING LONG STROKE OVERLAY: not included in any glyphset definition</li>
<li>U+0337 COMBINING SHORT SOLIDUS OVERLAY: not included in any glyphset definition</li>
<li>U+0338 COMBINING LONG SOLIDUS OVERLAY: not included in any glyphset definition</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+2126 OHM SIGN: not included in any glyphset definition</li>
<li>U+212E ESTIMATED SYMBOL: not included in any glyphset definition</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+2206 INCREMENT: try adding math</li>
<li>U+220F N-ARY PRODUCT: try adding math</li>
<li>U+2211 N-ARY SUMMATION: try adding math</li>
<li>U+2219 BULLET OPERATOR: try adding one of: math, yi, tai-tham, symbols</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CA LOZENGE: try adding one of: math, symbols</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>cyrillic-ext</code>, <code>greek-ext</code>, <code>hebrew</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Is there kerning info for non-ligated sequences? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gpos.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning info for the following non-ligated sequences:</p>
<pre><code>- f + i

- f + l
</code></pre>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure variable fonts include an avar table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.varfont.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This variable font does not have an avar table.</p>
 [code: missing-avar]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">de_Latn (German)</td>
<td align="left">Some base glyphs were missing: ẞ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">de_Latn (German)</td>
<td align="left">Some auxiliary glyphs were missing: ẞ</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Missing required codepoints:</p>
<pre><code>- 0x02DC (SMALL TILDE)


- 0x1E9E (LATIN CAPITAL LETTER SHARP S)
</code></pre>
 [code: missing-codepoints]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 2 | 8 | 95 | 8 | 136 | 0 | 
| 0% | 0% | 1% | 3% | 38% | 3% | 55% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
