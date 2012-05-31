
- - -

**Symfony\Component\DependencyInjection\ContainerBuilder**
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerBuilder.php at line 29</div>
#Class ContainerBuilder#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/container.html">Container</a>
    ***ContainerBuilder**


- - -

<p class="signature">public  class **ContainerBuilder**
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/container.html">Container</a>

</p>

<div class="comment" id="overview_description"><p>ContainerBuilder is a DI container that provides an API to easily describe services.</p></div>

<dl>
<dt>Author:</dt>
<dd>Fabien Potencier <fabien@symfony.com></dd>
<dt>Api.</dt>
</dl>

- - -

<table class="inherit">
<tr><th colspan="2">Fields inherited from Symfony\Component\DependencyInjection\Container</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/container.html#loading">loading</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/container.html#parameterBag">parameterBag</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/container.html#scopeChildren">scopeChildren</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/container.html#scopeStacks">scopeStacks</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/container.html#scopedServices">scopedServices</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/container.html#scopes">scopes</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/container.html#services">services</a></td></tr></table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#registerextension">registerExtension</a>(<a href="../../../symfony/component/dependencyinjection/extension/extensioninterface.html">ExtensionInterface</a> extension)</p><p class="description">Registers an extension.</p></td>
</tr>
<tr>
<td class="type">  <a href="../../../symfony/component/dependencyinjection/extension/extensioninterface.html">ExtensionInterface</a></td>
<td class="description"><p class="name"><a href="#getextension">getExtension</a>(string name)</p><p class="description">Returns an extension by alias or namespace.</p></td>
</tr>
<tr>
<td class="type">  array</td>
<td class="description"><p class="name"><a href="#getextensions">getExtensions</a>()</p><p class="description">Returns all registered extensions.</p></td>
</tr>
<tr>
<td class="type">  Boolean</td>
<td class="description"><p class="name"><a href="#hasextension">hasExtension</a>(string name)</p><p class="description">Checks if we have an extension.</p></td>
</tr>
<tr>
<td class="type">  ResourceInterface[]</td>
<td class="description"><p class="name"><a href="#getresources">getResources</a>()</p><p class="description">Returns an array of resources loaded to build this configuration.</p></td>
</tr>
<tr>
<td class="type">  <a href="../../../symfony/component/dependencyinjection/containerbuilder.html">ContainerBuilder</a></td>
<td class="description"><p class="name"><a href="#addresource">addResource</a>(ResourceInterface resource)</p><p class="description">Adds a resource for this configuration.</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#addobjectresource">addObjectResource</a>(object object)</p><p class="description">Adds the object class hierarchy as resources.</p></td>
</tr>
<tr>
<td class="type">  <a href="../../../symfony/component/dependencyinjection/containerbuilder.html">ContainerBuilder</a></td>
<td class="description"><p class="name"><a href="#loadfromextension">loadFromExtension</a>(string extension, array values)</p><p class="description">Loads the configuration for an extension.</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#addcompilerpass">addCompilerPass</a>(<a href="../../../symfony/component/dependencyinjection/compiler/compilerpassinterface.html">CompilerPassInterface</a> pass, string type)</p><p class="description">Adds a compiler pass.</p></td>
</tr>
<tr>
<td class="type">  <a href="../../../symfony/component/dependencyinjection/compiler/passconfig.html">PassConfig</a></td>
<td class="description"><p class="name"><a href="#getcompilerpassconfig">getCompilerPassConfig</a>()</p><p class="description">Returns the compiler pass config which can then be modified.</p></td>
</tr>
<tr>
<td class="type">  <a href="../../../symfony/component/dependencyinjection/compiler/compiler.html">Compiler</a></td>
<td class="description"><p class="name"><a href="#getcompiler">getCompiler</a>()</p><p class="description">Returns the compiler.</p></td>
</tr>
<tr>
<td class="type">  array</td>
<td class="description"><p class="name"><a href="#getscopes">getScopes</a>()</p><p class="description">Returns all Scopes.</p></td>
</tr>
<tr>
<td class="type">  array</td>
<td class="description"><p class="name"><a href="#getscopechildren">getScopeChildren</a>()</p><p class="description">Returns all Scope children.</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#set">set</a>(string id, object service, string scope)</p><p class="description">Sets a service.</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#removedefinition">removeDefinition</a>(string id)</p><p class="description">Removes a service definition.</p></td>
</tr>
<tr>
<td class="type">  Boolean</td>
<td class="description"><p class="name"><a href="#has">has</a>(string id)</p><p class="description">Returns true if the given service is defined.</p></td>
</tr>
<tr>
<td class="type">  object</td>
<td class="description"><p class="name"><a href="#get">get</a>(string id, integer invalidBehavior)</p><p class="description">Gets a service.</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#merge">merge</a>(<a href="../../../symfony/component/dependencyinjection/containerbuilder.html">ContainerBuilder</a> container)</p><p class="description">Merges a ContainerBuilder with the current ContainerBuilder configuration.
</p></td>
</tr>
<tr>
<td class="type">  array</td>
<td class="description"><p class="name"><a href="#getextensionconfig">getExtensionConfig</a>(string name)</p><p class="description">Returns the configuration array for the given extension.</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#compile">compile</a>()</p><p class="description">Compiles the container.
</p></td>
</tr>
<tr>
<td class="type">  array</td>
<td class="description"><p class="name"><a href="#getserviceids">getServiceIds</a>()</p><p class="description">Gets all service ids.</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#addaliases">addAliases</a>(array aliases)</p><p class="description">Adds the service aliases.</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#setaliases">setAliases</a>(array aliases)</p><p class="description">Sets the service aliases.</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#setalias">setAlias</a>(string alias, mixed id)</p><p class="description">Sets an alias for an existing service.</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#removealias">removeAlias</a>(string alias)</p><p class="description">Removes an alias.</p></td>
</tr>
<tr>
<td class="type">  Boolean</td>
<td class="description"><p class="name"><a href="#hasalias">hasAlias</a>(string id)</p><p class="description">Returns true if an alias exists under the given identifier.</p></td>
</tr>
<tr>
<td class="type">  array</td>
<td class="description"><p class="name"><a href="#getaliases">getAliases</a>()</p><p class="description">Gets all defined aliases.</p></td>
</tr>
<tr>
<td class="type">  string</td>
<td class="description"><p class="name"><a href="#getalias">getAlias</a>(string id)</p><p class="description">Gets an alias.</p></td>
</tr>
<tr>
<td class="type">  <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a></td>
<td class="description"><p class="name"><a href="#register">register</a>(string id, string class)</p><p class="description">Registers a service definition.
</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#adddefinitions">addDefinitions</a>(<a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a> definitions)</p><p class="description">Adds the service definitions.</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#setdefinitions">setDefinitions</a>(array definitions)</p><p class="description">Sets the service definitions.</p></td>
</tr>
<tr>
<td class="type">  array</td>
<td class="description"><p class="name"><a href="#getdefinitions">getDefinitions</a>()</p><p class="description">Gets all service definitions.</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#setdefinition">setDefinition</a>(string id, <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a> definition)</p><p class="description">Sets a service definition.</p></td>
</tr>
<tr>
<td class="type">  Boolean</td>
<td class="description"><p class="name"><a href="#hasdefinition">hasDefinition</a>(string id)</p><p class="description">Returns true if a service definition exists under the given identifier.</p></td>
</tr>
<tr>
<td class="type">  <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a></td>
<td class="description"><p class="name"><a href="#getdefinition">getDefinition</a>(string id)</p><p class="description">Gets a service definition.</p></td>
</tr>
<tr>
<td class="type">  <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a></td>
<td class="description"><p class="name"><a href="#finddefinition">findDefinition</a>(string id)</p><p class="description">Gets a service definition by id or alias.
</p></td>
</tr>
<tr>
<td class="type">  mixed</td>
<td class="description"><p class="name"><a href="#resolveservices">resolveServices</a>(mixed value)</p><p class="description">Replaces service references by the real service instance.</p></td>
</tr>
<tr>
<td class="type">  array</td>
<td class="description"><p class="name"><a href="#findtaggedserviceids">findTaggedServiceIds</a>(string name)</p><p class="description">Returns service ids for a given tag.</p></td>
</tr>
<tr>
<td class="type"> static  array</td>
<td class="description"><p class="name"><a href="#getserviceconditionals">getServiceConditionals</a>(mixed value)</p><p class="description">Returns the Service Conditionals.</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Symfony\Component\DependencyInjection\Container</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/container.html#__construct()">__construct</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/container.html#addScope()">addScope</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/container.html#camelize()">camelize</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/container.html#compile()">compile</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/container.html#enterScope()">enterScope</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/container.html#get()">get</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/container.html#getParameter()">getParameter</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/container.html#getParameterBag()">getParameterBag</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/container.html#getServiceIds()">getServiceIds</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/container.html#has()">has</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/container.html#hasParameter()">hasParameter</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/container.html#hasScope()">hasScope</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/container.html#isFrozen()">isFrozen</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/container.html#isScopeActive()">isScopeActive</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/container.html#leaveScope()">leaveScope</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/container.html#set()">set</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/container.html#setParameter()">setParameter</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/container.html#underscore()">underscore</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerBuilder.php at line 47</div>
<h3 id="registerExtension()">registerExtension</h3>

