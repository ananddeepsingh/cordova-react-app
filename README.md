# cordova-react-app
This app is sample app using Cordova and ReactJS to create hybrid app

#hybrid folder
This folder will contain react-app source code. User can modify code as per their requirements.

#simple folder
This folder will contain cordova folders where user can launch their app in web view.


#How to run app from React to Cordova

1. After changes in #hybrid folder use below command
	npm run build
	
2. Then copy contents on build folder and paste in www folder in #simple folder 
3. run cordova serve -> to see changes in browser
4. run cordova emulate android -> to see changes in app