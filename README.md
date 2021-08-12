# WakeApp
“All my life I have battled the alarm clock, pummeling the snooze button over and over with mounting self-loathing until the shame is finally strong enough to lever me upright”
~Isaac Marion


We all know how easy it is to hit snooze/dismiss on a raucous beeping early in morning and being late for lectures, meetings, fitness goals and whatnot. The standard alarm application is just too easy for a procrastinative individual to ignore and continue riding dragons and playing with fairies and building castles. To tackle this problem, we built an alarm application that requires the user to actually wake up to stop the rowdy noise by solving a problem.


The WakeApp Android Project is quite different from the standard alarm application which we use daily. Sure wake up of the user is achieved with this application. The Application consist of an alarm personalization menu where user needs to enter the details for setting the alarm. Once the alarm is set , it gets scheduled . Whenever the scheduled time arrives, the alarm raises. Basically , in any alarm application when the alarm raises at scheduled time , the two operations that user can perform are : DISMISS and SNOOZE. But , in our application when it raises , it asks some number of mathematical and logical questions randomly to which the user must answer. It is must , because until and unless the user solve those questions , the alarm tone plays in the background. The only way to stop the alarm is to solve the questions, during this process the user comes out from drowsy through which the main aim of the app is achieved. So that, the user can ensure sure wake up.

SCREENSHOTS

![image](https://user-images.githubusercontent.com/60723556/129130375-1892530b-fa0d-4f16-a116-499ee20ea314.png)
![image](https://user-images.githubusercontent.com/60723556/129130394-f878357f-d68a-4e48-91af-ba373a783667.png)
![image](https://user-images.githubusercontent.com/60723556/129130404-58d0bc24-ec6e-4a0c-9b51-40094f1f70ab.png)
![image](https://user-images.githubusercontent.com/60723556/129130410-ae2554f1-ba7c-48fb-804b-5299a44c2403.png)


APIS USED
○ Alarm Manager

■ This class provides access to the system alarm services. These allow you to schedule your application to be run at some point in the future.

○ Broadcast Receiver

■ A broadcast receiver is an Android component which allows you to register for system or application events. All registered receivers for an event are notified by the Android runtime once this event happens.

○ Ringtone Manager

■ RingtoneManager provides access to ringtones, notification, and other types of sounds. It manages querying the different media providers and combines the results into a single cursor. The TYPE_RINGTONE refers to the type of sounds that are suitable for the phone ringer.

○ Notification Manager

■ Class to notify the user of events that happen. This is how you tell the user that something has happened in the background.

○ Chronometer

■ Class that implements a simple timer. It is a subclass of TextView.

○ ArrayAdapter

■ ArrayAdapter uses a TextView to display each item within it. Behind the scenes, it uses toString() method of each object that it holds and displays this within the TextView.



METHODS IMPLEMENTED

1. int_Questions() - Method used to add the math questions. Uses random variable of random class to generate questions.
2. set_song() - Gets default ringtones from the phone to set for the alarm.
3. cancel_alarm() - Boolean function that cancels the alarm if the user chooses to.
4. set_Time() - Sets the time the user wants to wake up at.
5. set_Date() - Sets the date the user wants to wake up at.
6. set_Alarm() - Sets the alarm after the user enters all the required information.
7. solve_Question() - Function that gets the result after solving the problem.
