
- - -

**Doctrine\Common\Annotations\AnnotationReader**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\libs\doctrine-common\Doctrine\Common\Annotations\AnnotationReader.php at line 39#L39 class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\AnnotationReader.php at line 39</a>

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
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>()</p><p class="description">Constructor.
</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#addglobalignoredname">addGlobalIgnoredName</a>(string name)</p><p class="description">Add a new annotation to the globally ignored annotation names with regard to exception handling.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name"><a href="#getclassannotations">getClassAnnotations</a>(ReflectionClass class)</p><p class="description">Gets the annotations applied to a class.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>The</span></td>
<td class="description"><p class="name"><a href="#getclassannotation">getClassAnnotation</a>(ReflectionClass class, string annotationName)</p><p class="description">Gets a class annotation.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name"><a href="#getpropertyannotations">getPropertyAnnotations</a>(ReflectionProperty property)</p><p class="description">Gets the annotations applied to a property.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>The</span></td>
<td class="description"><p class="name"><a href="#getpropertyannotation">getPropertyAnnotation</a>(ReflectionProperty property, string annotationName)</p><p class="description">Gets a property annotation.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name"><a href="#getmethodannotations">getMethodAnnotations</a>(ReflectionMethod property, ReflectionMethod method)</p><p class="description">Gets the annotations applied to a method.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>The</span></td>
<td class="description"><p class="name"><a href="#getmethodannotation">getMethodAnnotation</a>(ReflectionMethod method, string annotationName)</p><p class="description">Gets a method annotation.</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\libs\doctrine-common\Doctrine\Common\Annotations\AnnotationReader.php at line 106#L106 class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\AnnotationReader.php at line 106</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> ()

<div class="details">
<p>Constructor.</p><p>Initializes a new AnnotationReader.</p></div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\libs\doctrine-common\Doctrine\Common\Annotations\AnnotationReader.php at line 62#L62 class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\AnnotationReader.php at line 62</a>

<h3 id="addGlobalIgnoredName()">addGlobalIgnoredName</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>addGlobalIgnoredName</span> (string name)

<div class="details">
<p>Add a new annotation to the globally ignored annotation names with regard to exception handling.</p></div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\libs\doctrine-common\Doctrine\Common\Annotations\AnnotationReader.php at line 125#L125 class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\AnnotationReader.php at line 125</a>

<h3 id="getClassAnnotations()">getClassAnnotations</h3>
<span class='k'></span> <span class='nx'>array</span> <span class='nf'>getClassAnnotations</span> (ReflectionClass class)

<div class="details">
<p>Gets the annotations applied to a class.</p><dl>
<dt>Parameters:</dt>
<dd>class - The ReflectionClass of the class from which the class annotations should be read.</dd>
<dt>Returns:</dt>
<dd>An array of Annotations.</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\libs\doctrine-common\Doctrine\Common\Annotations\AnnotationReader.php at line 141#L141 class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\AnnotationReader.php at line 141</a>

<h3 id="getClassAnnotation()">getClassAnnotation</h3>
<span class='k'></span> <span class='nx'>The</span> <span class='nf'>getClassAnnotation</span> (ReflectionClass class, string annotationName)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\libs\doctrine-common\Doctrine\Common\Annotations\AnnotationReader.php at line 160#L160 class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\AnnotationReader.php at line 160</a>

<h3 id="getPropertyAnnotations()">getPropertyAnnotations</h3>
<span class='k'></span> <span class='nx'>array</span> <span class='nf'>getPropertyAnnotations</span> (ReflectionProperty property)

<div class="details">
<p>Gets the annotations applied to a property.</p><dl>
<dt>Parameters:</dt>
<dd>property - The ReflectionProperty of the property from which the annotations should be read.</dd>
<dt>Returns:</dt>
<dd>An array of Annotations.</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\libs\doctrine-common\Doctrine\Common\Annotations\AnnotationReader.php at line 177#L177 class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\AnnotationReader.php at line 177</a>

<h3 id="getPropertyAnnotation()">getPropertyAnnotation</h3>
<span class='k'></span> <span class='nx'>The</span> <span class='nf'>getPropertyAnnotation</span> (ReflectionProperty property, string annotationName)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\libs\doctrine-common\Doctrine\Common\Annotations\AnnotationReader.php at line 196#L196 class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\AnnotationReader.php at line 196</a>

<h3 id="getMethodAnnotations()">getMethodAnnotations</h3>
<span class='k'></span> <span class='nx'>array</span> <span class='nf'>getMethodAnnotations</span> (ReflectionMethod property, ReflectionMethod method)

<div class="details">
<p>Gets the annotations applied to a method.</p><dl>
<dt>Parameters:</dt>
<dd>property - The ReflectionMethod of the method from which the annotations should be read.</dd>
<dt>Returns:</dt>
<dd>An array of Annotations.</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\libs\doctrine-common\Doctrine\Common\Annotations\AnnotationReader.php at line 213#L213 class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\AnnotationReader.php at line 213</a>

<h3 id="getMethodAnnotation()">getMethodAnnotation</h3>
<span class='k'></span> <span class='nx'>The</span> <span class='nf'>getMethodAnnotation</span> (ReflectionMethod method, string annotationName)

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

