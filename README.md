# Lab-1_202001407

**Name:** Karan Patel 
**ID:** 202001407  

### Q.1. Identify FRs and NFRs:  
**Functional requirements -**  
* **New User Registration:** Whoever wants to use the library's services and is a part of the institute must first register with the system for library resources.After successfully registering, the member would receive a user ID and password. For using LIS, one must use the following credentials.
* **User login:** User has to login using the ID and password he created during registration. If credentials entered are correct, the 'Home' page is shown. Now the user can use features of LIS like issue a book, return a book, reissue a book and many others.If the credentials entered by the user are incorrect then the login failure screen will be shown. If an incorrect password is entered three times consecutively then a security question which was chosen by the user while registering, with an input box to answer it will be shown. Account will be blocked on failing to answer security question. Admin can reactivate an account on request.
* **Issue book:** A LIS member can issue a book if:  
i) It is available in the library.
ii) No one else has issued that book.  
iii) Member has not issued maximum number of books he can issue at a time. 
After a successful issue of a book,user's account is updated to reflect the same.
* **Return book:** A book is issued for a finite time. That is, the book should be returned within this time. After returning the book successfully it is reflected in the user's account.
* **Reissue book:** A user can reissue a book if one needs to use it for more than the stipulated amount of time. A book can not be reissued more than 2 times.
* **Search book:** Users can search only if a book is present in the library using this facility. Book can be searched using its title, author's name, publisher's name or genre.
**Non-functional requirements -** 
* **Performance Requirements:**  
i) System should be available 24x7.  
ii) A particular number of users should be able to access it at any given time.
* **Database Requirement**  
* **Security Requirements:**   
i) Confidential information like passwords should not be stored in plain text, they should be encrypted.
ii) System should be accessible only using institute's LAN. 
* **Software Quality Attributes**
* **Design Constraints:** LIS has to be developed as a web application which should work on Firefox 5, Internet Explorer 8, Google Chrome 12, Opera 10,Safari,Microsoft edge. The web application should be developed using HTML 5.

### Q.2. Identify scope, features and non-functional aspects of the following problem.

**Scope:** The main scope of the project is to develop an application for people suffering from hearing loss. This mobile application uses artificial intelligence to recognize key sound events of interest to this community, such as car horns and babies, where immediate alerts and continual logging are critical for the user.

**Features:**
* It should be a mobile application that uses Artificial Intelligence.
* It should be optimised for Android.
* It should recognise key sounds in the environment.
* It should alert the user about a sound near them.
* It should increase the intensity of the signal as the sound gets louder (nearer) by vibrating or any other means.
* It could convert the audio into sign language.

**Non-functional Aspects:**
* The key sounds should include basic day to day noises like car horns, babies, etc.
* The alerts should be immediate to help the user react quickly.
* The sensitivty of the sound recognition should be neither to less (can't detect a sound) nor too high (detect sounds even though they are nowhere near).
* The application should have low latency so that it works in real-time.
