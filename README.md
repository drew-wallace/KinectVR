# KinectVR
Room Scale Full Body Tracking for Mobile VR

GET STARTED
(NEW MUCH SIMPLER GUIDE COMING SOON)

Hardware Setup • Server Setup • Start Tinkering
HARDWARE REQUIREMENTS
- A Windows machine with Kinect Studio Installed

- Kinect v1 or Kinect v2

- A mobile VR set (Google Cardboard or Samsung Gear VR)

SOFTWARE REQUIREMENTS
- Kinect SDK for Windows

- Unity

- Android Studio or Xcode

- Cardboard SDK (detailed tutorial for iPhone and Android)

- NodeJs (for networking)

HOW DOES IT WORK?


SIMPLE SETUP GUIDE (MORE DETAILED TUTORIAL IN THE WORKS)

 
After unzipping the download, open the KinectVR-broadcaster folder as a Unity Project


	
Open the broadcast unity scene


	
Select AliceManager inside the Kinect prefab, change the HOST to your local IP


	
Export as a Windows Standalone build, this will broadcast raw Kinect data to node.js


	
	
	
Right click the console shortcut, and select it's properties


	
Copy the url to the js file in the target field and make sure node.js is installed


	
Right click and edit the KinectVRServer.js file and modify var HOST to your local IP


	
Open the KinectVR-Server shortcut or run the KinectVRServer.js file in node.js


	
Open the KinectVR-broadcaster you exported earlier, it should auto connect to node.js


	
Open the KinectVR folder as a Unity project


	
Open the KinectVR-Client scene


	
Open the KinectVR prefab to find AliceManger


	
Edit the Host IP inside the AliceManager



When you press play, Unity will connect to node.js and recieve the Kinect data


