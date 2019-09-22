# IDE Configuration Settings

This is a list of the extensions, settings, keyboard shortcuts, and actions I use with my development environments. I thought it would be much easier to put them all in an easily-accessible list instead of trying to remember every setting and extension, and then hunt them down again when I migrate to a new machine or have to reinstall an editor.

## Visual Studio 2017

### Settings

* Enable Dark theme: `Tools -> Options -> Environment -> General -> Color theme`.

    Visual Studio prompts you to select a theme the first time it's opened, but it's good to know where to go to change it. If you're not using Dark theme, you're crazy.

* Set tabs to spaces: `Tools -> Options -> Text Editor -> All Languages -> Tabs`.

    Set tabs to 4 spaces.

* Make whitespace indicators more visible: `Tools -> Options -> Environment -> Fonts and Colors -> Item foreground`.

    Move the color slider up a few levels to make visible whitespace stand out a little more.

* Enable map mode in scroll bar: `Tools -> Options -> Text Editor -> All Languages -> Scroll Bars -> Behavior -> Use map mode`.

* Disable drag and drop in the code editor: `Tools -> Options -> Text Editor -> General -> Drag and drop text editing`.

### Extensions

* [Viasfora](https://marketplace.visualstudio.com/items?itemName=TomasRestrepo.Viasfora)

* [Trailing Whitespace Visualizer](https://marketplace.visualstudio.com/items?itemName=MadsKristensen.TrailingWhitespaceVisualizer)

* [Indent Guides](https://marketplace.visualstudio.com/items?itemName=SteveDowerMSFT.IndentGuides)

    Visual Studio enables these by default for C#, but they're oddly absent for C++.

* [ClangFormat](https://marketplace.visualstudio.com/items?itemName=LLVMExtensions.ClangFormat)

* [Microsoft Child Process Debugging Power Tool](https://marketplace.visualstudio.com/items?itemName=vsdbgplat.MicrosoftChildProcessDebuggingPowerTool)

### Useful Keyboard Shortcuts

* `F5`: Start debugging.

* `Ctrl + F5`: Start without debugging.

* `F9`: Set breakpoint.

* `F10`: Step to next line.

* `F11`: Step into function.

* `F12`: Go to definition.

* `Shift + F12`: Find all references.

* `Ctrl + k, Ctrl + c`: Comment selection.

* `Ctrl + k, Ctrl + u`: Uncomment selection.

* `Ctrl + -`: Go back.

### Actions/Other

* Untabify Selection: `Edit -> Advanced -> Untabify Selected Lines`

    This can also be accomplished with ClangFormat, but it's useful for untabifying selections of code you don't want formatted otherwise.

## Visual Studio Code

### Settings

Changes made to `settings.json`:

* Show indent lines: `"editor.renderIndentGuides": true`

* Show whitespace: `"editor.renderWhitespace": "all"`

* Trim trailing whitespace: `"files.trimTrailingWhitespace": true`

* Don't ignore leading or trailing whitespace in the diff: `"diffEditor.ignoreTrimWhitespace": false`

* Set Bash as the default terminal: `"terminal.integrated.shell.windows": "C:\\Program Files\\Git\\bin\\bash.exe"`

* Disable drag and drop in the code editor: `"editor.dragAndDrop": false`

### Extensions

* [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer)

* [C/C++](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools)

* [C/C++ Clang Command Adapter](https://marketplace.visualstudio.com/items?itemName=mitaki28.vscode-clang)

* [Github Markdown Preview](https://marketplace.visualstudio.com/items?itemName=bierner.github-markdown-preview): Includes the following extensions:

    * [Markdown Preview Github Styling](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-preview-github-styles)

    * [Markdown Emoji](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-emoji)

    * [Markdown Checkboxes](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-checkbox)

    * [Markdown yaml Preamble](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-yaml-preamble)

### Useful Keyboard Shortcuts

* `F1`: Show all commands.

* `Ctrl + ,`: Open Settings menu.

## MATLAB

### Settings

* [Create a dark theme](https://www.reddit.com/r/matlab/comments/1wb7lw/matlab_dark_theme_easy_way_to_bulkchange_colors/)

     `matlab.prf`can typically be found in `%APPDATA%\Roaming\Mathworks`, but using the `prefdir` command will show the path to the preferences directory.

### Useful Keyboard Shortcuts

* `F12`: Set or clear breakpoint on current line.

* `Ctrl + r`: Comment selection.

* `Ctrl + t`: Uncomment selection.

## Notepad++

* [Dracula theme](https://draculatheme.com/notepad-plus-plus/)