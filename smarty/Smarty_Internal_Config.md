- - -

**Smarty\Smarty_Internal_Config**
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_config.php at line 22</div>
#Class Smarty_Internal_Config#

**Smarty_Internal_Config**


- - -

<p class="signature">public  class **Smarty_Internal_Config**</p>

<div class="comment" id="overview_description"><p>Smarty Internal Plugin Config</p><p>Main class for config variables</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>Config</dd>
<dt>Property:</dt>
<dd>Smarty_Config_Source $source</dd>
<dd>Smarty_Config_Compiled $compiled</dd>
<dt>Ignore.</dt>
</dl>
- - -

<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#compiled_config">$compiled_config</a></p><p class="description">Compiled config file</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#compiled_filepath">$compiled_filepath</a></p><p class="description">filepath of compiled config file</p></td>
</tr>
<tr>
<td class="type"> int</td>
<td class="description"><p class="name"><a href="#compiled_timestamp">$compiled_timestamp</a></p><p class="description">Filemtime of compiled config Filemtime</p></td>
</tr>
<tr>
<td class="type"> Smarty_Internal_Config_File_Compiler object</td>
<td class="description"><p class="name"><a href="#compiler_object">$compiler_object</a></p><p class="description">Config file compiler object</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#config_resource">$config_resource</a></p><p class="description">Config resource</p></td>
</tr>
<tr>
<td class="type"> object</td>
<td class="description"><p class="name"><a href="#data">$data</a></p><p class="description">Object of config var storage</p></td>
</tr>
<tr>
<td class="type"> bool</td>
<td class="description"><p class="name"><a href="#mustCompile">$mustCompile</a></p><p class="description">flag if compiled config file is invalid and must be (re)compiled</p></td>
</tr>
<tr>
<td class="type"> Smarty object</td>
<td class="description"><p class="name"><a href="#smarty">$smarty</a></p><p class="description">Samrty instance</p></td>
</tr>
</table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(string config_resource, <a href="../smarty/smarty.html">Smarty</a> smarty, object data)</p><p class="description">Constructor of config file object</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#getCompiledFilepath">getCompiledFilepath</a>()</p><p class="description">Returns the compiled  filepath</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#buildCompiledFilepath">buildCompiledFilepath</a>()</p><p class="description">Get file path.</p></td>
</tr>
<tr>
<td class="type"> integer</td>
<td class="description"><p class="name"><a href="#getCompiledTimestamp">getCompiledTimestamp</a>()</p><p class="description">Returns the timpestamp of the compiled file</p></td>
</tr>
<tr>
<td class="type"> boolean</td>
<td class="description"><p class="name"><a href="#mustCompile">mustCompile</a>()</p><p class="description">Returns if the current config file must be compiledIt does compare the timestamps of config source and the compiled config and checks the force compile configuration</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#getCompiledConfig">getCompiledConfig</a>()</p><p class="description">Returns the compiled config fileIt checks if the config file must be compiled or just read the compiled version</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#compileConfigSource">compileConfigSource</a>()</p><p class="description">Compiles the config files</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#loadConfigVars">loadConfigVars</a>(mixed sections, object scope)</p><p class="description">load config variables</p></td>
</tr>
</table>

##Field Detail##
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_config.php at line 46</div>
<h3 id="compiled_config">compiled_config</h3>
```php
public  string **$compiled_config** = null```
<div class="details">
<p>Compiled config file</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_config.php at line 52</div>
<h3 id="compiled_filepath">compiled_filepath</h3>
```php
public  string **$compiled_filepath** = null```
<div class="details">
<p>filepath of compiled config file</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_config.php at line 58</div>
<h3 id="compiled_timestamp">compiled_timestamp</h3>
```php
public  int **$compiled_timestamp** = null```
<div class="details">
<p>Filemtime of compiled config Filemtime</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_config.php at line 69</div>
<h3 id="compiler_object">compiler_object</h3>
```php
public  Smarty_Internal_Config_File_Compiler object **$compiler_object** = null```
<div class="details">
<p>Config file compiler object</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_config.php at line 40</div>
<h3 id="config_resource">config_resource</h3>
```php
public  string **$config_resource** = null```
<div class="details">
<p>Config resource</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_config.php at line 35</div>
<h3 id="data">data</h3>
```php
public  object **$data** = null```
<div class="details">
<p>Object of config var storage</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_config.php at line 63</div>
<h3 id="mustCompile">mustCompile</h3>
```php
public  bool **$mustCompile** = null```
<div class="details">
<p>flag if compiled config file is invalid and must be (re)compiled</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_config.php at line 29</div>
<h3 id="smarty">smarty</h3>
```php
public  Smarty object **$smarty** = null```
<div class="details">
<p>Samrty instance</p></div>

- - -

<h2 id="detail_method">Constructor Detail</h2>
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_config.php at line 78</div>
<h3 id="__construct()">__construct</h3>
```php
public  void **__construct**(string config_resource, <a href="../smarty/smarty.html">Smarty</a> smarty, object data)```
<div class="details">
<p>Constructor of config file object</p><dl>
<dt>Parameters:</dt>
<dd>config_resource - config file resource name</dd>
<dd>smarty - Smarty instance</dd>
<dd>data - object for config vars storage</dd>
</dl>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_config.php at line 90</div>
<h3 id="getCompiledFilepath()">getCompiledFilepath</h3>
```php
public  string **getCompiledFilepath**()```
<div class="details">
<p>Returns the compiled  filepath</p><dl>
<dt>Returns:</dt>
<dd>the compiled filepath</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_config.php at line 102</div>
<h3 id="buildCompiledFilepath()">buildCompiledFilepath</h3>
```php
public  string **buildCompiledFilepath**()```
<div class="details">
<p>Get file path.</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_config.php at line 128</div>
<h3 id="getCompiledTimestamp()">getCompiledTimestamp</h3>
```php
public  integer **getCompiledTimestamp**()```
<div class="details">
<p>Returns the timpestamp of the compiled file</p><dl>
<dt>Returns:</dt>
<dd>the file timestamp</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_config.php at line 142</div>
<h3 id="mustCompile()">mustCompile</h3>
```php
public  boolean **mustCompile**()```
<div class="details">
<p>Returns if the current config file must be compiled</p><p>It does compare the timestamps of config source and the compiled config and checks the force compile configuration</p><dl>
<dt>Returns:</dt>
<dd>true if the file must be compiled</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_config.php at line 156</div>
<h3 id="getCompiledConfig()">getCompiledConfig</h3>
```php
public  string **getCompiledConfig**()```
<div class="details">
<p>Returns the compiled config file</p><p>It checks if the config file must be compiled or just read the compiled version</p><dl>
<dt>Returns:</dt>
<dd>the compiled config file</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_config.php at line 174</div>
<h3 id="compileConfigSource()">compileConfigSource</h3>
```php
public  void **compileConfigSource**()```
<div class="details">
<p>Compiles the config files</p><dl>
<dt>Throws:</dt>
<dd>Exception</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_config.php at line 208</div>
<h3 id="loadConfigVars()">loadConfigVars</h3>
```php
public  void **loadConfigVars**(mixed sections, object scope)```
<div class="details">
<p>load config variables</p><dl>
<dt>Parameters:</dt>
<dd>sections - array of section names, single section or null</dd>
<dd>scope - global,parent or local</dd>
</dl>
</div>

- - -

