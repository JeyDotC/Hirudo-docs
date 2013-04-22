- - -

#Globals#

- - -

<table id="summary_global" class="title">
<tr><th colspan="2" class="title">Global Summary</th></tr>
<tr>
<td>final  mixed</td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Default namespace/package-globals.md#ds">DS</a></p><p class="description">«Copyright 2012 Jeysson José Guevara Mendivil(JeyDotC)»This file is part of Hirudo.
</p></td>
</tr>
<tr>
<td>final  mixed</td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Default namespace/package-globals.md#hirudo_root">HIRUDO_ROOT</a></p></td>
</tr>
<tr>
<td> mixed</td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Default namespace/package-globals.md#v">V</a></p></td>
</tr>
<tr>
<td> mixed</td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Default namespace/package-globals.md#composerloader">composerLoader</a></p></td>
</tr>
<tr>
<td> mixed</td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Default namespace/package-globals.md#controller">controller</a></p></td>
</tr>
<tr>
<td> mixed</td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Default namespace/package-globals.md#controllerclass">controllerClass</a></p></td>
</tr>
<tr>
<td> mixed</td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Default namespace/package-globals.md#jversion">jversion</a></p><p class="description">«Copyright 2012 Jeysson José Guevara Mendivil(JeyDotC)»This file is part of Hirudo.
</p></td>
</tr>
<tr>
<td> mixed</td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Default namespace/package-globals.md#loader">loader</a></p></td>
</tr>
<tr>
<td> mixed</td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Default namespace/package-globals.md#manager">manager</a></p><p class="description">«Copyright 2012 Jeysson José Guevara Mendivil(JeyDotC)»This file is part of Hirudo.
</p></td>
</tr>
<tr>
<td> mixed</td>
<td class="description"><p class="name"><a href="#https://github.com/JeyDotC/Hirudo-docs/blob/master/Default namespace/package-globals.md#this">this</a></p></td>
</tr>
</table>

<h2 id="detail_global">Global Detail</h2>

<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/init.php#L22" target='_blank'>init.php at line 22</a>

<h3 id="DS">DS</h3>


public final  mixed **DS** = DIRECTORY_SEPARATOR

<div class="details">
<p>«Copyright 2012 Jeysson José Guevara Mendivil(JeyDotC)»</p><p>This file is part of Hirudo.</p><p>Hirudo is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.</p><p>Hirudo is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.</p><p>You should have received a copy of the GNU General Public License
along with Hirudo.  If not, see <http://www.gnu.org/licenses/>.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/init.php#L26" target='_blank'>init.php at line 26</a>

<h3 id="HIRUDO_ROOT">HIRUDO_ROOT</h3>


public final  mixed **HIRUDO_ROOT** = dirname(__FILE__

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/hirudo.php#L30" target='_blank'>hirudo.php at line 30</a>

<h3 id="V">V</h3>


public  mixed **V** = &quot;V15&quot;

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/init.php#L37" target='_blank'>init.php at line 37</a>

<h3 id="composerLoader">composerLoader</h3>


public  mixed **composerLoader** = require_once HIRUDO_ROOT . &quot;/vendor/autoload.php&quot;

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/hirudo.php#L36" target='_blank'>hirudo.php at line 36</a>

<h3 id="controller">controller</h3>


public  mixed **controller** = new $controllerClass(new ModulesManager(&quot;joomla-{$V}&quot;

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/hirudo.php#L35" target='_blank'>hirudo.php at line 35</a>

<h3 id="controllerClass">controllerClass</h3>


public  mixed **controllerClass** = &quot;Hirudo\\Impl\\Joomla\\{$V}\\JoomlaFrontController&quot;

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/hirudo.php#L28" target='_blank'>hirudo.php at line 28</a>

<h3 id="jversion">jversion</h3>


public  mixed **jversion** = new \JVersion

<div class="details">
<p>«Copyright 2012 Jeysson José Guevara Mendivil(JeyDotC)»</p><p>This file is part of Hirudo.</p><p>Hirudo is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.</p><p>Hirudo is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.</p><p>You should have received a copy of the GNU General Public License
along with Hirudo.  If not, see <http://www.gnu.org/licenses/>.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/init.php#L41" target='_blank'>init.php at line 41</a>

<h3 id="loader">loader</h3>


public  mixed **loader** = new Symfony\Component\ClassLoader\ApcClassLoader(&quot;hirudo&quot;

<div class="details">
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/index.php#L26" target='_blank'>index.php at line 26</a>

<h3 id="manager">manager</h3>


public  mixed **manager** = new ModulesManager

<div class="details">
<p>«Copyright 2012 Jeysson José Guevara Mendivil(JeyDotC)»</p><p>This file is part of Hirudo.</p><p>Hirudo is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.</p><p>Hirudo is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.</p><p>You should have received a copy of the GNU General Public License
along with Hirudo.  If not, see <http://www.gnu.org/licenses/>.</p>
</div>

- - -


<a href="https://github.com/JeyDotC/Hirudo/blob/make-composer-compatible/framework/Hirudo/Impl/Joomla/V15/views/_/tmpl/default.php#L3" target='_blank'>framework\Hirudo\Impl\Joomla\V15\views\_\tmpl\default.php at line 3</a>

<h3 id="this">this</h3>


public  mixed **this**

<div class="details">
</div>

- - -

