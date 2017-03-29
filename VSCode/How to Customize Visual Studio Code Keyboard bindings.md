# How to Customize Visual Studio Code Keyboard bindings

1. Go to VS Code menu Preferences-->Keyboard Shortcuts.

1. It opens Default Keyboard Shortcuts file and keybindings.json file.

1. Press F3 in Default Keyboard Shortcuts file and find a command to customize. For this sample scenario, type extension.runQuery.

1. Copy extension.runQuery keybinding definition from Default Keyboard Shortcuts file.

1. Paste to keybindings.json file and change the value for the "key" property to "F5".

	```json
	// Place your key bindings in this file to overwrite the defaults
	[
  		{ "key": "F5",           "command": "extension.runQuery",
                           "when": "editorTextFocus && editorLangId == 'sql'" }
	]
	```

1. Save keybindings.json file and try the new shortcut.