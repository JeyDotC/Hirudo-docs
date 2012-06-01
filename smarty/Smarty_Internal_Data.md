

- - -

**Smarty\Smarty_Internal_Data**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_data.php#L18" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_data.php at line 18</a>

#Class Smarty_Internal_Data#

**Smarty_Internal_Data**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty_Data.md">Smarty_Data</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty_Internal_Debug.md">Smarty_Internal_Debug</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty_Internal_TemplateBase.md">Smarty_Internal_TemplateBase</a> </dd>
</dl>



- - -

<p><strong>public  class</strong> <span>Smarty_Internal_Data</span></p>

<div class="comment" id="overview_description"><p>Base class with template and variable methodes</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>Template</dd>
</dl>


- - -



<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#config_vars"> $config_vars</a>
                                </p><p class="description">configuration settings</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty_Internal_Template'>Smarty_Internal_Template</a></span></td>
<td class="description"><p class="name" ><a href="#parent"> $parent</a>
                                </p><p class="description">parent template (if any)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name" ><a href="#template_class"> $template_class</a>
                                </p><p class="description">name of class used for templates</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#tpl_vars"> $tpl_vars</a>
                                </p><p class="description">template variables</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty_Internal_Data>Smarty_Internal_Data</a></span></td>
<td class="description"><p class="name"><a href="#assign">assign</a>(array|string tpl_var, mixed value, boolean nocache, boolean scope)</p><p class="description">assigns a Smarty variable</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty_Internal_Data>Smarty_Internal_Data</a></span></td>
<td class="description"><p class="name"><a href="#assignglobal">assignGlobal</a>(string varname, mixed value, boolean nocache)</p><p class="description">assigns a global Smarty variable</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty_Internal_Data>Smarty_Internal_Data</a></span></td>
<td class="description"><p class="name"><a href="#assignbyref">assignByRef</a>(string tpl_var, boolean nocache, mixed value)</p><p class="description">assigns values to template variables by reference</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty_Internal_Data>Smarty_Internal_Data</a></span></td>
<td class="description"><p class="name"><a href="#append">append</a>(array|string tpl_var, mixed value, boolean merge, boolean nocache)</p><p class="description">appends values to template variables</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty_Internal_Data>Smarty_Internal_Data</a></span></td>
<td class="description"><p class="name"><a href="#appendbyref">appendByRef</a>(string tpl_var, mixed &$value, boolean merge, mixed value)</p><p class="description">appends values to template variables by reference</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#gettemplatevars">getTemplateVars</a>(string varname, string _ptr, boolean search_parents)</p><p class="description">Returns a single or all template variables</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty_Internal_Data>Smarty_Internal_Data</a></span></td>
<td class="description"><p class="name"><a href="#clearassign">clearAssign</a>(string|array tpl_var)</p><p class="description">clear the given assigned template variable.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty_Internal_Data>Smarty_Internal_Data</a></span></td>
<td class="description"><p class="name"><a href="#clearallassign">clearAllAssign</a>()</p><p class="description">clear all the assigned template variables.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty_Internal_Data>Smarty_Internal_Data</a></span></td>
<td class="description"><p class="name"><a href="#configload">configLoad</a>(string config_file, mixed sections)</p><p class="description">load a config file, optionally load just selected sections</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>object</span></td>
<td class="description"><p class="name"><a href="#getvariable">getVariable</a>(string variable, object _ptr, boolean search_parents, bool error_enable)</p><p class="description">gets the object of a Smarty variable</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#getconfigvariable">getConfigVariable</a>(string variable, bool error_enable)</p><p class="description">gets  a config variable</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#getstreamvariable">getStreamVariable</a>(string variable)</p><p class="description">gets  a stream variable</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getconfigvars">getConfigVars</a>(string varname, bool search_parents)</p><p class="description">Returns a single or all config variables</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty_Internal_Data>Smarty_Internal_Data</a></span></td>
<td class="description"><p class="name"><a href="#clearconfig">clearConfig</a>(string varname)</p><p class="description">Deassigns a single or all config variables</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_data.php#L54" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_data.php at line 54</a>

