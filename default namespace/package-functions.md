- - -

# Functions #

- - -

<table id="summary_function" class="title">
<tr><th colspan="2" class="title">Function Summary</th></tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#smarty_function_bind()">smarty_function_bind</a>(array params, <a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> template)</p><p class="description">Binds a field to an entity property, Generally a parameter
of a task. </p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#smarty_function_css()">smarty_function_css</a>(array params, type template)</p><p class="description">Generates a script tag. </p></td>
</tr>
<tr>
<td class="type"> <type></td>
<td class="description"><p class="name"><a href="#smarty_function_foo()">smarty_function_foo</a>(array params, <a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> template)</p><p class="description"></p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#smarty_function_url()">smarty_function_url</a>(array params, <a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> template)</p><p class="description">Returns a URL based on the string given in the call attribute.
</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#smarty_modifier_toPath()">smarty_modifier_toPath</a>(string string, string extension)</p><p class="description">Converts the given string into a valid absolute path using the
<a href="../hirudo/lang/loader.html#toSinglePath()">Loader::toSinglePath()</a> method.</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#smarty_modifier_toViewPath()">smarty_modifier_toViewPath</a>(string string)</p><p class="description">Converts the given string into a valid absolute path like smarty_modifier_toPath
plugin, but in this time the path has only three parts, the application, the
module and the view name, so any view from any module can be included or inherited.</p></td>
</tr>
</table>

<h2 id="detail_function">Function Detail</h2>
<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Impl/Common/Templating/SmartyTemplatingPlugins/function.bind.php.md#line40" class="location">framework\hirudo\Hirudo\Impl\Common\Templating\SmartyTemplatingPlugins\function.bind.php at line 40</a>

<h3 id="smarty_function_bind()">smarty_function_bind</h3>
```php
public  string **smarty_function_bind**(array params, <a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> template)```
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

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Impl/Common/Templating/SmartyTemplatingPlugins/function.js.php.md#line16" class="location">framework\hirudo\Hirudo\Impl\Common\Templating\SmartyTemplatingPlugins\function.js.php at line 16</a>

<h3 id="smarty_function_css()">smarty_function_css</h3>
```php
public  string **smarty_function_css**(array params, type template)```
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

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/ext/libs/SampleExtension/Sample/SmartyExtensions/function.foo.php.md#line29" class="location">ext\libs\SampleExtension\Sample\SmartyExtensions\function.foo.php at line 29</a>

<h3 id="smarty_function_foo()">smarty_function_foo</h3>
```php
public  <type> **smarty_function_foo**(array params, <a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> template)```
<div class="details">
<p></p>
</div>

- - -

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Impl/Common/Templating/SmartyTemplatingPlugins/function.url.php.md#line45" class="location">framework\hirudo\Hirudo\Impl\Common\Templating\SmartyTemplatingPlugins\function.url.php at line 45</a>

<h3 id="smarty_function_url()">smarty_function_url</h3>
```php
public  string **smarty_function_url**(array params, <a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> template)```
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

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Impl/Common/Templating/SmartyTemplatingPlugins/modifier.toPath.php.md#line39" class="location">framework\hirudo\Hirudo\Impl\Common\Templating\SmartyTemplatingPlugins\modifier.toPath.php at line 39</a>

<h3 id="smarty_modifier_toPath()">smarty_modifier_toPath</h3>
```php
public  string **smarty_modifier_toPath**(string string, string extension)```
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

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/source/framework/hirudo/Hirudo/Impl/Common/Templating/SmartyTemplatingPlugins/modifier.toViewPath.php.md#line39" class="location">framework\hirudo\Hirudo\Impl\Common\Templating\SmartyTemplatingPlugins\modifier.toViewPath.php at line 39</a>

<h3 id="smarty_modifier_toViewPath()">smarty_modifier_toViewPath</h3>
```php
public  string **smarty_modifier_toViewPath**(string string)```
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

