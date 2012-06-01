

- - -

**Smarty\_smarty_doublequoted**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_parsetree.php#L133" >framework\libs\smarty\sysplugins\smarty_internal_parsetree.php at line 133</a>

#Class _smarty_doublequoted#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/_smarty_parsetree.md">_smarty_parsetree</a>
    * **_smarty_doublequoted**




- - -

<p class="signature"><span class='k'>public  class</span> <span class='nx'>_smarty_doublequoted</span>
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/_smarty_parsetree.md">_smarty_parsetree</a>

</p>

<div class="comment" id="overview_description"><p>Double quoted string inside a tag.</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>Compiler</dd>
<dt>Ignore.</dt>
</dl>


- - -

<table class="inherit">
<tr><th colspan="2">Fields inherited from Smarty\_smarty_parsetree</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/_smarty_parsetree.md">data</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/_smarty_parsetree.md">parser</a></td></tr></table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(object parser, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/_smarty_parsetree.md">_smarty_parsetree</a> subtree)</p><p class="description">Create parse tree buffer for double quoted string subtrees</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#append_subtree">append_subtree</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/_smarty_parsetree.md">_smarty_parsetree</a> subtree)</p><p class="description">Append buffer to subtree</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#to_smarty_php">to_smarty_php</a>()</p><p class="description">Merge subtree buffer content together</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\_smarty_parsetree</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/_smarty_parsetree.md">to_smarty_php</a></td></tr></table>

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_parsetree.php#L141" >framework\libs\smarty\sysplugins\smarty_internal_parsetree.php at line 141</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (object parser, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/_smarty_parsetree.md">_smarty_parsetree</a> subtree)

<div class="details">
<p>Create parse tree buffer for double quoted string subtrees</p><dl>
<dt>Parameters:</dt>
<dd>parser - parser object</dd>
<dd>subtree - parsetree buffer</dd>
</dl>

</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_parsetree.php#L155" >framework\libs\smarty\sysplugins\smarty_internal_parsetree.php at line 155</a>

<h3 id="append_subtree()">append_subtree</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>append_subtree</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/_smarty_parsetree.md">_smarty_parsetree</a> subtree)

<div class="details">
<p>Append buffer to subtree</p><dl>
<dt>Parameters:</dt>
<dd>subtree - parsetree buffer</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_parsetree.php#L179" >framework\libs\smarty\sysplugins\smarty_internal_parsetree.php at line 179</a>

<h3 id="to_smarty_php()">to_smarty_php</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>to_smarty_php</span> ()

<div class="details">
<p>Merge subtree buffer content together</p><dl>
<dt>Returns:</dt>
<dd>compiled template code</dd>
</dl>

</div>

- - -

