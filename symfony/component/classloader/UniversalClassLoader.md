
- - -

**Symfony\Component\ClassLoader\UniversalClassLoader**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/symfony/component/classloader/universalclassloader.php#L61 class="location">framework\libs\symfony-components\Symfony\Component\ClassLoader\UniversalClassLoader.php at line 61</a>

#Class UniversalClassLoader#

**UniversalClassLoader**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/classloader/apcuniversalclassloader.html">ApcUniversalClassLoader</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/classloader/debuguniversalclassloader.html">DebugUniversalClassLoader</a> </dd>
</dl>



- - -

<p class="signature">public  class **UniversalClassLoader**</p>

<div class="comment" id="overview_description"><p>UniversalClassLoader implements a "universal" autoloader for PHP 5.3.</p><p>It is able to load classes that use either:</p><p>* The technical interoperability standards for PHP 5.3 namespaces and
class names (https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-0.md);</p><p>* The PEAR naming convention for classes (http://pear.php.net/).</p><p>Classes from a sub-namespace or a sub-hierarchy of PEAR classes can be
looked for in a list of locations to ease the vendoring of a sub-set of
classes for large projects.</p><p>Example usage:</p><p>$loader = new UniversalClassLoader();</p><p>// register classes with namespaces
$loader->registerNamespaces(array(
'Symfony\Component' => __DIR__.'/component',
'Symfony'           => __DIR__.'/framework',
'Sensio'            => array(__DIR__.'/src', __DIR__.'/vendor'),
));</p><p>// register a library using the PEAR naming convention
$loader->registerPrefixes(array(
'Swift_' => __DIR__.'/Swift',
));</p><p>
// to enable searching the include path (eg. for PEAR packages)
$loader->useIncludePath(true);</p><p>// activate the autoloader
$loader->register();</p><p>In this example, if you try to use a class in the Symfony\Component
namespace or one of its children (Symfony\Component\Console for instance),
the autoloader will first look for the class under the component/
directory, and it will then fallback to the framework/ directory if not
found before giving up.</p></div>

<dl>
<dt>Author:</dt>
<dd>Fabien Potencier <fabien@symfony.com></dd>
<dt>Api.</dt>
</dl>


- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#useincludepath">useIncludePath</a>(Boolean useIncludePath)</p><p class="description">Turns on searching the include for class files. </p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>Boolean</span></td>
<td class="description"><p class="name"><a href="#getuseincludepath">getUseIncludePath</a>()</p><p class="description">Can be used to check if the autoloader uses the include path to check
for classes.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name"><a href="#getnamespaces">getNamespaces</a>()</p><p class="description">Gets the configured namespaces.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name"><a href="#getprefixes">getPrefixes</a>()</p><p class="description">Gets the configured class prefixes.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name"><a href="#getnamespacefallbacks">getNamespaceFallbacks</a>()</p><p class="description">Gets the directory(ies) to use as a fallback for namespaces.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name"><a href="#getprefixfallbacks">getPrefixFallbacks</a>()</p><p class="description">Gets the directory(ies) to use as a fallback for class prefixes.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#registernamespacefallbacks">registerNamespaceFallbacks</a>(array dirs)</p><p class="description">Registers the directory to use as a fallback for namespaces.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#registernamespacefallback">registerNamespaceFallback</a>(string dir)</p><p class="description">Registers a directory to use as a fallback for namespaces.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#registerprefixfallbacks">registerPrefixFallbacks</a>(array dirs)</p><p class="description">Registers directories to use as a fallback for class prefixes.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#registerprefixfallback">registerPrefixFallback</a>(string dir)</p><p class="description">Registers a directory to use as a fallback for class prefixes.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#registernamespaces">registerNamespaces</a>(array namespaces)</p><p class="description">Registers an array of namespaces</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#registernamespace">registerNamespace</a>(string namespace, array|string paths)</p><p class="description">Registers a namespace.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#registerprefixes">registerPrefixes</a>(array classes)</p><p class="description">Registers an array of classes using the PEAR naming convention.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#registerprefix">registerPrefix</a>(string prefix, array|string paths)</p><p class="description">Registers a set of classes using the PEAR naming convention.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#register">register</a>(Boolean prepend)</p><p class="description">Registers this instance as an autoloader.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#loadclass">loadClass</a>(string class)</p><p class="description">Loads the given class or interface.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string|null</span></td>
<td class="description"><p class="name"><a href="#findfile">findFile</a>(string class)</p><p class="description">Finds the path to the file where the class is defined.</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/symfony/component/classloader/universalclassloader.php#L75 class="location">framework\libs\symfony-components\Symfony\Component\ClassLoader\UniversalClassLoader.php at line 75</a>

<h3 id="useIncludePath()">useIncludePath</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>useIncludePath</span> (Boolean useIncludePath)

<div class="details">
<p>Turns on searching the include for class files. Allows easy loading
of installed PEAR packages</p></div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/symfony/component/classloader/universalclassloader.php#L85 class="location">framework\libs\symfony-components\Symfony\Component\ClassLoader\UniversalClassLoader.php at line 85</a>

<h3 id="getUseIncludePath()">getUseIncludePath</h3>
<span class='k'></span> <span class='nx'>Boolean</span> <span class='nf'>getUseIncludePath</span> ()

<div class="details">
<p>Can be used to check if the autoloader uses the include path to check
for classes.</p></div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/symfony/component/classloader/universalclassloader.php#L94 class="location">framework\libs\symfony-components\Symfony\Component\ClassLoader\UniversalClassLoader.php at line 94</a>

<h3 id="getNamespaces()">getNamespaces</h3>
<span class='k'></span> <span class='nx'>array</span> <span class='nf'>getNamespaces</span> ()

<div class="details">
<p>Gets the configured namespaces.</p><dl>
<dt>Returns:</dt>
<dd>A hash with namespaces as keys and directories as values</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/symfony/component/classloader/universalclassloader.php#L103 class="location">framework\libs\symfony-components\Symfony\Component\ClassLoader\UniversalClassLoader.php at line 103</a>

<h3 id="getPrefixes()">getPrefixes</h3>
<span class='k'></span> <span class='nx'>array</span> <span class='nf'>getPrefixes</span> ()

<div class="details">
<p>Gets the configured class prefixes.</p><dl>
<dt>Returns:</dt>
<dd>A hash with class prefixes as keys and directories as values</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/symfony/component/classloader/universalclassloader.php#L112 class="location">framework\libs\symfony-components\Symfony\Component\ClassLoader\UniversalClassLoader.php at line 112</a>

<h3 id="getNamespaceFallbacks()">getNamespaceFallbacks</h3>
<span class='k'></span> <span class='nx'>array</span> <span class='nf'>getNamespaceFallbacks</span> ()

<div class="details">
<p>Gets the directory(ies) to use as a fallback for namespaces.</p><dl>
<dt>Returns:</dt>
<dd>An array of directories</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/symfony/component/classloader/universalclassloader.php#L121 class="location">framework\libs\symfony-components\Symfony\Component\ClassLoader\UniversalClassLoader.php at line 121</a>

<h3 id="getPrefixFallbacks()">getPrefixFallbacks</h3>
<span class='k'></span> <span class='nx'>array</span> <span class='nf'>getPrefixFallbacks</span> ()

<div class="details">
<p>Gets the directory(ies) to use as a fallback for class prefixes.</p><dl>
<dt>Returns:</dt>
<dd>An array of directories</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/symfony/component/classloader/universalclassloader.php#L132 class="location">framework\libs\symfony-components\Symfony\Component\ClassLoader\UniversalClassLoader.php at line 132</a>

<h3 id="registerNamespaceFallbacks()">registerNamespaceFallbacks</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>registerNamespaceFallbacks</span> (array dirs)

<div class="details">
<p>Registers the directory to use as a fallback for namespaces.</p><dl>
<dt>Parameters:</dt>
<dd>dirs - An array of directories</dd>
<dt>Api.</dt>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/symfony/component/classloader/universalclassloader.php#L141 class="location">framework\libs\symfony-components\Symfony\Component\ClassLoader\UniversalClassLoader.php at line 141</a>

<h3 id="registerNamespaceFallback()">registerNamespaceFallback</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>registerNamespaceFallback</span> (string dir)

<div class="details">
<p>Registers a directory to use as a fallback for namespaces.</p><dl>
<dt>Parameters:</dt>
<dd>dir - A directory</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/symfony/component/classloader/universalclassloader.php#L152 class="location">framework\libs\symfony-components\Symfony\Component\ClassLoader\UniversalClassLoader.php at line 152</a>

<h3 id="registerPrefixFallbacks()">registerPrefixFallbacks</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>registerPrefixFallbacks</span> (array dirs)

<div class="details">
<p>Registers directories to use as a fallback for class prefixes.</p><dl>
<dt>Parameters:</dt>
<dd>dirs - An array of directories</dd>
<dt>Api.</dt>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/symfony/component/classloader/universalclassloader.php#L161 class="location">framework\libs\symfony-components\Symfony\Component\ClassLoader\UniversalClassLoader.php at line 161</a>

<h3 id="registerPrefixFallback()">registerPrefixFallback</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>registerPrefixFallback</span> (string dir)

<div class="details">
<p>Registers a directory to use as a fallback for class prefixes.</p><dl>
<dt>Parameters:</dt>
<dd>dir - A directory</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/symfony/component/classloader/universalclassloader.php#L172 class="location">framework\libs\symfony-components\Symfony\Component\ClassLoader\UniversalClassLoader.php at line 172</a>

<h3 id="registerNamespaces()">registerNamespaces</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>registerNamespaces</span> (array namespaces)

<div class="details">
<p>Registers an array of namespaces</p><dl>
<dt>Parameters:</dt>
<dd>namespaces - An array of namespaces (namespaces as keys and locations as values)</dd>
<dt>Api.</dt>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/symfony/component/classloader/universalclassloader.php#L186 class="location">framework\libs\symfony-components\Symfony\Component\ClassLoader\UniversalClassLoader.php at line 186</a>

<h3 id="registerNamespace()">registerNamespace</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>registerNamespace</span> (string namespace, array|string paths)

<div class="details">
<p>Registers a namespace.</p><dl>
<dt>Parameters:</dt>
<dd>namespace - The namespace</dd>
<dd>paths - The location(s) of the namespace</dd>
<dt>Api.</dt>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/symfony/component/classloader/universalclassloader.php#L197 class="location">framework\libs\symfony-components\Symfony\Component\ClassLoader\UniversalClassLoader.php at line 197</a>

<h3 id="registerPrefixes()">registerPrefixes</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>registerPrefixes</span> (array classes)

<div class="details">
<p>Registers an array of classes using the PEAR naming convention.</p><dl>
<dt>Parameters:</dt>
<dd>classes - An array of classes (prefixes as keys and locations as values)</dd>
<dt>Api.</dt>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/symfony/component/classloader/universalclassloader.php#L211 class="location">framework\libs\symfony-components\Symfony\Component\ClassLoader\UniversalClassLoader.php at line 211</a>

<h3 id="registerPrefix()">registerPrefix</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>registerPrefix</span> (string prefix, array|string paths)

<div class="details">
<p>Registers a set of classes using the PEAR naming convention.</p><dl>
<dt>Parameters:</dt>
<dd>prefix - The classes prefix</dd>
<dd>paths - The location(s) of the classes</dd>
<dt>Api.</dt>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/symfony/component/classloader/universalclassloader.php#L222 class="location">framework\libs\symfony-components\Symfony\Component\ClassLoader\UniversalClassLoader.php at line 222</a>

<h3 id="register()">register</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>register</span> (Boolean prepend)

<div class="details">
<p>Registers this instance as an autoloader.</p><dl>
<dt>Parameters:</dt>
<dd>prepend - Whether to prepend the autoloader or not</dd>
<dt>Api.</dt>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/symfony/component/classloader/universalclassloader.php#L231 class="location">framework\libs\symfony-components\Symfony\Component\ClassLoader\UniversalClassLoader.php at line 231</a>

<h3 id="loadClass()">loadClass</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>loadClass</span> (string class)

<div class="details">
<p>Loads the given class or interface.</p><dl>
<dt>Parameters:</dt>
<dd>class - The name of the class</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/symfony/component/classloader/universalclassloader.php#L244 class="location">framework\libs\symfony-components\Symfony\Component\ClassLoader\UniversalClassLoader.php at line 244</a>

<h3 id="findFile()">findFile</h3>
<span class='k'></span> <span class='nx'>string|null</span> <span class='nf'>findFile</span> (string class)

<div class="details">
<p>Finds the path to the file where the class is defined.</p><dl>
<dt>Parameters:</dt>
<dd>class - The name of the class</dd>
<dt>Returns:</dt>
<dd>The path, if found</dd>
</dl>
</div>

- - -

