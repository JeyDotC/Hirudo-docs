

- - -

**Smarty\Smarty_Internal_Compile_Config_Load**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_compile_config_load.php#L18" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_compile_config_load.php at line 18</a>

#Class Smarty_Internal_Compile_Config_Load#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_CompileBase.md">Smarty_Internal_CompileBase</a>
 &gt; **Smarty_Internal_Compile_Config_Load**




- - -

<p><strong>public  class</strong> <span>Smarty_Internal_Compile_Config_Load</span>
<strong>extends</strong> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_CompileBase.md">Smarty_Internal_CompileBase</a>

</p>

<div class="comment" id="overview_description"><p>Smarty Internal Plugin Compile Config Load Class</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>Compiler</dd>
</dl>


<hr />



<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Compile_Config_Load.md#optional_attributes"> $optional_attributes</a>
                                </p><p class="description">Attribute definition: Overwrites base class.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Compile_Config_Load.md#required_attributes"> $required_attributes</a>
                                </p><p class="description">Attribute definition: Overwrites base class.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Compile_Config_Load.md#shorttag_order"> $shorttag_order</a>
                                </p><p class="description">Attribute definition: Overwrites base class.</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Fields inherited from Smarty\Smarty_Internal_CompileBase</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_CompileBase.md#option_flags">option_flags</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_CompileBase.md#optional_attributes">optional_attributes</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_CompileBase.md#required_attributes">required_attributes</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_CompileBase.md#shorttag_order">shorttag_order</a></td></tr></table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#compile">compile</a>(array args, object compiler)</p><p class="description">Compiles code for the {config_load} tag</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_Internal_CompileBase</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_CompileBase.md#closetag">closeTag</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_CompileBase.md#getattributes">getAttributes</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_CompileBase.md#opentag">openTag</a></td></tr></table>

##Field Detail##

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_compile_config_load.php#L40" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_compile_config_load.php at line 40</a>

<h3 id="optional_attributes">optional_attributes</h3>
<span class='k'></span> <span class='nx'>array</span><span class='no'> $optional_attributes</span><span class='o'> = array('section', 'scope')</span>

<div class="details">
<p>Attribute definition: Overwrites base class.</p><dl>
<dt>See Also:</dt>
<dd><a href="../smarty/smarty_internal_compilebase.html">Smarty_Internal_CompileBase</a></dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_compile_config_load.php#L26" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_compile_config_load.php at line 26</a>

<h3 id="required_attributes">required_attributes</h3>
<span class='k'></span> <span class='nx'>array</span><span class='no'> $required_attributes</span><span class='o'> = array('file')</span>

<div class="details">
<p>Attribute definition: Overwrites base class.</p><dl>
<dt>See Also:</dt>
<dd><a href="../smarty/smarty_internal_compilebase.html">Smarty_Internal_CompileBase</a></dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_compile_config_load.php#L33" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_compile_config_load.php at line 33</a>

<h3 id="shorttag_order">shorttag_order</h3>
<span class='k'></span> <span class='nx'>array</span><span class='no'> $shorttag_order</span><span class='o'> = array('file','section')</span>

<div class="details">
<p>Attribute definition: Overwrites base class.</p><dl>
<dt>See Also:</dt>
<dd><a href="../smarty/smarty_internal_compilebase.html">Smarty_Internal_CompileBase</a></dd>
</dl>

</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_compile_config_load.php#L49" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_compile_config_load.php at line 49</a>

<h3 id="compile()">compile</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>compile</span> (array args, object compiler)

<div class="details">
<p>Compiles code for the {config_load} tag</p><dl>
<dt>Parameters:</dt>
<dd>args - array with attributes from parser</dd>
<dd>compiler - compiler object</dd>
<dt>Returns:</dt>
<dd>compiled code</dd>
</dl>

</div>

- - -

