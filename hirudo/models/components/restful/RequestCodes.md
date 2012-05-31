- - -

**Hirudo\Models\Components\Restful\RequestCodes**
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Models/Components/Restful/RestRequest.php.md#line24" class="location">framework\hirudo\Hirudo\Models\Components\Restful\RestRequest.php at line 24</a>

# Class RequestCodes #

<pre class="tree">** RequestCodes **\n</pre>

- - -

<p class="signature">public  class **RequestCodes**</p>

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
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#flush()">flush</a>()</p><p class="description"></p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#execute()">execute</a>()</p><p class="description"></p></td>
</tr>
<tr>
<td class="type">protected  void</td>
<td class="description"><p class="name"><a href="#executeGet()">executeGet</a>(type ch)</p><p class="description"></p></td>
</tr>
<tr>
<td class="type">protected  void</td>
<td class="description"><p class="name"><a href="#executePost()">executePost</a>(type ch)</p><p class="description"></p></td>
</tr>
<tr>
<td class="type">protected  void</td>
<td class="description"><p class="name"><a href="#executePut()">executePut</a>(type ch)</p><p class="description"></p></td>
</tr>
<tr>
<td class="type">protected  void</td>
<td class="description"><p class="name"><a href="#executeDelete()">executeDelete</a>(mixed ch)</p></td>
</tr>
<tr>
<td class="type">protected  void</td>
<td class="description"><p class="name"><a href="#doExecute()">doExecute</a>(mixed curlHandle)</p></td>
</tr>
<tr>
<td class="type">protected  void</td>
<td class="description"><p class="name"><a href="#setCurlOpts()">setCurlOpts</a>(mixed curlHandle)</p></td>
</tr>
<tr>
<td class="type">protected  void</td>
<td class="description"><p class="name"><a href="#setAuth()">setAuth</a>(mixed curlHandle)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getPassword()">getPassword</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setPassword()">setPassword</a>(mixed password)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getResponseBody()">getResponseBody</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getResponseInfo()">getResponseInfo</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getUrl()">getUrl</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setUrl()">setUrl</a>(mixed url)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getUsername()">getUsername</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setUsername()">setUsername</a>(mixed username)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getVerb()">getVerb</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setVerb()">setVerb</a>(mixed verb)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getRequestBody()">getRequestBody</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setRequestBody()">setRequestBody</a>(mixed requestBody)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#addHeaderVariable()">addHeaderVariable</a>(mixed name, mixed value)</p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Models/Components/Restful/RestRequest.php.md#line35" class="location">framework\hirudo\Hirudo\Models\Components\Restful\RestRequest.php at line 35</a>

<h3 id="flush()">flush</h3>
```php
public  void **flush**()```
<div class="details">
<p></p></div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Models/Components/Restful/RestRequest.php.md#line49" class="location">framework\hirudo\Hirudo\Models\Components\Restful\RestRequest.php at line 49</a>

<h3 id="execute()">execute</h3>
```php
public  void **execute**()```
<div class="details">
<p></p><dl>
<dt>Throws:</dt>
<dd><a href="../../../../symfony/component/dependencyinjection/exception/invalidargumentexception.html">InvalidArgumentException</a> - Cuando el protocolo del request no es GET, POST, PUT o DELETE.</dd>
<dd><a href="../../../../hirudo/models/components/restful/requestfailedexception.html">RequestFailedException</a> - When request fails.</dd>
</dl>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Models/Components/Restful/RestRequest.php.md#line100" class="location">framework\hirudo\Hirudo\Models\Components\Restful\RestRequest.php at line 100</a>

<h3 id="executeGet()">executeGet</h3>
```php
protected  void **executeGet**(type ch)```
<div class="details">
<p></p></div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Models/Components/Restful/RestRequest.php.md#line108" class="location">framework\hirudo\Hirudo\Models\Components\Restful\RestRequest.php at line 108</a>

<h3 id="executePost()">executePost</h3>
```php
protected  void **executePost**(type ch)```
<div class="details">
<p></p></div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Models/Components/Restful/RestRequest.php.md#line124" class="location">framework\hirudo\Hirudo\Models\Components\Restful\RestRequest.php at line 124</a>

<h3 id="executePut()">executePut</h3>
```php
protected  void **executePut**(type ch)```
<div class="details">
<p></p></div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Models/Components/Restful/RestRequest.php.md#line147" class="location">framework\hirudo\Hirudo\Models\Components\Restful\RestRequest.php at line 147</a>

