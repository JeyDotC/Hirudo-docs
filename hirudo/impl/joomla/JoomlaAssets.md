- - -

**Hirudo\Impl\Joomla\JoomlaAssets**
<div class="location">framework\hirudo\Hirudo\Impl\Joomla\JoomlaAssets.php at line 14</div>
#Class JoomlaAssets#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/assets.html">Assets</a>
    ***JoomlaAssets**


- - -

<p class="signature">public  class **JoomlaAssets**
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/assets.html">Assets</a>

</p>

<div class="comment" id="overview_description"><p>Description of JoomlaAssets</p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
<dt>Export(id="assets").</dt>
</dl>
- - -

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>()</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#load">load</a>(mixed assetPath)</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#addCSS">addCSS</a>(string cssPath)</p><p class="description">Creates a link tag. </p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#addJavaScript">addJavaScript</a>(string jsPath)</p><p class="description">Creates a script tag. </p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Hirudo\Core\Context\Assets</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/assets.html#addCSS()">addCSS</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/assets.html#addJavaScript()">addJavaScript</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/assets.html#generateCSSTag()">generateCSSTag</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/assets.html#generateScriptTag()">generateScriptTag</a></td></tr></table>

<h2 id="detail_method">Constructor Detail</h2>
<div class="location">framework\hirudo\Hirudo\Impl\Joomla\JoomlaAssets.php at line 18</div>
<h3 id="__construct()">__construct</h3>
```php
public  void **__construct**()```
<div class="details">
</div>

- - -

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\hirudo\Hirudo\Impl\Joomla\JoomlaAssets.php at line 23</div>
<h3 id="load()">load</h3>
```php
public  void **load**(mixed assetPath)```
<div class="details">
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Impl\Joomla\JoomlaAssets.php at line 28</div>
<h3 id="addCSS()">addCSS</h3>
```php
public  string **addCSS**(string cssPath)```
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

<div class="location">framework\hirudo\Hirudo\Impl\Joomla\JoomlaAssets.php at line 33</div>
<h3 id="addJavaScript()">addJavaScript</h3>
```php
public  string **addJavaScript**(string jsPath)```
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

