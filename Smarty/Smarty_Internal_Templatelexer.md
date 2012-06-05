

- - -

**Smarty\Smarty_Internal_Templatelexer**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L13" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 13</a>

#Class Smarty_Internal_Templatelexer#

**Smarty_Internal_Templatelexer**




- - -

<p><strong>public  class</strong> <span>Smarty_Internal_Templatelexer</span></p>

<div class="comment" id="overview_description"><p>Smarty Internal Plugin Templatelexer</p></div>



<hr />



<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Templatelexer.md#counter"> $counter</a>
                                </p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Templatelexer.md#data"> $data</a>
                                </p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Templatelexer.md#line"> $line</a>
                                </p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Templatelexer.md#node"> $node</a>
                                </p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Templatelexer.md#smarty_token_names"> $smarty_token_names</a>
                                </p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Templatelexer.md#state"> $state</a>
                                </p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Templatelexer.md#taglineno"> $taglineno</a>
                                </p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Templatelexer.md#token"> $token</a>
                                </p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Smarty/Smarty_Internal_Templatelexer.md#value"> $value</a>
                                </p></td>
</tr>
</table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(mixed data, mixed compiler)</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#yylex">yylex</a>()</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#yypushstate">yypushstate</a>(mixed state)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#yypopstate">yypopstate</a>()</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#yybegin">yybegin</a>(mixed state)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#yylex1">yylex1</a>()</p></td>
</tr>
</table>

##Field Detail##

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L16" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 16</a>

<h3 id="counter">counter</h3>
<span class='k'></span> <span class='nx'>mixed</span><span class='no'> $counter</span><div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L15" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 15</a>

<h3 id="data">data</h3>
<span class='k'></span> <span class='nx'>mixed</span><span class='no'> $data</span><span class='o'> = null</span>

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L20" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 20</a>

<h3 id="line">line</h3>
<span class='k'></span> <span class='nx'>mixed</span><span class='no'> $line</span><div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L19" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 19</a>

<h3 id="node">node</h3>
<span class='k'></span> <span class='nx'>mixed</span><span class='no'> $node</span><div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L24" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 24</a>

<h3 id="smarty_token_names">smarty_token_names</h3>
<span class='k'></span> <span class='nx'>mixed</span><span class='no'> $smarty_token_names</span><span class='o'> = array(...)</span>

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L22" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 22</a>

<h3 id="state">state</h3>
<span class='k'></span> <span class='nx'>mixed</span><span class='no'> $state</span><span class='o'> = 1</span>

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L21" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 21</a>

<h3 id="taglineno">taglineno</h3>
<span class='k'></span> <span class='nx'>mixed</span><span class='no'> $taglineno</span><div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L17" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 17</a>

<h3 id="token">token</h3>
<span class='k'></span> <span class='nx'>mixed</span><span class='no'> $token</span><div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L18" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 18</a>

<h3 id="value">value</h3>
<span class='k'></span> <span class='nx'>mixed</span><span class='no'> $value</span><div class="details">

</div>

- - -

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L27" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 27</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (mixed data, mixed compiler)

<div class="details">

</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L47" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 47</a>

<h3 id="yylex()">yylex</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>yylex</span> ()

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L52" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 52</a>

<h3 id="yypushstate()">yypushstate</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>yypushstate</span> (mixed state)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L58" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 58</a>

<h3 id="yypopstate()">yypopstate</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>yypopstate</span> ()

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L63" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 63</a>

<h3 id="yybegin()">yybegin</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>yybegin</span> (mixed state)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L70" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 70</a>

<h3 id="yylex1()">yylex1</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>yylex1</span> ()

<div class="details">

</div>

- - -

