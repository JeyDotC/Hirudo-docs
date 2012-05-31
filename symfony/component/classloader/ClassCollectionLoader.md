- - -

**Symfony\Component\ClassLoader\ClassCollectionLoader**
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/ClassLoader/ClassCollectionLoader.php.md#line19" class="location">framework\libs\symfony-components\Symfony\Component\ClassLoader\ClassCollectionLoader.php at line 19</a>

# Class ClassCollectionLoader #

<pre class="tree">** ClassCollectionLoader **\n</pre>

- - -

<p class="signature">public  class **ClassCollectionLoader**</p>

<div class="comment" id="overview_description"><p>ClassCollectionLoader.</p></div>

<dl>
<dt>Author:</dt>
<dd>Fabien Potencier <fabien@symfony.com></dd>
</dl>
- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type">static  void</td>
<td class="description"><p class="name"><a href="#load()">load</a>(array classes, string cacheDir, string name, Boolean autoReload, Boolean adaptive, string extension)</p><p class="description">Loads a list of classes and caches them in one big file.</p></td>
</tr>
<tr>
<td class="type">static  string</td>
<td class="description"><p class="name"><a href="#fixNamespaceDeclarations()">fixNamespaceDeclarations</a>(string source)</p><p class="description">Adds brackets around each namespace if it's not already the case.</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/ClassLoader/ClassCollectionLoader.php.md#line35" class="location">framework\libs\symfony-components\Symfony\Component\ClassLoader\ClassCollectionLoader.php at line 35</a>

<h3 id="load()">load</h3>
```php
public static  void **load**(array classes, string cacheDir, string name, Boolean autoReload, Boolean adaptive, string extension)```
<div class="details">
<p>Loads a list of classes and caches them in one big file.</p><dl>
<dt>Parameters:</dt>
<dd>classes - An array of classes to load</dd>
<dd>cacheDir - A cache directory</dd>
<dd>name - The cache name prefix</dd>
<dd>autoReload - Whether to flush the cache when the cache is stale or not</dd>
<dd>adaptive - Whether to remove already declared classes or not</dd>
<dd>extension - File extension of the resulting file</dd>
<dt>Throws:</dt>
<dd><a href="../../../symfony/component/dependencyinjection/exception/invalidargumentexception.html">\InvalidArgumentException</a> - When class can't be loaded</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/ClassLoader/ClassCollectionLoader.php.md#line126" class="location">framework\libs\symfony-components\Symfony\Component\ClassLoader\ClassCollectionLoader.php at line 126</a>

<h3 id="fixNamespaceDeclarations()">fixNamespaceDeclarations</h3>
```php
public static  string **fixNamespaceDeclarations**(string source)```
<div class="details">
<p>Adds brackets around each namespace if it's not already the case.</p><dl>
<dt>Parameters:</dt>
<dd>source - Namespace string</dd>
<dt>Returns:</dt>
<dd>Namespaces with brackets</dd>
</dl>
</div>

- - -

