- - -

**Hirudo\Models\Components\Restful\RESTfulComponent**
<div class="location">framework\hirudo\Hirudo\Models\Components\Restful\RESTfulComponent.php at line 43</div>
#Class RESTfulComponent#

**RESTfulComponent**


<dl>
<dt>All Implemented Interfaces:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/models/components/componentinterface.html">Hirudo\Models\Components\ComponentInterface</a> </dd>
</dl>

- - -

<p class="signature">public  class **RESTfulComponent**</p>

<div class="comment" id="overview_description"><p>A basic abstract implementation of a web service request, intended to ease
the construction of a web service consumer.</p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
</dl>
- - -

<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td class="type">static  mixed</td>
<td class="description"><p class="name"><a href="#DefaultRoot">$DefaultRoot</a></p></td>
</tr>
<tr>
<td class="type">protected  RestRequest</td>
<td class="description"><p class="name"><a href="#request">$request</a></p><p class="description"></p></td>
</tr>
<tr>
<td class="type">protected  mixed</td>
<td class="description"><p class="name"><a href="#serializationFactory">$serializationFactory</a></p></td>
</tr>
</table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(mixed baseURL, mixed root)</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type">protected  void</td>
<td class="description"><p class="name"><a href="#call">call</a>(str url, str verb, str data)</p></td>
</tr>
<tr>
<td class="type">protected  <a href="../../../../hirudo/serialization/entityserializerbase.html">EntitySerializerBase</a></td>
<td class="description"><p class="name"><a href="#getSerializer">getSerializer</a>()</p><p class="description"></p></td>
</tr>
<tr>
<td class="type">protected  <a href="../../../../hirudo/serialization/entitydeserializerbase.html">EntityDeserializerBase</a></td>
<td class="description"><p class="name"><a href="#getDeserializer">getDeserializer</a>()</p><p class="description">This is method getDeserializer</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#addHeaderVariable">addHeaderVariable</a>(mixed key, mixed value)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getLastUri">getLastUri</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getMessageFormat">getMessageFormat</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setMessageFormat">setMessageFormat</a>(mixed messageFormat)</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#getResponseFormat">getResponseFormat</a>()</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#setResponseFormat">setResponseFormat</a>(mixed responseFormat)</p></td>
</tr>
</table>

##Field Detail##
<div class="location">framework\hirudo\Hirudo\Models\Components\Restful\RESTfulComponent.php at line 45</div>
<h3 id="DefaultRoot">DefaultRoot</h3>
```php
public static  mixed **$DefaultRoot** = &quot;http://&quot;```
<div class="details">
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Models\Components\Restful\RESTfulComponent.php at line 51</div>
<h3 id="request">request</h3>
```php
protected  RestRequest **$request**```
<div class="details">
<p></p></div>

- - -

<div class="location">framework\hirudo\Hirudo\Models\Components\Restful\RESTfulComponent.php at line 52</div>
<h3 id="serializationFactory">serializationFactory</h3>
```php
protected  mixed **$serializationFactory**```
<div class="details">
</div>

- - -

<h2 id="detail_method">Constructor Detail</h2>
<div class="location">framework\hirudo\Hirudo\Models\Components\Restful\RESTfulComponent.php at line 58</div>
<h3 id="__construct()">__construct</h3>
```php
public  void **__construct**(mixed baseURL, mixed root)```
<div class="details">
</div>

- - -

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\hirudo\Hirudo\Models\Components\Restful\RESTfulComponent.php at line 66</div>
<h3 id="call()">call</h3>
```php
protected  void **call**(str url, str verb, str data)```
<div class="details">
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Models\Components\Restful\RESTfulComponent.php at line 82</div>
<h3 id="getSerializer()">getSerializer</h3>
```php
protected  <a href="../../../../hirudo/serialization/entityserializerbase.html">EntitySerializerBase</a> **getSerializer**()```
<div class="details">
<p></p></div>

- - -

<div class="location">framework\hirudo\Hirudo\Models\Components\Restful\RESTfulComponent.php at line 92</div>
<h3 id="getDeserializer()">getDeserializer</h3>
```php
protected  <a href="../../../../hirudo/serialization/entitydeserializerbase.html">EntityDeserializerBase</a> **getDeserializer**()```
<div class="details">
<p>This is method getDeserializer</p><dl>
<dt>Returns:</dt>
<dd>El objeto que se encargar� de la serializaci�n.</dd>
</dl>
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Models\Components\Restful\RESTfulComponent.php at line 96</div>
<h3 id="addHeaderVariable()">addHeaderVariable</h3>
```php
public  void **addHeaderVariable**(mixed key, mixed value)```
<div class="details">
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Models\Components\Restful\RESTfulComponent.php at line 100</div>
<h3 id="getLastUri()">getLastUri</h3>
```php
public  void **getLastUri**()```
<div class="details">
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Models\Components\Restful\RESTfulComponent.php at line 104</div>
<h3 id="getMessageFormat()">getMessageFormat</h3>
```php
public  void **getMessageFormat**()```
<div class="details">
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Models\Components\Restful\RESTfulComponent.php at line 108</div>
<h3 id="setMessageFormat()">setMessageFormat</h3>
```php
public  void **setMessageFormat**(mixed messageFormat)```
<div class="details">
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Models\Components\Restful\RESTfulComponent.php at line 112</div>
<h3 id="getResponseFormat()">getResponseFormat</h3>
```php
public  void **getResponseFormat**()```
<div class="details">
</div>

- - -

<div class="location">framework\hirudo\Hirudo\Models\Components\Restful\RESTfulComponent.php at line 116</div>
<h3 id="setResponseFormat()">setResponseFormat</h3>
```php
public  void **setResponseFormat**(mixed responseFormat)```
<div class="details">
</div>

- - -

