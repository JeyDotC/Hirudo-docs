

- - -

**Smarty\Smarty_Internal_Config**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_config.php#L22" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_config.php at line 22</a>

#Class Smarty_Internal_Config#

**Smarty_Internal_Config**




- - -

<p><strong>public  class</strong> <span>Smarty_Internal_Config</span></p>

<div class="comment" id="overview_description"><p>Smarty Internal Plugin Config</p><p>Main class for config variables</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>Config</dd>
<dt>Property:</dt>
<dd>Smarty_Config_Source $source</dd>
<dd>Smarty_Config_Compiled $compiled</dd>
<dt>Ignore.</dt>
</dl>


<hr />



<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Config.md#compiled_config"> $compiled_config</a>
                                </p><p class="description">Compiled config file</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Config.md#compiled_filepath"> $compiled_filepath</a>
                                </p><p class="description">filepath of compiled config file</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>int</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Config.md#compiled_timestamp"> $compiled_timestamp</a>
                                </p><p class="description">Filemtime of compiled config Filemtime</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>Smarty_Internal_Config_File_Compiler object</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Config.md#compiler_object"> $compiler_object</a>
                                </p><p class="description">Config file compiler object</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Config.md#config_resource"> $config_resource</a>
                                </p><p class="description">Config resource</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>object</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Config.md#data"> $data</a>
                                </p><p class="description">Object of config var storage</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>bool</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Config.md#mustcompile"> $mustCompile</a>
                                </p><p class="description">flag if compiled config file is invalid and must be (re)compiled</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>Smarty object</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Config.md#smarty"> $smarty</a>
                                </p><p class="description">Samrty instance</p></td>
</tr>
</table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(string config_resource, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md">Smarty</a> smarty, object data)</p><p class="description">Constructor of config file object</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getcompiledfilepath">getCompiledFilepath</a>()</p><p class="description">Returns the compiled  filepath</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#buildcompiledfilepath">buildCompiledFilepath</a>()</p><p class="description">Get file path.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>integer</span></td>
<td class="description"><p class="name"><a href="#getcompiledtimestamp">getCompiledTimestamp</a>()</p><p class="description">Returns the timpestamp of the compiled file</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#mustcompile">mustCompile</a>()</p><p class="description">Returns if the current config file must be compiledIt does compare the timestamps of config source and the compiled config and checks the force compile configuration</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getcompiledconfig">getCompiledConfig</a>()</p><p class="description">Returns the compiled config fileIt checks if the config file must be compiled or just read the compiled version</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#compileconfigsource">compileConfigSource</a>()</p><p class="description">Compiles the config files</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#loadconfigvars">loadConfigVars</a>(mixed sections, object scope)</p><p class="description">load config variables</p></td>
</tr>
</table>

##Field Detail##

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_config.php#L46" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_config.php at line 46</a>

<h3 id="compiled_config">compiled_config</h3>
<span class='k'></span> <span class='nx'>string</span><span class='no'> $compiled_config</span><span class='o'> = null</span>

<div class="details">
<p>Compiled config file</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_config.php#L52" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_config.php at line 52</a>

<h3 id="compiled_filepath">compiled_filepath</h3>
<span class='k'></span> <span class='nx'>string</span><span class='no'> $compiled_filepath</span><span class='o'> = null</span>

<div class="details">
<p>filepath of compiled config file</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_config.php#L58" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_config.php at line 58</a>

<h3 id="compiled_timestamp">compiled_timestamp</h3>
<span class='k'></span> <span class='nx'>int</span><span class='no'> $compiled_timestamp</span><span class='o'> = null</span>

<div class="details">
<p>Filemtime of compiled config Filemtime</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_config.php#L69" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_config.php at line 69</a>

<h3 id="compiler_object">compiler_object</h3>
<span class='k'></span> <span class='nx'>Smarty_Internal_Config_File_Compiler object</span><span class='no'> $compiler_object</span><span class='o'> = null</span>

<div class="details">
<p>Config file compiler object</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_config.php#L40" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_config.php at line 40</a>

<h3 id="config_resource">config_resource</h3>
<span class='k'></span> <span class='nx'>string</span><span class='no'> $config_resource</span><span class='o'> = null</span>

<div class="details">
<p>Config resource</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_config.php#L35" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_config.php at line 35</a>

<h3 id="data">data</h3>
<span class='k'></span> <span class='nx'>object</span><span class='no'> $data</span><span class='o'> = null</span>

<div class="details">
<p>Object of config var storage</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_config.php#L63" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_config.php at line 63</a>

<h3 id="mustCompile">mustCompile</h3>
<span class='k'></span> <span class='nx'>bool</span><span class='no'> $mustCompile</span><span class='o'> = null</span>

<div class="details">
<p>flag if compiled config file is invalid and must be (re)compiled</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_config.php#L29" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_config.php at line 29</a>

<h3 id="smarty">smarty</h3>
<span class='k'></span> <span class='nx'>Smarty object</span><span class='no'> $smarty</span><span class='o'> = null</span>

<div class="details">
<p>Samrty instance</p>
</div>

- - -

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_config.php#L78" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_config.php at line 78</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (string config_resource, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md">Smarty</a> smarty, object data)

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

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_config.php#L90" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_config.php at line 90</a>

<h3 id="getCompiledFilepath()">getCompiledFilepath</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getCompiledFilepath</span> ()

<div class="details">
<p>Returns the compiled  filepath</p><dl>
<dt>Returns:</dt>
<dd>the compiled filepath</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_config.php#L102" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_config.php at line 102</a>

<h3 id="buildCompiledFilepath()">buildCompiledFilepath</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>buildCompiledFilepath</span> ()

<div class="details">
<p>Get file path.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_config.php#L128" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_config.php at line 128</a>

<h3 id="getCompiledTimestamp()">getCompiledTimestamp</h3>
<span class='k'></span> <span class='nx'>integer</span> <span class='nf'>getCompiledTimestamp</span> ()

<div class="details">
<p>Returns the timpestamp of the compiled file</p><dl>
<dt>Returns:</dt>
<dd>the file timestamp</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_config.php#L142" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_config.php at line 142</a>

<h3 id="mustCompile()">mustCompile</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>mustCompile</span> ()

<div class="details">
<p>Returns if the current config file must be compiled</p><p>It does compare the timestamps of config source and the compiled config and checks the force compile configuration</p><dl>
<dt>Returns:</dt>
<dd>true if the file must be compiled</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_config.php#L156" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_config.php at line 156</a>

<h3 id="getCompiledConfig()">getCompiledConfig</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getCompiledConfig</span> ()

<div class="details">
<p>Returns the compiled config file</p><p>It checks if the config file must be compiled or just read the compiled version</p><dl>
<dt>Returns:</dt>
<dd>the compiled config file</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_config.php#L174" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_config.php at line 174</a>

<h3 id="compileConfigSource()">compileConfigSource</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>compileConfigSource</span> ()

<div class="details">
<p>Compiles the config files</p><dl>
<dt>Throws:</dt>
<dd>Exception</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_config.php#L208" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_config.php at line 208</a>

<h3 id="loadConfigVars()">loadConfigVars</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>loadConfigVars</span> (mixed sections, object scope)

<div class="details">
<p>load config variables</p><dl>
<dt>Parameters:</dt>
<dd>sections - array of section names, single section or null</dd>
<dd>scope - global,parent or local</dd>
</dl>

</div>

- - -

