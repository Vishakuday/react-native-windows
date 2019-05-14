# react-native-windows
Skeleton setup for react-native windows
Steps:
1) npm install
2) react-native windows
3) react-native run-windows

To run the app in production mode(change the folder paths accordingly): 

react-native bundle --platform windows --entry-file index.js --bundle-output windows\testapp\ReactAssets\index.windows.bundle --assets-dest windows\testapp\ReactAssets --dev false

To create packages:
1) Run the above the command
2) Open the sln file in visual studio
3) On the top change the processor setting to x64 and select release bundle.
3) in the solution explorer, right click on project and hover over store. 
4) Go to create app packages and select options accordingly.

To install the app :
1)open the app packager which has been created.
2) right click the powershell file and select run with powershell


