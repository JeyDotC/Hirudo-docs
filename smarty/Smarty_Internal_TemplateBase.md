- - -

**Smarty\Smarty_Internal_TemplateBase**
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_templatebase.php at line 18</div>
#Class Smarty_Internal_TemplateBase#

<a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html">Smarty_Internal_Data</a>
    ***Smarty_Internal_TemplateBase**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty.html">Smarty</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_template.html">Smarty_Internal_Template</a> </dd>
</dl>

- - -

<p class="signature">public abstract  class **Smarty_Internal_TemplateBase**
extends <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html">Smarty_Internal_Data</a>

</p>

<div class="comment" id="overview_description"><p>Class with shared template methodes</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>Template</dd>
</dl>
- - -

<table class="inherit">
<tr><th colspan="2">Fields inherited from Smarty\Smarty_Internal_Data</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#config_vars">config_vars</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#parent">parent</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#template_class">template_class</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#tpl_vars">tpl_vars</a></td></tr></table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#fetch">fetch</a>(string template, mixed cache_id, mixed compile_id, object parent, bool display, bool merge_tpl_vars, bool no_output_filter)</p><p class="description">fetches a rendered Smarty template</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#display">display</a>(string template, mixed cache_id, mixed compile_id, object parent)</p><p class="description">displays a Smarty template</p></td>
</tr>
<tr>
<td class="type"> boolean</td>
<td class="description"><p class="name"><a href="#isCached">isCached</a>(string|object template, mixed cache_id, mixed compile_id, object parent)</p><p class="description">test if cache is valid</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#createData">createData</a>(object parent)</p><p class="description">creates a data object</p></td>
</tr>
<tr>
<td class="type"> Smarty_Internal_Templatebase</td>
<td class="description"><p class="name"><a href="#registerPlugin">registerPlugin</a>(string type, string tag, callback callback, boolean cacheable, array cache_attr)</p><p class="description">Registers plugin to be used in templates</p></td>
</tr>
<tr>
<td class="type"> Smarty_Internal_Templatebase</td>
<td class="description"><p class="name"><a href="#unregisterPlugin">unregisterPlugin</a>(string type, string tag)</p><p class="description">Unregister Plugin</p></td>
</tr>
<tr>
<td class="type"> Smarty_Internal_Templatebase</td>
<td class="description"><p class="name"><a href="#registerResource">registerResource</a>(string type, Smarty_Resource|array callback)</p><p class="description">Registers a resource to fetch a template</p></td>
</tr>
<tr>
<td class="type"> Smarty_Internal_Templatebase</td>
<td class="description"><p class="name"><a href="#unregisterResource">unregisterResource</a>(string type)</p><p class="description">Unregisters a resource</p></td>
</tr>
<tr>
<td class="type"> Smarty_Internal_Templatebase</td>
<td class="description"><p class="name"><a href="#registerCacheResource">registerCacheResource</a>(string type, <a href="../smarty/smarty_cacheresource.html">Smarty_CacheResource</a> callback)</p><p class="description">Registers a cache resource to cache a template's output</p></td>
</tr>
<tr>
<td class="type"> Smarty_Internal_Templatebase</td>
<td class="description"><p class="name"><a href="#unregisterCacheResource">unregisterCacheResource</a>(string type)</p><p class="description">Unregisters a cache resource</p></td>
</tr>
<tr>
<td class="type"> Smarty_Internal_Templatebase</td>
<td class="description"><p class="name"><a href="#registerObject">registerObject</a>(string object, object object_impl, array allowed, boolean smarty_args, array block_methods, array block_functs, mixed object_name)</p><p class="description">Registers object to be used in templates</p></td>
</tr>
<tr>
<td class="type"> object</td>
<td class="description"><p class="name"><a href="#getRegisteredObject">getRegisteredObject</a>(string name)</p><p class="description">return a reference to a registered object</p></td>
</tr>
<tr>
<td class="type"> Smarty_Internal_Templatebase</td>
<td class="description"><p class="name"><a href="#unregisterObject">unregisterObject</a>(string name)</p><p class="description">unregister an object</p></td>
</tr>
<tr>
<td class="type"> Smarty_Internal_Templatebase</td>
<td class="description"><p class="name"><a href="#registerClass">registerClass</a>(string class, string class_impl, mixed class_name)</p><p class="description">Registers static classes to be used in templates</p></td>
</tr>
<tr>
<td class="type"> Smarty_Internal_Templatebase</td>
<td class="description"><p class="name"><a href="#registerDefaultPluginHandler">registerDefaultPluginHandler</a>(callable callback)</p><p class="description">Registers a default plugin handler</p></td>
</tr>
<tr>
<td class="type"> Smarty_Internal_Templatebase</td>
<td class="description"><p class="name"><a href="#registerDefaultTemplateHandler">registerDefaultTemplateHandler</a>(callable callback)</p><p class="description">Registers a default template handler</p></td>
</tr>
<tr>
<td class="type"> Smarty_Internal_Templatebase</td>
<td class="description"><p class="name"><a href="#registerDefaultConfigHandler">registerDefaultConfigHandler</a>(callable callback)</p><p class="description">Registers a default template handler</p></td>
</tr>
<tr>
<td class="type"> Smarty_Internal_Templatebase</td>
<td class="description"><p class="name"><a href="#registerFilter">registerFilter</a>(string type, callback callback)</p><p class="description">Registers a filter function</p></td>
</tr>
<tr>
<td class="type"> Smarty_Internal_Templatebase</td>
<td class="description"><p class="name"><a href="#unregisterFilter">unregisterFilter</a>(string type, callback callback)</p><p class="description">Unregisters a filter function</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#loadFilter">loadFilter</a>(string type, string name)</p><p class="description">load a filter of specified type and name</p></td>
</tr>
<tr>
<td class="type"> Smarty_Internal_Templatebase</td>
<td class="description"><p class="name"><a href="#unloadFilter">unloadFilter</a>(string type, string name)</p><p class="description">unload a filter of specified type and name</p></td>
</tr>
</table>

