
- - -

**Hirudo\Core\Context\ModulesContext**
<div class="location">framework\hirudo\Hirudo\Core\Context\ModulesContext.php at line 41</div>
#Class ModulesContext#

**ModulesContext**


- - -

<p class="signature">public  class **ModulesContext**</p>

<div class="comment" id="overview_description"><p>This class holds the instances of the objects that implements
the Hirudo abstract classes.</p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
</dl>

- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type">  <a href="../../../hirudo/core/context/modulecall.html">ModuleCall</a></td>
<td class="description"><p class="name"><a href="#getcurrentcall">getCurrentCall</a>()</p><p class="description">Gets the ModuleCall that is being executed.</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#setcurrentcall">setCurrentCall</a>(<a href="../../../hirudo/core/context/modulecall.html">ModuleCall</a> currentCall)</p><p class="description"></p></td>
</tr>
<tr>
<td class="type"> static  <a href="../../../hirudo/core/context/modulescontext.html">ModulesContext</a></td>
<td class="description"><p class="name"><a href="#instance">instance</a>()</p><p class="description">Gets the current ModulesContext instance. </p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#setuser">setUser</a>(<a href="../../../hirudo/core/context/principal.html">Principal</a> user)</p><p class="description"></p></td>
</tr>
<tr>
<td class="type">  <a href="../../../hirudo/core/context/principal.html">Principal</a></td>
<td class="description"><p class="name"><a href="#getcurrentuser">getCurrentUser</a>()</p><p class="description">Gets the current user which is stored in session.</p></td>
</tr>
<tr>
<td class="type">  Session</td>
<td class="description"><p class="name"><a href="#getsession">getSession</a>()</p><p class="description">Gets the current session.</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#setsession">setSession</a>(Session session)</p><p class="description"></p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#setrequest">setRequest</a>(<a href="../../../hirudo/core/context/request.html">Request</a> request)</p><p class="description"></p></td>
</tr>
<tr>
<td class="type">  <a href="../../../hirudo/core/context/request.html">Request</a></td>
<td class="description"><p class="name"><a href="#getrequest">getRequest</a>()</p><p class="description">Gets the current request object.</p></td>
</tr>
<tr>
<td class="type">  <a href="../../../hirudo/core/context/appconfig.html">AppConfig</a></td>
<td class="description"><p class="name"><a href="#getconfig">getConfig</a>()</p><p class="description">Gets the current configuration object.</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#setconfig">setConfig</a>(<a href="../../../hirudo/core/context/appconfig.html">AppConfig</a> config)</p><p class="description"></p></td>
</tr>
<tr>
<td class="type">  <a href="../../../hirudo/core/context/routing.html">Routing</a></td>
<td class="description"><p class="name"><a href="#getrouting">getRouting</a>()</p><p class="description">Gets the current implementation of the Routing class.
</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#setrouting">setRouting</a>(<a href="../../../hirudo/core/context/routing.html">Routing</a> routing)</p><p class="description"></p></td>
</tr>
<tr>
<td class="type">  <a href="../../../hirudo/core/templatinginterface.html">TemplatingInterface</a></td>
<td class="description"><p class="name"><a href="#gettemplating">getTemplating</a>()</p><p class="description">Gets the templating system object.</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#settemplating">setTemplating</a>(<a href="../../../hirudo/core/templatinginterface.html">TemplatingInterface</a> templating)</p><p class="description"></p></td>
</tr>
<tr>
<td class="type">  <a href="../../../hirudo/core/dependencyinjection/dependenciesmanager.html">DependenciesManager</a></td>
<td class="description"><p class="name"><a href="#getdependenciesmanager">getDependenciesManager</a>()</p><p class="description">Gets the current object responsible for the dependency injection.</p></td>
</tr>
<tr>
<td class="type">  <a href="../../../hirudo/core/context/assets.html">Assets</a></td>
<td class="description"><p class="name"><a href="#getassets">getAssets</a>()</p><p class="description">Gets the current assets management system.</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#setassets">setAssets</a>(<a href="../../../hirudo/core/context/assets.html">Assets</a> assets)</p><p class="description"></p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#setdependenciesmanager">setDependenciesManager</a>(<a href="../../../hirudo/core/dependencyinjection/dependenciesmanager.html">DependenciesManager</a> dependenciesManager)</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\hirudo\Hirudo\Core\Context\ModulesContext.php at line 68</div>
<h3 id="getCurrentCall()">getCurrentCall</h3>

public  <a href="../../../hirudo/core/context/modulecall.html">ModuleCall</a> **getCurrentCall** ()<div class="details">
<p>Gets the ModuleCall that is being executed.</p><dl>
<dt>Returns:</dt>
<dd>The current ModuleCall.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Context\ModulesContext.php at line 77</div>
<h3 id="setCurrentCall()">setCurrentCall</h3>

