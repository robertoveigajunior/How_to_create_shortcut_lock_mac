#Lock Screen Service

>**1 - Launch Automator from your Applications folder.**

>**2 - Select “Service” as the document type.**

>**3 - Select “Utilities” from the list on the left, then double-click “Run Shell Script” in the next column.**

  ![alt tag](http://www.macyourself.com/wp-content/uploads/2013/01/012713-lockscreen-screen1.jpg)

>**4 - On the top-right side of the screen, adjust the drop-down menus so the statement reads: “Service receives [no input] in [any application]”**

>**5 - Copy the following command into the large text box that appears:**

  >_/System/Library/CoreServices/"Menu Extras"/User.menu/Contents/Resources/CGSession -suspend_
  
  ![alt tag](http://www.macyourself.com/wp-content/uploads/2013/01/012713-lockscreen-screen2.jpg)

>**6 - Go to File > Save and name your service “Lock Screen”. Once saved, you can now quit Automator.**

#Lock Mac screen with keyboard shortcut

>**1 - Launch System Preferences and go to the Keyboard pane.**

>**2 - Next, select the “Keyboard Shortcuts” tab. From the list on the left, select “Application Shortcuts”. Click on the plus (+) button below to add your new shortcut.**

>**3 - In the dialog box we’ll want to leave “All Applications” selected in the first menu. Enter “Lock Screen” as the Menu Title. Please note this has to be exactly the same name you entered when saving the service in Automator. Finally, enter your keyboard shortcut. Let’s go with Command+Shift+L.**

  ![alt tag](http://www.macyourself.com/wp-content/uploads/2013/01/012713-lockscreen-screen3.jpg)

>**4 - Click Add and you’re all done!**

Agora quando você pressionar o atalho (Command+Shift+L), o mac irá imediatamente para a tela de inicio de sessão, apenas com a senha do usuario será possivel logar novamente.

**Referência:** _http://www.macyourself.com/2013/01/27/how-to-lock-your-mac-screen-with-a-keyboard-shortcut/_

