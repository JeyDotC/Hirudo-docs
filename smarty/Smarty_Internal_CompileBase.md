
- - -

**Smarty\Smarty_Internal_CompileBase**
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_compilebase.php at line 16</div>
#Class Smarty_Internal_CompileBase#

**Smarty_Internal_CompileBase**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_assign.html">Smarty_Internal_Compile_Assign</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_block.html">Smarty_Internal_Compile_Block</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_blockclose.html">Smarty_Internal_Compile_Blockclose</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_break.html">Smarty_Internal_Compile_Break</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_call.html">Smarty_Internal_Compile_Call</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_capture.html">Smarty_Internal_Compile_Capture</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_captureclose.html">Smarty_Internal_Compile_CaptureClose</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_config_load.html">Smarty_Internal_Compile_Config_Load</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_continue.html">Smarty_Internal_Compile_Continue</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_debug.html">Smarty_Internal_Compile_Debug</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_else.html">Smarty_Internal_Compile_Else</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_elseif.html">Smarty_Internal_Compile_Elseif</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_eval.html">Smarty_Internal_Compile_Eval</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_extends.html">Smarty_Internal_Compile_Extends</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_for.html">Smarty_Internal_Compile_For</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_forclose.html">Smarty_Internal_Compile_Forclose</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_foreach.html">Smarty_Internal_Compile_Foreach</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_foreachclose.html">Smarty_Internal_Compile_Foreachclose</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_foreachelse.html">Smarty_Internal_Compile_Foreachelse</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_forelse.html">Smarty_Internal_Compile_Forelse</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_function.html">Smarty_Internal_Compile_Function</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_functionclose.html">Smarty_Internal_Compile_Functionclose</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_if.html">Smarty_Internal_Compile_If</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_ifclose.html">Smarty_Internal_Compile_Ifclose</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_include.html">Smarty_Internal_Compile_Include</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_include_php.html">Smarty_Internal_Compile_Include_Php</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_insert.html">Smarty_Internal_Compile_Insert</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_ldelim.html">Smarty_Internal_Compile_Ldelim</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_nocache.html">Smarty_Internal_Compile_Nocache</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_nocacheclose.html">Smarty_Internal_Compile_Nocacheclose</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_private_block_plugin.html">Smarty_Internal_Compile_Private_Block_Plugin</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_private_function_plugin.html">Smarty_Internal_Compile_Private_Function_Plugin</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_private_modifier.html">Smarty_Internal_Compile_Private_Modifier</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_private_object_block_function.html">Smarty_Internal_Compile_Private_Object_Block_Function</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_private_object_function.html">Smarty_Internal_Compile_Private_Object_Function</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_private_print_expression.html">Smarty_Internal_Compile_Private_Print_Expression</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_private_registered_block.html">Smarty_Internal_Compile_Private_Registered_Block</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_private_registered_function.html">Smarty_Internal_Compile_Private_Registered_Function</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_private_special_variable.html">Smarty_Internal_Compile_Private_Special_Variable</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_rdelim.html">Smarty_Internal_Compile_Rdelim</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_section.html">Smarty_Internal_Compile_Section</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_sectionclose.html">Smarty_Internal_Compile_Sectionclose</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_sectionelse.html">Smarty_Internal_Compile_Sectionelse</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_setfilter.html">Smarty_Internal_Compile_Setfilter</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_setfilterclose.html">Smarty_Internal_Compile_Setfilterclose</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_while.html">Smarty_Internal_Compile_While</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_whileclose.html">Smarty_Internal_Compile_Whileclose</a> </dd>
</dl>

- - -

<p class="signature">public abstract  class **Smarty_Internal_CompileBase**</p>

<div class="comment" id="overview_description"><p>This class does extend all internal compile plugins</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>Compiler</dd>
</dl>

- - -

<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#option_flags">$option_flags</a></p><p class="description">Array of names of valid option flags</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#optional_attributes">$optional_attributes</a></p><p class="description">Array of names of optional attribute required by tag
use array('_any') if there is no restriction of attributes names</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#required_attributes">$required_attributes</a></p><p class="description">Array of names of required attribute required by tag</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#shorttag_order">$shorttag_order</a></p><p class="description">Shorttag attribute order defined by its names</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type">  array</td>
<td class="description"><p class="name"><a href="#getattributes">getAttributes</a>(object compiler, array attributes)</p><p class="description">This function checks if the attributes passed are validThe attributes passed for the tag to compile are checked against the list of required and
optional attributes. </p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#opentag">openTag</a>(object compiler, string openTag, mixed data)</p><p class="description">Push opening tag name on stackOptionally additional data can be saved on stack</p></td>
</tr>
<tr>
<td class="type">  mixed</td>
<td class="description"><p class="name"><a href="#closetag">closeTag</a>(object compiler, array|string expectedTag)</p><p class="description">Pop closing tagRaise an error if this stack-top doesn't match with expected opening tags</p></td>
</tr>
</table>

##Field Detail##
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_compilebase.php at line 42</div>
<h3 id="option_flags">option_flags</h3>

public  array $option_flags = array('nocache')
<div class="details">
<p>Array of names of valid option flags</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_compilebase.php at line 30</div>
<h3 id="optional_attributes">optional_attributes</h3>

public  array $optional_attributes = array()
<div class="details">
<p>Array of names of optional attribute required by tag
use array('_any') if there is no restriction of attributes names</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_compilebase.php at line 23</div>
<h3 id="required_attributes">required_attributes</h3>

public  array $required_attributes = array()
<div class="details">
<p>Array of names of required attribute required by tag</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_compilebase.php at line 36</div>
<h3 id="shorttag_order">shorttag_order</h3>

public  array $shorttag_order = array()
<div class="details">
<p>Shorttag attribute order defined by its names</p></div>

- - -

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_compilebase.php at line 56</div>
<h3 id="getAttributes()">getAttributes</h3>

public  array **getAttributes** (object compiler, array attributes)<div class="details">
<p>This function checks if the attributes passed are valid</p><p>The attributes passed for the tag to compile are checked against the list of required and
optional attributes. Required attributes must be present. Optional attributes are check against
the corresponding list. The keyword '_any' specifies that any attribute will be accepted
as valid</p><dl>
<dt>Parameters:</dt>
<dd>compiler - compiler object</dd>
<dd>attributes - attributes applied to the tag</dd>
<dt>Returns:</dt>
<dd>of mapped attributes for further processing</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_compilebase.php at line 136</div>
<h3 id="openTag()">openTag</h3>

public  void **openTag** (object compiler, string openTag, mixed data)<div class="details">
<p>Push opening tag name on stack</p><p>Optionally additional data can be saved on stack</p><dl>
<dt>Parameters:</dt>
<dd>compiler - compiler object</dd>
<dd>openTag - the opening tag's name</dd>
<dd>data - optional data saved</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_compilebase.php at line 150</div>
<h3 id="closeTag()">closeTag</h3>

public  mixed **closeTag** (object compiler, array|string expectedTag)<div class="details">
<p>Pop closing tag</p><p>Raise an error if this stack-top doesn't match with expected opening tags</p><dl>
<dt>Parameters:</dt>
<dd>compiler - compiler object</dd>
<dd>expectedTag - the expected opening tag names</dd>
<dt>Returns:</dt>
<dd>any type the opening tag's name or saved data</dd>
</dl>
</div>

- - -

