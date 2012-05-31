
- - -

**Doctrine\Common\Annotations\AnnotationRegistry**
<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\AnnotationRegistry.php at line 23</div>
#Class AnnotationRegistry#

**AnnotationRegistry**


- - -

<p class="signature">public final  class **AnnotationRegistry**</p>


- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> static  void</td>
<td class="description"><p class="name"><a href="#reset">reset</a>()</p></td>
</tr>
<tr>
<td class="type"> static  void</td>
<td class="description"><p class="name"><a href="#registerfile">registerFile</a>(mixed file)</p></td>
</tr>
<tr>
<td class="type"> static  void</td>
<td class="description"><p class="name"><a href="#registerautoloadnamespace">registerAutoloadNamespace</a>(string namespace, string|array|null dirs)</p><p class="description">Add a namespace with one or many directories to look for files or null for the include path.
</p></td>
</tr>
<tr>
<td class="type"> static  void</td>
<td class="description"><p class="name"><a href="#registerautoloadnamespaces">registerAutoloadNamespaces</a>(array namespaces)</p><p class="description">Register multiple namespacesLoading of this namespaces will be done with a PSR-0 namespace loading algorithm.</p></td>
</tr>
<tr>
<td class="type"> static  void</td>
<td class="description"><p class="name"><a href="#registerloader">registerLoader</a>(callable callable)</p><p class="description">Register an autoloading callable for annotations, much like spl_autoload_register().
</p></td>
</tr>
<tr>
<td class="type"> static  void</td>
<td class="description"><p class="name"><a href="#loadannotationclass">loadAnnotationClass</a>(string class)</p><p class="description">Autoload an annotation class silently.</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\AnnotationRegistry.php at line 44</div>
<h3 id="reset()">reset</h3>

public static  void **reset** ()<div class="details">
</div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\AnnotationRegistry.php at line 49</div>
<h3 id="registerFile()">registerFile</h3>

public static  void **registerFile** (mixed file)<div class="details">
</div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\AnnotationRegistry.php at line 61</div>
<h3 id="registerAutoloadNamespace()">registerAutoloadNamespace</h3>

public static  void **registerAutoloadNamespace** (string namespace, string|array|null dirs)<div class="details">
<p>Add a namespace with one or many directories to look for files or null for the include path.</p><p>Loading of this namespaces will be done with a PSR-0 namespace loading algorithm.</p></div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\AnnotationRegistry.php at line 72</div>
<h3 id="registerAutoloadNamespaces()">registerAutoloadNamespaces</h3>

public static  void **registerAutoloadNamespaces** (array namespaces)<div class="details">
<p>Register multiple namespaces</p><p>Loading of this namespaces will be done with a PSR-0 namespace loading algorithm.</p></div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\AnnotationRegistry.php at line 84</div>
<h3 id="registerLoader()">registerLoader</h3>

public static  void **registerLoader** (callable callable)<div class="details">
<p>Register an autoloading callable for annotations, much like spl_autoload_register().</p><p>NOTE: These class loaders HAVE to be silent when a class was not found!
IMPORTANT: Loaders have to return true if they loaded a class that could contain the searched annotation class.</p></div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Annotations\AnnotationRegistry.php at line 97</div>
<h3 id="loadAnnotationClass()">loadAnnotationClass</h3>

public static  void **loadAnnotationClass** (string class)<div class="details">
<p>Autoload an annotation class silently.</p></div>

- - -

