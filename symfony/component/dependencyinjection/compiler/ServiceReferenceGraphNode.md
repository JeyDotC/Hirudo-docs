
- - -

**Symfony\Component\DependencyInjection\Compiler\ServiceReferenceGraphNode**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/symfony/component/dependencyinjection/compiler/servicereferencegraphnode.php#L24 class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\ServiceReferenceGraphNode.php at line 24</a>

#Class ServiceReferenceGraphNode#

**ServiceReferenceGraphNode**




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
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(string id, mixed value)</p><p class="description">Constructor.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#addinedge">addInEdge</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/symfony/component/dependencyinjection/compiler/servicereferencegraphedge.html">ServiceReferenceGraphEdge</a> edge)</p><p class="description">Adds an in edge to this node.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#addoutedge">addOutEdge</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/symfony/component/dependencyinjection/compiler/servicereferencegraphedge.html">ServiceReferenceGraphEdge</a> edge)</p><p class="description">Adds an out edge to this node.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>Boolean</span></td>
<td class="description"><p class="name"><a href="#isalias">isAlias</a>()</p><p class="description">Checks if the value of this node is an Alias.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>Boolean</span></td>
<td class="description"><p class="name"><a href="#isdefinition">isDefinition</a>()</p><p class="description">Checks if the value of this node is a Definition.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getid">getId</a>()</p><p class="description">Returns the identifier.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name"><a href="#getinedges">getInEdges</a>()</p><p class="description">Returns the in edges.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name"><a href="#getoutedges">getOutEdges</a>()</p><p class="description">Returns the out edges.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#getvalue">getValue</a>()</p><p class="description">Returns the value of this Node</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/symfony/component/dependencyinjection/compiler/servicereferencegraphnode.php#L37 class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\ServiceReferenceGraphNode.php at line 37</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (string id, mixed value)

<div class="details">
<p>Constructor.</p><dl>
<dt>Parameters:</dt>
<dd>id - The node identifier</dd>
<dd>value - The node value</dd>
</dl>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/symfony/component/dependencyinjection/compiler/servicereferencegraphnode.php#L50 class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\ServiceReferenceGraphNode.php at line 50</a>

<h3 id="addInEdge()">addInEdge</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>addInEdge</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/symfony/component/dependencyinjection/compiler/servicereferencegraphedge.html">ServiceReferenceGraphEdge</a> edge)

<div class="details">
<p>Adds an in edge to this node.</p></div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/symfony/component/dependencyinjection/compiler/servicereferencegraphnode.php#L60 class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\ServiceReferenceGraphNode.php at line 60</a>

<h3 id="addOutEdge()">addOutEdge</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>addOutEdge</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/symfony/component/dependencyinjection/compiler/servicereferencegraphedge.html">ServiceReferenceGraphEdge</a> edge)

<div class="details">
<p>Adds an out edge to this node.</p></div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/symfony/component/dependencyinjection/compiler/servicereferencegraphnode.php#L70 class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\ServiceReferenceGraphNode.php at line 70</a>

<h3 id="isAlias()">isAlias</h3>
<span class='k'></span> <span class='nx'>Boolean</span> <span class='nf'>isAlias</span> ()

<div class="details">
<p>Checks if the value of this node is an Alias.</p><dl>
<dt>Returns:</dt>
<dd>True if the value is an Alias instance</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/symfony/component/dependencyinjection/compiler/servicereferencegraphnode.php#L80 class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\ServiceReferenceGraphNode.php at line 80</a>

<h3 id="isDefinition()">isDefinition</h3>
<span class='k'></span> <span class='nx'>Boolean</span> <span class='nf'>isDefinition</span> ()

<div class="details">
<p>Checks if the value of this node is a Definition.</p><dl>
<dt>Returns:</dt>
<dd>True if the value is a Definition instance</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/symfony/component/dependencyinjection/compiler/servicereferencegraphnode.php#L90 class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\ServiceReferenceGraphNode.php at line 90</a>

<h3 id="getId()">getId</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getId</span> ()

<div class="details">
<p>Returns the identifier.</p></div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/symfony/component/dependencyinjection/compiler/servicereferencegraphnode.php#L100 class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\ServiceReferenceGraphNode.php at line 100</a>

<h3 id="getInEdges()">getInEdges</h3>
<span class='k'></span> <span class='nx'>array</span> <span class='nf'>getInEdges</span> ()

<div class="details">
<p>Returns the in edges.</p><dl>
<dt>Returns:</dt>
<dd>The in ServiceReferenceGraphEdge array</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/symfony/component/dependencyinjection/compiler/servicereferencegraphnode.php#L110 class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\ServiceReferenceGraphNode.php at line 110</a>

<h3 id="getOutEdges()">getOutEdges</h3>
<span class='k'></span> <span class='nx'>array</span> <span class='nf'>getOutEdges</span> ()

<div class="details">
<p>Returns the out edges.</p><dl>
<dt>Returns:</dt>
<dd>The out ServiceReferenceGraphEdge array</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/symfony/component/dependencyinjection/compiler/servicereferencegraphnode.php#L120 class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\ServiceReferenceGraphNode.php at line 120</a>

<h3 id="getValue()">getValue</h3>
<span class='k'></span> <span class='nx'>mixed</span> <span class='nf'>getValue</span> ()

<div class="details">
<p>Returns the value of this Node</p><dl>
<dt>Returns:</dt>
<dd>The value</dd>
</dl>
</div>

- - -

