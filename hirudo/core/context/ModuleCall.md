

- - -

**Hirudo\Core\Context\ModuleCall**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/ModuleCall.php#L32" >framework\hirudo\Hirudo\Core\Context\ModuleCall.php at line 32</a>

#Class ModuleCall#

**ModuleCall**




- - -

<p class="signature"><span class='k'>public  class</span> <span class='nx'>ModuleCall</span></p>

<div class="comment" id="overview_description"><p>This class represents a call to a task from a module that
belongs to an application.</p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
</dl>


- - -

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(string app, string module, string task, UnderscoreException lastUnhandledException)</p><p class="description">Creates a module call.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'>static </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/ModuleCall>ModuleCall</a></span></td>
<td class="description"><p class="name"><a href="#fromstring">fromString</a>(string string)</p><p class="description">A factory method to create a module call from a string with the "AppName::ModuleName::taskName"
format.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getapp">getApp</a>()</p><p class="description">Gets the name of the requested application.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setapp">setApp</a>(string app)</p><p class="description">Sets the name of the requested application.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getmodule">getModule</a>()</p><p class="description">Gets the name of the requested module.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setmodule">setModule</a>(string module)</p><p class="description">sets the name of the requested module.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#gettask">getTask</a>()</p><p class="description">Gets the name of the requested task.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#settask">setTask</a>(string task)</p><p class="description">Sets the name of the requested task.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/exceptions/HirudoException>HirudoException</a></span></td>
<td class="description"><p class="name"><a href="#getlastunhandledexception">getLastUnhandledException</a>()</p><p class="description">Gets the last Unhandled exception from a previous module execution.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setlastunhandledexception">setLastUnhandledException</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/hirudo/core/exceptions/HirudoException.md">HirudoException</a> lastUnhandledException)</p><p class="description">Sets the last Unhandled exception from a previous module execution.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#hasunhandledexception">hasUnhandledException</a>()</p><p class="description">Were there an exception from a previous module execution?</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/ModuleCall.php#L51" >framework\hirudo\Hirudo\Core\Context\ModuleCall.php at line 51</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (string app, string module, string task, UnderscoreException lastUnhandledException)

<div class="details">
<p>Creates a module call.</p><dl>
<dt>Parameters:</dt>
<dd>app - The application the requested module belongs to.</dd>
<dd>module - The module to be executed.</dd>
<dd>task - The task this module should execute.</dd>
<dd>lastUnhandledException - If there where any unhandled exception on a previous module excecution.</dd>
</dl>

</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/ModuleCall.php#L65" >framework\hirudo\Hirudo\Core\Context\ModuleCall.php at line 65</a>

<h3 id="fromString()">fromString</h3>
<span class='k'>static </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/ModuleCall>ModuleCall</a></span> <span class='nf'>fromString</span> (string string)

<div class="details">
<p>A factory method to create a module call from a string with the "AppName::ModuleName::taskName"
format.</p><dl>
<dt>Parameters:</dt>
<dd>string - A string with the "AppName::ModuleName::taskName" format.</dd>
<dt>Returns:</dt>
<dd>A new instance of ModuleCall.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/ModuleCall.php#L75" >framework\hirudo\Hirudo\Core\Context\ModuleCall.php at line 75</a>

<h3 id="getApp()">getApp</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getApp</span> ()

<div class="details">
<p>Gets the name of the requested application.</p><dl>
<dt>Returns:</dt>
<dd>The application name.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/ModuleCall.php#L84" >framework\hirudo\Hirudo\Core\Context\ModuleCall.php at line 84</a>

<h3 id="setApp()">setApp</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setApp</span> (string app)

<div class="details">
<p>Sets the name of the requested application.</p><dl>
<dt>Parameters:</dt>
<dd>app - the application name</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/ModuleCall.php#L93" >framework\hirudo\Hirudo\Core\Context\ModuleCall.php at line 93</a>

<h3 id="getModule()">getModule</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getModule</span> ()

<div class="details">
<p>Gets the name of the requested module.</p><dl>
<dt>Returns:</dt>
<dd>The module name.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/ModuleCall.php#L102" >framework\hirudo\Hirudo\Core\Context\ModuleCall.php at line 102</a>

<h3 id="setModule()">setModule</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setModule</span> (string module)

<div class="details">
<p>sets the name of the requested module.</p><dl>
<dt>Parameters:</dt>
<dd>module - The module name.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/ModuleCall.php#L111" >framework\hirudo\Hirudo\Core\Context\ModuleCall.php at line 111</a>

<h3 id="getTask()">getTask</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getTask</span> ()

<div class="details">
<p>Gets the name of the requested task.</p><dl>
<dt>Returns:</dt>
<dd>The task name</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/ModuleCall.php#L120" >framework\hirudo\Hirudo\Core\Context\ModuleCall.php at line 120</a>

<h3 id="setTask()">setTask</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setTask</span> (string task)

<div class="details">
<p>Sets the name of the requested task.</p><dl>
<dt>Parameters:</dt>
<dd>task - The task name.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/ModuleCall.php#L129" >framework\hirudo\Hirudo\Core\Context\ModuleCall.php at line 129</a>

<h3 id="getLastUnhandledException()">getLastUnhandledException</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/exceptions/HirudoException>HirudoException</a></span> <span class='nf'>getLastUnhandledException</span> ()

<div class="details">
<p>Gets the last Unhandled exception from a previous module execution.</p><dl>
<dt>Returns:</dt>
<dd>An instance of HirudoException, null if there were no exceptions on a previous module excecution.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/ModuleCall.php#L138" >framework\hirudo\Hirudo\Core\Context\ModuleCall.php at line 138</a>

<h3 id="setLastUnhandledException()">setLastUnhandledException</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setLastUnhandledException</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/hirudo/core/exceptions/HirudoException.md">HirudoException</a> lastUnhandledException)

<div class="details">
<p>Sets the last Unhandled exception from a previous module execution.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Core/Context/ModuleCall.php#L147" >framework\hirudo\Hirudo\Core\Context\ModuleCall.php at line 147</a>

<h3 id="hasUnhandledException()">hasUnhandledException</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>hasUnhandledException</span> ()

<div class="details">
<p>Were there an exception from a previous module execution?</p>
</div>

- - -

