## Coffe Code Editor

### 2024-05-02  CCE V1.2


1. **Title Change**: The title of the code editor was updated from "Code Editor v1.0" to "Coffee Code Editor v1.2" in Version 1.2.

2. **Autocomplete Functionality**: Version 1.2 introduced autocomplete functionality for HTML tags. The `autocomplete_list` was defined with a list of HTML tags, and key bindings were added to show the autocomplete menu when pressing F5 or '<' key.

3. **Settings Handling**: Version 1.2 introduced functionality to save and load settings using a JSON file named 'settings.json'. This includes saving and loading the theme settings and tag colors. New functions `save_settings`, `load_settings`, `delete_saved_theme`, and `restore_default_theme` were added for managing settings.

4. **Menu Changes**: In Version 1.2, the "Open Folder" option was added to the File menu to allow users to open entire directories. Additionally, options to save the current theme, delete the saved theme, and restore the default theme were added to the Theme menu.

5. **Icon Addition**: Version 1.2 added functionality to set a custom icon for the code editor window using the `iconbitmap` method.

6. **Theme Handling**: In Version 1.2, the `update_theme` method was modified to update both the background and foreground colors of the text area according to the selected theme.

7. **Code Refactoring and Cleanup**: Both versions share similar structures and functionalities, but Version 1.2 includes some refactoring and cleanup for better organization and readability.

These changes in Version 1.2 enhance the functionality and user experience of the code editor, making it more versatile and user-friendly.
