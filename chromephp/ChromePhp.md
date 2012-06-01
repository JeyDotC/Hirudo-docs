

- - -

**ChromePhp\ChromePhp**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/ChromePhp.php#L25" >ChromePhp.php at line 25</a>

#Class ChromePhp#

**ChromePhp**




- - -

<p class="signature"><span class='k'>public  class</span> <span class='nx'>ChromePhp</span></p>

<div class="comment" id="overview_description"><p>Server Side Chrome PHP debugger class</p></div>

<dl>
<dt>Author:</dt>
<dd>Craig Campbell <iamcraigcampbell@gmail.com></dd>
</dl>


- - -



<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#_backtraces"> $_backtraces</a>
                                </p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>bool</span></td>
<td class="description"><p class="name" ><a href="#_error_triggered"> $_error_triggered</a>
                                </p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'>protected static </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo/blob/master/chromephp/chromephp.html'>ChromePhp</a></span></td>
<td class="description"><p class="name" ><a href="#_instance"> $_instance</a>
                                </p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#_processed"> $_processed</a>
                                </p><p class="description">Prevent recursion when working with objects referring to each other</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#_settings"> $_settings</a>
                                </p><p class="description"></p></td>
</tr>
</table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'>private </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>()</p><p class="description">constructor</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'>static </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo/blob/master/chromephp/chromephp.html>ChromePhp</a></span></td>
<td class="description"><p class="name"><a href="#getinstance">getInstance</a>()</p><p class="description">gets instance of this class</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#log">log</a>(string label, mixed value, string severity)</p><p class="description">logs a variable to the console</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#warn">warn</a>(string label, mixed value)</p><p class="description">logs a warning to the console</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#error">error</a>(string label, mixed value)</p><p class="description">logs an error to the console</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#group">group</a>(string value)</p><p class="description">sends a group log</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#info">info</a>(string value)</p><p class="description">sends an info log</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#groupcollapsed">groupCollapsed</a>(string value)</p><p class="description">sends a collapsed group log</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#groupend">groupEnd</a>(string value)</p><p class="description">ends a group log</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#addsetting">addSetting</a>(string key, mixed value)</p><p class="description">adds a setting</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#addsettings">addSettings</a>(array settings)</p><p class="description">add ability to set multiple settings in one call</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#getsetting">getSetting</a>(string key)</p><p class="description">gets a setting</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/ChromePhp.php#L64" >ChromePhp.php at line 64</a>

<h3 id="__construct">__construct</h3>
<span class='k'>private </span> <span class='nx'>void</span> <span class='nf'>__construct</span> ()

<div class="details">
<p>constructor</p>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/ChromePhp.php#L75" >ChromePhp.php at line 75</a>

<h3 id="getInstance()">getInstance</h3>
<span class='k'>static </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo/blob/master/chromephp/chromephp.html>ChromePhp</a></span> <span class='nf'>getInstance</span> ()

<div class="details">
<p>gets instance of this class</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/ChromePhp.php#L90" >ChromePhp.php at line 90</a>

<h3 id="log()">log</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>log</span> (string label, mixed value, string severity)

<div class="details">
<p>logs a variable to the console</p><dl>
<dt>Parameters:</dt>
<dd></dd>
<dd></dd>
<dd>severity - ChromePhp::LOG || ChromePhp::WARN || ChromePhp::ERROR</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/ChromePhp.php#L109" >ChromePhp.php at line 109</a>

<h3 id="warn()">warn</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>warn</span> (string label, mixed value)

<div class="details">
<p>logs a warning to the console</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/ChromePhp.php#L120" >ChromePhp.php at line 120</a>

<h3 id="error()">error</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>error</span> (string label, mixed value)

<div class="details">
<p>logs an error to the console</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/ChromePhp.php#L129" >ChromePhp.php at line 129</a>

<h3 id="group()">group</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>group</span> (string value)

<div class="details">
<p>sends a group log</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/ChromePhp.php#L138" >ChromePhp.php at line 138</a>

<h3 id="info()">info</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>info</span> (string value)

<div class="details">
<p>sends an info log</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/ChromePhp.php#L147" >ChromePhp.php at line 147</a>

<h3 id="groupCollapsed()">groupCollapsed</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>groupCollapsed</span> (string value)

<div class="details">
<p>sends a collapsed group log</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/ChromePhp.php#L156" >ChromePhp.php at line 156</a>

<h3 id="groupEnd()">groupEnd</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>groupEnd</span> (string value)

<div class="details">
<p>ends a group log</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/ChromePhp.php#L328" >ChromePhp.php at line 328</a>

<h3 id="addSetting()">addSetting</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>addSetting</span> (string key, mixed value)

<div class="details">
<p>adds a setting</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/ChromePhp.php#L338" >ChromePhp.php at line 338</a>

<h3 id="addSettings()">addSettings</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>addSettings</span> (array settings)

<div class="details">
<p>add ability to set multiple settings in one call</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/ChromePhp.php#L350" >ChromePhp.php at line 350</a>

<h3 id="getSetting()">getSetting</h3>
<span class='k'></span> <span class='nx'>mixed</span> <span class='nf'>getSetting</span> (string key)

<div class="details">
<p>gets a setting</p>
</div>

- - -

