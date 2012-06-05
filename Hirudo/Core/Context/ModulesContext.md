

- - -

**Hirudo\Core\Context\ModulesContext**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/ModulesContext.php#L41" target='_blank'>framework\hirudo\Hirudo\Core\Context\ModulesContext.php at line 41</a>

#Class ModulesContext#

**ModulesContext**




- - -

<p><strong>public  class</strong> <span>ModulesContext</span></p>

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
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/ModulesContext.md#getCurrentCall>ModuleCall</a></span></td>
<td class="description"><p class="name"><a href="#getcurrentcall">getCurrentCall</a>()</p><p class="description">Gets the ModuleCall that is being executed.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setcurrentcall">setCurrentCall</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/hirudo/core/context/ModuleCall.md">ModuleCall</a> currentCall)</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/ModulesContext.md#instance>ModulesContext</a></span></td>
<td class="description"><p class="name"><a href="#instance">instance</a>()</p><p class="description">Gets the current ModulesContext instance. </p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setuser">setUser</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/hirudo/core/context/Principal.md">Principal</a> user)</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/ModulesContext.md#getCurrentUser>Principal</a></span></td>
<td class="description"><p class="name"><a href="#getcurrentuser">getCurrentUser</a>()</p><p class="description">Gets the current user which is stored in session.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>Session</span></td>
<td class="description"><p class="name"><a href="#getsession">getSession</a>()</p><p class="description">Gets the current session.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setsession">setSession</a>(Session session)</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setrequest">setRequest</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/hirudo/core/context/Request.md">Request</a> request)</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/ModulesContext.md#getRequest>Request</a></span></td>
<td class="description"><p class="name"><a href="#getrequest">getRequest</a>()</p><p class="description">Gets the current request object.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/ModulesContext.md#getConfig>AppConfig</a></span></td>
<td class="description"><p class="name"><a href="#getconfig">getConfig</a>()</p><p class="description">Gets the current configuration object.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setconfig">setConfig</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/hirudo/core/context/AppConfig.md">AppConfig</a> config)</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/ModulesContext.md#getRouting>Routing</a></span></td>
<td class="description"><p class="name"><a href="#getrouting">getRouting</a>()</p><p class="description">Gets the current implementation of the Routing class.
</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setrouting">setRouting</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/hirudo/core/context/Routing.md">Routing</a> routing)</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/ModulesContext.md#getTemplating>TemplatingInterface</a></span></td>
<td class="description"><p class="name"><a href="#gettemplating">getTemplating</a>()</p><p class="description">Gets the templating system object.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#settemplating">setTemplating</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/hirudo/core/TemplatingInterface.md">TemplatingInterface</a> templating)</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/ModulesContext.md#getDependenciesManager>DependenciesManager</a></span></td>
<td class="description"><p class="name"><a href="#getdependenciesmanager">getDependenciesManager</a>()</p><p class="description">Gets the current object responsible for the dependency injection.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/ModulesContext.md#getAssets>Assets</a></span></td>
<td class="description"><p class="name"><a href="#getassets">getAssets</a>()</p><p class="description">Gets the current assets management system.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setassets">setAssets</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/hirudo/core/context/Assets.md">Assets</a> assets)</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setdependenciesmanager">setDependenciesManager</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/hirudo/core/dependencyinjection/DependenciesManager.md">DependenciesManager</a> dependenciesManager)</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/ModulesContext.php#L68" target='_blank'>framework\hirudo\Hirudo\Core\Context\ModulesContext.php at line 68</a>

<h3 id="getCurrentCall()">getCurrentCall</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/ModulesContext.md#getCurrentCall>ModuleCall</a></span> <span class='nf'>getCurrentCall</span> ()

<div class="details">
<p>Gets the ModuleCall that is being executed.</p><dl>
<dt>Returns:</dt>
<dd>The current ModuleCall.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/ModulesContext.php#L77" target='_blank'>framework\hirudo\Hirudo\Core\Context\ModulesContext.php at line 77</a>

<h3 id="setCurrentCall()">setCurrentCall</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setCurrentCall</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/hirudo/core/context/ModuleCall.md">ModuleCall</a> currentCall)

<div class="details">
<p></p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/ModulesContext.php#L88" target='_blank'>framework\hirudo\Hirudo\Core\Context\ModulesContext.php at line 88</a>

<h3 id="instance()">instance</h3>
<span class='k'>static </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/ModulesContext.md#instance>ModulesContext</a></span> <span class='nf'>instance</span> ()

<div class="details">
<p>Gets the current ModulesContext instance. Use this method to
obtain a ModulesContext object that is actually holding the context
instances.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/ModulesContext.php#L102" target='_blank'>framework\hirudo\Hirudo\Core\Context\ModulesContext.php at line 102</a>

<h3 id="setUser()">setUser</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setUser</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/hirudo/core/context/Principal.md">Principal</a> user)

<div class="details">
<p></p><dl>
<dt>Import(id="principal").</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/ModulesContext.php#L111" target='_blank'>framework\hirudo\Hirudo\Core\Context\ModulesContext.php at line 111</a>

<h3 id="getCurrentUser()">getCurrentUser</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/ModulesContext.md#getCurrentUser>Principal</a></span> <span class='nf'>getCurrentUser</span> ()

