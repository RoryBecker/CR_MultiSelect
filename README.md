# 'Multi Select' for CodeRush #

## Warning:

**This plugin now ships natively with CodeRush 11.2 and higher. It remains here as an example only.**

### Introduction ###
This awesome plugin allows you to define and use multiple selections instead of the normal singular selection supported by Windows natively.

### Additional Configuration ###

You will need to [bind some shortcut keys](http://community.devexpress.com/blogs/rorybecker/archive/2010/10/05/binding-keys-in-coderush.aspx) to make this plugin useful.

We suggest binding...

 * Ctrl + NumEnter = MultiSelectAdd
 * Ctrl + NumDel   = MultiSelectClear
 * Ctrl + NumMinus = MultiSelectUndo
 * Ctrl + NumPlud  = MultiSelectRedo

### Usage ###
Assuming that you've setup the keys as directed above..

 * Defining Multiple Selections.
   * Highlight come text
   * Use Ctrl + NumEnter to add a MultiSelect selection.
   * Repeat the first 2 steps as needed.

 * Use Ctrl + NumMinus to remove the most recently created selection.

Once you have defined your selections, you may either Cut or Copy those selections to the clipboard.

This clipboard content may be pasted anywhere in Windows where text could normally be entered.

For more details see [this blogpost](http://community.devexpress.com/blogs/rorybecker/archive/2011/09/20/new-plugin-cr-multiselect.aspx)
