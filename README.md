#Lock Screen Service

#Launch Automator from your Applications folder.

Select “Service” as the document type.
Select “Utilities” from the list on the left, then double-click “Run Shell Script” in the next column.

Lock Mac screen with keyboard shortcut
On the top-right side of the screen, adjust the drop-down menus so the statement reads: “Service receives [no input] in [any application]”
Copy the following command into the large text box that appears:
/System/Library/CoreServices/"Menu Extras"/User.menu/Contents/Resources/CGSession -suspend

Lock Mac screen with keyboard shortcut
Go to File > Save and name your service “Lock Screen”. Once saved, you can now quit Automator.
Lock Screen Keyboard Shortcut
Launch System Preferences and go to the Keyboard pane.
Next, select the “Keyboard Shortcuts” tab. From the list on the left, select “Application Shortcuts”. Click on the plus (+) button below to add your new shortcut.
In the dialog box we’ll want to leave “All Applications” selected in the first menu. Enter “Lock Screen” as the Menu Title. Please note this has to be exactly the same name you entered when saving the service in Automator. Finally, enter your keyboard shortcut. Let’s go with Command+Shift+L.
Lock Mac screen with keyboard shortcut
Click Add and you’re all done!
Now when you press your keyboard shortcut (Command+Shift+L), the Mac login screen will immediately be displayed. You’re still technically logged in and processes such as large downloads will continue in the background. But you can leave your Mac unattended without worry – no one will be able to access your account until you enter your password. When you do, everything on your desktop will be there just as you left it!
