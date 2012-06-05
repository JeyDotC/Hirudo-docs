

- - -

**Smarty\Smarty_Internal_TemplateCompilerBase**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatecompilerbase.php#L18" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatecompilerbase.php at line 18</a>

#Class Smarty_Internal_TemplateCompilerBase#

**Smarty_Internal_TemplateCompilerBase**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_SmartyTemplateCompiler.md">Smarty_Internal_SmartyTemplateCompiler</a> </dd>
</dl>



- - -

<p><strong>public abstract  class</strong> <span>Smarty_Internal_TemplateCompilerBase</span></p>

<div class="comment" id="overview_description"><p>Main abstract compiler class</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>Compiler</dd>
</dl>


- - -



<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#_tag_objects"> $_tag_objects</a>
                                </p><p class="description">compile tag objects</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#_tag_stack"> $_tag_stack</a>
                                </p><p class="description">tag stack</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#called_functions"> $called_functions</a>
                                </p><p class="description">called subfuntions from template function</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>bool</span></td>
<td class="description"><p class="name" ><a href="#compiles_template_function"> $compiles_template_function</a>
                                </p><p class="description">flag if currently a template function is compiled</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#default_handler_plugins"> $default_handler_plugins</a>
                                </p><p class="description">plugins loaded by default plugin handler</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="#default_modifier_list"> $default_modifier_list</a>
                                </p><p class="description">saved preprocessed modifier list</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name" ><a href="#forceNocache"> $forceNocache</a>
                                </p><p class="description">force compilation of complete template as nocache</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>bool</span></td>
<td class="description"><p class="name" ><a href="#inheritance"> $inheritance</a>
                                </p><p class="description">flag when compiling {block}</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#merged_templates"> $merged_templates</a>
                                </p><p class="description">merged templates</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#modifier_plugins"> $modifier_plugins</a>
                                </p><p class="description">flags for used modifier plugins</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>bool</span></td>
<td class="description"><p class="name" ><a href="#suppressHeader"> $suppressHeader</a>
                                </p><p class="description">suppress Smarty header code in compiled template</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>bool</span></td>
<td class="description"><p class="name" ><a href="#suppressMergedTemplates"> $suppressMergedTemplates</a>
                                </p><p class="description">suppress generation of merged template code</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>bool</span></td>
<td class="description"><p class="name" ><a href="#suppressNocacheProcessing"> $suppressNocacheProcessing</a>
                                </p><p class="description">suppress generation of nocache code</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>bool</span></td>
<td class="description"><p class="name" ><a href="#suppressTemplatePropertyHeader"> $suppressTemplatePropertyHeader</a>
                                </p><p class="description">suppress template property header code in compiled template</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_TemplateCompilerBase.md#template'>Smarty_Internal_Template</a></span></td>
<td class="description"><p class="name" ><a href="#template"> $template</a>
                                </p><p class="description">current template</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>bool</span></td>
<td class="description"><p class="name" ><a href="#write_compiled_code"> $write_compiled_code</a>
                                </p><p class="description">flag if compiled template file shall we written</p></td>
</tr>
</table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>()</p><p class="description">Initialize compiler</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>bool</span></td>
<td class="description"><p class="name"><a href="#compiletemplate">compileTemplate</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> template)</p><p class="description">Method to compile a Smarty template</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#compiletag">compileTag</a>(string tag, array args, array parameter)</p><p class="description">Compile TagThis is a call back from the lexer/parser
It executes the required compile plugin for the Smarty tag</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#calltagcompiler">callTagCompiler</a>(string tag, array args, mixed param1, mixed param2, mixed param3)</p><p class="description">lazy loads internal compile plugin for tag and calls the compile methodecompile objects cached for reuse.
</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getplugin">getPlugin</a>(string pugin_name, string plugin_type, mixed plugin_name)</p><p class="description">Check for plugins and return function name</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#getpluginfromdefaulthandler">getPluginFromDefaultHandler</a>(string tag, string plugin_type)</p><p class="description">Check for plugins by default plugin handler</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#processnocachecode">processNocacheCode</a>(string content, boolean is_code)</p><p class="description">Inject inline code for nocache template sectionsThis method gets the content of each template element from the parser.
</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#trigger_template_error">trigger_template_error</a>(string args, string line)</p><p class="description">display compiler error messages without dyingIf parameter $args is empty it is a parser detected syntax error.
</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatecompilerbase.php#L119" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatecompilerbase.php at line 119</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> ()