<h3 id="assign()">assign</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty_Internal_Data>Smarty_Internal_Data</a></span> <span class='nf'>assign</span> (array|string tpl_var, mixed value, boolean nocache, boolean scope)

<div class="details">
<p>assigns a Smarty variable</p><dl>
<dt>Parameters:</dt>
<dd>tpl_var - the template variable name(s)</dd>
<dd>value - the value to assign</dd>
<dd>nocache - if true any output of this variable will be not cached</dd>
<dd>scope - the scope the variable will have (local,parent or root)</dd>
<dt>Returns:</dt>
<dd>current Smarty_Internal_Data (or Smarty or Smarty_Internal_Template) instance for chaining</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_data.php#L79" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_data.php at line 79</a>

<h3 id="assignGlobal()">assignGlobal</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty_Internal_Data>Smarty_Internal_Data</a></span> <span class='nf'>assignGlobal</span> (string varname, mixed value, boolean nocache)

<div class="details">
<p>assigns a global Smarty variable</p><dl>
<dt>Parameters:</dt>
<dd>varname - the global variable name</dd>
<dd>value - the value to assign</dd>
<dd>nocache - if true any output of this variable will be not cached</dd>
<dt>Returns:</dt>
<dd>current Smarty_Internal_Data (or Smarty or Smarty_Internal_Template) instance for chaining</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_data.php#L95" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_data.php at line 95</a>

<h3 id="assignByRef()">assignByRef</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty_Internal_Data>Smarty_Internal_Data</a></span> <span class='nf'>assignByRef</span> (string tpl_var, boolean nocache, mixed value)

<div class="details">
<p>assigns values to template variables by reference</p><dl>
<dt>Parameters:</dt>
<dd>tpl_var - the template variable name</dd>
<dd> - &$value the referenced value to assign</dd>
<dd>nocache - if true any output of this variable will be not cached</dd>
<dt>Returns:</dt>
<dd>current Smarty_Internal_Data (or Smarty or Smarty_Internal_Template) instance for chaining</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_data.php#L114" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_data.php at line 114</a>

<h3 id="append()">append</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty_Internal_Data>Smarty_Internal_Data</a></span> <span class='nf'>append</span> (array|string tpl_var, mixed value, boolean merge, boolean nocache)

<div class="details">
<p>appends values to template variables</p><dl>
<dt>Parameters:</dt>
<dd>tpl_var - the template variable name(s)</dd>
<dd>value - the value to append</dd>
<dd>merge - flag if array elements shall be merged</dd>
<dd>nocache - if true any output of this variable will be not cached</dd>
<dt>Returns:</dt>
<dd>current Smarty_Internal_Data (or Smarty or Smarty_Internal_Template) instance for chaining</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_data.php#L174" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_data.php at line 174</a>

<h3 id="appendByRef()">appendByRef</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty_Internal_Data>Smarty_Internal_Data</a></span> <span class='nf'>appendByRef</span> (string tpl_var, mixed &$value, boolean merge, mixed value)

<div class="details">
<p>appends values to template variables by reference</p><dl>
<dt>Parameters:</dt>
<dd>tpl_var - the template variable name</dd>
<dd>&$value - the referenced value to append</dd>
<dd>merge - flag if array elements shall be merged</dd>
<dt>Returns:</dt>
<dd>current Smarty_Internal_Data (or Smarty or Smarty_Internal_Template) instance for chaining</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_data.php#L203" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_data.php at line 203</a>

<h3 id="getTemplateVars()">getTemplateVars</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getTemplateVars</span> (string varname, string _ptr, boolean search_parents)

<div class="details">
<p>Returns a single or all template variables</p><dl>
<dt>Parameters:</dt>
<dd>varname - variable name or null</dd>
<dd>_ptr - optional pointer to data object</dd>
<dd>search_parents - include parent templates?</dd>
<dt>Returns:</dt>
<dd>variable value or or array of variables</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_data.php#L246" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_data.php at line 246</a>

