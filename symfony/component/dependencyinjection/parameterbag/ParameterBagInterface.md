
- - -

**Symfony\Component\DependencyInjection\ParameterBag\ParameterBagInterface**
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ParameterBag\ParameterBagInterface.php at line 23</div>
#Interface ParameterBagInterface#

**ParameterBagInterface**


- - -

<p class="signature">public  interface **ParameterBagInterface**</p>

<div class="comment" id="overview_description"><p>ParameterBagInterface.</p></div>

<dl>
<dt>Author:</dt>
<dd>Fabien Potencier <fabien@symfony.com></dd>
<dt>Api.</dt>
</dl>

- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#clear">clear</a>()</p><p class="description">Clears all parameters.</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#add">add</a>(array parameters)</p><p class="description">Adds parameters to the service container parameters.</p></td>
</tr>
<tr>
<td class="type">  array</td>
<td class="description"><p class="name"><a href="#all">all</a>()</p><p class="description">Gets the service container parameters.</p></td>
</tr>
<tr>
<td class="type">  mixed</td>
<td class="description"><p class="name"><a href="#get">get</a>(string name)</p><p class="description">Gets a service container parameter.</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#set">set</a>(string name, mixed value)</p><p class="description">Sets a service container parameter.</p></td>
</tr>
<tr>
<td class="type">  Boolean</td>
<td class="description"><p class="name"><a href="#has">has</a>(string name)</p><p class="description">Returns true if a parameter name is defined.</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#resolve">resolve</a>()</p><p class="description">Replaces parameter placeholders (%name%) by their values for all parameters.</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#resolvevalue">resolveValue</a>(mixed value)</p><p class="description">Replaces parameter placeholders (%name%) by their values.</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ParameterBag\ParameterBagInterface.php at line 30</div>
<h3 id="clear()">clear</h3>

public  void **clear** ()<div class="details">
<p>Clears all parameters.</p><dl>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ParameterBag\ParameterBagInterface.php at line 39</div>
<h3 id="add()">add</h3>

public  void **add** (array parameters)<div class="details">
<p>Adds parameters to the service container parameters.</p><dl>
<dt>Parameters:</dt>
<dd>parameters - An array of parameters</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ParameterBag\ParameterBagInterface.php at line 48</div>
<h3 id="all()">all</h3>

public  array **all** ()<div class="details">
<p>Gets the service container parameters.</p><dl>
<dt>Returns:</dt>
<dd>An array of parameters</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ParameterBag\ParameterBagInterface.php at line 61</div>
<h3 id="get()">get</h3>

public  mixed **get** (string name)<div class="details">
<p>Gets a service container parameter.</p><dl>
<dt>Parameters:</dt>
<dd>name - The parameter name</dd>
<dt>Returns:</dt>
<dd>The parameter value</dd>
<dt>Throws:</dt>
<dd><a href="../../../../symfony/component/dependencyinjection/exception/parameternotfoundexception.html">ParameterNotFoundException</a> - if the parameter is not defined</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ParameterBag\ParameterBagInterface.php at line 71</div>
<h3 id="set()">set</h3>

public  void **set** (string name, mixed value)<div class="details">
<p>Sets a service container parameter.</p><dl>
<dt>Parameters:</dt>
<dd>name - The parameter name</dd>
<dd>value - The parameter value</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ParameterBag\ParameterBagInterface.php at line 82</div>
<h3 id="has()">has</h3>

public  Boolean **has** (string name)<div class="details">
<p>Returns true if a parameter name is defined.</p><dl>
<dt>Parameters:</dt>
<dd>name - The parameter name</dd>
<dt>Returns:</dt>
<dd>true if the parameter name is defined, false otherwise</dd>
<dt>Api.</dt>
</dl>
</div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ParameterBag\ParameterBagInterface.php at line 87</div>
<h3 id="resolve()">resolve</h3>

public  void **resolve** ()<div class="details">
<p>Replaces parameter placeholders (%name%) by their values for all parameters.</p></div>

- - -

<div class="location">framework\libs\symfony-components\Symfony\Component\DependencyInjection\ParameterBag\ParameterBagInterface.php at line 96</div>
<h3 id="resolveValue()">resolveValue</h3>

public  void **resolveValue** (mixed value)<div class="details">
<p>Replaces parameter placeholders (%name%) by their values.</p><dl>
<dt>Parameters:</dt>
<dd>value - A value</dd>
<dt>Throws:</dt>
<dd><a href="../../../../symfony/component/dependencyinjection/exception/parameternotfoundexception.html">ParameterNotFoundException</a> - if a placeholder references a parameter that does not exist</dd>
</dl>
</div>

- - -

