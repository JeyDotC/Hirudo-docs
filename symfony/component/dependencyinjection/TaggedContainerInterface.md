

- - -

**Symfony\Component\DependencyInjection\TaggedContainerInterface**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/TaggedContainerInterface.php#L21" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\TaggedContainerInterface.php at line 21</a>

#Interface TaggedContainerInterface#

<a href="">ContainerInterface</a>
    * **TaggedContainerInterface**




- - -

<p class="signature"><span class='k'>public  interface</span> <span class='nx'>TaggedContainerInterface</span>
extends <a href="">ContainerInterface</a>

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
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name"><a href="#findtaggedserviceids">findTaggedServiceIds</a>(string name)</p><p class="description">Returns service ids for a given tag.</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Symfony\Component\DependencyInjection\ContainerInterface</th></tr>
<tr><td><a href="">addScope</a>, <a href="">enterScope</a>, <a href="">get</a>, <a href="">getParameter</a>, <a href="">has</a>, <a href="">hasParameter</a>, <a href="">hasScope</a>, <a href="">isScopeActive</a>, <a href="">leaveScope</a>, <a href="">setParameter</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/TaggedContainerInterface.php#L32" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\TaggedContainerInterface.php at line 32</a>

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

