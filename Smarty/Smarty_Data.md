

- - -

**Smarty\Smarty_Data**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_data.php#L426" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_data.php at line 426</a>

#Class Smarty_Data#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md">Smarty_Internal_Data</a>
 &gt; **Smarty_Data**




- - -

<p><strong>public  class</strong> <span>Smarty_Data</span>
<strong>extends</strong> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md">Smarty_Internal_Data</a>

</p>

<div class="comment" id="overview_description"><p>class for the Smarty data object</p><p>The Smarty data object will hold Smarty variables in the current scope</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>Template</dd>
</dl>


<hr />



<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Data.md#smarty'>Smarty</a></span></td>
<td class="description"><p class="name" ><a href="smarty"> $smarty</a>
                                </p><p class="description">Smarty object</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Fields inherited from Smarty\Smarty_Internal_Data</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#config_vars">config_vars</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#parent">parent</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#template_class">template_class</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#tpl_vars">tpl_vars</a></td></tr></table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(Smarty|array _parent, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md">Smarty</a> smarty)</p><p class="description">create Smarty data object</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_Internal_Data</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#append">append</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#appendbyref">appendByRef</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#assign">assign</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#assignbyref">assignByRef</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#assignglobal">assignGlobal</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#clearallassign">clearAllAssign</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#clearassign">clearAssign</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#clearconfig">clearConfig</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#configload">configLoad</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#getconfigvariable">getConfigVariable</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#getconfigvars">getConfigVars</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#getstreamvariable">getStreamVariable</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#gettemplatevars">getTemplateVars</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#getvariable">getVariable</a></td></tr></table>

##Field Detail##

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_data.php#L433" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_data.php at line 433</a>

<h3 id="smarty">smarty</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Data.md#smarty'>Smarty</a></span><span class='no'> $smarty</span><span class='o'> = null</span>

<div class="details">
<p>Smarty object</p>
</div>

- - -

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_data.php#L441" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_data.php at line 441</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (Smarty|array _parent, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md">Smarty</a> smarty)

<div class="details">
<p>create Smarty data object</p><dl>
<dt>Parameters:</dt>
<dd>_parent - parent template</dd>
<dd>smarty - global smarty instance</dd>
</dl>

</div>

- - -

