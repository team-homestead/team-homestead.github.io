# Build Instructions

1) Go to https://github.com/team-homestead/client.  

2) Click on the green 'Clone or download' button.  A box will appear that says 'Clone with SSH', if it says 'Clone with HTTP', click on the 'Use SSH'.  Click on the clipboard icon to copy the address.

3) Open IntelliJ.  On the opening page, click on 'Get from version control' (if you already had an IntelliJ project open, go to 'File'->'New'->'Project from Version Control'.  A box will appear and in the URL, CTRL-V to paste the address copied in github and hit 'Clone'.  When asked to open project, say 'No' (if asked again, again say 'No').

4) Go back to your web browser and go to https://github.com/team-homestead/server and reapeat step 2 & 3.

5) Open IntelliJ again.  On the opening page, click on 'Import project' (if you already had an IntelliJ project open, go to 'File'->'New'->'Project from Existing Sources'.  Search for and click on the folder named 'server' and click 'Ok'.  A box will appear, import the project as a Maven project and click 'Finish'.

6) In the project window on the left hand side, expand 'server'->'src'->'main'->'java'->edu.cnm.deepdive.server and double click on 'PreloadLauncher'.  Click on the green play icon on line 5, and click 'Run'.

7) Return to the project window to the left and double click on 'ServerLauncher'.  Click on the green play icon on line 5, and click 'Run'.

8) At the top of the window, go to 'File'->'New'->'Project from Existing Sources'.  Search for and open the folder named 'client' and click 'Ok'.  A box will appear, import the project as a Gradle project (NOT Android gradle) and click 'Finish'.  When prompted, open project in 'New window'.  Leave 'server' window open and running.

9) At this point, open an emulator or connect a physical Android device.  At the top of the 'client' window, go to (Run|Run 'app').  The app will open on your device and is now ready for use.  See [Basic User Instructions](basic-user-instructions.md) if needed.  