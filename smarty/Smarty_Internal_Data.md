- - -

**Smarty\Smarty_Internal_Data**
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_data.php at line 18</div>
#Class Smarty_Internal_Data#

**Smarty_Internal_Data**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_data.html">Smarty_Data</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_debug.html">Smarty_Internal_Debug</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatebase.html">Smarty_Internal_TemplateBase</a> </dd>
</dl>

- - -

<p class="signature">public  class **Smarty_Internal_Data**</p>

<div class="comment" id="overview_description"><p>Base class with template and variable methodes</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>Template</dd>
</dl>
- - -

<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#config_vars">$config_vars</a></p><p class="description">configuration settings</p></td>
</tr>
<tr>
<td class="type"> <a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a></td>
<td class="description"><p class="name"><a href="#parent">$parent</a></p><p class="description">parent template (if any)</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#template_class">$template_class</a></p><p class="description">name of class used for templates</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#tpl_vars">$tpl_vars</a></p><p class="description">template variables</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> <a href="../smarty/smarty_internal_data.html">Smarty_Internal_Data</a></td>
<td class="description"><p class="name"><a href="#assign">assign</a>(array|string tpl_var, mixed value, boolean nocache, boolean scope)</p><p class="description">assigns a Smarty variable</p></td>
</tr>
<tr>
<td class="type"> <a href="../smarty/smarty_internal_data.html">Smarty_Internal_Data</a></td>
<td class="description"><p class="name"><a href="#assignGlobal">assignGlobal</a>(string varname, mixed value, boolean nocache)</p><p class="description">assigns a global Smarty variable</p></td>
</tr>
<tr>
<td class="type"> <a href="../smarty/smarty_internal_data.html">Smarty_Internal_Data</a></td>
<td class="description"><p class="name"><a href="#assignByRef">assignByRef</a>(string tpl_var, boolean nocache, mixed value)</p><p class="description">assigns values to template variables by reference</p></td>
</tr>
<tr>
<td class="type"> <a href="../smarty/smarty_internal_data.html">Smarty_Internal_Data</a></td>
<td class="description"><p class="name"><a href="#append">append</a>(array|string tpl_var, mixed value, boolean merge, boolean nocache)</p><p class="description">appends values to template variables</p></td>
</tr>
<tr>
<td class="type"> <a href="../smarty/smarty_internal_data.html">Smarty_Internal_Data</a></td>
<td class="description"><p class="name"><a href="#appendByRef">appendByRef</a>(string tpl_var, mixed &$value, boolean merge, mixed value)</p><p class="description">appends values to template variables by reference</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#getTemplateVars">getTemplateVars</a>(string varname, string _ptr, boolean search_parents)</p><p class="description">Returns a single or all template variables</p></td>
</tr>
<tr>
<td class="type"> <a href="../smarty/smarty_internal_data.html">Smarty_Internal_Data</a></td>
<td class="description"><p class="name"><a href="#clearAssign">clearAssign</a>(string|array tpl_var)</p><p class="description">clear the given assigned template variable.</p></td>
</tr>
<tr>
<td class="type"> <a href="../smarty/smarty_internal_data.html">Smarty_Internal_Data</a></td>
<td class="description"><p class="name"><a href="#clearAllAssign">clearAllAssign</a>()</p><p class="description">clear all the assigned template variables.</p></td>
</tr>
<tr>
<td class="type"> <a href="../smarty/smarty_internal_data.html">Smarty_Internal_Data</a></td>
<td class="description"><p class="name"><a href="#configLoad">configLoad</a>(string config_file, mixed sections)</p><p class="description">load a config file, optionally load just selected sections</p></td>
</tr>
<tr>
<td class="type"> object</td>
<td class="description"><p class="name"><a href="#getVariable">getVariable</a>(string variable, object _ptr, boolean search_parents, bool error_enable)</p><p class="description">gets the object of a Smarty variable</p></td>
</tr>
<tr>
<td class="type"> mixed</td>
<td class="description"><p class="name"><a href="#getConfigVariable">getConfigVariable</a>(string variable, bool error_enable)</p><p class="description">gets  a config variable</p></td>
</tr>
<tr>
<td class="type"> mixed</td>
<td class="description"><p class="name"><a href="#getStreamVariable">getStreamVariable</a>(string variable)</p><p class="description">gets  a stream variable</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#getConfigVars">getConfigVars</a>(string varname, bool search_parents)</p><p class="description">Returns a single or all config variables</p></td>
</tr>
<tr>
<td class="type"> <a href="../smarty/smarty_internal_data.html">Smarty_Internal_Data</a></td>
<td class="description"><p class="name"><a href="#clearConfig">clearConfig</a>(string varname)</p><p class="description">Deassigns a single or all config variables</p></td>
</tr>
</table>

