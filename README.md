# Digital-Education-Eureka
## A Location Based Tutoring App

## Abstract
Since, teachers cannot focus on each student individually, our mobile application Eureka helps the students to take tuition from people around them. It basically helps them to interact with people who have some knowledge in a specific stream or subject and learn something the other knows. This will help us share whatever we know with others and gain their knowledge too. Eureka integrates the Google Maps API to track the locations of all student requests on campus and displays them with digital pins. It allows each user to create and manage their own account, including the topics they would like to teach and profile picture. They can easily switch between tutor and student depending on their needs. Student requests are displayed across the map while tutor acceptances are displayed in a list view. Tutor and student can communicate easily through the chat area.

## Tech Stack Involved
The application is build completely with Android Studio and the modern language Kotlin. We used Google Firebase as our main authentication and database tool, storing user information, tutoring requests and offers, and user messages. We used the Google Maps API to accurately locate and display all students requesting assistance with their classes.

## Working-
Just like a normal mobile application,it has registration and login.After registering,wait for a few minutes as it might take time in uploading your database.

As soon as it uploads,your student-tutor window will appear.

If you are logging in directly,the wait will ne shorter(just the time taken for verification).After that the main activity student-tutor activity is opened.

Here,the default fragment is tutor's so,a map of areas around you will see some locations pinned,those are the requests from students wishing to learn. When you click on the pinned location, the subject and subject code will show in the marker title. On clicking the marker info the whole information will appear, i.e subject, subject code, time, date and whatever additional information the student enters.

But

The Name and other personal details are hidden because of the privacy and security issues. Instead of the name and personal info, we'll show the unique ID assigned to them during registration.

Now, With the subject and topic info, the app will ask for the charges of the tutor per hour. This is done to let the students who like teaching, earn a few extra bucks side by side.

If you want to study-

You have to move to the student window through the bottom navigation bar. There, you have to enter the details of what you want to study, when and how. This information will be stored in the database along with your location, now you just have to wait for the tutor to find you.

The location thus stored helps in marking the pin on the map.

When the tutor selects the student (based only on the subject, time etc. because he won't be able to access rest of the information), the details of the tutor appear in the waiting window of the students. They can check the ratings and reviews of the tutor and then decide whether to study from him/her or not.

In this way, we provide a secure studious environment in the campus.

If the student wants to study from the tutor who offered to teach, he/she can simply tap on the information displayed in the waiting window. This tap will signify acceptance of the tutor and a chat window will appear. In this window, both student and tutor and communicate beforehand to decide the way of the lessons and different criteria of teachings. The location for studying is to be decided somewhere where both can arrive easily. And if the mentee is not comfortable with the mentor, he/she can block the mentor, thus, providing a safe and secure social platform also.

The main benefit of this app comes into play for students who are too shy to ask doubts from teachers and too simple-minded to understand the ways of an online tutor. Those students are meant to be sit with and explain the topics like a friend.

# Thank you.
