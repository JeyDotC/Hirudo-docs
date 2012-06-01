

- - -

**Symfony\Component\DependencyInjection\Definition**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Definition.php#L21" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 21</a>

#Class Definition#

**Definition**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definitiondecorator.md">DefinitionDecorator</a> </dd>
</dl>



- - -

<p class="signature"><span class='k'>public  class</span> <span class='nx'>Definition</span></p>

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
<td><span class='k'>protected </span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="#arguments"> $arguments</a>
                                </p></td>
</tr>
</table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(string class, array arguments)</p><p class="description">Constructor.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html>Definition</a></span></td>
<td class="description"><p class="name"><a href="#setfactoryclass">setFactoryClass</a>(string factoryClass)</p><p class="description">Sets the name of the class that acts as a factory using the factory method,
which will be invoked statically.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getfactoryclass">getFactoryClass</a>()</p><p class="description">Gets the factory class.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html>Definition</a></span></td>
<td class="description"><p class="name"><a href="#setfactorymethod">setFactoryMethod</a>(string factoryMethod)</p><p class="description">Sets the factory method able to create an instance of this class.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getfactorymethod">getFactoryMethod</a>()</p><p class="description">Gets the factory method.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html>Definition</a></span></td>
<td class="description"><p class="name"><a href="#setfactoryservice">setFactoryService</a>(string factoryService)</p><p class="description">Sets the name of the service that acts as a factory using the factory method.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getfactoryservice">getFactoryService</a>()</p><p class="description">Gets the factory service id.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html>Definition</a></span></td>
<td class="description"><p class="name"><a href="#setclass">setClass</a>(string class)</p><p class="description">Sets the service class.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getclass">getClass</a>()</p><p class="description">Sets the service class.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html>Definition</a></span></td>
<td class="description"><p class="name"><a href="#setarguments">setArguments</a>(array arguments)</p><p class="description">Sets the arguments to pass to the service constructor/factory method.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setproperties">setProperties</a>(mixed properties)</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#getproperties">getProperties</a>()</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setproperty">setProperty</a>(mixed name, mixed value)</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html>Definition</a></span></td>
<td class="description"><p class="name"><a href="#addargument">addArgument</a>(mixed argument)</p><p class="description">Adds an argument to pass to the service constructor/factory method.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html>Definition</a></span></td>
<td class="description"><p class="name"><a href="#replaceargument">replaceArgument</a>(integer index, mixed argument)</p><p class="description">Sets a specific argument</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name"><a href="#getarguments">getArguments</a>()</p><p class="description">Gets the arguments to pass to the service constructor/factory method.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#getargument">getArgument</a>(integer index)</p><p class="description">Gets an argument to pass to the service constructor/factory method.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html>Definition</a></span></td>
<td class="description"><p class="name"><a href="#setmethodcalls">setMethodCalls</a>(array calls)</p><p class="description">Sets the methods to call after service initialization.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html>Definition</a></span></td>
<td class="description"><p class="name"><a href="#addmethodcall">addMethodCall</a>(string method, array arguments)</p><p class="description">Adds a method to call after service initialization.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html>Definition</a></span></td>
<td class="description"><p class="name"><a href="#removemethodcall">removeMethodCall</a>(string method)</p><p class="description">Removes a method to call after service initialization.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>Boolean</span></td>
<td class="description"><p class="name"><a href="#hasmethodcall">hasMethodCall</a>(string method)</p><p class="description">Check if the current definition has a given method to call after service initialization.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name"><a href="#getmethodcalls">getMethodCalls</a>()</p><p class="description">Gets the methods to call after service initialization.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html>Definition</a></span></td>
<td class="description"><p class="name"><a href="#settags">setTags</a>(array tags)</p><p class="description">Sets tags for this definition</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name"><a href="#gettags">getTags</a>()</p><p class="description">Returns all tags.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name"><a href="#gettag">getTag</a>(string name)</p><p class="description">Gets a tag by name.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html>Definition</a></span></td>
<td class="description"><p class="name"><a href="#addtag">addTag</a>(string name, array attributes)</p><p class="description">Adds a tag for this definition.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>Boolean</span></td>
<td class="description"><p class="name"><a href="#hastag">hasTag</a>(string name)</p><p class="description">Whether this definition has a tag with the given name</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html>Definition</a></span></td>
<td class="description"><p class="name"><a href="#cleartags">clearTags</a>()</p><p class="description">Clears the tags for this definition.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html>Definition</a></span></td>
<td class="description"><p class="name"><a href="#setfile">setFile</a>(string file)</p><p class="description">Sets a file to require before creating the service.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getfile">getFile</a>()</p><p class="description">Gets the file to require before creating the service.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html>Definition</a></span></td>
<td class="description"><p class="name"><a href="#setscope">setScope</a>(string scope)</p><p class="description">Sets the scope of the service</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getscope">getScope</a>()</p><p class="description">Returns the scope of the service</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html>Definition</a></span></td>
<td class="description"><p class="name"><a href="#setpublic">setPublic</a>(Boolean boolean)</p><p class="description">Sets the visibility of this service.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>Boolean</span></td>
<td class="description"><p class="name"><a href="#ispublic">isPublic</a>()</p><p class="description">Whether this service is public facing</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html>Definition</a></span></td>
<td class="description"><p class="name"><a href="#setsynthetic">setSynthetic</a>(Boolean boolean)</p><p class="description">Sets whether this definition is synthetic, that is not constructed by the
container, but dynamically injected.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>Boolean</span></td>
<td class="description"><p class="name"><a href="#issynthetic">isSynthetic</a>()</p><p class="description">Whether this definition is synthetic, that is not constructed by the
container, but dynamically injected.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html>Definition</a></span></td>
<td class="description"><p class="name"><a href="#setabstract">setAbstract</a>(Boolean boolean)</p><p class="description">Whether this definition is abstract, that means it merely serves as a
template for other definitions.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>Boolean</span></td>
<td class="description"><p class="name"><a href="#isabstract">isAbstract</a>()</p><p class="description">Whether this definition is abstract, that means it merely serves as a
template for other definitions.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html>Definition</a></span></td>
<td class="description"><p class="name"><a href="#setconfigurator">setConfigurator</a>(mixed callable)</p><p class="description">Sets a configurator to call after the service is fully initialized.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#getconfigurator">getConfigurator</a>()</p><p class="description">Gets the configurator to call after the service is fully initialized.</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Definition.php#L47" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 47</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (string class, array arguments)

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

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Definition.php#L70" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 70</a>

