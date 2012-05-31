- - -

**Smarty\Smarty_Internal_Filter_Handler**
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_filter_handler.php at line 18</div>
#Class Smarty_Internal_Filter_Handler#

**Smarty_Internal_Filter_Handler**


- - -

<p class="signature">public  class **Smarty_Internal_Filter_Handler**</p>

<div class="comment" id="overview_description"><p>Class for filter processing</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>PluginsInternal</dd>
</dl>
- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type">static  string</td>
<td class="description"><p class="name"><a href="#runFilter">runFilter</a>(string type, string content, <a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> template)</p><p class="description">Run filters over contentThe filters will be lazy loaded if required
class name format: Smarty_FilterType_FilterName
plugin filename format: filtertype.filtername.php
Smarty2 filter plugins could be used</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_filter_handler.php at line 33</div>
<h3 id="runFilter()">runFilter</h3>

```php
public static  string **runFilter**(string type, string content, <a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> template)
```
<div class="details">
<p>Run filters over content</p><p>The filters will be lazy loaded if required
class name format: Smarty_FilterType_FilterName
plugin filename format: filtertype.filtername.php
Smarty2 filter plugins could be used</p><dl>
<dt>Parameters:</dt>
<dd>type - the type of filter ('pre','post','output') which shall run</dd>
<dd>content - the content which shall be processed by the filters</dd>
<dd>template - template object</dd>
<dt>Returns:</dt>
<dd>the filtered content</dd>
</dl>
</div>

- - -

