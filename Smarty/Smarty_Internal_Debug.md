

- - -

**Smarty\Smarty_Internal_Debug**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_debug.php#L18" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_debug.php at line 18</a>

#Class Smarty_Internal_Debug#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md">Smarty_Internal_Data</a>
 &gt; **Smarty_Internal_Debug**




- - -

<p><strong>public  class</strong> <span>Smarty_Internal_Debug</span>
<strong>extends</strong> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md">Smarty_Internal_Data</a>

</p>

<div class="comment" id="overview_description"><p>Smarty Internal Plugin Debug Class</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>Debug</dd>
</dl>


<hr />



<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="template_data"> $template_data</a>
                                </p><p class="description">template data</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Fields inherited from Smarty\Smarty_Internal_Data</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#config_vars">config_vars</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#parent">parent</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#template_class">template_class</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#tpl_vars">tpl_vars</a></td></tr></table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#start_compile">start_compile</a>(object template)</p><p class="description">Start logging of compile time</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#end_compile">end_compile</a>(object template)</p><p class="description">End logging of compile time</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#start_render">start_render</a>(object template)</p><p class="description">Start logging of render time</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#end_render">end_render</a>(object template)</p><p class="description">End logging of compile time</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#start_cache">start_cache</a>(object template)</p><p class="description">Start logging of cache time</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#end_cache">end_cache</a>(object template)</p><p class="description">End logging of cache time</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#display_debug">display_debug</a>(Smarty_Internal_Template|Smarty obj)</p><p class="description">Opens a window for the Smarty Debugging Consol and display the data</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>StdClass</span></td>
<td class="description"><p class="name"><a href="#get_debug_vars">get_debug_vars</a>(Smarty_Internal_Template|Smarty_Data obj)</p><p class="description">Recursively gets variables from all template/data scopes</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_Internal_Data</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#append">append</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#appendbyref">appendByRef</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#assign">assign</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#assignbyref">assignByRef</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#assignglobal">assignGlobal</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#clearallassign">clearAllAssign</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#clearassign">clearAssign</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#clearconfig">clearConfig</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#configload">configLoad</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#getconfigvariable">getConfigVariable</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#getconfigvars">getConfigVars</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#getstreamvariable">getStreamVariable</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#gettemplatevars">getTemplateVars</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Data.md#getvariable">getVariable</a></td></tr></table>

##Field Detail##

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_debug.php#L25" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_debug.php at line 25</a>

<h3 id="template_data">template_data</h3>
<span class='k'>static </span> <span class='nx'>array</span><span class='no'> $template_data</span><span class='o'> = array()</span>

<div class="details">
<p>template data</p>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_debug.php#L32" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_debug.php at line 32</a>

<h3 id="start_compile()">start_compile</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>start_compile</span> (object template)

<div class="details">
<p>Start logging of compile time</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_debug.php#L43" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_debug.php at line 43</a>

<h3 id="end_compile()">end_compile</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>end_compile</span> (object template)

<div class="details">
<p>End logging of compile time</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_debug.php#L54" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_debug.php at line 54</a>

<h3 id="start_render()">start_render</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>start_render</span> (object template)

<div class="details">
<p>Start logging of render time</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_debug.php#L65" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_debug.php at line 65</a>

<h3 id="end_render()">end_render</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>end_render</span> (object template)

<div class="details">
<p>End logging of compile time</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_debug.php#L76" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_debug.php at line 76</a>

<h3 id="start_cache()">start_cache</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>start_cache</span> (object template)

<div class="details">
<p>Start logging of cache time</p><dl>
<dt>Parameters:</dt>
<dd>template - cached template</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_debug.php#L87" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_debug.php at line 87</a>

<h3 id="end_cache()">end_cache</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>end_cache</span> (object template)

<div class="details">
<p>End logging of cache time</p><dl>
<dt>Parameters:</dt>
<dd>template - cached template</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_debug.php#L98" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_debug.php at line 98</a>

<h3 id="display_debug()">display_debug</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>display_debug</span> (Smarty_Internal_Template|Smarty obj)

<div class="details">
<p>Opens a window for the Smarty Debugging Consol and display the data</p><dl>
<dt>Parameters:</dt>
<dd>obj - object to debug</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_debug.php#L144" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_debug.php at line 144</a>

<h3 id="get_debug_vars()">get_debug_vars</h3>
<span class='k'>static </span> <span class='nx'>StdClass</span> <span class='nf'>get_debug_vars</span> (Smarty_Internal_Template|Smarty_Data obj)

<div class="details">
<p>Recursively gets variables from all template/data scopes</p><dl>
<dt>Parameters:</dt>
<dd>obj - object to debug</dd>
</dl>

</div>

- - -

