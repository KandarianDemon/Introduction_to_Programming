## Installation Instructions

### Intellij IDEA

#### Program

1. Head over to http://jetbrains.com/idea/download Download the Community edition for your operating system
2. Execute the program (either from the downloading browser or your 'downloads' folder)
3. Choose Install Location -> Default is OK
4. Installation options
   - if you like desktop Shortcuts you might choose this
   - leave rest unselected
5. Choose Start Menu Folder -> Just click Install
6. When installation finished, Check 'Run IntelliJJ IDEA Community Edition' and click 'Finish'. In case it doesn't start automatically, you can start it via the app-bar.
7. You now should get a 'Welcome to IntelliJ IDEA' start up window
8. Choose 'new project'

#### Add-Ons

9. On the left side of the new window, click 'Android'
10. Click 'Install SDK' (SDK = Software Development Kit)
11. On the 'Missing SDK' Window, click 'Next'
12. 'SDK Components Setup' select
    - Android SDK
    - Android SDK Platform
    - API 32 (This number might be higher for you, depending on installation date)
    
    Click 'Next'
13. The next screen gives you a summary of your option. Click 'Finish', cross fingers and wait. If you're wondering what's going on, click 'Details'
14. When you're allowed to click 'Finish', make it so!
15. Now you're back on the 'Configure Android SDK' Window. Click next.

#### Load first program

16. You are now on the 'Select a Project Template' screen. Choose 'Phone and Tablet' (And observe that you will be able to also program wearables and TVs). On the rightmost panel choose 'Empty Activity' and click 'Next'
17. Now you can 'Configure Your Project'. Give your application a 'Name' like 'InstallationTest'. Make sure that you've selected the 'Language' Kotlin. Click on the Minimum SDK and select 'API 28: Android 9.0 (Pie)'. Click 'Finish'
18. Now loads of things are happening in the background, so this step might take some time. You can get some idea about what's going on in the right half of the bottom line of the program. (And you can close the 'Tip of the Day' Window ;-). You can also click on 'Show all' to get a  more detailed report. Despite from this, give your computer the time it needs.
19. Once you see some nicely colored program code, this step ist finished. Nice!

#### Install a virtual Phone

20. In the second (from the top) menu line, there is a drop-down menu called 'No device'. Click on it and select 'AVD Manager'
21. Select '+ Create Virtual Device'
22. Select 'Phone' and 'Pixel2'. Click Next.
23. As we selected Android 9.0 in step 17, let's keep this consistent. Choose 'Pie Download' and click next.
24. Accept the Licence agreement and click 'Next'
25. Once the 'Component Installer' is done, click 'Finish'
26. On the 'System Image Window', select 'Pie' (the Android version we just installed) and then 'Next'
27. On the 'Android Virtual Device (AVD)' window, stay with the defaults and click 'Finish'
28. Close the 'Your Virtual Devices' window

#### Start your first android program on the emulator

29. In the drop-down menu you should now see 'Pixel 2 API 28'. On the right there is a green rectangle. Click on it and wait.
30. Tons of magic happenng now, which we will talk about in the course.
31. Once everything is finished, you should see an Android Phone with an opened App. Awesome! You just installed you own App on an emulated Android device on your computer!!


