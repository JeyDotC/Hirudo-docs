

- - -

**Hirudo\Core\Context\AppConfig**


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Core/Context/AppConfig.php#L35" target='_blank'>framework\Hirudo\Core\Context\AppConfig.php at line 35</a>

#Class AppConfig#

**AppConfig**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Impl/Drupal/DrupalAppConfig.md">Hirudo\Impl\Drupal\DrupalAppConfig</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Impl/StandAlone/SAppConfig.md">Hirudo\Impl\StandAlone\SAppConfig</a> </dd>
</dl>



- - -

<p><strong>public abstract  class</strong> <span>AppConfig</span></p>

<div class="comment" id="overview_description"><p><p><strong>WARNING:</strong> AS THE CONFIGURATION SYSTEM IS NOT COMPLETE, THIS
CLASS IS SUBJECT TO DRASTIC CHANGES IN THE NEAR FUTURE.
If this issue: https://github.com/JeyDotC/Hirudo/issues/3 is closed, then
ignore this warning</p>.</p><p><p>This class brings support for configuration
based on the host CMS.</p></p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
</dl>


<hr />

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>()</p><p class="description">Creates a new AppConfig and loads the current configuration.</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'>protected abstract </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#load">load</a>()</p><p class="description">Load the configuration data.</p></td>
</tr>
<tr>
<td><span class='k'>abstract </span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#get">get</a>(string key, mixed default)</p><p class="description">Gets a value from the collected configuration data.</p></td>
</tr>
<tr>
<td><span class='k'>abstract </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#loadapp">loadApp</a>(mixed appName)</p></td>
</tr>
<tr>
<td><span class='k'>abstract </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#loadvalues">loadValues</a>(mixed values)</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'>abstract </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#has">has</a>(mixed key)</p><p class="description"></p></td>
</tr>
</table>

<h2>Constructor Detail</h2>


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Core/Context/AppConfig.php#L40" target='_blank'>framework\Hirudo\Core\Context\AppConfig.php at line 40</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> ()

<div class="details">
<p>Creates a new AppConfig and loads the current configuration.</p>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Core/Context/AppConfig.php#L47" target='_blank'>framework\Hirudo\Core\Context\AppConfig.php at line 47</a>

<h3 id="load()">load</h3>
<span class='k'>protected abstract </span> <span class='nx'>void</span> <span class='nf'>load</span> ()

<div class="details">
<p>Load the configuration data.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Core/Context/AppConfig.php#L58" target='_blank'>framework\Hirudo\Core\Context\AppConfig.php at line 58</a>

<h3 id="get()">get</h3>
<span class='k'>abstract </span> <span class='nx'>mixed</span> <span class='nf'>get</span> (string key, mixed default)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Core/Context/AppConfig.php#L60" target='_blank'>framework\Hirudo\Core\Context\AppConfig.php at line 60</a>

<h3 id="loadApp()">loadApp</h3>
<span class='k'>abstract </span> <span class='nx'>void</span> <span class='nf'>loadApp</span> (mixed appName)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Core/Context/AppConfig.php#L65" target='_blank'>framework\Hirudo\Core\Context\AppConfig.php at line 65</a>

<h3 id="loadValues()">loadValues</h3>
<span class='k'>abstract </span> <span class='nx'>void</span> <span class='nf'>loadValues</span> (mixed values)

<div class="details">
<p></p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Core/Context/AppConfig.php#L70" target='_blank'>framework\Hirudo\Core\Context\AppConfig.php at line 70</a>

<h3 id="has()">has</h3>
<span class='k'>abstract </span> <span class='nx'>void</span> <span class='nf'>has</span> (mixed key)

<div class="details">
<p></p>
</div>

- - -

