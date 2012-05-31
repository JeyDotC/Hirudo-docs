- - -

**Hirudo\Impl\StandAlone\SAppConfig**
<div class="location">framework\hirudo\Hirudo\Impl\StandAlone\SAppConfig.php at line 36</div>
#Class SAppConfig#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/appconfig.html">AppConfig</a>
    ***SAppConfig**


- - -

<p class="signature">public  class **SAppConfig**
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/appconfig.html">AppConfig</a>

</p>

<div class="comment" id="overview_description"><p>Description of SAppConfig</p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
<dt>Hirudo\Core\Annotations\Export(id="Config").</dt>
</dl>
- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> mixed</td>
<td class="description"><p class="name"><a href="#get">get</a>(string key, mixed default)</p><p class="description">Gets a value from the collected configuration data.</p></td>
</tr>
<tr>
<td class="type">protected  void</td>
<td class="description"><p class="name"><a href="#load">load</a>()</p><p class="description">Load the configuration data.</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Hirudo\Core\Context\AppConfig</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/appconfig.html#__construct()">__construct</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/appconfig.html#get()">get</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/core/context/appconfig.html#load()">load</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\hirudo\Hirudo\Impl\StandAlone\SAppConfig.php at line 44</div>
<h3 id="get()">get</h3>

```php
public  mixed **get**(string key, mixed default)
```
<div class="details">
<p>Gets a value from the collected configuration data.</p><dl>
<dt>Parameters:</dt>
<dd>key - The key that identifies the value in config.</dd>
<dd>default - A default value which is returned if there is no value associated to the given key.</dd>
<dt>Returns:</dt>
<dd>The value associated to the key. If the config value has inner data, the returned value will be an array.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Impl\StandAlone\SAppConfig.php at line 52</div>
<h3 id="load()">load</h3>

```php
protected  void **load**()
```
<div class="details">
<p>Load the configuration data.</p></div>

- - -

