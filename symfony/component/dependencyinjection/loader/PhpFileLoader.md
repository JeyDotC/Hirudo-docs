- - -

**Symfony\Component\DependencyInjection\Loader\PhpFileLoader**
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Loader\PhpFileLoader.php at line 24</div>
#Class PhpFileLoader#

BaseFileLoader
*<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/loader/fileloader.html">FileLoader</a>
        ***PhpFileLoader**


- - -

<p class="signature">public  class **PhpFileLoader**
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/loader/fileloader.html">FileLoader</a>

</p>

<div class="comment" id="overview_description"><p>PhpFileLoader loads service definitions from a PHP file.</p><p>The PHP file is required and the $container variable can be
used form the file to change the container.</p></div>

<dl>
<dt>Author:</dt>
<dd>Fabien Potencier <fabien@symfony.com></dd>
</dl>
- - -

<table class="inherit">
<tr><th colspan="2">Fields inherited from Symfony\Component\DependencyInjection\Loader\FileLoader</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/loader/fileloader.html#container">container</a></td></tr></table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#load">load</a>(mixed file, string type)</p><p class="description">Loads a PHP file.</p></td>
</tr>
<tr>
<td class="type"> Boolean</td>
<td class="description"><p class="name"><a href="#supports">supports</a>(mixed resource, string type)</p><p class="description">Returns true if this class supports the given resource.</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Symfony\Component\DependencyInjection\Loader\FileLoader</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/loader/fileloader.html#__construct()">__construct</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Loader\PhpFileLoader.php at line 32</div>
<h3 id="load()">load</h3>
```php
public  void **load**(mixed file, string type)```
<div class="details">
<p>Loads a PHP file.</p><dl>
<dt>Parameters:</dt>
<dd>file - The resource</dd>
<dd>type - The resource type</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Loader\PhpFileLoader.php at line 53</div>
<h3 id="supports()">supports</h3>
```php
public  Boolean **supports**(mixed resource, string type)```
<div class="details">
<p>Returns true if this class supports the given resource.</p><dl>
<dt>Parameters:</dt>
<dd>resource - A resource</dd>
<dd>type - The resource type</dd>
<dt>Returns:</dt>
<dd>true if this class supports the given resource, false otherwise</dd>
</dl>
</div>

- - -

