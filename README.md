# keylogger
This project selectively records keystrokes exclusively on the local machine where it operates, saving the data in a file named keystrokes.log for later retrieval.

**Keylogger Setup Guide**

To prioritize your privacy, this program avoids capturing and sending every keystroke to an external party. Instead, it exclusively records keystrokes on the local machine where it operates. The recorded data is stored in a file named `keystrokes.log`, accessible for later reference.

**Setup Instructions:**

1. **Administrator/Root Privileges:**
   - Ensure you have administrator/root privileges to run the tool.

2. **Install Keyboard Library:**
   - Use the following command to install the required keyboard library:
     ```
     sudo pip3 install keyboard
     ```

3. **Run the Program:**
   - Execute the program using the command:
     ```
     sudo python3 keylogger.py
     ```

4. **Testing the Keylogger:**
   - Type any text on your keyboard.
   - Locate the `keystrokes.log` file in the same directory as your `keylogger.py`.
   - View the file content using the `cat` command.

Feel free to test and explore the functionality of the keylogger in a controlled environment.
