
- - -

**Doctrine\Common\Lexer**
<div class="location">framework\libs\doctrine-common\Doctrine\Common\Lexer.php at line 32</div>
#Class Lexer#

**Lexer**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/doctrine/common/annotations/doclexer.html">Doctrine\Common\Annotations\DocLexer</a> </dd>
</dl>

- - -

<p class="signature">public abstract  class **Lexer**</p>

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

- - -

<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td class="type"> array The next token in the input.</td>
<td class="description"><p class="name"><a href="#lookahead">$lookahead</a></p><p class="description"></p></td>
</tr>
<tr>
<td class="type"> array The last matched/seen token.</td>
<td class="description"><p class="name"><a href="#token">$token</a></p><p class="description"></p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#setinput">setInput</a>(string input)</p><p class="description">Sets the input data to be tokenized.
</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#reset">reset</a>()</p><p class="description">Resets the lexer.</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#resetpeek">resetPeek</a>()</p><p class="description">Resets the peek pointer to 0.</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#resetposition">resetPosition</a>(integer position)</p><p class="description">Resets the lexer position on the input to the given position.</p></td>
</tr>
<tr>
<td class="type">  boolean</td>
<td class="description"><p class="name"><a href="#isnexttoken">isNextToken</a>(integer|string token)</p><p class="description">Checks whether a given token matches the current lookahead.</p></td>
</tr>
<tr>
<td class="type">  boolean</td>
<td class="description"><p class="name"><a href="#isnexttokenany">isNextTokenAny</a>(array tokens)</p><p class="description">Checks whether any of the given tokens matches the current lookahead</p></td>
</tr>
<tr>
<td class="type">  array|null</td>
<td class="description"><p class="name"><a href="#movenext">moveNext</a>()</p><p class="description">Moves to the next token in the input string.
</p></td>
</tr>
<tr>
<td class="type">  void</td>
<td class="description"><p class="name"><a href="#skipuntil">skipUntil</a>($type The, mixed type)</p><p class="description">Tells the lexer to skip input tokens until it sees a token with the given value.</p></td>
</tr>
<tr>
<td class="type">  boolean</td>
<td class="description"><p class="name"><a href="#isa">isA</a>(mixed value, integer token)</p><p class="description">Checks if given value is identical to the given token</p></td>
</tr>
<tr>
<td class="type">  array</td>
<td class="description"><p class="name"><a href="#peek">peek</a>()</p><p class="description">Moves the lookahead token forward.</p></td>
</tr>
<tr>
<td class="type">  array|null</td>
<td class="description"><p class="name"><a href="#glimpse">glimpse</a>()</p><p class="description">Peeks at the next token, returns it and immediately resets the peek.</p></td>
</tr>
<tr>
<td class="type"> protected  void</td>
<td class="description"><p class="name"><a href="#scan">scan</a>(string input)</p><p class="description">Scans the input string for tokens.</p></td>
</tr>
<tr>
<td class="type"> static  string</td>
<td class="description"><p class="name"><a href="#getliteral">getLiteral</a>(integer token)</p><p class="description">Gets the literal for a given token.</p></td>
</tr>
<tr>
<td class="type"> protected abstract  array</td>
<td class="description"><p class="name"><a href="#getcatchablepatterns">getCatchablePatterns</a>()</p><p class="description">Lexical catchable patterns.</p></td>
</tr>
<tr>
<td class="type"> protected abstract  array</td>
<td class="description"><p class="name"><a href="#getnoncatchablepatterns">getNonCatchablePatterns</a>()</p><p class="description">Lexical non-catchable patterns.</p></td>
</tr>
<tr>
<td class="type"> protected abstract  integer</td>
<td class="description"><p class="name"><a href="#gettype">getType</a>(string value)</p><p class="description">Retrieve token type. </p></td>
</tr>
</table>

##Field Detail##
<div class="location">framework\libs\doctrine-common\Doctrine\Common\Lexer.php at line 52</div>
<h3 id="lookahead">lookahead</h3>

public  array The next token in the input. $lookahead
<div class="details">
<p></p></div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Lexer.php at line 57</div>
<h3 id="token">token</h3>

