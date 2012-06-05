

- - -

**Symfony\Component\DependencyInjection\Compiler\CheckDefinitionValidityPass**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/CheckDefinitionValidityPass.php#L30" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\CheckDefinitionValidityPass.php at line 30</a>

#Class CheckDefinitionValidityPass#

**CheckDefinitionValidityPass**




- - -

<p><strong>public  class</strong> <span>CheckDefinitionValidityPass</span></p>

<div class="comment" id="overview_description"><p>This pass validates each definition individually only taking the information
into account which is contained in the definition itself.</p><p>Later passes can rely on the following, and specifically do not need to
perform these checks themselves:</p>
<ul>
<li>non synthetic, non abstract services always have a class set</li>
<li>synthetic services are always public</li>
</ul>
<p>- synthetic services are always of non-prototype scope</p></div>

<dl>
<dt>Author:</dt>
<dd>Johannes M. Schmitt <schmittjoh@gmail.com></dd>
</dl>


<hr />

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#process">process</a>(<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/ContainerBuilder.md">ContainerBuilder</a> container)</p><p class="description">Processes the ContainerBuilder to validate the Definition.</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/CheckDefinitionValidityPass.php#L38" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\CheckDefinitionValidityPass.php at line 38</a>

<h3 id="process()">process</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>process</span> (<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/ContainerBuilder.md">ContainerBuilder</a> container)

<div class="details">
<p>Processes the ContainerBuilder to validate the Definition.</p><dl>
<dt>Throws:</dt>
<dd><a href="../../../../symfony/component/dependencyinjection/exception/runtimeexception.html">\RuntimeException</a> - When the Definition is invalid</dd>
</dl>

</div>

- - -

