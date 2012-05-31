- - -

**Symfony\Component\DependencyInjection\DefinitionDecorator**
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/DefinitionDecorator.php.md#line21" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\DefinitionDecorator.php at line 21</a>

# Class DefinitionDecorator #

<pre class="tree"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html">Definition</a>\n    *** DefinitionDecorator **\n</pre>

- - -

<p class="signature">public  class **DefinitionDecorator**\nextends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html">Definition</a>

</p>

<div class="comment" id="overview_description"><p>This definition decorates another definition.</p></div>

<dl>
<dt>Author:</dt>
<dd>Johannes M. Schmitt <schmittjoh@gmail.com></dd>
<dt>Api.</dt>
</dl>
- - -

<table class="inherit">
<tr><th colspan="2">Fields inherited from Symfony\Component\DependencyInjection\Definition</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html#arguments">arguments</a></td></tr></table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct()">__construct</a>(<a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a> parent, string class, array arguments)</p><p class="description">Constructor.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a></td>
<td class="description"><p class="name"><a href="#getParent()">getParent</a>()</p><p class="description">Returns the Definition being decorated.</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#getChanges()">getChanges</a>()</p><p class="description">Returns all changes tracked for the Definition object.</p></td>
</tr>
<tr>
<td class="type"> <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a></td>
<td class="description"><p class="name"><a href="#setClass()">setClass</a>(string class)</p><p class="description">Sets the service class.</p></td>
</tr>
<tr>
<td class="type"> <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a></td>
<td class="description"><p class="name"><a href="#setFactoryClass()">setFactoryClass</a>(mixed class, string factoryClass)</p><p class="description">Sets the name of the class that acts as a factory using the factory method,
which will be invoked statically.</p></td>
</tr>
<tr>
<td class="type"> <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a></td>
<td class="description"><p class="name"><a href="#setFactoryMethod()">setFactoryMethod</a>(mixed method, string factoryMethod)</p><p class="description">Sets the factory method able to create an instance of this class.</p></td>
</tr>
<tr>
<td class="type"> <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a></td>
<td class="description"><p class="name"><a href="#setFactoryService()">setFactoryService</a>(mixed service, string factoryService)</p><p class="description">Sets the name of the service that acts as a factory using the factory method.</p></td>
</tr>
<tr>
<td class="type"> <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a></td>
<td class="description"><p class="name"><a href="#setConfigurator()">setConfigurator</a>(mixed callable)</p><p class="description">Sets a configurator to call after the service is fully initialized.</p></td>
</tr>
<tr>
<td class="type"> <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a></td>
<td class="description"><p class="name"><a href="#setFile()">setFile</a>(string file)</p><p class="description">Sets a file to require before creating the service.</p></td>
</tr>
<tr>
<td class="type"> <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a></td>
<td class="description"><p class="name"><a href="#setPublic()">setPublic</a>(Boolean boolean)</p><p class="description">Sets the visibility of this service.</p></td>
</tr>
<tr>
<td class="type"> <a href="../../../symfony/component/dependencyinjection/definitiondecorator.html">DefinitionDecorator</a></td>
<td class="description"><p class="name"><a href="#replaceArgument()">replaceArgument</a>(integer index, mixed value, mixed argument)</p><p class="description">You should always use this method when overwriting existing arguments
of the parent definition.
</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Symfony\Component\DependencyInjection\Definition</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html#__construct()">__construct</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html#addArgument()">addArgument</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html#addMethodCall()">addMethodCall</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html#addTag()">addTag</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html#clearTags()">clearTags</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html#getArgument()">getArgument</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html#getArguments()">getArguments</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html#getClass()">getClass</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html#getConfigurator()">getConfigurator</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html#getFactoryClass()">getFactoryClass</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html#getFactoryMethod()">getFactoryMethod</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html#getFactoryService()">getFactoryService</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html#getFile()">getFile</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html#getMethodCalls()">getMethodCalls</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html#getProperties()">getProperties</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html#getScope()">getScope</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html#getTag()">getTag</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html#getTags()">getTags</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html#hasMethodCall()">hasMethodCall</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html#hasTag()">hasTag</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html#isAbstract()">isAbstract</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html#isPublic()">isPublic</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html#isSynthetic()">isSynthetic</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html#removeMethodCall()">removeMethodCall</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html#replaceArgument()">replaceArgument</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html#setAbstract()">setAbstract</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html#setArguments()">setArguments</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html#setClass()">setClass</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html#setConfigurator()">setConfigurator</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html#setFactoryClass()">setFactoryClass</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html#setFactoryMethod()">setFactoryMethod</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html#setFactoryService()">setFactoryService</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html#setFile()">setFile</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html#setMethodCalls()">setMethodCalls</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html#setProperties()">setProperties</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html#setProperty()">setProperty</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html#setPublic()">setPublic</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html#setScope()">setScope</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html#setSynthetic()">setSynthetic</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html#setTags()">setTags</a></td></tr></table>

