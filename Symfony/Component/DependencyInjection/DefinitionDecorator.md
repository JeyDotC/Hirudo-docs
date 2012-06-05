

- - -

**Symfony\Component\DependencyInjection\DefinitionDecorator**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/DefinitionDecorator.php#L21" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\DefinitionDecorator.php at line 21</a>

#Class DefinitionDecorator#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Definition.md">Definition</a>
 &gt; **DefinitionDecorator**




- - -

<p><strong>public  class</strong> <span>DefinitionDecorator</span>
<strong>extends</strong> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Definition.md">Definition</a>

</p>

<div class="comment" id="overview_description"><p>This definition decorates another definition.</p></div>

<dl>
<dt>Author:</dt>
<dd>Johannes M. Schmitt <schmittjoh@gmail.com></dd>
<dt>Api.</dt>
</dl>


<hr />

<table class="inherit">
<tr><th colspan="2">Fields inherited from Symfony\Component\DependencyInjection\Definition</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Definition.md#arguments">arguments</a></td></tr></table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Definition.md">Definition</a> parent, string class, array arguments)</p><p class="description">Constructor.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/DefinitionDecorator.md#getParent>Definition</a></span></td>
<td class="description"><p class="name"><a href="#getparent">getParent</a>()</p><p class="description">Returns the Definition being decorated.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name"><a href="#getchanges">getChanges</a>()</p><p class="description">Returns all changes tracked for the Definition object.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/DefinitionDecorator.md#setClass>Definition</a></span></td>
<td class="description"><p class="name"><a href="#setclass">setClass</a>(string class)</p><p class="description">Sets the service class.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/DefinitionDecorator.md#setFactoryClass>Definition</a></span></td>
<td class="description"><p class="name"><a href="#setfactoryclass">setFactoryClass</a>(mixed class, string factoryClass)</p><p class="description">Sets the name of the class that acts as a factory using the factory method,
which will be invoked statically.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/DefinitionDecorator.md#setFactoryMethod>Definition</a></span></td>
<td class="description"><p class="name"><a href="#setfactorymethod">setFactoryMethod</a>(mixed method, string factoryMethod)</p><p class="description">Sets the factory method able to create an instance of this class.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/DefinitionDecorator.md#setFactoryService>Definition</a></span></td>
<td class="description"><p class="name"><a href="#setfactoryservice">setFactoryService</a>(mixed service, string factoryService)</p><p class="description">Sets the name of the service that acts as a factory using the factory method.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/DefinitionDecorator.md#setConfigurator>Definition</a></span></td>
<td class="description"><p class="name"><a href="#setconfigurator">setConfigurator</a>(mixed callable)</p><p class="description">Sets a configurator to call after the service is fully initialized.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/DefinitionDecorator.md#setFile>Definition</a></span></td>
<td class="description"><p class="name"><a href="#setfile">setFile</a>(string file)</p><p class="description">Sets a file to require before creating the service.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/DefinitionDecorator.md#setPublic>Definition</a></span></td>
<td class="description"><p class="name"><a href="#setpublic">setPublic</a>(Boolean boolean)</p><p class="description">Sets the visibility of this service.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/DefinitionDecorator.md#replaceArgument>DefinitionDecorator</a></span></td>
<td class="description"><p class="name"><a href="#replaceargument">replaceArgument</a>(integer index, mixed value, mixed argument)</p><p class="description">You should always use this method when overwriting existing arguments
of the parent definition.
</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Symfony\Component\DependencyInjection\Definition</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Definition.md#__construct">__construct</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Definition.md#addArgument">addArgument</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Definition.md#addMethodCall">addMethodCall</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Definition.md#addTag">addTag</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Definition.md#clearTags">clearTags</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Definition.md#getArgument">getArgument</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Definition.md#getArguments">getArguments</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Definition.md#getClass">getClass</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Definition.md#getConfigurator">getConfigurator</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Definition.md#getFactoryClass">getFactoryClass</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Definition.md#getFactoryMethod">getFactoryMethod</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Definition.md#getFactoryService">getFactoryService</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Definition.md#getFile">getFile</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Definition.md#getMethodCalls">getMethodCalls</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Definition.md#getProperties">getProperties</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Definition.md#getScope">getScope</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Definition.md#getTag">getTag</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Definition.md#getTags">getTags</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Definition.md#hasMethodCall">hasMethodCall</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Definition.md#hasTag">hasTag</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Definition.md#isAbstract">isAbstract</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Definition.md#isPublic">isPublic</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Definition.md#isSynthetic">isSynthetic</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Definition.md#removeMethodCall">removeMethodCall</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Definition.md#replaceArgument">replaceArgument</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Definition.md#setAbstract">setAbstract</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Definition.md#setArguments">setArguments</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Definition.md#setClass">setClass</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Definition.md#setConfigurator">setConfigurator</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Definition.md#setFactoryClass">setFactoryClass</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Definition.md#setFactoryMethod">setFactoryMethod</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Definition.md#setFactoryService">setFactoryService</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Definition.md#setFile">setFile</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Definition.md#setMethodCalls">setMethodCalls</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Definition.md#setProperties">setProperties</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Definition.md#setProperty">setProperty</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Definition.md#setPublic">setPublic</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Definition.md#setScope">setScope</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Definition.md#setSynthetic">setSynthetic</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Definition.md#setTags">setTags</a></td></tr></table>

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/DefinitionDecorator.php#L33" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\DefinitionDecorator.php at line 33</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/Definition.md">Definition</a> parent, string class, array arguments)