public  void **registerExtension** (<a href="../../../symfony/component/dependencyinjection/extension/extensioninterface.html">ExtensionInterface</a> extension)<div class="details">
<p>Registers an extension.</p><dl>
<dt>Parameters:</dt>
<dd>extension - An extension instance</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerBuilder.php at line 64</div>
<h3 id="getExtension()">getExtension</h3>

public  <a href="../../../symfony/component/dependencyinjection/extension/extensioninterface.html">ExtensionInterface</a> **getExtension** (string name)<div class="details">
<p>Returns an extension by alias or namespace.</p><dl>
<dt>Parameters:</dt>
<dd>name - An alias or a namespace</dd>
<dt>Returns:</dt>
<dd>An extension instance</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerBuilder.php at line 83</div>
<h3 id="getExtensions()">getExtensions</h3>

public  array **getExtensions** ()<div class="details">
<p>Returns all registered extensions.</p><dl>
<dt>Returns:</dt>
<dd>An array of ExtensionInterface</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerBuilder.php at line 95</div>
<h3 id="hasExtension()">hasExtension</h3>

public  Boolean **hasExtension** (string name)<div class="details">
<p>Checks if we have an extension.</p><dl>
<dt>Parameters:</dt>
<dd>name - The name of the extension</dd>
<dt>Returns:</dt>
<dd>If the extension exists</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerBuilder.php at line 106</div>
<h3 id="getResources()">getResources</h3>

