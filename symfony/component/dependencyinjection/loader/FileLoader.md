

- - -

**Symfony\Component\DependencyInjection\Loader\FileLoader**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Loader/FileLoader.php#L23" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Loader\FileLoader.php at line 23</a>

#Class FileLoader#

BaseFileLoader
* **FileLoader**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/loader/IniFileLoader.md">IniFileLoader</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/loader/PhpFileLoader.md">PhpFileLoader</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/loader/XmlFileLoader.md">XmlFileLoader</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/loader/YamlFileLoader.md">YamlFileLoader</a> </dd>
</dl>



- - -

<p class="signature"><span class='k'>public abstract  class</span> <span class='nx'>FileLoader</span>
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
<td><span class='k'>protected </span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="#container"> $container</a>
                                </p></td>
</tr>
</table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/symfony/component/dependencyinjection/ContainerBuilder.md">ContainerBuilder</a> container, FileLocator locator)</p><p class="description">Constructor.</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Loader/FileLoader.php#L33" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Loader\FileLoader.php at line 33</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/symfony/component/dependencyinjection/ContainerBuilder.md">ContainerBuilder</a> container, FileLocator locator)

<div class="details">
<p>Constructor.</p><dl>
<dt>Parameters:</dt>
<dd>container - A ContainerBuilder instance</dd>
<dd>locator - A FileLocator instance</dd>
</dl>

</div>

- - -

