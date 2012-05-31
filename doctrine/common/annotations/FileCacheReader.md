- - -

**Doctrine\Common\Annotations\FileCacheReader**
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/doctrine-common/Doctrine/Common/Annotations/FileCacheReader.php.md#line29" class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\FileCacheReader.php at line 29</a>

# Class FileCacheReader #

<pre class="tree">** FileCacheReader **\n</pre>

- - -

<p class="signature">public  class **FileCacheReader**</p>

<div class="comment" id="overview_description"><p>File cache reader for annotations.</p></div>

<dl>
<dt>Author:</dt>
<dd>Johannes M. Schmitt <schmittjoh@gmail.com></dd>
<dd>Benjamin Eberlei <kontakt@beberlei.de></dd>
</dl>
- - -

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct()">__construct</a>(<a href="../../../doctrine/common/annotations/reader.html">Reader</a> reader, mixed cacheDir, bool debug)</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getClassAnnotations()">getClassAnnotations</a>(ReflectionClass class)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getPropertyAnnotations()">getPropertyAnnotations</a>(ReflectionProperty property)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getMethodAnnotations()">getMethodAnnotations</a>(ReflectionMethod method)</p></td>
</tr>
<tr>
<td class="type"> The</td>
<td class="description"><p class="name"><a href="#getClassAnnotation()">getClassAnnotation</a>(ReflectionClass class, string annotationName)</p><p class="description">Gets a class annotation.</p></td>
</tr>
<tr>
<td class="type"> The</td>
<td class="description"><p class="name"><a href="#getMethodAnnotation()">getMethodAnnotation</a>(ReflectionMethod method, string annotationName)</p><p class="description">Gets a method annotation.</p></td>
</tr>
<tr>
<td class="type"> The</td>
<td class="description"><p class="name"><a href="#getPropertyAnnotation()">getPropertyAnnotation</a>(ReflectionProperty property, string annotationName)</p><p class="description">Gets a property annotation.</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#clearLoadedAnnotations()">clearLoadedAnnotations</a>()</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/doctrine-common/Doctrine/Common/Annotations/FileCacheReader.php.md#line39" class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\FileCacheReader.php at line 39</a>

<h3 id="__construct()">__construct</h3>
```php
public  void **__construct**(<a href="../../../doctrine/common/annotations/reader.html">Reader</a> reader, mixed cacheDir, bool debug)```
<div class="details">
</div>

- - -

<h2 id="detail_method">Method Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/doctrine-common/Doctrine/Common/Annotations/FileCacheReader.php.md#line53" class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\FileCacheReader.php at line 53</a>

<h3 id="getClassAnnotations()">getClassAnnotations</h3>
```php
public  void **getClassAnnotations**(ReflectionClass class)```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/doctrine-common/Doctrine/Common/Annotations/FileCacheReader.php.md#line81" class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\FileCacheReader.php at line 81</a>

<h3 id="getPropertyAnnotations()">getPropertyAnnotations</h3>
```php
public  void **getPropertyAnnotations**(ReflectionProperty property)```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/doctrine-common/Doctrine/Common/Annotations/FileCacheReader.php.md#line110" class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\FileCacheReader.php at line 110</a>

<h3 id="getMethodAnnotations()">getMethodAnnotations</h3>
```php
public  void **getMethodAnnotations**(ReflectionMethod method)```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/doctrine-common/Doctrine/Common/Annotations/FileCacheReader.php.md#line152" class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\FileCacheReader.php at line 152</a>

<h3 id="getClassAnnotation()">getClassAnnotation</h3>
```php
public  The **getClassAnnotation**(ReflectionClass class, string annotationName)```
<div class="details">
<p>Gets a class annotation.</p><dl>
<dt>Parameters:</dt>
<dd>class - The ReflectionClass of the class from which the class annotations should be read.</dd>
<dd>annotationName - The name of the annotation.</dd>
<dt>Returns:</dt>
<dd>Annotation or NULL, if the requested annotation does not exist.</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/doctrine-common/Doctrine/Common/Annotations/FileCacheReader.php.md#line172" class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\FileCacheReader.php at line 172</a>

<h3 id="getMethodAnnotation()">getMethodAnnotation</h3>
```php
public  The **getMethodAnnotation**(ReflectionMethod method, string annotationName)```
<div class="details">
<p>Gets a method annotation.</p><dl>
<dt>Parameters:</dt>
<dd></dd>
<dd>annotationName - The name of the annotation.</dd>
<dt>Returns:</dt>
<dd>Annotation or NULL, if the requested annotation does not exist.</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/doctrine-common/Doctrine/Common/Annotations/FileCacheReader.php.md#line192" class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\FileCacheReader.php at line 192</a>

<h3 id="getPropertyAnnotation()">getPropertyAnnotation</h3>
```php
public  The **getPropertyAnnotation**(ReflectionProperty property, string annotationName)```
<div class="details">
<p>Gets a property annotation.</p><dl>
<dt>Parameters:</dt>
<dd></dd>
<dd>annotationName - The name of the annotation.</dd>
<dt>Returns:</dt>
<dd>Annotation or NULL, if the requested annotation does not exist.</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/doctrine-common/Doctrine/Common/Annotations/FileCacheReader.php.md#line205" class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\FileCacheReader.php at line 205</a>

<h3 id="clearLoadedAnnotations()">clearLoadedAnnotations</h3>
```php
public  void **clearLoadedAnnotations**()```
<div class="details">
</div>

- - -