<table class="inherit">
<tr><th colspan="2">Methods inherited from Smarty\Smarty_Internal_Data</th></tr>
<tr><td><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#append()">append</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#appendByRef()">appendByRef</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#assign()">assign</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#assignByRef()">assignByRef</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#assignGlobal()">assignGlobal</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#clearAllAssign()">clearAllAssign</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#clearAssign()">clearAssign</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#clearConfig()">clearConfig</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#configLoad()">configLoad</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#getConfigVariable()">getConfigVariable</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#getConfigVars()">getConfigVars</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#getStreamVariable()">getStreamVariable</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#getTemplateVars()">getTemplateVars</a>, <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_internal_data.html#getVariable()">getVariable</a></td></tr></table>

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\smarty\sysplugins\smarty_internal_templatebase.php at line 32</div>
<h3 id="fetch()">fetch</h3>

```php
public  string **fetch**(string template, mixed cache_id, mixed compile_id, object parent, bool display, bool merge_tpl_vars, bool no_output_filter)
```
<div class="details">
<p>fetches a rendered Smarty template</p><dl>
<dt>Parameters:</dt>
<dd>template - the resource handle of the template file or template object</dd>
<dd>cache_id - cache id to be used with this template</dd>
<dd>compile_id - compile id to be used with this template</dd>
<dd>parent - next higher level of Smarty variables</dd>
<dd>display - true: display, false: fetch</dd>
<dd>merge_tpl_vars - if true parent template variables merged in to local scope</dd>
<dd>no_output_filter - if true do not run output filter</dd>
<dt>Returns:</dt>
<dd>rendered template output</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_templatebase.php at line 371</div>
<h3 id="display()">display</h3>

