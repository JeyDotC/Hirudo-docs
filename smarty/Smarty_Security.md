
- - -

**Smarty\Smarty_Security**
<div class="location">framework\libs\smarty\sysplugins\smarty_security.php at line 22</div>
#Class Smarty_Security#

**Smarty_Security**


- - -

<p class="signature">public  class **Smarty_Security**</p>

<div class="comment" id="overview_description"><p>This class does contain the security settings</p></div>


- - -

<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td class="type">protected  array</td>
<td class="description"><p class="name"><a href="#_config_dir">$_config_dir</a></p><p class="description">Cache for $config_dir lookups</p></td>
</tr>
<tr>
<td class="type">protected  array</td>
<td class="description"><p class="name"><a href="#_php_resource_dir">$_php_resource_dir</a></p><p class="description">Cache for $php_resource_dir lookups</p></td>
</tr>
<tr>
<td class="type">protected  array</td>
<td class="description"><p class="name"><a href="#_resource_dir">$_resource_dir</a></p><p class="description">Cache for $resource_dir lookups</p></td>
</tr>
<tr>
<td class="type">protected  array</td>
<td class="description"><p class="name"><a href="#_secure_dir">$_secure_dir</a></p><p class="description">Cache for $secure_dir lookups</p></td>
</tr>
<tr>
<td class="type">protected  array</td>
<td class="description"><p class="name"><a href="#_template_dir">$_template_dir</a></p><p class="description">Cache for $template_dir lookups</p></td>
</tr>
<tr>
<td class="type">protected  array</td>
<td class="description"><p class="name"><a href="#_trusted_dir">$_trusted_dir</a></p><p class="description">Cache for $trusted_dir lookups</p></td>
</tr>
<tr>
<td class="type"> boolean</td>
<td class="description"><p class="name"><a href="#allow_constants">$allow_constants</a></p><p class="description">+ flag if constants can be accessed from template</p></td>
</tr>
<tr>
<td class="type"> boolean</td>
<td class="description"><p class="name"><a href="#allow_super_globals">$allow_super_globals</a></p><p class="description">+ flag if super globals can be accessed from template</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#allowed_modifiers">$allowed_modifiers</a></p><p class="description">This is an array of allowed modifier plugins.
</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#allowed_tags">$allowed_tags</a></p><p class="description">This is an array of allowed tags.
</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#disabled_modifiers">$disabled_modifiers</a></p><p class="description">This is an array of disabled modifier plugins.
</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#disabled_tags">$disabled_tags</a></p><p class="description">This is an array of disabled tags.
</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#php_functions">$php_functions</a></p><p class="description">This is an array of trusted PHP functions.
</p></td>
</tr>
<tr>
<td class="type"> integer</td>
<td class="description"><p class="name"><a href="#php_handling">$php_handling</a></p><p class="description">This determines how Smarty handles "</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#php_modifiers">$php_modifiers</a></p><p class="description">This is an array of trusted PHP modifers.
</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#secure_dir">$secure_dir</a></p><p class="description">This is the list of template directories that are considered secure.
</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#static_classes">$static_classes</a></p><p class="description">This is an array of trusted static classes.
</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#streams">$streams</a></p><p class="description">This is an array of trusted streams.
</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#trusted_dir">$trusted_dir</a></p><p class="description">This is an array of directories where trusted php scripts reside.
</p></td>
</tr>
<tr>
<td class="type"> array</td>
<td class="description"><p class="name"><a href="#trusted_uri">$trusted_uri</a></p><p class="description">List of regular expressions (PCRE) that include trusted URIs</p></td>
</tr>
</table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td class="type"> void</td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(<a href="../smarty/smarty.html">Smarty</a> smarty)</p><p class="description"></p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td class="type">  boolean</td>
<td class="description"><p class="name"><a href="#istrustedphpfunction">isTrustedPhpFunction</a>(string function_name, object compiler)</p><p class="description">Check if PHP function is trusted.</p></td>
</tr>
<tr>
<td class="type">  boolean</td>
<td class="description"><p class="name"><a href="#istrustedstaticclass">isTrustedStaticClass</a>(string class_name, object compiler)</p><p class="description">Check if static class is trusted.</p></td>
</tr>
<tr>
<td class="type">  boolean</td>
<td class="description"><p class="name"><a href="#istrustedphpmodifier">isTrustedPhpModifier</a>(string modifier_name, object compiler)</p><p class="description">Check if PHP modifier is trusted.</p></td>
</tr>
<tr>
<td class="type">  boolean</td>
<td class="description"><p class="name"><a href="#istrustedtag">isTrustedTag</a>(string tag_name, object compiler)</p><p class="description">Check if tag is trusted.</p></td>
</tr>
<tr>
<td class="type">  boolean</td>
<td class="description"><p class="name"><a href="#istrustedmodifier">isTrustedModifier</a>(string modifier_name, object compiler)</p><p class="description">Check if modifier plugin is trusted.</p></td>
</tr>
<tr>
<td class="type">  boolean</td>
<td class="description"><p class="name"><a href="#istrustedstream">isTrustedStream</a>(string stream_name)</p><p class="description">Check if stream is trusted.</p></td>
</tr>
<tr>
<td class="type">  boolean</td>
<td class="description"><p class="name"><a href="#istrustedresourcedir">isTrustedResourceDir</a>(string filepath)</p><p class="description">Check if directory of file resource is trusted.</p></td>
</tr>
<tr>
<td class="type">  boolean</td>
<td class="description"><p class="name"><a href="#istrusteduri">isTrustedUri</a>(string uri)</p><p class="description">Check if URI (e.g. </p></td>
</tr>
<tr>
<td class="type">  boolean</td>
<td class="description"><p class="name"><a href="#istrustedphpdir">isTrustedPHPDir</a>(string filepath)</p><p class="description">Check if directory of file resource is trusted.</p></td>
</tr>
</table>

##Field Detail##
<div class="location">framework\libs\smarty\sysplugins\smarty_security.php at line 142</div>
<h3 id="_config_dir">_config_dir</h3>

protected  array $_config_dir = null
<div class="details">
<p>Cache for $config_dir lookups</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_security.php at line 152</div>
<h3 id="_php_resource_dir">_php_resource_dir</h3>

protected  array $_php_resource_dir = null
<div class="details">
<p>Cache for $php_resource_dir lookups</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_security.php at line 132</div>
<h3 id="_resource_dir">_resource_dir</h3>

protected  array $_resource_dir = null
<div class="details">
<p>Cache for $resource_dir lookups</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_security.php at line 147</div>
<h3 id="_secure_dir">_secure_dir</h3>

protected  array $_secure_dir = null
<div class="details">
<p>Cache for $secure_dir lookups</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_security.php at line 137</div>
<h3 id="_template_dir">_template_dir</h3>

protected  array $_template_dir = null
<div class="details">
<p>Cache for $template_dir lookups</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_security.php at line 157</div>
<h3 id="_trusted_dir">_trusted_dir</h3>

protected  array $_trusted_dir = null
<div class="details">
<p>Cache for $trusted_dir lookups</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_security.php at line 121</div>
<h3 id="allow_constants">allow_constants</h3>

public  boolean $allow_constants = true
<div class="details">
<p>+ flag if constants can be accessed from template</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_security.php at line 126</div>
<h3 id="allow_super_globals">allow_super_globals</h3>

public  boolean $allow_super_globals = true
<div class="details">
<p>+ flag if super globals can be accessed from template</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_security.php at line 101</div>
<h3 id="allowed_modifiers">allowed_modifiers</h3>

public  array $allowed_modifiers = array()
<div class="details">
<p>This is an array of allowed modifier plugins.</p><p>If empty no restriction by allowed_modifiers.</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_security.php at line 87</div>
<h3 id="allowed_tags">allowed_tags</h3>

public  array $allowed_tags = array()
<div class="details">
<p>This is an array of allowed tags.</p><p>If empty no restriction by allowed_tags.</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_security.php at line 108</div>
<h3 id="disabled_modifiers">disabled_modifiers</h3>

public  array $disabled_modifiers = array()
<div class="details">
<p>This is an array of disabled modifier plugins.</p><p>If empty no restriction by disabled_modifiers.</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_security.php at line 94</div>
<h3 id="disabled_tags">disabled_tags</h3>

public  array $disabled_tags = array()
<div class="details">
<p>This is an array of disabled tags.</p><p>If empty no restriction by disabled_tags.</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_security.php at line 72</div>
<h3 id="php_functions">php_functions</h3>

public  array $php_functions = array(...)
<div class="details">
<p>This is an array of trusted PHP functions.</p><p>If empty all functions are allowed.
To disable all PHP functions set $php_functions = null.</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_security.php at line 36</div>
<h3 id="php_handling">php_handling</h3>

public  integer $php_handling = Smarty::PHP_PASSTHRU
<div class="details">
<p>This determines how Smarty handles "<?php ... ?>" tags in templates.
possible values:</p>
<ul>
<li>Smarty::PHP_PASSTHRU -> echo PHP tags as they are</li>
<li>Smarty::PHP_QUOTE    -> escape tags as entities</li>
<li>Smarty::PHP_REMOVE   -> remove php tags</li>
<li>Smarty::PHP_ALLOW    -> execute php tags</li>
</ul>
<p></p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_security.php at line 80</div>
<h3 id="php_modifiers">php_modifiers</h3>

public  array $php_modifiers = array(...)
<div class="details">
<p>This is an array of trusted PHP modifers.</p><p>If empty all modifiers are allowed.
To disable all modifier set $modifiers = null.</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_security.php at line 43</div>
<h3 id="secure_dir">secure_dir</h3>

public  array $secure_dir = array()
<div class="details">
<p>This is the list of template directories that are considered secure.
$template_dir is in this list implicitly.</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_security.php at line 64</div>
<h3 id="static_classes">static_classes</h3>

public  array $static_classes = array()
<div class="details">
<p>This is an array of trusted static classes.</p><p>If empty access to all static classes is allowed.
If set to 'none' none is allowed.</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_security.php at line 116</div>
<h3 id="streams">streams</h3>

public  array $streams = array('file')
<div class="details">
<p>This is an array of trusted streams.</p><p>If empty all streams are allowed.
To disable all streams set $streams = null.</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_security.php at line 50</div>
<h3 id="trusted_dir">trusted_dir</h3>

public  array $trusted_dir = array()
<div class="details">
<p>This is an array of directories where trusted php scripts reside.
<code>$security</code> is disabled during their inclusion/execution.</p></div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_security.php at line 56</div>
<h3 id="trusted_uri">trusted_uri</h3>

public  array $trusted_uri = array()
<div class="details">
<p>List of regular expressions (PCRE) that include trusted URIs</p></div>

- - -

<h2 id="detail_method">Constructor Detail</h2>
<div class="location">framework\libs\smarty\sysplugins\smarty_security.php at line 163</div>
<h3 id="__construct()">__construct</h3>

```php
public  void **__construct**(<a href="../smarty/smarty.html">Smarty</a> smarty)
```
<div class="details">
<p></p></div>

- - -

<h2 id="detail_method">Method Detail</h2>
<div class="location">framework\libs\smarty\sysplugins\smarty_security.php at line 176</div>
<h3 id="isTrustedPhpFunction()">isTrustedPhpFunction</h3>

public  boolean **isTrustedPhpFunction** (string function_name, object compiler)<div class="details">
<p>Check if PHP function is trusted.</p><dl>
<dt>Parameters:</dt>
<dd></dd>
<dd>compiler - compiler object</dd>
<dt>Returns:</dt>
<dd>true if function is trusted</dd>
<dt>Throws:</dt>
<dd><a href="../smarty/smartycompilerexception.html">SmartyCompilerException</a> - if php function is not trusted</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_security.php at line 194</div>
<h3 id="isTrustedStaticClass()">isTrustedStaticClass</h3>

public  boolean **isTrustedStaticClass** (string class_name, object compiler)<div class="details">
<p>Check if static class is trusted.</p><dl>
<dt>Parameters:</dt>
<dd></dd>
<dd>compiler - compiler object</dd>
<dt>Returns:</dt>
<dd>true if class is trusted</dd>
<dt>Throws:</dt>
<dd><a href="../smarty/smartycompilerexception.html">SmartyCompilerException</a> - if static class is not trusted</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_security.php at line 212</div>
<h3 id="isTrustedPhpModifier()">isTrustedPhpModifier</h3>

public  boolean **isTrustedPhpModifier** (string modifier_name, object compiler)<div class="details">
<p>Check if PHP modifier is trusted.</p><dl>
<dt>Parameters:</dt>
<dd></dd>
<dd>compiler - compiler object</dd>
<dt>Returns:</dt>
<dd>true if modifier is trusted</dd>
<dt>Throws:</dt>
<dd><a href="../smarty/smartycompilerexception.html">SmartyCompilerException</a> - if modifier is not trusted</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_security.php at line 230</div>
<h3 id="isTrustedTag()">isTrustedTag</h3>

public  boolean **isTrustedTag** (string tag_name, object compiler)<div class="details">
<p>Check if tag is trusted.</p><dl>
<dt>Parameters:</dt>
<dd></dd>
<dd>compiler - compiler object</dd>
<dt>Returns:</dt>
<dd>true if tag is trusted</dd>
<dt>Throws:</dt>
<dd><a href="../smarty/smartycompilerexception.html">SmartyCompilerException</a> - if modifier is not trusted</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_security.php at line 260</div>
<h3 id="isTrustedModifier()">isTrustedModifier</h3>

public  boolean **isTrustedModifier** (string modifier_name, object compiler)<div class="details">
<p>Check if modifier plugin is trusted.</p><dl>
<dt>Parameters:</dt>
<dd></dd>
<dd>compiler - compiler object</dd>
<dt>Returns:</dt>
<dd>true if tag is trusted</dd>
<dt>Throws:</dt>
<dd><a href="../smarty/smartycompilerexception.html">SmartyCompilerException</a> - if modifier is not trusted</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_security.php at line 288</div>
<h3 id="isTrustedStream()">isTrustedStream</h3>

public  boolean **isTrustedStream** (string stream_name)<div class="details">
<p>Check if stream is trusted.</p><dl>
<dt>Returns:</dt>
<dd>true if stream is trusted</dd>
<dt>Throws:</dt>
<dd><a href="../smarty/smartyexception.html">SmartyException</a> - if stream is not trusted</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_security.php at line 304</div>
<h3 id="isTrustedResourceDir()">isTrustedResourceDir</h3>

public  boolean **isTrustedResourceDir** (string filepath)<div class="details">
<p>Check if directory of file resource is trusted.</p><dl>
<dt>Returns:</dt>
<dd>true if directory is trusted</dd>
<dt>Throws:</dt>
<dd><a href="../smarty/smartyexception.html">SmartyException</a> - if directory is not trusted</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_security.php at line 386</div>
<h3 id="isTrustedUri()">isTrustedUri</h3>

public  boolean **isTrustedUri** (string uri)<div class="details">
<p>Check if URI (e.g. {fetch} or {html_image}) is trusted</p><p>To simplify things, isTrustedUri() resolves all input to "{$PROTOCOL}://{$HOSTNAME}".
So "http://username:password@hello.world.example.org:8080/some-path?some=query-string"
is reduced to "http://hello.world.example.org" prior to applying the patters from <code><a href="../smarty/smarty_security.html#trusted_uri">$trusted_uri</a></code>.</p><dl>
<dt>Returns:</dt>
<dd>true if URI is trusted</dd>
<dt>Throws:</dt>
<dd><a href="../smarty/smartyexception.html">SmartyException</a> - if URI is not trusted</dd>
<dt>Uses:</dt>
<dd>$trusted_uri for list of patterns to match against $uri</dd>
</dl>
</div>

- - -

<div class="location">framework\libs\smarty\sysplugins\smarty_security.php at line 408</div>
<h3 id="isTrustedPHPDir()">isTrustedPHPDir</h3>

public  boolean **isTrustedPHPDir** (string filepath)<div class="details">
<p>Check if directory of file resource is trusted.</p><dl>
<dt>Returns:</dt>
<dd>true if directory is trusted</dd>
<dt>Throws:</dt>
<dd><a href="../smarty/smartyexception.html">SmartyException</a> - if PHP directory is not trusted</dd>
</dl>
</div>

- - -

