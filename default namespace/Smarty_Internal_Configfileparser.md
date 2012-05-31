
- - -

**Default namespace\Smarty_Internal_Configfileparser**
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 87</div>
#Class Smarty_Internal_Configfileparser#

**Smarty_Internal_Configfileparser**


- - -

<p class="signature">public  class **Smarty_Internal_Configfileparser**</p>


- - -

<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td class="type"> mixed</td>
<td class="description"><p class="name"><a href="#retvalue">$retvalue</a></p></td>
</tr>
<tr>
<td class="type"> mixed</td>
<td class="description"><p class="name"><a href="#successful">$successful</a></p></td>
</tr>
<tr>
<td class="type">static  mixed</td>
<td class="description"><p class="name"><a href="#yyexpectedtokens">$yyExpectedTokens</a></p></td>
</tr>
<tr>
<td class="type">static  mixed</td>
<td class="description"><p class="name"><a href="#yyreducemap">$yyReduceMap</a></p></td>
</tr>
<tr>
<td class="type">static  mixed</td>
<td class="description"><p class="name"><a href="#yyruleinfo">$yyRuleInfo</a></p></td>
</tr>
<tr>
<td class="type">static  mixed</td>
<td class="description"><p class="name"><a href="#yyrulename">$yyRuleName</a></p></td>
</tr>
<tr>
<td class="type"> mixed</td>
<td class="description"><p class="name"><a href="#yytokenname">$yyTokenName</a></p></td>
</tr>
<tr>
<td class="type">static  mixed</td>
<td class="description"><p class="name"><a href="#yytracefile">$yyTraceFILE</a></p></td>
</tr>
<tr>
<td class="type">static  mixed</td>
<td class="description"><p class="name"><a href="#yytraceprompt">$yyTracePrompt</a></p></td>
</tr>
<tr>
<td class="type">static  mixed</td>
<td class="description"><p class="name"><a href="#yy_default">$yy_default</a></p></td>
</tr>
<tr>
<td class="type">static  mixed</td>
<td class="description"><p class="name"><a href="#yy_lookahead">$yy_lookahead</a></p></td>
</tr>
<tr>
<td class="type"> mixed</td>
<td class="description"><p class="name"><a href="#yyerrcnt">$yyerrcnt</a></p></td>
</tr>
<tr>
<td class="type"> mixed</td>
<td class="description"><p class="name"><a href="#yyidx">$yyidx</a></p></td>
</tr>
<tr>
<td class="type"> mixed</td>
<td class="description"><p class="name"><a href="#yystack">$yystack</a></p></td>
</tr>
</table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(mixed lex, mixed compiler)</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> static  void</td>
<td class="description"><p class="name"><a href="#instance">instance</a>(mixed new_instance)</p></td>
</tr>
<tr>
<td class="type"> static  void</td>
<td class="description"><p class="name"><a href="#printtrace">PrintTrace</a>()</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#tokenname">tokenName</a>(mixed tokenType)</p></td>
</tr>
<tr>
<td class="type"> static  void</td>
<td class="description"><p class="name"><a href="#yy_destructor">yy_destructor</a>(mixed yymajor, mixed yypminor)</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#yy_pop_parser_stack">yy_pop_parser_stack</a>()</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#yy_get_expected_tokens">yy_get_expected_tokens</a>(mixed token)</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#yy_is_expected_token">yy_is_expected_token</a>(mixed token)</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#yy_find_shift_action">yy_find_shift_action</a>(mixed iLookAhead)</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#yy_find_reduce_action">yy_find_reduce_action</a>(mixed stateno, mixed iLookAhead)</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#yy_shift">yy_shift</a>(mixed yyNewState, mixed yyMajor, mixed yypMinor)</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#yy_r0">yy_r0</a>()</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#yy_r1">yy_r1</a>()</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#yy_r4">yy_r4</a>()</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#yy_r5">yy_r5</a>()</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#yy_r6">yy_r6</a>()</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#yy_r7">yy_r7</a>()</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#yy_r8">yy_r8</a>()</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#yy_r9">yy_r9</a>()</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#yy_r10">yy_r10</a>()</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#yy_r11">yy_r11</a>()</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#yy_r12">yy_r12</a>()</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#yy_r13">yy_r13</a>()</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#yy_r14">yy_r14</a>()</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#yy_r15">yy_r15</a>()</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#yy_r16">yy_r16</a>()</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#yy_r17">yy_r17</a>()</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#yy_reduce">yy_reduce</a>(mixed yyruleno)</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#yy_parse_failed">yy_parse_failed</a>()</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#yy_syntax_error">yy_syntax_error</a>(mixed yymajor, mixed TOKEN)</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#yy_accept">yy_accept</a>()</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#doparse">doParse</a>(mixed yymajor, mixed yytokenvalue)</p></td>
</tr>
</table>

##Field Detail##
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 93</div>
<h3 id="retvalue">retvalue</h3>

public  mixed $retvalue = 0
<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 92</div>
<h3 id="successful">successful</h3>

public  mixed $successful = true
<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 185</div>
<h3 id="yyExpectedTokens">yyExpectedTokens</h3>

public static  mixed $yyExpectedTokens = array(...)
<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 493</div>
<h3 id="yyReduceMap">yyReduceMap</h3>

public static  mixed $yyReduceMap = array(...)
<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 491</div>
<h3 id="yyRuleInfo">yyRuleInfo</h3>

