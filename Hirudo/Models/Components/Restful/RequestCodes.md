

- - -

**Hirudo\Models\Components\Restful\RequestCodes**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Models/Components/Restful/RestRequest.php#L24" target='_blank'>framework\hirudo\Hirudo\Models\Components\Restful\RestRequest.php at line 24</a>

#Class RequestCodes#

**RequestCodes**




- - -

<p><strong>public  class</strong> <span>RequestCodes</span></p>

<div class="comment" id="overview_description"><p>«Copyright 2012 Jeysson José Guevara Mendivil(JeyDotC)»</p><p>This file is part of Hirudo.</p><p>Hirudo is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.</p><p>Hirudo is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.</p><p>You should have received a copy of the GNU General Public License
along with Hirudo.  If not, see <http://www.gnu.org/licenses/>.</p></div>



- - -

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

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Models/Components/Restful/RestRequest.php#L35" target='_blank'>framework\hirudo\Hirudo\Models\Components\Restful\RestRequest.php at line 35</a>

<h3 id="flush()">flush</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>flush</span> ()

<div class="details">
<p></p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Models/Components/Restful/RestRequest.php#L49" target='_blank'>framework\hirudo\Hirudo\Models\Components\Restful\RestRequest.php at line 49</a>

<h3 id="execute()">execute</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>execute</span> ()

<div class="details">
<p></p><dl>
<dt>Throws:</dt>
<dd><a href="../../../../symfony/component/dependencyinjection/exception/invalidargumentexception.html">InvalidArgumentException</a> - Cuando el protocolo del request no es GET, POST, PUT o DELETE.</dd>
<dd><a href="../../../../hirudo/models/components/restful/requestfailedexception.html">RequestFailedException</a> - When request fails.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Models/Components/Restful/RestRequest.php#L100" target='_blank'>framework\hirudo\Hirudo\Models\Components\Restful\RestRequest.php at line 100</a>

<h3 id="executeGet()">executeGet</h3>
<span class='k'>protected </span> <span class='nx'>void</span> <span class='nf'>executeGet</span> (type ch)

<div class="details">
<p></p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Models/Components/Restful/RestRequest.php#L108" target='_blank'>framework\hirudo\Hirudo\Models\Components\Restful\RestRequest.php at line 108</a>

<h3 id="executePost()">executePost</h3>
<span class='k'>protected </span> <span class='nx'>void</span> <span class='nf'>executePost</span> (type ch)

<div class="details">
<p></p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Models/Components/Restful/RestRequest.php#L124" target='_blank'>framework\hirudo\Hirudo\Models\Components\Restful\RestRequest.php at line 124</a>

<h3 id="executePut()">executePut</h3>
<span class='k'>protected </span> <span class='nx'>void</span> <span class='nf'>executePut</span> (type ch)

<div class="details">
<p></p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Models/Components/Restful/RestRequest.php#L147" target='_blank'>framework\hirudo\Hirudo\Models\Components\Restful\RestRequest.php at line 147</a>

<h3 id="executeDelete()">executeDelete</h3>
<span class='k'>protected </span> <span class='nx'>void</span> <span class='nf'>executeDelete</span> (mixed ch)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Models/Components/Restful/RestRequest.php#L153" target='_blank'>framework\hirudo\Hirudo\Models\Components\Restful\RestRequest.php at line 153</a>

<h3 id="doExecute()">doExecute</h3>
<span class='k'>protected </span> <span class='nx'>void</span> <span class='nf'>doExecute</span> (mixed curlHandle)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Models/Components/Restful/RestRequest.php#L166" target='_blank'>framework\hirudo\Hirudo\Models\Components\Restful\RestRequest.php at line 166</a>

<h3 id="setCurlOpts()">setCurlOpts</h3>
<span class='k'>protected </span> <span class='nx'>void</span> <span class='nf'>setCurlOpts</span> (mixed curlHandle)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Models/Components/Restful/RestRequest.php#L173" target='_blank'>framework\hirudo\Hirudo\Models\Components\Restful\RestRequest.php at line 173</a>

<h3 id="setAuth()">setAuth</h3>
<span class='k'>protected </span> <span class='nx'>void</span> <span class='nf'>setAuth</span> (mixed curlHandle)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Models/Components/Restful/RestRequest.php#L182" target='_blank'>framework\hirudo\Hirudo\Models\Components\Restful\RestRequest.php at line 182</a>

<h3 id="getPassword()">getPassword</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>getPassword</span> ()

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Models/Components/Restful/RestRequest.php#L186" target='_blank'>framework\hirudo\Hirudo\Models\Components\Restful\RestRequest.php at line 186</a>

<h3 id="setPassword()">setPassword</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setPassword</span> (mixed password)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Models/Components/Restful/RestRequest.php#L190" target='_blank'>framework\hirudo\Hirudo\Models\Components\Restful\RestRequest.php at line 190</a>

<h3 id="getResponseBody()">getResponseBody</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>getResponseBody</span> ()

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Models/Components/Restful/RestRequest.php#L194" target='_blank'>framework\hirudo\Hirudo\Models\Components\Restful\RestRequest.php at line 194</a>

<h3 id="getResponseInfo()">getResponseInfo</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>getResponseInfo</span> ()

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Models/Components/Restful/RestRequest.php#L198" target='_blank'>framework\hirudo\Hirudo\Models\Components\Restful\RestRequest.php at line 198</a>

<h3 id="getUrl()">getUrl</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>getUrl</span> ()

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Models/Components/Restful/RestRequest.php#L202" target='_blank'>framework\hirudo\Hirudo\Models\Components\Restful\RestRequest.php at line 202</a>

<h3 id="setUrl()">setUrl</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setUrl</span> (mixed url)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Models/Components/Restful/RestRequest.php#L206" target='_blank'>framework\hirudo\Hirudo\Models\Components\Restful\RestRequest.php at line 206</a>

<h3 id="getUsername()">getUsername</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>getUsername</span> ()

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Models/Components/Restful/RestRequest.php#L210" target='_blank'>framework\hirudo\Hirudo\Models\Components\Restful\RestRequest.php at line 210</a>

<h3 id="setUsername()">setUsername</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setUsername</span> (mixed username)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Models/Components/Restful/RestRequest.php#L214" target='_blank'>framework\hirudo\Hirudo\Models\Components\Restful\RestRequest.php at line 214</a>

<h3 id="getVerb()">getVerb</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>getVerb</span> ()

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Models/Components/Restful/RestRequest.php#L218" target='_blank'>framework\hirudo\Hirudo\Models\Components\Restful\RestRequest.php at line 218</a>

<h3 id="setVerb()">setVerb</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setVerb</span> (mixed verb)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Models/Components/Restful/RestRequest.php#L222" target='_blank'>framework\hirudo\Hirudo\Models\Components\Restful\RestRequest.php at line 222</a>

<h3 id="getRequestBody()">getRequestBody</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>getRequestBody</span> ()

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Models/Components/Restful/RestRequest.php#L226" target='_blank'>framework\hirudo\Hirudo\Models\Components\Restful\RestRequest.php at line 226</a>

<h3 id="setRequestBody()">setRequestBody</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setRequestBody</span> (mixed requestBody)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Models/Components/Restful/RestRequest.php#L230" target='_blank'>framework\hirudo\Hirudo\Models\Components\Restful\RestRequest.php at line 230</a>

<h3 id="addHeaderVariable()">addHeaderVariable</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>addHeaderVariable</span> (mixed name, mixed value)

<div class="details">

</div>

- - -

