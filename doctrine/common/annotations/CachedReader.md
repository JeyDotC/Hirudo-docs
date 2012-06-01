

- - -

**Doctrine\Common\Annotations\CachedReader**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Annotations/CachedReader.php#L30" >framework\libs\doctrine-common\Doctrine\Common\Annotations\CachedReader.php at line 30</a>

#Class CachedReader#

**CachedReader**




- - -

<p class="signature"><span class='k'>public final  class</span> <span class='nx'>CachedReader</span></p>

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
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/doctrine/common/annotations/reader.md">Reader</a> reader, <a href="https://github.com/JeyDotC/Hirudo/blob/master/doctrine/common/cache/cache.md">Cache</a> cache, bool debug)</p><p class="description"></p></td>
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
<td class="description"><p class="name"><a href="#getclassannotation">getClassAnnotation</a>(ReflectionClass class, mixed annotationName)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#getpropertyannotations">getPropertyAnnotations</a>(ReflectionProperty property)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#getpropertyannotation">getPropertyAnnotation</a>(ReflectionProperty property, mixed annotationName)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#getmethodannotations">getMethodAnnotations</a>(ReflectionMethod method)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#getmethodannotation">getMethodAnnotation</a>(ReflectionMethod method, mixed annotationName)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#clearloadedannotations">clearLoadedAnnotations</a>()</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Annotations/CachedReader.php#L58" >framework\libs\doctrine-common\Doctrine\Common\Annotations\CachedReader.php at line 58</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/doctrine/common/annotations/reader.md">Reader</a> reader, <a href="https://github.com/JeyDotC/Hirudo/blob/master/doctrine/common/cache/cache.md">Cache</a> cache, bool debug)

<div class="details">
<p></p>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Annotations/CachedReader.php#L65" >framework\libs\doctrine-common\Doctrine\Common\Annotations\CachedReader.php at line 65</a>

<h3 id="getClassAnnotations()">getClassAnnotations</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>getClassAnnotations</span> (ReflectionClass class)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Annotations/CachedReader.php#L81" >framework\libs\doctrine-common\Doctrine\Common\Annotations\CachedReader.php at line 81</a>

<h3 id="getClassAnnotation()">getClassAnnotation</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>getClassAnnotation</span> (ReflectionClass class, mixed annotationName)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Annotations/CachedReader.php#L92" >framework\libs\doctrine-common\Doctrine\Common\Annotations\CachedReader.php at line 92</a>

<h3 id="getPropertyAnnotations()">getPropertyAnnotations</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>getPropertyAnnotations</span> (ReflectionProperty property)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Annotations/CachedReader.php#L109" >framework\libs\doctrine-common\Doctrine\Common\Annotations\CachedReader.php at line 109</a>

<h3 id="getPropertyAnnotation()">getPropertyAnnotation</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>getPropertyAnnotation</span> (ReflectionProperty property, mixed annotationName)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Annotations/CachedReader.php#L120" >framework\libs\doctrine-common\Doctrine\Common\Annotations\CachedReader.php at line 120</a>

<h3 id="getMethodAnnotations()">getMethodAnnotations</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>getMethodAnnotations</span> (ReflectionMethod method)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Annotations/CachedReader.php#L137" >framework\libs\doctrine-common\Doctrine\Common\Annotations\CachedReader.php at line 137</a>

<h3 id="getMethodAnnotation()">getMethodAnnotation</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>getMethodAnnotation</span> (ReflectionMethod method, mixed annotationName)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Annotations/CachedReader.php#L148" >framework\libs\doctrine-common\Doctrine\Common\Annotations\CachedReader.php at line 148</a>

<h3 id="clearLoadedAnnotations()">clearLoadedAnnotations</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>clearLoadedAnnotations</span> ()

<div class="details">

</div>

- - -