<h3 id="executeDelete()">executeDelete</h3>
```php
protected  void **executeDelete**(mixed ch)```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Models/Components/Restful/RestRequest.php.md#line153" class="location">framework\hirudo\Hirudo\Models\Components\Restful\RestRequest.php at line 153</a>

<h3 id="doExecute()">doExecute</h3>
```php
protected  void **doExecute**(mixed curlHandle)```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Models/Components/Restful/RestRequest.php.md#line166" class="location">framework\hirudo\Hirudo\Models\Components\Restful\RestRequest.php at line 166</a>

<h3 id="setCurlOpts()">setCurlOpts</h3>
```php
protected  void **setCurlOpts**(mixed curlHandle)```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Models/Components/Restful/RestRequest.php.md#line173" class="location">framework\hirudo\Hirudo\Models\Components\Restful\RestRequest.php at line 173</a>

<h3 id="setAuth()">setAuth</h3>
```php
protected  void **setAuth**(mixed curlHandle)```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Models/Components/Restful/RestRequest.php.md#line182" class="location">framework\hirudo\Hirudo\Models\Components\Restful\RestRequest.php at line 182</a>

<h3 id="getPassword()">getPassword</h3>
```php
public  void **getPassword**()```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Models/Components/Restful/RestRequest.php.md#line186" class="location">framework\hirudo\Hirudo\Models\Components\Restful\RestRequest.php at line 186</a>

<h3 id="setPassword()">setPassword</h3>
```php
public  void **setPassword**(mixed password)```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Models/Components/Restful/RestRequest.php.md#line190" class="location">framework\hirudo\Hirudo\Models\Components\Restful\RestRequest.php at line 190</a>

<h3 id="getResponseBody()">getResponseBody</h3>
```php
public  void **getResponseBody**()```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Models/Components/Restful/RestRequest.php.md#line194" class="location">framework\hirudo\Hirudo\Models\Components\Restful\RestRequest.php at line 194</a>

<h3 id="getResponseInfo()">getResponseInfo</h3>
```php
public  void **getResponseInfo**()```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Models/Components/Restful/RestRequest.php.md#line198" class="location">framework\hirudo\Hirudo\Models\Components\Restful\RestRequest.php at line 198</a>

<h3 id="getUrl()">getUrl</h3>
```php
public  void **getUrl**()```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Models/Components/Restful/RestRequest.php.md#line202" class="location">framework\hirudo\Hirudo\Models\Components\Restful\RestRequest.php at line 202</a>

<h3 id="setUrl()">setUrl</h3>
```php
public  void **setUrl**(mixed url)```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Models/Components/Restful/RestRequest.php.md#line206" class="location">framework\hirudo\Hirudo\Models\Components\Restful\RestRequest.php at line 206</a>

<h3 id="getUsername()">getUsername</h3>
```php
public  void **getUsername**()```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Models/Components/Restful/RestRequest.php.md#line210" class="location">framework\hirudo\Hirudo\Models\Components\Restful\RestRequest.php at line 210</a>

<h3 id="setUsername()">setUsername</h3>
```php
public  void **setUsername**(mixed username)```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Models/Components/Restful/RestRequest.php.md#line214" class="location">framework\hirudo\Hirudo\Models\Components\Restful\RestRequest.php at line 214</a>

<h3 id="getVerb()">getVerb</h3>
```php
public  void **getVerb**()```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Models/Components/Restful/RestRequest.php.md#line218" class="location">framework\hirudo\Hirudo\Models\Components\Restful\RestRequest.php at line 218</a>

<h3 id="setVerb()">setVerb</h3>
```php
public  void **setVerb**(mixed verb)```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Models/Components/Restful/RestRequest.php.md#line222" class="location">framework\hirudo\Hirudo\Models\Components\Restful\RestRequest.php at line 222</a>

<h3 id="getRequestBody()">getRequestBody</h3>
```php
public  void **getRequestBody**()```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Models/Components/Restful/RestRequest.php.md#line226" class="location">framework\hirudo\Hirudo\Models\Components\Restful\RestRequest.php at line 226</a>

<h3 id="setRequestBody()">setRequestBody</h3>
```php
public  void **setRequestBody**(mixed requestBody)```
<div class="details">
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Models/Components/Restful/RestRequest.php.md#line230" class="location">framework\hirudo\Hirudo\Models\Components\Restful\RestRequest.php at line 230</a>

<h3 id="addHeaderVariable()">addHeaderVariable</h3>
```php
public  void **addHeaderVariable**(mixed name, mixed value)```
<div class="details">
</div>

- - -

