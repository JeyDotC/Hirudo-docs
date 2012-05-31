- - -

**Symfony\Component\DependencyInjection\Compiler\ResolveDefinitionTemplatesPass**
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\ResolveDefinitionTemplatesPass.php at line 24</div>
#Class ResolveDefinitionTemplatesPass#

**ResolveDefinitionTemplatesPass**


<dl>
<dt>All Implemented Interfaces:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/compiler/compilerpassinterface.html">CompilerPassInterface</a> </dd>
</dl>

- - -

<p class="signature">public  class **ResolveDefinitionTemplatesPass**</p>

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
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#process">process</a>(<a href="../../../../symfony/component/dependencyinjection/containerbuilder.html">ContainerBuilder</a> container)</p><p class="description">Process the ContainerBuilder to replace DefinitionDecorator instances with their real Definition instances.</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\ResolveDefinitionTemplatesPass.php at line 35</div>
<h3 id="process()">process</h3>
```php
public  void **process**(<a href="../../../../symfony/component/dependencyinjection/containerbuilder.html">ContainerBuilder</a> container)```
<div class="details">
<p>Process the ContainerBuilder to replace DefinitionDecorator instances with their real Definition instances.</p></div>

- - -

