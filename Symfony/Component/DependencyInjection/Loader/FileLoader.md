

- - -

**Symfony\Component\DependencyInjection\Loader\FileLoader**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Loader/FileLoader.php#L23" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\Loader\FileLoader.php at line 23</a>

#Class FileLoader#

BaseFileLoader &gt; **FileLoader**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Loader/IniFileLoader.md">IniFileLoader</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Loader/PhpFileLoader.md">PhpFileLoader</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Loader/XmlFileLoader.md">XmlFileLoader</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Loader/YamlFileLoader.md">YamlFileLoader</a> </dd>
</dl>



- - -

<p><strong>public abstract  class</strong> <span>FileLoader</span>
<strong>extends</strong> BaseFileLoader

</p>

<div class="comment" id="overview_description"><p>FileLoader is the abstract class used by all built-in loaders that are file based.</p></div>

<dl>
<dt>Author:</dt>
<dd>Fabien Potencier <fabien@symfony.com></dd>
</dl>


<hr />



<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Loader/FileLoader.md#container"> $container</a>
                                </p></td>
</tr>
</table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/ContainerBuilder.md">ContainerBuilder</a> container, FileLocator locator)</p><p class="description">Constructor.</p></td>
</tr>
</table>

##Field Detail##

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Loader/FileLoader.php#L25" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\Loader\FileLoader.php at line 25</a>

<h3 id="container">container</h3>
<span class='k'>protected </span> <span class='nx'>mixed</span><span class='no'> $container</span><span class='o'> = null</span>

<div class="details">

</div>

- - -

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Loader/FileLoader.php#L33" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\Loader\FileLoader.php at line 33</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/ContainerBuilder.md">ContainerBuilder</a> container, FileLocator locator)

<div class="details">
<p>Constructor.</p><dl>
<dt>Parameters:</dt>
<dd>container - A ContainerBuilder instance</dd>
<dd>locator - A FileLocator instance</dd>
</dl>

</div>

- - -

