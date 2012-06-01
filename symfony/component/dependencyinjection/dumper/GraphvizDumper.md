

- - -

**Symfony\Component\DependencyInjection\Dumper\GraphvizDumper**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Dumper/GraphvizDumper.php#L29" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Dumper\GraphvizDumper.php at line 29</a>

#Class GraphvizDumper#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/dumper/dumper.md">Dumper</a>
    * **GraphvizDumper**




- - -

<p class="signature"><span class='k'>public  class</span> <span class='nx'>GraphvizDumper</span>
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/dumper/dumper.md">Dumper</a>

</p>

<div class="comment" id="overview_description"><p>GraphvizDumper dumps a service container as a graphviz file.</p><p>You can convert the generated dot file with the dot utility (http://www.graphviz.org/):</p><p>dot -Tpng container.dot > foo.png</p></div>

<dl>
<dt>Author:</dt>
<dd>Fabien Potencier <fabien@symfony.com></dd>
<dt>Api.</dt>
</dl>


- - -

<table class="inherit">
<tr><th colspan="2">Fields inherited from Symfony\Component\DependencyInjection\Dumper\Dumper</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/dumper/dumper.md">container</a></td></tr></table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#dump">dump</a>(array options)</p><p class="description">Dumps the service container as a graphviz graph.
</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Symfony\Component\DependencyInjection\Dumper\Dumper</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/dumper/dumper.md">__construct</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Dumper/GraphvizDumper.php#L51" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Dumper\GraphvizDumper.php at line 51</a>

<h3 id="dump()">dump</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>dump</span> (array options)

<div class="details">
<p>Dumps the service container as a graphviz graph.</p><p>Available options:</p><p>* graph: The default options for the whole graph
* node: The default options for nodes
* edge: The default options for edges
* node.instance: The default options for services that are defined directly by object instances
* node.definition: The default options for services that are defined via service definition instances
* node.missing: The default options for missing services</p><dl>
<dt>Parameters:</dt>
<dd>options - An array of options</dd>
<dt>Returns:</dt>
<dd>The dot representation of the service container</dd>
</dl>

</div>

- - -

