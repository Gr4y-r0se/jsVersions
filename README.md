# jsVersions
###### WebConsole Commands for JS Package Versions
Here is a list of all the webconsole commands I (and my many venerable colleagues) have used in penetration tests to discover package versions.

 - Adobe Target: `adobe.target.VERSION`
 - Angular: `getAllAngularRootElements()[0].attributes["ng-version"];`
 - AngularJS: `angular.version.full`  
 - Bootstrap: `bootstrap.Alert.VERSION` / `$.fn.tooltip.Constructor.VERSION`
 - Core: `core.version` / `window['__core-js_shared__'].versions[0].version`
 - D3: `d3.version`
 - Data Tables: `$.fn.dataTable.version` / `$().dataTable.version`
 - Dojo: `dojo.version`
 - Dropzone: `Dropzone.version`
 - Ember.js: `Ember.VERSION`
 - ExtJS 3.x: `Ext.version`  
 - ExtJS 4.0: `Ext.getVersion('extjs')`  
 - ExtJS >= 4.1: `Ext.getVersion().version`
 - FancyBox: `jQuery.fancybox.version`
 - Highcharts: `Highcharts.version`  
 - jQuery: `jQuery().jquery` 
 - jQueryUI : `jQuery.ui.version` / `$.ui.version`
 - Knockout.js: `ko.version`
 - Lodash: `_.VERSION`
 - Microsoft Clarity: `clarity.v`
 - Migrate: `jQuery.migrateVersion`
 - Modernizr: `Modernizr._version`
 - Moment: `moment.version`  
 - Prototype: `prototype.version`
 - React: `React.version`
 - RequireJS: `require.version`
 - TinyMCE: `tinymce.majorVersion + "." + tinymce.minorVersion`
 - Toastr: `toastr.version`
 - Wordpress Emoji: `window._wpemojiSettings.source.concatemoji`
 - YUI: `Y.VERSION`

__________________________
#### Scanning
If you want to scan many sites for package versions using the above, then please see [jsInspector](https://github.com/BDragisic/jsInspector), a tool written in collaboration with [@BDragisic](https://github.com/BDragisic).
__________________________
#### Additions
If you have any additions, please open a pull request. You can use the below as a style guide:

```md
 - PackageName: `command.one` / `command.two`
```

Notes:

 - Give the package name first, then a colon, then the command. 
 - This list is organised alphabetically by package name, and web console commands are organised alphabetically as well.
 - If there are multiple web console commands, please separate these with forward slashes.