public  ResourceInterface[] **getResources** ()<div class="details">
<p>Returns an array of resources loaded to build this configuration.</p><dl>
<dt>Returns:</dt>
<dd>An array of resources</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerBuilder.php at line 119</div>
<h3 id="addResource()">addResource</h3>

public  <a href="../../../symfony/component/dependencyinjection/containerbuilder.html">ContainerBuilder</a> **addResource** (ResourceInterface resource)<div class="details">
<p>Adds a resource for this configuration.</p><dl>
<dt>Parameters:</dt>
<dd>resource - A resource instance</dd>
<dt>Returns:</dt>
<dd>The current instance</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerBuilder.php at line 132</div>
<h3 id="addObjectResource()">addObjectResource</h3>

public  void **addObjectResource** (object object)<div class="details">
<p>Adds the object class hierarchy as resources.</p><dl>
<dt>Parameters:</dt>
<dd>object - An object instance</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerBuilder.php at line 149</div>
<h3 id="loadFromExtension()">loadFromExtension</h3>

public  <a href="../../../symfony/component/dependencyinjection/containerbuilder.html">ContainerBuilder</a> **loadFromExtension** (string extension, array values)<div class="details">
<p>Loads the configuration for an extension.</p><dl>
<dt>Parameters:</dt>
<dd>extension - The extension alias or namespace</dd>
<dd>values - An array of values that customizes the extension</dd>
<dt>Returns:</dt>
<dd>The current instance</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerBuilder.php at line 169</div>
<h3 id="addCompilerPass()">addCompilerPass</h3>

