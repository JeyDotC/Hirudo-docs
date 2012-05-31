- - -

**Hirudo\Core\Context\ModuleCall**
<div class="location">framework\hirudo\Hirudo\Core\Context\ModuleCall.php at line 32</div>
#Class ModuleCall#

**ModuleCall**


- - -

<p class="signature">public  class **ModuleCall**</p>

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
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(string app, string module, string task, UnderscoreException lastUnhandledException)</p><p class="description">Creates a module call.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type">static  <a href="../../../hirudo/core/context/modulecall.html">ModuleCall</a></td>
<td class="description"><p class="name"><a href="#fromString">fromString</a>(string string)</p><p class="description">A factory method to create a module call from a string with the "AppName::ModuleName::taskName"
format.</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#getApp">getApp</a>()</p><p class="description">Gets the name of the requested application.</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setApp">setApp</a>(string app)</p><p class="description">Sets the name of the requested application.</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#getModule">getModule</a>()</p><p class="description">Gets the name of the requested module.</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setModule">setModule</a>(string module)</p><p class="description">sets the name of the requested module.</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#getTask">getTask</a>()</p><p class="description">Gets the name of the requested task.</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setTask">setTask</a>(string task)</p><p class="description">Sets the name of the requested task.</p></td>
</tr>
<tr>
<td class="type"> <a href="../../../hirudo/core/exceptions/hirudoexception.html">HirudoException</a></td>
<td class="description"><p class="name"><a href="#getLastUnhandledException">getLastUnhandledException</a>()</p><p class="description">Gets the last Unhandled exception from a previous module execution.</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setLastUnhandledException">setLastUnhandledException</a>(<a href="../../../hirudo/core/exceptions/hirudoexception.html">HirudoException</a> lastUnhandledException)</p><p class="description">Sets the last Unhandled exception from a previous module execution.</p></td>
</tr>
<tr>
<td class="type"> boolean</td>
<td class="description"><p class="name"><a href="#hasUnhandledException">hasUnhandledException</a>()</p><p class="description">Were there an exception from a previous module execution?</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>
<div class="location">framework\hirudo\Hirudo\Core\Context\ModuleCall.php at line 51</div>
<h3 id="__construct()">__construct</h3>
```php
public  void **__construct**(string app, string module, string task, UnderscoreException lastUnhandledException)```
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
<div class="location">framework\hirudo\Hirudo\Core\Context\ModuleCall.php at line 65</div>
<h3 id="fromString()">fromString</h3>
```php
public static  <a href="../../../hirudo/core/context/modulecall.html">ModuleCall</a> **fromString**(string string)```
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

<div class="location">framework\hirudo\Hirudo\Core\Context\ModuleCall.php at line 75</div>
<h3 id="getApp()">getApp</h3>
```php
public  string **getApp**()```
<div class="details">
<p>Gets the name of the requested application.</p><dl>
<dt>Returns:</dt>
<dd>The application name.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Context\ModuleCall.php at line 84</div>
<h3 id="setApp()">setApp</h3>
```php
public  void **setApp**(string app)```
<div class="details">
<p>Sets the name of the requested application.</p><dl>
<dt>Parameters:</dt>
<dd>app - the application name</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Context\ModuleCall.php at line 93</div>
<h3 id="getModule()">getModule</h3>
```php
public  string **getModule**()```
<div class="details">
<p>Gets the name of the requested module.</p><dl>
<dt>Returns:</dt>
<dd>The module name.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Context\ModuleCall.php at line 102</div>
<h3 id="setModule()">setModule</h3>
```php
public  void **setModule**(string module)```
<div class="details">
<p>sets the name of the requested module.</p><dl>
<dt>Parameters:</dt>
<dd>module - The module name.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Context\ModuleCall.php at line 111</div>
<h3 id="getTask()">getTask</h3>
```php
public  string **getTask**()```
<div class="details">
<p>Gets the name of the requested task.</p><dl>
<dt>Returns:</dt>
<dd>The task name</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Context\ModuleCall.php at line 120</div>
<h3 id="setTask()">setTask</h3>
```php
public  void **setTask**(string task)```
<div class="details">
<p>Sets the name of the requested task.</p><dl>
<dt>Parameters:</dt>
<dd>task - The task name.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Context\ModuleCall.php at line 129</div>
<h3 id="getLastUnhandledException()">getLastUnhandledException</h3>
```php
public  <a href="../../../hirudo/core/exceptions/hirudoexception.html">HirudoException</a> **getLastUnhandledException**()```
<div class="details">
<p>Gets the last Unhandled exception from a previous module execution.</p><dl>
<dt>Returns:</dt>
<dd>An instance of HirudoException, null if there were no exceptions on a previous module excecution.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Context\ModuleCall.php at line 138</div>
<h3 id="setLastUnhandledException()">setLastUnhandledException</h3>
```php
public  void **setLastUnhandledException**(<a href="../../../hirudo/core/exceptions/hirudoexception.html">HirudoException</a> lastUnhandledException)```
<div class="details">
<p>Sets the last Unhandled exception from a previous module execution.</p></div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Context\ModuleCall.php at line 147</div>
<h3 id="hasUnhandledException()">hasUnhandledException</h3>
```php
public  boolean **hasUnhandledException**()```
<div class="details">
<p>Were there an exception from a previous module execution?</p></div>

- - -