<h3 id="clearAssign()">clearAssign</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty_Internal_Data>Smarty_Internal_Data</a></span> <span class='nf'>clearAssign</span> (string|array tpl_var)

<div class="details">
<p>clear the given assigned template variable.</p><dl>
<dt>Parameters:</dt>
<dd>tpl_var - the template variable(s) to clear</dd>
<dt>Returns:</dt>
<dd>current Smarty_Internal_Data (or Smarty or Smarty_Internal_Template) instance for chaining</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_data.php#L263" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_data.php at line 263</a>

<h3 id="clearAllAssign()">clearAllAssign</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty_Internal_Data>Smarty_Internal_Data</a></span> <span class='nf'>clearAllAssign</span> ()

<div class="details">
<p>clear all the assigned template variables.</p><dl>
<dt>Returns:</dt>
<dd>current Smarty_Internal_Data (or Smarty or Smarty_Internal_Template) instance for chaining</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_data.php#L276" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_data.php at line 276</a>

<h3 id="configLoad()">configLoad</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty_Internal_Data>Smarty_Internal_Data</a></span> <span class='nf'>configLoad</span> (string config_file, mixed sections)

<div class="details">
<p>load a config file, optionally load just selected sections</p><dl>
<dt>Parameters:</dt>
<dd>config_file - filename</dd>
<dd>sections - array of section names, single section or null</dd>
<dt>Returns:</dt>
<dd>current Smarty_Internal_Data (or Smarty or Smarty_Internal_Template) instance for chaining</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_data.php#L292" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_data.php at line 292</a>

<h3 id="getVariable()">getVariable</h3>
<span class='k'></span> <span class='nx'>object</span> <span class='nf'>getVariable</span> (string variable, object _ptr, boolean search_parents, bool error_enable)

<div class="details">
<p>gets the object of a Smarty variable</p><dl>
<dt>Parameters:</dt>
<dd>variable - the name of the Smarty variable</dd>
<dd>_ptr - optional pointer to data object</dd>
<dd>search_parents - search also in parent data</dd>
<dt>Returns:</dt>
<dd>the object of the variable</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_data.php#L325" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_data.php at line 325</a>

<h3 id="getConfigVariable()">getConfigVariable</h3>
<span class='k'></span> <span class='nx'>mixed</span> <span class='nf'>getConfigVariable</span> (string variable, bool error_enable)

<div class="details">
<p>gets  a config variable</p><dl>
<dt>Parameters:</dt>
<dd>variable - the name of the config variable</dd>
<dt>Returns:</dt>
<dd>the value of the config variable</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_data.php#L349" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_data.php at line 349</a>

<h3 id="getStreamVariable()">getStreamVariable</h3>
<span class='k'></span> <span class='nx'>mixed</span> <span class='nf'>getStreamVariable</span> (string variable)

<div class="details">
<p>gets  a stream variable</p><dl>
<dt>Parameters:</dt>
<dd>variable - the stream of the variable</dd>
<dt>Returns:</dt>
<dd>the value of the stream variable</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_data.php#L374" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_data.php at line 374</a>

<h3 id="getConfigVars()">getConfigVars</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getConfigVars</span> (string varname, bool search_parents)

<div class="details">
<p>Returns a single or all config variables</p><dl>
<dt>Parameters:</dt>
<dd>varname - variable name or null</dd>
<dt>Returns:</dt>
<dd>variable value or or array of variables</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_data.php#L406" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_data.php at line 406</a>

<h3 id="clearConfig()">clearConfig</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/Smarty_Internal_Data>Smarty_Internal_Data</a></span> <span class='nf'>clearConfig</span> (string varname)

<div class="details">
<p>Deassigns a single or all config variables</p><dl>
<dt>Parameters:</dt>
<dd>varname - variable name or null</dd>
<dt>Returns:</dt>
<dd>current Smarty_Internal_Data (or Smarty or Smarty_Internal_Template) instance for chaining</dd>
</dl>

</div>

- - -

