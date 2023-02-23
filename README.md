# PROCEYE
# About
A Chrome extension that operates on assessment websites, activating when a user opens a test page. It opens a form for the user to enter their name, email, and test invitation code,also asks the user to declare whether the provided information is correct or not and upon clicking the Start Test button, the user's information is sent to the backend server for storage.The extension performs a camera and audio check, and initiates image proctoring, sending images to the server every 5 seconds (configurable). All image and user activity data are stored on the backend server.

# Step to follow
* Download the zip file on local machine and extract all the files in it.
* Load the file on chrome extension by clicking "load unpacked" on chrome://extensions/
* Run the server by writing "nodemon server.js" on terminal.
* The extension is now ready to use.
* After filling form, wait for 20-30 seconds for the webcam to capture some snapshots.
* Admin can see the captured snapshots along with details on http://localhost:5000/admin
