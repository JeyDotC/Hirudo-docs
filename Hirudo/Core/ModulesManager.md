

- - -

**Hirudo\Core\ModulesManager**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/ModulesManager.php#L46" target='_blank'>framework\Hirudo\Core\ModulesManager.php at line 46</a>

#Class ModulesManager#

**ModulesManager**




- - -

<p><strong>public  class</strong> <span>ModulesManager</span></p>

<div class="comment" id="overview_description"><p>This class serves as a front controller in Hirudo, is the main entry
point of the framework.</p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
</dl>


<hr />

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(str implementationPackage, array<string> implementationClasses)</p><p class="description">Creates a new modules manager.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#run">run</a>(mixed call)</p><p class="description">Executes the requested action based on the request parameters or the
default configuration.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#executecall">executeCall</a>(<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/ModuleCall.md">ModuleCall</a> call)</p><p class="description">Executes a ModuleCall.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#prepareapplication">prepareApplication</a>(mixed appName)</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setautoloader">setAutoLoader</a>(type loader)</p><p class="description">Sets the autoloader class.</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>UniversalClassLoader</span></td>
<td class="description"><p class="name"><a href="#getautoloader">getAutoLoader</a>()</p><p class="description"></p></td>
</tr>
</table>

<h2>Constructor Detail</h2>


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/ModulesManager.php#L67" target='_blank'>framework\Hirudo\Core\ModulesManager.php at line 67</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (str implementationPackage, array<string> implementationClasses)

<div class="details">
<p>Creates a new modules manager.</p><dl>
<dt>Parameters:</dt>
<dd>implementationClasses - A list of fully qualified class names that implement the core functionalities of Hirudo.</dd>
</dl>

</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/ModulesManager.php#L105" target='_blank'>framework\Hirudo\Core\ModulesManager.php at line 105</a>

<h3 id="run()">run</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>run</span> (mixed call)

<div class="details">
<p>Executes the requested action based on the request parameters or the
default configuration.</p><dl>
<dt>Returns:</dt>
<dd>The program's output.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/ModulesManager.php#L128" target='_blank'>framework\Hirudo\Core\ModulesManager.php at line 128</a>

<h3 id="executeCall()">executeCall</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>executeCall</span> (<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/ModuleCall.md">ModuleCall</a> call)

<div class="details">
<p>Executes a ModuleCall.</p><dl>
<dt>Parameters:</dt>
<dd>call - The call to be executed.</dd>
<dt>Returns:</dt>
<dd>The resulting output.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/ModulesManager.php#L172" target='_blank'>framework\Hirudo\Core\ModulesManager.php at line 172</a>

<h3 id="prepareApplication()">prepareApplication</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>prepareApplication</span> (mixed appName)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/ModulesManager.php#L206" target='_blank'>framework\Hirudo\Core\ModulesManager.php at line 206</a>

<h3 id="setAutoLoader()">setAutoLoader</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>setAutoLoader</span> (type loader)

<div class="details">
<p>Sets the autoloader class.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/ModulesManager.php#L214" target='_blank'>framework\Hirudo\Core\ModulesManager.php at line 214</a>

<h3 id="getAutoLoader()">getAutoLoader</h3>
<span class='k'>static </span> <span class='nx'>UniversalClassLoader</span> <span class='nf'>getAutoLoader</span> ()

<div class="details">
<p></p>
</div>

- - -

