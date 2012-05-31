- - -

**Symfony\Component\DependencyInjection\Compiler\ServiceReferenceGraphNode**
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/ServiceReferenceGraphNode.php.md#line24" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\ServiceReferenceGraphNode.php at line 24</a>

# Class ServiceReferenceGraphNode #

<pre class="tree">** ServiceReferenceGraphNode **\n</pre>

- - -

<p class="signature">public  class **ServiceReferenceGraphNode**</p>

<div class="comment" id="overview_description"><p>Represents a node in your service graph.</p><p>Value is typically a definition, or an alias.</p></div>

<dl>
<dt>Author:</dt>
<dd>Johannes M. Schmitt <schmittjoh@gmail.com></dd>
</dl>
- - -

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct()">__construct</a>(string id, mixed value)</p><p class="description">Constructor.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#addInEdge()">addInEdge</a>(<a href="../../../../symfony/component/dependencyinjection/compiler/servicereferencegraphedge.html">ServiceReferenceGraphEdge</a> edge)</p><p class="description">Adds an in edge to this node.</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#addOutEdge()">addOutEdge</a>(<a href="../../../../symfony/component/dependencyinjection/compiler/servicereferencegraphedge.html">ServiceReferenceGraphEdge</a> edge)</p><p class="description">Adds an out edge to this node.</p></td>
</tr>
<tr>
<td class="type"> Boolean</td>
<td class="description"><p class="name"><a href="#isAlias()">isAlias</a>()</p><p class="description">Checks if the value of this node is an Alias.</p></td>
</tr>
<tr>
<td class="type"> Boolean</td>
<td class="description"><p class="name"><a href="#isDefinition()">isDefinition</a>()</p><p class="description">Checks if the value of this node is a Definition.</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#getId()">getId</a>()</p><p class="description">Returns the identifier.</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#getInEdges()">getInEdges</a>()</p><p class="description">Returns the in edges.</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#getOutEdges()">getOutEdges</a>()</p><p class="description">Returns the out edges.</p></td>
</tr>
<tr>
<td class="type"> mixed</td>
<td class="description"><p class="name"><a href="#getValue()">getValue</a>()</p><p class="description">Returns the value of this Node</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/ServiceReferenceGraphNode.php.md#line37" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\ServiceReferenceGraphNode.php at line 37</a>

<h3 id="__construct()">__construct</h3>
```php
public  void **__construct**(string id, mixed value)```
<div class="details">
<p>Constructor.</p><dl>
<dt>Parameters:</dt>
<dd>id - The node identifier</dd>
<dd>value - The node value</dd>
</dl>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/ServiceReferenceGraphNode.php.md#line50" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\ServiceReferenceGraphNode.php at line 50</a>

<h3 id="addInEdge()">addInEdge</h3>
```php
public  void **addInEdge**(<a href="../../../../symfony/component/dependencyinjection/compiler/servicereferencegraphedge.html">ServiceReferenceGraphEdge</a> edge)```
<div class="details">
<p>Adds an in edge to this node.</p></div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/ServiceReferenceGraphNode.php.md#line60" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\ServiceReferenceGraphNode.php at line 60</a>

<h3 id="addOutEdge()">addOutEdge</h3>
```php
public  void **addOutEdge**(<a href="../../../../symfony/component/dependencyinjection/compiler/servicereferencegraphedge.html">ServiceReferenceGraphEdge</a> edge)```
<div class="details">
<p>Adds an out edge to this node.</p></div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/ServiceReferenceGraphNode.php.md#line70" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\ServiceReferenceGraphNode.php at line 70</a>

<h3 id="isAlias()">isAlias</h3>
```php
public  Boolean **isAlias**()```
<div class="details">
<p>Checks if the value of this node is an Alias.</p><dl>
<dt>Returns:</dt>
<dd>True if the value is an Alias instance</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/ServiceReferenceGraphNode.php.md#line80" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\ServiceReferenceGraphNode.php at line 80</a>

<h3 id="isDefinition()">isDefinition</h3>
```php
public  Boolean **isDefinition**()```
<div class="details">
<p>Checks if the value of this node is a Definition.</p><dl>
<dt>Returns:</dt>
<dd>True if the value is a Definition instance</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/ServiceReferenceGraphNode.php.md#line90" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\ServiceReferenceGraphNode.php at line 90</a>

<h3 id="getId()">getId</h3>
```php
public  string **getId**()```
<div class="details">
<p>Returns the identifier.</p></div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/ServiceReferenceGraphNode.php.md#line100" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\ServiceReferenceGraphNode.php at line 100</a>

<h3 id="getInEdges()">getInEdges</h3>
```php
public  array **getInEdges**()```
<div class="details">
<p>Returns the in edges.</p><dl>
<dt>Returns:</dt>
<dd>The in ServiceReferenceGraphEdge array</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/ServiceReferenceGraphNode.php.md#line110" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\ServiceReferenceGraphNode.php at line 110</a>

<h3 id="getOutEdges()">getOutEdges</h3>
```php
public  array **getOutEdges**()```
<div class="details">
<p>Returns the out edges.</p><dl>
<dt>Returns:</dt>
<dd>The out ServiceReferenceGraphEdge array</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/ServiceReferenceGraphNode.php.md#line120" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\ServiceReferenceGraphNode.php at line 120</a>

<h3 id="getValue()">getValue</h3>
```php
public  mixed **getValue**()```
<div class="details">
<p>Returns the value of this Node</p><dl>
<dt>Returns:</dt>
<dd>The value</dd>
</dl>
</div>

- - -

