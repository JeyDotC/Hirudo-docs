- - -

**Hirudo\Core\Events\Annotations\ForCall**
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/Events/Annotations/ForCall.php.md#line30" class="location">framework\hirudo\Hirudo\Core\Events\Annotations\ForCall.php at line 30</a>

# Class ForCall #

<pre class="tree">** ForCall **\n</pre>

- - -

<p class="signature">public  class **ForCall**</p>

<div class="comment" id="overview_description"><p><p>Signals a Task event listener to only listen the event
when the current call matches the given characteristics.</p></p><p>Example:</p><p><code>
ForCall(app="MyApp", module="Amodule", task="aTask")
</code></p><p><p>Indicates that the event listener will only listen the event when the call
is for the 'MyApp' application on the 'Amodule' module in the 'aTask' task.</p></p><p><p>Omitting any of those characteristics indicates that the event will be
listened for any value of it. For example, omitting the app and module values
will cause the event to be listened for any application and module but only on
the 'aTask' task.</p></p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
<dt>Annotation.</dt>
<dt>Target("CLASS").</dt>
</dl>
- - -

<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#app">$app</a></p><p class="description"></p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#module">$module</a></p><p class="description"></p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#task">$task</a></p><p class="description"></p></td>
</tr>
</table>

##Field Detail##
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/Events/Annotations/ForCall.php.md#line36" class="location">framework\hirudo\Hirudo\Core\Events\Annotations\ForCall.php at line 36</a>

<h3 id="app">app</h3>
```php
public  string **$app** = &quot;&quot;```
<div class="details">
<p></p></div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/Events/Annotations/ForCall.php.md#line42" class="location">framework\hirudo\Hirudo\Core\Events\Annotations\ForCall.php at line 42</a>

<h3 id="module">module</h3>
```php
public  string **$module** = &quot;&quot;```
<div class="details">
<p></p></div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Core/Events/Annotations/ForCall.php.md#line48" class="location">framework\hirudo\Hirudo\Core\Events\Annotations\ForCall.php at line 48</a>

<h3 id="task">task</h3>
```php
public  string **$task** = &quot;&quot;```
<div class="details">
<p></p></div>

- - -