<h3 id="setFactoryClass()">setFactoryClass</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html>Definition</a></span> <span class='nf'>setFactoryClass</span> (string factoryClass)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Definition.php#L84" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 84</a>

<h3 id="getFactoryClass()">getFactoryClass</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getFactoryClass</span> ()

<div class="details">
<p>Gets the factory class.</p><dl>
<dt>Returns:</dt>
<dd>The factory class name</dd>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Definition.php#L98" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 98</a>

<h3 id="setFactoryMethod()">setFactoryMethod</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html>Definition</a></span> <span class='nf'>setFactoryMethod</span> (string factoryMethod)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Definition.php#L112" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 112</a>

<h3 id="getFactoryMethod()">getFactoryMethod</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getFactoryMethod</span> ()

<div class="details">
<p>Gets the factory method.</p><dl>
<dt>Returns:</dt>
<dd>The factory method name</dd>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Definition.php#L126" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 126</a>

<h3 id="setFactoryService()">setFactoryService</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html>Definition</a></span> <span class='nf'>setFactoryService</span> (string factoryService)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Definition.php#L140" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 140</a>

<h3 id="getFactoryService()">getFactoryService</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getFactoryService</span> ()

<div class="details">
<p>Gets the factory service id.</p><dl>
<dt>Returns:</dt>
<dd>The factory service id</dd>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Definition.php#L154" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 154</a>

<h3 id="setClass()">setClass</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html>Definition</a></span> <span class='nf'>setClass</span> (string class)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Definition.php#L168" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 168</a>

<h3 id="getClass()">getClass</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getClass</span> ()

