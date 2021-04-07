# WIDK
## Created by Daniel Haim

WIDK - Word I Don't Know is a short apple script that lets you assign a keyboard shortcut to automatically add a portion of highlighted text to a note in the mac bulletin notes app.
If you have any questions feel free to reach out. In it's current configuration the script is set to add the word to a note names "WIDK". 


To get the script working:
1. Create a note on the notes app called WIDK (to name a note just have WIDK on a line of its own at the beginning of the note)
2. Save the script to your computer using automator. 
you can either download the WIDK file and place it in the Library/Services folder or follow steps 2.1 - 2.6
2.1 Open the automator app (pre installed with any mac)
2.2 Choose a new Quick Action from the menu that opens app
2.3 Open the library if it isn't enabled. (from the top menu click view > show library)
2.4 In the search filed lookup run apple script
2.5 Drag and drop into the editor on the right
2.6 Paste the script from the WIDK file and save under the name WIDK 

3. Enable the WIDK shortcut 
3.1 In the system preferences click keyboard icon 
3.2 Select the shortcuts tab
3.3 Select services from the categories menu on the left
3.4 Scroll all the way down and under general you should see WIDK
3.5 To the right of the WIDK script name you should see "none" when you hover over it, it'll turn into add shortcut , click on add shortcut
3.6 i personally use the shortcut Control+W but you can pick any shortcut you want.


5. Set the permissions
5.1 (go back to the main system preferences) and click Security & Privacy 
5.2 Select the Privacy Tab 
5.3 Select the accessibility from the categories menu on the left
5.4 enable automator

6. You're done !
7. You might be promoted to approve permission for each app you use the shortcut from.


