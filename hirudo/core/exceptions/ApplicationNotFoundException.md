- - -

**Hirudo\Core\Exceptions\ApplicationNotFoundException**
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/Exceptions/ApplicationNotFoundException.php.md#line29" class="location">framework\hirudo\Hirudo\Core\Exceptions\ApplicationNotFoundException.php at line 29</a>

# Class ApplicationNotFoundException #

<pre class="tree">\Exception\n*<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/exceptions/hirudoexception.html">HirudoException</a>\n        *** ApplicationNotFoundException **\n</pre>

- - -

<p class="signature">public  class **ApplicationNotFoundException**\nextends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/exceptions/hirudoexception.html">HirudoException</a>

</p>

<div class="comment" id="overview_description"><p>Thrown when there is an attempt to call a non existent application</p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
</dl>
- - -

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct()">__construct</a>(string app, string path)</p><p class="description">Creates an ApplicationNotFoundException.</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Hirudo\Core\Exceptions\HirudoException</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/exceptions/hirudoexception.html#__construct()">__construct</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/exceptions/hirudoexception.html#getApp()">getApp</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/exceptions/hirudoexception.html#getModule()">getModule</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/exceptions/hirudoexception.html#getTask()">getTask</a></td></tr></table>

<h2 id="detail_method">Constructor Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/Exceptions/ApplicationNotFoundException.php.md#line37" class="location">framework\hirudo\Hirudo\Core\Exceptions\ApplicationNotFoundException.php at line 37</a>

<h3 id="__construct()">__construct</h3>
```php
public  void **__construct**(string app, string path)```
<div class="details">
<p>Creates an ApplicationNotFoundException.</p><dl>
<dt>Parameters:</dt>
<dd>app - The application name.</dd>
<dd>path - The directory in which the application should be.</dd>
</dl>
</div>

- - -

