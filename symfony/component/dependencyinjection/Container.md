
- - -

**Symfony\Component\DependencyInjection\Container**
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Container.php at line 60</div>
#Class Container#

**Container**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/containerbuilder.html">ContainerBuilder</a> </dd>
</dl>

- - -

<p class="signature">public  class **Container**</p>

<div class="comment" id="overview_description"><p>Container is a dependency injection container.</p><p>It gives access to object instances (services).</p><p>Services and parameters are simple key/pair stores.</p><p>Parameter and service keys are case insensitive.</p><p>A service id can contain lowercased letters, digits, underscores, and dots.
Underscores are used to separate words, and dots to group services
under namespaces:</p>
<ul>
<li>request</li>
<li>mysql_session_storage</li>
<li>symfony.mysql_session_storage</li>
</ul>
<p>A service can also be defined by creating a method named
getXXXService(), where XXX is the camelized version of the id:</p>
<ul>
<li>request -> getRequestService()</li>
<li>mysql_session_storage -> getMysqlSessionStorageService()</li>
<li>symfony.mysql_session_storage -> getSymfony_MysqlSessionStorageService()</li>
</ul>
<p>The container can have three possible behaviors when a service does not exist:</p><p>* EXCEPTION_ON_INVALID_REFERENCE: Throws an exception (the default)
* NULL_ON_INVALID_REFERENCE:      Returns null
* IGNORE_ON_INVALID_REFERENCE:    Ignores the wrapping command asking for the reference
(for instance, ignore a setter if the service does not exist)</p></div>

<dl>
<dt>Author:</dt>
<dd>Fabien Potencier <fabien@symfony.com></dd>
<dd>Johannes M. Schmitt <schmittjoh@gmail.com></dd>
<dt>Api.</dt>
</dl>

- - -

<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td class="type">protected  mixed</td>
<td class="description"><p class="name"><a href="#loading">$loading</a></p></td>
</tr>
<tr>
<td class="type">protected  mixed</td>
<td class="description"><p class="name"><a href="#parameterbag">$parameterBag</a></p></td>
</tr>
<tr>
<td class="type">protected  mixed</td>
<td class="description"><p class="name"><a href="#scopechildren">$scopeChildren</a></p></td>
</tr>
<tr>
<td class="type">protected  mixed</td>
<td class="description"><p class="name"><a href="#scopestacks">$scopeStacks</a></p></td>
</tr>
<tr>
<td class="type">protected  mixed</td>
<td class="description"><p class="name"><a href="#scopedservices">$scopedServices</a></p></td>
</tr>
<tr>
<td class="type">protected  mixed</td>
<td class="description"><p class="name"><a href="#scopes">$scopes</a></p></td>
</tr>
<tr>
<td class="type">protected  mixed</td>
<td class="description"><p class="name"><a href="#services">$services</a></p></td>
</tr>
</table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(<a href="../../../symfony/component/dependencyinjection/parameterbag/parameterbaginterface.html">ParameterBagInterface</a> parameterBag)</p><p class="description">Constructor.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#compile">compile</a>()</p><p class="description">Compiles the container.
</p></td>
</tr>
<tr>
<td class="type">  Boolean</td>
<td class="description"><p class="name"><a href="#isfrozen">isFrozen</a>()</p><p class="description">Returns true if the container parameter bag are frozen.</p></td>
</tr>
<tr>
<td class="type">  <a href="../../../symfony/component/dependencyinjection/parameterbag/parameterbaginterface.html">ParameterBagInterface</a></td>
<td class="description"><p class="name"><a href="#getparameterbag">getParameterBag</a>()</p><p class="description">Gets the service container parameter bag.</p></td>
</tr>
<tr>
<td class="type">  mixed</td>
<td class="description"><p class="name"><a href="#getparameter">getParameter</a>(string name)</p><p class="description">Gets a parameter.</p></td>
</tr>
<tr>
<td class="type">  Boolean</td>
<td class="description"><p class="name"><a href="#hasparameter">hasParameter</a>(string name)</p><p class="description">Checks if a parameter exists.</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#setparameter">setParameter</a>(string name, mixed value)</p><p class="description">Sets a parameter.</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#set">set</a>(string id, object service, string scope)</p><p class="description">Sets a service.</p></td>
</tr>
<tr>
<td class="type">  Boolean</td>
<td class="description"><p class="name"><a href="#has">has</a>(string id)</p><p class="description">Returns true if the given service is defined.</p></td>
</tr>
<tr>
<td class="type">  object</td>
<td class="description"><p class="name"><a href="#get">get</a>(string id, integer invalidBehavior)</p><p class="description">Gets a service.
</p></td>
</tr>
<tr>
<td class="type">  array</td>
<td class="description"><p class="name"><a href="#getserviceids">getServiceIds</a>()</p><p class="description">Gets all service ids.</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#enterscope">enterScope</a>(string name)</p><p class="description">This is called when you enter a scope</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#leavescope">leaveScope</a>(string name)</p><p class="description">This is called to leave the current scope, and move back to the parent
scope.</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#addscope">addScope</a>(<a href="../../../symfony/component/dependencyinjection/scopeinterface.html">ScopeInterface</a> scope)</p><p class="description">Adds a scope to the container.</p></td>
</tr>
<tr>
<td class="type">  Boolean</td>
<td class="description"><p class="name"><a href="#hasscope">hasScope</a>(string name)</p><p class="description">Returns whether this container has a certain scope</p></td>
</tr>
<tr>
<td class="type">  Boolean</td>
<td class="description"><p class="name"><a href="#isscopeactive">isScopeActive</a>(string name)</p><p class="description">Returns whether this scope is currently activeThis does not actually check if the passed scope actually exists.</p></td>
</tr>
<tr>
<td class="type"> static  string</td>
<td class="description"><p class="name"><a href="#camelize">camelize</a>(string id)</p><p class="description">Camelizes a string.</p></td>
</tr>
<tr>
<td class="type"> static  string</td>
<td class="description"><p class="name"><a href="#underscore">underscore</a>(string id)</p><p class="description">A string to underscore.</p></td>
</tr>
</table>

