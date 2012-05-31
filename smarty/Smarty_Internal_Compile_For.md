
- - -

**Smarty\Smarty_Internal_Compile_For**
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_compile_for.php at line 18</div>
#Class Smarty_Internal_Compile_For#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.html">Smarty_Internal_CompileBase</a>
    ***Smarty_Internal_Compile_For**


- - -

<p class="signature">public  class **Smarty_Internal_Compile_For**
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.html">Smarty_Internal_CompileBase</a>

</p>

<div class="comment" id="overview_description"><p>Smarty Internal Plugin Compile For Class</p></div>

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
<td class="type">  string</td>
<td class="description"><p class="name"><a href="#compile">compile</a>(array args, object compiler, array parameter)</p><p class="description">Compiles code for the {for} tagSmarty 3 does implement two different sytaxes:- {for $var in $array}
For looping over arrays or iterators- {for $x=0; $x</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_Internal_CompileBase</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.html#closeTag()">closeTag</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.html#getAttributes()">getAttributes</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.html#openTag()">openTag</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_compile_for.php at line 39</div>
<h3 id="compile()">compile</h3>

public  string **compile** (array args, object compiler, array parameter)<div class="details">
<p>Compiles code for the {for} tag</p><p>Smarty 3 does implement two different sytaxes:</p><p>- {for $var in $array}
For looping over arrays or iterators</p><p>- {for $x=0; $x<$y; $x++}
For general loops</p><p>The parser is gereration different sets of attribute by which this compiler can
determin which syntax is used.</p><dl>
<dt>Parameters:</dt>
<dd>args - array with attributes from parser</dd>
<dd>compiler - compiler object</dd>
<dd>parameter - array with compilation parameter</dd>
<dt>Returns:</dt>
<dd>compiled code</dd>
</dl>
</div>

- - -

