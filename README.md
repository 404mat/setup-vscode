# vscode-setup : Settings for Visual Studio Code

These are my personnal favorite settings and extensions that I apply on every machine (home or work) for the Visual Studio Code IDE.
Older major versions of these settings can be found in the `archive` folder at the root of the project, or by browsing old commits. They will get updated as my taste changes over the time 😄

## Fonts

Font of choice for editor and terminal : [Anonymous Pro](https://fonts.google.com/specimen/Anonymous+Pro)

2nd font of choice : [JetBrains Mono](https://www.jetbrains.com/fr-fr/lp/mono/)

## Settings

The [settings file](./vscode-settings.json) can be copied as is. Some settings require a few extensions to be installed in VSCode. You can find them in the **Extensions** section below.

## Themes

I mainly use my own theme that you can find here : [MossFrame](https://github.com/404mat/mossframe)

Other theme I made : [404 Muted](https://github.com/404mat/404muted).

## Extensions

Som extensions are specific to languages and my personnal use. The other ones are mainly for developer experience (animations, colors, ease of use, ...).

- Theming

  - [VSCode Animations](https://marketplace.visualstudio.com/items?itemName=BrandonKirbyson.vscode-animations) : _beautiful_ animations in Visual Studio Code
  - [APC Customize UI++](https://marketplace.visualstudio.com/items?itemName=drcika.apc-extension): Used for VSCode Animations
  - [CityLights Icon Pack](https://marketplace.visualstudio.com/items?itemName=Yummygum.city-lights-icon-vsc) : Nice icon pack

- Developer Experience

  - [Git Blame](https://marketplace.visualstudio.com/items?itemName=waderyan.gitblame) : See at a glance the author of a block/line of code
  - [npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense) : npm autocomplete in imports statements
  - [Error Lens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens): Inline errors
  - [TabOut](https://marketplace.visualstudio.com/items?itemName=albert.TabOut): Quickly tab out of brackets and parenthesis
  - [Tailwind Fold](https://marketplace.visualstudio.com/items?itemName=stivo.tailwind-fold): Fold HTML classes to cleanup editor view
  - [Scope to This](https://marketplace.visualstudio.com/items?itemName=rhalaly.scope-to-this): Scope to a specific folder
  - [Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight): Highlight hex codes colors
  - [Todo Highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight): Highlight todo and fixme words
  - [Rightclick Git](https://marketplace.visualstudio.com/items?itemName=Everspace.rightclick-git): Git actions in context menu
  - [Bookmarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks)
  - [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

- Tools

  - [SonarLint](https://marketplace.visualstudio.com/items?itemName=SonarSource.sonarlint-vscode)
  - [StyleLint](https://marketplace.visualstudio.com/items?itemName=stylelint.vscode-stylelint)
  - [Edit CSV](https://marketplace.visualstudio.com/items?itemName=janisdd.vscode-edit-csv) : to edit CSV files in a nice UI
  - [Rainbow CSV](https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv) : to have colors in CSV files (helps in huge files)
  - [StackOverflow Instant Search](https://marketplace.visualstudio.com/items?itemName=Alexey-Strakh.stackoverflow-search): Search StackOevrflow from VSCode
  - [icns_preview](https://marketplace.visualstudio.com/items?itemName=waifuproject.icns-preview): MacOS icons viewer
  - [Tailwind Docs](https://marketplace.visualstudio.com/items?itemName=austenc.tailwind-docs)

- Language specific

  - [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
  - [React Native Tools](https://marketplace.visualstudio.com/items?itemName=msjsdiag.vscode-react-native)
  - [TailwindCSS Intellisense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss)
  - [Pretty TypeScript Errors](https://marketplace.visualstudio.com/items?itemName=yoavbls.pretty-ts-errors) : Must need or TypeScript errors comprehension

You can install them all at once by running the `install_extensions.sh` script.

## Keybinds

I currently use the default keybinds, but if they change I will put them here. I also added Cmd+N to toggle the secondary sidebar.
