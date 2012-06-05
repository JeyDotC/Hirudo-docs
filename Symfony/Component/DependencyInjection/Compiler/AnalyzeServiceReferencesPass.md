

- - -

**Symfony\Component\DependencyInjection\Compiler\AnalyzeServiceReferencesPass**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/AnalyzeServiceReferencesPass.php#L27" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\AnalyzeServiceReferencesPass.php at line 27</a>

#Class AnalyzeServiceReferencesPass#

**AnalyzeServiceReferencesPass**




- - -

<p><strong>public  class</strong> <span>AnalyzeServiceReferencesPass</span></p>

<div class="comment" id="overview_description"><p>Run this pass before passes that need to know more about the relation of
your services.</p><p>This class will populate the ServiceReferenceGraph with information. You can
retrieve the graph in other passes from the compiler.</p></div>

<dl>
<dt>Author:</dt>
<dd>Johannes M. Schmitt <schmittjoh@gmail.com></dd>
</dl>


<hr />

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(Boolean onlyConstructorArguments)</p><p class="description">Constructor.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setrepeatedpass">setRepeatedPass</a>(<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Compiler/RepeatedPass.md">RepeatedPass</a> repeatedPass)</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#process">process</a>(<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/ContainerBuilder.md">ContainerBuilder</a> container)</p><p class="description">Processes a ContainerBuilder object to populate the service reference graph.</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/AnalyzeServiceReferencesPass.php#L41" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\AnalyzeServiceReferencesPass.php at line 41</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (Boolean onlyConstructorArguments)

<div class="details">
<p>Constructor.</p><dl>
<dt>Parameters:</dt>
<dd>onlyConstructorArguments - Sets this Service Reference pass to ignore method calls</dd>
</dl>

</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/AnalyzeServiceReferencesPass.php#L49" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\AnalyzeServiceReferencesPass.php at line 49</a>

<h3 id="setRepeatedPass()">setRepeatedPass</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setRepeatedPass</span> (<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Compiler/RepeatedPass.md">RepeatedPass</a> repeatedPass)

<div class="details">
<p></p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/AnalyzeServiceReferencesPass.php#L58" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\AnalyzeServiceReferencesPass.php at line 58</a>

<h3 id="process()">process</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>process</span> (<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/ContainerBuilder.md">ContainerBuilder</a> container)

<div class="details">
<p>Processes a ContainerBuilder object to populate the service reference graph.</p>
</div>

- - -

