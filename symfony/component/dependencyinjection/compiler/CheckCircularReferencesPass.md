- - -

**Symfony\Component\DependencyInjection\Compiler\CheckCircularReferencesPass**
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\CheckCircularReferencesPass.php at line 27</div>
#Class CheckCircularReferencesPass#

**CheckCircularReferencesPass**


- - -

<p class="signature">public  class **CheckCircularReferencesPass**</p>

<div class="comment" id="overview_description"><p>Checks your services for circular references</p><p>References from method calls are ignored since we might be able to resolve
these references depending on the order in which services are called.</p><p>Circular reference from method calls will only be detected at run-time.</p></div>

<dl>
<dt>Author:</dt>
<dd>Johannes M. Schmitt <schmittjoh@gmail.com></dd>
</dl>
- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#process">process</a>(<a href="../../../../symfony/component/dependencyinjection/containerbuilder.html">ContainerBuilder</a> container)</p><p class="description">Checks the ContainerBuilder object for circular references.</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\CheckCircularReferencesPass.php at line 37</div>
<h3 id="process()">process</h3>

```php
public  void **process**(<a href="../../../../symfony/component/dependencyinjection/containerbuilder.html">ContainerBuilder</a> container)
```
<div class="details">
<p>Checks the ContainerBuilder object for circular references.</p><dl>
<dt>Parameters:</dt>
<dd>container - The ContainerBuilder instances</dd>
</dl>
</div>

- - -

