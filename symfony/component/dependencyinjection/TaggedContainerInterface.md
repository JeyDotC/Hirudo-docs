- - -

**Symfony\Component\DependencyInjection\TaggedContainerInterface**
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/TaggedContainerInterface.php.md#line21" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\TaggedContainerInterface.php at line 21</a>

# Interface TaggedContainerInterface #

<pre class="tree"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/containerinterface.html">ContainerInterface</a>\n    *** TaggedContainerInterface **\n</pre>

- - -

<p class="signature">public  interface **TaggedContainerInterface**\nextends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/containerinterface.html">ContainerInterface</a>

</p>

<div class="comment" id="overview_description"><p>TaggedContainerInterface is the interface implemented when a container knows how to deals with tags.</p></div>

<dl>
<dt>Author:</dt>
<dd>Fabien Potencier <fabien@symfony.com></dd>
<dt>Api.</dt>
</dl>
- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#findTaggedServiceIds()">findTaggedServiceIds</a>(string name)</p><p class="description">Returns service ids for a given tag.</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Symfony\Component\DependencyInjection\ContainerInterface</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/containerinterface.html#addScope()">addScope</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/containerinterface.html#enterScope()">enterScope</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/containerinterface.html#get()">get</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/containerinterface.html#getParameter()">getParameter</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/containerinterface.html#has()">has</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/containerinterface.html#hasParameter()">hasParameter</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/containerinterface.html#hasScope()">hasScope</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/containerinterface.html#isScopeActive()">isScopeActive</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/containerinterface.html#leaveScope()">leaveScope</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/containerinterface.html#setParameter()">setParameter</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/TaggedContainerInterface.php.md#line32" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\TaggedContainerInterface.php at line 32</a>

<h3 id="findTaggedServiceIds()">findTaggedServiceIds</h3>
```php
public  array **findTaggedServiceIds**(string name)```
<div class="details">
<p>Returns service ids for a given tag.</p><dl>
<dt>Parameters:</dt>
<dd>name - The tag name</dd>
<dt>Returns:</dt>
<dd>An array of tags</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