##Field Detail##
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_data.php at line 43</div>
<h3 id="config_vars">config_vars</h3>
```php
public  array **$config_vars** = array()```
<div class="details">
<p>configuration settings</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_data.php at line 37</div>
<h3 id="parent">parent</h3>
```php
public  <a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> **$parent** = null```
<div class="details">
<p>parent template (if any)</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_data.php at line 25</div>
<h3 id="template_class">template_class</h3>
```php
public  string **$template_class** = 'Smarty_Internal_Template'```
<div class="details">
<p>name of class used for templates</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_data.php at line 31</div>
<h3 id="tpl_vars">tpl_vars</h3>
```php
public  array **$tpl_vars** = array()```
<div class="details">
<p>template variables</p></div>

- - -

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_data.php at line 54</div>
<h3 id="assign()">assign</h3>
```php
public  <a href="../smarty/smarty_internal_data.html">Smarty_Internal_Data</a> **assign**(array|string tpl_var, mixed value, boolean nocache, boolean scope)```
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

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_data.php at line 79</div>
<h3 id="assignGlobal()">assignGlobal</h3>
```php
public  <a href="../smarty/smarty_internal_data.html">Smarty_Internal_Data</a> **assignGlobal**(string varname, mixed value, boolean nocache)```
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

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_data.php at line 95</div>
<h3 id="assignByRef()">assignByRef</h3>
```php
public  <a href="../smarty/smarty_internal_data.html">Smarty_Internal_Data</a> **assignByRef**(string tpl_var, boolean nocache, mixed value)```
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

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_data.php at line 114</div>
<h3 id="append()">append</h3>
```php
public  <a href="../smarty/smarty_internal_data.html">Smarty_Internal_Data</a> **append**(array|string tpl_var, mixed value, boolean merge, boolean nocache)```
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

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_data.php at line 174</div>
<h3 id="appendByRef()">appendByRef</h3>
```php
public  <a href="../smarty/smarty_internal_data.html">Smarty_Internal_Data</a> **appendByRef**(string tpl_var, mixed &$value, boolean merge, mixed value)```
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

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_data.php at line 203</div>
<h3 id="getTemplateVars()">getTemplateVars</h3>
```php
public  string **getTemplateVars**(string varname, string _ptr, boolean search_parents)```
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

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_data.php at line 246</div>
<h3 id="clearAssign()">clearAssign</h3>
```php
public  <a href="../smarty/smarty_internal_data.html">Smarty_Internal_Data</a> **clearAssign**(string|array tpl_var)```
<div class="details">
<p>clear the given assigned template variable.</p><dl>
<dt>Parameters:</dt>
<dd>tpl_var - the template variable(s) to clear</dd>
<dt>Returns:</dt>
<dd>current Smarty_Internal_Data (or Smarty or Smarty_Internal_Template) instance for chaining</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_data.php at line 263</div>
<h3 id="clearAllAssign()">clearAllAssign</h3>
```php
public  <a href="../smarty/smarty_internal_data.html">Smarty_Internal_Data</a> **clearAllAssign**()```
<div class="details">
<p>clear all the assigned template variables.</p><dl>
<dt>Returns:</dt>
<dd>current Smarty_Internal_Data (or Smarty or Smarty_Internal_Template) instance for chaining</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_data.php at line 276</div>
<h3 id="configLoad()">configLoad</h3>
```php
public  <a href="../smarty/smarty_internal_data.html">Smarty_Internal_Data</a> **configLoad**(string config_file, mixed sections)```
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

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_data.php at line 292</div>
<h3 id="getVariable()">getVariable</h3>
```php
public  object **getVariable**(string variable, object _ptr, boolean search_parents, bool error_enable)```
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

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_data.php at line 325</div>
<h3 id="getConfigVariable()">getConfigVariable</h3>
```php
public  mixed **getConfigVariable**(string variable, bool error_enable)```
<div class="details">
<p>gets  a config variable</p><dl>
<dt>Parameters:</dt>
<dd>variable - the name of the config variable</dd>
<dt>Returns:</dt>
<dd>the value of the config variable</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_data.php at line 349</div>
<h3 id="getStreamVariable()">getStreamVariable</h3>
```php
public  mixed **getStreamVariable**(string variable)```
<div class="details">
<p>gets  a stream variable</p><dl>
<dt>Parameters:</dt>
<dd>variable - the stream of the variable</dd>
<dt>Returns:</dt>
<dd>the value of the stream variable</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_data.php at line 374</div>
<h3 id="getConfigVars()">getConfigVars</h3>
```php
public  string **getConfigVars**(string varname, bool search_parents)```
<div class="details">
<p>Returns a single or all config variables</p><dl>
<dt>Parameters:</dt>
<dd>varname - variable name or null</dd>
<dt>Returns:</dt>
<dd>variable value or or array of variables</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_data.php at line 406</div>
<h3 id="clearConfig()">clearConfig</h3>
```php
public  <a href="../smarty/smarty_internal_data.html">Smarty_Internal_Data</a> **clearConfig**(string varname)```
<div class="details">
<p>Deassigns a single or all config variables</p><dl>
<dt>Parameters:</dt>
<dd>varname - variable name or null</dd>
<dt>Returns:</dt>
<dd>current Smarty_Internal_Data (or Smarty or Smarty_Internal_Template) instance for chaining</dd>
</dl>
</div>

- - -

