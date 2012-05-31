- - -

**Smarty\Smarty_Data**
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_internal_data.php.md#line426" class="location">framework\libs\smarty\sysplugins\smarty_internal_data.php at line 426</a>

# Class Smarty_Data #

<pre class="tree"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html">Smarty_Internal_Data</a>\n    *** Smarty_Data **\n</pre>

- - -

<p class="signature">public  class **Smarty_Data**\nextends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html">Smarty_Internal_Data</a>

</p>

<div class="comment" id="overview_description"><p>class for the Smarty data object</p><p>The Smarty data object will hold Smarty variables in the current scope</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>Template</dd>
</dl>
- - -

<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td class="type"> <a href="../smarty/smarty.html">Smarty</a></td>
<td class="description"><p class="name"><a href="#smarty">$smarty</a></p><p class="description">Smarty object</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Fields inherited from Smarty\Smarty_Internal_Data</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#config_vars">config_vars</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#parent">parent</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#template_class">template_class</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#tpl_vars">tpl_vars</a></td></tr></table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct()">__construct</a>(Smarty|array _parent, <a href="../smarty/smarty.html">Smarty</a> smarty)</p><p class="description">create Smarty data object</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_Internal_Data</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#append()">append</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#appendByRef()">appendByRef</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#assign()">assign</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#assignByRef()">assignByRef</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#assignGlobal()">assignGlobal</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#clearAllAssign()">clearAllAssign</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#clearAssign()">clearAssign</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#clearConfig()">clearConfig</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#configLoad()">configLoad</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#getConfigVariable()">getConfigVariable</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#getConfigVars()">getConfigVars</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#getStreamVariable()">getStreamVariable</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#getTemplateVars()">getTemplateVars</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#getVariable()">getVariable</a></td></tr></table>

##Field Detail##
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_internal_data.php.md#line433" class="location">framework\libs\smarty\sysplugins\smarty_internal_data.php at line 433</a>

<h3 id="smarty">smarty</h3>
```php
public  <a href="../smarty/smarty.html">Smarty</a> **$smarty** = null```
<div class="details">
<p>Smarty object</p></div>

- - -

<h2 id="detail_method">Constructor Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_internal_data.php.md#line441" class="location">framework\libs\smarty\sysplugins\smarty_internal_data.php at line 441</a>

<h3 id="__construct()">__construct</h3>
```php
public  void **__construct**(Smarty|array _parent, <a href="../smarty/smarty.html">Smarty</a> smarty)```
<div class="details">
<p>create Smarty data object</p><dl>
<dt>Parameters:</dt>
<dd>_parent - parent template</dd>
<dd>smarty - global smarty instance</dd>
</dl>
</div>

- - -