```php
public  void **display**(string template, mixed cache_id, mixed compile_id, object parent)
```
<div class="details">
<p>displays a Smarty template</p><dl>
<dt>Parameters:</dt>
<dd>template - the resource handle of the template file or template object</dd>
<dd>cache_id - cache id to be used with this template</dd>
<dd>compile_id - compile id to be used with this template</dd>
<dd>parent - next higher level of Smarty variables</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_templatebase.php at line 386</div>
<h3 id="isCached()">isCached</h3>

```php
public  boolean **isCached**(string|object template, mixed cache_id, mixed compile_id, object parent)
```
<div class="details">
<p>test if cache is valid</p><dl>
<dt>Parameters:</dt>
<dd>template - the resource handle of the template file or template object</dd>
<dd>cache_id - cache id to be used with this template</dd>
<dd>compile_id - compile id to be used with this template</dd>
<dd>parent - next higher level of Smarty variables</dd>
<dt>Returns:</dt>
<dd>cache status</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_templatebase.php at line 407</div>
<h3 id="createData()">createData</h3>

```php
public  void **createData**(object parent)
```
<div class="details">
<p>creates a data object</p><dl>
<dt>Parameters:</dt>
<dd>parent - next higher level of Smarty variables</dd>
<dt>Returns:</dt>
<dd>Smarty_Data data object</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_templatebase.php at line 423</div>
<h3 id="registerPlugin()">registerPlugin</h3>

```php
public  Smarty_Internal_Templatebase **registerPlugin**(string type, string tag, callback callback, boolean cacheable, array cache_attr)
```
<div class="details">
<p>Registers plugin to be used in templates</p><dl>
<dt>Parameters:</dt>
<dd>type - plugin type</dd>
<dd>tag - name of template tag</dd>
<dd>callback - PHP callback to register</dd>
<dd>cacheable - if true (default) this fuction is cachable</dd>
<dd>cache_attr - caching attributes if any</dd>
<dt>Returns:</dt>
<dd>current Smarty_Internal_Templatebase (or Smarty or Smarty_Internal_Template) instance for chaining</dd>
<dt>Throws:</dt>
<dd><a href="../smarty/smartyexception.html">SmartyException</a> - when the plugin tag is invalid</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_templatebase.php at line 443</div>
<h3 id="unregisterPlugin()">unregisterPlugin</h3>

```php
public  Smarty_Internal_Templatebase **unregisterPlugin**(string type, string tag)
```
<div class="details">
<p>Unregister Plugin</p><dl>
<dt>Parameters:</dt>
<dd>type - of plugin</dd>
<dd>tag - name of plugin</dd>
<dt>Returns:</dt>
<dd>current Smarty_Internal_Templatebase (or Smarty or Smarty_Internal_Template) instance for chaining</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_templatebase.php at line 459</div>
<h3 id="registerResource()">registerResource</h3>

```php
public  Smarty_Internal_Templatebase **registerResource**(string type, Smarty_Resource|array callback)
```
<div class="details">
<p>Registers a resource to fetch a template</p><dl>
<dt>Parameters:</dt>
<dd>type - name of resource type</dd>
<dd>callback - or instance of Smarty_Resource, or array of callbacks to handle resource (deprecated)</dd>
<dt>Returns:</dt>
<dd>current Smarty_Internal_Templatebase (or Smarty or Smarty_Internal_Template) instance for chaining</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_templatebase.php at line 471</div>
<h3 id="unregisterResource()">unregisterResource</h3>

```php
public  Smarty_Internal_Templatebase **unregisterResource**(string type)
```
<div class="details">
<p>Unregisters a resource</p><dl>
<dt>Parameters:</dt>
<dd>type - name of resource type</dd>
<dt>Returns:</dt>
<dd>current Smarty_Internal_Templatebase (or Smarty or Smarty_Internal_Template) instance for chaining</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_templatebase.php at line 487</div>
<h3 id="registerCacheResource()">registerCacheResource</h3>

