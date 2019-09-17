# VSCode-tips-and-tricks

## How to split a line based on space or comma

- Move the list to the position where you would like to see the first element
- Select the first comma
- Execute editor.action.addSelectionToNextFindMatch (on Windows it's set to CTRL+d by default) until all commas are selected. Keep pressing Ctrl + D again and again
- Now you have multiple selections with multiple cursors at every comma. Press the right arrow key to set the cursors behind the commas
- Press ENTER
- Adjust the indentation if you wa
