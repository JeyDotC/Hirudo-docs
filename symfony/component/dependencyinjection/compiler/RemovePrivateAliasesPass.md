

- - -

**Symfony\Component\DependencyInjection\Compiler\RemovePrivateAliasesPass**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/RemovePrivateAliasesPass.php#L23" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\RemovePrivateAliasesPass.php at line 23</a>

#Class RemovePrivateAliasesPass#

**RemovePrivateAliasesPass**


<dl>
<dt>All Implemented Interfaces:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/compiler/compilerpassinterface.md">CompilerPassInterface</a> </dd>
</dl>



- - -

<p class="signature"><span class='k'>public  class</span> <span class='nx'>RemovePrivateAliasesPass</span></p>

<div class="comment" id="overview_description"><p>Remove private aliases from the container. They were only used to establish
dependencies between services, and these dependencies have been resolved in
one of the previous passes.</p></div>

<dl>
<dt>Author:</dt>
<dd>Johannes M. Schmitt <schmittjoh@gmail.com></dd>
</dl>


- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#process">process</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/symfony/component/dependencyinjection/containerbuilder.md">ContainerBuilder</a> container)</p><p class="description">Removes private aliases from the ContainerBuilder</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/RemovePrivateAliasesPass.php#L30" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\RemovePrivateAliasesPass.php at line 30</a>

<h3 id="process()">process</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>process</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/symfony/component/dependencyinjection/containerbuilder.md">ContainerBuilder</a> container)

<div class="details">
<p>Removes private aliases from the ContainerBuilder</p>
</div>

- - -

