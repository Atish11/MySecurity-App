# MySecurity-App



MySecurity App is a project done while studying Cybersecurity by Atish Ojha. This application is known as secure application. Using its Signup, Sigin and forgot password technology one can make their application secure. Here I have used Java as programing language and google firebase as the database of the application.

This is Android based application.


## Screenshots

### Splash Activity
<img width="325" height="700" src="https://user-images.githubusercontent.com/78890102/184328296-7cf211e9-aba8-4e36-ab7c-32c1a372dceb.jpg">

Opening the application user will be greeted with this screen. This screen contains logo of the application which remains for 2-5 sec depending on user’s internet. As I have used firebase database to store all the information of the application. So internet is necessary to run application.

---

### SignIn Activity
<img width="325" height="700" src="https://user-images.githubusercontent.com/78890102/184329508-c773f100-961e-440f-b27f-e25c19f49053.jpg">

After few seconds on splash screen user is directed sign in page. Here if user has created their account then they have to provide required information to sign in to application, if not than have to click on “New User | Sign Up!” to create a new account. User have an account but forgot password they can reset it by clicking on “Forgot Password?”
Data of user are saved on firebase and login system is also handled by authentication system of firebase.

---

### Forgot Password Activity
<img width="325" height="700" src="https://user-images.githubusercontent.com/78890102/184331198-0a099007-323b-4ca3-b42f-2928ce705d76.jpg">

When User clicked on “Forgot Password?” in sign in page they are redirected to this page. If user needs to reset their password they have just to provide registered email and click on reset password button. If email is registered in application than user get an email in same email address sand can reset password from there. If email is incorrect then an error message is shown to user. By clicking on “Go Back” user is redirected to sign in page.

---

### Sign Up Activity
<img width="325" height="700" src="https://user-images.githubusercontent.com/78890102/184331208-d436fe6a-1dc9-4891-a683-a59e9e5e89a5.jpg">

When User clicked on “New User | Sign Up!” in sign in page they are redirected to this page. Here user needs to provide required information and a unique email to create an account.
Providing data and clicking on Sign Up button system checks information and if everything is valid then user is redirected to login page where usher should provide required information to sign in.

---

### Home Activity
<img width="325" height="700" src="https://user-images.githubusercontent.com/78890102/184331196-b953c1af-ff42-4492-a24a-222581b1b033.jpg">

After giving correct credentials user is redirect to this page with a toast message. 

---

### Sign Out
<img width="325" height="700" src="https://user-images.githubusercontent.com/78890102/184331153-fb22464e-35f3-4beb-9dca-4a941331c23a.jpg">

By clicking Sign Out from navigation drawer menu user is promoted to an alert dialog saying are you sure if user select ok then user get signed out from the application.

---

### After Sign Out Sucessful
<img width="325" height="700" src="https://user-images.githubusercontent.com/78890102/184331141-d9a38f79-858c-4f21-9179-62fdefdf5331.jpg">

After user sign out is successful they are directed to login page with a toast message. If user wants to exit application they can click the cross icon at Top right of the application which will allow user to exit application.

---





