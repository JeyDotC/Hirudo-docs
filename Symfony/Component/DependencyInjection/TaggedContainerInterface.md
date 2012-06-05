

- - -

**Symfony\Component\DependencyInjection\TaggedContainerInterface**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/TaggedContainerInterface.php#L21" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\TaggedContainerInterface.php at line 21</a>

#Interface TaggedContainerInterface#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/ContainerInterface.md">ContainerInterface</a>
 &gt; **TaggedContainerInterface**




- - -

<p><strong>public  interface</strong> <span>TaggedContainerInterface</span>
<strong>extends</strong> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/ContainerInterface.md">ContainerInterface</a>

</p>

<div class="comment" id="overview_description"><p>TaggedContainerInterface is the interface implemented when a container knows how to deals with tags.</p></div>

<dl>
<dt>Author:</dt>
<dd>Fabien Potencier <fabien@symfony.com></dd>
<dt>Api.</dt>
</dl>


<hr />

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name"><a href="#findtaggedserviceids">findTaggedServiceIds</a>(string name)</p><p class="description">Returns service ids for a given tag.</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Symfony\Component\DependencyInjection\ContainerInterface</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/ContainerInterface.md#addscope">addScope</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/ContainerInterface.md#enterscope">enterScope</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/ContainerInterface.md#get">get</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/ContainerInterface.md#getparameter">getParameter</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/ContainerInterface.md#has">has</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/ContainerInterface.md#hasparameter">hasParameter</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/ContainerInterface.md#hasscope">hasScope</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/ContainerInterface.md#isscopeactive">isScopeActive</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/ContainerInterface.md#leavescope">leaveScope</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/ContainerInterface.md#setparameter">setParameter</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/TaggedContainerInterface.php#L32" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\TaggedContainerInterface.php at line 32</a>

<h3 id="findTaggedServiceIds()">findTaggedServiceIds</h3>
<span class='k'></span> <span class='nx'>array</span> <span class='nf'>findTaggedServiceIds</span> (string name)

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

