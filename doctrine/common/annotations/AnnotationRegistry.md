

- - -

**Doctrine\Common\Annotations\AnnotationRegistry**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Annotations/AnnotationRegistry.php#L23" >framework\libs\doctrine-common\Doctrine\Common\Annotations\AnnotationRegistry.php at line 23</a>

#Class AnnotationRegistry#

**AnnotationRegistry**




- - -

<p class="signature"><span class='k'>public final  class</span> <span class='nx'>AnnotationRegistry</span></p>



- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#reset">reset</a>()</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#registerfile">registerFile</a>(mixed file)</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#registerautoloadnamespace">registerAutoloadNamespace</a>(string namespace, string|array|null dirs)</p><p class="description">Add a namespace with one or many directories to look for files or null for the include path.
</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#registerautoloadnamespaces">registerAutoloadNamespaces</a>(array namespaces)</p><p class="description">Register multiple namespacesLoading of this namespaces will be done with a PSR-0 namespace loading algorithm.</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#registerloader">registerLoader</a>(callable callable)</p><p class="description">Register an autoloading callable for annotations, much like spl_autoload_register().
</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#loadannotationclass">loadAnnotationClass</a>(string class)</p><p class="description">Autoload an annotation class silently.</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Annotations/AnnotationRegistry.php#L44" >framework\libs\doctrine-common\Doctrine\Common\Annotations\AnnotationRegistry.php at line 44</a>

<h3 id="reset()">reset</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>reset</span> ()

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Annotations/AnnotationRegistry.php#L49" >framework\libs\doctrine-common\Doctrine\Common\Annotations\AnnotationRegistry.php at line 49</a>

<h3 id="registerFile()">registerFile</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>registerFile</span> (mixed file)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Annotations/AnnotationRegistry.php#L61" >framework\libs\doctrine-common\Doctrine\Common\Annotations\AnnotationRegistry.php at line 61</a>

<h3 id="registerAutoloadNamespace()">registerAutoloadNamespace</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>registerAutoloadNamespace</span> (string namespace, string|array|null dirs)

<div class="details">
<p>Add a namespace with one or many directories to look for files or null for the include path.</p><p>Loading of this namespaces will be done with a PSR-0 namespace loading algorithm.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Annotations/AnnotationRegistry.php#L72" >framework\libs\doctrine-common\Doctrine\Common\Annotations\AnnotationRegistry.php at line 72</a>

<h3 id="registerAutoloadNamespaces()">registerAutoloadNamespaces</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>registerAutoloadNamespaces</span> (array namespaces)

<div class="details">
<p>Register multiple namespaces</p><p>Loading of this namespaces will be done with a PSR-0 namespace loading algorithm.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Annotations/AnnotationRegistry.php#L84" >framework\libs\doctrine-common\Doctrine\Common\Annotations\AnnotationRegistry.php at line 84</a>

<h3 id="registerLoader()">registerLoader</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>registerLoader</span> (callable callable)

<div class="details">
<p>Register an autoloading callable for annotations, much like spl_autoload_register().</p><p>NOTE: These class loaders HAVE to be silent when a class was not found!
IMPORTANT: Loaders have to return true if they loaded a class that could contain the searched annotation class.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Annotations/AnnotationRegistry.php#L97" >framework\libs\doctrine-common\Doctrine\Common\Annotations\AnnotationRegistry.php at line 97</a>

<h3 id="loadAnnotationClass()">loadAnnotationClass</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>loadAnnotationClass</span> (string class)

<div class="details">
<p>Autoload an annotation class silently.</p>
</div>

- - -

