- - -

**Smarty\Smarty_Internal_Config_File_Compiler**
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_config_file_compiler.php at line 19</div>
#Class Smarty_Internal_Config_File_Compiler#

**Smarty_Internal_Config_File_Compiler**


- - -

<p class="signature">public  class **Smarty_Internal_Config_File_Compiler**</p>

<div class="comment" id="overview_description"><p>Main config file compiler class</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>Config</dd>
</dl>
- - -

<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td class="type"> Smarty_Internal_Config object</td>
<td class="description"><p class="name"><a href="#config">$config</a></p><p class="description">Smarty object</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#config_data">$config_data</a></p><p class="description">Compiled config data sections and variables</p></td>
</tr>
<tr>
<td class="type"> object</td>
<td class="description"><p class="name"><a href="#lex">$lex</a></p><p class="description">Lexer object</p></td>
</tr>
<tr>
<td class="type"> object</td>
<td class="description"><p class="name"><a href="#parser">$parser</a></p><p class="description">Parser object</p></td>
</tr>
<tr>
<td class="type"> Smarty object</td>
<td class="description"><p class="name"><a href="#smarty">$smarty</a></p><p class="description">Smarty object</p></td>
</tr>
</table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(<a href="../smarty/smarty.html">Smarty</a> smarty)</p><p class="description">Initialize compiler</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> bool</td>
<td class="description"><p class="name"><a href="#compileSource">compileSource</a>(<a href="../smarty/smarty_internal_config.html">Smarty_Internal_Config</a> config)</p><p class="description">Method to compile a Smarty template.</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#trigger_config_file_error">trigger_config_file_error</a>(string args)</p><p class="description">display compiler error messages without dyingIf parameter $args is empty it is a parser detected syntax error.
</p></td>
</tr>
</table>

##Field Detail##
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_config_file_compiler.php at line 47</div>
<h3 id="config">config</h3>

```php
public  Smarty_Internal_Config object$config
```
<div class="details">
<p>Smarty object</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_config_file_compiler.php at line 54</div>
<h3 id="config_data">config_data</h3>

```php
public  array$config_data = array()
```
<div class="details">
<p>Compiled config data sections and variables</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_config_file_compiler.php at line 26</div>
<h3 id="lex">lex</h3>

```php
public  object$lex = 'local'
```
<div class="details">
<p>Lexer object</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_config_file_compiler.php at line 33</div>
<h3 id="parser">parser</h3>

```php
public  object$parser
```
<div class="details">
<p>Parser object</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_config_file_compiler.php at line 40</div>
<h3 id="smarty">smarty</h3>

```php
public  Smarty object$smarty
```
<div class="details">
<p>Smarty object</p></div>

- - -

<h2 id="detail_method">Constructor Detail</h2>
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_config_file_compiler.php at line 61</div>
<h3 id="__construct()">__construct</h3>

```php
public  void **__construct**(<a href="../smarty/smarty.html">Smarty</a> smarty)
```
<div class="details">
<p>Initialize compiler</p><dl>
<dt>Parameters:</dt>
<dd>smarty - base instance</dd>
</dl>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_config_file_compiler.php at line 74</div>
<h3 id="compileSource()">compileSource</h3>

```php
public  bool **compileSource**(<a href="../smarty/smarty_internal_config.html">Smarty_Internal_Config</a> config)
```
<div class="details">
<p>Method to compile a Smarty template.</p><dl>
<dt>Parameters:</dt>
<dd>config - config object</dd>
<dt>Returns:</dt>
<dd>true if compiling succeeded, false if it failed</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_config_file_compiler.php at line 110</div>
<h3 id="trigger_config_file_error()">trigger_config_file_error</h3>

```php
public  void **trigger_config_file_error**(string args)
```
<div class="details">
<p>display compiler error messages without dying</p><p>If parameter $args is empty it is a parser detected syntax error.
In this case the parser is called to obtain information about exspected tokens.</p><p>If parameter $args contains a string this is used as error message</p><dl>
<dt>Parameters:</dt>
<dd>args - individual error message or null</dd>
</dl>
</div>

- - -

