

- - -

**HTTP_Session2\HTTP_Session2_Container**


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container.php#L64" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container.php at line 64</a>

#Class HTTP_Session2_Container#

**HTTP_Session2_Container**


<dl>
<dt>All Known Subclasses:</dt>
<dd><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/HTTP_Session2/HTTP_Session2_Container_DB.md">HTTP_Session2_Container_DB</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/HTTP_Session2/HTTP_Session2_Container_MDB2.md">HTTP_Session2_Container_MDB2</a> <a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/HTTP_Session2/HTTP_Session2_Container_Memcache.md">HTTP_Session2_Container_Memcache</a> </dd>
</dl>



- - -

<p><strong>public abstract  class</strong> <span>HTTP_Session2_Container</span></p>

<div class="comment" id="overview_description"><p>Container class for storing session data data</p></div>

<dl>
<dt>Category:</dt>
<dd>HTTP</dd>
<dt>Author:</dt>
<dd>Alexander Radivaniovich <info@wwwlab.net></dd>
<dd>Tony Bibbs <tony@geeklog.net></dd>
<dt>License:</dt>
<dd>http://www.opensource.org/licenses/bsd-license.php The BSD License</dd>
<dt>Version:</dt>
<dd>Release: @package_version@</dd>
<dt>See Also:</dt>
<dd><code><a href="http://pear.php.net/package/HTTP_Session2">http://pear.php.net/package/HTTP_Session2</a></code></dd>
</dl>


<hr />



<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>array</span></td>
<td class="description"><p class="name" ><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/HTTP_Session2/HTTP_Session2_Container.md#options"> $options</a>
                                </p><p class="description">Additional options for the container object</p></td>
</tr>
</table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(array options)</p><p class="description">Constrtuctor method</p></td>
</tr>
</table>

<table id="summary_method">
<tr><th colspan="2">Method Summary</th></tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#setdefaults">setDefaults</a>()</p><p class="description">Set some default options</p></td>
</tr>
<tr>
<td><span class='k'>protected </span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#parseoptions">parseOptions</a>(array options)</p><p class="description">Parse options passed to the container class</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#set">set</a>()</p><p class="description">Set session save handler</p></td>
</tr>
</table>

##Field Detail##

<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container.php#L71" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container.php at line 71</a>

<h3 id="options">options</h3>
<span class='k'>protected </span> <span class='nx'>array</span><span class='no'> $options</span><span class='o'> = array()</span>

<div class="details">
<p>Additional options for the container object</p>
</div>

- - -

<h2>Constructor Detail</h2>


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container.php#L80" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container.php at line 80</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (array options)

<div class="details">
<p>Constrtuctor method</p><dl>
<dt>Parameters:</dt>
<dd>options - Additional options for the container object</dd>
</dl>

</div>

- - -

<h2 id="detail_method">Method Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container.php#L103" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container.php at line 103</a>

<h3 id="setDefaults()">setDefaults</h3>
<span class='k'>protected </span> <span class='nx'>void</span> <span class='nf'>setDefaults</span> ()

<div class="details">
<p>Set some default options</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container.php#L114" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container.php at line 114</a>

<h3 id="parseOptions()">parseOptions</h3>
<span class='k'>protected </span> <span class='nx'>void</span> <span class='nf'>parseOptions</span> (array options)

<div class="details">
<p>Parse options passed to the container class</p><dl>
<dt>Parameters:</dt>
<dd>options - Options</dd>
</dl>

</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/StandAlone/lib/HTTP/Session2/Container.php#L128" target='_blank'>framework\Hirudo\Impl\StandAlone\lib\HTTP\Session2\Container.php at line 128</a>

<h3 id="set()">set</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>set</span> ()

<div class="details">
<p>Set session save handler</p>
</div>

- - -

