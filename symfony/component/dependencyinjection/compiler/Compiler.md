
- - -

**Symfony\Component\DependencyInjection\Compiler\Compiler**
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\Compiler.php at line 24</div>
#Class Compiler#

**Compiler**


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
<td class="description"><p class="name"><a href="#__construct">__construct</a>()</p><p class="description">Constructor.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type">  <a href="../../../../symfony/component/dependencyinjection/compiler/passconfig.html">PassConfig</a></td>
<td class="description"><p class="name"><a href="#getpassconfig">getPassConfig</a>()</p><p class="description">Returns the PassConfig.</p></td>
</tr>
<tr>
<td class="type">  <a href="../../../../symfony/component/dependencyinjection/compiler/servicereferencegraph.html">ServiceReferenceGraph</a></td>
<td class="description"><p class="name"><a href="#getservicereferencegraph">getServiceReferenceGraph</a>()</p><p class="description">Returns the ServiceReferenceGraph.</p></td>
</tr>
<tr>
<td class="type">  <a href="../../../../symfony/component/dependencyinjection/compiler/loggingformatter.html">LoggingFormatter</a></td>
<td class="description"><p class="name"><a href="#getloggingformatter">getLoggingFormatter</a>()</p><p class="description">Returns the logging formatter which can be used by compilation passes.</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#addpass">addPass</a>(<a href="../../../../symfony/component/dependencyinjection/compiler/compilerpassinterface.html">CompilerPassInterface</a> pass, string type)</p><p class="description">Adds a pass to the PassConfig.</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#addlogmessage">addLogMessage</a>(string string)</p><p class="description">Adds a log message.</p></td>
</tr>
<tr>
<td class="type">  array</td>
<td class="description"><p class="name"><a href="#getlog">getLog</a>()</p><p class="description">Returns the log.</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#compile">compile</a>(<a href="../../../../symfony/component/dependencyinjection/containerbuilder.html">ContainerBuilder</a> container)</p><p class="description">Run the Compiler and process all Passes.</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\Compiler.php at line 34</div>
<h3 id="__construct()">__construct</h3>

```php
public  void **__construct**()
```
<div class="details">
<p>Constructor.</p></div>

- - -

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\Compiler.php at line 49</div>
<h3 id="getPassConfig()">getPassConfig</h3>

public  <a href="../../../../symfony/component/dependencyinjection/compiler/passconfig.html">PassConfig</a> **getPassConfig** ()<div class="details">
<p>Returns the PassConfig.</p><dl>
<dt>Returns:</dt>
<dd>The PassConfig instance</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\Compiler.php at line 61</div>
<h3 id="getServiceReferenceGraph()">getServiceReferenceGraph</h3>

public  <a href="../../../../symfony/component/dependencyinjection/compiler/servicereferencegraph.html">ServiceReferenceGraph</a> **getServiceReferenceGraph** ()<div class="details">
<p>Returns the ServiceReferenceGraph.</p><dl>
<dt>Returns:</dt>
<dd>The ServiceReferenceGraph instance</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\Compiler.php at line 71</div>
<h3 id="getLoggingFormatter()">getLoggingFormatter</h3>

public  <a href="../../../../symfony/component/dependencyinjection/compiler/loggingformatter.html">LoggingFormatter</a> **getLoggingFormatter** ()<div class="details">
<p>Returns the logging formatter which can be used by compilation passes.</p></div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\Compiler.php at line 84</div>
<h3 id="addPass()">addPass</h3>

public  void **addPass** (<a href="../../../../symfony/component/dependencyinjection/compiler/compilerpassinterface.html">CompilerPassInterface</a> pass, string type)<div class="details">
<p>Adds a pass to the PassConfig.</p><dl>
<dt>Parameters:</dt>
<dd>pass - A compiler pass</dd>
<dd>type - The type of the pass</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\Compiler.php at line 94</div>
<h3 id="addLogMessage()">addLogMessage</h3>

public  void **addLogMessage** (string string)<div class="details">
<p>Adds a log message.</p><dl>
<dt>Parameters:</dt>
<dd>string - The log message</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\Compiler.php at line 104</div>
<h3 id="getLog()">getLog</h3>

public  array **getLog** ()<div class="details">
<p>Returns the log.</p><dl>
<dt>Returns:</dt>
<dd>Log array</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\Compiler\Compiler.php at line 116</div>
<h3 id="compile()">compile</h3>

public  void **compile** (<a href="../../../../symfony/component/dependencyinjection/containerbuilder.html">ContainerBuilder</a> container)<div class="details">
<p>Run the Compiler and process all Passes.</p><dl>
<dt>Api.</dt>
</dl>
</div>

- - -

