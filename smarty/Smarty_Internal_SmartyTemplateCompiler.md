
- - -

**Smarty\Smarty_Internal_SmartyTemplateCompiler**
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_smartytemplatecompiler.php at line 23</div>
#Class Smarty_Internal_SmartyTemplateCompiler#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatecompilerbase.html">Smarty_Internal_TemplateCompilerBase</a>
    ***Smarty_Internal_SmartyTemplateCompiler**


- - -

<p class="signature">public  class **Smarty_Internal_SmartyTemplateCompiler**
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatecompilerbase.html">Smarty_Internal_TemplateCompilerBase</a>

</p>

<div class="comment" id="overview_description"><p>Class SmartyTemplateCompiler</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>Compiler</dd>
</dl>

- - -

<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td class="type"> object</td>
<td class="description"><p class="name"><a href="#lex">$lex</a></p><p class="description">Lexer object</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#lexer_class">$lexer_class</a></p><p class="description">Lexer class name</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#local_var">$local_var</a></p><p class="description">array of vars which can be compiled in local scope</p></td>
</tr>
<tr>
<td class="type"> object</td>
<td class="description"><p class="name"><a href="#parser">$parser</a></p><p class="description">Parser object</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#parser_class">$parser_class</a></p><p class="description">Parser class name</p></td>
</tr>
<tr>
<td class="type"> object</td>
<td class="description"><p class="name"><a href="#smarty">$smarty</a></p><p class="description">Smarty object</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Fields inherited from Smarty\Smarty_Internal_TemplateCompilerBase</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatecompilerbase.html#_tag_objects">_tag_objects</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatecompilerbase.html#_tag_stack">_tag_stack</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatecompilerbase.html#called_functions">called_functions</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatecompilerbase.html#compiles_template_function">compiles_template_function</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatecompilerbase.html#default_handler_plugins">default_handler_plugins</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatecompilerbase.html#default_modifier_list">default_modifier_list</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatecompilerbase.html#forceNocache">forceNocache</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatecompilerbase.html#inheritance">inheritance</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatecompilerbase.html#merged_templates">merged_templates</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatecompilerbase.html#modifier_plugins">modifier_plugins</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatecompilerbase.html#suppressHeader">suppressHeader</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatecompilerbase.html#suppressMergedTemplates">suppressMergedTemplates</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatecompilerbase.html#suppressNocacheProcessing">suppressNocacheProcessing</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatecompilerbase.html#suppressTemplatePropertyHeader">suppressTemplatePropertyHeader</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatecompilerbase.html#template">template</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatecompilerbase.html#write_compiled_code">write_compiled_code</a></td></tr></table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(string lexer_class, string parser_class, <a href="../smarty/smarty.html">Smarty</a> smarty)</p><p class="description">Initialize compiler</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> protected  bool</td>
<td class="description"><p class="name"><a href="#docompile">doCompile</a>(mixed _content)</p><p class="description">Methode to compile a Smarty template</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_Internal_TemplateCompilerBase</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatecompilerbase.html#__construct()">__construct</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatecompilerbase.html#callTagCompiler()">callTagCompiler</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatecompilerbase.html#compileTag()">compileTag</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatecompilerbase.html#compileTemplate()">compileTemplate</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatecompilerbase.html#getPlugin()">getPlugin</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatecompilerbase.html#getPluginFromDefaultHandler()">getPluginFromDefaultHandler</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatecompilerbase.html#processNocacheCode()">processNocacheCode</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_templatecompilerbase.html#trigger_template_error()">trigger_template_error</a></td></tr></table>

##Field Detail##
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_smartytemplatecompiler.php at line 44</div>
<h3 id="lex">lex</h3>

public  object $lex
<div class="details">
<p>Lexer object</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_smartytemplatecompiler.php at line 30</div>
<h3 id="lexer_class">lexer_class</h3>

public  string $lexer_class = null
<div class="details">
<p>Lexer class name</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_smartytemplatecompiler.php at line 65</div>
<h3 id="local_var">local_var</h3>

public  array $local_var = array()
<div class="details">
<p>array of vars which can be compiled in local scope</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_smartytemplatecompiler.php at line 51</div>
<h3 id="parser">parser</h3>

public  object $parser
<div class="details">
<p>Parser object</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_smartytemplatecompiler.php at line 37</div>
<h3 id="parser_class">parser_class</h3>

public  string $parser_class
<div class="details">
<p>Parser class name</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_smartytemplatecompiler.php at line 58</div>
<h3 id="smarty">smarty</h3>

public  object $smarty
<div class="details">
<p>Smarty object</p></div>

- - -

<h2 id="detail_method">Constructor Detail</h2>
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_smartytemplatecompiler.php at line 74</div>
<h3 id="__construct()">__construct</h3>

```php
public  void **__construct**(string lexer_class, string parser_class, <a href="../smarty/smarty.html">Smarty</a> smarty)
```
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
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_smartytemplatecompiler.php at line 89</div>
<h3 id="doCompile()">doCompile</h3>

protected  bool **doCompile** (mixed _content)<div class="details">
<p>Methode to compile a Smarty template</p><dl>
<dt>Parameters:</dt>
<dd>_content - template source</dd>
<dt>Returns:</dt>
<dd>true if compiling succeeded, false if it failed</dd>
</dl>
</div>

- - -

