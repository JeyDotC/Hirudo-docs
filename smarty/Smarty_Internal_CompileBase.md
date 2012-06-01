

- - -

**Smarty\Smarty_Internal_CompileBase**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_compilebase.php#L16" >framework\libs\smarty\sysplugins\smarty_internal_compilebase.php at line 16</a>

#Class Smarty_Internal_CompileBase#

**Smarty_Internal_CompileBase**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_assign.md">Smarty_Internal_Compile_Assign</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_block.md">Smarty_Internal_Compile_Block</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_blockclose.md">Smarty_Internal_Compile_Blockclose</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_break.md">Smarty_Internal_Compile_Break</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_call.md">Smarty_Internal_Compile_Call</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_capture.md">Smarty_Internal_Compile_Capture</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_captureclose.md">Smarty_Internal_Compile_CaptureClose</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_config_load.md">Smarty_Internal_Compile_Config_Load</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_continue.md">Smarty_Internal_Compile_Continue</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_debug.md">Smarty_Internal_Compile_Debug</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_else.md">Smarty_Internal_Compile_Else</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_elseif.md">Smarty_Internal_Compile_Elseif</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_eval.md">Smarty_Internal_Compile_Eval</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_extends.md">Smarty_Internal_Compile_Extends</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_for.md">Smarty_Internal_Compile_For</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_forclose.md">Smarty_Internal_Compile_Forclose</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_foreach.md">Smarty_Internal_Compile_Foreach</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_foreachclose.md">Smarty_Internal_Compile_Foreachclose</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_foreachelse.md">Smarty_Internal_Compile_Foreachelse</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_forelse.md">Smarty_Internal_Compile_Forelse</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_function.md">Smarty_Internal_Compile_Function</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_functionclose.md">Smarty_Internal_Compile_Functionclose</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_if.md">Smarty_Internal_Compile_If</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_ifclose.md">Smarty_Internal_Compile_Ifclose</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_include.md">Smarty_Internal_Compile_Include</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_include_php.md">Smarty_Internal_Compile_Include_Php</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_insert.md">Smarty_Internal_Compile_Insert</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_ldelim.md">Smarty_Internal_Compile_Ldelim</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_nocache.md">Smarty_Internal_Compile_Nocache</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_nocacheclose.md">Smarty_Internal_Compile_Nocacheclose</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_private_block_plugin.md">Smarty_Internal_Compile_Private_Block_Plugin</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_private_function_plugin.md">Smarty_Internal_Compile_Private_Function_Plugin</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_private_modifier.md">Smarty_Internal_Compile_Private_Modifier</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_private_object_block_function.md">Smarty_Internal_Compile_Private_Object_Block_Function</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_private_object_function.md">Smarty_Internal_Compile_Private_Object_Function</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_private_print_expression.md">Smarty_Internal_Compile_Private_Print_Expression</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_private_registered_block.md">Smarty_Internal_Compile_Private_Registered_Block</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_private_registered_function.md">Smarty_Internal_Compile_Private_Registered_Function</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_private_special_variable.md">Smarty_Internal_Compile_Private_Special_Variable</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_rdelim.md">Smarty_Internal_Compile_Rdelim</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_section.md">Smarty_Internal_Compile_Section</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_sectionclose.md">Smarty_Internal_Compile_Sectionclose</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_sectionelse.md">Smarty_Internal_Compile_Sectionelse</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_setfilter.md">Smarty_Internal_Compile_Setfilter</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_setfilterclose.md">Smarty_Internal_Compile_Setfilterclose</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_while.md">Smarty_Internal_Compile_While</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_compile_whileclose.md">Smarty_Internal_Compile_Whileclose</a> </dd>
</dl>



- - -

<p class="signature"><span class='k'>public abstract  class</span> <span class='nx'>Smarty_Internal_CompileBase</span></p>

<div class="comment" id="overview_description"><p>This class does extend all internal compile plugins</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>Compiler</dd>
</dl>


- - -



<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#option_flags"> $option_flags</a>
                                </p><p class="description">Array of names of valid option flags</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#optional_attributes"> $optional_attributes</a>
                                </p><p class="description">Array of names of optional attribute required by tag
use array('_any') if there is no restriction of attributes names</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#required_attributes"> $required_attributes</a>
                                </p><p class="description">Array of names of required attribute required by tag</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#shorttag_order"> $shorttag_order</a>
                                </p><p class="description">Shorttag attribute order defined by its names</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name"><a href="#getattributes">getAttributes</a>(object compiler, array attributes)</p><p class="description">This function checks if the attributes passed are validThe attributes passed for the tag to compile are checked against the list of required and
optional attributes. </p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#opentag">openTag</a>(object compiler, string openTag, mixed data)</p><p class="description">Push opening tag name on stackOptionally additional data can be saved on stack</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#closetag">closeTag</a>(object compiler, array|string expectedTag)</p><p class="description">Pop closing tagRaise an error if this stack-top doesn't match with expected opening tags</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_compilebase.php#L56" >framework\libs\smarty\sysplugins\smarty_internal_compilebase.php at line 56</a>

<h3 id="getAttributes()">getAttributes</h3>
<span class='k'></span> <span class='nx'>array</span> <span class='nf'>getAttributes</span> (object compiler, array attributes)

<div class="details">
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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_compilebase.php#L136" >framework\libs\smarty\sysplugins\smarty_internal_compilebase.php at line 136</a>

<h3 id="openTag()">openTag</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>openTag</span> (object compiler, string openTag, mixed data)

<div class="details">
<p>Push opening tag name on stack</p><p>Optionally additional data can be saved on stack</p><dl>
<dt>Parameters:</dt>
<dd>compiler - compiler object</dd>
<dd>openTag - the opening tag's name</dd>
<dd>data - optional data saved</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_compilebase.php#L150" >framework\libs\smarty\sysplugins\smarty_internal_compilebase.php at line 150</a>

<h3 id="closeTag()">closeTag</h3>
<span class='k'></span> <span class='nx'>mixed</span> <span class='nf'>closeTag</span> (object compiler, array|string expectedTag)

<div class="details">
<p>Pop closing tag</p><p>Raise an error if this stack-top doesn't match with expected opening tags</p><dl>
<dt>Parameters:</dt>
<dd>compiler - compiler object</dd>
<dd>expectedTag - the expected opening tag names</dd>
<dt>Returns:</dt>
<dd>any type the opening tag's name or saved data</dd>
</dl>

</div>

- - -

