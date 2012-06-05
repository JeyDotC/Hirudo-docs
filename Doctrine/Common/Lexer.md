

- - -

**Doctrine\Common\Lexer**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Lexer.php#L32" target='_blank'>framework\libs\doctrine-common\Doctrine\Common\Lexer.php at line 32</a>

#Class Lexer#

**Lexer**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Doctrine/Common/Annotations/DocLexer.md">Doctrine\Common\Annotations\DocLexer</a> </dd>
</dl>



- - -

<p><strong>public abstract  class</strong> <span>Lexer</span></p>

<div class="comment" id="overview_description"><p>Base class for writing simple lexers, i.e. for creating small DSLs.</p></div>

<dl>
<dt>Since:</dt>
<dd>2.0</dd>
<dt>Author:</dt>
<dd>Guilherme Blanco <guilhermeblanco@hotmail.com></dd>
<dd>Jonathan Wage <jonwage@gmail.com></dd>
<dd>Roman Borschel <roman@code-factory.org></dd>
<dt>Todo:</dt>
<dd>Rename: AbstractLexer</dd>
</dl>


<hr />



<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>array The next token in the input.</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Doctrine/Common/Lexer.md#lookahead"> $lookahead</a>
                                </p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array The last matched/seen token.</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Doctrine/Common/Lexer.md#token"> $token</a>
                                </p><p class="description"></p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setinput">setInput</a>(string input)</p><p class="description">Sets the input data to be tokenized.
</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#reset">reset</a>()</p><p class="description">Resets the lexer.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#resetpeek">resetPeek</a>()</p><p class="description">Resets the peek pointer to 0.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#resetposition">resetPosition</a>(integer position)</p><p class="description">Resets the lexer position on the input to the given position.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#isnexttoken">isNextToken</a>(integer|string token)</p><p class="description">Checks whether a given token matches the current lookahead.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#isnexttokenany">isNextTokenAny</a>(array tokens)</p><p class="description">Checks whether any of the given tokens matches the current lookahead</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array|null</span></td>
<td class="description"><p class="name"><a href="#movenext">moveNext</a>()</p><p class="description">Moves to the next token in the input string.
</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#skipuntil">skipUntil</a>($type The, mixed type)</p><p class="description">Tells the lexer to skip input tokens until it sees a token with the given value.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#isa">isA</a>(mixed value, integer token)</p><p class="description">Checks if given value is identical to the given token</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name"><a href="#peek">peek</a>()</p><p class="description">Moves the lookahead token forward.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array|null</span></td>
<td class="description"><p class="name"><a href="#glimpse">glimpse</a>()</p><p class="description">Peeks at the next token, returns it and immediately resets the peek.</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#scan">scan</a>(string input)</p><p class="description">Scans the input string for tokens.</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getliteral">getLiteral</a>(integer token)</p><p class="description">Gets the literal for a given token.</p></td>
</tr>
<tr>
<td><span class='k'>protected abstract </span> <span class='nx'>array</span></td>
<td class="description"><p class="name"><a href="#getcatchablepatterns">getCatchablePatterns</a>()</p><p class="description">Lexical catchable patterns.</p></td>
</tr>
<tr>
<td><span class='k'>protected abstract </span> <span class='nx'>array</span></td>
<td class="description"><p class="name"><a href="#getnoncatchablepatterns">getNonCatchablePatterns</a>()</p><p class="description">Lexical non-catchable patterns.</p></td>
</tr>
<tr>
<td><span class='k'>protected abstract </span> <span class='nx'>integer</span></td>
<td class="description"><p class="name"><a href="#gettype">getType</a>(string value)</p><p class="description">Retrieve token type. </p></td>
</tr>
</table>

##Field Detail##

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Lexer.php#L52" target='_blank'>framework\libs\doctrine-common\Doctrine\Common\Lexer.php at line 52</a>

<h3 id="lookahead">lookahead</h3>
<span class='k'></span> <span class='nx'>array The next token in the input.</span><span class='no'> $lookahead</span><div class="details">
<p></p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Lexer.php#L57" target='_blank'>framework\libs\doctrine-common\Doctrine\Common\Lexer.php at line 57</a>

<h3 id="token">token</h3>
<span class='k'></span> <span class='nx'>array The last matched/seen token.</span><span class='no'> $token</span><div class="details">
<p></p>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Lexer.php#L67" target='_blank'>framework\libs\doctrine-common\Doctrine\Common\Lexer.php at line 67</a>

<h3 id="setInput()">setInput</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setInput</span> (string input)

<div class="details">
<p>Sets the input data to be tokenized.</p><p>The Lexer is immediately reset and the new input tokenized.
Any unprocessed tokens from any previous input are lost.</p><dl>
<dt>Parameters:</dt>
<dd>input - The input to be tokenized.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Lexer.php#L76" target='_blank'>framework\libs\doctrine-common\Doctrine\Common\Lexer.php at line 76</a>

<h3 id="reset()">reset</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>reset</span> ()

<div class="details">
<p>Resets the lexer.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Lexer.php#L86" target='_blank'>framework\libs\doctrine-common\Doctrine\Common\Lexer.php at line 86</a>

<h3 id="resetPeek()">resetPeek</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>resetPeek</span> ()

