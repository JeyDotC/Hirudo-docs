

- - -

**Smarty\Smarty_Internal_Compile_Nocacheclose**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_compile_nocache.php#L50" >framework\libs\smarty\sysplugins\smarty_internal_compile_nocache.php at line 50</a>

#Class Smarty_Internal_Compile_Nocacheclose#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.html">Smarty_Internal_CompileBase</a>
    * **Smarty_Internal_Compile_Nocacheclose**




- - -

<p class="signature"><span class='k'>public  class</span> <span class='nx'>Smarty_Internal_Compile_Nocacheclose</span>
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.html">Smarty_Internal_CompileBase</a>

</p>

<div class="comment" id="overview_description"><p>Smarty Internal Plugin Compile Nocacheclose Class</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>Compiler</dd>
</dl>


- - -

<table class="inherit">
<tr><th colspan="2">Fields inherited from Smarty\Smarty_Internal_CompileBase</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.html#option_flags">option_flags</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.html#optional_attributes">optional_attributes</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.html#required_attributes">required_attributes</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.html#shorttag_order">shorttag_order</a></td></tr></table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>bool</span></td>
<td class="description"><p class="name"><a href="#compile">compile</a>(array args, object compiler)</p><p class="description">Compiles code for the {/nocache} tagThis tag does not generate compiled output. </p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_Internal_CompileBase</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.html#closeTag()">closeTag</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.html#getAttributes()">getAttributes</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.html#openTag()">openTag</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_compile_nocache.php#L61" >framework\libs\smarty\sysplugins\smarty_internal_compile_nocache.php at line 61</a>

<h3 id="compile()">compile</h3>
<span class='k'></span> <span class='nx'>bool</span> <span class='nf'>compile</span> (array args, object compiler)

<div class="details">
<p>Compiles code for the {/nocache} tag</p><p>This tag does not generate compiled output. It only sets a compiler flag.</p><dl>
<dt>Parameters:</dt>
<dd>args - array with attributes from parser</dd>
<dd>compiler - compiler object</dd>
</dl>

</div>

- - -

