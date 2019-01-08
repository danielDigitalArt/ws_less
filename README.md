# ws_less
less compiler extension for TYPO3

# Typoscript
```
		editor = fileadmin/templates/less/editor.less
		editor.outputdir = fileadmin/templates/css/
		editor.noHash = 1
```
Will generate "fileadmin/templates/css/editor.css" this file can be uses for the ckeditor formating, so in the CsPresets.yaml one must only set "contentsCss: "../fileadmin/templates/css/editor.css"" in order to have the ability to define the editor-style in a less file.
