- - -

**Symfony\Component\DependencyInjection\Loader\XmlFileLoader**
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Loader\XmlFileLoader.php at line 29</div>
#Class XmlFileLoader#

BaseFileLoader
*<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/loader/fileloader.html">FileLoader</a>
        ***XmlFileLoader**


- - -

<p class="signature">public  class **XmlFileLoader**
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/loader/fileloader.html">FileLoader</a>

</p>

<div class="comment" id="overview_description"><p>XmlFileLoader loads XML files service definitions.</p></div>

<dl>
<dt>Author:</dt>
<dd>Fabien Potencier <fabien@symfony.com></dd>
</dl>
- - -

<table class="inherit">
<tr><th colspan="2">Fields inherited from Symfony\Component\DependencyInjection\Loader\FileLoader</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/loader/fileloader.html#container">container</a></td></tr></table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#load">load</a>(mixed file, string type)</p><p class="description">Loads an XML file.</p></td>
</tr>
<tr>
<td class="type"> Boolean</td>
<td class="description"><p class="name"><a href="#supports">supports</a>(mixed resource, string type)</p><p class="description">Returns true if this class supports the given resource.</p></td>
</tr>
<tr>
<td class="type">static  array</td>
<td class="description"><p class="name"><a href="#convertDomElementToArray">convertDomElementToArray</a>(\DomElement element)</p><p class="description">Converts a \DomElement object to a PHP array.
</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Symfony\Component\DependencyInjection\Loader\FileLoader</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/loader/fileloader.html#__construct()">__construct</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Loader\XmlFileLoader.php at line 37</div>
<h3 id="load()">load</h3>

```php
public  void **load**(mixed file, string type)
```
<div class="details">
<p>Loads an XML file.</p><dl>
<dt>Parameters:</dt>
<dd>file - The resource</dd>
<dd>type - The resource type</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Loader\XmlFileLoader.php at line 70</div>
<h3 id="supports()">supports</h3>

```php
public  Boolean **supports**(mixed resource, string type)
```
<div class="details">
<p>Returns true if this class supports the given resource.</p><dl>
<dt>Parameters:</dt>
<dd>resource - A resource</dd>
<dd>type - The resource type</dd>
<dt>Returns:</dt>
<dd>true if this class supports the given resource, false otherwise</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Loader\XmlFileLoader.php at line 462</div>
<h3 id="convertDomElementToArray()">convertDomElementToArray</h3>

```php
public static  array **convertDomElementToArray**(\DomElement element)
```
<div class="details">
<p>Converts a \DomElement object to a PHP array.</p><p>The following rules applies during the conversion:</p><p>* Each tag is converted to a key value or an array
if there is more than one "value"</p><p>* The content of a tag is set under a "value" key (<foo>bar</foo>)
if the tag also has some nested tags</p><p>* The attributes are converted to keys (<foo foo="bar"/>)</p><p>* The nested-tags are converted to keys (<foo><foo>bar</foo></foo>)</p><dl>
<dt>Parameters:</dt>
<dd>element - A \DomElement instance</dd>
<dt>Returns:</dt>
<dd>A PHP array</dd>
</dl>
</div>

- - -

