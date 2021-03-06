

- - -

**Hirudo\Impl\Common\Templating\SmartyTemplating**


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/Common/Templating/SmartyTemplating.php#L38" target='_blank'>framework\Hirudo\Impl\Common\Templating\SmartyTemplating.php at line 38</a>

#Class SmartyTemplating#

**SmartyTemplating**


<dl>
<dt>All Implemented Interfaces:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/TemplatingInterface.md">Hirudo\Core\TemplatingInterface</a> </dd>
</dl>



- - -

<p><strong>public  class</strong> <span>SmartyTemplating</span></p>

<div class="comment" id="overview_description"><p>A Smarty based templating system.</p></div>

<dl>
<dt>Hirudo\Core\Annotations\Export(id="templating",:</dt>
<dd>factory="instance")</dd>
</dl>


<hr />

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>()</p><p class="description">Creates a new instance of smarty templating.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#assign">assign</a>(string name, mixed value)</p><p class="description">Adds a variable to the view so it can be accessed from the smarty template.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#display">display</a>(string moduleDir, string view)</p><p class="description">Renders the view and retuns it as a string.</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Impl/Common/Templating/SmartyTemplating.md>SmartyTemplating</a></span></td>
<td class="description"><p class="name"><a href="#instance">instance</a>()</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#addextensionspath">addExtensionsPath</a>(string path)</p><p class="description">Adds a path to smarty extensions so these can be used in the templates.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#pick">pick</a>(mixed views)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#getfileextension">getFileExtension</a>()</p></td>
</tr>
</table>

<h2>Constructor Detail</h2>


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/Common/Templating/SmartyTemplating.php#L49" target='_blank'>framework\Hirudo\Impl\Common\Templating\SmartyTemplating.php at line 49</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> ()

<div class="details">
<p>Creates a new instance of smarty templating.</p>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/Common/Templating/SmartyTemplating.php#L72" target='_blank'>framework\Hirudo\Impl\Common\Templating\SmartyTemplating.php at line 72</a>

<h3 id="assign()">assign</h3>
<span class='k'></span> <span class='nx'>mixed</span> <span class='nf'>assign</span> (string name, mixed value)

<div class="details">
<p><p>Adds a variable to the view so it can be accessed from the smarty template.</p></p><dl>
<dt>Parameters:</dt>
<dd>name - The name that the variable will adopt.</dd>
<dd>value - The value of the variable.</dd>
<dt>Returns:</dt>
<dd>The assigned value</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/Common/Templating/SmartyTemplating.php#L85" target='_blank'>framework\Hirudo\Impl\Common\Templating\SmartyTemplating.php at line 85</a>

<h3 id="display()">display</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>display</span> (string moduleDir, string view)

<div class="details">
<p>Renders the view and retuns it as a string.</p><dl>
<dt>Parameters:</dt>
<dd>moduleDir - The absolute path to the module.</dd>
<dd>view - The name of the view to be rendered.</dd>
<dt>Returns:</dt>
<dd>The output of the view as a string.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/Common/Templating/SmartyTemplating.php#L99" target='_blank'>framework\Hirudo\Impl\Common\Templating\SmartyTemplating.php at line 99</a>

<h3 id="instance()">instance</h3>
<span class='k'>static </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Impl/Common/Templating/SmartyTemplating.md>SmartyTemplating</a></span> <span class='nf'>instance</span> ()

<div class="details">
<p></p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/Common/Templating/SmartyTemplating.php#L112" target='_blank'>framework\Hirudo\Impl\Common\Templating\SmartyTemplating.php at line 112</a>

<h3 id="addExtensionsPath()">addExtensionsPath</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>addExtensionsPath</span> (string path)

<div class="details">
<p>Adds a path to smarty extensions so these can be used in the templates.</p><dl>
<dt>Parameters:</dt>
<dd>path - The absolute path to the smarty extensions.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/Common/Templating/SmartyTemplating.php#L116" target='_blank'>framework\Hirudo\Impl\Common\Templating\SmartyTemplating.php at line 116</a>

<h3 id="pick()">pick</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>pick</span> (mixed views)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/Common/Templating/SmartyTemplating.php#L126" target='_blank'>framework\Hirudo\Impl\Common\Templating\SmartyTemplating.php at line 126</a>

<h3 id="getFileExtension()">getFileExtension</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>getFileExtension</span> ()

<div class="details">

</div>

- - -

