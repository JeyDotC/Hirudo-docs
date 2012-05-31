- - -

**Hirudo\Core\Task**
<div class="location">framework\hirudo\Hirudo\Core\Task.php at line 35</div>
#Class Task#

**Task**


- - -

<p class="signature">public  class **Task**</p>

<div class="comment" id="overview_description"><p>Is a representation of a module's task, it holds the information about the action
to be executed and can be used to know which are it's requirements and also
resolve them.</p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
</dl>
- - -

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(\ReflectionMethod reflectionMethod, <a href="../../hirudo/core/module.html">Module</a> owner)</p><p class="description">Constructs a task.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#getName">getName</a>()</p><p class="description">Gets the method name.</p></td>
</tr>
<tr>
<td class="type"> array<\ReflectionParameter></td>
<td class="description"><p class="name"><a href="#getGetParams">getGetParams</a>()</p><p class="description">Gets the method's parameters.</p></td>
</tr>
<tr>
<td class="type"> array<\ReflectionParameter></td>
<td class="description"><p class="name"><a href="#getPostParams">getPostParams</a>()</p><p class="description">Gets the method's parameters that should be resolved from POST.</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setParamValue">setParamValue</a>(string paramName, mixed value)</p><p class="description">Sets the value of a method's param.</p></td>
</tr>
<tr>
<td class="type"> type</td>
<td class="description"><p class="name"><a href="#getParamValue">getParamValue</a>(string paramName)</p><p class="description">Gets the value of a method's param.</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#invoke">invoke</a>()</p><p class="description">Executes the task.</p></td>
</tr>
<tr>
<td class="type"> array<mixed></td>
<td class="description"><p class="name"><a href="#getTaskAnnotations">getTaskAnnotations</a>()</p><p class="description">Gets the method's meta data.</p></td>
</tr>
<tr>
<td class="type"> mixed</td>
<td class="description"><p class="name"><a href="#getTaskAnnotation">getTaskAnnotation</a>(string annotationName)</p><p class="description">Gets a single annotation from the merhod.</p></td>
</tr>
<tr>
<td class="type"> <a href="../../hirudo/core/module.html">Module</a></td>
<td class="description"><p class="name"><a href="#getModule">getModule</a>()</p><p class="description">Gets the module that owns the method to be executed.</p></td>
</tr>
<tr>
<td class="type"> boolean</td>
<td class="description"><p class="name"><a href="#isPostOnly">isPostOnly</a>()</p><p class="description">Says if the method must be executed only if the request method is POST</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>
<div class="location">framework\hirudo\Hirudo\Core\Task.php at line 65</div>
<h3 id="__construct()">__construct</h3>
```php
public  void **__construct**(\ReflectionMethod reflectionMethod, <a href="../../hirudo/core/module.html">Module</a> owner)```
<div class="details">
<p>Constructs a task.</p><dl>
<dt>Parameters:</dt>
<dd>reflectionMethod - The method to be called.</dd>
<dd>owner - The module that is the owner of the task.</dd>
</dl>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\hirudo\Hirudo\Core\Task.php at line 89</div>
<h3 id="getName()">getName</h3>
```php
public  string **getName**()```
<div class="details">
<p>Gets the method name.</p></div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Task.php at line 98</div>
<h3 id="getGetParams()">getGetParams</h3>
```php
public  array<\ReflectionParameter> **getGetParams**()```
<div class="details">
<p>Gets the method's parameters.</p></div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Task.php at line 107</div>
<h3 id="getPostParams()">getPostParams</h3>
```php
public  array<\ReflectionParameter> **getPostParams**()```
<div class="details">
<p>Gets the method's parameters that should be resolved from POST.</p></div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Task.php at line 117</div>
<h3 id="setParamValue()">setParamValue</h3>
```php
public  void **setParamValue**(string paramName, mixed value)```
<div class="details">
<p>Sets the value of a method's param.</p><dl>
<dt>Parameters:</dt>
<dd>paramName - The parameter name.</dd>
<dd>value - The value for the parameter.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Task.php at line 127</div>
<h3 id="getParamValue()">getParamValue</h3>
```php
public  type **getParamValue**(string paramName)```
<div class="details">
<p>Gets the value of a method's param.</p></div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Task.php at line 134</div>
<h3 id="invoke()">invoke</h3>
```php
public  void **invoke**()```
<div class="details">
<p>Executes the task.</p></div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Task.php at line 143</div>
<h3 id="getTaskAnnotations()">getTaskAnnotations</h3>
```php
public  array<mixed> **getTaskAnnotations**()```
<div class="details">
<p>Gets the method's meta data.</p><dl>
<dt>Returns:</dt>
<dd>An annotations list.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Task.php at line 153</div>
<h3 id="getTaskAnnotation()">getTaskAnnotation</h3>
```php
public  mixed **getTaskAnnotation**(string annotationName)```
<div class="details">
<p>Gets a single annotation from the merhod.</p><dl>
<dt>Parameters:</dt>
<dd>annotationName - The fully qualified annotation class or annotation id.</dd>
<dt>Returns:</dt>
<dd>The annotation</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Task.php at line 162</div>
<h3 id="getModule()">getModule</h3>
```php
public  <a href="../../hirudo/core/module.html">Module</a> **getModule**()```
<div class="details">
<p>Gets the module that owns the method to be executed.</p></div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Task.php at line 171</div>
<h3 id="isPostOnly()">isPostOnly</h3>
```php
public  boolean **isPostOnly**()```
<div class="details">
<p>Says if the method must be executed only if the request method is POST</p><dl>
<dt>Returns:</dt>
<dd>True if the method must be executed only if the request method is POST</dd>
</dl>
</div>

- - -

