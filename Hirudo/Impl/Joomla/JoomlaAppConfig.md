

- - -

**Hirudo\Impl\Joomla\JoomlaAppConfig**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/Joomla/JoomlaAppConfig.php#L37" target='_blank'>framework\hirudo\Hirudo\Impl\Joomla\JoomlaAppConfig.php at line 37</a>

#Class JoomlaAppConfig#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/AppConfig.md">AppConfig</a>
 &gt; **JoomlaAppConfig**




- - -

<p><strong>public  class</strong> <span>JoomlaAppConfig</span>
<strong>extends</strong> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/AppConfig.md">AppConfig</a>

</p>

<div class="comment" id="overview_description"><p>Description of JAppConfig</p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
<dt>Export:</dt>
<dd>(id="config", factory="instance")</dd>
</dl>


<hr />

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>JAppConfig</span></td>
<td class="description"><p class="name"><a href="#instance">instance</a>()</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#get">get</a>(string key, mixed default)</p><p class="description">Gets a value from the collected configuration data.</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#load">load</a>()</p><p class="description">Load the configuration data.</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Hirudo\Core\Context\AppConfig</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/AppConfig.md#__construct">__construct</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/AppConfig.md#get">get</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/AppConfig.md#load">load</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/Joomla/JoomlaAppConfig.php#L49" target='_blank'>framework\hirudo\Hirudo\Impl\Joomla\JoomlaAppConfig.php at line 49</a>

<h3 id="instance()">instance</h3>
<span class='k'>static </span> <span class='nx'>JAppConfig</span> <span class='nf'>instance</span> ()

<div class="details">
<p></p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/Joomla/JoomlaAppConfig.php#L63" target='_blank'>framework\hirudo\Hirudo\Impl\Joomla\JoomlaAppConfig.php at line 63</a>

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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Impl/Joomla/JoomlaAppConfig.php#L67" target='_blank'>framework\hirudo\Hirudo\Impl\Joomla\JoomlaAppConfig.php at line 67</a>

<h3 id="load()">load</h3>
<span class='k'>protected </span> <span class='nx'>void</span> <span class='nf'>load</span> ()

<div class="details">
<p>Load the configuration data.</p>
</div>

- - -

