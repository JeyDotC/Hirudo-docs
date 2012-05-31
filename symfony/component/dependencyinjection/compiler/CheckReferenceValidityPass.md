
- - -

**Symfony\Component\DependencyInjection\Compiler\CheckReferenceValidityPass**
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\CheckReferenceValidityPass.php at line 31</div>
#Class CheckReferenceValidityPass#

**CheckReferenceValidityPass**


- - -

<p class="signature">public  class **CheckReferenceValidityPass**</p>

<div class="comment" id="overview_description"><p>Checks the validity of references</p><p>The following checks are performed by this pass:</p>
<ul>
<li>target definitions are not abstract</li>
<li>target definitions are of equal or wider scope</li>
</ul>
<p>- target definitions are in the same scope hierarchy</p></div>

<dl>
<dt>Author:</dt>
<dd>Johannes M. Schmitt <schmittjoh@gmail.com></dd>
</dl>

- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#process">process</a>(<a href="../../../../symfony/component/dependencyinjection/containerbuilder.html">ContainerBuilder</a> container)</p><p class="description">Processes the ContainerBuilder to validate References.</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\CheckReferenceValidityPass.php at line 45</div>
<h3 id="process()">process</h3>

public  void **process** (<a href="../../../../symfony/component/dependencyinjection/containerbuilder.html">ContainerBuilder</a> container)<div class="details">
<p>Processes the ContainerBuilder to validate References.</p></div>

- - -

