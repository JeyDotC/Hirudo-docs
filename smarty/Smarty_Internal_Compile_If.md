- - -

**Smarty\Smarty_Internal_Compile_If**
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_compile_if.php at line 18</div>
#Class Smarty_Internal_Compile_If#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.html">Smarty_Internal_CompileBase</a>
    ***Smarty_Internal_Compile_If**


- - -

<p class="signature">public  class **Smarty_Internal_Compile_If**
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.html">Smarty_Internal_CompileBase</a>

</p>

<div class="comment" id="overview_description"><p>Smarty Internal Plugin Compile If Class</p></div>

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
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#compile">compile</a>(array args, object compiler, array parameter)</p><p class="description">Compiles code for the {if} tag</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_Internal_CompileBase</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.html#closeTag()">closeTag</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.html#getAttributes()">getAttributes</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.html#openTag()">openTag</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_compile_if.php at line 28</div>
<h3 id="compile()">compile</h3>
```php
public  string **compile**(array args, object compiler, array parameter)```
<div class="details">
<p>Compiles code for the {if} tag</p><dl>
<dt>Parameters:</dt>
<dd>args - array with attributes from parser</dd>
<dd>compiler - compiler object</dd>
<dd>parameter - array with compilation parameter</dd>
<dt>Returns:</dt>
<dd>compiled code</dd>
</dl>
</div>

- - -
