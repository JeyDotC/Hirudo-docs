- - -

**Hirudo\Core\HeaderBag**
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/Module.php.md#line35" class="location">framework\hirudo\Hirudo\Core\Module.php at line 35</a>

# Class HeaderBag #

<pre class="tree">** HeaderBag **\n</pre>

- - -

<p class="signature">public  class **HeaderBag**</p>

<div class="comment" id="overview_description"><p>A class that allows the edition of the response headers.</p></div>

- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setHeader()">setHeader</a>(string key, string|array value, boolean replace)</p><p class="description">Sets a header value.</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setHeaders()">setHeaders</a>(array headers)</p><p class="description">Adds the given headers list.</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setContentsForDownload()">setContentsForDownload</a>(string mime, string filename)</p><p class="description">An utility method that causes the resulting output to be downloaded
instead of being rendered in browser.</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/Module.php.md#line44" class="location">framework\hirudo\Hirudo\Core\Module.php at line 44</a>

<h3 id="setHeader()">setHeader</h3>
```php
public  void **setHeader**(string key, string|array value, boolean replace)```
<div class="details">
<p>Sets a header value.</p><dl>
<dt>Parameters:</dt>
<dd>key - The header key.</dd>
<dd>value - The header value. If the value is an array, all of its elements are added under the same key given as the first parameter.</dd>
<dd>replace - Tells if the new value shall replace the existing one.</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/Module.php.md#line71" class="location">framework\hirudo\Hirudo\Core\Module.php at line 71</a>

<h3 id="setHeaders()">setHeaders</h3>
```php
public  void **setHeaders**(array headers)```
<div class="details">
<p><p>Adds the given headers list.</p></p><p><p>The array can have any conbination of these elements styles.</p></p><p><div>
<code>
array(
"Header-Key" => "Header-Value", //Key/Value pairs
"Header-Key: Header-Value", //Single values with all header information in a single string
"Header-Key" => array("Value1", "Value2", "...ValueN"), //A list of header values under a single key.
)
</code>
</div></p><dl>
<dt>Parameters:</dt>
<dd>headers - List of headers.</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/Module.php.md#line88" class="location">framework\hirudo\Hirudo\Core\Module.php at line 88</a>

<h3 id="setContentsForDownload()">setContentsForDownload</h3>
```php
public  void **setContentsForDownload**(string mime, string filename)```
<div class="details">
<p><p>An utility method that causes the resulting output to be downloaded
instead of being rendered in browser.</p></p><dl>
<dt>Parameters:</dt>
<dd>mime - The mime type of the file to be downloaded.</dd>
<dd>filename - A file name for the file to be downloaded.</dd>
</dl>
</div>

- - -

