

- - -

**Smarty\Smarty_Internal_Filter_Handler**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_filter_handler.php#L18" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_filter_handler.php at line 18</a>

#Class Smarty_Internal_Filter_Handler#

**Smarty_Internal_Filter_Handler**




- - -

<p><strong>public  class</strong> <span>Smarty_Internal_Filter_Handler</span></p>

<div class="comment" id="overview_description"><p>Class for filter processing</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>PluginsInternal</dd>
</dl>


- - -

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#runfilter">runFilter</a>(string type, string content, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> template)</p><p class="description">Run filters over contentThe filters will be lazy loaded if required
class name format: Smarty_FilterType_FilterName
plugin filename format: filtertype.filtername.php
Smarty2 filter plugins could be used</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_filter_handler.php#L33" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_filter_handler.php at line 33</a>

<h3 id="runFilter()">runFilter</h3>
<span class='k'>static </span> <span class='nx'>string</span> <span class='nf'>runFilter</span> (string type, string content, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> template)

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

