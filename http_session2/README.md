- - -

#Namespace HTTP_Session2#

<table class="title">
<tr><th colspan="2" class="title">Class Summary</th></tr>
<tr><td class="name"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/http_session2/http_session2.html">HTTP_Session2</a></td><td class="description">Class for managing HTTP sessionsProvides access to session-state values as well as session-level
settings and lifetime management methods.
</td></tr>
<tr><td class="name"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/http_session2/http_session2_container.html">HTTP_Session2_Container</a></td><td class="description">Container class for storing session data data</td></tr>
<tr><td class="name"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/http_session2/http_session2_container_db.html">HTTP_Session2_Container_DB</a></td><td class="description">Database container for session dataCreate the following table to store session data

CREATE TABLE `sessiondata` (
`id` CHAR(32) NOT NULL,
`expiry` INT UNSIGNED NOT NULL DEFAULT 0,
`data` TEXT NOT NULL,
PRIMARY KEY (`id`)
);
</td></tr>
<tr><td class="name"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/http_session2/http_session2_container_mdb2.html">HTTP_Session2_Container_MDB2</a></td><td class="description">Database container for session dataCreate the following table to store session data

CREATE TABLE `sessiondata` (
`id` CHAR(32) NOT NULL,
`expiry` INT UNSIGNED NOT NULL DEFAULT 0,
`data` TEXT NOT NULL,
PRIMARY KEY (`id`)
);
</td></tr>
<tr><td class="name"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/http_session2/http_session2_container_memcache.html">HTTP_Session2_Container_Memcache</a></td><td class="description">Memcache container for session data</td></tr>
</table>

<table class="title">
<tr><th colspan="2" class="title">Interface Summary</th></tr>
<tr><td class="name"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/http_session2/http_session2_container_interface.html">HTTP_Session2_Container_Interface</a></td><td class="description">Container class for storing session data data</td></tr>
</table>

<table class="title">
<tr><th colspan="2" class="title">Exception Summary</th></tr>
<tr><td class="name"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/http_session2/http_session2_exception.html">HTTP_Session2_Exception</a></td><td class="description">HTTP_Session2_ExceptionPHP version 5</td></tr>
</table>

<table class="title">
<tr><th colspan="2" class="title">Global Summary</th></tr>
<tr><td class="name"><a href="package-globals.md#STARTED">STARTED</a></td><td class="description"></td></tr>
</table>

- - -
