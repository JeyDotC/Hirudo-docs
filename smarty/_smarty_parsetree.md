

- - -

**Smarty\_smarty_parsetree**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_parsetree.php#L18" >framework\libs\smarty\sysplugins\smarty_internal_parsetree.php at line 18</a>

#Class _smarty_parsetree#

**_smarty_parsetree**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="">_smarty_code</a> <a href="">_smarty_doublequoted</a> <a href="">_smarty_dq_content</a> <a href="">_smarty_linebreak</a> <a href="">_smarty_tag</a> <a href="">_smarty_template_buffer</a> <a href="">_smarty_text</a> </dd>
</dl>



- - -

<p class="signature"><span class='k'>public abstract  class</span> <span class='nx'>_smarty_parsetree</span></p>

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
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="#data"> $data</a>
                                </p><p class="description">Buffer content</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>object</span></td>
<td class="description"><p class="name" ><a href="#parser"> $parser</a>
                                </p><p class="description">Parser object</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'>abstract </span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#to_smarty_php">to_smarty_php</a>()</p><p class="description">Return buffer</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_parsetree.php#L36" >framework\libs\smarty\sysplugins\smarty_internal_parsetree.php at line 36</a>

<h3 id="to_smarty_php()">to_smarty_php</h3>
<span class='k'>abstract </span> <span class='nx'>string</span> <span class='nf'>to_smarty_php</span> ()

<div class="details">
<p>Return buffer</p><dl>
<dt>Returns:</dt>
<dd>buffer content</dd>
</dl>

</div>

- - -

