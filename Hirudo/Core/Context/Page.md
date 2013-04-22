

- - -

**Hirudo\Core\Context\Page**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Context/Page.php#L31" target='_blank'>framework\Hirudo\Core\Context\Page.php at line 31</a>

#Interface Page#

**Page**




- - -

<p><strong>public  interface</strong> <span>Page</span></p>

<div class="comment" id="overview_description"><p></p></div>

<dl>
<dt>Author:</dt>
<dd>JeyDotC</dd>
</dl>


<hr />

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/Page.md>Page</a></span></td>
<td class="description"><p class="name"><a href="#settitle">setTitle</a>(string title)</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/Page.md>Page</a></span></td>
<td class="description"><p class="name"><a href="#setheading">setHeading</a>(string heading)</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/Page.md>Page</a></span></td>
<td class="description"><p class="name"><a href="#addmessage">addMessage</a>(\Hirudo\Core\Util\Message message)</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/Page.md>Page</a></span></td>
<td class="description"><p class="name"><a href="#addbreadcrumb">addBreadcrumb</a>(string title, string url)</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#rendertitle">renderTitle</a>()</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#renderheading">renderHeading</a>()</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#rendermessages">renderMessages</a>()</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#renderbreadcrumbs">renderBreadcrumbs</a>()</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#gettitle">getTitle</a>()</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#getheading">getHeading</a>()</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array<Message></span></td>
<td class="description"><p class="name"><a href="#getmessages">getMessages</a>()</p><p class="description"></p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array<Breadcrumb></span></td>
<td class="description"><p class="name"><a href="#getbreadcrumbs">getBreadcrumbs</a>()</p><p class="description"></p></td>
</tr>
</table>

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Context/Page.php#L39" target='_blank'>framework\Hirudo\Core\Context\Page.php at line 39</a>

<h3 id="setTitle()">setTitle</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/Page.md>Page</a></span> <span class='nf'>setTitle</span> (string title)

<div class="details">
<p></p><dl>
<dt>Returns:</dt>
<dd>$this</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Context/Page.php#L47" target='_blank'>framework\Hirudo\Core\Context\Page.php at line 47</a>

<h3 id="setHeading()">setHeading</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/Page.md>Page</a></span> <span class='nf'>setHeading</span> (string heading)

<div class="details">
<p></p><dl>
<dt>Returns:</dt>
<dd>$this</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Context/Page.php#L55" target='_blank'>framework\Hirudo\Core\Context\Page.php at line 55</a>

<h3 id="addMessage()">addMessage</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/Page.md>Page</a></span> <span class='nf'>addMessage</span> (\Hirudo\Core\Util\Message message)

<div class="details">
<p></p><dl>
<dt>Returns:</dt>
<dd>$this</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Context/Page.php#L64" target='_blank'>framework\Hirudo\Core\Context\Page.php at line 64</a>

<h3 id="addBreadcrumb()">addBreadcrumb</h3>
<span class='k'></span> <span class='nx'><a href='https://github.com/JeyDotC/Hirudo-docs/blob/master/Hirudo/Core/Context/Page.md>Page</a></span> <span class='nf'>addBreadcrumb</span> (string title, string url)

<div class="details">
<p></p><dl>
<dt>Returns:</dt>
<dd>$this</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Context/Page.php#L69" target='_blank'>framework\Hirudo\Core\Context\Page.php at line 69</a>

<h3 id="renderTitle()">renderTitle</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>renderTitle</span> ()

<div class="details">
<p></p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Context/Page.php#L74" target='_blank'>framework\Hirudo\Core\Context\Page.php at line 74</a>

<h3 id="renderHeading()">renderHeading</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>renderHeading</span> ()

<div class="details">
<p></p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Context/Page.php#L79" target='_blank'>framework\Hirudo\Core\Context\Page.php at line 79</a>

<h3 id="renderMessages()">renderMessages</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>renderMessages</span> ()

<div class="details">
<p></p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Context/Page.php#L84" target='_blank'>framework\Hirudo\Core\Context\Page.php at line 84</a>

<h3 id="renderBreadcrumbs()">renderBreadcrumbs</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>renderBreadcrumbs</span> ()

<div class="details">
<p></p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Context/Page.php#L89" target='_blank'>framework\Hirudo\Core\Context\Page.php at line 89</a>

<h3 id="getTitle()">getTitle</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getTitle</span> ()

<div class="details">
<p></p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Context/Page.php#L94" target='_blank'>framework\Hirudo\Core\Context\Page.php at line 94</a>

<h3 id="getHeading()">getHeading</h3>
<span class='k'></span> <span class='nx'>string</span> <span class='nf'>getHeading</span> ()

<div class="details">
<p></p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Context/Page.php#L99" target='_blank'>framework\Hirudo\Core\Context\Page.php at line 99</a>

<h3 id="getMessages()">getMessages</h3>
<span class='k'></span> <span class='nx'>array<Message></span> <span class='nf'>getMessages</span> ()

<div class="details">
<p></p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/Hirudo/Core/Context/Page.php#L104" target='_blank'>framework\Hirudo\Core\Context\Page.php at line 104</a>

<h3 id="getBreadcrumbs()">getBreadcrumbs</h3>
<span class='k'></span> <span class='nx'>array<Breadcrumb></span> <span class='nf'>getBreadcrumbs</span> ()

<div class="details">
<p></p>
</div>

- - -

