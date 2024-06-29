# vscode-setup : Settings for Visual Studio Code

These are my personnal favorite settings and extensions that I apply on every machine (home or work) for the Visual Studio Code IDE.
Older major versions of these settings can be found in the `archive`  folder at the root of the project, or by browsing old commits. They will get updated as my taste changes over the time 😄

## Fonts

Font of choice for editor and terminal : [Anonymous Pro](https://fonts.google.com/specimen/Anonymous+Pro)

2nd font of choice : [JetBrains Mono](https://www.jetbrains.com/fr-fr/lp/mono/)

## Settings

Some settings require a few extensions to be installed in VSCode. You can find them in the **Extensions** section below.

    {
		"editor.fontFamily": "Anonymous Pro",
		"editor.fontLigatures": true,
		"editor.lineHeight": 1.2,
		"editor.snippetSuggestions": "inline",
		"editor.suggestSelection": "first",
		"editor.linkedEditing": true,
		"editor.cursorSmoothCaretAnimation": "on",
		"editor.cursorBlinking": "phase",
		"editor.minimap.enabled": false,
		"editor.padding.top": 14,
		"editor.padding.bottom": 14,
		"editor.renderLineHighlight": "gutter",
		"editor.renderWhitespace": "none",
		"editor.lightbulb.enabled": "off",
		"editor.scrollbar.vertical": "auto",
		"editor.scrollbar.verticalScrollbarSize": 9,
		"editor.overviewRulerBorder": false,

		"window.zoomLevel": 3,
		"window.menuBarVisibility": "compact",
		"window.newWindowDimensions": "offset",
		"window.openFoldersInNewWindow": "on",
		"window.titleBarStyle": "custom",

		"explorer.compactFolders": false,
		"explorer.confirmDragAndDrop": false,

		"workbench.colorTheme": "404 - Muted",
		"workbench.tree.indent": 24,
		
		"workbench.iconTheme": "moxer-icons",
		"workbench.statusBar.visible": false,
		"workbench.sideBar.location": "right",
		"workbench.activityBar.location": "bottom",
		"workbench.startupEditor": "welcomePageInEmptyWorkbench",

		"terminal.integrated.defaultProfile.windows": "Git Bash",
		"terminal.integrated.cursorStyle": "line",
		"terminal.integrated.rightClickBehavior": "default",
		"terminal.integrated.tabs.enabled": false,
		"terminal.integrated.fontSize": 16,

		// Telemetry

		//  - all: Sends usage data, errors, and crash reports.
		//  - error: Sends general error telemetry and crash reports.
		//  - crash: Sends OS level crash reports.
		//  - off: Disables all product telemetry.
		"telemetry.telemetryLevel": "all",

		// Controls when the restricted mode banner is shown.
		//  - always: Show the banner every time an untrusted workspace is open.
		//  - untilDismissed: Show the banner when an untrusted workspace is opened until dismissed.
		//  - never: Do not show the banner when an untrusted workspace is open.
		"security.workspace.trust.banner": "never",

		// When enabled, the diff editor ignores changes in leading or trailing whitespace.
		"diffEditor.ignoreTrimWhitespace": false,

		"security.workspace.trust.untrustedFiles": "open",

		// Extension VSCode Animations
		"vscode_custom_css.imports": [],
		"animations.Install-Method": "Apc Customize UI++",
		"apc.imports": [
			"file:///c:/Users/Mathias/.vscode/extensions/brandonkirbyson.vscode-animations-2.0.3/dist/updateHandler.js"
		],
		"apc.font.family": "Dank Mono",
		"apc.electron": {
		},
		"apc.statusBar": {
			"position": "editor-bottom",
			"height": 22,
			"fontSize": 12
		},
		"apc.activityBar": {
			"position": "bottom",
			"size": 25,
		}
	}

## Themes

I mainly use my own theme that you can find here : [404 Muted](https://github.com/404mat/404muted).

## Extensions

Som extensions are specific to languages and my personnal use. The other ones are mainly for developer experience (animations, colors, ease of use, ...).

 * Developer Experience
	 * [Git Blame](https://marketplace.visualstudio.com/items?itemName=waderyan.gitblame) : See at a glance the author of a block/line of code
	 * [npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense) : npm autocomplete in imports statements
	 * [VSCode Animations](https://marketplace.visualstudio.com/items?itemName=BrandonKirbyson.vscode-animations) : *beautiful* animations in Visual Studio Code
	 * [Moxer Icons](https://marketplace.visualstudio.com/items?itemName=Equinusocio.moxer-icons) : Nice icon pack
	 * [Error Lens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens): Inline errors
	 * [TabOut](https://marketplace.visualstudio.com/items?itemName=albert.TabOut): Quickly tab out of brackets and parenthesis

* Tools
	 * [SonarLint](https://marketplace.visualstudio.com/items?itemName=SonarSource.sonarlint-vscode)
	 * [StyleLint](https://marketplace.visualstudio.com/items?itemName=stylelint.vscode-stylelint)
	 * [Edit CSV](https://marketplace.visualstudio.com/items?itemName=janisdd.vscode-edit-csv) : to edit CSV files in a nice UI
	 * [JSON to CSV](https://marketplace.visualstudio.com/items?itemName=khaeransori.json2csv) : Convert JSON to CSV (both ways work)
	 * [Rainbow CSV](https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv) : to have colors in CSV files (helps in huge files)
	 * [StackOverflow Instant Search](https://marketplace.visualstudio.com/items?itemName=Alexey-Strakh.stackoverflow-search): Search StackOevrflow from VSCode
	 * [icns_preview](https://marketplace.visualstudio.com/items?itemName=waifuproject.icns-preview): MacOS icons viewer
	 * [Excel Viewer](https://marketplace.visualstudio.com/items?itemName=GrapeCity.gc-excelviewer)

* Language specific
	* [Angular Language Service](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template) : Editor services for Angular templates
	* [Angular Schematics](https://marketplace.visualstudio.com/items?itemName=cyrilletuzi.angular-schematics) : easy Angular components geenration on right click
	* [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
	* [JSON](https://marketplace.visualstudio.com/items?itemName=ZainChen.json)
	* [React Native Tools](https://marketplace.visualstudio.com/items?itemName=msjsdiag.vscode-react-native)

Terminal commands for easy install :

    code --install-extension waderyan.gitblame
    code --install-extension christian-kohler.npm-intellisense
    code --install-extension BrandonKirbyson.vscode-animations
    code --install-extension Equinusocio.moxer-icons
	code --install-extension usernamehw.errorlens
	code --install-extension albert.tabout
    
    code --install-extension SonarSource.sonarlint-vscode
    code --install-extension stylelint.vscode-stylelint
    code --install-extension janisdd.vscode-edit-csv
    code --install-extension khaeransori.json2csv
    code --install-extension mechatroner.rainbow-csv
	code --install-extension Alexey-Strakh.stackoverflow-search
	code --install-extension waifuproject.icns-preview
	code --install-extension GrapeCity.gc-excelviewer
    
    code --install-extension Angular.ng-template
    code --install-extension cyrilletuzi.angular-schematics
    code --install-extension dbaeumer.vscode-eslint
    code --install-extension ZainChen.json
    code --install-extension msjsdiag.vscode-react-native

## Keybinds

Remplir Keybinds
