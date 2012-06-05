

- - -

**Symfony\Component\DependencyInjection\Compiler\CheckCircularReferencesPass**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/CheckCircularReferencesPass.php#L27" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\CheckCircularReferencesPass.php at line 27</a>

#Class CheckCircularReferencesPass#

**CheckCircularReferencesPass**




- - -

<p><strong>public  class</strong> <span>CheckCircularReferencesPass</span></p>

<div class="comment" id="overview_description"><p>Checks your services for circular references</p><p>References from method calls are ignored since we might be able to resolve
these references depending on the order in which services are called.</p><p>Circular reference from method calls will only be detected at run-time.</p></div>

<dl>
<dt>Author:</dt>
<dd>Johannes M. Schmitt <schmittjoh@gmail.com></dd>
</dl>


<hr />

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#process">process</a>(<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/ContainerBuilder.md">ContainerBuilder</a> container)</p><p class="description">Checks the ContainerBuilder object for circular references.</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/CheckCircularReferencesPass.php#L37" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\CheckCircularReferencesPass.php at line 37</a>

<h3 id="process()">process</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>process</span> (<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/ContainerBuilder.md">ContainerBuilder</a> container)

<div class="details">
<p>Checks the ContainerBuilder object for circular references.</p><dl>
<dt>Parameters:</dt>
<dd>container - The ContainerBuilder instances</dd>
</dl>

</div>

- - -

