- - -

**Smarty\Smarty_Internal_Compile_Break**
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_internal_compile_break.php.md#line17" class="location">framework\libs\smarty\sysplugins\smarty_internal_compile_break.php at line 17</a>

# Class Smarty_Internal_Compile_Break #

<pre class="tree"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.html">Smarty_Internal_CompileBase</a>\n    *** Smarty_Internal_Compile_Break **\n</pre>

- - -

<p class="signature">public  class **Smarty_Internal_Compile_Break**\nextends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.html">Smarty_Internal_CompileBase</a>

</p>

<div class="comment" id="overview_description"><p>Smarty Internal Plugin Compile Break Class</p></div>

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
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#shorttag_order">$shorttag_order</a></p><p class="description">Attribute definition: Overwrites base class.</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Fields inherited from Smarty\Smarty_Internal_CompileBase</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.html#option_flags">option_flags</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.html#optional_attributes">optional_attributes</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.html#required_attributes">required_attributes</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.html#shorttag_order">shorttag_order</a></td></tr></table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#compile()">compile</a>(array args, object compiler, array parameter)</p><p class="description">Compiles code for the {break} tag</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_Internal_CompileBase</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.html#closeTag()">closeTag</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.html#getAttributes()">getAttributes</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.html#openTag()">openTag</a></td></tr></table>

##Field Detail##
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_internal_compile_break.php.md#line25" class="location">framework\libs\smarty\sysplugins\smarty_internal_compile_break.php at line 25</a>

<h3 id="optional_attributes">optional_attributes</h3>
```php
public  array **$optional_attributes** = array('levels')```
<div class="details">
<p>Attribute definition: Overwrites base class.</p><dl>
<dt>See Also:</dt>
<dd><a href="../smarty/smarty_internal_compilebase.html">Smarty_Internal_CompileBase</a></dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_internal_compile_break.php.md#line32" class="location">framework\libs\smarty\sysplugins\smarty_internal_compile_break.php at line 32</a>

<h3 id="shorttag_order">shorttag_order</h3>
```php
public  array **$shorttag_order** = array('levels')```
<div class="details">
<p>Attribute definition: Overwrites base class.</p><dl>
<dt>See Also:</dt>
<dd><a href="../smarty/smarty_internal_compilebase.html">Smarty_Internal_CompileBase</a></dd>
</dl>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_internal_compile_break.php.md#line42" class="location">framework\libs\smarty\sysplugins\smarty_internal_compile_break.php at line 42</a>

<h3 id="compile()">compile</h3>
```php
public  string **compile**(array args, object compiler, array parameter)```
<div class="details">
<p>Compiles code for the {break} tag</p><dl>
<dt>Parameters:</dt>
<dd>args - array with attributes from parser</dd>
<dd>compiler - compiler object</dd>
<dd>parameter - array with compilation parameter</dd>
<dt>Returns:</dt>
<dd>compiled code</dd>
</dl>
</div>

- - -

