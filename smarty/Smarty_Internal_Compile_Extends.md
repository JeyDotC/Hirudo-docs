

- - -

**Smarty\Smarty_Internal_Compile_Extends**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_compile_extends.php#L19" >framework\libs\smarty\sysplugins\smarty_internal_compile_extends.php at line 19</a>

#Class Smarty_Internal_Compile_Extends#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.md">Smarty_Internal_CompileBase</a>
    * **Smarty_Internal_Compile_Extends**




- - -

<p class="signature"><span class='k'>public  class</span> <span class='nx'>Smarty_Internal_Compile_Extends</span>
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.md">Smarty_Internal_CompileBase</a>

</p>

<div class="comment" id="overview_description"><p>Smarty Internal Plugin Compile extend Class</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>Compiler</dd>
</dl>


- - -



<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>int</span></td>
<td class="description"><p class="name" ><a href="#mbstring_overload"> $mbstring_overload</a>
                                </p><p class="description">mbstring.overload flag</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#required_attributes"> $required_attributes</a>
                                </p><p class="description">Attribute definition: Overwrites base class.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#shorttag_order"> $shorttag_order</a>
                                </p><p class="description">Attribute definition: Overwrites base class.</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Fields inherited from Smarty\Smarty_Internal_CompileBase</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.md">option_flags</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.md">optional_attributes</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.md">required_attributes</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.md">shorttag_order</a></td></tr></table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#compile">compile</a>(array args, object compiler)</p><p class="description">Compiles code for the {extends} tag</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_Internal_CompileBase</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.md">closeTag</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.md">getAttributes</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.md">openTag</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_compile_extends.php#L49" >framework\libs\smarty\sysplugins\smarty_internal_compile_extends.php at line 49</a>

<h3 id="compile()">compile</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>compile</span> (array args, object compiler)

<div class="details">
<p>Compiles code for the {extends} tag</p><dl>
<dt>Parameters:</dt>
<dd>args - array with attributes from parser</dd>
<dd>compiler - compiler object</dd>
<dt>Returns:</dt>
<dd>compiled code</dd>
</dl>

</div>

- - -