public  array The last matched/seen token. $token
<div class="details">
<p></p></div>

- - -

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\doctrine-common\Doctrine\Common\Lexer.php at line 67</div>
<h3 id="setInput()">setInput</h3>

public  void **setInput** (string input)<div class="details">
<p>Sets the input data to be tokenized.</p><p>The Lexer is immediately reset and the new input tokenized.
Any unprocessed tokens from any previous input are lost.</p><dl>
<dt>Parameters:</dt>
<dd>input - The input to be tokenized.</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Lexer.php at line 76</div>
<h3 id="reset()">reset</h3>

public  void **reset** ()<div class="details">
<p>Resets the lexer.</p></div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Lexer.php at line 86</div>
<h3 id="resetPeek()">resetPeek</h3>

public  void **resetPeek** ()<div class="details">
<p>Resets the peek pointer to 0.</p></div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Lexer.php at line 95</div>
<h3 id="resetPosition()">resetPosition</h3>

public  void **resetPosition** (integer position)<div class="details">
<p>Resets the lexer position on the input to the given position.</p><dl>
<dt>Parameters:</dt>
<dd>position - Position to place the lexical scanner</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Lexer.php at line 105</div>
<h3 id="isNextToken()">isNextToken</h3>

public  boolean **isNextToken** (integer|string token)<div class="details">
<p>Checks whether a given token matches the current lookahead.</p></div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Lexer.php at line 115</div>
<h3 id="isNextTokenAny()">isNextTokenAny</h3>

public  boolean **isNextTokenAny** (array tokens)<div class="details">
<p>Checks whether any of the given tokens matches the current lookahead</p></div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Lexer.php at line 130</div>
<h3 id="moveNext()">moveNext</h3>

public  array|null **moveNext** ()<div class="details">
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

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Lexer.php at line 143</div>
<h3 id="skipUntil()">skipUntil</h3>

public  void **skipUntil** ($type The, mixed type)<div class="details">
<p>Tells the lexer to skip input tokens until it sees a token with the given value.</p><dl>
<dt>Parameters:</dt>
<dd>The - token type to skip until.</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Lexer.php at line 156</div>
<h3 id="isA()">isA</h3>

public  boolean **isA** (mixed value, integer token)<div class="details">
<p>Checks if given value is identical to the given token</p></div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Lexer.php at line 165</div>
<h3 id="peek()">peek</h3>

public  array **peek** ()<div class="details">
<p>Moves the lookahead token forward.</p><dl>
<dt>Returns:</dt>
<dd>| null The next token or NULL if there are no more tokens ahead.</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Lexer.php at line 178</div>
<h3 id="glimpse()">glimpse</h3>

public  array|null **glimpse** ()<div class="details">
<p>Peeks at the next token, returns it and immediately resets the peek.</p><dl>
<dt>Returns:</dt>
<dd>The next token or NULL if there are no more tokens ahead.</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Lexer.php at line 189</div>
<h3 id="scan()">scan</h3>

protected  void **scan** (string input)<div class="details">
<p>Scans the input string for tokens.</p><dl>
<dt>Parameters:</dt>
<dd>input - a query string</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Lexer.php at line 218</div>
<h3 id="getLiteral()">getLiteral</h3>

public static  string **getLiteral** (integer token)<div class="details">
<p>Gets the literal for a given token.</p></div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Lexer.php at line 237</div>
<h3 id="getCatchablePatterns()">getCatchablePatterns</h3>

protected abstract  array **getCatchablePatterns** ()<div class="details">
<p>Lexical catchable patterns.</p></div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Lexer.php at line 244</div>
<h3 id="getNonCatchablePatterns()">getNonCatchablePatterns</h3>

protected abstract  array **getNonCatchablePatterns** ()<div class="details">
<p>Lexical non-catchable patterns.</p></div>

- - -

<div class="location">framework\libs\doctrine-common\Doctrine\Common\Lexer.php at line 252</div>
<h3 id="getType()">getType</h3>

protected abstract  integer **getType** (string value)<div class="details">
<p>Retrieve token type. Also processes the token value if necessary.</p></div>

- - -

