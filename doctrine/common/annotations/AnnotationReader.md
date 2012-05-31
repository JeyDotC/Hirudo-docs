- - -

**Doctrine\Common\Annotations\AnnotationReader**
<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\AnnotationReader.php at line 39</div>
#Class AnnotationReader#

**AnnotationReader**


- - -

<p class="signature">public final  class **AnnotationReader**</p>

<div class="comment" id="overview_description"><p>A reader for docblock annotations.</p></div>

<dl>
<dt>Author:</dt>
<dd>Benjamin Eberlei <kontakt@beberlei.de></dd>
<dd>Guilherme Blanco <guilhermeblanco@hotmail.com></dd>
<dd>Jonathan Wage <jonwage@gmail.com></dd>
<dd>Roman Borschel <roman@code-factory.org></dd>
<dd>Johannes M. Schmitt <schmittjoh@gmail.com></dd>
</dl>
- - -

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>()</p><p class="description">Constructor.
</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type">static  void</td>
<td class="description"><p class="name"><a href="#addGlobalIgnoredName">addGlobalIgnoredName</a>(string name)</p><p class="description">Add a new annotation to the globally ignored annotation names with regard to exception handling.</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#getClassAnnotations">getClassAnnotations</a>(ReflectionClass class)</p><p class="description">Gets the annotations applied to a class.</p></td>
</tr>
<tr>
<td class="type"> The</td>
<td class="description"><p class="name"><a href="#getClassAnnotation">getClassAnnotation</a>(ReflectionClass class, string annotationName)</p><p class="description">Gets a class annotation.</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#getPropertyAnnotations">getPropertyAnnotations</a>(ReflectionProperty property)</p><p class="description">Gets the annotations applied to a property.</p></td>
</tr>
<tr>
<td class="type"> The</td>
<td class="description"><p class="name"><a href="#getPropertyAnnotation">getPropertyAnnotation</a>(ReflectionProperty property, string annotationName)</p><p class="description">Gets a property annotation.</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#getMethodAnnotations">getMethodAnnotations</a>(ReflectionMethod property, ReflectionMethod method)</p><p class="description">Gets the annotations applied to a method.</p></td>
</tr>
<tr>
<td class="type"> The</td>
<td class="description"><p class="name"><a href="#getMethodAnnotation">getMethodAnnotation</a>(ReflectionMethod method, string annotationName)</p><p class="description">Gets a method annotation.</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>
<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\AnnotationReader.php at line 106</div>
<h3 id="__construct()">__construct</h3>

```php
public  void **__construct**()
```
<div class="details">
<p>Constructor.</p><p>Initializes a new AnnotationReader.</p></div>

- - -

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\AnnotationReader.php at line 62</div>
<h3 id="addGlobalIgnoredName()">addGlobalIgnoredName</h3>

```php
public static  void **addGlobalIgnoredName**(string name)
```
<div class="details">
<p>Add a new annotation to the globally ignored annotation names with regard to exception handling.</p></div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\AnnotationReader.php at line 125</div>
<h3 id="getClassAnnotations()">getClassAnnotations</h3>

```php
public  array **getClassAnnotations**(ReflectionClass class)
```
<div class="details">
<p>Gets the annotations applied to a class.</p><dl>
<dt>Parameters:</dt>
<dd>class - The ReflectionClass of the class from which the class annotations should be read.</dd>
<dt>Returns:</dt>
<dd>An array of Annotations.</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\AnnotationReader.php at line 141</div>
<h3 id="getClassAnnotation()">getClassAnnotation</h3>

```php
public  The **getClassAnnotation**(ReflectionClass class, string annotationName)
```
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

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\AnnotationReader.php at line 160</div>
<h3 id="getPropertyAnnotations()">getPropertyAnnotations</h3>

```php
public  array **getPropertyAnnotations**(ReflectionProperty property)
```
<div class="details">
<p>Gets the annotations applied to a property.</p><dl>
<dt>Parameters:</dt>
<dd>property - The ReflectionProperty of the property from which the annotations should be read.</dd>
<dt>Returns:</dt>
<dd>An array of Annotations.</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\AnnotationReader.php at line 177</div>
<h3 id="getPropertyAnnotation()">getPropertyAnnotation</h3>

```php
public  The **getPropertyAnnotation**(ReflectionProperty property, string annotationName)
```
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

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\AnnotationReader.php at line 196</div>
<h3 id="getMethodAnnotations()">getMethodAnnotations</h3>

```php
public  array **getMethodAnnotations**(ReflectionMethod property, ReflectionMethod method)
```
<div class="details">
<p>Gets the annotations applied to a method.</p><dl>
<dt>Parameters:</dt>
<dd>property - The ReflectionMethod of the method from which the annotations should be read.</dd>
<dt>Returns:</dt>
<dd>An array of Annotations.</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\AnnotationReader.php at line 213</div>
<h3 id="getMethodAnnotation()">getMethodAnnotation</h3>

```php
public  The **getMethodAnnotation**(ReflectionMethod method, string annotationName)
```
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

