

- - -

**Smarty\_smarty_tag**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_parsetree.php#L47" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_parsetree.php at line 47</a>

#Class _smarty_tag#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/_smarty_parsetree.md">_smarty_parsetree</a>
 &gt; **_smarty_tag**




- - -

<p><strong>public  class</strong> <span>_smarty_tag</span>
<strong>extends</strong> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/_smarty_parsetree.md">_smarty_parsetree</a>

</p>

<div class="comment" id="overview_description"><p>A complete smarty tag.</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>Compiler</dd>
<dt>Ignore.</dt>
</dl>


<hr />



<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>int</span></td>
<td class="description"><p class="name" ><a href="#saved_block_nesting"> $saved_block_nesting</a>
                                </p><p class="description">Saved block nesting level</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Fields inherited from Smarty\_smarty_parsetree</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/_smarty_parsetree.md#data">data</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/_smarty_parsetree.md#parser">parser</a></td></tr></table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(object parser, string data)</p><p class="description">Create parse tree buffer for Smarty tag</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#to_smarty_php">to_smarty_php</a>()</p><p class="description">Return buffer content</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#assign_to_var">assign_to_var</a>()</p><p class="description">Return complied code that loads the evaluated outout of buffer content into a temporary variable</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\_smarty_parsetree</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/_smarty_parsetree.md#to_smarty_php">to_smarty_php</a></td></tr></table>

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_parsetree.php#L61" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_parsetree.php at line 61</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (object parser, string data)

<div class="details">
<p>Create parse tree buffer for Smarty tag</p><dl>
<dt>Parameters:</dt>
<dd>parser - parser object</dd>
<dd>data - content</dd>
</dl>

</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_parsetree.php#L73" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_parsetree.php at line 73</a>

<h3 id="to_smarty_php()">to_smarty_php</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>to_smarty_php</span> ()

<div class="details">
<p>Return buffer content</p><dl>
<dt>Returns:</dt>
<dd>content</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_parsetree.php#L83" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_parsetree.php at line 83</a>

<h3 id="assign_to_var()">assign_to_var</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>assign_to_var</span> ()

<div class="details">
<p>Return complied code that loads the evaluated outout of buffer content into a temporary variable</p><dl>
<dt>Returns:</dt>
<dd>template code</dd>
</dl>

</div>

- - -

