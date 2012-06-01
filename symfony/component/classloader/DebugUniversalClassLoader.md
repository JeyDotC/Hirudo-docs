

- - -

**Symfony\Component\ClassLoader\DebugUniversalClassLoader**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/ClassLoader/DebugUniversalClassLoader.php#L19" >framework\libs\symfony-components\Symfony\Component\ClassLoader\DebugUniversalClassLoader.php at line 19</a>

#Class DebugUniversalClassLoader#

<a href="">UniversalClassLoader</a>
    * **DebugUniversalClassLoader**




- - -

<p class="signature"><span class='k'>public  class</span> <span class='nx'>DebugUniversalClassLoader</span>
extends <a href="">UniversalClassLoader</a>

</p>

<div class="comment" id="overview_description"><p>Checks that the class is actually declared in the included file.</p></div>

<dl>
<dt>Author:</dt>
<dd>Fabien Potencier <fabien@symfony.com></dd>
<dt>Api.</dt>
</dl>


- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#enable">enable</a>()</p><p class="description">Replaces all regular UniversalClassLoader instances by a DebugUniversalClassLoader ones.</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#loadclass">loadClass</a>(string class)</p><p class="description">Loads the given class or interface.</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Symfony\Component\ClassLoader\UniversalClassLoader</th></tr>
<tr><td><a href="">findFile</a>, <a href="">getNamespaceFallbacks</a>, <a href="">getNamespaces</a>, <a href="">getPrefixFallbacks</a>, <a href="">getPrefixes</a>, <a href="">getUseIncludePath</a>, <a href="">loadClass</a>, <a href="">register</a>, <a href="">registerNamespace</a>, <a href="">registerNamespaceFallback</a>, <a href="">registerNamespaceFallbacks</a>, <a href="">registerNamespaces</a>, <a href="">registerPrefix</a>, <a href="">registerPrefixFallback</a>, <a href="">registerPrefixFallbacks</a>, <a href="">registerPrefixes</a>, <a href="">useIncludePath</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/ClassLoader/DebugUniversalClassLoader.php#L24" >framework\libs\symfony-components\Symfony\Component\ClassLoader\DebugUniversalClassLoader.php at line 24</a>

<h3 id="enable()">enable</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>enable</span> ()

<div class="details">
<p>Replaces all regular UniversalClassLoader instances by a DebugUniversalClassLoader ones.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/ClassLoader/DebugUniversalClassLoader.php#L52" >framework\libs\symfony-components\Symfony\Component\ClassLoader\DebugUniversalClassLoader.php at line 52</a>

<h3 id="loadClass()">loadClass</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>loadClass</span> (string class)

<div class="details">
<p>Loads the given class or interface.</p><dl>
<dt>Parameters:</dt>
<dd>class - The name of the class</dd>
</dl>

</div>

- - -

