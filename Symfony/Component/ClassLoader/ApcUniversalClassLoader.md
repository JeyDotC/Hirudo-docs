

- - -

**Symfony\Component\ClassLoader\ApcUniversalClassLoader**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/ClassLoader/ApcUniversalClassLoader.php#L63" target='_blank'>framework\libs\symfony-components\Symfony\Component\ClassLoader\ApcUniversalClassLoader.php at line 63</a>

#Class ApcUniversalClassLoader#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/ClassLoader/UniversalClassLoader.md">UniversalClassLoader</a>
 &gt; **ApcUniversalClassLoader**




- - -

<p><strong>public  class</strong> <span>ApcUniversalClassLoader</span>
<strong>extends</strong> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/ClassLoader/UniversalClassLoader.md">UniversalClassLoader</a>

</p>

<div class="comment" id="overview_description"><p>ApcUniversalClassLoader implements a "universal" autoloader cached in APC for PHP 5.3.</p><p>It is able to load classes that use either:</p><p>* The technical interoperability standards for PHP 5.3 namespaces and
class names (http://groups.google.com/group/php-standards/web/psr-0-final-proposal);</p><p>* The PEAR naming convention for classes (http://pear.php.net/).</p><p>Classes from a sub-namespace or a sub-hierarchy of PEAR classes can be
looked for in a list of locations to ease the vendoring of a sub-set of
classes for large projects.</p><p>Example usage:</p><p>require 'vendor/symfony/src/Symfony/Component/ClassLoader/UniversalClassLoader.php';
require 'vendor/symfony/src/Symfony/Component/ClassLoader/ApcUniversalClassLoader.php';</p><p>use Symfony\Component\ClassLoader\ApcUniversalClassLoader;</p><p>$loader = new ApcUniversalClassLoader('apc.prefix.');</p><p>// register classes with namespaces
$loader->registerNamespaces(array(
'Symfony\Component' => __DIR__.'/component',
'Symfony'           => __DIR__.'/framework',
'Sensio'            => array(__DIR__.'/src', __DIR__.'/vendor'),
));</p><p>// register a library using the PEAR naming convention
$loader->registerPrefixes(array(
'Swift_' => __DIR__.'/Swift',
));</p><p>// activate the autoloader
$loader->register();</p><p>In this example, if you try to use a class in the Symfony\Component
namespace or one of its children (Symfony\Component\Console for instance),
the autoloader will first look for the class under the component/
directory, and it will then fallback to the framework/ directory if not
found before giving up.</p></div>

<dl>
<dt>Author:</dt>
<dd>Fabien Potencier <fabien@symfony.com></dd>
<dd>Kris Wallsmith <kris@symfony.com></dd>
<dt>Api.</dt>
</dl>


<hr />

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(string prefix)</p><p class="description">Constructor.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>string|null</span></td>
<td class="description"><p class="name"><a href="#findfile">findFile</a>(string class)</p><p class="description">Finds a file by class name while caching lookups to APC.</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Symfony\Component\ClassLoader\UniversalClassLoader</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/ClassLoader/UniversalClassLoader.md#findFile">findFile</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/ClassLoader/UniversalClassLoader.md#getNamespaceFallbacks">getNamespaceFallbacks</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/ClassLoader/UniversalClassLoader.md#getNamespaces">getNamespaces</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/ClassLoader/UniversalClassLoader.md#getPrefixFallbacks">getPrefixFallbacks</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/ClassLoader/UniversalClassLoader.md#getPrefixes">getPrefixes</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/ClassLoader/UniversalClassLoader.md#getUseIncludePath">getUseIncludePath</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/ClassLoader/UniversalClassLoader.md#loadClass">loadClass</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/ClassLoader/UniversalClassLoader.md#register">register</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/ClassLoader/UniversalClassLoader.md#registerNamespace">registerNamespace</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/ClassLoader/UniversalClassLoader.md#registerNamespaceFallback">registerNamespaceFallback</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/ClassLoader/UniversalClassLoader.md#registerNamespaceFallbacks">registerNamespaceFallbacks</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/ClassLoader/UniversalClassLoader.md#registerNamespaces">registerNamespaces</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/ClassLoader/UniversalClassLoader.md#registerPrefix">registerPrefix</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/ClassLoader/UniversalClassLoader.md#registerPrefixFallback">registerPrefixFallback</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/ClassLoader/UniversalClassLoader.md#registerPrefixFallbacks">registerPrefixFallbacks</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/ClassLoader/UniversalClassLoader.md#registerPrefixes">registerPrefixes</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/ClassLoader/UniversalClassLoader.md#useIncludePath">useIncludePath</a></td></tr></table>

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/ClassLoader/ApcUniversalClassLoader.php#L74" target='_blank'>framework\libs\symfony-components\Symfony\Component\ClassLoader\ApcUniversalClassLoader.php at line 74</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (string prefix)

<div class="details">
<p>Constructor.</p><dl>
<dt>Parameters:</dt>
<dd>prefix - A prefix to create a namespace in APC</dd>
<dt>Api.</dt>
</dl>

</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/ClassLoader/ApcUniversalClassLoader.php#L88" target='_blank'>framework\libs\symfony-components\Symfony\Component\ClassLoader\ApcUniversalClassLoader.php at line 88</a>

<h3 id="findFile()">findFile</h3>
<span class='k'></span> <span class='nx'>string|null</span> <span class='nf'>findFile</span> (string class)

<div class="details">
<p>Finds a file by class name while caching lookups to APC.</p><dl>
<dt>Parameters:</dt>
<dd>class - A class name to resolve to file</dd>
<dt>Returns:</dt>
<dd>The path, if found</dd>
</dl>

</div>

- - -
