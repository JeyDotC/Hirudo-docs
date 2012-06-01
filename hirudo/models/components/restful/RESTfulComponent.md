

- - -

**Hirudo\Models\Components\Restful\RESTfulComponent**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Models/Components/Restful/RESTfulComponent.php#L43" >framework\hirudo\Hirudo\Models\Components\Restful\RESTfulComponent.php at line 43</a>

#Class RESTfulComponent#

**RESTfulComponent**


<dl>
<dt>All Implemented Interfaces:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/models/components/componentinterface.md">Hirudo\Models\Components\ComponentInterface</a> </dd>
</dl>



- - -

<p class="signature"><span class='k'>public  class</span> <span class='nx'>RESTfulComponent</span></p>

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
<td><span class='k'>static </span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="#DefaultRoot"> $DefaultRoot</a>
                                </p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>RestRequest</span></td>
<td class="description"><p class="name" ><a href="#request"> $request</a>
                                </p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="#serializationFactory"> $serializationFactory</a>
                                </p></td>
</tr>
</table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(mixed baseURL, mixed root)</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#call">call</a>(str url, str verb, str data)</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/serialization/entityserializerbase.html>EntitySerializerBase</a></span></td>
<td class="description"><p class="name"><a href="#getserializer">getSerializer</a>()</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/serialization/entitydeserializerbase.html>EntityDeserializerBase</a></span></td>
<td class="description"><p class="name"><a href="#getdeserializer">getDeserializer</a>()</p><p class="description">This is method getDeserializer</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#addheadervariable">addHeaderVariable</a>(mixed key, mixed value)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#getlasturi">getLastUri</a>()</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#getmessageformat">getMessageFormat</a>()</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setmessageformat">setMessageFormat</a>(mixed messageFormat)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#getresponseformat">getResponseFormat</a>()</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setresponseformat">setResponseFormat</a>(mixed responseFormat)</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Models/Components/Restful/RESTfulComponent.php#L58" >framework\hirudo\Hirudo\Models\Components\Restful\RESTfulComponent.php at line 58</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (mixed baseURL, mixed root)

<div class="details">

</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Models/Components/Restful/RESTfulComponent.php#L66" >framework\hirudo\Hirudo\Models\Components\Restful\RESTfulComponent.php at line 66</a>

<h3 id="call()">call</h3>
<span class='k'>protected </span> <span class='nx'>void</span> <span class='nf'>call</span> (str url, str verb, str data)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Models/Components/Restful/RESTfulComponent.php#L82" >framework\hirudo\Hirudo\Models\Components\Restful\RESTfulComponent.php at line 82</a>

<h3 id="getSerializer()">getSerializer</h3>
<span class='k'>protected </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/serialization/entityserializerbase.html>EntitySerializerBase</a></span> <span class='nf'>getSerializer</span> ()

<div class="details">
<p></p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Models/Components/Restful/RESTfulComponent.php#L92" >framework\hirudo\Hirudo\Models\Components\Restful\RESTfulComponent.php at line 92</a>

<h3 id="getDeserializer()">getDeserializer</h3>
<span class='k'>protected </span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/hirudo/serialization/entitydeserializerbase.html>EntityDeserializerBase</a></span> <span class='nf'>getDeserializer</span> ()

<div class="details">
<p>This is method getDeserializer</p><dl>
<dt>Returns:</dt>
<dd>El objeto que se encargar� de la serializaci�n.</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Models/Components/Restful/RESTfulComponent.php#L96" >framework\hirudo\Hirudo\Models\Components\Restful\RESTfulComponent.php at line 96</a>

<h3 id="addHeaderVariable()">addHeaderVariable</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>addHeaderVariable</span> (mixed key, mixed value)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Models/Components/Restful/RESTfulComponent.php#L100" >framework\hirudo\Hirudo\Models\Components\Restful\RESTfulComponent.php at line 100</a>

<h3 id="getLastUri()">getLastUri</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>getLastUri</span> ()

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Models/Components/Restful/RESTfulComponent.php#L104" >framework\hirudo\Hirudo\Models\Components\Restful\RESTfulComponent.php at line 104</a>

<h3 id="getMessageFormat()">getMessageFormat</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>getMessageFormat</span> ()

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Models/Components/Restful/RESTfulComponent.php#L108" >framework\hirudo\Hirudo\Models\Components\Restful\RESTfulComponent.php at line 108</a>

<h3 id="setMessageFormat()">setMessageFormat</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setMessageFormat</span> (mixed messageFormat)

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Models/Components/Restful/RESTfulComponent.php#L112" >framework\hirudo\Hirudo\Models\Components\Restful\RESTfulComponent.php at line 112</a>

<h3 id="getResponseFormat()">getResponseFormat</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>getResponseFormat</span> ()

<div class="details">

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/hirudo/Hirudo/Models/Components/Restful/RESTfulComponent.php#L116" >framework\hirudo\Hirudo\Models\Components\Restful\RESTfulComponent.php at line 116</a>

<h3 id="setResponseFormat()">setResponseFormat</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>setResponseFormat</span> (mixed responseFormat)

<div class="details">

</div>

- - -

