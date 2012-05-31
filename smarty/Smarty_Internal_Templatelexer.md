
- - -

**Smarty\Smarty_Internal_Templatelexer**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L13 class="location">framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 13</a>

#Class Smarty_Internal_Templatelexer#

**Smarty_Internal_Templatelexer**




- - -

<p class="signature">public  class **Smarty_Internal_Templatelexer**</p>

<div class="comment" id="overview_description"><p>Smarty Internal Plugin Templatelexer</p></div>



- - -



<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="#counter"> $counter</a>
                                </p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="#data"> $data</a>
                                </p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="#line"> $line</a>
                                </p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="#node"> $node</a>
                                </p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="#smarty_token_names"> $smarty_token_names</a>
                                </p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="#state"> $state</a>
                                </p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="#taglineno"> $taglineno</a>
                                </p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="#token"> $token</a>
                                </p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="#value"> $value</a>
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

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L27 class="location">framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 27</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (mixed data, mixed compiler)

<div class="details">
</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L47 class="location">framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 47</a>

<h3 id="yylex()">yylex</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>yylex</span> ()

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L52 class="location">framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 52</a>

<h3 id="yypushstate()">yypushstate</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>yypushstate</span> (mixed state)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L58 class="location">framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 58</a>

<h3 id="yypopstate()">yypopstate</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>yypopstate</span> ()

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L63 class="location">framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 63</a>

<h3 id="yybegin()">yybegin</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>yybegin</span> (mixed state)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_templatelexer.php#L70 class="location">framework\libs\smarty\sysplugins\smarty_internal_templatelexer.php at line 70</a>

<h3 id="yylex1()">yylex1</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>yylex1</span> ()

<div class="details">
</div>

- - -

