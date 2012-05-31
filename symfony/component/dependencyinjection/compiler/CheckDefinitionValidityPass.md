
- - -

**Symfony\Component\DependencyInjection\Compiler\CheckDefinitionValidityPass**
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\CheckDefinitionValidityPass.php at line 30</div>
#Class CheckDefinitionValidityPass#

**CheckDefinitionValidityPass**


- - -

<p class="signature">public  class **CheckDefinitionValidityPass**</p>

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

- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#process">process</a>(<a href="../../../../symfony/component/dependencyinjection/containerbuilder.html">ContainerBuilder</a> container)</p><p class="description">Processes the ContainerBuilder to validate the Definition.</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\CheckDefinitionValidityPass.php at line 38</div>
<h3 id="process()">process</h3>

public  void **process** (<a href="../../../../symfony/component/dependencyinjection/containerbuilder.html">ContainerBuilder</a> container)<div class="details">
<p>Processes the ContainerBuilder to validate the Definition.</p><dl>
<dt>Throws:</dt>
<dd><a href="../../../../symfony/component/dependencyinjection/exception/runtimeexception.html">\RuntimeException</a> - When the Definition is invalid</dd>
</dl>
</div>

- - -

