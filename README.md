An extended source code plugin viewer for TinyMCE 4.1
=================

A TinyMCE version 4.1 third party plugin which extends the source code view to include html indenting.
Uses jsbeautifier http://jsbeautifier.org/


Installation
------------

1. Copy the plugin directory into for example your TinyMCE folder.
2. add to web page script link to beautify-html.js, for example
      <script src="/<path to>/js-beautify-master/js/beautify-html.js"></script>
3. add external plugin to tinymce.init code block, for example
      external_plugins: {
          "codebeautify": "/<path to>/js-beautify-master/TinyMCEplugin/plugin.js"
   },
4. optionaly add to tool bar, for example
      toolbar: "codebeautify"

                    
Usage
-----

To test the installation open the TestTinyMCE.html found in the js-beautify-master folder.
Note you might need to update the Javascript paths at the being of this html file. 
Default installation location is /TinyMCE/js-beautify-master

Note
----
If beautify-html.js is not present this plugin will revert back to the standard html source code view used by version 4.1 of TinyMCE