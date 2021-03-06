

- - -

**Hirudo\Core\Context\Assets**


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Core/Context/Assets.php#L33" target='_blank'>framework\Hirudo\Core\Context\Assets.php at line 33</a>

#Class Assets#

**Assets**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Impl/Drupal/DrupalAssets.md">Hirudo\Impl\Drupal\DrupalAssets</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Impl/Joomla/V15/JoomlaAssets.md">Hirudo\Impl\Joomla\V15\JoomlaAssets</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Impl/Joomla/V30/JoomlaAssets.md">Hirudo\Impl\Joomla\V30\JoomlaAssets</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Impl/StandAlone/SAssets.md">Hirudo\Impl\StandAlone\SAssets</a> </dd>
</dl>



- - -

<p><strong>public abstract  class</strong> <span>Assets</span></p>

<div class="comment" id="overview_description"><p><p>This class creates the script and link tags.</p></p><p><p><strong>Note:</strong> The entire tag is created instead of just adjusting
the path to the asset. This is because adjusting the path is not enough in
some CMS, like Joomla.</p></p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
</dl>


<hr />

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'>abstract </span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#addjavascript">addJavaScript</a>(string jsPath, boolean external)</p><p class="description">Creates a script tag. </p></td>
</tr>
<tr>
<td><span class='k'>abstract </span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#addcss">addCSS</a>(string cssPath, boolean external)</p><p class="description">Creates a link tag. </p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#generatescripttag">generateScriptTag</a>(string jsPath)</p><p class="description">This helper function generates a script tag which src attribute will
be set to the given path. </p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#generatecsstag">generateCSSTag</a>(string cssPath)</p><p class="description">This helper function generates a link tag which src attribute will
be set to the given path. </p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#resolvelocalpath">resolveLocalPath</a>(mixed path)</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Core/Context/Assets.php#L49" target='_blank'>framework\Hirudo\Core\Context\Assets.php at line 49</a>

<h3 id="addJavaScript()">addJavaScript</h3>
<span class='k'>abstract </span> <span class='nx'>string</span> <span class='nf'>addJavaScript</span> (string jsPath, boolean external)

<div class="details">
<p><p>Creates a script tag. Depending on the CMS it will may automatically insert
the tag using the CMS assets system or simply returns a string representing
the tag.</p></p><dl>
<dt>Parameters:</dt>
<dd>jsPath - The path to a JavaScript file. The path is as if the current directory were the assets/ folder, thus, if the javascript file is at <code>MyHirudoProject/assets/js/Path/To/MyScript.js</code> the jsPath should be <code>js/Path/To/MyScript.js</code>.</dd>
<dd>external - Is the script external to the application? in such case the path is considered absolute.</dd>
<dt>Returns:</dt>
<dd>The script tag.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Core/Context/Assets.php#L65" target='_blank'>framework\Hirudo\Core\Context\Assets.php at line 65</a>

<h3 id="addCSS()">addCSS</h3>
<span class='k'>abstract </span> <span class='nx'>string</span> <span class='nf'>addCSS</span> (string cssPath, boolean external)

<div class="details">
<p><p>Creates a link tag. Depending on the CMS it will may automatically insert
the tag using the CMS assets system or simply returns a string representing
the tag.</p></p><dl>
<dt>Parameters:</dt>
<dd>cssPath - The path to a CSS file. The path is as if the current directory were the assets/ folder, thus, if the CSS file is at <code>MyHirudoProject/assets/css/Path/To/MyCSS.css</code> the cssPath should be <code>css/Path/To/MyCSS.css</code>.</dd>
<dd>external - Is the css external to the application? in such case the path is considered absolute.</dd>
<dt>Returns:</dt>
<dd>The link tag.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Core/Context/Assets.php#L75" target='_blank'>framework\Hirudo\Core\Context\Assets.php at line 75</a>

<h3 id="generateScriptTag()">generateScriptTag</h3>
<span class='k'>protected </span> <span class='nx'>string</span> <span class='nf'>generateScriptTag</span> (string jsPath)

<div class="details">
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


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Core/Context/Assets.php#L87" target='_blank'>framework\Hirudo\Core\Context\Assets.php at line 87</a>

<h3 id="generateCSSTag()">generateCSSTag</h3>
<span class='k'>protected </span> <span class='nx'>string</span> <span class='nf'>generateCSSTag</span> (string cssPath)

<div class="details">
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


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Core/Context/Assets.php#L91" target='_blank'>framework\Hirudo\Core\Context\Assets.php at line 91</a>

<h3 id="resolveLocalPath()">resolveLocalPath</h3>
<span class='k'>protected </span> <span class='nx'>void</span> <span class='nf'>resolveLocalPath</span> (mixed path)

<div class="details">

</div>

- - -

