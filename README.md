## Obsidian Multi-line Formatting Plugin 

This plugin is designed to offer formatting over an entire selection, even if that selection has paragraph breaks in the middle! However, this plugin is new and has only had limited testing. I am grateful for your patience and your bug reports!

## Usage

Select the text you want to format, and use the command **Format, even over multiple lines** (you can change this command name and what kind of formatting to apply in Settings). Be careful not to start but not end your selection in the middle of another type of paired formatting (e.g. bold, italics, highlighting, etc.) or vise versa. If no text is selected, the command will "toggle on" the formatting, so that what you type next will be formatted.

## Settings

Two formatting styles exist by default. To add a new formatting style, scroll to the bottom of the settings pane (Multi-line Formatting Plugin Options) and click the **Add formatting style** button.

For each formatting style, you can enter the formatting you want to apply as **Left** and **Right**. You can change the **Nickname** of the command so that the name in the command palette better reflects the kind of formatting you choose.

If you want to be able to select large amounts of text but not apply your formatting style to headings in that selection you can toggle **Skip Headings** on.

You can delete formatting styles that you are not using by clicking the **Delete this style** button at the bottom of styles settings for any style.

### Hotkeys

Like any other Obsidian commands, you can assign hotkeys to the formatting style commands generated by the Multi-line Formatting plugin in the **Hotkeys** options (separate from the Plugin Options), including reassigning the usual Strong/Bold (Ctrl + b) and Italics/Emphasis (Ctrl + i) hotkeys to their Multi-line Formatting commands.

## Limitations

Again, this is an early version of this plugin which has had limited testing. Help me improve it by reporting any unexpected behaviour. However, note that currently code block sections are skipped, but code blocks embedded in list items or blockquotes are not formatted correctly. 

### Planned Features

- Jump to formattable part of the line if you apply the command with an empty selection 
- Handle embedded code blocks

## Bug reports and feature requests appreciated!

Please let me know how this plugin can be improved.

### Acknowledgements

A huge thank you to **lynchjames**, whose [Note Refactor Plugin](https://github.com/lynchjames/note-refactor-obsidian) formed the base for this plugin, and to **THeK3nger** for the [Obsidian Plugin Template](https://github.com/THeK3nger/obsidian-plugin-template), and to [roshanshariff](https://github.com/roshanshariff) for help debugging and refactoring!