public static  mixed $yyRuleInfo = array(...)
<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 212</div>
<h3 id="yyRuleName">yyRuleName</h3>

public static  mixed $yyRuleName = array(...)
<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 210</div>
<h3 id="yyTokenName">yyTokenName</h3>

public  mixed $yyTokenName = array(...)
<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 204</div>
<h3 id="yyTraceFILE">yyTraceFILE</h3>

public static  mixed $yyTraceFILE
<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 205</div>
<h3 id="yyTracePrompt">yyTracePrompt</h3>

public static  mixed $yyTracePrompt
<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 186</div>
<h3 id="yy_default">yy_default</h3>

public static  mixed $yy_default = array(...)
<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 182</div>
<h3 id="yy_lookahead">yy_lookahead</h3>

public static  mixed $yy_lookahead = array(...)
<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 207</div>
<h3 id="yyerrcnt">yyerrcnt</h3>

public  mixed $yyerrcnt
<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 206</div>
<h3 id="yyidx">yyidx</h3>

public  mixed $yyidx
<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 208</div>
<h3 id="yystack">yystack</h3>

public  mixed $yystack = array()
<div class="details">
</div>

- - -

<h2 id="detail_method">Constructor Detail</h2>
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 97</div>
<h3 id="__construct()">__construct</h3>

```php
public  void **__construct**(mixed lex, mixed compiler)
```
<div class="details">
</div>

- - -

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 104</div>
<h3 id="instance()">instance</h3>

public static  void **instance** (mixed new_instance)<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 198</div>
<h3 id="PrintTrace()">PrintTrace</h3>

public static  void **PrintTrace** ()<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 214</div>
<h3 id="tokenName()">tokenName</h3>

public  void **tokenName** (mixed tokenType)<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 226</div>
<h3 id="yy_destructor()">yy_destructor</h3>

public static  void **yy_destructor** (mixed yymajor, mixed yypminor)<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 233</div>
<h3 id="yy_pop_parser_stack()">yy_pop_parser_stack</h3>

public  void **yy_pop_parser_stack** ()<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 260</div>
<h3 id="yy_get_expected_tokens()">yy_get_expected_tokens</h3>

public  void **yy_get_expected_tokens** (mixed token)<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 328</div>
<h3 id="yy_is_expected_token()">yy_is_expected_token</h3>

public  void **yy_is_expected_token** (mixed token)<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 399</div>
<h3 id="yy_find_shift_action()">yy_find_shift_action</h3>

public  void **yy_find_shift_action** (mixed iLookAhead)<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 433</div>
<h3 id="yy_find_reduce_action()">yy_find_reduce_action</h3>

public  void **yy_find_reduce_action** (mixed stateno, mixed iLookAhead)<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 456</div>
<h3 id="yy_shift()">yy_shift</h3>

public  void **yy_shift** (mixed yyNewState, mixed yyMajor, mixed yypMinor)<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 495</div>
<h3 id="yy_r0()">yy_r0</h3>

public  void **yy_r0** ()<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 500</div>
<h3 id="yy_r1()">yy_r1</h3>

public  void **yy_r1** ()<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 505</div>
<h3 id="yy_r4()">yy_r4</h3>

public  void **yy_r4** ()<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 511</div>
<h3 id="yy_r5()">yy_r5</h3>

public  void **yy_r5** ()<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 519</div>
<h3 id="yy_r6()">yy_r6</h3>

public  void **yy_r6** ()<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 524</div>
<h3 id="yy_r7()">yy_r7</h3>

public  void **yy_r7** ()<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 529</div>
<h3 id="yy_r8()">yy_r8</h3>

public  void **yy_r8** ()<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 534</div>
<h3 id="yy_r9()">yy_r9</h3>

public  void **yy_r9** ()<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 539</div>
<h3 id="yy_r10()">yy_r10</h3>

public  void **yy_r10** ()<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 544</div>
<h3 id="yy_r11()">yy_r11</h3>

public  void **yy_r11** ()<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 549</div>
<h3 id="yy_r12()">yy_r12</h3>

public  void **yy_r12** ()<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 554</div>
<h3 id="yy_r13()">yy_r13</h3>

public  void **yy_r13** ()<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 559</div>
<h3 id="yy_r14()">yy_r14</h3>

public  void **yy_r14** ()<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 564</div>
<h3 id="yy_r15()">yy_r15</h3>

public  void **yy_r15** ()<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 569</div>
<h3 id="yy_r16()">yy_r16</h3>

public  void **yy_r16** ()<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 574</div>
<h3 id="yy_r17()">yy_r17</h3>

public  void **yy_r17** ()<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 581</div>
<h3 id="yy_reduce()">yy_reduce</h3>

public  void **yy_reduce** (mixed yyruleno)<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 622</div>
<h3 id="yy_parse_failed()">yy_parse_failed</h3>

public  void **yy_parse_failed** ()<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 632</div>
<h3 id="yy_syntax_error()">yy_syntax_error</h3>

public  void **yy_syntax_error** (mixed yymajor, mixed TOKEN)<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 642</div>
<h3 id="yy_accept()">yy_accept</h3>

public  void **yy_accept** ()<div class="details">
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_configfileparser.php at line 659</div>
<h3 id="doParse()">doParse</h3>

public  void **doParse** (mixed yymajor, mixed yytokenvalue)<div class="details">
</div>

- - -

