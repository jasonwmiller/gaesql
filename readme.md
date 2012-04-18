GAE SQL Designer - Documentation

Table of contents

Usage
Browsers
Basics
Contact
Changelog
Usage

Hello and welcome to GAE SQL Designer documentation. This page will hopefully help you with understanding how GAE SQL Designer works and how can it be tailored to suit your needs.

Browsers

GAE SQL Designer was tested in the following browsers:

Firefox 2.x
Firefox 3.x
Internet Explorer 6
Internet Explorer 7
Internet Explorer 8
Safari 3
Opera 9.x
Konqueror 3.5.x
Konqueror is the only browser (from this list) which lacks support for Smooth connectors and XSLT transformations (generation of SQL scripts).

Basics

The application allows you to:

Draw E-R designs
Edit tables and rows
Manage keys
Create relations (FK constraints)
Save & Load designs
Import DB schemas
Most commands are intuitively available from the right sidebar. Some tasks are described below.

To drag a table, press mouse button while pointing at table header. You can then move the table around the canvas.

To edit table properties, either double-click its heading, or select it and then press 'Edit table' button in sidebar.

To edit field properties, either double-click it, or select it and then press 'Edit field' button in sidebar.

To manage keys for a table, select a table and press 'Edit keys' button in sidebar.

To draw a connector (relation), first select a field which forms a Primary Key. Then click 'Create foreign key' button in sidebar and click target table's heading. New field and relation will be created.

To perform any kind of save/load/export/import task, press the 'Save/Load' button in sidebar. A dialog window will appear, allowing you to perform clientside or serverside tasks.

Contact

This Ported to work on Google Appengine by Jason W. Miller, ©
Based Heavly on WWW SQL Designer by Ondrej Zara, © 2005-2008. It is released under GNU GPL licence.