<div class="details">
<p>Initialize compiler</p>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatecompilerbase.php#L130" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatecompilerbase.php at line 130</a>

<h3 id="compileTemplate()">compileTemplate</h3>
<span class='k'></span> <span class='nx'>bool</span> <span class='nf'>compileTemplate</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> template)

<div class="details">
<p>Method to compile a Smarty template</p><dl>
<dt>Parameters:</dt>
<dd>template - template object to compile</dd>
<dt>Returns:</dt>
<dd>true if compiling succeeded, false if it failed</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatecompilerbase.php#L211" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatecompilerbase.php at line 211</a>

<h3 id="compileTag()">compileTag</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>compileTag</span> (string tag, array args, array parameter)

<div class="details">
<p>Compile Tag</p><p>This is a call back from the lexer/parser
It executes the required compile plugin for the Smarty tag</p><dl>
<dt>Parameters:</dt>
<dd>tag - tag name</dd>
<dd>args - array with tag attributes</dd>
<dd>parameter - array with compilation parameter</dd>
<dt>Returns:</dt>
<dd>compiled code</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatecompilerbase.php#L424" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatecompilerbase.php at line 424</a>

<h3 id="callTagCompiler()">callTagCompiler</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>callTagCompiler</span> (string tag, array args, mixed param1, mixed param2, mixed param3)

<div class="details">
<p>lazy loads internal compile plugin for tag and calls the compile methode</p><p>compile objects cached for reuse.
class name format:  Smarty_Internal_Compile_TagName
plugin filename format: Smarty_Internal_Tagname.php</p><dl>
<dt>Parameters:</dt>
<dd>tag - tag name</dd>
<dd>args - list of tag attributes</dd>
<dd>param1 - optional parameter</dd>
<dd>param2 - optional parameter</dd>
<dd>param3 - optional parameter</dd>
<dt>Returns:</dt>
<dd>compiled code</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatecompilerbase.php#L453" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatecompilerbase.php at line 453</a>

<h3 id="getPlugin()">getPlugin</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getPlugin</span> (string pugin_name, string plugin_type, mixed plugin_name)

<div class="details">
<p>Check for plugins and return function name</p><dl>
<dt>Parameters:</dt>
<dd>pugin_name - name of plugin or function</dd>
<dd>plugin_type - type of plugin</dd>
<dt>Returns:</dt>
<dd>call name of function</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatecompilerbase.php#L508" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatecompilerbase.php at line 508</a>

<h3 id="getPluginFromDefaultHandler()">getPluginFromDefaultHandler</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>getPluginFromDefaultHandler</span> (string tag, string plugin_type)

<div class="details">
<p>Check for plugins by default plugin handler</p><dl>
<dt>Parameters:</dt>
<dd>tag - name of tag</dd>
<dd>plugin_type - type of plugin</dd>
<dt>Returns:</dt>
<dd>true if found</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatecompilerbase.php#L557" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatecompilerbase.php at line 557</a>

<h3 id="processNocacheCode()">processNocacheCode</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>processNocacheCode</span> (string content, boolean is_code)

<div class="details">
<p>Inject inline code for nocache template sections</p><p>This method gets the content of each template element from the parser.
If the content is compiled code and it should be not cached the code is injected
into the rendered output.</p><dl>
<dt>Parameters:</dt>
<dd>content - content of template element</dd>
<dd>is_code - true if content is compiled code</dd>
<dt>Returns:</dt>
<dd>content</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatecompilerbase.php#L599" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatecompilerbase.php at line 599</a>

<h3 id="trigger_template_error()">trigger_template_error</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>trigger_template_error</span> (string args, string line)

<div class="details">
<p>display compiler error messages without dying</p><p>If parameter $args is empty it is a parser detected syntax error.
In this case the parser is called to obtain information about expected tokens.</p><p>If parameter $args contains a string this is used as error message</p><dl>
<dt>Parameters:</dt>
<dd>args - individual error message or null</dd>
<dd>line - line-number</dd>
<dt>Throws:</dt>
<dd><a href="../smarty/smartycompilerexception.html">SmartyCompilerException</a> - when an unexpected token is found</dd>
</dl>

</div>

- - -

