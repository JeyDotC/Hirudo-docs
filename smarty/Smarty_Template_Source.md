- - -

**Smarty\Smarty_Template_Source**
<div class="location">framework\libs\smarty\sysplugins\smarty_resource.php at line 557</div>
#Class Smarty_Template_Source#

**Smarty_Template_Source**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/smarty/smarty_config_source.html">Smarty_Config_Source</a> </dd>
</dl>

- - -

<p class="signature">public static  class **Smarty_Template_Source**</p>

<div class="comment" id="overview_description"><p>Smarty Resource Data Object</p><p>Meta Data Container for Template Files</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>TemplateResources</dd>
<dt>Author:</dt>
<dd>Rodney Rehm</dd>
<dt>Property:</dt>
<dd>integer $timestamp Source Timestamp</dd>
<dd>boolean $exists Source Existance</dd>
<dd>boolean $template Extended Template reference</dd>
<dd>string $content Source Content</dd>
</dl>
- - -

<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#compiler_class">$compiler_class</a></p><p class="description">Name of the Class to compile this resource's contents with</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#components">$components</a></p><p class="description">The Components an extended template is made of</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#filepath">$filepath</a></p><p class="description">Source Filepath</p></td>
</tr>
<tr>
<td class="type"> <a href="../smarty/smarty_resource.html">Smarty_Resource</a></td>
<td class="description"><p class="name"><a href="#handler">$handler</a></p><p class="description">Resource Handler</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#name">$name</a></p><p class="description">Resource Name</p></td>
</tr>
<tr>
<td class="type"> boolean</td>
<td class="description"><p class="name"><a href="#recompiled">$recompiled</a></p><p class="description">Source must be recompiled on every occasion</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#resource">$resource</a></p><p class="description">Template Resource (Smarty_Internal_Template::$template_resource)</p></td>
</tr>
<tr>
<td class="type"> <a href="../smarty/smarty.html">Smarty</a></td>
<td class="description"><p class="name"><a href="#smarty">$smarty</a></p><p class="description">Smarty instance</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#template_lexer_class">$template_lexer_class</a></p><p class="description">Name of the Class to tokenize this resource's contents with</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#template_parser_class">$template_parser_class</a></p><p class="description">Name of the Class to parse this resource's contents with</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#type">$type</a></p><p class="description">Resource Type</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#uid">$uid</a></p><p class="description">Unique Template ID</p></td>
</tr>
<tr>
<td class="type"> boolean</td>
<td class="description"><p class="name"><a href="#uncompiled">$uncompiled</a></p><p class="description">Source is bypassing compiler</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#unique_resource">$unique_resource</a></p><p class="description">Unique Resource Name</p></td>
</tr>
</table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(<a href="../smarty/smarty_resource.html">Smarty_Resource</a> handler, <a href="../smarty/smarty.html">Smarty</a> smarty, string resource, string type, string name, string unique_resource)</p><p class="description">create Source Object container</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type"> <a href="../smarty/smarty_template_compiled.html">Smarty_Template_Compiled</a></td>
<td class="description"><p class="name"><a href="#getCompiled">getCompiled</a>(<a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template)</p><p class="description">get a Compiled Object of this source</p></td>
</tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#renderUncompiled">renderUncompiled</a>(<a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template)</p><p class="description">render the uncompiled source</p></td>
</tr>
</table>

##Field Detail##
<div class="location">framework\libs\smarty\sysplugins\smarty_resource.php at line 563</div>
<h3 id="compiler_class">compiler_class</h3>

```php
public  string$compiler_class = null
```
<div class="details">
<p>Name of the Class to compile this resource's contents with</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_resource.php at line 629</div>
<h3 id="components">components</h3>

```php
public  array$components = null
```
<div class="details">
<p>The Components an extended template is made of</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_resource.php at line 611</div>
<h3 id="filepath">filepath</h3>

