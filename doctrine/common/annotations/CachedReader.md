- - -

**Doctrine\Common\Annotations\CachedReader**
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/doctrine-common/Doctrine/Common/Annotations/CachedReader.php.md#line30" class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\CachedReader.php at line 30</a>

# Class CachedReader #

<pre class="tree">** CachedReader **\n</pre>

- - -

<p class="signature">public final  class **CachedReader**</p>

<div class="comment" id="overview_description"><p>A cache aware annotation reader.</p></div>

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
<td class="description"><p class="name"><a href="#__construct()">__construct</a>(<a href="../../../doctrine/common/annotations/reader.html">Reader</a> reader, <a href="../../../doctrine/common/cache/cache.html">Cache</a> cache, bool debug)</p><p class="description"></p></td>
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
<td class="description"><p class="name"><a href="#getClassAnnotation()">getClassAnnotation</a>(ReflectionClass class, mixed annotationName)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getPropertyAnnotations()">getPropertyAnnotations</a>(ReflectionProperty property)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getPropertyAnnotation()">getPropertyAnnotation</a>(ReflectionProperty property, mixed annotationName)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getMethodAnnotations()">getMethodAnnotations</a>(ReflectionMethod method)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getMethodAnnotation()">getMethodAnnotation</a>(ReflectionMethod method, mixed annotationName)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#clearLoadedAnnotations()">clearLoadedAnnotations</a>()</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/doctrine-common/Doctrine/Common/Annotations/CachedReader.php.md#line58" class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\CachedReader.php at line 58</a>

<h3 id="__construct()">__construct</h3>
```php
public  void **__construct**(<a href="../../../doctrine/common/annotations/reader.html">Reader</a> reader, <a href="../../../doctrine/common/cache/cache.html">Cache</a> cache, bool debug)```
<div class="details">
<p></p></div>

- - -

<h2 id="detail_method">Method Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/doctrine-common/Doctrine/Common/Annotations/CachedReader.php.md#line65" class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\CachedReader.php at line 65</a>

<h3 id="getClassAnnotations()">getClassAnnotations</h3>
```php
public  void **getClassAnnotations**(ReflectionClass class)```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/doctrine-common/Doctrine/Common/Annotations/CachedReader.php.md#line81" class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\CachedReader.php at line 81</a>

<h3 id="getClassAnnotation()">getClassAnnotation</h3>
```php
public  void **getClassAnnotation**(ReflectionClass class, mixed annotationName)```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/doctrine-common/Doctrine/Common/Annotations/CachedReader.php.md#line92" class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\CachedReader.php at line 92</a>

<h3 id="getPropertyAnnotations()">getPropertyAnnotations</h3>
```php
public  void **getPropertyAnnotations**(ReflectionProperty property)```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/doctrine-common/Doctrine/Common/Annotations/CachedReader.php.md#line109" class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\CachedReader.php at line 109</a>

<h3 id="getPropertyAnnotation()">getPropertyAnnotation</h3>
```php
public  void **getPropertyAnnotation**(ReflectionProperty property, mixed annotationName)```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/doctrine-common/Doctrine/Common/Annotations/CachedReader.php.md#line120" class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\CachedReader.php at line 120</a>

<h3 id="getMethodAnnotations()">getMethodAnnotations</h3>
```php
public  void **getMethodAnnotations**(ReflectionMethod method)```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/doctrine-common/Doctrine/Common/Annotations/CachedReader.php.md#line137" class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\CachedReader.php at line 137</a>

<h3 id="getMethodAnnotation()">getMethodAnnotation</h3>
```php
public  void **getMethodAnnotation**(ReflectionMethod method, mixed annotationName)```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/doctrine-common/Doctrine/Common/Annotations/CachedReader.php.md#line148" class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\CachedReader.php at line 148</a>

<h3 id="clearLoadedAnnotations()">clearLoadedAnnotations</h3>
```php
public  void **clearLoadedAnnotations**()```
<div class="details">
</div>

- - -