<div class="details">
<p>Sets the service class.</p><dl>
<dt>Returns:</dt>
<dd>The service class</dd>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Definition.php#L182" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 182</a>

<h3 id="setArguments()">setArguments</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html>Definition</a></span> <span class='nf'>setArguments</span> (array arguments)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Definition.php#L192" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 192</a>

<h3 id="setProperties()">setProperties</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setProperties</span> (mixed properties)

<div class="details">
<p></p><dl>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Definition.php#L202" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 202</a>

<h3 id="getProperties()">getProperties</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>getProperties</span> ()

<div class="details">
<p></p><dl>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Definition.php#L210" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 210</a>

<h3 id="setProperty()">setProperty</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setProperty</span> (mixed name, mixed value)

<div class="details">
<p></p><dl>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Definition.php#L226" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 226</a>

<h3 id="addArgument()">addArgument</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html>Definition</a></span> <span class='nf'>addArgument</span> (mixed argument)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Definition.php#L243" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 243</a>

<h3 id="replaceArgument()">replaceArgument</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html>Definition</a></span> <span class='nf'>replaceArgument</span> (integer index, mixed argument)

<div class="details">
<p>Sets a specific argument</p><dl>
<dt>Returns:</dt>
<dd>The current instance</dd>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Definition.php#L261" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 261</a>

<h3 id="getArguments()">getArguments</h3>
<span class='k'></span> <span class='nx'>array</span> <span class='nf'>getArguments</span> ()

<div class="details">
<p>Gets the arguments to pass to the service constructor/factory method.</p><dl>
<dt>Returns:</dt>
<dd>The array of arguments</dd>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Definition.php#L275" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 275</a>

<h3 id="getArgument()">getArgument</h3>
<span class='k'></span> <span class='nx'>mixed</span> <span class='nf'>getArgument</span> (integer index)

<div class="details">
<p>Gets an argument to pass to the service constructor/factory method.</p><dl>
<dt>Returns:</dt>
<dd>The argument value</dd>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Definition.php#L293" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 293</a>

<h3 id="setMethodCalls()">setMethodCalls</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html>Definition</a></span> <span class='nf'>setMethodCalls</span> (array calls)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Definition.php#L313" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 313</a>

<h3 id="addMethodCall()">addMethodCall</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html>Definition</a></span> <span class='nf'>addMethodCall</span> (string method, array arguments)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Definition.php#L329" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 329</a>

<h3 id="removeMethodCall()">removeMethodCall</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html>Definition</a></span> <span class='nf'>removeMethodCall</span> (string method)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Definition.php#L350" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 350</a>

<h3 id="hasMethodCall()">hasMethodCall</h3>
<span class='k'></span> <span class='nx'>Boolean</span> <span class='nf'>hasMethodCall</span> (string method)

<div class="details">
<p>Check if the current definition has a given method to call after service initialization.</p><dl>
<dt>Parameters:</dt>
<dd>method - The method name to search for</dd>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Definition.php#L368" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 368</a>

<h3 id="getMethodCalls()">getMethodCalls</h3>
<span class='k'></span> <span class='nx'>array</span> <span class='nf'>getMethodCalls</span> ()

<div class="details">
<p>Gets the methods to call after service initialization.</p><dl>
<dt>Returns:</dt>
<dd>An array of method calls</dd>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Definition.php#L382" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 382</a>

<h3 id="setTags()">setTags</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html>Definition</a></span> <span class='nf'>setTags</span> (array tags)

<div class="details">
<p>Sets tags for this definition</p><dl>
<dt>Returns:</dt>
<dd>the current instance</dd>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Definition.php#L396" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 396</a>

<h3 id="getTags()">getTags</h3>
<span class='k'></span> <span class='nx'>array</span> <span class='nf'>getTags</span> ()

<div class="details">
<p>Returns all tags.</p><dl>
<dt>Returns:</dt>
<dd>An array of tags</dd>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Definition.php#L410" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 410</a>

<h3 id="getTag()">getTag</h3>
<span class='k'></span> <span class='nx'>array</span> <span class='nf'>getTag</span> (string name)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Definition.php#L425" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 425</a>