```php
public  string$filepath = null
```
<div class="details">
<p>Source Filepath</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_resource.php at line 635</div>
<h3 id="handler">handler</h3>

```php
public  <a href="../smarty/smarty_resource.html">Smarty_Resource</a>$handler = null
```
<div class="details">
<p>Resource Handler</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_resource.php at line 599</div>
<h3 id="name">name</h3>

```php
public  string$name = null
```
<div class="details">
<p>Resource Name</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_resource.php at line 623</div>
<h3 id="recompiled">recompiled</h3>

```php
public  boolean$recompiled = null
```
<div class="details">
<p>Source must be recompiled on every occasion</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_resource.php at line 587</div>
<h3 id="resource">resource</h3>

```php
public  string$resource = null
```
<div class="details">
<p>Template Resource (Smarty_Internal_Template::$template_resource)</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_resource.php at line 641</div>
<h3 id="smarty">smarty</h3>

```php
public  <a href="../smarty/smarty.html">Smarty</a>$smarty = null
```
<div class="details">
<p>Smarty instance</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_resource.php at line 569</div>
<h3 id="template_lexer_class">template_lexer_class</h3>

```php
public  string$template_lexer_class = null
```
<div class="details">
<p>Name of the Class to tokenize this resource's contents with</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_resource.php at line 575</div>
<h3 id="template_parser_class">template_parser_class</h3>

```php
public  string$template_parser_class = null
```
<div class="details">
<p>Name of the Class to parse this resource's contents with</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_resource.php at line 593</div>
<h3 id="type">type</h3>

```php
public  string$type = null
```
<div class="details">
<p>Resource Type</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_resource.php at line 581</div>
<h3 id="uid">uid</h3>

```php
public  string$uid = null
```
<div class="details">
<p>Unique Template ID</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_resource.php at line 617</div>
<h3 id="uncompiled">uncompiled</h3>

```php
public  boolean$uncompiled = null
```
<div class="details">
<p>Source is bypassing compiler</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_resource.php at line 605</div>
<h3 id="unique_resource">unique_resource</h3>

```php
public  string$unique_resource = null
```
<div class="details">
<p>Unique Resource Name</p></div>

- - -

<h2 id="detail_method">Constructor Detail</h2>
<div class="location">framework\libs\smarty\sysplugins\smarty_resource.php at line 653</div>
<h3 id="__construct()">__construct</h3>

```php
public  void **__construct**(<a href="../smarty/smarty_resource.html">Smarty_Resource</a> handler, <a href="../smarty/smarty.html">Smarty</a> smarty, string resource, string type, string name, string unique_resource)
```
<div class="details">
<p>create Source Object container</p><dl>
<dt>Parameters:</dt>
<dd>handler - Resource Handler this source object communicates with</dd>
<dd>smarty - Smarty instance this source object belongs to</dd>
<dd>resource - full template_resource</dd>
<dd>type - type of resource</dd>
<dd>name - resource name</dd>
<dd>unique_resource - unqiue resource name</dd>
</dl>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\smarty\sysplugins\smarty_resource.php at line 676</div>
<h3 id="getCompiled()">getCompiled</h3>

```php
public  <a href="../smarty/smarty_template_compiled.html">Smarty_Template_Compiled</a> **getCompiled**(<a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template)
```
<div class="details">
<p>get a Compiled Object of this source</p><dl>
<dt>Parameters:</dt>
<dd>_template - template objet</dd>
<dt>Returns:</dt>
<dd>compiled object</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_resource.php at line 700</div>
<h3 id="renderUncompiled()">renderUncompiled</h3>

```php
public  void **renderUncompiled**(<a href="../smarty/smarty_internal_template.html">Smarty_Internal_Template</a> _template)
```
<div class="details">
<p>render the uncompiled source</p><dl>
<dt>Parameters:</dt>
<dd>_template - template object</dd>
</dl>
</div>

- - -

