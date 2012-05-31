- - -

**Hirudo\Core\Exceptions\HirudoException**
<div class="location">framework\hirudo\Hirudo\Core\Exceptions\HirudoException.php at line 37</div>
#Class HirudoException#

\Exception
***HirudoException**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/exceptions/applicationnotfoundexception.html">ApplicationNotFoundException</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/exceptions/modulenotfoundexception.html">ModuleNotFoundException</a> </dd>
</dl>

- - -

<p class="signature">public  class **HirudoException**
extends \Exception

</p>

<div class="comment" id="overview_description"><p><p>Base class for exceptions occurred on Hirudo. This class contains the
current ModuleCall.</p></p><p><p>All exceptions thrown by an application that doesn't inherit this class,
are wraped into an instance of this class as the 'previous' exception.</p></p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
<dt>See Also:</dt>
<dd>\Exception</dd>
</dl>
- - -

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(<a href="../../../hirudo/core/context/modulecall.html">ModuleCall</a> call, string message, \Exception previous)</p><p class="description">Creates a HirudoException.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#getApp">getApp</a>()</p><p class="description">Gets the name of the application in which this exception were thrown.</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#getModule">getModule</a>()</p><p class="description">Gets the name of the module in which this exception were thrown.</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#getTask">getTask</a>()</p><p class="description">Gets the task of the application in which this exception were thrown.</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>
<div class="location">framework\hirudo\Hirudo\Core\Exceptions\HirudoException.php at line 52</div>
<h3 id="__construct()">__construct</h3>

```php
public  void **__construct**(<a href="../../../hirudo/core/context/modulecall.html">ModuleCall</a> call, string message, \Exception previous)
```
<div class="details">
<p>Creates a HirudoException.</p><dl>
<dt>Parameters:</dt>
<dd>call - The module call in which this exception were thrown.</dd>
<dd>message - A useful message.</dd>
<dd>previous - An inner exception.</dd>
</dl>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\hirudo\Hirudo\Core\Exceptions\HirudoException.php at line 70</div>
<h3 id="getApp()">getApp</h3>

```php
public  string **getApp**()
```
<div class="details">
<p>Gets the name of the application in which this exception were thrown.</p><dl>
<dt>Returns:</dt>
<dd>The application name.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Exceptions\HirudoException.php at line 79</div>
<h3 id="getModule()">getModule</h3>

```php
public  string **getModule**()
```
<div class="details">
<p>Gets the name of the module in which this exception were thrown.</p><dl>
<dt>Returns:</dt>
<dd>The module name.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Exceptions\HirudoException.php at line 87</div>
<h3 id="getTask()">getTask</h3>

```php
public  string **getTask**()
```
<div class="details">
<p>Gets the task of the application in which this exception were thrown.</p><dl>
<dt>Returns:</dt>
<dd>The task name.</dd>
</dl>
</div>

- - -

