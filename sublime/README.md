# Quick Setup for Golang Development

1. Install golang
2. Install sublime text
3. Install package manager from:
https://packagecontrol.io/installation
4. Copy the following into the `Package Control.sublime-settings` file in the `Packages/User` directory, or copy the file in this directory.
    ```
	{
		"bootstrapped": true,
		"in_process_packages":
		[
		],
		"installed_packages":
		[
			"GitGutter",
			"GoGuru",
			"GoImports",
			"Markdown Preview",
			"MarkdownEditing",
			"Package Control"
		]
	}
    ```
    Note: By pre-populating the `Package Control.sublime-settings` file, the package control will automatically dowbload the packages on startup of sublime.
5. Update the `Preferences.sublime-settings` file in the `Packages/User` directory to contain the GOPATH environment, as shown in the following snippet.
    ```
	{
		"env":
		{
		"GOPATH": "$HOME/Development/go"
		},
		"font_size": 12,
		"ignored_packages":
		[
			"Vintage",
			"Markdown"
		]
	}
    ```
6. Configure GoSublime to use goimports:
    ```
    ...
    "fmt_cmd": ["goimports"],
    ...
    ```