<div class="details">
<p>Constructor.</p><dl>
<dt>Parameters:</dt>
<dd>parent - The Definition instance to decorate.</dd>
<dt>Api.</dt>
</dl>

</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/DefinitionDecorator.php#L47" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\DefinitionDecorator.php at line 47</a>

<h3 id="getParent()">getParent</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/DefinitionDecorator.md#getParent>Definition</a></span> <span class='nf'>getParent</span> ()

<div class="details">
<p>Returns the Definition being decorated.</p><dl>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/DefinitionDecorator.php#L58" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\DefinitionDecorator.php at line 58</a>

<h3 id="getChanges()">getChanges</h3>
<span class='k'></span> <span class='nx'>array</span> <span class='nf'>getChanges</span> ()

<div class="details">
<p>Returns all changes tracked for the Definition object.</p><dl>
<dt>Returns:</dt>
<dd>An array of changes for this Definition</dd>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/DefinitionDecorator.php#L67" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\DefinitionDecorator.php at line 67</a>

<h3 id="setClass()">setClass</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/DefinitionDecorator.md#setClass>Definition</a></span> <span class='nf'>setClass</span> (string class)

<div class="details">
<p>Sets the service class.</p><dl>
<dt>Api.</dt>
<dt>Parameters:</dt>
<dd>class - The service class</dd>
<dt>Returns:</dt>
<dd>The current instance</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/DefinitionDecorator.php#L78" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\DefinitionDecorator.php at line 78</a>

<h3 id="setFactoryClass()">setFactoryClass</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/DefinitionDecorator.md#setFactoryClass>Definition</a></span> <span class='nf'>setFactoryClass</span> (mixed class, string factoryClass)

<div class="details">
<p>Sets the name of the class that acts as a factory using the factory method,
which will be invoked statically.</p><dl>
<dt>Api.</dt>
<dt>Parameters:</dt>
<dd>factoryClass - The factory class name</dd>
<dt>Returns:</dt>
<dd>The current instance</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/DefinitionDecorator.php#L89" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\DefinitionDecorator.php at line 89</a>

<h3 id="setFactoryMethod()">setFactoryMethod</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/DefinitionDecorator.md#setFactoryMethod>Definition</a></span> <span class='nf'>setFactoryMethod</span> (mixed method, string factoryMethod)

<div class="details">
<p>Sets the factory method able to create an instance of this class.</p><dl>
<dt>Api.</dt>
<dt>Parameters:</dt>
<dd>factoryMethod - The factory method name</dd>
<dt>Returns:</dt>
<dd>The current instance</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/DefinitionDecorator.php#L100" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\DefinitionDecorator.php at line 100</a>

<h3 id="setFactoryService()">setFactoryService</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/DefinitionDecorator.md#setFactoryService>Definition</a></span> <span class='nf'>setFactoryService</span> (mixed service, string factoryService)

<div class="details">
<p>Sets the name of the service that acts as a factory using the factory method.</p><dl>
<dt>Api.</dt>
<dt>Parameters:</dt>
<dd>factoryService - The factory service id</dd>
<dt>Returns:</dt>
<dd>The current instance</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/DefinitionDecorator.php#L111" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\DefinitionDecorator.php at line 111</a>

<h3 id="setConfigurator()">setConfigurator</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/DefinitionDecorator.md#setConfigurator>Definition</a></span> <span class='nf'>setConfigurator</span> (mixed callable)

<div class="details">
<p>Sets a configurator to call after the service is fully initialized.</p><dl>
<dt>Api.</dt>
<dt>Parameters:</dt>
<dd>callable - A PHP callable</dd>
<dt>Returns:</dt>
<dd>The current instance</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/DefinitionDecorator.php#L122" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\DefinitionDecorator.php at line 122</a>

<h3 id="setFile()">setFile</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/DefinitionDecorator.md#setFile>Definition</a></span> <span class='nf'>setFile</span> (string file)

<div class="details">
<p>Sets a file to require before creating the service.</p><dl>
<dt>Api.</dt>
<dt>Parameters:</dt>
<dd>file - A full pathname to include</dd>
<dt>Returns:</dt>
<dd>The current instance</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/DefinitionDecorator.php#L133" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\DefinitionDecorator.php at line 133</a>

<h3 id="setPublic()">setPublic</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/DefinitionDecorator.md#setPublic>Definition</a></span> <span class='nf'>setPublic</span> (Boolean boolean)

<div class="details">
<p>Sets the visibility of this service.</p><dl>
<dt>Api.</dt>
<dt>Returns:</dt>
<dd>The current instance</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/DefinitionDecorator.php#L155" target='_blank'>framework\libs\symfony-components\Symfony\Component\DependencyInjection\DefinitionDecorator.php at line 155</a>

<h3 id="replaceArgument()">replaceArgument</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Symfony/Component/DependencyInjection/DefinitionDecorator.md#replaceArgument>DefinitionDecorator</a></span> <span class='nf'>replaceArgument</span> (integer index, mixed value, mixed argument)

<div class="details">
<p>You should always use this method when overwriting existing arguments
of the parent definition.</p><p>If you directly call setArguments() keep in mind that you must follow
certain conventions when you want to overwrite the arguments of the
parent definition, otherwise your arguments will only be appended.</p><dl>
<dt>Returns:</dt>
<dd>the current instance</dd>
<dt>Throws:</dt>
<dd><a href="../../../symfony/component/dependencyinjection/exception/invalidargumentexception.html">\InvalidArgumentException</a> - when $index isn't an integer</dd>
<dt>Api.</dt>
</dl>

</div>

- - -
