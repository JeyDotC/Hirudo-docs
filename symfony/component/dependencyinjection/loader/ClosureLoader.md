
- - -

**Symfony\Component\DependencyInjection\Loader\ClosureLoader**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\libs\symfony-components\Symfony\Component\DependencyInjection\Loader\ClosureLoader.php at line 24#L24 class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Loader\ClosureLoader.php at line 24</a>

#Class ClosureLoader#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/lang/loader.html">Loader</a>
    * **ClosureLoader**




- - -

<p class="signature">public  class **ClosureLoader**
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/lang/loader.html">Loader</a>

</p>

<div class="comment" id="overview_description"><p>ClosureLoader loads service definitions from a PHP closure.</p><p>The Closure has access to the container as its first argument.</p></div>

<dl>
<dt>Author:</dt>
<dd>Fabien Potencier <fabien@symfony.com></dd>
<dt>See Also:</dt>
<dd><a href="../../../../hirudo/lang/loader.html#using()">Loader::using()</a></dd>
</dl>


- - -

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(<a href="../../../../symfony/component/dependencyinjection/containerbuilder.html">ContainerBuilder</a> container)</p><p class="description">Constructor.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#load">load</a>(\Closure closure, string type)</p><p class="description">Loads a Closure.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>Boolean</span></td>
<td class="description"><p class="name"><a href="#supports">supports</a>(mixed resource, string type)</p><p class="description">Returns true if this class supports the given resource.</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Hirudo\Lang\Loader</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/lang/loader.html#arrayToPaths()">arrayToPaths</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/lang/loader.html#isDir()">isDir</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/lang/loader.html#isFile()">isFile</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/lang/loader.html#toPaths()">toPaths</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/lang/loader.html#toSinglePath()">toSinglePath</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/lang/loader.html#using()">using</a></td></tr></table>

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\libs\symfony-components\Symfony\Component\DependencyInjection\Loader\ClosureLoader.php at line 33#L33 class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Loader\ClosureLoader.php at line 33</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (<a href="../../../../symfony/component/dependencyinjection/containerbuilder.html">ContainerBuilder</a> container)

<div class="details">
<p>Constructor.</p><dl>
<dt>Parameters:</dt>
<dd>container - A ContainerBuilder instance</dd>
</dl>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\libs\symfony-components\Symfony\Component\DependencyInjection\Loader\ClosureLoader.php at line 44#L44 class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Loader\ClosureLoader.php at line 44</a>

<h3 id="load()">load</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>load</span> (\Closure closure, string type)

<div class="details">
<p>Loads a Closure.</p><dl>
<dt>Parameters:</dt>
<dd>closure - The resource</dd>
<dd>type - The resource type</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework\libs\symfony-components\Symfony\Component\DependencyInjection\Loader\ClosureLoader.php at line 57#L57 class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Loader\ClosureLoader.php at line 57</a>

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

