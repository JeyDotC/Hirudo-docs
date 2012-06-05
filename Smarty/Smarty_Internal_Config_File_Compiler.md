

- - -

**Smarty\Smarty_Internal_Config_File_Compiler**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_config_file_compiler.php#L19" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_config_file_compiler.php at line 19</a>

#Class Smarty_Internal_Config_File_Compiler#

**Smarty_Internal_Config_File_Compiler**




- - -

<p><strong>public  class</strong> <span>Smarty_Internal_Config_File_Compiler</span></p>

<div class="comment" id="overview_description"><p>Main config file compiler class</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>Config</dd>
</dl>


- - -



<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>Smarty_Internal_Config object</span></td>
<td class="description"><p class="name" ><a href="#config"> $config</a>
                                </p><p class="description">Smarty object</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#config_data"> $config_data</a>
                                </p><p class="description">Compiled config data sections and variables</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>object</span></td>
<td class="description"><p class="name" ><a href="#lex"> $lex</a>
                                </p><p class="description">Lexer object</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>object</span></td>
<td class="description"><p class="name" ><a href="#parser"> $parser</a>
                                </p><p class="description">Parser object</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>Smarty object</span></td>
<td class="description"><p class="name" ><a href="#smarty"> $smarty</a>
                                </p><p class="description">Smarty object</p></td>
</tr>
</table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty.md">Smarty</a> smarty)</p><p class="description">Initialize compiler</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>bool</span></td>
<td class="description"><p class="name"><a href="#compilesource">compileSource</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Internal_Config.md">Smarty_Internal_Config</a> config)</p><p class="description">Method to compile a Smarty template.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#trigger_config_file_error">trigger_config_file_error</a>(string args)</p><p class="description">display compiler error messages without dyingIf parameter $args is empty it is a parser detected syntax error.
</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_config_file_compiler.php#L61" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_config_file_compiler.php at line 61</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty.md">Smarty</a> smarty)

<div class="details">
<p>Initialize compiler</p><dl>
<dt>Parameters:</dt>
<dd>smarty - base instance</dd>
</dl>

</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_config_file_compiler.php#L74" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_config_file_compiler.php at line 74</a>

<h3 id="compileSource()">compileSource</h3>
<span class='k'></span> <span class='nx'>bool</span> <span class='nf'>compileSource</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Internal_Config.md">Smarty_Internal_Config</a> config)

<div class="details">
<p>Method to compile a Smarty template.</p><dl>
<dt>Parameters:</dt>
<dd>config - config object</dd>
<dt>Returns:</dt>
<dd>true if compiling succeeded, false if it failed</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_config_file_compiler.php#L110" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_config_file_compiler.php at line 110</a>

<h3 id="trigger_config_file_error()">trigger_config_file_error</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>trigger_config_file_error</span> (string args)

<div class="details">
<p>display compiler error messages without dying</p><p>If parameter $args is empty it is a parser detected syntax error.
In this case the parser is called to obtain information about exspected tokens.</p><p>If parameter $args contains a string this is used as error message</p><dl>
<dt>Parameters:</dt>
<dd>args - individual error message or null</dd>
</dl>

</div>

- - -

