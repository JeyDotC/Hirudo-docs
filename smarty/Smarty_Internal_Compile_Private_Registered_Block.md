- - -

**Smarty\Smarty_Internal_Compile_Private_Registered_Block**
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_internal_compile_private_registered_block.php.md#line18" class="location">framework\libs\smarty\sysplugins\smarty_internal_compile_private_registered_block.php at line 18</a>

# Class Smarty_Internal_Compile_Private_Registered_Block #

<pre class="tree"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.html">Smarty_Internal_CompileBase</a>\n    *** Smarty_Internal_Compile_Private_Registered_Block **\n</pre>

- - -

<p class="signature">public  class **Smarty_Internal_Compile_Private_Registered_Block**\nextends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.html">Smarty_Internal_CompileBase</a>

</p>

<div class="comment" id="overview_description"><p>Smarty Internal Plugin Compile Registered Block Class</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>Compiler</dd>
</dl>
- - -

<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#optional_attributes">$optional_attributes</a></p><p class="description">Attribute definition: Overwrites base class.</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Fields inherited from Smarty\Smarty_Internal_CompileBase</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.html#option_flags">option_flags</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.html#optional_attributes">optional_attributes</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.html#required_attributes">required_attributes</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.html#shorttag_order">shorttag_order</a></td></tr></table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#compile()">compile</a>(array args, object compiler, array parameter, string tag)</p><p class="description">Compiles code for the execution of a block function</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_Internal_CompileBase</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.html#closeTag()">closeTag</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.html#getAttributes()">getAttributes</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.html#openTag()">openTag</a></td></tr></table>

##Field Detail##
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_internal_compile_private_registered_block.php.md#line26" class="location">framework\libs\smarty\sysplugins\smarty_internal_compile_private_registered_block.php at line 26</a>

<h3 id="optional_attributes">optional_attributes</h3>
```php
public  array **$optional_attributes** = array('_any')```
<div class="details">
<p>Attribute definition: Overwrites base class.</p><dl>
<dt>See Also:</dt>
<dd><a href="../smarty/smarty_internal_compilebase.html">Smarty_Internal_CompileBase</a></dd>
</dl>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_internal_compile_private_registered_block.php.md#line37" class="location">framework\libs\smarty\sysplugins\smarty_internal_compile_private_registered_block.php at line 37</a>

<h3 id="compile()">compile</h3>
```php
public  string **compile**(array args, object compiler, array parameter, string tag)```
<div class="details">
<p>Compiles code for the execution of a block function</p><dl>
<dt>Parameters:</dt>
<dd>args - array with attributes from parser</dd>
<dd>compiler - compiler object</dd>
<dd>parameter - array with compilation parameter</dd>
<dd>tag - name of block function</dd>
<dt>Returns:</dt>
<dd>compiled code</dd>
</dl>
</div>

- - -

