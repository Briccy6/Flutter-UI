Flutter UIKit
<a href="https://play.google.com/store/apps/details?id=com.mtechviral.flutteruikit&pcampaignid=MKT-Other-global-all-co-prtnr-py-PartBadge-Mar2515-1"> <img alt="Get it on Google Play" src="https://play.google.com/intl/en_us/badges/images/generic/en_badge_web_generic.png" height="90px"/> </a>
The goal of this project is to provide an ultimate collection of real-world app's UIs. While I built Flutter UIKit for my own needs, it is also intended to showcase good app structure and a clean, well-organized Flutter codebase.

The source code is 100% Dart, and everything resides in the /lib folder.

This project will try to showcase only the best, most popular, and well-designed templates that you will actually need and find useful rather than overwhelming you with a plethora of low-quality ones.

Happy learning. :+1:

Show some :heart: and star the repo to support the project






YouTube Channel
MTechViral

Facebook Group
Let's Flutter

Collection of flutter apps with tutorial
Flutter Example Apps

Screenshots
<img height="480px" src="https://raw.githubusercontent.com/iampawan/Flutter-UI-Kit/master/raw/fu12.png"> <img height="480px" src="https://raw.githubusercontent.com/iampawan/Flutter-UI-Kit/master/raw/fu1.png"> <img height="480px" src="https://raw.githubusercontent.com/iampawan/Flutter-UI-Kit/master/raw/fu2.png"> <img height="480px" src="https://raw.githubusercontent.com/iampawan/Flutter-UI-Kit/master/raw/fu3.png"> <img height="480px" src="https://raw.githubusercontent.com/iampawan/Flutter-UI-Kit/master/raw/fu4.png"> <img height="480px" src="https://raw.githubusercontent.com/iampawan/Flutter-UI-Kit/master/raw/fu5.png"> <img height="480px" src="https://raw.githubusercontent.com/iampawan/Flutter-UI-Kit/master/raw/fu6.png"> <img height="480px" src="https://raw.githubusercontent.com/iampawan/Flutter-UI-Kit/master/raw/fu7.png"> <img height="480px" src="https://raw.githubusercontent.com/iampawan/Flutter-UI-Kit/master/raw/fu8.png"> <img height="480px" src="https://raw.githubusercontent.com/iampawan/Flutter-UI-Kit/master/raw/fu9.png"> <img height="480px" src="https://raw.githubusercontent.com/iampawan/Flutter-UI-Kit/master/raw/fu10.png"> <img height="480px" src="https://raw.githubusercontent.com/iampawan/Flutter-UI-Kit/master/raw/fu11.png">
Available Templates:
Templates Category	Currently Available
Profile	View Profile, Profile 2
Shopping	Shopping List, Shopping Details, Product Details
Login	Login With OTP, Login 2
Timeline	Feed, Tweets
Dashboard	Dashboard 1, Dashboard 2
Settings	Device Settings
No Item	No Search Result
Payment	Credit Card, Payment Success
Building the project
Missing Key.Properties file
If you try to build the project straight away, you'll get an error complaining that a key.properties file is missing and Exit code 1 from: /Flutter-UI-Kit-master/android/gradlew app:properties:. To resolve that,

Open Flutter-UI-Kit-master/android/app/ and create a new file named key.properties.
Add the following lines in that file:
makefile
Copy code
storePassword=<your store password>
keyPassword=<your key password>
keyAlias=<your key alias>
storeFile=<your store file path>
Now you should be able to build the project without any issues.
