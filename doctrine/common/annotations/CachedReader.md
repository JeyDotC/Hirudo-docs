- - -

**Doctrine\Common\Annotations\CachedReader**
<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\CachedReader.php at line 30</div>
#Class CachedReader#

**CachedReader**


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
<td class="description"><p class="name"><a href="#__construct">__construct</a>(<a href="../../../doctrine/common/annotations/reader.html">Reader</a> reader, <a href="../../../doctrine/common/cache/cache.html">Cache</a> cache, bool debug)</p><p class="description"></p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getClassAnnotations">getClassAnnotations</a>(ReflectionClass class)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getClassAnnotation">getClassAnnotation</a>(ReflectionClass class, mixed annotationName)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getPropertyAnnotations">getPropertyAnnotations</a>(ReflectionProperty property)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getPropertyAnnotation">getPropertyAnnotation</a>(ReflectionProperty property, mixed annotationName)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getMethodAnnotations">getMethodAnnotations</a>(ReflectionMethod method)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getMethodAnnotation">getMethodAnnotation</a>(ReflectionMethod method, mixed annotationName)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#clearLoadedAnnotations">clearLoadedAnnotations</a>()</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>
<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\CachedReader.php at line 58</div>
<h3 id="__construct()">__construct</h3>

```php
public  void **__construct**(<a href="../../../doctrine/common/annotations/reader.html">Reader</a> reader, <a href="../../../doctrine/common/cache/cache.html">Cache</a> cache, bool debug)
```
<div class="details">
<p></p></div>

- - -

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\CachedReader.php at line 65</div>
<h3 id="getClassAnnotations()">getClassAnnotations</h3>

```php
public  void **getClassAnnotations**(ReflectionClass class)
```
<div class="details">
</div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\CachedReader.php at line 81</div>
<h3 id="getClassAnnotation()">getClassAnnotation</h3>

```php
public  void **getClassAnnotation**(ReflectionClass class, mixed annotationName)
```
<div class="details">
</div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\CachedReader.php at line 92</div>
<h3 id="getPropertyAnnotations()">getPropertyAnnotations</h3>

```php
public  void **getPropertyAnnotations**(ReflectionProperty property)
```
<div class="details">
</div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\CachedReader.php at line 109</div>
<h3 id="getPropertyAnnotation()">getPropertyAnnotation</h3>

```php
public  void **getPropertyAnnotation**(ReflectionProperty property, mixed annotationName)
```
<div class="details">
</div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\CachedReader.php at line 120</div>
<h3 id="getMethodAnnotations()">getMethodAnnotations</h3>

```php
public  void **getMethodAnnotations**(ReflectionMethod method)
```
<div class="details">
</div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\CachedReader.php at line 137</div>
<h3 id="getMethodAnnotation()">getMethodAnnotation</h3>

```php
public  void **getMethodAnnotation**(ReflectionMethod method, mixed annotationName)
```
<div class="details">
</div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\CachedReader.php at line 148</div>
<h3 id="clearLoadedAnnotations()">clearLoadedAnnotations</h3>

```php
public  void **clearLoadedAnnotations**()
```
<div class="details">
</div>

- - -