public  void **setCurrentCall** (<a href="../../../hirudo/core/context/modulecall.html">ModuleCall</a> currentCall)<div class="details">
<p></p></div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Context\ModulesContext.php at line 88</div>
<h3 id="instance()">instance</h3>

public static  <a href="../../../hirudo/core/context/modulescontext.html">ModulesContext</a> **instance** ()<div class="details">
<p>Gets the current ModulesContext instance. Use this method to
obtain a ModulesContext object that is actually holding the context
instances.</p></div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Context\ModulesContext.php at line 102</div>
<h3 id="setUser()">setUser</h3>

public  void **setUser** (<a href="../../../hirudo/core/context/principal.html">Principal</a> user)<div class="details">
<p></p><dl>
<dt>Import(id="principal").</dt>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Context\ModulesContext.php at line 111</div>
<h3 id="getCurrentUser()">getCurrentUser</h3>

public  <a href="../../../hirudo/core/context/principal.html">Principal</a> **getCurrentUser** ()<div class="details">
<p>Gets the current user which is stored in session.</p></div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Context\ModulesContext.php at line 120</div>
<h3 id="getSession()">getSession</h3>

public  Session **getSession** ()<div class="details">
<p>Gets the current session.</p></div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Context\ModulesContext.php at line 128</div>
<h3 id="setSession()">setSession</h3>

public  void **setSession** (Session session)<div class="details">
<p></p><dl>
<dt>Import(id="session").</dt>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Context\ModulesContext.php at line 136</div>
<h3 id="setRequest()">setRequest</h3>

public  void **setRequest** (<a href="../../../hirudo/core/context/request.html">Request</a> request)<div class="details">
<p></p><dl>
<dt>Import(id="request").</dt>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Context\ModulesContext.php at line 145</div>
<h3 id="getRequest()">getRequest</h3>

public  <a href="../../../hirudo/core/context/request.html">Request</a> **getRequest** ()<div class="details">
<p>Gets the current request object.</p></div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Context\ModulesContext.php at line 154</div>
<h3 id="getConfig()">getConfig</h3>

public  <a href="../../../hirudo/core/context/appconfig.html">AppConfig</a> **getConfig** ()<div class="details">
<p>Gets the current configuration object.</p></div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Context\ModulesContext.php at line 163</div>
<h3 id="setConfig()">setConfig</h3>

public  void **setConfig** (<a href="../../../hirudo/core/context/appconfig.html">AppConfig</a> config)<div class="details">
<p></p><dl>
<dt>Import(id="config").</dt>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Context\ModulesContext.php at line 176</div>
<h3 id="getRouting()">getRouting</h3>

public  <a href="../../../hirudo/core/context/routing.html">Routing</a> **getRouting** ()<div class="details">
<p>Gets the current implementation of the Routing class.
<strong>Note:</strong> The returned object is not bound to any module,
so, the action() and moduleAction() methods will return the URL with the
Application and Module parts empty. Always use the appAction() method if
you are getting the routing object fron this method.</p></div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Context\ModulesContext.php at line 185</div>
<h3 id="setRouting()">setRouting</h3>

public  void **setRouting** (<a href="../../../hirudo/core/context/routing.html">Routing</a> routing)<div class="details">
<p></p><dl>
<dt>Import(id="routing").</dt>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Context\ModulesContext.php at line 194</div>
<h3 id="getTemplating()">getTemplating</h3>

public  <a href="../../../hirudo/core/templatinginterface.html">TemplatingInterface</a> **getTemplating** ()<div class="details">
<p>Gets the templating system object.</p></div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Context\ModulesContext.php at line 203</div>
<h3 id="setTemplating()">setTemplating</h3>

public  void **setTemplating** (<a href="../../../hirudo/core/templatinginterface.html">TemplatingInterface</a> templating)<div class="details">
<p></p><dl>
<dt>Import(id="templating").</dt>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Context\ModulesContext.php at line 212</div>
<h3 id="getDependenciesManager()">getDependenciesManager</h3>

public  <a href="../../../hirudo/core/dependencyinjection/dependenciesmanager.html">DependenciesManager</a> **getDependenciesManager** ()<div class="details">
<p>Gets the current object responsible for the dependency injection.</p></div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Context\ModulesContext.php at line 221</div>
<h3 id="getAssets()">getAssets</h3>

public  <a href="../../../hirudo/core/context/assets.html">Assets</a> **getAssets** ()<div class="details">
<p>Gets the current assets management system.</p></div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Context\ModulesContext.php at line 230</div>
<h3 id="setAssets()">setAssets</h3>

public  void **setAssets** (<a href="../../../hirudo/core/context/assets.html">Assets</a> assets)<div class="details">
<p></p><dl>
<dt>Import(id="assets").</dt>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Context\ModulesContext.php at line 234</div>
<h3 id="setDependenciesManager()">setDependenciesManager</h3>

public  void **setDependenciesManager** (<a href="../../../hirudo/core/dependencyinjection/dependenciesmanager.html">DependenciesManager</a> dependenciesManager)<div class="details">
</div>

- - -

