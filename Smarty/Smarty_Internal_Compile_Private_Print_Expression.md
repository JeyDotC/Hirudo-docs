

- - -

**Smarty\Smarty_Internal_Compile_Private_Print_Expression**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_compile_private_print_expression.php#L18" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_compile_private_print_expression.php at line 18</a>

#Class Smarty_Internal_Compile_Private_Print_Expression#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_CompileBase.md">Smarty_Internal_CompileBase</a>
 &gt; **Smarty_Internal_Compile_Private_Print_Expression**




- - -

<p><strong>public  class</strong> <span>Smarty_Internal_Compile_Private_Print_Expression</span>
<strong>extends</strong> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_CompileBase.md">Smarty_Internal_CompileBase</a>

</p>

<div class="comment" id="overview_description"><p>Smarty Internal Plugin Compile Print Expression Class</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>Compiler</dd>
</dl>


<hr />



<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="option_flags"> $option_flags</a>
                                </p><p class="description">Attribute definition: Overwrites base class.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="optional_attributes"> $optional_attributes</a>
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
<td class="description"><p class="name"><a href="#compile">compile</a>(array args, object compiler, array parameter)</p><p class="description">Compiles code for gererting output from any expression</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_Internal_CompileBase</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_CompileBase.md#closetag">closeTag</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_CompileBase.md#getattributes">getAttributes</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_CompileBase.md#opentag">openTag</a></td></tr></table>

##Field Detail##

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_compile_private_print_expression.php#L33" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_compile_private_print_expression.php at line 33</a>

<h3 id="option_flags">option_flags</h3>
<span class='k'></span> <span class='nx'>array</span><span class='no'> $option_flags</span><span class='o'> = array('nocache', 'nofilter')</span>

<div class="details">
<p>Attribute definition: Overwrites base class.</p><dl>
<dt>See Also:</dt>
<dd><a href="../smarty/smarty_internal_compilebase.html">Smarty_Internal_CompileBase</a></dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_compile_private_print_expression.php#L26" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_compile_private_print_expression.php at line 26</a>

<h3 id="optional_attributes">optional_attributes</h3>
<span class='k'></span> <span class='nx'>array</span><span class='no'> $optional_attributes</span><span class='o'> = array('assign')</span>

<div class="details">
<p>Attribute definition: Overwrites base class.</p><dl>
<dt>See Also:</dt>
<dd><a href="../smarty/smarty_internal_compilebase.html">Smarty_Internal_CompileBase</a></dd>
</dl>

</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_compile_private_print_expression.php#L43" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_compile_private_print_expression.php at line 43</a>

<h3 id="compile()">compile</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>compile</span> (array args, object compiler, array parameter)

<div class="details">
<p>Compiles code for gererting output from any expression</p><dl>
<dt>Parameters:</dt>
<dd>args - array with attributes from parser</dd>
<dd>compiler - compiler object</dd>
<dd>parameter - array with compilation parameter</dd>
<dt>Returns:</dt>
<dd>compiled code</dd>
</dl>

</div>

- - -