<h3 id="addTag()">addTag</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html>Definition</a></span> <span class='nf'>addTag</span> (string name, array attributes)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Definition.php#L441" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 441</a>

<h3 id="hasTag()">hasTag</h3>
<span class='k'></span> <span class='nx'>Boolean</span> <span class='nf'>hasTag</span> (string name)

<div class="details">
<p>Whether this definition has a tag with the given name</p><dl>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Definition.php#L453" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 453</a>

<h3 id="clearTags()">clearTags</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html>Definition</a></span> <span class='nf'>clearTags</span> ()

<div class="details">
<p>Clears the tags for this definition.</p><dl>
<dt>Returns:</dt>
<dd>The current instance</dd>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Definition.php#L469" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 469</a>

<h3 id="setFile()">setFile</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html>Definition</a></span> <span class='nf'>setFile</span> (string file)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Definition.php#L483" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 483</a>

<h3 id="getFile()">getFile</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getFile</span> ()

<div class="details">
<p>Gets the file to require before creating the service.</p><dl>
<dt>Returns:</dt>
<dd>The full pathname to include</dd>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Definition.php#L497" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 497</a>

<h3 id="setScope()">setScope</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html>Definition</a></span> <span class='nf'>setScope</span> (string scope)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Definition.php#L511" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 511</a>

<h3 id="getScope()">getScope</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getScope</span> ()

<div class="details">
<p>Returns the scope of the service</p><dl>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Definition.php#L524" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 524</a>

<h3 id="setPublic()">setPublic</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html>Definition</a></span> <span class='nf'>setPublic</span> (Boolean boolean)

<div class="details">
<p>Sets the visibility of this service.</p><dl>
<dt>Returns:</dt>
<dd>The current instance</dd>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Definition.php#L538" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 538</a>

<h3 id="isPublic()">isPublic</h3>
<span class='k'></span> <span class='nx'>Boolean</span> <span class='nf'>isPublic</span> ()

<div class="details">
<p>Whether this service is public facing</p><dl>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Definition.php#L553" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 553</a>

<h3 id="setSynthetic()">setSynthetic</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html>Definition</a></span> <span class='nf'>setSynthetic</span> (Boolean boolean)

<div class="details">
<p>Sets whether this definition is synthetic, that is not constructed by the
container, but dynamically injected.</p><dl>
<dt>Returns:</dt>
<dd>the current instance</dd>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Definition.php#L568" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 568</a>

<h3 id="isSynthetic()">isSynthetic</h3>
<span class='k'></span> <span class='nx'>Boolean</span> <span class='nf'>isSynthetic</span> ()

<div class="details">
<p>Whether this definition is synthetic, that is not constructed by the
container, but dynamically injected.</p><dl>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Definition.php#L583" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 583</a>

<h3 id="setAbstract()">setAbstract</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html>Definition</a></span> <span class='nf'>setAbstract</span> (Boolean boolean)

<div class="details">
<p>Whether this definition is abstract, that means it merely serves as a
template for other definitions.</p><dl>
<dt>Returns:</dt>
<dd>the current instance</dd>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Definition.php#L598" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 598</a>

<h3 id="isAbstract()">isAbstract</h3>
<span class='k'></span> <span class='nx'>Boolean</span> <span class='nf'>isAbstract</span> ()

<div class="details">
<p>Whether this definition is abstract, that means it merely serves as a
template for other definitions.</p><dl>
<dt>Api.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Definition.php#L612" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 612</a>

<h3 id="setConfigurator()">setConfigurator</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/definition.html>Definition</a></span> <span class='nf'>setConfigurator</span> (mixed callable)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Definition.php#L626" >framework\libs\symfony-components\Symfony\Component\DependencyInjection\Definition.php at line 626</a>

<h3 id="getConfigurator()">getConfigurator</h3>
<span class='k'></span> <span class='nx'>mixed</span> <span class='nf'>getConfigurator</span> ()

<div class="details">
<p>Gets the configurator to call after the service is fully initialized.</p><dl>
<dt>Returns:</dt>
<dd>The PHP callable to call</dd>
<dt>Api.</dt>
</dl>

</div>

- - -

