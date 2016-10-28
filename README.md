angular-xlsx-model
==================

Angular directive to convert XLSX files into JSON directly into the model.

Not compatible with Internet Explorer. It doesn't support JS readAsBinaryString. Will not fix.

Usage
-----

Install with bower:

    bower install angular-xlsx-model --save

Add to your HTML files:

    <script src='/bower_components/xlsx-model/xlsx-model.js'></script>

Inject the directive to your angular application:

    angular.module('myApp', ['xlsx-model']);

Start using:

`index.html`:

    <input type='file' xlsx-model='excel'>
    <pre>{{excel | json}}</pre>

Demo
--------------------

Check this Plunker: <http://plnkr.co/edit/inETA0PcxIkm4EmS9qjD?p=preview>.

Author
------
© 2016, Helvio Pedreschi `<helvio88@gmail.com>`. 

License
-------
The files are licensed under the MIT terms.
