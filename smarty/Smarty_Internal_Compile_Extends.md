- - -

**Smarty\Smarty_Internal_Compile_Extends**
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_internal_compile_extends.php.md#line19" class="location">framework\libs\smarty\sysplugins\smarty_internal_compile_extends.php at line 19</a>

# Class Smarty_Internal_Compile_Extends #

<pre class="tree"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.html">Smarty_Internal_CompileBase</a>\n    *** Smarty_Internal_Compile_Extends **\n</pre>

- - -

<p class="signature">public  class **Smarty_Internal_Compile_Extends**\nextends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.html">Smarty_Internal_CompileBase</a>

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
<td class="type"> int</td>
<td class="description"><p class="name"><a href="#mbstring_overload">$mbstring_overload</a></p><p class="description">mbstring.overload flag</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#required_attributes">$required_attributes</a></p><p class="description">Attribute definition: Overwrites base class.</p></td>
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
<td class="description"><p class="name"><a href="#compile()">compile</a>(array args, object compiler)</p><p class="description">Compiles code for the {extends} tag</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_Internal_CompileBase</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.html#closeTag()">closeTag</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.html#getAttributes()">getAttributes</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.html#openTag()">openTag</a></td></tr></table>

##Field Detail##
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_internal_compile_extends.php.md#line40" class="location">framework\libs\smarty\sysplugins\smarty_internal_compile_extends.php at line 40</a>

<h3 id="mbstring_overload">mbstring_overload</h3>
```php
public  int **$mbstring_overload** = 0```
<div class="details">
<p>mbstring.overload flag</p></div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_internal_compile_extends.php.md#line27" class="location">framework\libs\smarty\sysplugins\smarty_internal_compile_extends.php at line 27</a>

<h3 id="required_attributes">required_attributes</h3>
```php
public  array **$required_attributes** = array('file')```
<div class="details">
<p>Attribute definition: Overwrites base class.</p><dl>
<dt>See Also:</dt>
<dd><a href="../smarty/smarty_internal_compilebase.html">Smarty_Internal_CompileBase</a></dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_internal_compile_extends.php.md#line34" class="location">framework\libs\smarty\sysplugins\smarty_internal_compile_extends.php at line 34</a>

<h3 id="shorttag_order">shorttag_order</h3>
```php
public  array **$shorttag_order** = array('file')```
<div class="details">
<p>Attribute definition: Overwrites base class.</p><dl>
<dt>See Also:</dt>
<dd><a href="../smarty/smarty_internal_compilebase.html">Smarty_Internal_CompileBase</a></dd>
</dl>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_internal_compile_extends.php.md#line49" class="location">framework\libs\smarty\sysplugins\smarty_internal_compile_extends.php at line 49</a>

<h3 id="compile()">compile</h3>
```php
public  string **compile**(array args, object compiler)```
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