<div class="details">
<p>Gets the current user which is stored in session.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/ModulesContext.php#L120" target='_blank'>framework\hirudo\Hirudo\Core\Context\ModulesContext.php at line 120</a>

<h3 id="getSession()">getSession</h3>
<span class='k'></span> <span class='nx'>Session</span> <span class='nf'>getSession</span> ()

<div class="details">
<p>Gets the current session.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/ModulesContext.php#L128" target='_blank'>framework\hirudo\Hirudo\Core\Context\ModulesContext.php at line 128</a>

<h3 id="setSession()">setSession</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setSession</span> (Session session)

<div class="details">
<p></p><dl>
<dt>Import(id="session").</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/ModulesContext.php#L136" target='_blank'>framework\hirudo\Hirudo\Core\Context\ModulesContext.php at line 136</a>

<h3 id="setRequest()">setRequest</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setRequest</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/hirudo/core/context/Request.md">Request</a> request)

<div class="details">
<p></p><dl>
<dt>Import(id="request").</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/ModulesContext.php#L145" target='_blank'>framework\hirudo\Hirudo\Core\Context\ModulesContext.php at line 145</a>

<h3 id="getRequest()">getRequest</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/ModulesContext.md#getRequest>Request</a></span> <span class='nf'>getRequest</span> ()

<div class="details">
<p>Gets the current request object.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/ModulesContext.php#L154" target='_blank'>framework\hirudo\Hirudo\Core\Context\ModulesContext.php at line 154</a>

<h3 id="getConfig()">getConfig</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/ModulesContext.md#getConfig>AppConfig</a></span> <span class='nf'>getConfig</span> ()

<div class="details">
<p>Gets the current configuration object.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/ModulesContext.php#L163" target='_blank'>framework\hirudo\Hirudo\Core\Context\ModulesContext.php at line 163</a>

<h3 id="setConfig()">setConfig</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setConfig</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/hirudo/core/context/AppConfig.md">AppConfig</a> config)

<div class="details">
<p></p><dl>
<dt>Import(id="config").</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/ModulesContext.php#L176" target='_blank'>framework\hirudo\Hirudo\Core\Context\ModulesContext.php at line 176</a>

<h3 id="getRouting()">getRouting</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/ModulesContext.md#getRouting>Routing</a></span> <span class='nf'>getRouting</span> ()

<div class="details">
<p>Gets the current implementation of the Routing class.
<strong>Note:</strong> The returned object is not bound to any module,
so, the action() and moduleAction() methods will return the URL with the
Application and Module parts empty. Always use the appAction() method if
you are getting the routing object fron this method.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/ModulesContext.php#L185" target='_blank'>framework\hirudo\Hirudo\Core\Context\ModulesContext.php at line 185</a>

<h3 id="setRouting()">setRouting</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setRouting</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/hirudo/core/context/Routing.md">Routing</a> routing)

<div class="details">
<p></p><dl>
<dt>Import(id="routing").</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/ModulesContext.php#L194" target='_blank'>framework\hirudo\Hirudo\Core\Context\ModulesContext.php at line 194</a>

<h3 id="getTemplating()">getTemplating</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/ModulesContext.md#getTemplating>TemplatingInterface</a></span> <span class='nf'>getTemplating</span> ()

<div class="details">
<p>Gets the templating system object.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/ModulesContext.php#L203" target='_blank'>framework\hirudo\Hirudo\Core\Context\ModulesContext.php at line 203</a>

<h3 id="setTemplating()">setTemplating</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setTemplating</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/hirudo/core/TemplatingInterface.md">TemplatingInterface</a> templating)

<div class="details">
<p></p><dl>
<dt>Import(id="templating").</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/ModulesContext.php#L212" target='_blank'>framework\hirudo\Hirudo\Core\Context\ModulesContext.php at line 212</a>

<h3 id="getDependenciesManager()">getDependenciesManager</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/ModulesContext.md#getDependenciesManager>DependenciesManager</a></span> <span class='nf'>getDependenciesManager</span> ()

<div class="details">
<p>Gets the current object responsible for the dependency injection.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/ModulesContext.php#L221" target='_blank'>framework\hirudo\Hirudo\Core\Context\ModulesContext.php at line 221</a>

<h3 id="getAssets()">getAssets</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/ModulesContext.md#getAssets>Assets</a></span> <span class='nf'>getAssets</span> ()

<div class="details">
<p>Gets the current assets management system.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/ModulesContext.php#L230" target='_blank'>framework\hirudo\Hirudo\Core\Context\ModulesContext.php at line 230</a>

<h3 id="setAssets()">setAssets</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setAssets</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/hirudo/core/context/Assets.md">Assets</a> assets)

<div class="details">
<p></p><dl>
<dt>Import(id="assets").</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/ModulesContext.php#L234" target='_blank'>framework\hirudo\Hirudo\Core\Context\ModulesContext.php at line 234</a>

<h3 id="setDependenciesManager()">setDependenciesManager</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setDependenciesManager</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/hirudo/core/dependencyinjection/DependenciesManager.md">DependenciesManager</a> dependenciesManager)

<div class="details">

</div>

- - -

