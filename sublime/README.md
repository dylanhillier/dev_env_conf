# Quick Setup for Golang Development


1. Install sublime text
2. Install package manager from:
https://packagecontrol.io/installation
3. Copy the following into the `Package Control.sublime-settings` file in the `Packages/User` directory, or copy the file in this directory.
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

Note: By pre-populating the `Package Control.sublime-settings` file, the package control will automatically dowbload the packages on startup of sublime.`
