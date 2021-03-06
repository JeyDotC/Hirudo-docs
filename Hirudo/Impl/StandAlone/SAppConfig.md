

- - -

**Hirudo\Impl\StandAlone\SAppConfig**


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/StandAlone/SAppConfig.php#L36" target='_blank'>framework\Hirudo\Impl\StandAlone\SAppConfig.php at line 36</a>

#Class SAppConfig#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/AppConfig.md">AppConfig</a>
 &gt; **SAppConfig**




- - -

<p><strong>public  class</strong> <span>SAppConfig</span>
<strong>extends</strong> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/AppConfig.md">AppConfig</a>

</p>

<div class="comment" id="overview_description"><p>Description of SAppConfig</p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
<dt>Hirudo\Core\Annotations\Export(id="Config").</dt>
</dl>


<hr />

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#get">get</a>(string key, mixed default)</p><p class="description">Gets a value from the collected configuration data.</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#load">load</a>()</p><p class="description">Load the configuration data.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#has">has</a>(mixed key)</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#loadapp">loadApp</a>(mixed appName)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#loadvalues">loadValues</a>(mixed values)</p><p class="description"></p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Hirudo\Core\Context\AppConfig</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/AppConfig.md#__construct">__construct</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/AppConfig.md#get">get</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/AppConfig.md#has">has</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/AppConfig.md#load">load</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/AppConfig.md#loadapp">loadApp</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/AppConfig.md#loadvalues">loadValues</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/StandAlone/SAppConfig.php#L44" target='_blank'>framework\Hirudo\Impl\StandAlone\SAppConfig.php at line 44</a>

<h3 id="get()">get</h3>
<span class='k'></span> <span class='nx'>mixed</span> <span class='nf'>get</span> (string key, mixed default)

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


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/StandAlone/SAppConfig.php#L52" target='_blank'>framework\Hirudo\Impl\StandAlone\SAppConfig.php at line 52</a>

<h3 id="load()">load</h3>
<span class='k'>protected </span> <span class='nx'>void</span> <span class='nf'>load</span> ()

<div class="details">
<p>Load the configuration data.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/StandAlone/SAppConfig.php#L58" target='_blank'>framework\Hirudo\Impl\StandAlone\SAppConfig.php at line 58</a>

<h3 id="has()">has</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>has</span> (mixed key)

<div class="details">
<p></p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/StandAlone/SAppConfig.php#L62" target='_blank'>framework\Hirudo\Impl\StandAlone\SAppConfig.php at line 62</a>

<h3 id="loadApp()">loadApp</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>loadApp</span> (mixed appName)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/StandAlone/SAppConfig.php#L87" target='_blank'>framework\Hirudo\Impl\StandAlone\SAppConfig.php at line 87</a>

<h3 id="loadValues()">loadValues</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>loadValues</span> (mixed values)

<div class="details">
<p></p>
</div>

- - -