public  void **addCompilerPass** (<a href="../../../symfony/component/dependencyinjection/compiler/compilerpassinterface.html">CompilerPassInterface</a> pass, string type)<div class="details">
<p>Adds a compiler pass.</p><dl>
<dt>Parameters:</dt>
<dd>pass - A compiler pass</dd>
<dd>type - The type of compiler pass</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerBuilder.php at line 186</div>
<h3 id="getCompilerPassConfig()">getCompilerPassConfig</h3>

public  <a href="../../../symfony/component/dependencyinjection/compiler/passconfig.html">PassConfig</a> **getCompilerPassConfig** ()<div class="details">
<p>Returns the compiler pass config which can then be modified.</p><dl>
<dt>Returns:</dt>
<dd>The compiler pass config</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerBuilder.php at line 201</div>
<h3 id="getCompiler()">getCompiler</h3>

public  <a href="../../../symfony/component/dependencyinjection/compiler/compiler.html">Compiler</a> **getCompiler** ()<div class="details">
<p>Returns the compiler.</p><dl>
<dt>Returns:</dt>
<dd>The compiler</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerBuilder.php at line 216</div>
<h3 id="getScopes()">getScopes</h3>

public  array **getScopes** ()<div class="details">
<p>Returns all Scopes.</p><dl>
<dt>Returns:</dt>
<dd>An array of scopes</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerBuilder.php at line 227</div>
<h3 id="getScopeChildren()">getScopeChildren</h3>

public  array **getScopeChildren** ()<div class="details">
<p>Returns all Scope children.</p><dl>
<dt>Returns:</dt>
<dd>An array of scope children.</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerBuilder.php at line 242</div>
<h3 id="set()">set</h3>

public  void **set** (string id, object service, string scope)<div class="details">
<p>Sets a service.</p><dl>
<dt>Parameters:</dt>
<dd>id - The service identifier</dd>
<dd>service - The service instance</dd>
<dd>scope - The scope</dd>
<dt>Throws:</dt>
<dd>BadMethodCallException</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerBuilder.php at line 261</div>
<h3 id="removeDefinition()">removeDefinition</h3>

public  void **removeDefinition** (string id)<div class="details">
<p>Removes a service definition.</p><dl>
<dt>Parameters:</dt>
<dd>id - The service identifier</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerBuilder.php at line 274</div>
<h3 id="has()">has</h3>

public  Boolean **has** (string id)<div class="details">
<p>Returns true if the given service is defined.</p><dl>
<dt>Parameters:</dt>
<dd>id - The service identifier</dd>
<dt>Returns:</dt>
<dd>true if the service is defined, false otherwise</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerBuilder.php at line 295</div>
<h3 id="get()">get</h3>

public  object **get** (string id, integer invalidBehavior)<div class="details">
<p>Gets a service.</p><dl>
<dt>Parameters:</dt>
<dd>id - The service identifier</dd>
<dd>invalidBehavior - The behavior when the service does not exist</dd>
<dt>Returns:</dt>
<dd>The associated service</dd>
<dt>Throws:</dt>
<dd><a href="../../../symfony/component/dependencyinjection/exception/invalidargumentexception.html">\InvalidArgumentException</a> - if the service is not defined</dd>
<dd>\LogicException - if the service has a circular reference to itself</dd>
<dt>See Also:</dt>
<dd><a href="../../../symfony/component/dependencyinjection/reference.html">Reference</a></dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerBuilder.php at line 352</div>
<h3 id="merge()">merge</h3>

public  void **merge** (<a href="../../../symfony/component/dependencyinjection/containerbuilder.html">ContainerBuilder</a> container)<div class="details">
<p>Merges a ContainerBuilder with the current ContainerBuilder configuration.</p><p>Service definitions overrides the current defined ones.</p><p>But for parameters, they are overridden by the current ones. It allows
the parameters passed to the container constructor to have precedence
over the loaded ones.</p><p>$container = new ContainerBuilder(array('foo' => 'bar'));
$loader = new LoaderXXX($container);
$loader->load('resource_name');
$container->register('foo', new stdClass());</p><p>In the above example, even if the loaded resource defines a foo
parameter, the value will still be 'bar' as defined in the ContainerBuilder
constructor.</p><dl>
<dt>Parameters:</dt>
<dd>container - The ContainerBuilder instance to merge.</dd>
<dt>Throws:</dt>
<dd>\LogicException - when this ContainerBuilder is frozen</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerBuilder.php at line 383</div>
<h3 id="getExtensionConfig()">getExtensionConfig</h3>

