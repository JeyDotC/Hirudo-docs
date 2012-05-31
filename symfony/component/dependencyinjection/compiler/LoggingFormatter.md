- - -

**Symfony\Component\DependencyInjection\Compiler\LoggingFormatter**
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\LoggingFormatter.php at line 21</div>
#Class LoggingFormatter#

**LoggingFormatter**


- - -

<p class="signature">public  class **LoggingFormatter**</p>

<div class="comment" id="overview_description"><p>Used to format logging messages during the compilation.</p></div>

<dl>
<dt>Author:</dt>
<dd>Johannes M. Schmitt <schmittjoh@gmail.com></dd>
</dl>
- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#formatRemoveService">formatRemoveService</a>(<a href="../../../../symfony/component/dependencyinjection/compiler/compilerpassinterface.html">CompilerPassInterface</a> pass, mixed id, mixed reason)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#formatInlineService">formatInlineService</a>(<a href="../../../../symfony/component/dependencyinjection/compiler/compilerpassinterface.html">CompilerPassInterface</a> pass, mixed id, mixed target)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#formatUpdateReference">formatUpdateReference</a>(<a href="../../../../symfony/component/dependencyinjection/compiler/compilerpassinterface.html">CompilerPassInterface</a> pass, mixed serviceId, mixed oldDestId, mixed newDestId)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#formatResolveInheritance">formatResolveInheritance</a>(<a href="../../../../symfony/component/dependencyinjection/compiler/compilerpassinterface.html">CompilerPassInterface</a> pass, mixed childId, mixed parentId)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#format">format</a>(<a href="../../../../symfony/component/dependencyinjection/compiler/compilerpassinterface.html">CompilerPassInterface</a> pass, mixed message)</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\LoggingFormatter.php at line 23</div>
<h3 id="formatRemoveService()">formatRemoveService</h3>
```php
public  void **formatRemoveService**(<a href="../../../../symfony/component/dependencyinjection/compiler/compilerpassinterface.html">CompilerPassInterface</a> pass, mixed id, mixed reason)```
<div class="details">
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\LoggingFormatter.php at line 28</div>
<h3 id="formatInlineService()">formatInlineService</h3>
```php
public  void **formatInlineService**(<a href="../../../../symfony/component/dependencyinjection/compiler/compilerpassinterface.html">CompilerPassInterface</a> pass, mixed id, mixed target)```
<div class="details">
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\LoggingFormatter.php at line 33</div>
<h3 id="formatUpdateReference()">formatUpdateReference</h3>
```php
public  void **formatUpdateReference**(<a href="../../../../symfony/component/dependencyinjection/compiler/compilerpassinterface.html">CompilerPassInterface</a> pass, mixed serviceId, mixed oldDestId, mixed newDestId)```
<div class="details">
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\LoggingFormatter.php at line 38</div>
<h3 id="formatResolveInheritance()">formatResolveInheritance</h3>
```php
public  void **formatResolveInheritance**(<a href="../../../../symfony/component/dependencyinjection/compiler/compilerpassinterface.html">CompilerPassInterface</a> pass, mixed childId, mixed parentId)```
<div class="details">
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\LoggingFormatter.php at line 43</div>
<h3 id="format()">format</h3>
```php
public  void **format**(<a href="../../../../symfony/component/dependencyinjection/compiler/compilerpassinterface.html">CompilerPassInterface</a> pass, mixed message)```
<div class="details">
</div>

- - -

