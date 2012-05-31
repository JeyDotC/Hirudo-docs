- - -

**Symfony\Component\DependencyInjection\Definition**
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 21</div>
#Class Definition#

**Definition**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definitiondecorator.html">DefinitionDecorator</a> </dd>
</dl>

- - -

<p class="signature">public  class **Definition**</p>

<div class="comment" id="overview_description"><p>Definition represents a service definition.</p></div>

<dl>
<dt>Author:</dt>
<dd>Fabien Potencier <fabien@symfony.com></dd>
<dt>Api.</dt>
</dl>
- - -

<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td class="type">protected  mixed</td>
<td class="description"><p class="name"><a href="#arguments">$arguments</a></p></td>
</tr>
</table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(string class, array arguments)</p><p class="description">Constructor.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a></td>
<td class="description"><p class="name"><a href="#setFactoryClass">setFactoryClass</a>(string factoryClass)</p><p class="description">Sets the name of the class that acts as a factory using the factory method,
which will be invoked statically.</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#getFactoryClass">getFactoryClass</a>()</p><p class="description">Gets the factory class.</p></td>
</tr>
<tr>
<td class="type"> <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a></td>
<td class="description"><p class="name"><a href="#setFactoryMethod">setFactoryMethod</a>(string factoryMethod)</p><p class="description">Sets the factory method able to create an instance of this class.</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#getFactoryMethod">getFactoryMethod</a>()</p><p class="description">Gets the factory method.</p></td>
</tr>
<tr>
<td class="type"> <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a></td>
<td class="description"><p class="name"><a href="#setFactoryService">setFactoryService</a>(string factoryService)</p><p class="description">Sets the name of the service that acts as a factory using the factory method.</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#getFactoryService">getFactoryService</a>()</p><p class="description">Gets the factory service id.</p></td>
</tr>
<tr>
<td class="type"> <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a></td>
<td class="description"><p class="name"><a href="#setClass">setClass</a>(string class)</p><p class="description">Sets the service class.</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#getClass">getClass</a>()</p><p class="description">Sets the service class.</p></td>
</tr>
<tr>
<td class="type"> <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a></td>
<td class="description"><p class="name"><a href="#setArguments">setArguments</a>(array arguments)</p><p class="description">Sets the arguments to pass to the service constructor/factory method.</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setProperties">setProperties</a>(mixed properties)</p><p class="description"></p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getProperties">getProperties</a>()</p><p class="description"></p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setProperty">setProperty</a>(mixed name, mixed value)</p><p class="description"></p></td>
</tr>
<tr>
<td class="type"> <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a></td>
<td class="description"><p class="name"><a href="#addArgument">addArgument</a>(mixed argument)</p><p class="description">Adds an argument to pass to the service constructor/factory method.</p></td>
</tr>
<tr>
<td class="type"> <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a></td>
<td class="description"><p class="name"><a href="#replaceArgument">replaceArgument</a>(integer index, mixed argument)</p><p class="description">Sets a specific argument</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#getArguments">getArguments</a>()</p><p class="description">Gets the arguments to pass to the service constructor/factory method.</p></td>
</tr>
<tr>
<td class="type"> mixed</td>
<td class="description"><p class="name"><a href="#getArgument">getArgument</a>(integer index)</p><p class="description">Gets an argument to pass to the service constructor/factory method.</p></td>
</tr>
<tr>
<td class="type"> <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a></td>
<td class="description"><p class="name"><a href="#setMethodCalls">setMethodCalls</a>(array calls)</p><p class="description">Sets the methods to call after service initialization.</p></td>
</tr>
<tr>
<td class="type"> <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a></td>
<td class="description"><p class="name"><a href="#addMethodCall">addMethodCall</a>(string method, array arguments)</p><p class="description">Adds a method to call after service initialization.</p></td>
</tr>
<tr>
<td class="type"> <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a></td>
<td class="description"><p class="name"><a href="#removeMethodCall">removeMethodCall</a>(string method)</p><p class="description">Removes a method to call after service initialization.</p></td>
</tr>
<tr>
<td class="type"> Boolean</td>
<td class="description"><p class="name"><a href="#hasMethodCall">hasMethodCall</a>(string method)</p><p class="description">Check if the current definition has a given method to call after service initialization.</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#getMethodCalls">getMethodCalls</a>()</p><p class="description">Gets the methods to call after service initialization.</p></td>
</tr>
<tr>
<td class="type"> <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a></td>
<td class="description"><p class="name"><a href="#setTags">setTags</a>(array tags)</p><p class="description">Sets tags for this definition</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#getTags">getTags</a>()</p><p class="description">Returns all tags.</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#getTag">getTag</a>(string name)</p><p class="description">Gets a tag by name.</p></td>
</tr>
<tr>
<td class="type"> <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a></td>
<td class="description"><p class="name"><a href="#addTag">addTag</a>(string name, array attributes)</p><p class="description">Adds a tag for this definition.</p></td>
</tr>
<tr>
<td class="type"> Boolean</td>
<td class="description"><p class="name"><a href="#hasTag">hasTag</a>(string name)</p><p class="description">Whether this definition has a tag with the given name</p></td>
</tr>
<tr>
<td class="type"> <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a></td>
<td class="description"><p class="name"><a href="#clearTags">clearTags</a>()</p><p class="description">Clears the tags for this definition.</p></td>
</tr>
<tr>
<td class="type"> <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a></td>
<td class="description"><p class="name"><a href="#setFile">setFile</a>(string file)</p><p class="description">Sets a file to require before creating the service.</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#getFile">getFile</a>()</p><p class="description">Gets the file to require before creating the service.</p></td>
</tr>
<tr>
<td class="type"> <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a></td>
<td class="description"><p class="name"><a href="#setScope">setScope</a>(string scope)</p><p class="description">Sets the scope of the service</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#getScope">getScope</a>()</p><p class="description">Returns the scope of the service</p></td>
</tr>
<tr>
<td class="type"> <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a></td>
<td class="description"><p class="name"><a href="#setPublic">setPublic</a>(Boolean boolean)</p><p class="description">Sets the visibility of this service.</p></td>
</tr>
<tr>
<td class="type"> Boolean</td>
<td class="description"><p class="name"><a href="#isPublic">isPublic</a>()</p><p class="description">Whether this service is public facing</p></td>
</tr>
<tr>
<td class="type"> <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a></td>
<td class="description"><p class="name"><a href="#setSynthetic">setSynthetic</a>(Boolean boolean)</p><p class="description">Sets whether this definition is synthetic, that is not constructed by the
container, but dynamically injected.</p></td>
</tr>
<tr>
<td class="type"> Boolean</td>
<td class="description"><p class="name"><a href="#isSynthetic">isSynthetic</a>()</p><p class="description">Whether this definition is synthetic, that is not constructed by the
container, but dynamically injected.</p></td>
</tr>
<tr>
<td class="type"> <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a></td>
<td class="description"><p class="name"><a href="#setAbstract">setAbstract</a>(Boolean boolean)</p><p class="description">Whether this definition is abstract, that means it merely serves as a
template for other definitions.</p></td>
</tr>
<tr>
<td class="type"> Boolean</td>
<td class="description"><p class="name"><a href="#isAbstract">isAbstract</a>()</p><p class="description">Whether this definition is abstract, that means it merely serves as a
template for other definitions.</p></td>
</tr>
<tr>
<td class="type"> <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a></td>
<td class="description"><p class="name"><a href="#setConfigurator">setConfigurator</a>(mixed callable)</p><p class="description">Sets a configurator to call after the service is fully initialized.</p></td>
</tr>
<tr>
<td class="type"> mixed</td>
<td class="description"><p class="name"><a href="#getConfigurator">getConfigurator</a>()</p><p class="description">Gets the configurator to call after the service is fully initialized.</p></td>
</tr>
</table>

