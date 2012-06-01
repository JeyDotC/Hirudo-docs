

- - -

**Smarty\Smarty_Security**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_security.php#L22" >framework\libs\smarty\sysplugins\smarty_security.php at line 22</a>

#Class Smarty_Security#

**Smarty_Security**




- - -

<p class="signature"><span class='k'>public  class</span> <span class='nx'>Smarty_Security</span></p>

<div class="comment" id="overview_description"><p>This class does contain the security settings</p></div>



- - -



<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#_config_dir"> $_config_dir</a>
                                </p><p class="description">Cache for $config_dir lookups</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#_php_resource_dir"> $_php_resource_dir</a>
                                </p><p class="description">Cache for $php_resource_dir lookups</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#_resource_dir"> $_resource_dir</a>
                                </p><p class="description">Cache for $resource_dir lookups</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#_secure_dir"> $_secure_dir</a>
                                </p><p class="description">Cache for $secure_dir lookups</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#_template_dir"> $_template_dir</a>
                                </p><p class="description">Cache for $template_dir lookups</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#_trusted_dir"> $_trusted_dir</a>
                                </p><p class="description">Cache for $trusted_dir lookups</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name" ><a href="#allow_constants"> $allow_constants</a>
                                </p><p class="description">+ flag if constants can be accessed from template</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name" ><a href="#allow_super_globals"> $allow_super_globals</a>
                                </p><p class="description">+ flag if super globals can be accessed from template</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#allowed_modifiers"> $allowed_modifiers</a>
                                </p><p class="description">This is an array of allowed modifier plugins.
</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#allowed_tags"> $allowed_tags</a>
                                </p><p class="description">This is an array of allowed tags.
</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#disabled_modifiers"> $disabled_modifiers</a>
                                </p><p class="description">This is an array of disabled modifier plugins.
</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#disabled_tags"> $disabled_tags</a>
                                </p><p class="description">This is an array of disabled tags.
</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#php_functions"> $php_functions</a>
                                </p><p class="description">This is an array of trusted PHP functions.
</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>integer</span></td>
<td class="description"><p class="name" ><a href="#php_handling"> $php_handling</a>
                                </p><p class="description">This determines how Smarty handles "</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#php_modifiers"> $php_modifiers</a>
                                </p><p class="description">This is an array of trusted PHP modifers.
</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#secure_dir"> $secure_dir</a>
                                </p><p class="description">This is the list of template directories that are considered secure.
</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#static_classes"> $static_classes</a>
                                </p><p class="description">This is an array of trusted static classes.
</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#streams"> $streams</a>
                                </p><p class="description">This is an array of trusted streams.
</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#trusted_dir"> $trusted_dir</a>
                                </p><p class="description">This is an array of directories where trusted php scripts reside.
</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="#trusted_uri"> $trusted_uri</a>
                                </p><p class="description">List of regular expressions (PCRE) that include trusted URIs</p></td>
</tr>
</table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty.md">Smarty</a> smarty)</p><p class="description"></p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#istrustedphpfunction">isTrustedPhpFunction</a>(string function_name, object compiler)</p><p class="description">Check if PHP function is trusted.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#istrustedstaticclass">isTrustedStaticClass</a>(string class_name, object compiler)</p><p class="description">Check if static class is trusted.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#istrustedphpmodifier">isTrustedPhpModifier</a>(string modifier_name, object compiler)</p><p class="description">Check if PHP modifier is trusted.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#istrustedtag">isTrustedTag</a>(string tag_name, object compiler)</p><p class="description">Check if tag is trusted.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#istrustedmodifier">isTrustedModifier</a>(string modifier_name, object compiler)</p><p class="description">Check if modifier plugin is trusted.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#istrustedstream">isTrustedStream</a>(string stream_name)</p><p class="description">Check if stream is trusted.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#istrustedresourcedir">isTrustedResourceDir</a>(string filepath)</p><p class="description">Check if directory of file resource is trusted.</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#istrusteduri">isTrustedUri</a>(string uri)</p><p class="description">Check if URI (e.g. </p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name"><a href="#istrustedphpdir">isTrustedPHPDir</a>(string filepath)</p><p class="description">Check if directory of file resource is trusted.</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_security.php#L163" >framework\libs\smarty\sysplugins\smarty_security.php at line 163</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty.md">Smarty</a> smarty)

<div class="details">
<p></p>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_security.php#L176" >framework\libs\smarty\sysplugins\smarty_security.php at line 176</a>

<h3 id="isTrustedPhpFunction()">isTrustedPhpFunction</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>isTrustedPhpFunction</span> (string function_name, object compiler)

<div class="details">
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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_security.php#L194" >framework\libs\smarty\sysplugins\smarty_security.php at line 194</a>

<h3 id="isTrustedStaticClass()">isTrustedStaticClass</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>isTrustedStaticClass</span> (string class_name, object compiler)

<div class="details">
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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_security.php#L212" >framework\libs\smarty\sysplugins\smarty_security.php at line 212</a>

<h3 id="isTrustedPhpModifier()">isTrustedPhpModifier</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>isTrustedPhpModifier</span> (string modifier_name, object compiler)

<div class="details">
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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_security.php#L230" >framework\libs\smarty\sysplugins\smarty_security.php at line 230</a>

<h3 id="isTrustedTag()">isTrustedTag</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>isTrustedTag</span> (string tag_name, object compiler)

<div class="details">
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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_security.php#L260" >framework\libs\smarty\sysplugins\smarty_security.php at line 260</a>

<h3 id="isTrustedModifier()">isTrustedModifier</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>isTrustedModifier</span> (string modifier_name, object compiler)

<div class="details">
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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_security.php#L288" >framework\libs\smarty\sysplugins\smarty_security.php at line 288</a>

<h3 id="isTrustedStream()">isTrustedStream</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>isTrustedStream</span> (string stream_name)

<div class="details">
<p>Check if stream is trusted.</p><dl>
<dt>Returns:</dt>
<dd>true if stream is trusted</dd>
<dt>Throws:</dt>
<dd><a href="../smarty/smartyexception.html">SmartyException</a> - if stream is not trusted</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_security.php#L304" >framework\libs\smarty\sysplugins\smarty_security.php at line 304</a>

<h3 id="isTrustedResourceDir()">isTrustedResourceDir</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>isTrustedResourceDir</span> (string filepath)

<div class="details">
<p>Check if directory of file resource is trusted.</p><dl>
<dt>Returns:</dt>
<dd>true if directory is trusted</dd>
<dt>Throws:</dt>
<dd><a href="../smarty/smartyexception.html">SmartyException</a> - if directory is not trusted</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_security.php#L386" >framework\libs\smarty\sysplugins\smarty_security.php at line 386</a>

<h3 id="isTrustedUri()">isTrustedUri</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>isTrustedUri</span> (string uri)

<div class="details">
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


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_security.php#L408" >framework\libs\smarty\sysplugins\smarty_security.php at line 408</a>

<h3 id="isTrustedPHPDir()">isTrustedPHPDir</h3>
<span class='k'></span> <span class='nx'>boolean</span> <span class='nf'>isTrustedPHPDir</span> (string filepath)

<div class="details">
<p>Check if directory of file resource is trusted.</p><dl>
<dt>Returns:</dt>
<dd>true if directory is trusted</dd>
<dt>Throws:</dt>
<dd><a href="../smarty/smartyexception.html">SmartyException</a> - if PHP directory is not trusted</dd>
</dl>

</div>

- - -

