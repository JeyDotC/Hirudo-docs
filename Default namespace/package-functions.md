- - -

#Functions#

- - -

<table id="summary_function" class="title">
<tr><th colspan="2" class="title">Function Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Default namespace/package-functions.md#if_">if_</a>(boolean condition, mixed isTrue, mixed isFalse)</p><p class="description">Represents a ternary operator.
</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Default namespace/package-functions.md#new_">new_</a>(string className, mixed _)</p><p class="description">This function is intended to be used in a template to create new instances of
objects.
</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Default namespace/package-functions.md#smarty_block_page_breadcrumbs">smarty_block_page_breadcrumbs</a>(mixed params, mixed content, Smarty_Internal_Template template, mixed repeat)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Default namespace/package-functions.md#smarty_block_page_messages">smarty_block_page_messages</a>(mixed params, mixed content, Smarty_Internal_Template template, mixed repeat)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Default namespace/package-functions.md#smarty_function_bind">smarty_function_bind</a>(array params, Smarty_Internal_Template template)</p><p class="description">Binds a field to an entity property, Generally a parameter
of a task. </p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Default namespace/package-functions.md#smarty_function_css">smarty_function_css</a>(array params, type template)</p><p class="description">Generates a css link tag. </p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Default namespace/package-functions.md#smarty_function_js">smarty_function_js</a>(array params, type template)</p><p class="description">Generates a script tag. </p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Default namespace/package-functions.md#smarty_function_page_add_breadcrumb">smarty_function_page_add_breadcrumb</a>(mixed params, mixed template)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Default namespace/package-functions.md#smarty_function_page_add_message">smarty_function_page_add_message</a>(mixed params, mixed template)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Default namespace/package-functions.md#smarty_function_page_title">smarty_function_page_title</a>(mixed params, mixed template)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Default namespace/package-functions.md#smarty_function_url">smarty_function_url</a>(array params, Smarty_Internal_Template template)</p><p class="description">Returns a URL based on the string given in the call attribute.
</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Default namespace/package-functions.md#smarty_modifier_toassetpath">smarty_modifier_toAssetPath</a>(string string)</p><p class="description">Converts the given string into a valid absolute path like smarty_modifier_toPath
plugin, but in this time the path has only three parts, the application, the
module and the view name, so any view from any module can be included or inherited.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Default namespace/package-functions.md#smarty_modifier_topath">smarty_modifier_toPath</a>(string string, string extension)</p><p class="description">Converts the given string into a valid absolute path using the
<a href="../hirudo/lang/loader.html#toSinglePath()">Loader::toSinglePath()</a> method.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>string</span></td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Default namespace/package-functions.md#smarty_modifier_toviewpath">smarty_modifier_toViewPath</a>(string string)</p><p class="description">Converts the given string into a valid absolute path like smarty_modifier_toPath
plugin, but in this time the path has only three parts, the application, the
module and the view name, so any view from any module can be included or inherited.</p></td>
</tr>
</table>

<h2 id="detail_function">Function Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/Common/Templating/helperFunctions.php#L32" target='_blank'>framework\Hirudo\Impl\Common\Templating\helperFunctions.php at line 32</a>

<h3 id="if_()">if_</h3>
<span class='k'></span> <span class='nx'>mixed</span> if_ (boolean condition, mixed isTrue, mixed isFalse)

<div class="details">
<p>Represents a ternary operator.</p><p>Usage: {$value = if_($myCondition == true, "A value", "else value which is optional.")}</p>
<dl>
<dt>Parameters:</dt>
<dd>condition - the condition to be tested.</dd>
<dd>isTrue - The value returned if true.</dd>
<dd>isFalse - The value returned if false.</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/Common/Templating/helperFunctions.php#L14" target='_blank'>framework\Hirudo\Impl\Common\Templating\helperFunctions.php at line 14</a>

<h3 id="new_()">new_</h3>
<span class='k'></span> <span class='nx'>mixed</span> new_ (string className, mixed _)

<div class="details">
<p>This function is intended to be used in a template to create new instances of
objects.</p><p>Usage: {$value = new_("My\Class", $param1, "Another param")}</p>
<dl>
<dt>Parameters:</dt>
<dd>className - The class to be instantiated.</dd>
<dd>_ - Constructor parameters.</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/Common/Templating/SmartyTemplatingPlugins/block.page_breadcrumbs.php#L3" target='_blank'>framework\Hirudo\Impl\Common\Templating\SmartyTemplatingPlugins\block.page_breadcrumbs.php at line 3</a>

