

- - -

**Smarty\Smarty_Internal_SmartyTemplateCompiler**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_smartytemplatecompiler.php#L23" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_smartytemplatecompiler.php at line 23</a>

#Class Smarty_Internal_SmartyTemplateCompiler#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateCompilerBase.md">Smarty_Internal_TemplateCompilerBase</a>
 &gt; **Smarty_Internal_SmartyTemplateCompiler**




- - -

<p><strong>public  class</strong> <span>Smarty_Internal_SmartyTemplateCompiler</span>
<strong>extends</strong> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateCompilerBase.md">Smarty_Internal_TemplateCompilerBase</a>

</p>

<div class="comment" id="overview_description"><p>Class SmartyTemplateCompiler</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>Compiler</dd>
</dl>


<hr />



<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>object</span></td>
<td class="description"><p class="name" ><a href="#lex"> $lex</a>
                                </p><p class="description">Lexer object</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name" ><a href="#lexer_class"> $lexer_class</a>
                                </p><p class="description">Lexer class name</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#local_var"> $local_var</a>
                                </p><p class="description">array of vars which can be compiled in local scope</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>object</span></td>
<td class="description"><p class="name" ><a href="#parser"> $parser</a>
                                </p><p class="description">Parser object</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name" ><a href="#parser_class"> $parser_class</a>
                                </p><p class="description">Parser class name</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>object</span></td>
<td class="description"><p class="name" ><a href="#smarty"> $smarty</a>
                                </p><p class="description">Smarty object</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Fields inherited from Smarty\Smarty_Internal_TemplateCompilerBase</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateCompilerBase.md#_tag_objects">_tag_objects</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateCompilerBase.md#_tag_stack">_tag_stack</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateCompilerBase.md#called_functions">called_functions</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateCompilerBase.md#compiles_template_function">compiles_template_function</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateCompilerBase.md#default_handler_plugins">default_handler_plugins</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateCompilerBase.md#default_modifier_list">default_modifier_list</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateCompilerBase.md#forceNocache">forceNocache</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateCompilerBase.md#inheritance">inheritance</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateCompilerBase.md#merged_templates">merged_templates</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateCompilerBase.md#modifier_plugins">modifier_plugins</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateCompilerBase.md#suppressHeader">suppressHeader</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateCompilerBase.md#suppressMergedTemplates">suppressMergedTemplates</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateCompilerBase.md#suppressNocacheProcessing">suppressNocacheProcessing</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateCompilerBase.md#suppressTemplatePropertyHeader">suppressTemplatePropertyHeader</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateCompilerBase.md#template">template</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateCompilerBase.md#write_compiled_code">write_compiled_code</a></td></tr></table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(string lexer_class, string parser_class, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md">Smarty</a> smarty)</p><p class="description">Initialize compiler</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>bool</span></td>
<td class="description"><p class="name"><a href="#docompile">doCompile</a>(mixed _content)</p><p class="description">Methode to compile a Smarty template</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_Internal_TemplateCompilerBase</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateCompilerBase.md#__construct">__construct</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateCompilerBase.md#callTagCompiler">callTagCompiler</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateCompilerBase.md#compileTag">compileTag</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateCompilerBase.md#compileTemplate">compileTemplate</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateCompilerBase.md#getPlugin">getPlugin</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateCompilerBase.md#getPluginFromDefaultHandler">getPluginFromDefaultHandler</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateCompilerBase.md#processNocacheCode">processNocacheCode</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateCompilerBase.md#trigger_template_error">trigger_template_error</a></td></tr></table>

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_smartytemplatecompiler.php#L74" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_smartytemplatecompiler.php at line 74</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (string lexer_class, string parser_class, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty.md">Smarty</a> smarty)

<div class="details">
<p>Initialize compiler</p><dl>
<dt>Parameters:</dt>
<dd>lexer_class - class name</dd>
<dd>parser_class - class name</dd>
<dd>smarty - global instance</dd>
</dl>

</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_smartytemplatecompiler.php#L89" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_smartytemplatecompiler.php at line 89</a>

<h3 id="doCompile()">doCompile</h3>
<span class='k'>protected </span> <span class='nx'>bool</span> <span class='nf'>doCompile</span> (mixed _content)

<div class="details">
<p>Methode to compile a Smarty template</p><dl>
<dt>Parameters:</dt>
<dd>_content - template source</dd>
<dt>Returns:</dt>
<dd>true if compiling succeeded, false if it failed</dd>
</dl>

</div>

- - -
