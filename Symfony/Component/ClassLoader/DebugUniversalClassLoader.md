

- - -

**Symfony\Component\ClassLoader\DebugUniversalClassLoader**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/ClassLoader/DebugUniversalClassLoader.php#L19" target='_blank'>framework\libs\symfony-components\Symfony\Component\ClassLoader\DebugUniversalClassLoader.php at line 19</a>

#Class DebugUniversalClassLoader#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/ClassLoader/UniversalClassLoader.md">UniversalClassLoader</a>
 &gt; **DebugUniversalClassLoader**




- - -

<p><strong>public  class</strong> <span>DebugUniversalClassLoader</span>
<strong>extends</strong> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/ClassLoader/UniversalClassLoader.md">UniversalClassLoader</a>

</p>

<div class="comment" id="overview_description"><p>Checks that the class is actually declared in the included file.</p></div>

<dl>
<dt>Author:</dt>
<dd>Fabien Potencier <fabien@symfony.com></dd>
<dt>Api.</dt>
</dl>


<hr />

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
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/ClassLoader/UniversalClassLoader.md#findFile">findFile</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/ClassLoader/UniversalClassLoader.md#getNamespaceFallbacks">getNamespaceFallbacks</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/ClassLoader/UniversalClassLoader.md#getNamespaces">getNamespaces</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/ClassLoader/UniversalClassLoader.md#getPrefixFallbacks">getPrefixFallbacks</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/ClassLoader/UniversalClassLoader.md#getPrefixes">getPrefixes</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/ClassLoader/UniversalClassLoader.md#getUseIncludePath">getUseIncludePath</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/ClassLoader/UniversalClassLoader.md#loadClass">loadClass</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/ClassLoader/UniversalClassLoader.md#register">register</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/ClassLoader/UniversalClassLoader.md#registerNamespace">registerNamespace</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/ClassLoader/UniversalClassLoader.md#registerNamespaceFallback">registerNamespaceFallback</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/ClassLoader/UniversalClassLoader.md#registerNamespaceFallbacks">registerNamespaceFallbacks</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/ClassLoader/UniversalClassLoader.md#registerNamespaces">registerNamespaces</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/ClassLoader/UniversalClassLoader.md#registerPrefix">registerPrefix</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/ClassLoader/UniversalClassLoader.md#registerPrefixFallback">registerPrefixFallback</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/ClassLoader/UniversalClassLoader.md#registerPrefixFallbacks">registerPrefixFallbacks</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/ClassLoader/UniversalClassLoader.md#registerPrefixes">registerPrefixes</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/ClassLoader/UniversalClassLoader.md#useIncludePath">useIncludePath</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/ClassLoader/DebugUniversalClassLoader.php#L24" target='_blank'>framework\libs\symfony-components\Symfony\Component\ClassLoader\DebugUniversalClassLoader.php at line 24</a>

<h3 id="enable()">enable</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>enable</span> ()

<div class="details">
<p>Replaces all regular UniversalClassLoader instances by a DebugUniversalClassLoader ones.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/ClassLoader/DebugUniversalClassLoader.php#L52" target='_blank'>framework\libs\symfony-components\Symfony\Component\ClassLoader\DebugUniversalClassLoader.php at line 52</a>

<h3 id="loadClass()">loadClass</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>loadClass</span> (string class)

<div class="details">
<p>Loads the given class or interface.</p><dl>
<dt>Parameters:</dt>
<dd>class - The name of the class</dd>
</dl>

</div>

- - -

