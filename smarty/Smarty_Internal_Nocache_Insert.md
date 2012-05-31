- - -

**Smarty\Smarty_Internal_Nocache_Insert**
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_internal_nocache_insert.php.md#line18" class="location">framework\libs\smarty\sysplugins\smarty_internal_nocache_insert.php at line 18</a>

# Class Smarty_Internal_Nocache_Insert #

<pre class="tree">** Smarty_Internal_Nocache_Insert **\n</pre>

- - -

<p class="signature">public  class **Smarty_Internal_Nocache_Insert**</p>

<div class="comment" id="overview_description"><p>Smarty Internal Plugin Compile Insert Class</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>Compiler</dd>
</dl>
- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type">static  string</td>
<td class="description"><p class="name"><a href="#compile()">compile</a>(string _function, array _attr, <a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template, string _script, string _assign)</p><p class="description">Compiles code for the {insert} tag into cache file</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/libs/smarty/sysplugins/smarty_internal_nocache_insert.php.md#line30" class="location">framework\libs\smarty\sysplugins\smarty_internal_nocache_insert.php at line 30</a>

<h3 id="compile()">compile</h3>
```php
public static  string **compile**(string _function, array _attr, <a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template, string _script, string _assign)```
<div class="details">
<p>Compiles code for the {insert} tag into cache file</p><dl>
<dt>Parameters:</dt>
<dd>_function - insert function name</dd>
<dd>_attr - array with parameter</dd>
<dd>_template - template object</dd>
<dd>_script - script name to load or 'null'</dd>
<dd>_assign - optional variable name</dd>
<dt>Returns:</dt>
<dd>compiled code</dd>
</dl>
</div>

- - -

