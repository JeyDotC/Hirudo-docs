

- - -

**Smarty\_smarty_code**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_parsetree.php#L99" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_parsetree.php at line 99</a>

#Class _smarty_code#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/_smarty_parsetree.md">_smarty_parsetree</a>
    * **_smarty_code**




- - -

<p><strong>public  class</strong> <span>_smarty_code</span>
<strong>extends</strong> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/_smarty_parsetree.md">_smarty_parsetree</a>

</p>

<div class="comment" id="overview_description"><p>Code fragment inside a tag.</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>Compiler</dd>
<dt>Ignore.</dt>
</dl>


- - -

<table class="inherit">
<tr><th colspan="2">Fields inherited from Smarty\_smarty_parsetree</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/_smarty_parsetree.md#data">data</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/_smarty_parsetree.md#parser">parser</a></td></tr></table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(object parser, string data)</p><p class="description">Create parse tree buffer for code fragment</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#to_smarty_php">to_smarty_php</a>()</p><p class="description">Return buffer content in parentheses</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\_smarty_parsetree</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/_smarty_parsetree.md#to_smarty_php">to_smarty_php</a></td></tr></table>

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_parsetree.php#L108" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_parsetree.php at line 108</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (object parser, string data)

<div class="details">
<p>Create parse tree buffer for code fragment</p><dl>
<dt>Parameters:</dt>
<dd>parser - parser object</dd>
<dd>data - content</dd>
</dl>

</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_parsetree.php#L119" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_parsetree.php at line 119</a>

<h3 id="to_smarty_php()">to_smarty_php</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>to_smarty_php</span> ()

<div class="details">
<p>Return buffer content in parentheses</p><dl>
<dt>Returns:</dt>
<dd>content</dd>
</dl>

</div>

- - -