```php
public  Smarty_Internal_Templatebase **registerCacheResource**(string type, <a href="../smarty/smarty_cacheresource.html">Smarty_CacheResource</a> callback)
```
<div class="details">
<p>Registers a cache resource to cache a template's output</p><dl>
<dt>Parameters:</dt>
<dd>type - name of cache resource type</dd>
<dd>callback - instance of Smarty_CacheResource to handle output caching</dd>
<dt>Returns:</dt>
<dd>current Smarty_Internal_Templatebase (or Smarty or Smarty_Internal_Template) instance for chaining</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_templatebase.php at line 499</div>
<h3 id="unregisterCacheResource()">unregisterCacheResource</h3>

```php
public  Smarty_Internal_Templatebase **unregisterCacheResource**(string type)
```
<div class="details">
<p>Unregisters a cache resource</p><dl>
<dt>Parameters:</dt>
<dd>type - name of cache resource type</dd>
<dt>Returns:</dt>
<dd>current Smarty_Internal_Templatebase (or Smarty or Smarty_Internal_Template) instance for chaining</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_templatebase.php at line 520</div>
<h3 id="registerObject()">registerObject</h3>

```php
public  Smarty_Internal_Templatebase **registerObject**(string object, object object_impl, array allowed, boolean smarty_args, array block_methods, array block_functs, mixed object_name)
```
<div class="details">
<p>Registers object to be used in templates</p><dl>
<dt>Parameters:</dt>
<dd>object - name of template object</dd>
<dd>object_impl - the referenced PHP object to register</dd>
<dd>allowed - list of allowed methods (empty = all)</dd>
<dd>smarty_args - smarty argument format, else traditional</dd>
<dd>block_methods - list of block-methods</dd>
<dd>block_functs - list of methods that are block format</dd>
<dt>Returns:</dt>
<dd>current Smarty_Internal_Templatebase (or Smarty or Smarty_Internal_Template) instance for chaining</dd>
<dt>Throws:</dt>
<dd><a href="../smarty/smartyexception.html">SmartyException</a> - if any of the methods in $allowed or $block_methods are invalid</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_templatebase.php at line 551</div>
<h3 id="getRegisteredObject()">getRegisteredObject</h3>

```php
public  object **getRegisteredObject**(string name)
```
<div class="details">
<p>return a reference to a registered object</p><dl>
<dt>Parameters:</dt>
<dd>name - object name</dd>
<dt>Throws:</dt>
<dd><a href="../smarty/smartyexception.html">SmartyException</a> - if no such object is found</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_templatebase.php at line 568</div>
<h3 id="unregisterObject()">unregisterObject</h3>

```php
public  Smarty_Internal_Templatebase **unregisterObject**(string name)
```
<div class="details">
<p>unregister an object</p><dl>
<dt>Parameters:</dt>
<dd>name - object name</dd>
<dt>Returns:</dt>
<dd>current Smarty_Internal_Templatebase (or Smarty or Smarty_Internal_Template) instance for chaining</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_templatebase.php at line 585</div>
<h3 id="registerClass()">registerClass</h3>

```php
public  Smarty_Internal_Templatebase **registerClass**(string class, string class_impl, mixed class_name)
```
<div class="details">
<p>Registers static classes to be used in templates</p><dl>
<dt>Parameters:</dt>
<dd>class - name of template class</dd>
<dd>class_impl - the referenced PHP class to register</dd>
<dt>Returns:</dt>
<dd>current Smarty_Internal_Templatebase (or Smarty or Smarty_Internal_Template) instance for chaining</dd>
<dt>Throws:</dt>
<dd><a href="../smarty/smartyexception.html">SmartyException</a> - if $class_impl does not refer to an existing class</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_templatebase.php at line 603</div>
<h3 id="registerDefaultPluginHandler()">registerDefaultPluginHandler</h3>

