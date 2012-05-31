- - -

**Doctrine\Common\Annotations\SimpleAnnotationReader**
<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\SimpleAnnotationReader.php at line 34</div>
#Class SimpleAnnotationReader#

**SimpleAnnotationReader**


<dl>
<dt>All Implemented Interfaces:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/annotations/reader.html">Reader</a> </dd>
</dl>

- - -

<p class="signature">public  class **SimpleAnnotationReader**</p>

<div class="comment" id="overview_description"><p>Simple Annotation Reader.</p><p>This annotation reader is intended to be used in projects where you have
full-control over all annotations that are available.</p></div>

<dl>
<dt>Since:</dt>
<dd>2.2</dd>
<dt>Author:</dt>
<dd>Johannes M. Schmitt <schmittjoh@gmail.com></dd>
<dd>Fabio B. Silva <fabio.bat.silva@gmail.com></dd>
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
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#addNamespace">addNamespace</a>(string namespace)</p><p class="description">Adds a namespace in which we will look for annotations.</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#getClassAnnotations">getClassAnnotations</a>(ReflectionClass class)</p><p class="description">Gets the annotations applied to a class.</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#getMethodAnnotations">getMethodAnnotations</a>(ReflectionMethod property, ReflectionMethod method)</p><p class="description">Gets the annotations applied to a method.</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#getPropertyAnnotations">getPropertyAnnotations</a>(ReflectionProperty property)</p><p class="description">Gets the annotations applied to a property.</p></td>
</tr>
<tr>
<td class="type"> The</td>
<td class="description"><p class="name"><a href="#getClassAnnotation">getClassAnnotation</a>(ReflectionClass class, string annotationName)</p><p class="description">Gets a class annotation.</p></td>
</tr>
<tr>
<td class="type"> The</td>
<td class="description"><p class="name"><a href="#getMethodAnnotation">getMethodAnnotation</a>(ReflectionMethod method, string annotationName)</p><p class="description">Gets a method annotation.</p></td>
</tr>
<tr>
<td class="type"> The</td>
<td class="description"><p class="name"><a href="#getPropertyAnnotation">getPropertyAnnotation</a>(ReflectionProperty property, string annotationName)</p><p class="description">Gets a property annotation.</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>
<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\SimpleAnnotationReader.php at line 46</div>
<h3 id="__construct()">__construct</h3>
```php
public  void **__construct**()```
<div class="details">
<p>Constructor.</p><p>Initializes a new SimpleAnnotationReader.</p></div>

- - -

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\SimpleAnnotationReader.php at line 57</div>
<h3 id="addNamespace()">addNamespace</h3>
```php
public  void **addNamespace**(string namespace)```
<div class="details">
<p>Adds a namespace in which we will look for annotations.</p></div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\SimpleAnnotationReader.php at line 69</div>
<h3 id="getClassAnnotations()">getClassAnnotations</h3>
```php
public  array **getClassAnnotations**(ReflectionClass class)```
<div class="details">
<p>Gets the annotations applied to a class.</p><dl>
<dt>Parameters:</dt>
<dd>class - The ReflectionClass of the class from which the class annotations should be read.</dd>
<dt>Returns:</dt>
<dd>An array of Annotations.</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\SimpleAnnotationReader.php at line 81</div>
<h3 id="getMethodAnnotations()">getMethodAnnotations</h3>
```php
public  array **getMethodAnnotations**(ReflectionMethod property, ReflectionMethod method)```
<div class="details">
<p>Gets the annotations applied to a method.</p><dl>
<dt>Parameters:</dt>
<dd>property - The ReflectionMethod of the method from which the annotations should be read.</dd>
<dt>Returns:</dt>
<dd>An array of Annotations.</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\SimpleAnnotationReader.php at line 93</div>
<h3 id="getPropertyAnnotations()">getPropertyAnnotations</h3>
```php
public  array **getPropertyAnnotations**(ReflectionProperty property)```
<div class="details">
<p>Gets the annotations applied to a property.</p><dl>
<dt>Parameters:</dt>
<dd>property - The ReflectionProperty of the property from which the annotations should be read.</dd>
<dt>Returns:</dt>
<dd>An array of Annotations.</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\SimpleAnnotationReader.php at line 106</div>
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

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\SimpleAnnotationReader.php at line 124</div>
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

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\SimpleAnnotationReader.php at line 142</div>
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

