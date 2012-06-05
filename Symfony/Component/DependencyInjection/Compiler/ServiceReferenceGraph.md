

- - -

**Symfony\Component\DependencyInjection\Compiler\ServiceReferenceGraph**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/ServiceReferenceGraph.php#L22" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\ServiceReferenceGraph.php at line 22</a>

#Class ServiceReferenceGraph#

**ServiceReferenceGraph**




- - -

<p><strong>public  class</strong> <span>ServiceReferenceGraph</span></p>

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
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>()</p><p class="description">Constructor.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#hasnode">hasNode</a>(string id)</p><p class="description">Checks if the graph has a specific node.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Compiler/ServiceReferenceGraph.md#getNode>ServiceReferenceGraphNode</a></span></td>
<td class="description"><p class="name"><a href="#getnode">getNode</a>(string id)</p><p class="description">Gets a node by identifier.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name"><a href="#getnodes">getNodes</a>()</p><p class="description">Returns all nodes.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#clear">clear</a>()</p><p class="description">Clears all nodes.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#connect">connect</a>(string sourceId, string sourceValue, string destId, string destValue, string reference)</p><p class="description">Connects 2 nodes together in the Graph.</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/ServiceReferenceGraph.php#L29" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\ServiceReferenceGraph.php at line 29</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> ()

<div class="details">
<p>Constructor.</p>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/ServiceReferenceGraph.php#L39" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\ServiceReferenceGraph.php at line 39</a>

<h3 id="hasNode()">hasNode</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>hasNode</span> (string id)

<div class="details">
<p>Checks if the graph has a specific node.</p><dl>
<dt>Parameters:</dt>
<dd>id - Id to check</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/ServiceReferenceGraph.php#L51" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\ServiceReferenceGraph.php at line 51</a>

<h3 id="getNode()">getNode</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Compiler/ServiceReferenceGraph.md#getNode>ServiceReferenceGraphNode</a></span> <span class='nf'>getNode</span> (string id)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/ServiceReferenceGraph.php#L65" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\ServiceReferenceGraph.php at line 65</a>

<h3 id="getNodes()">getNodes</h3>
<span class='k'></span> <span class='nx'>array</span> <span class='nf'>getNodes</span> ()

<div class="details">
<p>Returns all nodes.</p><dl>
<dt>Returns:</dt>
<dd>An array of all ServiceReferenceGraphNode objects</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/ServiceReferenceGraph.php#L73" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\ServiceReferenceGraph.php at line 73</a>

<h3 id="clear()">clear</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>clear</span> ()

<div class="details">
<p>Clears all nodes.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/ServiceReferenceGraph.php#L87" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\ServiceReferenceGraph.php at line 87</a>

<h3 id="connect()">connect</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>connect</span> (string sourceId, string sourceValue, string destId, string destValue, string reference)

<div class="details">
<p>Connects 2 nodes together in the Graph.</p>
</div>

- - -