```php
public  Smarty_Internal_Templatebase **registerDefaultPluginHandler**(callable callback)
```
<div class="details">
<p>Registers a default plugin handler</p><dl>
<dt>Parameters:</dt>
<dd>callback - class/method name</dd>
<dt>Returns:</dt>
<dd>current Smarty_Internal_Templatebase (or Smarty or Smarty_Internal_Template) instance for chaining</dd>
<dt>Throws:</dt>
<dd><a href="../smarty/smartyexception.html">SmartyException</a> - if $callback is not callable</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_templatebase.php at line 621</div>
<h3 id="registerDefaultTemplateHandler()">registerDefaultTemplateHandler</h3>

```php
public  Smarty_Internal_Templatebase **registerDefaultTemplateHandler**(callable callback)
```
<div class="details">
<p>Registers a default template handler</p><dl>
<dt>Parameters:</dt>
<dd>callback - class/method name</dd>
<dt>Returns:</dt>
<dd>current Smarty_Internal_Templatebase (or Smarty or Smarty_Internal_Template) instance for chaining</dd>
<dt>Throws:</dt>
<dd><a href="../smarty/smartyexception.html">SmartyException</a> - if $callback is not callable</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_templatebase.php at line 639</div>
<h3 id="registerDefaultConfigHandler()">registerDefaultConfigHandler</h3>

```php
public  Smarty_Internal_Templatebase **registerDefaultConfigHandler**(callable callback)
```
<div class="details">
<p>Registers a default template handler</p><dl>
<dt>Parameters:</dt>
<dd>callback - class/method name</dd>
<dt>Returns:</dt>
<dd>current Smarty_Internal_Templatebase (or Smarty or Smarty_Internal_Template) instance for chaining</dd>
<dt>Throws:</dt>
<dd><a href="../smarty/smartyexception.html">SmartyException</a> - if $callback is not callable</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_templatebase.php at line 657</div>
<h3 id="registerFilter()">registerFilter</h3>

```php
public  Smarty_Internal_Templatebase **registerFilter**(string type, callback callback)
```
<div class="details">
<p>Registers a filter function</p><dl>
<dt>Parameters:</dt>
<dd>type - filter type</dd>
<dd></dd>
<dt>Returns:</dt>
<dd>current Smarty_Internal_Templatebase (or Smarty or Smarty_Internal_Template) instance for chaining</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_templatebase.php at line 670</div>
<h3 id="unregisterFilter()">unregisterFilter</h3>

```php
public  Smarty_Internal_Templatebase **unregisterFilter**(string type, callback callback)
```
<div class="details">
<p>Unregisters a filter function</p><dl>
<dt>Parameters:</dt>
<dd>type - filter type</dd>
<dd></dd>
<dt>Returns:</dt>
<dd>current Smarty_Internal_Templatebase (or Smarty or Smarty_Internal_Template) instance for chaining</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_templatebase.php at line 704</div>
<h3 id="loadFilter()">loadFilter</h3>

```php
public  void **loadFilter**(string type, string name)
```
<div class="details">
<p>load a filter of specified type and name</p><dl>
<dt>Parameters:</dt>
<dd>type - filter type</dd>
<dd>name - filter name</dd>
<dt>Throws:</dt>
<dd><a href="../smarty/smartyexception.html">SmartyException</a> - if filter could not be loaded</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_internal_templatebase.php at line 727</div>
<h3 id="unloadFilter()">unloadFilter</h3>

```php
public  Smarty_Internal_Templatebase **unloadFilter**(string type, string name)
```
<div class="details">
<p>unload a filter of specified type and name</p><dl>
<dt>Parameters:</dt>
<dd>type - filter type</dd>
<dd>name - filter name</dd>
<dt>Returns:</dt>
<dd>current Smarty_Internal_Templatebase (or Smarty or Smarty_Internal_Template) instance for chaining</dd>
</dl>
</div>

- - -

