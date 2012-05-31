
- - -

**Symfony\Component\DependencyInjection\Compiler\AnalyzeServiceReferencesPass**
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\AnalyzeServiceReferencesPass.php at line 27</div>
#Class AnalyzeServiceReferencesPass#

**AnalyzeServiceReferencesPass**


- - -

<p class="signature">public  class **AnalyzeServiceReferencesPass**</p>

<div class="comment" id="overview_description"><p>Run this pass before passes that need to know more about the relation of
your services.</p><p>This class will populate the ServiceReferenceGraph with information. You can
retrieve the graph in other passes from the compiler.</p></div>

<dl>
<dt>Author:</dt>
<dd>Johannes M. Schmitt <schmittjoh@gmail.com></dd>
</dl>

- - -

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(Boolean onlyConstructorArguments)</p><p class="description">Constructor.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#setrepeatedpass">setRepeatedPass</a>(<a href="../../../../symfony/component/dependencyinjection/compiler/repeatedpass.html">RepeatedPass</a> repeatedPass)</p><p class="description"></p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#process">process</a>(<a href="../../../../symfony/component/dependencyinjection/containerbuilder.html">ContainerBuilder</a> container)</p><p class="description">Processes a ContainerBuilder object to populate the service reference graph.</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\AnalyzeServiceReferencesPass.php at line 41</div>
<h3 id="__construct()">__construct</h3>

```php
public  void **__construct**(Boolean onlyConstructorArguments)
```
<div class="details">
<p>Constructor.</p><dl>
<dt>Parameters:</dt>
<dd>onlyConstructorArguments - Sets this Service Reference pass to ignore method calls</dd>
</dl>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\AnalyzeServiceReferencesPass.php at line 49</div>
<h3 id="setRepeatedPass()">setRepeatedPass</h3>

public  void **setRepeatedPass** (<a href="../../../../symfony/component/dependencyinjection/compiler/repeatedpass.html">RepeatedPass</a> repeatedPass)<div class="details">
<p></p></div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\AnalyzeServiceReferencesPass.php at line 58</div>
<h3 id="process()">process</h3>

public  void **process** (<a href="../../../../symfony/component/dependencyinjection/containerbuilder.html">ContainerBuilder</a> container)<div class="details">
<p>Processes a ContainerBuilder object to populate the service reference graph.</p></div>

- - -

