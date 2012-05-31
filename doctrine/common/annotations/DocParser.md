- - -

**Doctrine\Common\Annotations\DocParser**
<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\DocParser.php at line 41</div>
#Class DocParser#

**DocParser**


- - -

<p class="signature">public final  class **DocParser**</p>

<div class="comment" id="overview_description"><p>A parser for docblock annotations.</p><p>It is strongly discouraged to change the default annotation parsing process.</p></div>

<dl>
<dt>Author:</dt>
<dd>Benjamin Eberlei <kontakt@beberlei.de></dd>
<dd>Guilherme Blanco <guilhermeblanco@hotmail.com></dd>
<dd>Jonathan Wage <jonwage@gmail.com></dd>
<dd>Roman Borschel <roman@code-factory.org></dd>
<dd>Johannes M. Schmitt <schmittjoh@gmail.com></dd>
<dd>Fabio B. Silva <fabio.bat.silva@gmail.com></dd>
</dl>
- - -

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>()</p><p class="description">Constructs a new DocParser.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setIgnoredAnnotationNames">setIgnoredAnnotationNames</a>(array names)</p><p class="description">Sets the annotation names that are ignored during the parsing process.
</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setIgnoreNotImportedAnnotations">setIgnoreNotImportedAnnotations</a>(mixed bool)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#addNamespace">addNamespace</a>(array namespaces, mixed namespace)</p><p class="description">Sets the default namespaces.</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setImports">setImports</a>(mixed imports)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setTarget">setTarget</a>(integer target)</p><p class="description">Sets current target context as bitmask.</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#parse">parse</a>(string input, string context)</p><p class="description">Parses the given docblock string for annotations.</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>
<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\DocParser.php at line 139</div>
<h3 id="__construct()">__construct</h3>
```php
public  void **__construct**()```
<div class="details">
<p>Constructs a new DocParser.</p></div>

- - -

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\DocParser.php at line 151</div>
<h3 id="setIgnoredAnnotationNames()">setIgnoredAnnotationNames</h3>
```php
public  void **setIgnoredAnnotationNames**(array names)```
<div class="details">
<p>Sets the annotation names that are ignored during the parsing process.</p><p>The names are supposed to be the raw names as used in the class, not the
fully qualified class names.</p></div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\DocParser.php at line 155</div>
<h3 id="setIgnoreNotImportedAnnotations()">setIgnoreNotImportedAnnotations</h3>
```php
public  void **setIgnoreNotImportedAnnotations**(mixed bool)```
<div class="details">
</div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\DocParser.php at line 163</div>
<h3 id="addNamespace()">addNamespace</h3>
```php
public  void **addNamespace**(array namespaces, mixed namespace)```
<div class="details">
<p>Sets the default namespaces.</p></div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\DocParser.php at line 170</div>
<h3 id="setImports()">setImports</h3>
```php
public  void **setImports**(mixed imports)```
<div class="details">
</div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\DocParser.php at line 182</div>
<h3 id="setTarget()">setTarget</h3>
```php
public  void **setTarget**(integer target)```
<div class="details">
<p>Sets current target context as bitmask.</p></div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\DocParser.php at line 193</div>
<h3 id="parse()">parse</h3>
```php
public  array **parse**(string input, string context)```
<div class="details">
<p>Parses the given docblock string for annotations.</p><dl>
<dt>Parameters:</dt>
<dd>input - The docblock string to parse.</dd>
<dd>context - The parsing context.</dd>
<dt>Returns:</dt>
<dd>Array of annotations. If no annotations are found, an empty array is returned.</dd>
</dl>
</div>

- - -

