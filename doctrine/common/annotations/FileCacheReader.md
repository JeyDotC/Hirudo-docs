

- - -

**Doctrine\Common\Annotations\FileCacheReader**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Annotations/FileCacheReader.php#L29" target='_blank'>framework\libs\doctrine-common\Doctrine\Common\Annotations\FileCacheReader.php at line 29</a>

#Class FileCacheReader#

**FileCacheReader**




- - -

<p><strong>public  class</strong> <span>FileCacheReader</span></p>

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
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/doctrine/common/annotations/Reader.md">Reader</a> reader, mixed cacheDir, bool debug)</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#getclassannotations">getClassAnnotations</a>(ReflectionClass class)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#getpropertyannotations">getPropertyAnnotations</a>(ReflectionProperty property)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#getmethodannotations">getMethodAnnotations</a>(ReflectionMethod method)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>The</span></td>
<td class="description"><p class="name"><a href="#getclassannotation">getClassAnnotation</a>(ReflectionClass class, string annotationName)</p><p class="description">Gets a class annotation.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>The</span></td>
<td class="description"><p class="name"><a href="#getmethodannotation">getMethodAnnotation</a>(ReflectionMethod method, string annotationName)</p><p class="description">Gets a method annotation.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>The</span></td>
<td class="description"><p class="name"><a href="#getpropertyannotation">getPropertyAnnotation</a>(ReflectionProperty property, string annotationName)</p><p class="description">Gets a property annotation.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#clearloadedannotations">clearLoadedAnnotations</a>()</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Annotations/FileCacheReader.php#L39" target='_blank'>framework\libs\doctrine-common\Doctrine\Common\Annotations\FileCacheReader.php at line 39</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/doctrine/common/annotations/Reader.md">Reader</a> reader, mixed cacheDir, bool debug)

<div class="details">

</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Annotations/FileCacheReader.php#L53" target='_blank'>framework\libs\doctrine-common\Doctrine\Common\Annotations\FileCacheReader.php at line 53</a>

<h3 id="getClassAnnotations()">getClassAnnotations</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>getClassAnnotations</span> (ReflectionClass class)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Annotations/FileCacheReader.php#L81" target='_blank'>framework\libs\doctrine-common\Doctrine\Common\Annotations\FileCacheReader.php at line 81</a>

<h3 id="getPropertyAnnotations()">getPropertyAnnotations</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>getPropertyAnnotations</span> (ReflectionProperty property)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Annotations/FileCacheReader.php#L110" target='_blank'>framework\libs\doctrine-common\Doctrine\Common\Annotations\FileCacheReader.php at line 110</a>

<h3 id="getMethodAnnotations()">getMethodAnnotations</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>getMethodAnnotations</span> (ReflectionMethod method)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Annotations/FileCacheReader.php#L152" target='_blank'>framework\libs\doctrine-common\Doctrine\Common\Annotations\FileCacheReader.php at line 152</a>

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Annotations/FileCacheReader.php#L172" target='_blank'>framework\libs\doctrine-common\Doctrine\Common\Annotations\FileCacheReader.php at line 172</a>

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Annotations/FileCacheReader.php#L192" target='_blank'>framework\libs\doctrine-common\Doctrine\Common\Annotations\FileCacheReader.php at line 192</a>

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Annotations/FileCacheReader.php#L205" target='_blank'>framework\libs\doctrine-common\Doctrine\Common\Annotations\FileCacheReader.php at line 205</a>

<h3 id="clearLoadedAnnotations()">clearLoadedAnnotations</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>clearLoadedAnnotations</span> ()

<div class="details">

</div>

- - -

