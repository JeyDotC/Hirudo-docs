

- - -

**Hirudo\Core\Task**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Task.php#L35" target='_blank'>framework\Hirudo\Core\Task.php at line 35</a>

#Class Task#

**Task**




- - -

<p><strong>public  class</strong> <span>Task</span></p>

<div class="comment" id="overview_description"><p>Is a representation of a module's task, it holds the information about the action
to be executed and can be used to know which are it's requirements and also
resolve them.</p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
</dl>


<hr />

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(\ReflectionMethod reflectionMethod, \Hirudo\Core\Module owner)</p><p class="description">Constructs a task.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getname">getName</a>()</p><p class="description">Gets the method name.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array<\ReflectionParameter></span></td>
<td class="description"><p class="name"><a href="#getparams">getParams</a>()</p><p class="description">Gets the method's parameters.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setparamvalue">setParamValue</a>(string paramName, mixed value)</p><p class="description">Sets the value of a method's param.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>type</span></td>
<td class="description"><p class="name"><a href="#getparamvalue">getParamValue</a>(string paramName)</p><p class="description">Gets the value of a method's param.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#invoke">invoke</a>()</p><p class="description">Executes the task.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array<mixed></span></td>
<td class="description"><p class="name"><a href="#gettaskannotations">getTaskAnnotations</a>()</p><p class="description">Gets the method's meta data.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#gettaskannotation">getTaskAnnotation</a>(string annotationName)</p><p class="description">Gets a single annotation from the merhod.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md>Module</a></span></td>
<td class="description"><p class="name"><a href="#getmodule">getModule</a>()</p><p class="description">Gets the module that owns the method to be executed.</p></td>
</tr>
</table>

<h2>Constructor Detail</h2>


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Task.php#L63" target='_blank'>framework\Hirudo\Core\Task.php at line 63</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (\ReflectionMethod reflectionMethod, \Hirudo\Core\Module owner)

<div class="details">
<p>Constructs a task.</p><dl>
<dt>Parameters:</dt>
<dd>reflectionMethod - The method to be called.</dd>
<dd>owner - The module that is the owner of the task.</dd>
</dl>

</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Task.php#L79" target='_blank'>framework\Hirudo\Core\Task.php at line 79</a>

<h3 id="getName()">getName</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getName</span> ()

<div class="details">
<p>Gets the method name.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Task.php#L88" target='_blank'>framework\Hirudo\Core\Task.php at line 88</a>

<h3 id="getParams()">getParams</h3>
<span class='k'></span> <span class='nx'>array<\ReflectionParameter></span> <span class='nf'>getParams</span> ()

<div class="details">
<p>Gets the method's parameters.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Task.php#L98" target='_blank'>framework\Hirudo\Core\Task.php at line 98</a>

<h3 id="setParamValue()">setParamValue</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setParamValue</span> (string paramName, mixed value)

<div class="details">
<p>Sets the value of a method's param.</p><dl>
<dt>Parameters:</dt>
<dd>paramName - The parameter name.</dd>
<dd>value - The value for the parameter.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Task.php#L108" target='_blank'>framework\Hirudo\Core\Task.php at line 108</a>

<h3 id="getParamValue()">getParamValue</h3>
<span class='k'></span> <span class='nx'>type</span> <span class='nf'>getParamValue</span> (string paramName)

<div class="details">
<p>Gets the value of a method's param.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Task.php#L115" target='_blank'>framework\Hirudo\Core\Task.php at line 115</a>

<h3 id="invoke()">invoke</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>invoke</span> ()

<div class="details">
<p>Executes the task.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Task.php#L124" target='_blank'>framework\Hirudo\Core\Task.php at line 124</a>

<h3 id="getTaskAnnotations()">getTaskAnnotations</h3>
<span class='k'></span> <span class='nx'>array<mixed></span> <span class='nf'>getTaskAnnotations</span> ()

<div class="details">
<p>Gets the method's meta data.</p><dl>
<dt>Returns:</dt>
<dd>An annotations list.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Task.php#L134" target='_blank'>framework\Hirudo\Core\Task.php at line 134</a>

<h3 id="getTaskAnnotation()">getTaskAnnotation</h3>
<span class='k'></span> <span class='nx'>mixed</span> <span class='nf'>getTaskAnnotation</span> (string annotationName)

<div class="details">
<p>Gets a single annotation from the merhod.</p><dl>
<dt>Parameters:</dt>
<dd>annotationName - The fully qualified annotation class or annotation id.</dd>
<dt>Returns:</dt>
<dd>The annotation</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Task.php#L143" target='_blank'>framework\Hirudo\Core\Task.php at line 143</a>

<h3 id="getModule()">getModule</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md>Module</a></span> <span class='nf'>getModule</span> ()

<div class="details">
<p>Gets the module that owns the method to be executed.</p>
</div>

- - -

