
- - -

**Hirudo\Core\Context\AppConfig**
<div class="location">framework\hirudo\Hirudo\Core\Context\AppConfig.php at line 35</div>
#Class AppConfig#

**AppConfig**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/impl/joomla/joomlaappconfig.html">Hirudo\Impl\Joomla\JoomlaAppConfig</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/impl/standalone/sappconfig.html">Hirudo\Impl\StandAlone\SAppConfig</a> </dd>
</dl>

- - -

<p class="signature">public abstract  class **AppConfig**</p>

<div class="comment" id="overview_description"><p><p><strong>WARNING:</strong> AS THE CONFIGURATION SYSTEM IS NOT COMPLETE, THIS
CLASS IS SUBJECT TO DRASTIC CHANGES IN THE NEAR FUTURE.
If this issue: https://github.com/JeyDotC/Hirudo/issues/3 is closed, then
ignore this warning</p>.</p><p><p>This class brings support for configuration
based on the host CMS.</p></p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
</dl>

- - -

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>()</p><p class="description">Creates a new AppConfig and loads the current configuration.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> protected abstract  void</td>
<td class="description"><p class="name"><a href="#load">load</a>()</p><p class="description">Load the configuration data.</p></td>
</tr>
<tr>
<td class="type"> abstract  mixed</td>
<td class="description"><p class="name"><a href="#get">get</a>(string key, mixed default)</p><p class="description">Gets a value from the collected configuration data.</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>
<div class="location">framework\hirudo\Hirudo\Core\Context\AppConfig.php at line 40</div>
<h3 id="__construct()">__construct</h3>

```php
public  void **__construct**()
```
<div class="details">
<p>Creates a new AppConfig and loads the current configuration.</p></div>

- - -

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\hirudo\Hirudo\Core\Context\AppConfig.php at line 47</div>
<h3 id="load()">load</h3>

protected abstract  void **load** ()<div class="details">
<p>Load the configuration data.</p></div>

- - -

<div class="location">framework\hirudo\Hirudo\Core\Context\AppConfig.php at line 58</div>
<h3 id="get()">get</h3>

public abstract  mixed **get** (string key, mixed default)<div class="details">
<p>Gets a value from the collected configuration data.</p><dl>
<dt>Parameters:</dt>
<dd>key - The key that identifies the value in config.</dd>
<dd>default - A default value which is returned if there is no value associated to the given key.</dd>
<dt>Returns:</dt>
<dd>The value associated to the key. If the config value has inner data, the returned value will be an array.</dd>
</dl>
</div>

- - -

