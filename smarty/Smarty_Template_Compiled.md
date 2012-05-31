- - -

**Smarty\Smarty_Template_Compiled**
<div class="location">framework\libs\smarty\sysplugins\smarty_resource.php at line 765</div>
#Class Smarty_Template_Compiled#

**Smarty_Template_Compiled**


- - -

<p class="signature">public  class **Smarty_Template_Compiled**</p>

<div class="comment" id="overview_description"><p>Smarty Resource Data Object</p><p>Meta Data Container for Template Files</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>TemplateResources</dd>
<dt>Author:</dt>
<dd>Rodney Rehm</dd>
<dt>Property:</dt>
<dd>string $content compiled content</dd>
</dl>
- - -

<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#_properties">$_properties</a></p><p class="description">Metadata propertiespopulated by Smarty_Internal_Template::decodeProperties()</p></td>
</tr>
<tr>
<td class="type"> boolean</td>
<td class="description"><p class="name"><a href="#exists">$exists</a></p><p class="description">Compiled Existance</p></td>
</tr>
<tr>
<td class="type"> string</td>
<td class="description"><p class="name"><a href="#filepath">$filepath</a></p><p class="description">Compiled Filepath</p></td>
</tr>
<tr>
<td class="type"> boolean</td>
<td class="description"><p class="name"><a href="#isCompiled">$isCompiled</a></p><p class="description">Template was compiled</p></td>
</tr>
<tr>
<td class="type"> boolean</td>
<td class="description"><p class="name"><a href="#loaded">$loaded</a></p><p class="description">Compiled Content Loaded</p></td>
</tr>
<tr>
<td class="type"> <a href="../smarty/smarty_template_source.html">Smarty_Template_Source</a></td>
<td class="description"><p class="name"><a href="#source">$source</a></p><p class="description">Source Object</p></td>
</tr>
<tr>
<td class="type"> integer</td>
<td class="description"><p class="name"><a href="#timestamp">$timestamp</a></p><p class="description">Compiled Timestamp</p></td>
</tr>
</table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(<a href="../smarty/smarty_template_source.html">Smarty_Template_Source</a> source)</p><p class="description">create Compiled Object container</p></td>
</tr>
</table>

##Field Detail##
<div class="location">framework\libs\smarty\sysplugins\smarty_resource.php at line 809</div>
<h3 id="_properties">_properties</h3>

```php
public  array$_properties = null
```
<div class="details">
<p>Metadata properties</p><p>populated by Smarty_Internal_Template::decodeProperties()</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_resource.php at line 783</div>
<h3 id="exists">exists</h3>

```php
public  boolean$exists = false
```
<div class="details">
<p>Compiled Existance</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_resource.php at line 771</div>
<h3 id="filepath">filepath</h3>

```php
public  string$filepath = null
```
<div class="details">
<p>Compiled Filepath</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_resource.php at line 795</div>
<h3 id="isCompiled">isCompiled</h3>

```php
public  boolean$isCompiled = false
```
<div class="details">
<p>Template was compiled</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_resource.php at line 789</div>
<h3 id="loaded">loaded</h3>

```php
public  boolean$loaded = false
```
<div class="details">
<p>Compiled Content Loaded</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_resource.php at line 801</div>
<h3 id="source">source</h3>

```php
public  <a href="../smarty/smarty_template_source.html">Smarty_Template_Source</a>$source = null
```
<div class="details">
<p>Source Object</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_resource.php at line 777</div>
<h3 id="timestamp">timestamp</h3>

```php
public  integer$timestamp = null
```
<div class="details">
<p>Compiled Timestamp</p></div>

- - -

<h2 id="detail_method">Constructor Detail</h2>
<div class="location">framework\libs\smarty\sysplugins\smarty_resource.php at line 816</div>
<h3 id="__construct()">__construct</h3>

```php
public  void **__construct**(<a href="../smarty/smarty_template_source.html">Smarty_Template_Source</a> source)
```
<div class="details">
<p>create Compiled Object container</p><dl>
<dt>Parameters:</dt>
<dd>source - source object this compiled object belongs to</dd>
</dl>
</div>

- - -

