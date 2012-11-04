

- - -

**Hirudo\Impl\Joomla\JoomlaAssets**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/Joomla/JoomlaAssets.php#L14" target='_blank'>framework\hirudo\Hirudo\Impl\Joomla\JoomlaAssets.php at line 14</a>

#Class JoomlaAssets#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/Assets.md">Assets</a>
 &gt; **JoomlaAssets**




- - -

<p><strong>public  class</strong> <span>JoomlaAssets</span>
<strong>extends</strong> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/Assets.md">Assets</a>

</p>

<div class="comment" id="overview_description"><p>Description of JoomlaAssets</p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
<dt>Export(id="assets").</dt>
</dl>


<hr />

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>()</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#addcss">addCSS</a>(string cssPath)</p><p class="description">Creates a link tag. </p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#addjavascript">addJavaScript</a>(string jsPath)</p><p class="description">Creates a script tag. </p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Hirudo\Core\Context\Assets</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/Assets.md#addcss">addCSS</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/Assets.md#addjavascript">addJavaScript</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/Assets.md#generatecsstag">generateCSSTag</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/Assets.md#generatescripttag">generateScriptTag</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/Assets.md#resolvelocalpath">resolveLocalPath</a></td></tr></table>

<h2>Constructor Detail</h2>


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/Joomla/JoomlaAssets.php#L18" target='_blank'>framework\hirudo\Hirudo\Impl\Joomla\JoomlaAssets.php at line 18</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> ()

<div class="details">

</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/Joomla/JoomlaAssets.php#L23" target='_blank'>framework\hirudo\Hirudo\Impl\Joomla\JoomlaAssets.php at line 23</a>

<h3 id="addCSS()">addCSS</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>addCSS</span> (string cssPath)

<div class="details">
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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/Joomla/JoomlaAssets.php#L28" target='_blank'>framework\hirudo\Hirudo\Impl\Joomla\JoomlaAssets.php at line 28</a>

<h3 id="addJavaScript()">addJavaScript</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>addJavaScript</span> (string jsPath)

<div class="details">
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

