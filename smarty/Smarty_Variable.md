
- - -

**Smarty\Smarty_Variable**


<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_data.php#L467 class="location">framework\libs\smarty\sysplugins\smarty_internal_data.php at line 467</a>

#Class Smarty_Variable#

**Smarty_Variable**




- - -

<p class="signature">public  class **Smarty_Variable**</p>

<div class="comment" id="overview_description"><p>class for the Smarty variable object</p><p>This class defines the Smarty variable object</p></div>

<dl>
<dt>Subpackage:</dt>
<dd>Template</dd>
</dl>


- - -



<table id="summary_field">
<tr><th colspan="2">Field Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>boolean</span></td>
<td class="description"><p class="name" ><a href="#nocache"> $nocache</a>
                                </p><p class="description">if true any output of this variable will be not cached</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>int</span></td>
<td class="description"><p class="name" ><a href="#scope"> $scope</a>
                                </p><p class="description">the scope the variable will have  (local,parent or root)</p></td>
</tr>
<tr>
<td><span class='k'></span> <span class='nx'>mixed</span></td>
<td class="description"><p class="name" ><a href="#value"> $value</a>
                                </p><p class="description">template variable</p></td>
</tr>
</table>

<table id="summary_constructor">
<tr><th colspan="2">Constructor Summary</th></tr>
<tr>
<td><span class='k'></span> <span class='nx'>void</span></td>
<td class="description"><p class="name"><a href="#__construct">__construct</a>(mixed value, boolean nocache, int scope)</p><p class="description">create Smarty variable object</p></td>
</tr>
</table>

<h2 id="detail_method">Constructor Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/master/framework/libs/smarty/sysplugins/smarty_internal_data.php#L495 class="location">framework\libs\smarty\sysplugins\smarty_internal_data.php at line 495</a>

<h3 id="__construct">__construct</h3>
<span class='k'></span> <span class='nx'>void</span> <span class='nf'>__construct</span> (mixed value, boolean nocache, int scope)

<div class="details">
<p>create Smarty variable object</p><dl>
<dt>Parameters:</dt>
<dd>value - the value to assign</dd>
<dd>nocache - if true any output of this variable will be not cached</dd>
<dd>scope - the scope the variable will have (local,parent or root)</dd>
</dl>
</div>

- - -

