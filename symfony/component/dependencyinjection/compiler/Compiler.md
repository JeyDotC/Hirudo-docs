- - -

**Symfony\Component\DependencyInjection\Compiler\Compiler**
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/Compiler.php.md#line24" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\Compiler.php at line 24</a>

# Class Compiler #

<pre class="tree">** Compiler **\n</pre>

- - -

<p class="signature">public  class **Compiler**</p>

<div class="comment" id="overview_description"><p>This class is used to remove circular dependencies between individual passes.</p></div>

<dl>
<dt>Author:</dt>
<dd>Johannes M. Schmitt <schmittjoh@gmail.com></dd>
<dt>Api.</dt>
</dl>
- - -

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct()">__construct</a>()</p><p class="description">Constructor.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> <a href="../../../../symfony/component/dependencyinjection/compiler/passconfig.html">PassConfig</a></td>
<td class="description"><p class="name"><a href="#getPassConfig()">getPassConfig</a>()</p><p class="description">Returns the PassConfig.</p></td>
</tr>
<tr>
<td class="type"> <a href="../../../../symfony/component/dependencyinjection/compiler/servicereferencegraph.html">ServiceReferenceGraph</a></td>
<td class="description"><p class="name"><a href="#getServiceReferenceGraph()">getServiceReferenceGraph</a>()</p><p class="description">Returns the ServiceReferenceGraph.</p></td>
</tr>
<tr>
<td class="type"> <a href="../../../../symfony/component/dependencyinjection/compiler/loggingformatter.html">LoggingFormatter</a></td>
<td class="description"><p class="name"><a href="#getLoggingFormatter()">getLoggingFormatter</a>()</p><p class="description">Returns the logging formatter which can be used by compilation passes.</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#addPass()">addPass</a>(<a href="../../../../symfony/component/dependencyinjection/compiler/compilerpassinterface.html">CompilerPassInterface</a> pass, string type)</p><p class="description">Adds a pass to the PassConfig.</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#addLogMessage()">addLogMessage</a>(string string)</p><p class="description">Adds a log message.</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#getLog()">getLog</a>()</p><p class="description">Returns the log.</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#compile()">compile</a>(<a href="../../../../symfony/component/dependencyinjection/containerbuilder.html">ContainerBuilder</a> container)</p><p class="description">Run the Compiler and process all Passes.</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/Compiler.php.md#line34" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\Compiler.php at line 34</a>

<h3 id="__construct()">__construct</h3>
```php
public  void **__construct**()```
<div class="details">
<p>Constructor.</p></div>

- - -

<h2 id="detail_method">Method Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/Compiler.php.md#line49" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\Compiler.php at line 49</a>

<h3 id="getPassConfig()">getPassConfig</h3>
```php
public  <a href="../../../../symfony/component/dependencyinjection/compiler/passconfig.html">PassConfig</a> **getPassConfig**()```
<div class="details">
<p>Returns the PassConfig.</p><dl>
<dt>Returns:</dt>
<dd>The PassConfig instance</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/Compiler.php.md#line61" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\Compiler.php at line 61</a>

<h3 id="getServiceReferenceGraph()">getServiceReferenceGraph</h3>
```php
public  <a href="../../../../symfony/component/dependencyinjection/compiler/servicereferencegraph.html">ServiceReferenceGraph</a> **getServiceReferenceGraph**()```
<div class="details">
<p>Returns the ServiceReferenceGraph.</p><dl>
<dt>Returns:</dt>
<dd>The ServiceReferenceGraph instance</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/Compiler.php.md#line71" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\Compiler.php at line 71</a>

<h3 id="getLoggingFormatter()">getLoggingFormatter</h3>
```php
public  <a href="../../../../symfony/component/dependencyinjection/compiler/loggingformatter.html">LoggingFormatter</a> **getLoggingFormatter**()```
<div class="details">
<p>Returns the logging formatter which can be used by compilation passes.</p></div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/Compiler.php.md#line84" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\Compiler.php at line 84</a>

<h3 id="addPass()">addPass</h3>
```php
public  void **addPass**(<a href="../../../../symfony/component/dependencyinjection/compiler/compilerpassinterface.html">CompilerPassInterface</a> pass, string type)```
<div class="details">
<p>Adds a pass to the PassConfig.</p><dl>
<dt>Parameters:</dt>
<dd>pass - A compiler pass</dd>
<dd>type - The type of the pass</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/Compiler.php.md#line94" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\Compiler.php at line 94</a>

<h3 id="addLogMessage()">addLogMessage</h3>
```php
public  void **addLogMessage**(string string)```
<div class="details">
<p>Adds a log message.</p><dl>
<dt>Parameters:</dt>
<dd>string - The log message</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/Compiler.php.md#line104" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\Compiler.php at line 104</a>

<h3 id="getLog()">getLog</h3>
```php
public  array **getLog**()```
<div class="details">
<p>Returns the log.</p><dl>
<dt>Returns:</dt>
<dd>Log array</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/symfony-components/Symfony/Component/DependencyInjection/Compiler/Compiler.php.md#line116" class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\Compiler.php at line 116</a>

<h3 id="compile()">compile</h3>
```php
public  void **compile**(<a href="../../../../symfony/component/dependencyinjection/containerbuilder.html">ContainerBuilder</a> container)```
<div class="details">
<p>Run the Compiler and process all Passes.</p><dl>
<dt>Api.</dt>
</dl>
</div>

- - -

