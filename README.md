#[mnmenu](http://www.marcnuri.com/)


##Description

[JQuery](http://jquery.com/) plugin to create dropdown menus from ul lists.

This is a very simple and straightforward plugin. It's still a work in progress project
with more features to come, so check for updates to see what's new in upcoming versions.

##Requirements

This is a [JQuery](http://jquery.com/) plugin, so obviously it requires the jquery library.

##Usage

###Html

Add JQuery and mnmenu scripts to the `<head>` section.

``<script src="../lib/jqmin.1.10.1.js" type="text/javascript"></script>``
``<script src="../src/jquery.mnmenu.js" type="text/javascript"></script>``

The menu should be initialized in an ``<ul>`` element

Initialize the menu for your list:

``<script>$(document).ready(function() {
``    $('#idmenu').mnmenu();
``})</script>

###CSS

See the example style.css for customization options.