- - -

**Hirudo\Lang\Loader**
<div class="location">framework\hirudo\Hirudo\Lang\Loader.php at line 46</div>
#Class Loader#

**Loader**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/loader/closureloader.html">Symfony\Component\DependencyInjection\Loader\ClosureLoader</a> </dd>
</dl>

- - -

<p class="signature">public final  class **Loader**</p>

<div class="comment" id="overview_description"><p><p>A PHP file loader. It's like an enhanced require_once. The improvements
consist on:</p></p>
<ul>
<li>Having a sigle style for path strings using the '::' notation for directrory separators</li>
<li>The use of the '*' notation to load all files in a path.</li>
</ul>
<p></p></div>

<dl>
<dt>See Also:</dt>
<dd><a href="../../../../hirudo/lang/loader.html#using()">Loader::using()</a></dd>
</dl>
- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type">static  void</td>
<td class="description"><p class="name"><a href="#using">using</a>(string|array file, string extension)</p><p class="description">Loads a PHP file using a package syntax which consists of a path from
the Loader's root where is used the :: operator instead of
the directory separator and ommiting the file extension. </p></td>
</tr>
<tr>
<td class="type">static  array</td>
<td class="description"><p class="name"><a href="#arrayToPaths">arrayToPaths</a>(array array, string extension)</p><p class="description">Traduces a list of strings with the <a href="../../hirudo/lang/loader.html#using()">Loader::using()</a> format to the
resulting paths.</p></td>
</tr>
<tr>
<td class="type">static  array</td>
<td class="description"><p class="name"><a href="#toPaths">toPaths</a>(array array, string extension, mixed string)</p><p class="description">Traduces string with the <a href="../../hirudo/lang/loader.html#using()">Loader::using()</a> format to the
resulting paths.</p></td>
</tr>
<tr>
<td class="type">static  void</td>
<td class="description"><p class="name"><a href="#toSinglePath">toSinglePath</a>(mixed string, mixed extension)</p></td>
</tr>
<tr>
<td class="type">static  void</td>
<td class="description"><p class="name"><a href="#isDir">isDir</a>(mixed dir)</p></td>
</tr>
<tr>
<td class="type">static  void</td>
<td class="description"><p class="name"><a href="#isFile">isFile</a>(mixed file, mixed extension)</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\hirudo\Hirudo\Lang\Loader.php at line 72</div>
<h3 id="using()">using</h3>

```php
public static  void **using**(string|array file, string extension)
```
<div class="details">
<p><p>Loads a PHP file using a package syntax which consists of a path from
the Loader's root where is used the <code>::</code> operator instead of
the directory separator and ommiting the file extension.
e.g. <code>Loader::using("folder::inner::MyPhpFile")</code></p></p><p><p>The character <code>*</code> can be used to load all the files in a
directory.</p></p><dl>
<dt>Parameters:</dt>
<dd>file - The path or paths to the files with the format specified above.</dd>
<dd>extension - = ".php" An optional extension to be applied when a file doesn't belong to the group of files found from the <code>*</code> operator.</dd>
<dt>Throws:</dt>
<dd><a href="../../hirudo/lang/invalidpathexception.html">InvalidPathException</a> - If $string is not a string, is null or is empty.</dd>
<dd>LogicException - If $extension is not a string.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Lang\Loader.php at line 101</div>
<h3 id="arrayToPaths()">arrayToPaths</h3>

```php
public static  array **arrayToPaths**(array array, string extension)
```
<div class="details">
<p>Traduces a list of strings with the <code><a href="../../hirudo/lang/loader.html#using()">Loader::using()</a></code> format to the
resulting paths.</p><dl>
<dt>Parameters:</dt>
<dd>array - An array of strings representing the paths.</dd>
<dd>extension - An extension to be applied to the paths.</dd>
<dt>Returns:</dt>
<dd>An array of absolute paths.</dd>
<dt>See Also:</dt>
<dd><a href="../../hirudo/lang/loader.html#using()">For more details.</a></dd>
<dd>For more details.</dd>
<dt>Throws:</dt>
<dd><a href="../../hirudo/lang/invalidpathexception.html">InvalidPathException</a> - If $string is not a string, is null or is empty.</dd>
<dd>LogicException - If $extension is not a string.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Lang\Loader.php at line 124</div>
<h3 id="toPaths()">toPaths</h3>

```php
public static  array **toPaths**(array array, string extension, mixed string)
```
<div class="details">
<p>Traduces string with the <code><a href="../../hirudo/lang/loader.html#using()">Loader::using()</a></code> format to the
resulting paths.</p><dl>
<dt>Parameters:</dt>
<dd>array - A string representing the paths.</dd>
<dd>extension - An extension to be applied to the paths.</dd>
<dt>Returns:</dt>
<dd>An array of absolute paths.</dd>
<dt>See Also:</dt>
<dd><a href="../../hirudo/lang/loader.html#using()">For more details.</a></dd>
<dt>Throws:</dt>
<dd><a href="../../hirudo/lang/invalidpathexception.html">InvalidPathException</a> - If $string is not a string, is null or is empty.</dd>
<dd>LogicException - If $extension is not a string.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Lang\Loader.php at line 143</div>
<h3 id="toSinglePath()">toSinglePath</h3>

```php
public static  void **toSinglePath**(mixed string, mixed extension)
```
<div class="details">
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Lang\Loader.php at line 163</div>
<h3 id="isDir()">isDir</h3>

```php
public static  void **isDir**(mixed dir)
```
<div class="details">
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Lang\Loader.php at line 168</div>
<h3 id="isFile()">isFile</h3>

```php
public static  void **isFile**(mixed file, mixed extension)
```
<div class="details">
</div>

- - -