##Field Detail##
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Container.php at line 68</div>
<h3 id="loading">loading</h3>

protected  mixed $loading = array()
<div class="details">
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Container.php at line 62</div>
<h3 id="parameterBag">parameterBag</h3>

protected  mixed $parameterBag = true
<div class="details">
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Container.php at line 65</div>
<h3 id="scopeChildren">scopeChildren</h3>

protected  mixed $scopeChildren
<div class="details">
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Container.php at line 67</div>
<h3 id="scopeStacks">scopeStacks</h3>

protected  mixed $scopeStacks
<div class="details">
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Container.php at line 66</div>
<h3 id="scopedServices">scopedServices</h3>

protected  mixed $scopedServices
<div class="details">
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Container.php at line 64</div>
<h3 id="scopes">scopes</h3>

protected  mixed $scopes
<div class="details">
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Container.php at line 63</div>
<h3 id="services">services</h3>

protected  mixed $services
<div class="details">
</div>

- - -

<h2 id="detail_method">Constructor Detail</h2>
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Container.php at line 77</div>
<h3 id="__construct()">__construct</h3>

```php
public  void **__construct**(<a href="../../../symfony/component/dependencyinjection/parameterbag/parameterbaginterface.html">ParameterBagInterface</a> parameterBag)
```
<div class="details">
<p>Constructor.</p><dl>
<dt>Parameters:</dt>
<dd>parameterBag - A ParameterBagInterface instance</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Container.php at line 100</div>
<h3 id="compile()">compile</h3>

public  void **compile** ()<div class="details">
<p>Compiles the container.</p><p>This method does two things:</p><p>* Parameter values are resolved;
* The parameter bag is frozen.</p><dl>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Container.php at line 114</div>
<h3 id="isFrozen()">isFrozen</h3>

public  Boolean **isFrozen** ()<div class="details">
<p>Returns true if the container parameter bag are frozen.</p><dl>
<dt>Returns:</dt>
<dd>true if the container parameter bag are frozen, false otherwise</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Container.php at line 126</div>
<h3 id="getParameterBag()">getParameterBag</h3>

public  <a href="../../../symfony/component/dependencyinjection/parameterbag/parameterbaginterface.html">ParameterBagInterface</a> **getParameterBag** ()<div class="details">
<p>Gets the service container parameter bag.</p><dl>
<dt>Returns:</dt>
<dd>A ParameterBagInterface instance</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Container.php at line 142</div>
<h3 id="getParameter()">getParameter</h3>

