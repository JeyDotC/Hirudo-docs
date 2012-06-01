

- - -

**Smarty\Smarty_Data**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_data.php#L426" >framework\libs\smarty\sysplugins\smarty_internal_data.php at line 426</a>

#Class Smarty_Data#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.md">Smarty_Internal_Data</a>
    * **Smarty_Data**




- - -

<p class="signature"><span class='k'>public  class</span> <span class='nx'>Smarty_Data</span>
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.md">Smarty_Internal_Data</a>

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
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html'>Smarty</a></span></td>
<td class="description"><p class="name" ><a href="#smarty"> $smarty</a>
                                </p><p class="description">Smarty object</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Fields inherited from Smarty\Smarty_Internal_Data</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.md">config_vars</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.md">parent</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.md">template_class</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.md">tpl_vars</a></td></tr></table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(Smarty|array _parent, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty.md">Smarty</a> smarty)</p><p class="description">create Smarty data object</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_Internal_Data</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.md">append</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.md">appendByRef</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.md">assign</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.md">assignByRef</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.md">assignGlobal</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.md">clearAllAssign</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.md">clearAssign</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.md">clearConfig</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.md">configLoad</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.md">getConfigVariable</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.md">getConfigVars</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.md">getStreamVariable</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.md">getTemplateVars</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.md">getVariable</a></td></tr></table>

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_data.php#L441" >framework\libs\smarty\sysplugins\smarty_internal_data.php at line 441</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (Smarty|array _parent, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty.md">Smarty</a> smarty)

<div class="details">
<p>create Smarty data object</p><dl>
<dt>Parameters:</dt>
<dd>_parent - parent template</dd>
<dd>smarty - global smarty instance</dd>
</dl>

</div>

- - -