public  array **getExtensionConfig** (string name)<div class="details">
<p>Returns the configuration array for the given extension.</p><dl>
<dt>Parameters:</dt>
<dd>name - The name of the extension</dd>
<dt>Returns:</dt>
<dd>An array of configuration</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerBuilder.php at line 407</div>
<h3 id="compile()">compile</h3>

public  void **compile** ()<div class="details">
<p>Compiles the container.</p><p>This method passes the container to compiler
passes whose job is to manipulate and optimize
the container.</p><p>The main compiler passes roughly do four things:</p><p>* The extension configurations are merged;
* Parameter values are resolved;
* The parameter bag is frozen;
* Extension loading is disabled.</p><dl>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerBuilder.php at line 428</div>
<h3 id="getServiceIds()">getServiceIds</h3>

public  array **getServiceIds** ()<div class="details">
<p>Gets all service ids.</p><dl>
<dt>Returns:</dt>
<dd>An array of all defined service ids</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerBuilder.php at line 439</div>
<h3 id="addAliases()">addAliases</h3>

public  void **addAliases** (array aliases)<div class="details">
<p>Adds the service aliases.</p><dl>
<dt>Parameters:</dt>
<dd>aliases - An array of aliases</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerBuilder.php at line 452</div>
<h3 id="setAliases()">setAliases</h3>

public  void **setAliases** (array aliases)<div class="details">
<p>Sets the service aliases.</p><dl>
<dt>Parameters:</dt>
<dd>aliases - An array of service definitions</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerBuilder.php at line 465</div>
<h3 id="setAlias()">setAlias</h3>

public  void **setAlias** (string alias, mixed id)<div class="details">
<p>Sets an alias for an existing service.</p><dl>
<dt>Parameters:</dt>
<dd>alias - The alias to create</dd>
<dd>id - The service to alias</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerBuilder.php at line 490</div>
<h3 id="removeAlias()">removeAlias</h3>

public  void **removeAlias** (string alias)<div class="details">
<p>Removes an alias.</p><dl>
<dt>Parameters:</dt>
<dd>alias - The alias to remove</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerBuilder.php at line 503</div>
<h3 id="hasAlias()">hasAlias</h3>

public  Boolean **hasAlias** (string id)<div class="details">
<p>Returns true if an alias exists under the given identifier.</p><dl>
<dt>Parameters:</dt>
<dd>id - The service identifier</dd>
<dt>Returns:</dt>
<dd>true if the alias exists, false otherwise</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerBuilder.php at line 514</div>
<h3 id="getAliases()">getAliases</h3>

public  array **getAliases** ()<div class="details">
<p>Gets all defined aliases.</p><dl>
<dt>Returns:</dt>
<dd>An array of aliases</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerBuilder.php at line 529</div>
<h3 id="getAlias()">getAlias</h3>

public  string **getAlias** (string id)<div class="details">
<p>Gets an alias.</p><dl>
<dt>Parameters:</dt>
<dd>id - The service identifier</dd>
<dt>Returns:</dt>
<dd>The aliased service identifier</dd>
<dt>Throws:</dt>
<dd><a href="../../../symfony/component/dependencyinjection/exception/invalidargumentexception.html">\InvalidArgumentException</a> - if the alias does not exist</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerBuilder.php at line 552</div>
<h3 id="register()">register</h3>

public  <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a> **register** (string id, string class)<div class="details">
<p>Registers a service definition.</p><p>This methods allows for simple registration of service definition
with a fluid interface.</p><dl>
<dt>Parameters:</dt>
<dd>id - The service identifier</dd>
<dd>class - The service class</dd>
<dt>Returns:</dt>
<dd>A Definition instance</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerBuilder.php at line 563</div>
<h3 id="addDefinitions()">addDefinitions</h3>

