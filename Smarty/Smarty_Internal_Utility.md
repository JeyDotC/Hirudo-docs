

- - -

**Smarty\Smarty_Internal_Utility**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_utility.php#L41" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_utility.php at line 41</a>

#Class Smarty_Internal_Utility#

**Smarty_Internal_Utility**




- - -

<p><strong>public  class</strong> <span>Smarty_Internal_Utility</span></p>

<div class="comment" id="overview_description"><p>Utility class</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>Security</dd>
</dl>


- - -

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'>private final </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>()</p><p class="description">private constructor to prevent calls creation of new instances</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>integer</span></td>
<td class="description"><p class="name"><a href="#compilealltemplates">compileAllTemplates</a>(string extension, bool force_compile, int time_limit, int max_errors, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty.md">Smarty</a> smarty, mixed extention)</p><p class="description">Compile all template files</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>integer</span></td>
<td class="description"><p class="name"><a href="#compileallconfig">compileAllConfig</a>(string extension, bool force_compile, int time_limit, int max_errors, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty.md">Smarty</a> smarty, mixed extention)</p><p class="description">Compile all config files</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>integer</span></td>
<td class="description"><p class="name"><a href="#clearcompiledtemplate">clearCompiledTemplate</a>(string resource_name, string compile_id, integer exp_time, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty.md">Smarty</a> smarty)</p><p class="description">Delete compiled template file</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>array</span></td>
<td class="description"><p class="name"><a href="#gettags">getTags</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> templae, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> template)</p><p class="description">Return array of tag/attributes of all tags used by an template</p></td>
</tr>
<tr>
<td><span class='k'>static </span> <span class='nx'>bool</span></td>
<td class="description"><p class="name"><a href="#testinstall">testInstall</a>(<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty.md">Smarty</a> smarty, array errors)</p><p class="description">diagnose Smarty setupIf $errors is secified, the diagnostic report will be appended to the array, rather than being output.</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_utility.php#L46" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_utility.php at line 46</a>

<h3 id="__construct">__construct</h3>
<span class='k'>private final </span> <span class='nx'>void</span> <span class='nf'>__construct</span> ()

<div class="details">
<p>private constructor to prevent calls creation of new instances</p>
</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_utility.php#L61" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_utility.php at line 61</a>

<h3 id="compileAllTemplates()">compileAllTemplates</h3>
<span class='k'>static </span> <span class='nx'>integer</span> <span class='nf'>compileAllTemplates</span> (string extension, bool force_compile, int time_limit, int max_errors, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty.md">Smarty</a> smarty, mixed extention)

<div class="details">
<p>Compile all template files</p><dl>
<dt>Parameters:</dt>
<dd>extension - template file name extension</dd>
<dd>force_compile - force all to recompile</dd>
<dd>time_limit - set maximum execution time</dd>
<dd>max_errors - set maximum allowed errors</dd>
<dd>smarty - Smarty instance</dd>
<dt>Returns:</dt>
<dd>number of template files compiled</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_utility.php#L124" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_utility.php at line 124</a>

<h3 id="compileAllConfig()">compileAllConfig</h3>
<span class='k'>static </span> <span class='nx'>integer</span> <span class='nf'>compileAllConfig</span> (string extension, bool force_compile, int time_limit, int max_errors, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty.md">Smarty</a> smarty, mixed extention)

<div class="details">
<p>Compile all config files</p><dl>
<dt>Parameters:</dt>
<dd>extension - config file name extension</dd>
<dd>force_compile - force all to recompile</dd>
<dd>time_limit - set maximum execution time</dd>
<dd>max_errors - set maximum allowed errors</dd>
<dd>smarty - Smarty instance</dd>
<dt>Returns:</dt>
<dd>number of config files compiled</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_utility.php#L182" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_utility.php at line 182</a>

<h3 id="clearCompiledTemplate()">clearCompiledTemplate</h3>
<span class='k'>static </span> <span class='nx'>integer</span> <span class='nf'>clearCompiledTemplate</span> (string resource_name, string compile_id, integer exp_time, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty.md">Smarty</a> smarty)

<div class="details">
<p>Delete compiled template file</p><dl>
<dt>Parameters:</dt>
<dd>resource_name - template name</dd>
<dd>compile_id - compile id</dd>
<dd>exp_time - expiration time</dd>
<dd>smarty - Smarty instance</dd>
<dt>Returns:</dt>
<dd>number of template files deleted</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_utility.php#L276" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_utility.php at line 276</a>

<h3 id="getTags()">getTags</h3>
<span class='k'>static </span> <span class='nx'>array</span> <span class='nf'>getTags</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> templae, <a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty_Internal_Template.md">Smarty_Internal_Template</a> template)

<div class="details">
<p>Return array of tag/attributes of all tags used by an template</p><dl>
<dt>Parameters:</dt>
<dd>templae - template object</dd>
<dt>Returns:</dt>
<dd>of tag/attributes</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_utility.php#L293" target='_blank'>framework\libs\smarty\sysplugins\smarty_internal_utility.php at line 293</a>

<h3 id="testInstall()">testInstall</h3>
<span class='k'>static </span> <span class='nx'>bool</span> <span class='nf'>testInstall</span> (<a href="https://github.com/JeyDotC/Hirudo/blob/master/smarty/Smarty.md">Smarty</a> smarty, array errors)

<div class="details">
<p>diagnose Smarty setup</p><p>If $errors is secified, the diagnostic report will be appended to the array, rather than being output.</p><dl>
<dt>Parameters:</dt>
<dd>smarty - Smarty instance to test</dd>
<dd>errors - array to push results into rather than outputting them</dd>
<dt>Returns:</dt>
<dd>status, true if everything is fine, false else</dd>
</dl>

</div>

- - -