<h3 id="smarty_block_page_breadcrumbs()">smarty_block_page_breadcrumbs</h3>
<span class='k'></span> <span class='nx'>void</span> smarty_block_page_breadcrumbs (mixed params, mixed content, Smarty_Internal_Template template, mixed repeat)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/Common/Templating/SmartyTemplatingPlugins/block.page_messages.php#L3" target='_blank'>framework\Hirudo\Impl\Common\Templating\SmartyTemplatingPlugins\block.page_messages.php at line 3</a>

<h3 id="smarty_block_page_messages()">smarty_block_page_messages</h3>
<span class='k'></span> <span class='nx'>void</span> smarty_block_page_messages (mixed params, mixed content, Smarty_Internal_Template template, mixed repeat)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/Drupal/Templating/SmartyTemplatingPlugins/function.bind.php#L40" target='_blank'>framework\Hirudo\Impl\Drupal\Templating\SmartyTemplatingPlugins\function.bind.php at line 40</a>

<h3 id="smarty_function_bind()">smarty_function_bind</h3>
<span class='k'></span> <span class='nx'>string</span> smarty_function_bind (array params, Smarty_Internal_Template template)

<div class="details">
<p><p>Binds a field to an entity property, Generally a parameter
of a task. Usage:
<code>
<input {bind="taskParameter.property.innerProperty"} id="myField" type="someType" />
</code></p></p><p><p>Note the absence of the <strong>name=</strong> attribute, the attribute is generated
by this method. In fact, the same thing can be achieved by just using the array-like
naming, like this:
<code>
<input name="taskParameter[property][innerProperty]" id="myField" type="someType" />
</code></p></p>
<dl>
<dt>Returns:</dt>
<dd>The resulting name attribute.</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/Drupal/Templating/SmartyTemplatingPlugins/function.css.php#L16" target='_blank'>framework\Hirudo\Impl\Drupal\Templating\SmartyTemplatingPlugins\function.css.php at line 16</a>

<h3 id="smarty_function_css()">smarty_function_css</h3>
<span class='k'></span> <span class='nx'>string</span> smarty_function_css (array params, type template)

<div class="details">
<p>Generates a css link tag.
Usage: <code>{css file="path/to/my/cssFile.css"}</code></p>
<dl>
<dt>Returns:</dt>
<dd>The resulting link tag.</dd>
<dt>See Also:</dt>
<dd><a href="../hirudo/core/context/assets.html">For more information about assets management.</a></dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/Drupal/Templating/SmartyTemplatingPlugins/function.js.php#L16" target='_blank'>framework\Hirudo\Impl\Drupal\Templating\SmartyTemplatingPlugins\function.js.php at line 16</a>

<h3 id="smarty_function_js()">smarty_function_js</h3>
<span class='k'></span> <span class='nx'>string</span> smarty_function_js (array params, type template)

<div class="details">
<p>Generates a script tag.
Usage: <code>{script file="path/to/my/jsFile.js"}</code></p>
<dl>
<dt>Returns:</dt>
<dd>The resulting script tag.</dd>
<dt>See Also:</dt>
<dd><a href="../hirudo/core/context/assets.html">For more information about assets management.</a></dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/Common/Templating/SmartyTemplatingPlugins/function.page_add_breadcrumb.php#L6" target='_blank'>framework\Hirudo\Impl\Common\Templating\SmartyTemplatingPlugins\function.page_add_breadcrumb.php at line 6</a>

<h3 id="smarty_function_page_add_breadcrumb()">smarty_function_page_add_breadcrumb</h3>
<span class='k'></span> <span class='nx'>void</span> smarty_function_page_add_breadcrumb (mixed params, mixed template)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/Common/Templating/SmartyTemplatingPlugins/function.page_add_message.php#L7" target='_blank'>framework\Hirudo\Impl\Common\Templating\SmartyTemplatingPlugins\function.page_add_message.php at line 7</a>

<h3 id="smarty_function_page_add_message()">smarty_function_page_add_message</h3>
<span class='k'></span> <span class='nx'>void</span> smarty_function_page_add_message (mixed params, mixed template)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/Common/Templating/SmartyTemplatingPlugins/function.page_title.php#L3" target='_blank'>framework\Hirudo\Impl\Common\Templating\SmartyTemplatingPlugins\function.page_title.php at line 3</a>

<h3 id="smarty_function_page_title()">smarty_function_page_title</h3>
<span class='k'></span> <span class='nx'>void</span> smarty_function_page_title (mixed params, mixed template)

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/Drupal/Templating/SmartyTemplatingPlugins/function.url.php#L45" target='_blank'>framework\Hirudo\Impl\Drupal\Templating\SmartyTemplatingPlugins\function.url.php at line 45</a>

