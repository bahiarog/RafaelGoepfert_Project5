# VR Project
Vr Project is a VR app for iOS Devices. This app is the result of an VR Degree on udacity.com
# Quick Start
To get started putting VR app on iOS, navigate to the Apple ID website and create a free account. Note that this account will not be able to publish apps to the store unless you pay Apple's yearly fee, but you can still test on your personal device. Once you have created an account, you will need to install the latest version of XCode from the Mac App Store.
##**XCode Setup**
This is a BIG download so feel free to step away from your computer or check out more VR apps. Once it is installed, go ahead and open Xcode and from the menu bar, select Xcode > Preferences.

Choose Accounts at the top of the window to display information about the Apple IDs that have been added to Xcode. Click the plus sign in the bottom-left corner and choose Add Apple ID. Enter the e-mail and password for the account you created. With that, XCode should be setup.
###**Unity Setup**
Let’s now hop into Unity. Once Unity opens into the Udacity project, go to File > Build Settings...
Here, let’s click iOS, then Switch Platform. This may take a minute.

The last step to check is the Player Settings. If we click that Player Settings button, it will bring up a lot of settings in the Inspector. In this project, we have already filled out all the information here.

But when you are building your own app, you will want to make sure the the Default Orientation is set to Landscape Left.
And in Other Settings, you will also want to set the Bundle Identifier to be a unique name.
And with that, click Build and Run.

After checking those settings, click Build. When we do that Unity, will prompt you for a location to Save an XCode project that it will create. Let’s create a Build folder in the top directory of your project.

Once that completes, we can close Unity and then open the project that we built into XCode. Don't worry for now if you see lots of yellow warning symbols in XCode as long as your build works (as versions of Unity and XCode drift, there will be more). You can now connect your iPhone to your Mac with a USB charging cable.
Once your app builds and you see the new icon on your iPhone. If you try to launch it the first time you will probably get an error that the developer is untrusted on your phone. If you look at Xcode on your computer, you'll see this dialogue box telling you how to trust your Developer App certificate. You can then click the Run button and then once XCode builds the project, your phone will be running the Udacity app.

# License
The content of this repository is licensed under bahiarog@me.com
