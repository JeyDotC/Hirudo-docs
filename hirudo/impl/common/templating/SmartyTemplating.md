- - -

**Hirudo\Impl\Common\Templating\SmartyTemplating**
<div class="location">framework\hirudo\Hirudo\Impl\Common\Templating\SmartyTemplating.php at line 35</div>
#Class SmartyTemplating#

**SmartyTemplating**


<dl>
<dt>All Implemented Interfaces:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/templatinginterface.html">Hirudo\Core\TemplatingInterface</a> </dd>
</dl>

- - -

<p class="signature">public  class **SmartyTemplating**</p>

<div class="comment" id="overview_description"><p>A Smarty based templating system.</p></div>

<dl>
<dt>Hirudo\Core\Annotations\Export(id="templating",:</dt>
<dd>factory="instance")</dd>
</dl>
- - -

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>()</p><p class="description">Creates a new instance of smarty templating.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> mixed</td>
<td class="description"><p class="name"><a href="#assign">assign</a>(string name, mixed value)</p><p class="description">Adds a variable to the view so it can be accessed from the smarty template.</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#display">display</a>(string moduleDir, string view)</p><p class="description">Renders the view and retuns it as a string.</p></td>
</tr>
<tr>
<td class="type">static  <a href="../../../../hirudo/impl/common/templating/smartytemplating.html">SmartyTemplating</a></td>
<td class="description"><p class="name"><a href="#instance">instance</a>()</p><p class="description"></p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#addExtensionsPath">addExtensionsPath</a>(string path)</p><p class="description">Adds a path to smarty extensions so these can be used in the templates.</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>
<div class="location">framework\hirudo\Hirudo\Impl\Common\Templating\SmartyTemplating.php at line 46</div>
<h3 id="__construct()">__construct</h3>
```php
public  void **__construct**()```
<div class="details">
<p>Creates a new instance of smarty templating.</p></div>

- - -

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\hirudo\Hirudo\Impl\Common\Templating\SmartyTemplating.php at line 61</div>
<h3 id="assign()">assign</h3>
```php
public  mixed **assign**(string name, mixed value)```
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

<div class="location">framework\hirudo\Hirudo\Impl\Common\Templating\SmartyTemplating.php at line 74</div>
<h3 id="display()">display</h3>
```php
public  string **display**(string moduleDir, string view)```
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

<div class="location">framework\hirudo\Hirudo\Impl\Common\Templating\SmartyTemplating.php at line 88</div>
<h3 id="instance()">instance</h3>
```php
public static  <a href="../../../../hirudo/impl/common/templating/smartytemplating.html">SmartyTemplating</a> **instance**()```
<div class="details">
<p></p></div>

- - -

<div class="location">framework\hirudo\Hirudo\Impl\Common\Templating\SmartyTemplating.php at line 101</div>
<h3 id="addExtensionsPath()">addExtensionsPath</h3>
```php
public  void **addExtensionsPath**(string path)```
<div class="details">
<p>Adds a path to smarty extensions so these can be used in the templates.</p><dl>
<dt>Parameters:</dt>
<dd>path - The absolute path to the smarty extensions.</dd>
</dl>
</div>

- - -

