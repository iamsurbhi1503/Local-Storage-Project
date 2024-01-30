# Local-Storage-Project

This script allows users to save and retrieve text entered into a textarea using local storage. It includes functionality to automatically populate the textarea with previously saved text and updates the local storage whenever the user makes changes.

### How it Works

1. **Textarea Element:**
   - The script identifies the textarea element with the ID "myTextarea."

2. **Save to Local Storage:**
   - The `saveToLocalStorage` function is defined to store the content of the textarea in the local storage using the key "savedText."

3. **Check for Existing Data:**
   - On page load, the script checks if there is existing text stored in the local storage under the key "savedText."

4. **Populate Textarea:**
   - If saved text is found, it is retrieved from local storage and populated in the textarea.

5. **Event Listener:**
   - An event listener is added to the textarea for the "input" event.
   - Whenever the user makes changes to the textarea content, the `saveToLocalStorage` function is triggered to update the local storage.

### How to Use

1. **Loading Saved Text:**
   - Upon page load, the script checks for previously saved text in the local storage.
   - If found, it populates the textarea with the saved text.

2. **Saving Text to Local Storage:**
   - As the user types or modifies the text in the textarea, the local storage is automatically updated.
   - The text is saved under the key "savedText."

3. **Retrieving Saved Text:**
   - Saved text is retrieved and displayed in the textarea when the user revisits the page.

### Notes

- **Local Storage:**
  - The script uses the local storage feature of the browser to persistently store and retrieve the textarea content.

- **Event Listener:**
  - The "input" event listener ensures that changes to the textarea trigger the saving function in real-time.

### Potential Enhancements

- **Clear Button:**
  - Add a button to clear the saved text from both the textarea and local storage.

- **User Feedback:**
  - Provide feedback to the user when the text is successfully saved or cleared.

### Contributions

Contributions and feedback are welcome. If you encounter issues or have suggestions for improvements, feel free to open an issue or submit a pull request on the GitHub repository.

Enjoy using the Local Storage Textarea script!
