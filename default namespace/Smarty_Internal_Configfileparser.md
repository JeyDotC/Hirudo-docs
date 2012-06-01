

- - -

**Default namespace\Smarty_Internal_Configfileparser**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_configfileparser.php#L87" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 87</a>

#Class Smarty_Internal_Configfileparser#

**Smarty_Internal_Configfileparser**




- - -

<p><strong>public  class</strong> <span>Smarty_Internal_Configfileparser</span></p>



- - -



<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="#retvalue"> $retvalue</a>
                                </p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="#successful"> $successful</a>
                                </p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="#yyExpectedTokens"> $yyExpectedTokens</a>
                                </p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="#yyReduceMap"> $yyReduceMap</a>
                                </p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="#yyRuleInfo"> $yyRuleInfo</a>
                                </p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="#yyRuleName"> $yyRuleName</a>
                                </p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="#yyTokenName"> $yyTokenName</a>
                                </p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="#yyTraceFILE"> $yyTraceFILE</a>
                                </p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="#yyTracePrompt"> $yyTracePrompt</a>
                                </p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="#yy_default"> $yy_default</a>
                                </p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="#yy_lookahead"> $yy_lookahead</a>
                                </p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="#yyerrcnt"> $yyerrcnt</a>
                                </p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="#yyidx"> $yyidx</a>
                                </p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="#yystack"> $yystack</a>
                                </p></td>
</tr>
</table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(mixed lex, mixed compiler)</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#instance">instance</a>(mixed new_instance)</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#printtrace">PrintTrace</a>()</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#tokenname">tokenName</a>(mixed tokenType)</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#yy_destructor">yy_destructor</a>(mixed yymajor, mixed yypminor)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#yy_pop_parser_stack">yy_pop_parser_stack</a>()</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#yy_get_expected_tokens">yy_get_expected_tokens</a>(mixed token)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#yy_is_expected_token">yy_is_expected_token</a>(mixed token)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#yy_find_shift_action">yy_find_shift_action</a>(mixed iLookAhead)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#yy_find_reduce_action">yy_find_reduce_action</a>(mixed stateno, mixed iLookAhead)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#yy_shift">yy_shift</a>(mixed yyNewState, mixed yyMajor, mixed yypMinor)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#yy_r0">yy_r0</a>()</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#yy_r1">yy_r1</a>()</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#yy_r4">yy_r4</a>()</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#yy_r5">yy_r5</a>()</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#yy_r6">yy_r6</a>()</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#yy_r7">yy_r7</a>()</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#yy_r8">yy_r8</a>()</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#yy_r9">yy_r9</a>()</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#yy_r10">yy_r10</a>()</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#yy_r11">yy_r11</a>()</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#yy_r12">yy_r12</a>()</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#yy_r13">yy_r13</a>()</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#yy_r14">yy_r14</a>()</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#yy_r15">yy_r15</a>()</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#yy_r16">yy_r16</a>()</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#yy_r17">yy_r17</a>()</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#yy_reduce">yy_reduce</a>(mixed yyruleno)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#yy_parse_failed">yy_parse_failed</a>()</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#yy_syntax_error">yy_syntax_error</a>(mixed yymajor, mixed TOKEN)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#yy_accept">yy_accept</a>()</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#doparse">doParse</a>(mixed yymajor, mixed yytokenvalue)</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_configfileparser.php#L97" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 97</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (mixed lex, mixed compiler)

<div class="details">

</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_configfileparser.php#L104" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 104</a>

<h3 id="instance()">instance</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>instance</span> (mixed new_instance)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_configfileparser.php#L198" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 198</a>

<h3 id="PrintTrace()">PrintTrace</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>PrintTrace</span> ()

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_configfileparser.php#L214" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 214</a>

<h3 id="tokenName()">tokenName</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>tokenName</span> (mixed tokenType)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_configfileparser.php#L226" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 226</a>

<h3 id="yy_destructor()">yy_destructor</h3>
<span class='k'>static </span> <span class='nx'>void</span> <span class='nf'>yy_destructor</span> (mixed yymajor, mixed yypminor)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_configfileparser.php#L233" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 233</a>

