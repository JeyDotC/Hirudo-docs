- - -

**Symfony\Component\DependencyInjection\Loader\FileLoader**
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Loader\FileLoader.php at line 23</div>
#Class FileLoader#

BaseFileLoader
***FileLoader**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/loader/inifileloader.html">IniFileLoader</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/loader/phpfileloader.html">PhpFileLoader</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/loader/xmlfileloader.html">XmlFileLoader</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/loader/yamlfileloader.html">YamlFileLoader</a> </dd>
</dl>

- - -

<p class="signature">public abstract  class **FileLoader**
extends BaseFileLoader

</p>

<div class="comment" id="overview_description"><p>FileLoader is the abstract class used by all built-in loaders that are file based.</p></div>

<dl>
<dt>Author:</dt>
<dd>Fabien Potencier <fabien@symfony.com></dd>
</dl>
- - -

<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td class="type">protected  mixed</td>
<td class="description"><p class="name"><a href="#container">$container</a></p></td>
</tr>
</table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(<a href="../../../../symfony/component/dependencyinjection/containerbuilder.html">ContainerBuilder</a> container, FileLocator locator)</p><p class="description">Constructor.</p></td>
</tr>
</table>

##Field Detail##
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Loader\FileLoader.php at line 25</div>
<h3 id="container">container</h3>
```php
protected  mixed **$container** = null```
<div class="details">
</div>

- - -

<h2 id="detail_method">Constructor Detail</h2>
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Loader\FileLoader.php at line 33</div>
<h3 id="__construct()">__construct</h3>
```php
public  void **__construct**(<a href="../../../../symfony/component/dependencyinjection/containerbuilder.html">ContainerBuilder</a> container, FileLocator locator)```
<div class="details">
<p>Constructor.</p><dl>
<dt>Parameters:</dt>
<dd>container - A ContainerBuilder instance</dd>
<dd>locator - A FileLocator instance</dd>
</dl>
</div>

- - -