public  mixed **getParameter** (string name)<div class="details">
<p>Gets a parameter.</p><dl>
<dt>Parameters:</dt>
<dd>name - The parameter name</dd>
<dt>Returns:</dt>
<dd>The parameter value</dd>
<dt>Throws:</dt>
<dd><a href="../../../symfony/component/dependencyinjection/exception/invalidargumentexception.html">\InvalidArgumentException</a> - if the parameter is not defined</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Container.php at line 156</div>
<h3 id="hasParameter()">hasParameter</h3>

public  Boolean **hasParameter** (string name)<div class="details">
<p>Checks if a parameter exists.</p><dl>
<dt>Parameters:</dt>
<dd>name - The parameter name</dd>
<dt>Returns:</dt>
<dd>The presence of parameter in container</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Container.php at line 169</div>
<h3 id="setParameter()">setParameter</h3>

public  void **setParameter** (string name, mixed value)<div class="details">
<p>Sets a parameter.</p><dl>
<dt>Parameters:</dt>
<dd>name - The parameter name</dd>
<dd>value - The parameter value</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Container.php at line 183</div>
<h3 id="set()">set</h3>

public  void **set** (string id, object service, string scope)<div class="details">
<p>Sets a service.</p><dl>
<dt>Parameters:</dt>
<dd>id - The service identifier</dd>
<dd>service - The service instance</dd>
<dd>scope - The scope of the service</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Container.php at line 211</div>
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

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Container.php at line 235</div>
<h3 id="get()">get</h3>

public  object **get** (string id, integer invalidBehavior)<div class="details">
<p>Gets a service.</p><p>If a service is both defined through a set() method and
with a set*Service() method, the former has always precedence.</p><dl>
<dt>Parameters:</dt>
<dd>id - The service identifier</dd>
<dd>invalidBehavior - The behavior when the service does not exist</dd>
<dt>Returns:</dt>
<dd>The associated service</dd>
<dt>Throws:</dt>
<dd><a href="../../../symfony/component/dependencyinjection/exception/invalidargumentexception.html">\InvalidArgumentException</a> - if the service is not defined</dd>
<dt>See Also:</dt>
<dd><a href="../../../symfony/component/dependencyinjection/reference.html">Reference</a></dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Container.php at line 272</div>
<h3 id="getServiceIds()">getServiceIds</h3>

public  array **getServiceIds** ()<div class="details">
<p>Gets all service ids.</p><dl>
<dt>Returns:</dt>
<dd>An array of all defined service ids</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Container.php at line 293</div>
<h3 id="enterScope()">enterScope</h3>

public  void **enterScope** (string name)<div class="details">
<p>This is called when you enter a scope</p><dl>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Container.php at line 339</div>
<h3 id="leaveScope()">leaveScope</h3>

public  void **leaveScope** (string name)<div class="details">
<p>This is called to leave the current scope, and move back to the parent
scope.</p><dl>
<dt>Parameters:</dt>
<dd>name - The name of the scope to leave</dd>
<dt>Throws:</dt>
<dd><a href="../../../symfony/component/dependencyinjection/exception/invalidargumentexception.html">\InvalidArgumentException</a> - if the scope is not active</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Container.php at line 377</div>
<h3 id="addScope()">addScope</h3>

public  void **addScope** (<a href="../../../symfony/component/dependencyinjection/scopeinterface.html">ScopeInterface</a> scope)<div class="details">
<p>Adds a scope to the container.</p><dl>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Container.php at line 410</div>
<h3 id="hasScope()">hasScope</h3>

public  Boolean **hasScope** (string name)<div class="details">
<p>Returns whether this container has a certain scope</p><dl>
<dt>Parameters:</dt>
<dd>name - The name of the scope</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Container.php at line 425</div>
<h3 id="isScopeActive()">isScopeActive</h3>

public  Boolean **isScopeActive** (string name)<div class="details">
<p>Returns whether this scope is currently active</p><p>This does not actually check if the passed scope actually exists.</p><dl>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Container.php at line 436</div>
<h3 id="camelize()">camelize</h3>

public static  string **camelize** (string id)<div class="details">
<p>Camelizes a string.</p><dl>
<dt>Parameters:</dt>
<dd>id - A string to camelize</dd>
<dt>Returns:</dt>
<dd>The camelized string</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Container.php at line 447</div>
<h3 id="underscore()">underscore</h3>

public static  string **underscore** (string id)<div class="details">
<p>A string to underscore.</p><dl>
<dt>Parameters:</dt>
<dd>id - The string to underscore</dd>
<dt>Returns:</dt>
<dd>The underscored string</dd>
</dl>
</div>

- - -

