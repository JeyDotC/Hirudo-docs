

- - -

**Symfony\Component\DependencyInjection\Loader\IniFileLoader**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Loader/IniFileLoader.php#L22" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Loader\IniFileLoader.php at line 22</a>

#Class IniFileLoader#

BaseFileLoader
* <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/loader/FileLoader.md">FileLoader</a>
        * **IniFileLoader**




- - -

<p class="signature"><span class='k'>public  class</span> <span class='nx'>IniFileLoader</span>
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/loader/FileLoader.md">FileLoader</a>

</p>

<div class="comment" id="overview_description"><p>IniFileLoader loads parameters from INI files.</p></div>

<dl>
<dt>Author:</dt>
<dd>Fabien Potencier <fabien@symfony.com></dd>
</dl>


- - -

<table class="inherit">
<tr><th colspan="2">Fields inherited from Symfony\Component\DependencyInjection\Loader\FileLoader</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/loader/FileLoader.md#container">container</a></td></tr></table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#load">load</a>(mixed file, string type)</p><p class="description">Loads a resource.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>Boolean</span></td>
<td class="description"><p class="name"><a href="#supports">supports</a>(mixed resource, string type)</p><p class="description">Returns true if this class supports the given resource.</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Symfony\Component\DependencyInjection\Loader\FileLoader</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/loader/FileLoader.md#__construct">__construct</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Loader/IniFileLoader.php#L32" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Loader\IniFileLoader.php at line 32</a>

<h3 id="load()">load</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>load</span> (mixed file, string type)

<div class="details">
<p>Loads a resource.</p><dl>
<dt>Parameters:</dt>
<dd>file - The resource</dd>
<dd>type - The resource type</dd>
<dt>Throws:</dt>
<dd><a href="../../../../symfony/component/dependencyinjection/exception/invalidargumentexception.html">\InvalidArgumentException</a> - When ini file is not valid</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Loader/IniFileLoader.php#L58" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Loader\IniFileLoader.php at line 58</a>

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

