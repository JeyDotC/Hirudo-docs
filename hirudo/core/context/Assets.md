
- - -

**Hirudo\Core\Context\Assets**
<div class="location">framework\hirudo\Hirudo\Core\Context\Assets.php at line 32</div>
#Class Assets#

**Assets**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/impl/joomla/joomlaassets.html">Hirudo\Impl\Joomla\JoomlaAssets</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/impl/standalone/sassets.html">Hirudo\Impl\StandAlone\SAssets</a> </dd>
</dl>

- - -

<p class="signature">public abstract  class **Assets**</p>

<div class="comment" id="overview_description"><p><p>This class creates the script and link tags.</p></p><p><p><strong>Note:</strong> The entire tag is created instead of just adjusting
the path to the asset. This is because adjusting the path is not enough in
some CMS, like Joomla.</p></p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
</dl>

- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> abstract  string</td>
<td class="description"><p class="name"><a href="#addjavascript">addJavaScript</a>(string jsPath)</p><p class="description">Creates a script tag. </p></td>
</tr>
<tr>
<td class="type"> abstract  string</td>
<td class="description"><p class="name"><a href="#addcss">addCSS</a>(string cssPath)</p><p class="description">Creates a link tag. </p></td>
</tr>
<tr>
<td class="type"> protected  string</td>
<td class="description"><p class="name"><a href="#generatescripttag">generateScriptTag</a>(string jsPath)</p><p class="description">This helper function generates a script tag which src attribute will
be set to the given path. </p></td>
</tr>
<tr>
<td class="type"> protected  string</td>
<td class="description"><p class="name"><a href="#generatecsstag">generateCSSTag</a>(string cssPath)</p><p class="description">This helper function generates a link tag which src attribute will
be set to the given path. </p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\hirudo\Hirudo\Core\Context\Assets.php at line 46</div>
<h3 id="addJavaScript()">addJavaScript</h3>

public abstract  string **addJavaScript** (string jsPath)<div class="details">
<p><p>Creates a script tag. Depending on the CMS it will may automatically insert
the tag using the CMS assets system or simply returns a string representing
the tag.</p></p><dl>
<dt>Parameters:</dt>
<dd>jsPath - The path to a JavaScript file. The path is as if the current directory were the assets/ folder, thus, if the javascript file is at <code>MyHirudoProject/assets/js/Path/To/MyScript.js</code> the jsPath should be <code>js/Path/To/MyScript.js</code>.</dd>
<dt>Returns:</dt>
<dd>The script tag.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Context\Assets.php at line 60</div>
<h3 id="addCSS()">addCSS</h3>

public abstract  string **addCSS** (string cssPath)<div class="details">
<p><p>Creates a link tag. Depending on the CMS it will may automatically insert
the tag using the CMS assets system or simply returns a string representing
the tag.</p></p><dl>
<dt>Parameters:</dt>
<dd>cssPath - The path to a CSS file. The path is as if the current directory were the assets/ folder, thus, if the CSS file is at <code>MyHirudoProject/assets/css/Path/To/MyCSS.css</code> the cssPath should be <code>css/Path/To/MyCSS.css</code>.</dd>
<dt>Returns:</dt>
<dd>The link tag.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Context\Assets.php at line 70</div>
<h3 id="generateScriptTag()">generateScriptTag</h3>

protected  string **generateScriptTag** (string jsPath)<div class="details">
<p>This helper function generates a script tag which src attribute will
be set to the given path. Note that the jsPath must be already adjusted
to meet the CMS conventions.</p><dl>
<dt>Parameters:</dt>
<dd>jsPath - A path to a javascript file.</dd>
<dt>Returns:</dt>
<dd>The script tag.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Context\Assets.php at line 82</div>
<h3 id="generateCSSTag()">generateCSSTag</h3>

protected  string **generateCSSTag** (string cssPath)<div class="details">
<p>This helper function generates a link tag which src attribute will
be set to the given path. Note that the cssPath must be already adjusted
to meet the CMS conventions.</p><dl>
<dt>Parameters:</dt>
<dd>cssPath - A path to a CSS file.</dd>
<dt>Returns:</dt>
<dd>The link tag.</dd>
</dl>
</div>

- - -