<h2 id="detail_method">Constructor Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/DefinitionDecorator.php.md#line33" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\DefinitionDecorator.php at line 33</a>

<h3 id="__construct()">__construct</h3>
```php
public  void **__construct**(<a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a> parent, string class, array arguments)```
<div class="details">
<p>Constructor.</p><dl>
<dt>Parameters:</dt>
<dd>parent - The Definition instance to decorate.</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/DefinitionDecorator.php.md#line47" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\DefinitionDecorator.php at line 47</a>

<h3 id="getParent()">getParent</h3>
```php
public  <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a> **getParent**()```
<div class="details">
<p>Returns the Definition being decorated.</p><dl>
<dt>Api.</dt>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/DefinitionDecorator.php.md#line58" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\DefinitionDecorator.php at line 58</a>

<h3 id="getChanges()">getChanges</h3>
```php
public  array **getChanges**()```
<div class="details">
<p>Returns all changes tracked for the Definition object.</p><dl>
<dt>Returns:</dt>
<dd>An array of changes for this Definition</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/DefinitionDecorator.php.md#line67" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\DefinitionDecorator.php at line 67</a>

<h3 id="setClass()">setClass</h3>
```php
public  <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a> **setClass**(string class)```
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

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/DefinitionDecorator.php.md#line78" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\DefinitionDecorator.php at line 78</a>

<h3 id="setFactoryClass()">setFactoryClass</h3>
```php
public  <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a> **setFactoryClass**(mixed class, string factoryClass)```
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

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/DefinitionDecorator.php.md#line89" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\DefinitionDecorator.php at line 89</a>

<h3 id="setFactoryMethod()">setFactoryMethod</h3>
```php
public  <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a> **setFactoryMethod**(mixed method, string factoryMethod)```
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

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/DefinitionDecorator.php.md#line100" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\DefinitionDecorator.php at line 100</a>

<h3 id="setFactoryService()">setFactoryService</h3>
```php
public  <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a> **setFactoryService**(mixed service, string factoryService)```
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

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/DefinitionDecorator.php.md#line111" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\DefinitionDecorator.php at line 111</a>

<h3 id="setConfigurator()">setConfigurator</h3>
```php
public  <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a> **setConfigurator**(mixed callable)```
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

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/DefinitionDecorator.php.md#line122" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\DefinitionDecorator.php at line 122</a>

<h3 id="setFile()">setFile</h3>
```php
public  <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a> **setFile**(string file)```
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

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/DefinitionDecorator.php.md#line133" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\DefinitionDecorator.php at line 133</a>

<h3 id="setPublic()">setPublic</h3>
```php
public  <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a> **setPublic**(Boolean boolean)```
<div class="details">
<p>Sets the visibility of this service.</p><dl>
<dt>Api.</dt>
<dt>Returns:</dt>
<dd>The current instance</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/DefinitionDecorator.php.md#line155" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\DefinitionDecorator.php at line 155</a>

<h3 id="replaceArgument()">replaceArgument</h3>
```php
public  <a href="../../../symfony/component/dependencyinjection/definitiondecorator.html">DefinitionDecorator</a> **replaceArgument**(integer index, mixed value, mixed argument)```
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

