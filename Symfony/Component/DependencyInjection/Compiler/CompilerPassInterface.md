

- - -

**Symfony\Component\DependencyInjection\Compiler\CompilerPassInterface**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/CompilerPassInterface.php#L23" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\CompilerPassInterface.php at line 23</a>

#Interface CompilerPassInterface#

**CompilerPassInterface**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Compiler/RepeatablePassInterface.md">RepeatablePassInterface</a> </dd>
</dl>



- - -

<p><strong>public  interface</strong> <span>CompilerPassInterface</span></p>

<div class="comment" id="overview_description"><p>Interface that must be implemented by compilation passes</p></div>

<dl>
<dt>Author:</dt>
<dd>Johannes M. Schmitt <schmittjoh@gmail.com></dd>
<dt>Api.</dt>
</dl>


<hr />

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#process">process</a>(<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/ContainerBuilder.md">ContainerBuilder</a> container)</p><p class="description">You can modify the container here before it is dumped to PHP code.</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/CompilerPassInterface.php#L33" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\CompilerPassInterface.php at line 33</a>

<h3 id="process()">process</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>process</span> (<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/ContainerBuilder.md">ContainerBuilder</a> container)

<div class="details">
<p>You can modify the container here before it is dumped to PHP code.</p><dl>
<dt>Api.</dt>
</dl>

</div>

- - -

