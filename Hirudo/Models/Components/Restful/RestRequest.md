

- - -

**Hirudo\Models\Components\Restful\RestRequest**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Models/Components/Restful/RestRequest.php#L148" target='_blank'>framework\Hirudo\Models\Components\Restful\RestRequest.php at line 148</a>

#Class RestRequest#

**RestRequest**




- - -

<p><strong>public  class</strong> <span>RestRequest</span></p>

<div class="comment" id="overview_description"><p>This class envelops the curl functions into an useful and easy-to-use class.</p></div>



<hr />



<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Models/Components/Restful/RestRequest.md#password"> $password</a>
                                </p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Models/Components/Restful/RestRequest.md#requestbody"> $requestBody</a>
                                </p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Models/Components/Restful/RestRequest.md#requestlength"> $requestLength</a>
                                </p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Models/Components/Restful/RestRequest.md#responsebody"> $responseBody</a>
                                </p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Models/Components/Restful/RestRequest.md#responseinfo"> $responseInfo</a>
                                </p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Models/Components/Restful/RestRequest.md#responsestatus"> $responseStatus</a>
                                </p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Models/Components/Restful/RestRequest.md#url"> $url</a>
                                </p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Models/Components/Restful/RestRequest.md#username"> $username</a>
                                </p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Models/Components/Restful/RestRequest.md#verb"> $verb</a>
                                </p></td>
</tr>
</table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(string url, string verb, string requestBody)</p><p class="description">Creates a new instance of RestRequest</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#flush">flush</a>()</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#execute">execute</a>()</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#executeget">executeGet</a>(type ch)</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#executepost">executePost</a>(type ch)</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#executeput">executePut</a>(type ch)</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#executedelete">executeDelete</a>(mixed ch)</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#doexecute">doExecute</a>(mixed curlHandle)</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setcurlopts">setCurlOpts</a>(mixed curlHandle)</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setauth">setAuth</a>(mixed curlHandle)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#getpassword">getPassword</a>()</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setpassword">setPassword</a>(mixed password)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#getresponsebody">getResponseBody</a>()</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#getresponseinfo">getResponseInfo</a>()</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#geturl">getUrl</a>()</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#seturl">setUrl</a>(mixed url)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#getusername">getUsername</a>()</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setusername">setUsername</a>(mixed username)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#getverb">getVerb</a>()</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setverb">setVerb</a>(mixed verb)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#getrequestbody">getRequestBody</a>()</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setrequestbody">setRequestBody</a>(mixed requestBody)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#addheadervariable">addHeaderVariable</a>(mixed name, mixed value)</p></td>
</tr>
</table>

##Field Detail##

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Models/Components/Restful/RestRequest.php#L155" target='_blank'>framework\Hirudo\Models\Components\Restful\RestRequest.php at line 155</a>

<h3 id="password">password</h3>
<span class='k'>protected </span> <span class='nx'>mixed</span><span class='no'> $password</span><span class='o'> = null</span>

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Models/Components/Restful/RestRequest.php#L152" target='_blank'>framework\Hirudo\Models\Components\Restful\RestRequest.php at line 152</a>

<h3 id="requestBody">requestBody</h3>
<span class='k'>protected </span> <span class='nx'>mixed</span><span class='no'> $requestBody</span><div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Models/Components/Restful/RestRequest.php#L153" target='_blank'>framework\Hirudo\Models\Components\Restful\RestRequest.php at line 153</a>

<h3 id="requestLength">requestLength</h3>
<span class='k'>protected </span> <span class='nx'>mixed</span><span class='no'> $requestLength</span><span class='o'> = 0</span>

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Models/Components/Restful/RestRequest.php#L156" target='_blank'>framework\Hirudo\Models\Components\Restful\RestRequest.php at line 156</a>

<h3 id="responseBody">responseBody</h3>
<span class='k'>protected </span> <span class='nx'>mixed</span><span class='no'> $responseBody</span><span class='o'> = null</span>

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Models/Components/Restful/RestRequest.php#L157" target='_blank'>framework\Hirudo\Models\Components\Restful\RestRequest.php at line 157</a>