##Field Detail##
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 37</div>
<h3 id="arguments">arguments</h3>
```php
protected  mixed **$arguments**```
<div class="details">
</div>

- - -

<h2 id="detail_method">Constructor Detail</h2>
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 47</div>
<h3 id="__construct()">__construct</h3>
```php
public  void **__construct**(string class, array arguments)```
<div class="details">
<p>Constructor.</p><dl>
<dt>Parameters:</dt>
<dd>class - The service class</dd>
<dd>arguments - An array of arguments to pass to the service constructor</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 70</div>
<h3 id="setFactoryClass()">setFactoryClass</h3>
```php
public  <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a> **setFactoryClass**(string factoryClass)```
<div class="details">
<p>Sets the name of the class that acts as a factory using the factory method,
which will be invoked statically.</p><dl>
<dt>Parameters:</dt>
<dd>factoryClass - The factory class name</dd>
<dt>Returns:</dt>
<dd>The current instance</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 84</div>
<h3 id="getFactoryClass()">getFactoryClass</h3>
```php
public  string **getFactoryClass**()```
<div class="details">
<p>Gets the factory class.</p><dl>
<dt>Returns:</dt>
<dd>The factory class name</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 98</div>
<h3 id="setFactoryMethod()">setFactoryMethod</h3>
```php
public  <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a> **setFactoryMethod**(string factoryMethod)```
<div class="details">
<p>Sets the factory method able to create an instance of this class.</p><dl>
<dt>Parameters:</dt>
<dd>factoryMethod - The factory method name</dd>
<dt>Returns:</dt>
<dd>The current instance</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 112</div>
<h3 id="getFactoryMethod()">getFactoryMethod</h3>
```php
public  string **getFactoryMethod**()```
<div class="details">
<p>Gets the factory method.</p><dl>
<dt>Returns:</dt>
<dd>The factory method name</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 126</div>
<h3 id="setFactoryService()">setFactoryService</h3>
```php
public  <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a> **setFactoryService**(string factoryService)```
<div class="details">
<p>Sets the name of the service that acts as a factory using the factory method.</p><dl>
<dt>Parameters:</dt>
<dd>factoryService - The factory service id</dd>
<dt>Returns:</dt>
<dd>The current instance</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 140</div>
<h3 id="getFactoryService()">getFactoryService</h3>
```php
public  string **getFactoryService**()```
<div class="details">
<p>Gets the factory service id.</p><dl>
<dt>Returns:</dt>
<dd>The factory service id</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 154</div>
<h3 id="setClass()">setClass</h3>
```php
public  <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a> **setClass**(string class)```
<div class="details">
<p>Sets the service class.</p><dl>
<dt>Parameters:</dt>
<dd>class - The service class</dd>
<dt>Returns:</dt>
<dd>The current instance</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 168</div>
<h3 id="getClass()">getClass</h3>
```php
public  string **getClass**()```
<div class="details">
<p>Sets the service class.</p><dl>
<dt>Returns:</dt>
<dd>The service class</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 182</div>
<h3 id="setArguments()">setArguments</h3>
```php
public  <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a> **setArguments**(array arguments)```
<div class="details">
<p>Sets the arguments to pass to the service constructor/factory method.</p><dl>
<dt>Parameters:</dt>
<dd>arguments - An array of arguments</dd>
<dt>Returns:</dt>
<dd>The current instance</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 192</div>
<h3 id="setProperties()">setProperties</h3>
```php
public  void **setProperties**(mixed properties)```
<div class="details">
<p></p><dl>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 202</div>
<h3 id="getProperties()">getProperties</h3>
```php
public  void **getProperties**()```
<div class="details">
<p></p><dl>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 210</div>
<h3 id="setProperty()">setProperty</h3>
```php
public  void **setProperty**(mixed name, mixed value)```
<div class="details">
<p></p><dl>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 226</div>
<h3 id="addArgument()">addArgument</h3>
```php
public  <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a> **addArgument**(mixed argument)```
<div class="details">
<p>Adds an argument to pass to the service constructor/factory method.</p><dl>
<dt>Parameters:</dt>
<dd>argument - An argument</dd>
<dt>Returns:</dt>
<dd>The current instance</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 243</div>
<h3 id="replaceArgument()">replaceArgument</h3>
```php
public  <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a> **replaceArgument**(integer index, mixed argument)```
<div class="details">
<p>Sets a specific argument</p><dl>
<dt>Returns:</dt>
<dd>The current instance</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 261</div>
<h3 id="getArguments()">getArguments</h3>
```php
public  array **getArguments**()```
<div class="details">
<p>Gets the arguments to pass to the service constructor/factory method.</p><dl>
<dt>Returns:</dt>
<dd>The array of arguments</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 275</div>
<h3 id="getArgument()">getArgument</h3>
```php
public  mixed **getArgument**(integer index)```
<div class="details">
<p>Gets an argument to pass to the service constructor/factory method.</p><dl>
<dt>Returns:</dt>
<dd>The argument value</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 293</div>
<h3 id="setMethodCalls()">setMethodCalls</h3>
```php
public  <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a> **setMethodCalls**(array calls)```
<div class="details">
<p>Sets the methods to call after service initialization.</p><dl>
<dt>Parameters:</dt>
<dd>calls - An array of method calls</dd>
<dt>Returns:</dt>
<dd>The current instance</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 313</div>
<h3 id="addMethodCall()">addMethodCall</h3>
```php
public  <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a> **addMethodCall**(string method, array arguments)```
<div class="details">
<p>Adds a method to call after service initialization.</p><dl>
<dt>Parameters:</dt>
<dd>method - The method name to call</dd>
<dd>arguments - An array of arguments to pass to the method call</dd>
<dt>Returns:</dt>
<dd>The current instance</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 329</div>
<h3 id="removeMethodCall()">removeMethodCall</h3>
```php
public  <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a> **removeMethodCall**(string method)```
<div class="details">
<p>Removes a method to call after service initialization.</p><dl>
<dt>Parameters:</dt>
<dd>method - The method name to remove</dd>
<dt>Returns:</dt>
<dd>The current instance</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 350</div>
<h3 id="hasMethodCall()">hasMethodCall</h3>
```php
public  Boolean **hasMethodCall**(string method)```
<div class="details">
<p>Check if the current definition has a given method to call after service initialization.</p><dl>
<dt>Parameters:</dt>
<dd>method - The method name to search for</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 368</div>
<h3 id="getMethodCalls()">getMethodCalls</h3>
```php
public  array **getMethodCalls**()```
<div class="details">
<p>Gets the methods to call after service initialization.</p><dl>
<dt>Returns:</dt>
<dd>An array of method calls</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 382</div>
<h3 id="setTags()">setTags</h3>
```php
public  <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a> **setTags**(array tags)```
<div class="details">
<p>Sets tags for this definition</p><dl>
<dt>Returns:</dt>
<dd>the current instance</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 396</div>
<h3 id="getTags()">getTags</h3>
```php
public  array **getTags**()```
<div class="details">
<p>Returns all tags.</p><dl>
<dt>Returns:</dt>
<dd>An array of tags</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 410</div>
<h3 id="getTag()">getTag</h3>
```php
public  array **getTag**(string name)```
<div class="details">
<p>Gets a tag by name.</p><dl>
<dt>Parameters:</dt>
<dd>name - The tag name</dd>
<dt>Returns:</dt>
<dd>An array of attributes</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 425</div>
<h3 id="addTag()">addTag</h3>
```php
public  <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a> **addTag**(string name, array attributes)```
<div class="details">
<p>Adds a tag for this definition.</p><dl>
<dt>Parameters:</dt>
<dd>name - The tag name</dd>
<dd>attributes - An array of attributes</dd>
<dt>Returns:</dt>
<dd>The current instance</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 441</div>
<h3 id="hasTag()">hasTag</h3>
```php
public  Boolean **hasTag**(string name)```
<div class="details">
<p>Whether this definition has a tag with the given name</p><dl>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 453</div>
<h3 id="clearTags()">clearTags</h3>
```php
public  <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a> **clearTags**()```
<div class="details">
<p>Clears the tags for this definition.</p><dl>
<dt>Returns:</dt>
<dd>The current instance</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 469</div>
<h3 id="setFile()">setFile</h3>
```php
public  <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a> **setFile**(string file)```
<div class="details">
<p>Sets a file to require before creating the service.</p><dl>
<dt>Parameters:</dt>
<dd>file - A full pathname to include</dd>
<dt>Returns:</dt>
<dd>The current instance</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 483</div>
<h3 id="getFile()">getFile</h3>
```php
public  string **getFile**()```
<div class="details">
<p>Gets the file to require before creating the service.</p><dl>
<dt>Returns:</dt>
<dd>The full pathname to include</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 497</div>
<h3 id="setScope()">setScope</h3>
```php
public  <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a> **setScope**(string scope)```
<div class="details">
<p>Sets the scope of the service</p><dl>
<dt>Parameters:</dt>
<dd>scope - Whether the service must be shared or not</dd>
<dt>Returns:</dt>
<dd>The current instance</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 511</div>
<h3 id="getScope()">getScope</h3>
```php
public  string **getScope**()```
<div class="details">
<p>Returns the scope of the service</p><dl>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 524</div>
<h3 id="setPublic()">setPublic</h3>
```php
public  <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a> **setPublic**(Boolean boolean)```
<div class="details">
<p>Sets the visibility of this service.</p><dl>
<dt>Returns:</dt>
<dd>The current instance</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 538</div>
<h3 id="isPublic()">isPublic</h3>
```php
public  Boolean **isPublic**()```
<div class="details">
<p>Whether this service is public facing</p><dl>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 553</div>
<h3 id="setSynthetic()">setSynthetic</h3>
```php
public  <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a> **setSynthetic**(Boolean boolean)```
<div class="details">
<p>Sets whether this definition is synthetic, that is not constructed by the
container, but dynamically injected.</p><dl>
<dt>Returns:</dt>
<dd>the current instance</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 568</div>
<h3 id="isSynthetic()">isSynthetic</h3>
```php
public  Boolean **isSynthetic**()```
<div class="details">
<p>Whether this definition is synthetic, that is not constructed by the
container, but dynamically injected.</p><dl>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 583</div>
<h3 id="setAbstract()">setAbstract</h3>
```php
public  <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a> **setAbstract**(Boolean boolean)```
<div class="details">
<p>Whether this definition is abstract, that means it merely serves as a
template for other definitions.</p><dl>
<dt>Returns:</dt>
<dd>the current instance</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 598</div>
<h3 id="isAbstract()">isAbstract</h3>
```php
public  Boolean **isAbstract**()```
<div class="details">
<p>Whether this definition is abstract, that means it merely serves as a
template for other definitions.</p><dl>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 612</div>
<h3 id="setConfigurator()">setConfigurator</h3>
```php
public  <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a> **setConfigurator**(mixed callable)```
<div class="details">
<p>Sets a configurator to call after the service is fully initialized.</p><dl>
<dt>Parameters:</dt>
<dd>callable - A PHP callable</dd>
<dt>Returns:</dt>
<dd>The current instance</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 626</div>
<h3 id="getConfigurator()">getConfigurator</h3>
```php
public  mixed **getConfigurator**()```
<div class="details">
<p>Gets the configurator to call after the service is fully initialized.</p><dl>
<dt>Returns:</dt>
<dd>The PHP callable to call</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

