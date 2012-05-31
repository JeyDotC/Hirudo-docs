- - -

**Symfony\Component\DependencyInjection\Compiler\ResolveReferencesToAliasesPass**
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\ResolveReferencesToAliasesPass.php at line 23</div>
#Class ResolveReferencesToAliasesPass#

**ResolveReferencesToAliasesPass**


<dl>
<dt>All Implemented Interfaces:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/compiler/compilerpassinterface.html">CompilerPassInterface</a> </dd>
</dl>

- - -

<p class="signature">public  class **ResolveReferencesToAliasesPass**</p>

<div class="comment" id="overview_description"><p>Replaces all references to aliases with references to the actual service.</p></div>

<dl>
<dt>Author:</dt>
<dd>Johannes M. Schmitt <schmittjoh@gmail.com></dd>
</dl>
- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#process">process</a>(<a href="../../../../symfony/component/dependencyinjection/containerbuilder.html">ContainerBuilder</a> container)</p><p class="description">Processes the ContainerBuilder to replace references to aliases with actual service references.</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\ResolveReferencesToAliasesPass.php at line 32</div>
<h3 id="process()">process</h3>
```php
public  void **process**(<a href="../../../../symfony/component/dependencyinjection/containerbuilder.html">ContainerBuilder</a> container)```
<div class="details">
<p>Processes the ContainerBuilder to replace references to aliases with actual service references.</p></div>

- - -

