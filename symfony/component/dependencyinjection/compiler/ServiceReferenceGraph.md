- - -

**Symfony\Component\DependencyInjection\Compiler\ServiceReferenceGraph**
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\ServiceReferenceGraph.php at line 22</div>
#Class ServiceReferenceGraph#

**ServiceReferenceGraph**


- - -

<p class="signature">public  class **ServiceReferenceGraph**</p>

<div class="comment" id="overview_description"><p>This is a directed graph of your services.</p><p>This information can be used by your compiler passes instead of collecting
it themselves which improves performance quite a lot.</p></div>

<dl>
<dt>Author:</dt>
<dd>Johannes M. Schmitt <schmittjoh@gmail.com></dd>
</dl>
- - -

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>()</p><p class="description">Constructor.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#hasNode">hasNode</a>(string id)</p><p class="description">Checks if the graph has a specific node.</p></td>
</tr>
<tr>
<td class="type"> <a href="../../../../symfony/component/dependencyinjection/compiler/servicereferencegraphnode.html">ServiceReferenceGraphNode</a></td>
<td class="description"><p class="name"><a href="#getNode">getNode</a>(string id)</p><p class="description">Gets a node by identifier.</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#getNodes">getNodes</a>()</p><p class="description">Returns all nodes.</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#clear">clear</a>()</p><p class="description">Clears all nodes.</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#connect">connect</a>(string sourceId, string sourceValue, string destId, string destValue, string reference)</p><p class="description">Connects 2 nodes together in the Graph.</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\ServiceReferenceGraph.php at line 29</div>
<h3 id="__construct()">__construct</h3>

```php
public  void **__construct**()
```
<div class="details">
<p>Constructor.</p></div>

- - -

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\ServiceReferenceGraph.php at line 39</div>
<h3 id="hasNode()">hasNode</h3>

```php
public  void **hasNode**(string id)
```
<div class="details">
<p>Checks if the graph has a specific node.</p><dl>
<dt>Parameters:</dt>
<dd>id - Id to check</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\ServiceReferenceGraph.php at line 51</div>
<h3 id="getNode()">getNode</h3>

```php
public  <a href="../../../../symfony/component/dependencyinjection/compiler/servicereferencegraphnode.html">ServiceReferenceGraphNode</a> **getNode**(string id)
```
<div class="details">
<p>Gets a node by identifier.</p><dl>
<dt>Parameters:</dt>
<dd>id - The id to retrieve</dd>
<dt>Returns:</dt>
<dd>The node matching the supplied identifier</dd>
<dt>Throws:</dt>
<dd><a href="../../../../symfony/component/dependencyinjection/exception/invalidargumentexception.html">\InvalidArgumentException</a></dd>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\ServiceReferenceGraph.php at line 65</div>
<h3 id="getNodes()">getNodes</h3>

```php
public  array **getNodes**()
```
<div class="details">
<p>Returns all nodes.</p><dl>
<dt>Returns:</dt>
<dd>An array of all ServiceReferenceGraphNode objects</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\ServiceReferenceGraph.php at line 73</div>
<h3 id="clear()">clear</h3>

```php
public  void **clear**()
```
<div class="details">
<p>Clears all nodes.</p></div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\ServiceReferenceGraph.php at line 87</div>
<h3 id="connect()">connect</h3>

```php
public  void **connect**(string sourceId, string sourceValue, string destId, string destValue, string reference)
```
<div class="details">
<p>Connects 2 nodes together in the Graph.</p></div>

- - -

