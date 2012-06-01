

- - -

**Symfony\Component\DependencyInjection\Compiler\ResolveDefinitionTemplatesPass**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/ResolveDefinitionTemplatesPass.php#L24" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\ResolveDefinitionTemplatesPass.php at line 24</a>

#Class ResolveDefinitionTemplatesPass#

**ResolveDefinitionTemplatesPass**


<dl>
<dt>All Implemented Interfaces:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/compiler/compilerpassinterface.md">CompilerPassInterface</a> </dd>
</dl>



- - -

<p class="signature"><span class='k'>public  class</span> <span class='nx'>ResolveDefinitionTemplatesPass</span></p>

<div class="comment" id="overview_description"><p>This replaces all DefinitionDecorator instances with their equivalent fully
merged Definition instance.</p></div>

<dl>
<dt>Author:</dt>
<dd>Johannes M. Schmitt <schmittjoh@gmail.com></dd>
</dl>


- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#process">process</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/symfony/component/dependencyinjection/containerbuilder.md">ContainerBuilder</a> container)</p><p class="description">Process the ContainerBuilder to replace DefinitionDecorator instances with their real Definition instances.</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/ResolveDefinitionTemplatesPass.php#L35" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\ResolveDefinitionTemplatesPass.php at line 35</a>

<h3 id="process()">process</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>process</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/symfony/component/dependencyinjection/containerbuilder.md">ContainerBuilder</a> container)

<div class="details">
<p>Process the ContainerBuilder to replace DefinitionDecorator instances with their real Definition instances.</p>
</div>

- - -

