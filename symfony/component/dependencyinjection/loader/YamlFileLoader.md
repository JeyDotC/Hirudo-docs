

- - -

**Symfony\Component\DependencyInjection\Loader\YamlFileLoader**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Loader/YamlFileLoader.php#L30" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Loader\YamlFileLoader.php at line 30</a>

#Class YamlFileLoader#

BaseFileLoader
* <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/loader/fileloader.md">FileLoader</a>
        * **YamlFileLoader**




- - -

<p class="signature"><span class='k'>public  class</span> <span class='nx'>YamlFileLoader</span>
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/loader/fileloader.md">FileLoader</a>

</p>

<div class="comment" id="overview_description"><p>YamlFileLoader loads YAML files service definitions.</p><p>The YAML format does not support anonymous services (cf. the XML loader).</p></div>

<dl>
<dt>Author:</dt>
<dd>Fabien Potencier <fabien@symfony.com></dd>
</dl>


- - -

<table class="inherit">
<tr><th colspan="2">Fields inherited from Symfony\Component\DependencyInjection\Loader\FileLoader</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/loader/fileloader.md">container</a></td></tr></table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#load">load</a>(mixed file, string type)</p><p class="description">Loads a Yaml file.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>Boolean</span></td>
<td class="description"><p class="name"><a href="#supports">supports</a>(mixed resource, string type)</p><p class="description">Returns true if this class supports the given resource.</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Symfony\Component\DependencyInjection\Loader\FileLoader</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/loader/fileloader.md">__construct</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Loader/YamlFileLoader.php#L38" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Loader\YamlFileLoader.php at line 38</a>

<h3 id="load()">load</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>load</span> (mixed file, string type)

<div class="details">
<p>Loads a Yaml file.</p><dl>
<dt>Parameters:</dt>
<dd>file - The resource</dd>
<dd>type - The resource type</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Loader/YamlFileLoader.php#L76" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Loader\YamlFileLoader.php at line 76</a>

<h3 id="supports()">supports</h3>
<span class='k'></span> <span class='nx'>Boolean</span> <span class='nf'>supports</span> (mixed resource, string type)

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

