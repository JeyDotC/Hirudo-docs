- - -

**Symfony\Component\DependencyInjection\Compiler\ServiceReferenceGraphEdge**
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\ServiceReferenceGraphEdge.php at line 21</div>
#Class ServiceReferenceGraphEdge#

**ServiceReferenceGraphEdge**


- - -

<p class="signature">public  class **ServiceReferenceGraphEdge**</p>

<div class="comment" id="overview_description"><p>Represents an edge in your service graph.</p><p>Value is typically a reference.</p></div>

<dl>
<dt>Author:</dt>
<dd>Johannes M. Schmitt <schmittjoh@gmail.com></dd>
</dl>
- - -

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(<a href="../../../../symfony/component/dependencyinjection/compiler/servicereferencegraphnode.html">ServiceReferenceGraphNode</a> sourceNode, <a href="../../../../symfony/component/dependencyinjection/compiler/servicereferencegraphnode.html">ServiceReferenceGraphNode</a> destNode, string value)</p><p class="description">Constructor.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> <a href="../../../../symfony/component/dependencyinjection/compiler/servicereferencegraphnode.html">ServiceReferenceGraphNode</a></td>
<td class="description"><p class="name"><a href="#getValue">getValue</a>()</p><p class="description">Returns the value of the edge</p></td>
</tr>
<tr>
<td class="type"> <a href="../../../../symfony/component/dependencyinjection/compiler/servicereferencegraphnode.html">ServiceReferenceGraphNode</a></td>
<td class="description"><p class="name"><a href="#getSourceNode">getSourceNode</a>()</p><p class="description">Returns the source node</p></td>
</tr>
<tr>
<td class="type"> <a href="../../../../symfony/component/dependencyinjection/compiler/servicereferencegraphnode.html">ServiceReferenceGraphNode</a></td>
<td class="description"><p class="name"><a href="#getDestNode">getDestNode</a>()</p><p class="description">Returns the destination node</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\ServiceReferenceGraphEdge.php at line 34</div>
<h3 id="__construct()">__construct</h3>
```php
public  void **__construct**(<a href="../../../../symfony/component/dependencyinjection/compiler/servicereferencegraphnode.html">ServiceReferenceGraphNode</a> sourceNode, <a href="../../../../symfony/component/dependencyinjection/compiler/servicereferencegraphnode.html">ServiceReferenceGraphNode</a> destNode, string value)```
<div class="details">
<p>Constructor.</p></div>

- - -

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\ServiceReferenceGraphEdge.php at line 46</div>
<h3 id="getValue()">getValue</h3>
```php
public  <a href="../../../../symfony/component/dependencyinjection/compiler/servicereferencegraphnode.html">ServiceReferenceGraphNode</a> **getValue**()```
<div class="details">
<p>Returns the value of the edge</p></div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\ServiceReferenceGraphEdge.php at line 56</div>
<h3 id="getSourceNode()">getSourceNode</h3>
```php
public  <a href="../../../../symfony/component/dependencyinjection/compiler/servicereferencegraphnode.html">ServiceReferenceGraphNode</a> **getSourceNode**()```
<div class="details">
<p>Returns the source node</p></div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\ServiceReferenceGraphEdge.php at line 66</div>
<h3 id="getDestNode()">getDestNode</h3>
```php
public  <a href="../../../../symfony/component/dependencyinjection/compiler/servicereferencegraphnode.html">ServiceReferenceGraphNode</a> **getDestNode**()```
<div class="details">
<p>Returns the destination node</p></div>

- - -

