

- - -

**KitchenSink\Modules\EventListening\EventListening**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/src/KitchenSink/Modules/EventListening/EventListening.php#L18" target='_blank'>src\KitchenSink\Modules\EventListening\EventListening.php at line 18</a>

#Class EventListening#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md">Module</a>
 &gt; **EventListening**




- - -

<p><strong>public  class</strong> <span>EventListening</span>
<strong>extends</strong> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md">Module</a>

</p>

<div class="comment" id="overview_description"><p>Description of EventListeningModule</p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
</dl>


<hr />

<table class="inherit">
<tr><th colspan="2">Fields inherited from Hirudo\Core\Module</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#context">context</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#currentuser">currentUser</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#headers">headers</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#page">page</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#request">request</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#route">route</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#session">session</a></td></tr></table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#gotosomewhereelse">goToSomewhereElse</a>(<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Events/BeforeTaskEvent.md">BeforeTaskEvent</a> e)</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#listentospecificcall">listenToSpecificCall</a>(<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Events/AfterTaskEvent.md">AfterTaskEvent</a> e)</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#broadcastevent">broadCastEvent</a>()</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#respondtocustomevent">respondToCustomEvent</a>(type event)</p><p class="description"></p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Hirudo\Core\Module</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#addmessage">addMessage</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#assign">assign</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#assignmany">assignMany</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#component">component</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#createmodulefromclassname">createModuleFromClassName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#display">display</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#getappname">getAppName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#getmoduledir">getModuleDir</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#getname">getName</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#gettask">getTask</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#onmoduleready">onModuleReady</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#redirect">redirect</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Module.md#setdefaulttask">setDefaultTask</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/src/KitchenSink/Modules/EventListening/EventListening.php#L28" target='_blank'>src\KitchenSink\Modules\EventListening\EventListening.php at line 28</a>

<h3 id="goToSomewhereElse()">goToSomewhereElse</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>goToSomewhereElse</span> (<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Events/BeforeTaskEvent.md">BeforeTaskEvent</a> e)

<div class="details">
<p></p><dl>
<dt>Parameters:</dt>
<dd>e - Hey, Listen!</dd>
<dt>Listen(to="beforeTask").</dt>
<dt>IgnoreCall.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/src/KitchenSink/Modules/EventListening/EventListening.php#L46" target='_blank'>src\KitchenSink\Modules\EventListening\EventListening.php at line 46</a>

<h3 id="listenToSpecificCall()">listenToSpecificCall</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>listenToSpecificCall</span> (<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Events/AfterTaskEvent.md">AfterTaskEvent</a> e)

<div class="details">
<p></p><dl>
<dt>Listen(to="afterTask",:</dt>
<dd>constraints={"KitchenSink::EventListening::broadCastEvent"})</dd>
<dt>IgnoreCall.</dt>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/src/KitchenSink/Modules/EventListening/EventListening.php#L61" target='_blank'>src\KitchenSink\Modules\EventListening\EventListening.php at line 61</a>

<h3 id="broadCastEvent()">broadCastEvent</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>broadCastEvent</span> ()

<div class="details">
<p></p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/src/KitchenSink/Modules/EventListening/EventListening.php#L72" target='_blank'>src\KitchenSink\Modules\EventListening\EventListening.php at line 72</a>

<h3 id="respondToCustomEvent()">respondToCustomEvent</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>respondToCustomEvent</span> (type event)

<div class="details">
<p></p><dl>
<dt>Listen(to="myCustomEvent").</dt>
<dt>IgnoreCall.</dt>
</dl>

</div>

- - -

