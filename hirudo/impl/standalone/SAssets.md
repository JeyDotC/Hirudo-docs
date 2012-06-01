

- - -

**Hirudo\Impl\StandAlone\SAssets**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/SAssets.php#L14" >framework\hirudo\Hirudo\Impl\StandAlone\SAssets.php at line 14</a>

#Class SAssets#

<a href="">Assets</a>
    * **SAssets**




- - -

<p class="signature"><span class='k'>public  class</span> <span class='nx'>SAssets</span>
extends <a href="">Assets</a>

</p>

<div class="comment" id="overview_description"><p>Description of SAssets</p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
<dt>Export(id="assets").</dt>
</dl>


- - -

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
<tr><td><a href="">addCSS</a>, <a href="">addJavaScript</a>, <a href="">generateCSSTag</a>, <a href="">generateScriptTag</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/SAssets.php#L16" >framework\hirudo\Hirudo\Impl\StandAlone\SAssets.php at line 16</a>

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/StandAlone/SAssets.php#L20" >framework\hirudo\Hirudo\Impl\StandAlone\SAssets.php at line 20</a>

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

