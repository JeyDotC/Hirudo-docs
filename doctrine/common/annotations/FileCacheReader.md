
- - -

**Doctrine\Common\Annotations\FileCacheReader**
<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\FileCacheReader.php at line 29</div>
#Class FileCacheReader#

**FileCacheReader**


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
<td class="description"><p class="name"><a href="#__construct">__construct</a>(<a href="../../../doctrine/common/annotations/reader.html">Reader</a> reader, mixed cacheDir, bool debug)</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#getclassannotations">getClassAnnotations</a>(ReflectionClass class)</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#getpropertyannotations">getPropertyAnnotations</a>(ReflectionProperty property)</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#getmethodannotations">getMethodAnnotations</a>(ReflectionMethod method)</p></td>
</tr>
<tr>
<td class="type">  The</td>
<td class="description"><p class="name"><a href="#getclassannotation">getClassAnnotation</a>(ReflectionClass class, string annotationName)</p><p class="description">Gets a class annotation.</p></td>
</tr>
<tr>
<td class="type">  The</td>
<td class="description"><p class="name"><a href="#getmethodannotation">getMethodAnnotation</a>(ReflectionMethod method, string annotationName)</p><p class="description">Gets a method annotation.</p></td>
</tr>
<tr>
<td class="type">  The</td>
<td class="description"><p class="name"><a href="#getpropertyannotation">getPropertyAnnotation</a>(ReflectionProperty property, string annotationName)</p><p class="description">Gets a property annotation.</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#clearloadedannotations">clearLoadedAnnotations</a>()</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>
<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\FileCacheReader.php at line 39</div>
<h3 id="__construct()">__construct</h3>

```php
public  void **__construct**(<a href="../../../doctrine/common/annotations/reader.html">Reader</a> reader, mixed cacheDir, bool debug)
```
<div class="details">
</div>

- - -

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\FileCacheReader.php at line 53</div>
<h3 id="getClassAnnotations()">getClassAnnotations</h3>

public  void **getClassAnnotations** (ReflectionClass class)<div class="details">
</div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\FileCacheReader.php at line 81</div>
<h3 id="getPropertyAnnotations()">getPropertyAnnotations</h3>

public  void **getPropertyAnnotations** (ReflectionProperty property)<div class="details">
</div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\FileCacheReader.php at line 110</div>
<h3 id="getMethodAnnotations()">getMethodAnnotations</h3>

public  void **getMethodAnnotations** (ReflectionMethod method)<div class="details">
</div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\FileCacheReader.php at line 152</div>
<h3 id="getClassAnnotation()">getClassAnnotation</h3>

public  The **getClassAnnotation** (ReflectionClass class, string annotationName)<div class="details">
<p>Gets a class annotation.</p><dl>
<dt>Parameters:</dt>
<dd>class - The ReflectionClass of the class from which the class annotations should be read.</dd>
<dd>annotationName - The name of the annotation.</dd>
<dt>Returns:</dt>
<dd>Annotation or NULL, if the requested annotation does not exist.</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\FileCacheReader.php at line 172</div>
<h3 id="getMethodAnnotation()">getMethodAnnotation</h3>

public  The **getMethodAnnotation** (ReflectionMethod method, string annotationName)<div class="details">
<p>Gets a method annotation.</p><dl>
<dt>Parameters:</dt>
<dd></dd>
<dd>annotationName - The name of the annotation.</dd>
<dt>Returns:</dt>
<dd>Annotation or NULL, if the requested annotation does not exist.</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\FileCacheReader.php at line 192</div>
<h3 id="getPropertyAnnotation()">getPropertyAnnotation</h3>

public  The **getPropertyAnnotation** (ReflectionProperty property, string annotationName)<div class="details">
<p>Gets a property annotation.</p><dl>
<dt>Parameters:</dt>
<dd></dd>
<dd>annotationName - The name of the annotation.</dd>
<dt>Returns:</dt>
<dd>Annotation or NULL, if the requested annotation does not exist.</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\FileCacheReader.php at line 205</div>
<h3 id="clearLoadedAnnotations()">clearLoadedAnnotations</h3>

public  void **clearLoadedAnnotations** ()<div class="details">
</div>

- - -

