

- - -

**Hirudo\Impl\Common\Templating\SmartyTemplating**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/Common/Templating/SmartyTemplating.php#L35" >framework\hirudo\Hirudo\Impl\Common\Templating\SmartyTemplating.php at line 35</a>

#Class SmartyTemplating#

**SmartyTemplating**


<dl>
<dt>All Implemented Interfaces:</dt>
<dd><a href="">Hirudo\Core\TemplatingInterface</a> </dd>
</dl>



- - -

<p class="signature"><span class='k'>public  class</span> <span class='nx'>SmartyTemplating</span></p>

<div class="comment" id="overview_description"><p>A Smarty based templating system.</p></div>

<dl>
<dt>Hirudo\Core\Annotations\Export(id="templating",:</dt>
<dd>factory="instance")</dd>
</dl>


- - -

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
<td><span class='k'>static </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/impl/common/templating/SmartyTemplating>SmartyTemplating</a></span></td>
<td class="description"><p class="name"><a href="#instance">instance</a>()</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#addextensionspath">addExtensionsPath</a>(string path)</p><p class="description">Adds a path to smarty extensions so these can be used in the templates.</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/Common/Templating/SmartyTemplating.php#L46" >framework\hirudo\Hirudo\Impl\Common\Templating\SmartyTemplating.php at line 46</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> ()

<div class="details">
<p>Creates a new instance of smarty templating.</p>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/Common/Templating/SmartyTemplating.php#L61" >framework\hirudo\Hirudo\Impl\Common\Templating\SmartyTemplating.php at line 61</a>

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/Common/Templating/SmartyTemplating.php#L74" >framework\hirudo\Hirudo\Impl\Common\Templating\SmartyTemplating.php at line 74</a>

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/Common/Templating/SmartyTemplating.php#L88" >framework\hirudo\Hirudo\Impl\Common\Templating\SmartyTemplating.php at line 88</a>

<h3 id="instance()">instance</h3>
<span class='k'>static </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/impl/common/templating/SmartyTemplating>SmartyTemplating</a></span> <span class='nf'>instance</span> ()

<div class="details">
<p></p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/Common/Templating/SmartyTemplating.php#L101" >framework\hirudo\Hirudo\Impl\Common\Templating\SmartyTemplating.php at line 101</a>

<h3 id="addExtensionsPath()">addExtensionsPath</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>addExtensionsPath</span> (string path)

<div class="details">
<p>Adds a path to smarty extensions so these can be used in the templates.</p><dl>
<dt>Parameters:</dt>
<dd>path - The absolute path to the smarty extensions.</dd>
</dl>

</div>

- - -

