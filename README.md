Android Alarm Application with Service and BroadcastReceiver
This project is an Android application that demonstrates how to set, run, and cancel a one-time alarm using core Android components like Service, BroadcastReceiver, and AlarmManager.

AIM
To create an Android application that allows a user to set a specific time for an alarm. When the alarm time is reached, a background Service is started, which plays an alarm sound. The user also has the ability to cancel a set alarm, which stops the sound if it's playing and prevents it from ringing in the future.

Features
Set Alarm: Users can click a "Create" button to open a TimePickerDialog and select a time for the alarm.
Display Set Time: Once an alarm is set, its time is displayed on a dedicated card, which becomes visible.
Alarm Notification: At the exact time set by the user, an alarm sound starts playing.
Cancel Alarm: Users can cancel the scheduled alarm. If the alarm is already ringing, it will stop.
Persistent Alarm Scheduling: The app requests the necessary SCHEDULE_EXACT_ALARM permission to ensure reliability on modern Android versions.
UI with Material Design: The user interface is built using Material Components like MaterialCardView and MaterialButton.

