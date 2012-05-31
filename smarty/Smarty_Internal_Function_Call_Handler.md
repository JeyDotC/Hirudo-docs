- - -

**Smarty\Smarty_Internal_Function_Call_Handler**
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_function_call_handler.php at line 16</div>
#Class Smarty_Internal_Function_Call_Handler#

**Smarty_Internal_Function_Call_Handler**


- - -

<p class="signature">public  class **Smarty_Internal_Function_Call_Handler**</p>

<div class="comment" id="overview_description"><p>This class does call function defined with the {function} tag</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>PluginsInternal</dd>
</dl>
- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type">static  void</td>
<td class="description"><p class="name"><a href="#call">call</a>(string _name, <a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template, array _params, string _hash, bool _nocache)</p><p class="description">This function handles calls to template functions defined by {function}
It does create a PHP function at the first call</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_function_call_handler.php at line 28</div>
<h3 id="call()">call</h3>
```php
public static  void **call**(string _name, <a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template, array _params, string _hash, bool _nocache)```
<div class="details">
<p>This function handles calls to template functions defined by {function}
It does create a PHP function at the first call</p><dl>
<dt>Parameters:</dt>
<dd>_name - template function name</dd>
<dd>_template - template object</dd>
<dd>_params - Smarty variables passed as call parameter</dd>
<dd>_hash - nocache hash value</dd>
<dd>_nocache - nocache flag</dd>
</dl>
</div>

- - -

