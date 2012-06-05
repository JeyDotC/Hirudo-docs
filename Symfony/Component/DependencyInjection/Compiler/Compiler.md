

- - -

**Symfony\Component\DependencyInjection\Compiler\Compiler**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/Compiler.php#L24" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\Compiler.php at line 24</a>

#Class Compiler#

**Compiler**




- - -

<p><strong>public  class</strong> <span>Compiler</span></p>

<div class="comment" id="overview_description"><p>This class is used to remove circular dependencies between individual passes.</p></div>

<dl>
<dt>Author:</dt>
<dd>Johannes M. Schmitt <schmittjoh@gmail.com></dd>
<dt>Api.</dt>
</dl>


<hr />

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
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Compiler/Compiler.md#getPassConfig>PassConfig</a></span></td>
<td class="description"><p class="name"><a href="#getpassconfig">getPassConfig</a>()</p><p class="description">Returns the PassConfig.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Compiler/Compiler.md#getServiceReferenceGraph>ServiceReferenceGraph</a></span></td>
<td class="description"><p class="name"><a href="#getservicereferencegraph">getServiceReferenceGraph</a>()</p><p class="description">Returns the ServiceReferenceGraph.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Compiler/Compiler.md#getLoggingFormatter>LoggingFormatter</a></span></td>
<td class="description"><p class="name"><a href="#getloggingformatter">getLoggingFormatter</a>()</p><p class="description">Returns the logging formatter which can be used by compilation passes.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#addpass">addPass</a>(<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Compiler/CompilerPassInterface.md">CompilerPassInterface</a> pass, string type)</p><p class="description">Adds a pass to the PassConfig.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#addlogmessage">addLogMessage</a>(string string)</p><p class="description">Adds a log message.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name"><a href="#getlog">getLog</a>()</p><p class="description">Returns the log.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#compile">compile</a>(<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/ContainerBuilder.md">ContainerBuilder</a> container)</p><p class="description">Run the Compiler and process all Passes.</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/Compiler.php#L34" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\Compiler.php at line 34</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> ()

<div class="details">
<p>Constructor.</p>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/Compiler.php#L49" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\Compiler.php at line 49</a>

<h3 id="getPassConfig()">getPassConfig</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Compiler/Compiler.md#getPassConfig>PassConfig</a></span> <span class='nf'>getPassConfig</span> ()

<div class="details">
<p>Returns the PassConfig.</p><dl>
<dt>Returns:</dt>
<dd>The PassConfig instance</dd>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/Compiler.php#L61" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\Compiler.php at line 61</a>

<h3 id="getServiceReferenceGraph()">getServiceReferenceGraph</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Compiler/Compiler.md#getServiceReferenceGraph>ServiceReferenceGraph</a></span> <span class='nf'>getServiceReferenceGraph</span> ()

<div class="details">
<p>Returns the ServiceReferenceGraph.</p><dl>
<dt>Returns:</dt>
<dd>The ServiceReferenceGraph instance</dd>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/Compiler.php#L71" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\Compiler.php at line 71</a>

<h3 id="getLoggingFormatter()">getLoggingFormatter</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Compiler/Compiler.md#getLoggingFormatter>LoggingFormatter</a></span> <span class='nf'>getLoggingFormatter</span> ()

<div class="details">
<p>Returns the logging formatter which can be used by compilation passes.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/Compiler.php#L84" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\Compiler.php at line 84</a>

<h3 id="addPass()">addPass</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>addPass</span> (<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Compiler/CompilerPassInterface.md">CompilerPassInterface</a> pass, string type)

<div class="details">
<p>Adds a pass to the PassConfig.</p><dl>
<dt>Parameters:</dt>
<dd>pass - A compiler pass</dd>
<dd>type - The type of the pass</dd>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/Compiler.php#L94" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\Compiler.php at line 94</a>

<h3 id="addLogMessage()">addLogMessage</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>addLogMessage</span> (string string)

<div class="details">
<p>Adds a log message.</p><dl>
<dt>Parameters:</dt>
<dd>string - The log message</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/Compiler.php#L104" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\Compiler.php at line 104</a>

<h3 id="getLog()">getLog</h3>
<span class='k'></span> <span class='nx'>array</span> <span class='nf'>getLog</span> ()

<div class="details">
<p>Returns the log.</p><dl>
<dt>Returns:</dt>
<dd>Log array</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/Compiler.php#L116" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\Compiler.php at line 116</a>

<h3 id="compile()">compile</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>compile</span> (<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/ContainerBuilder.md">ContainerBuilder</a> container)

<div class="details">
<p>Run the Compiler and process all Passes.</p><dl>
<dt>Api.</dt>
</dl>

</div>

- - -

