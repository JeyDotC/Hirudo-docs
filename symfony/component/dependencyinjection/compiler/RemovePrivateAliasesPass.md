
- - -

**Symfony\Component\DependencyInjection\Compiler\RemovePrivateAliasesPass**
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\RemovePrivateAliasesPass.php at line 23</div>
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
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#process">process</a>(<a href="../../../../symfony/component/dependencyinjection/containerbuilder.html">ContainerBuilder</a> container)</p><p class="description">Removes private aliases from the ContainerBuilder</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\RemovePrivateAliasesPass.php at line 30</div>
<h3 id="process()">process</h3>

public  void **process** (<a href="../../../../symfony/component/dependencyinjection/containerbuilder.html">ContainerBuilder</a> container)<div class="details">
<p>Removes private aliases from the ContainerBuilder</p></div>

- - -