<h3 id="yy_pop_parser_stack()">yy_pop_parser_stack</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>yy_pop_parser_stack</span> ()

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_configfileparser.php#L260" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 260</a>

<h3 id="yy_get_expected_tokens()">yy_get_expected_tokens</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>yy_get_expected_tokens</span> (mixed token)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_configfileparser.php#L328" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 328</a>

<h3 id="yy_is_expected_token()">yy_is_expected_token</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>yy_is_expected_token</span> (mixed token)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_configfileparser.php#L399" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 399</a>

<h3 id="yy_find_shift_action()">yy_find_shift_action</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>yy_find_shift_action</span> (mixed iLookAhead)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_configfileparser.php#L433" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 433</a>

<h3 id="yy_find_reduce_action()">yy_find_reduce_action</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>yy_find_reduce_action</span> (mixed stateno, mixed iLookAhead)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_configfileparser.php#L456" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 456</a>

<h3 id="yy_shift()">yy_shift</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>yy_shift</span> (mixed yyNewState, mixed yyMajor, mixed yypMinor)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_configfileparser.php#L495" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 495</a>

<h3 id="yy_r0()">yy_r0</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>yy_r0</span> ()

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_configfileparser.php#L500" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 500</a>

<h3 id="yy_r1()">yy_r1</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>yy_r1</span> ()

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_configfileparser.php#L505" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 505</a>

<h3 id="yy_r4()">yy_r4</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>yy_r4</span> ()

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_configfileparser.php#L511" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 511</a>

<h3 id="yy_r5()">yy_r5</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>yy_r5</span> ()

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_configfileparser.php#L519" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 519</a>

<h3 id="yy_r6()">yy_r6</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>yy_r6</span> ()

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_configfileparser.php#L524" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 524</a>

<h3 id="yy_r7()">yy_r7</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>yy_r7</span> ()

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_configfileparser.php#L529" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 529</a>

<h3 id="yy_r8()">yy_r8</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>yy_r8</span> ()

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_configfileparser.php#L534" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 534</a>

<h3 id="yy_r9()">yy_r9</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>yy_r9</span> ()

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_configfileparser.php#L539" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 539</a>

<h3 id="yy_r10()">yy_r10</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>yy_r10</span> ()

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_configfileparser.php#L544" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 544</a>

<h3 id="yy_r11()">yy_r11</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>yy_r11</span> ()

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_configfileparser.php#L549" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 549</a>

<h3 id="yy_r12()">yy_r12</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>yy_r12</span> ()

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_configfileparser.php#L554" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 554</a>

<h3 id="yy_r13()">yy_r13</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>yy_r13</span> ()

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_configfileparser.php#L559" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 559</a>

<h3 id="yy_r14()">yy_r14</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>yy_r14</span> ()

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_configfileparser.php#L564" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 564</a>

<h3 id="yy_r15()">yy_r15</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>yy_r15</span> ()

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_configfileparser.php#L569" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 569</a>

<h3 id="yy_r16()">yy_r16</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>yy_r16</span> ()

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_configfileparser.php#L574" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 574</a>

<h3 id="yy_r17()">yy_r17</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>yy_r17</span> ()

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_configfileparser.php#L581" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 581</a>

<h3 id="yy_reduce()">yy_reduce</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>yy_reduce</span> (mixed yyruleno)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_configfileparser.php#L622" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 622</a>

<h3 id="yy_parse_failed()">yy_parse_failed</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>yy_parse_failed</span> ()

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_configfileparser.php#L632" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 632</a>

<h3 id="yy_syntax_error()">yy_syntax_error</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>yy_syntax_error</span> (mixed yymajor, mixed TOKEN)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_configfileparser.php#L642" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 642</a>

<h3 id="yy_accept()">yy_accept</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>yy_accept</span> ()

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_configfileparser.php#L659" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 659</a>

<h3 id="doParse()">doParse</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>doParse</span> (mixed yymajor, mixed yytokenvalue)

<div class="details">

</div>

- - -

