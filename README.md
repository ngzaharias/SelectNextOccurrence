# Select Next Occurrence

Download this extension from the [VS Gallery](https://marketplace.visualstudio.com/items?itemName=thomaswelen.SelectNextOccurrence).

---------------------------------------

This extension makes it possible to select next occurrences of a selected text for editing.

Aims to replicate the Ctrl+D command of Sublime Text for faster coding.

See the [change log](CHANGELOG.md) for changes.

## Features

- Select next occurrence of current selection. 
- Skip occurrence
- Undo occurrence
- Use multiple carets to edit
  - Alt-Click to add caret

![Select Next Occurrence](select_next.gif)

##### Options
Toggle case-sensitive search by using the "Match case" setting from the find-dialog (Ctrl+F)

### Key-bindings
Go to Tools -> Options -> Keyboard and search for these command names to edit at your choice. Make sure the _Use new shortcut in_ is set to: ***Text Editor***

- ```Edit.SelectNextOccurrence``` is bound to ***Ctrl+D*** by default.
- ```Edit.SkipOccurrence``` is ***not bound*** by default. *(Recommended Ctrl+K, Ctrl+D)*
- ```Edit.UndoOccurrence``` is ***not bound*** by default. *(Recommended Ctrl+U)*

![Select Next Occurrence Keyboard bindings](kbd_shortcuts.png)

## Contribute
Check out the [contribution guidelines](CONTRIBUTING.md)
if you want to contribute to this project.

For cloning and building this project yourself, make sure
to install the
[Extensibility Tools 2015](https://visualstudiogallery.msdn.microsoft.com/ab39a092-1343-46e2-b0f1-6a3f91155aa6)
extension for Visual Studio which enables some features
used by this project.

## License
[Apache 2.0](LICENSE)