<h3 id="responseInfo">responseInfo</h3>
<span class='k'>protected </span> <span class='nx'>mixed</span><span class='no'> $responseInfo</span><span class='o'> = null</span>

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Models/Components/Restful/RestRequest.php#L158" target='_blank'>framework\Hirudo\Models\Components\Restful\RestRequest.php at line 158</a>

<h3 id="responseStatus">responseStatus</h3>
<span class='k'>protected </span> <span class='nx'>mixed</span><span class='no'> $responseStatus</span><span class='o'> = 0</span>

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Models/Components/Restful/RestRequest.php#L150" target='_blank'>framework\Hirudo\Models\Components\Restful\RestRequest.php at line 150</a>

<h3 id="url">url</h3>
<span class='k'>protected </span> <span class='nx'>mixed</span><span class='no'> $url</span><div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Models/Components/Restful/RestRequest.php#L154" target='_blank'>framework\Hirudo\Models\Components\Restful\RestRequest.php at line 154</a>

<h3 id="username">username</h3>
<span class='k'>protected </span> <span class='nx'>mixed</span><span class='no'> $username</span><span class='o'> = null</span>

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Models/Components/Restful/RestRequest.php#L151" target='_blank'>framework\Hirudo\Models\Components\Restful\RestRequest.php at line 151</a>

<h3 id="verb">verb</h3>
<span class='k'>protected </span> <span class='nx'>mixed</span><span class='no'> $verb</span><div class="details">

</div>

- - -

<h2>Constructor Detail</h2>


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Models/Components/Restful/RestRequest.php#L167" target='_blank'>framework\Hirudo\Models\Components\Restful\RestRequest.php at line 167</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (string url, string verb, string requestBody)

<div class="details">
<p>Creates a new instance of RestRequest</p><dl>
<dt>Parameters:</dt>
<dd>url - [Optional] The service URL.</dd>
<dd>verb - [Optional] The protocol for the request, GET by default.</dd>
<dd>requestBody - [Optional] Any data sent to the request.</dd>
</dl>

</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Models/Components/Restful/RestRequest.php#L176" target='_blank'>framework\Hirudo\Models\Components\Restful\RestRequest.php at line 176</a>

<h3 id="flush()">flush</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>flush</span> ()

<div class="details">
<p></p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Models/Components/Restful/RestRequest.php#L190" target='_blank'>framework\Hirudo\Models\Components\Restful\RestRequest.php at line 190</a>

<h3 id="execute()">execute</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>execute</span> ()

<div class="details">
<p></p><dl>
<dt>Throws:</dt>
<dd>InvalidArgumentException - Cuando el protocolo del request no es GET, POST, PUT o DELETE.</dd>
<dd><a href="../../../../hirudo/models/components/restful/requestfailedexception.html">RequestFailedException</a> - When request fails.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Models/Components/Restful/RestRequest.php#L241" target='_blank'>framework\Hirudo\Models\Components\Restful\RestRequest.php at line 241</a>

<h3 id="executeGet()">executeGet</h3>
<span class='k'>protected </span> <span class='nx'>void</span> <span class='nf'>executeGet</span> (type ch)

<div class="details">
<p></p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Models/Components/Restful/RestRequest.php#L249" target='_blank'>framework\Hirudo\Models\Components\Restful\RestRequest.php at line 249</a>

<h3 id="executePost()">executePost</h3>
<span class='k'>protected </span> <span class='nx'>void</span> <span class='nf'>executePost</span> (type ch)

<div class="details">
<p></p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Models/Components/Restful/RestRequest.php#L265" target='_blank'>framework\Hirudo\Models\Components\Restful\RestRequest.php at line 265</a>

<h3 id="executePut()">executePut</h3>
<span class='k'>protected </span> <span class='nx'>void</span> <span class='nf'>executePut</span> (type ch)

<div class="details">
<p></p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Models/Components/Restful/RestRequest.php#L288" target='_blank'>framework\Hirudo\Models\Components\Restful\RestRequest.php at line 288</a>

<h3 id="executeDelete()">executeDelete</h3>
<span class='k'>protected </span> <span class='nx'>void</span> <span class='nf'>executeDelete</span> (mixed ch)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Models/Components/Restful/RestRequest.php#L294" target='_blank'>framework\Hirudo\Models\Components\Restful\RestRequest.php at line 294</a>

