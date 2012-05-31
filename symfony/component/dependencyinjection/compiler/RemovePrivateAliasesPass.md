
- - -

**Symfony\Component\DependencyInjection\Compiler\RemovePrivateAliasesPass**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/symfony/component/dependencyinjection/compiler/removeprivatealiasespass.php#L23 class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\RemovePrivateAliasesPass.php at line 23</a>

#Class RemovePrivateAliasesPass#

**RemovePrivateAliasesPass**


<dl>
<dt>All Implemented Interfaces:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/compiler/compilerpassinterface.html">CompilerPassInterface</a> </dd>
</dl>



- - -

<p class="signature">public  class **RemovePrivateAliasesPass**</p>

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
<td class="description"><p class="name"><a href="#process">process</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/symfony/component/dependencyinjection/containerbuilder.html">ContainerBuilder</a> container)</p><p class="description">Removes private aliases from the ContainerBuilder</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/symfony/component/dependencyinjection/compiler/removeprivatealiasespass.php#L30 class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\RemovePrivateAliasesPass.php at line 30</a>

<h3 id="process()">process</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>process</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/symfony/component/dependencyinjection/containerbuilder.html">ContainerBuilder</a> container)

<div class="details">
<p>Removes private aliases from the ContainerBuilder</p></div>

- - -