<div class="details">
<p>Resets the peek pointer to 0.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Lexer.php#L95" target='_blank'>framework\libs\doctrine-common\Doctrine\Common\Lexer.php at line 95</a>

<h3 id="resetPosition()">resetPosition</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>resetPosition</span> (integer position)

<div class="details">
<p>Resets the lexer position on the input to the given position.</p><dl>
<dt>Parameters:</dt>
<dd>position - Position to place the lexical scanner</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Lexer.php#L105" target='_blank'>framework\libs\doctrine-common\Doctrine\Common\Lexer.php at line 105</a>

<h3 id="isNextToken()">isNextToken</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>isNextToken</span> (integer|string token)

<div class="details">
<p>Checks whether a given token matches the current lookahead.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Lexer.php#L115" target='_blank'>framework\libs\doctrine-common\Doctrine\Common\Lexer.php at line 115</a>

<h3 id="isNextTokenAny()">isNextTokenAny</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>isNextTokenAny</span> (array tokens)

<div class="details">
<p>Checks whether any of the given tokens matches the current lookahead</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Lexer.php#L130" target='_blank'>framework\libs\doctrine-common\Doctrine\Common\Lexer.php at line 130</a>

<h3 id="moveNext()">moveNext</h3>
<span class='k'></span> <span class='nx'>array|null</span> <span class='nf'>moveNext</span> ()

<div class="details">
<p>Moves to the next token in the input string.</p><p>A token is an associative array containing three items:</p>
<ul>
<li>'value'    : the string value of the token in the input string</li>
<li>'type'     : the type of the token (identifier, numeric, string, input
parameter, none)</li>
</ul>
<p>- 'position' : the position of the token in the input string</p><dl>
<dt>Returns:</dt>
<dd>the next token; null if there is no more tokens left</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Lexer.php#L143" target='_blank'>framework\libs\doctrine-common\Doctrine\Common\Lexer.php at line 143</a>

<h3 id="skipUntil()">skipUntil</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>skipUntil</span> ($type The, mixed type)

<div class="details">
<p>Tells the lexer to skip input tokens until it sees a token with the given value.</p><dl>
<dt>Parameters:</dt>
<dd>The - token type to skip until.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Lexer.php#L156" target='_blank'>framework\libs\doctrine-common\Doctrine\Common\Lexer.php at line 156</a>

<h3 id="isA()">isA</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>isA</span> (mixed value, integer token)

<div class="details">
<p>Checks if given value is identical to the given token</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Lexer.php#L165" target='_blank'>framework\libs\doctrine-common\Doctrine\Common\Lexer.php at line 165</a>

<h3 id="peek()">peek</h3>
<span class='k'></span> <span class='nx'>array</span> <span class='nf'>peek</span> ()

<div class="details">
<p>Moves the lookahead token forward.</p><dl>
<dt>Returns:</dt>
<dd>| null The next token or NULL if there are no more tokens ahead.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Lexer.php#L178" target='_blank'>framework\libs\doctrine-common\Doctrine\Common\Lexer.php at line 178</a>

<h3 id="glimpse()">glimpse</h3>
<span class='k'></span> <span class='nx'>array|null</span> <span class='nf'>glimpse</span> ()

<div class="details">
<p>Peeks at the next token, returns it and immediately resets the peek.</p><dl>
<dt>Returns:</dt>
<dd>The next token or NULL if there are no more tokens ahead.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Lexer.php#L189" target='_blank'>framework\libs\doctrine-common\Doctrine\Common\Lexer.php at line 189</a>

<h3 id="scan()">scan</h3>
<span class='k'>protected </span> <span class='nx'>void</span> <span class='nf'>scan</span> (string input)

<div class="details">
<p>Scans the input string for tokens.</p><dl>
<dt>Parameters:</dt>
<dd>input - a query string</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Lexer.php#L218" target='_blank'>framework\libs\doctrine-common\Doctrine\Common\Lexer.php at line 218</a>

<h3 id="getLiteral()">getLiteral</h3>
<span class='k'>static </span> <span class='nx'>string</span> <span class='nf'>getLiteral</span> (integer token)

<div class="details">
<p>Gets the literal for a given token.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Lexer.php#L237" target='_blank'>framework\libs\doctrine-common\Doctrine\Common\Lexer.php at line 237</a>

<h3 id="getCatchablePatterns()">getCatchablePatterns</h3>
<span class='k'>protected abstract </span> <span class='nx'>array</span> <span class='nf'>getCatchablePatterns</span> ()

<div class="details">
<p>Lexical catchable patterns.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Lexer.php#L244" target='_blank'>framework\libs\doctrine-common\Doctrine\Common\Lexer.php at line 244</a>

<h3 id="getNonCatchablePatterns()">getNonCatchablePatterns</h3>
<span class='k'>protected abstract </span> <span class='nx'>array</span> <span class='nf'>getNonCatchablePatterns</span> ()

<div class="details">
<p>Lexical non-catchable patterns.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/doctrine-common/Doctrine/Common/Lexer.php#L252" target='_blank'>framework\libs\doctrine-common\Doctrine\Common\Lexer.php at line 252</a>

<h3 id="getType()">getType</h3>
<span class='k'>protected abstract </span> <span class='nx'>integer</span> <span class='nf'>getType</span> (string value)

<div class="details">
<p>Retrieve token type. Also processes the token value if necessary.</p>
</div>

- - -