<h3 id="doExecute()">doExecute</h3>
<span class='k'>protected </span> <span class='nx'>void</span> <span class='nf'>doExecute</span> (mixed curlHandle)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Models/Components/Restful/RestRequest.php#L307" target='_blank'>framework\Hirudo\Models\Components\Restful\RestRequest.php at line 307</a>

<h3 id="setCurlOpts()">setCurlOpts</h3>
<span class='k'>protected </span> <span class='nx'>void</span> <span class='nf'>setCurlOpts</span> (mixed curlHandle)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Models/Components/Restful/RestRequest.php#L314" target='_blank'>framework\Hirudo\Models\Components\Restful\RestRequest.php at line 314</a>

<h3 id="setAuth()">setAuth</h3>
<span class='k'>protected </span> <span class='nx'>void</span> <span class='nf'>setAuth</span> (mixed curlHandle)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Models/Components/Restful/RestRequest.php#L323" target='_blank'>framework\Hirudo\Models\Components\Restful\RestRequest.php at line 323</a>

<h3 id="getPassword()">getPassword</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>getPassword</span> ()

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Models/Components/Restful/RestRequest.php#L327" target='_blank'>framework\Hirudo\Models\Components\Restful\RestRequest.php at line 327</a>

<h3 id="setPassword()">setPassword</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setPassword</span> (mixed password)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Models/Components/Restful/RestRequest.php#L331" target='_blank'>framework\Hirudo\Models\Components\Restful\RestRequest.php at line 331</a>

<h3 id="getResponseBody()">getResponseBody</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>getResponseBody</span> ()

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Models/Components/Restful/RestRequest.php#L335" target='_blank'>framework\Hirudo\Models\Components\Restful\RestRequest.php at line 335</a>

<h3 id="getResponseInfo()">getResponseInfo</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>getResponseInfo</span> ()

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Models/Components/Restful/RestRequest.php#L339" target='_blank'>framework\Hirudo\Models\Components\Restful\RestRequest.php at line 339</a>

<h3 id="getUrl()">getUrl</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>getUrl</span> ()

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Models/Components/Restful/RestRequest.php#L343" target='_blank'>framework\Hirudo\Models\Components\Restful\RestRequest.php at line 343</a>

<h3 id="setUrl()">setUrl</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setUrl</span> (mixed url)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Models/Components/Restful/RestRequest.php#L347" target='_blank'>framework\Hirudo\Models\Components\Restful\RestRequest.php at line 347</a>

<h3 id="getUsername()">getUsername</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>getUsername</span> ()

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Models/Components/Restful/RestRequest.php#L351" target='_blank'>framework\Hirudo\Models\Components\Restful\RestRequest.php at line 351</a>

<h3 id="setUsername()">setUsername</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setUsername</span> (mixed username)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Models/Components/Restful/RestRequest.php#L355" target='_blank'>framework\Hirudo\Models\Components\Restful\RestRequest.php at line 355</a>

<h3 id="getVerb()">getVerb</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>getVerb</span> ()

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Models/Components/Restful/RestRequest.php#L359" target='_blank'>framework\Hirudo\Models\Components\Restful\RestRequest.php at line 359</a>

<h3 id="setVerb()">setVerb</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setVerb</span> (mixed verb)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Models/Components/Restful/RestRequest.php#L363" target='_blank'>framework\Hirudo\Models\Components\Restful\RestRequest.php at line 363</a>

<h3 id="getRequestBody()">getRequestBody</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>getRequestBody</span> ()

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Models/Components/Restful/RestRequest.php#L367" target='_blank'>framework\Hirudo\Models\Components\Restful\RestRequest.php at line 367</a>

<h3 id="setRequestBody()">setRequestBody</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setRequestBody</span> (mixed requestBody)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Models/Components/Restful/RestRequest.php#L371" target='_blank'>framework\Hirudo\Models\Components\Restful\RestRequest.php at line 371</a>

<h3 id="addHeaderVariable()">addHeaderVariable</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>addHeaderVariable</span> (mixed name, mixed value)

<div class="details">

</div>

- - -

