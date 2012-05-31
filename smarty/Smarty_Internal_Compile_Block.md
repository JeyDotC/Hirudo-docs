
- - -

**Smarty\Smarty_Internal_Compile_Block**
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_compile_block.php at line 18</div>
#Class Smarty_Internal_Compile_Block#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.html">Smarty_Internal_CompileBase</a>
    ***Smarty_Internal_Compile_Block**


- - -

<p class="signature">public  class **Smarty_Internal_Compile_Block**
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.html">Smarty_Internal_CompileBase</a>

</p>

<div class="comment" id="overview_description"><p>Smarty Internal Plugin Compile Block Class</p></div>

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
<td class="type">  boolean</td>
<td class="description"><p class="name"><a href="#compile">compile</a>(array args, object compiler)</p><p class="description">Compiles code for the {block} tag</p></td>
</tr>
<tr>
<td class="type"> static  void</td>
<td class="description"><p class="name"><a href="#saveblockdata">saveBlockData</a>(string block_content, string block_tag, object template, string filepath)</p><p class="description">Save or replace child block source by block name during parsing</p></td>
</tr>
<tr>
<td class="type"> static  string</td>
<td class="description"><p class="name"><a href="#compilechildblock">compileChildBlock</a>(object compiler, string _name)</p><p class="description">Compile saved child block source</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_Internal_CompileBase</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.html#closeTag()">closeTag</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.html#getAttributes()">getAttributes</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compilebase.html#openTag()">openTag</a></td></tr></table>

##Field Detail##
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_compile_block.php at line 40</div>
<h3 id="optional_attributes">optional_attributes</h3>

public  array $optional_attributes = array('hide')
<div class="details">
<p>Attribute definition: Overwrites base class.</p><dl>
<dt>See Also:</dt>
<dd><a href="../smarty/smarty_internal_compilebase.html">Smarty_Internal_CompileBase</a></dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_compile_block.php at line 26</div>
<h3 id="required_attributes">required_attributes</h3>

public  array $required_attributes = array('name')
<div class="details">
<p>Attribute definition: Overwrites base class.</p><dl>
<dt>See Also:</dt>
<dd><a href="../smarty/smarty_internal_compilebase.html">Smarty_Internal_CompileBase</a></dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_compile_block.php at line 33</div>
<h3 id="shorttag_order">shorttag_order</h3>

public  array $shorttag_order = array('name', 'hide')
<div class="details">
<p>Attribute definition: Overwrites base class.</p><dl>
<dt>See Also:</dt>
<dd><a href="../smarty/smarty_internal_compilebase.html">Smarty_Internal_CompileBase</a></dd>
</dl>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_compile_block.php at line 49</div>
<h3 id="compile()">compile</h3>

public  boolean **compile** (array args, object compiler)<div class="details">
<p>Compiles code for the {block} tag</p><dl>
<dt>Parameters:</dt>
<dd>args - array with attributes from parser</dd>
<dd>compiler - compiler object</dd>
<dt>Returns:</dt>
<dd>true</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_compile_block.php at line 76</div>
<h3 id="saveBlockData()">saveBlockData</h3>

public static  void **saveBlockData** (string block_content, string block_tag, object template, string filepath)<div class="details">
<p>Save or replace child block source by block name during parsing</p><dl>
<dt>Parameters:</dt>
<dd>block_content - block source content</dd>
<dd>block_tag - opening block tag</dd>
<dd>template - template object</dd>
<dd>filepath - filepath of template source</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_compile_block.php at line 149</div>
<h3 id="compileChildBlock()">compileChildBlock</h3>

public static  string **compileChildBlock** (object compiler, string _name)<div class="details">
<p>Compile saved child block source</p><dl>
<dt>Parameters:</dt>
<dd>compiler - compiler object</dd>
<dd>_name - optional name of child block</dd>
<dt>Returns:</dt>
<dd>compiled code of schild block</dd>
</dl>
</div>

- - -

