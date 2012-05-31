
- - -

**Smarty\_smarty_parsetree**
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_parsetree.php at line 18</div>
#Class _smarty_parsetree#

**_smarty_parsetree**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/_smarty_code.html">_smarty_code</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/_smarty_doublequoted.html">_smarty_doublequoted</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/_smarty_dq_content.html">_smarty_dq_content</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/_smarty_linebreak.html">_smarty_linebreak</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/_smarty_tag.html">_smarty_tag</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/_smarty_template_buffer.html">_smarty_template_buffer</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/_smarty_text.html">_smarty_text</a> </dd>
</dl>

- - -

<p class="signature">public abstract  class **_smarty_parsetree**</p>

<div class="comment" id="overview_description"><p></p></div>

<dl>
<dt>Subpackage:</dt>
<dd>Compiler</dd>
<dt>Ignore.</dt>
</dl>

- - -

<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td class="type"> mixed</td>
<td class="description"><p class="name"><a href="#data">$data</a></p><p class="description">Buffer content</p></td>
</tr>
<tr>
<td class="type"> object</td>
<td class="description"><p class="name"><a href="#parser">$parser</a></p><p class="description">Parser object</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> abstract  string</td>
<td class="description"><p class="name"><a href="#to_smarty_php">to_smarty_php</a>()</p><p class="description">Return buffer</p></td>
</tr>
</table>

##Field Detail##
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_parsetree.php at line 29</div>
<h3 id="data">data</h3>

public  mixed $data
<div class="details">
<p>Buffer content</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_parsetree.php at line 24</div>
<h3 id="parser">parser</h3>

public  object $parser = null
<div class="details">
<p>Parser object</p></div>

- - -

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_parsetree.php at line 36</div>
<h3 id="to_smarty_php()">to_smarty_php</h3>

public abstract  string **to_smarty_php** ()<div class="details">
<p>Return buffer</p><dl>
<dt>Returns:</dt>
<dd>buffer content</dd>
</dl>
</div>

- - -