<h3 id="smarty_function_url()">smarty_function_url</h3>
<span class='k'></span> <span class='nx'>string</span> smarty_function_url (array params, Smarty_Internal_Template template)

<div class="details">
<p>Returns a URL based on the string given in the call attribute.
Usage: <code>{url call="AppName::ModuleName::taskName"}</code> Any extra
parameters will be used as params for the url. For example, if we have:
<code>{url call="AppName::ModuleName::taskName" id=123 name="MyName"}</code>
the resulting url will be the same if we called:
<code>
$aRoutingObject->appAction("AppName", "ModuleName", "taskName",
array(
"id"=>123,
"name"=>"MyName"
)
);
</code></p>
<dl>
<dt>Returns:</dt>
<dd>The generated URL.</dd>
<dt>See Also:</dt>
<dd><a href="../hirudo/core/context/routing.html">For more information about Hirudo URLs</a></dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/Drupal/Templating/SmartyTemplatingPlugins/modifier.toAssetPath.php#L39" target='_blank'>framework\Hirudo\Impl\Drupal\Templating\SmartyTemplatingPlugins\modifier.toAssetPath.php at line 39</a>

<h3 id="smarty_modifier_toAssetPath()">smarty_modifier_toAssetPath</h3>
<span class='k'></span> <span class='nx'>string</span> smarty_modifier_toAssetPath (string string)

<div class="details">
<p><p>Converts the given string into a valid absolute path like smarty_modifier_toPath
plugin, but in this time the path has only three parts, the application, the
module and the view name, so any view from any module can be included or inherited.</p>
<dl>
<dt>Parameters:</dt>
<dd>string - The complete name of the view with format AppName::ModuleName::viewName</dd>
<dt>Returns:</dt>
<dd>The resulting path.</dd>
<dt>See Also:</dt>
<dd><a href="../hirudo/lang/loader.html#using()">For details about the string format required by this method.</a></dd>
<dt>Throws:</dt>
<dd><a href="../hirudo/lang/invalidpathexception.html">InvalidPathException</a> - If $string is not a string, is null or is empty.</dd>
<dd>LogicException - If $extension is not a string.</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/Drupal/Templating/SmartyTemplatingPlugins/modifier.toPath.php#L39" target='_blank'>framework\Hirudo\Impl\Drupal\Templating\SmartyTemplatingPlugins\modifier.toPath.php at line 39</a>

<h3 id="smarty_modifier_toPath()">smarty_modifier_toPath</h3>
<span class='k'></span> <span class='nx'>string</span> smarty_modifier_toPath (string string, string extension)

<div class="details">
<p><p>Converts the given string into a valid absolute path using the
<code><a href="../hirudo/lang/loader.html#toSinglePath()">Loader::toSinglePath()</a></code> method.</p></p>
<dl>
<dt>Parameters:</dt>
<dd>string - The path to be converted.</dd>
<dd>extension - = ".tpl" The extension of the required path.</dd>
<dt>Returns:</dt>
<dd>The resulting path.</dd>
<dt>See Also:</dt>
<dd><a href="../hirudo/lang/loader.html#using()">For details about the string format required by this method.</a></dd>
<dt>Throws:</dt>
<dd><a href="../hirudo/lang/invalidpathexception.html">InvalidPathException</a> - If $string is not a string, is null or is empty.</dd>
<dd>LogicException - If $extension is not a string.</dd>
</dl>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/Drupal/Templating/SmartyTemplatingPlugins/modifier.toViewPath.php#L39" target='_blank'>framework\Hirudo\Impl\Drupal\Templating\SmartyTemplatingPlugins\modifier.toViewPath.php at line 39</a>

<h3 id="smarty_modifier_toViewPath()">smarty_modifier_toViewPath</h3>
<span class='k'></span> <span class='nx'>string</span> smarty_modifier_toViewPath (string string)

<div class="details">
<p><p>Converts the given string into a valid absolute path like smarty_modifier_toPath
plugin, but in this time the path has only three parts, the application, the
module and the view name, so any view from any module can be included or inherited.</p>
<dl>
<dt>Parameters:</dt>
<dd>string - The complete name of the view with format AppName::ModuleName::viewName</dd>
<dt>Returns:</dt>
<dd>The resulting path.</dd>
<dt>See Also:</dt>
<dd><a href="../hirudo/lang/loader.html#using()">For details about the string format required by this method.</a></dd>
<dt>Throws:</dt>
<dd><a href="../hirudo/lang/invalidpathexception.html">InvalidPathException</a> - If $string is not a string, is null or is empty.</dd>
<dd>LogicException - If $extension is not a string.</dd>
</dl>
</div>

- - -