public  void **addDefinitions** (<a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a> definitions)<div class="details">
<p>Adds the service definitions.</p><dl>
<dt>Parameters:</dt>
<dd>definitions - An array of service definitions</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerBuilder.php at line 576</div>
<h3 id="setDefinitions()">setDefinitions</h3>

public  void **setDefinitions** (array definitions)<div class="details">
<p>Sets the service definitions.</p><dl>
<dt>Parameters:</dt>
<dd>definitions - An array of service definitions</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerBuilder.php at line 588</div>
<h3 id="getDefinitions()">getDefinitions</h3>

public  array **getDefinitions** ()<div class="details">
<p>Gets all service definitions.</p><dl>
<dt>Returns:</dt>
<dd>An array of Definition instances</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerBuilder.php at line 602</div>
<h3 id="setDefinition()">setDefinition</h3>

public  void **setDefinition** (string id, <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a> definition)<div class="details">
<p>Sets a service definition.</p><dl>
<dt>Parameters:</dt>
<dd>id - The service identifier</dd>
<dd>definition - A Definition instance</dd>
<dt>Throws:</dt>
<dd>BadMethodCallException</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerBuilder.php at line 623</div>
<h3 id="hasDefinition()">hasDefinition</h3>

public  Boolean **hasDefinition** (string id)<div class="details">
<p>Returns true if a service definition exists under the given identifier.</p><dl>
<dt>Parameters:</dt>
<dd>id - The service identifier</dd>
<dt>Returns:</dt>
<dd>true if the service definition exists, false otherwise</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerBuilder.php at line 638</div>
<h3 id="getDefinition()">getDefinition</h3>

public  <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a> **getDefinition** (string id)<div class="details">
<p>Gets a service definition.</p><dl>
<dt>Parameters:</dt>
<dd>id - The service identifier</dd>
<dt>Returns:</dt>
<dd>A Definition instance</dd>
<dt>Throws:</dt>
<dd><a href="../../../symfony/component/dependencyinjection/exception/invalidargumentexception.html">\InvalidArgumentException</a> - if the service definition does not exist</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerBuilder.php at line 661</div>
<h3 id="findDefinition()">findDefinition</h3>

public  <a href="../../../symfony/component/dependencyinjection/definition.html">Definition</a> **findDefinition** (string id)<div class="details">
<p>Gets a service definition by id or alias.</p><p>The method "unaliases" recursively to return a Definition instance.</p><dl>
<dt>Parameters:</dt>
<dd>id - The service identifier or alias</dd>
<dt>Returns:</dt>
<dd>A Definition instance</dd>
<dt>Throws:</dt>
<dd><a href="../../../symfony/component/dependencyinjection/exception/invalidargumentexception.html">\InvalidArgumentException</a> - if the service definition does not exist</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerBuilder.php at line 759</div>
<h3 id="resolveServices()">resolveServices</h3>

public  mixed **resolveServices** (mixed value)<div class="details">
<p>Replaces service references by the real service instance.</p><dl>
<dt>Parameters:</dt>
<dd>value - A value</dd>
<dt>Returns:</dt>
<dd>The same value with all service references replaced by the real service instances</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerBuilder.php at line 782</div>
<h3 id="findTaggedServiceIds()">findTaggedServiceIds</h3>

public  array **findTaggedServiceIds** (string name)<div class="details">
<p>Returns service ids for a given tag.</p><dl>
<dt>Parameters:</dt>
<dd>name - The tag name</dd>
<dt>Returns:</dt>
<dd>An array of tags</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ContainerBuilder.php at line 799</div>
<h3 id="getServiceConditionals()">getServiceConditionals</h3>

public static  array **getServiceConditionals** (mixed value)<div class="details">
<p>Returns the Service Conditionals.</p><dl>
<dt>Parameters:</dt>
<dd>value - An array of conditionals to return.</dd>
<dt>Returns:</dt>
<dd>An array of Service conditionals</dd>
</dl>
</div>

- - -

