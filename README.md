# My Fun Run

## Team Roster:

 * Anastasia Hristian
 * Christie Ryan
 * Jason Shaner

## Ground rules

 * [Ground rules](ground-rules.md)

## Project description 

_My Fun Run_ is an Android virtual themed race app with a cloud service which allows you to store 
that data from races. Users can track and save their routes while utilizing themed race mode options
 to simulate real life themed runs. This ultra-immersive running game will get any user motivated to 
 get running and achieve their goals.
 
During registration a user will be asked to select their desired skill level: beginner, intermediate, or advanced. After registration when 
the user logs in they will select a race, along with an optional theme or event. Users will be able to track their distance, time, and pace for
 each run. This saved data can be used to track their daily, weekly,and monthly progress. These 
 stats can also be used to compete against other users of the app. Their stats will be
 grouped according to skill level, and will be ranked on the distance they ran and their time. This will
 create ranking for users to see where they stand against other app users. Also, runners can choose 
 to comment on other user's runs providing further encouragement. Runners will repeat this process
 for each run they complete and choose to publish for others ranking and others to view. Users can
 choose not to publish run stats and save for private viewing and personal tracking purposes.

## User stories

* Seasoned Runners

    > As an active, competitive runner who is always looking to increase my speed and endurance, I need a convenient way to keep track of my daily runs,
      and see how I measure up to other runners in the community.
	
* Novice/Unmotivated Runners
	
	> As someone relatively new to running, and looking to make it part of my regular exercise routine, I need a fun motivator to help me stay interested and focused,
      and a way for friends and family to offer encouragement.

## External services/sources

   * [Google Sing In](https://developers.google.com/android/guides/http-auth) - will allow users an easy login process.

   * [Accelerator](https://developer.android.com/guide/topics/sensors/sensors_motion) - will help the app gather user run stats.
   
   * [Timer/Clock](https://developer.android.com/guide/components/intents-common#CreateTimer) - will be used to track the length of the user's run.
     
   * [Media Player](https://developer.android.com/reference/android/media/MediaPlayer) - will be used to control playback of audio/video files and streams.
      
   * [GPS](https://developer.android.com/training/articles/wear-location-detection) - will allow users to track their distance while running.

   * [Push Notifications](https://developer.android.com/guide/topics/ui/notifiers/notifications) - will allow users to stay motivated by receiving notification reminders.
     
   * [Bluetooth](https://developer.android.com/guide/topics/connectivity/bluetooth) - will allow the user the ability to connect for a hands free experience.
     
   * [Google Play Store](https://developer.android.com/distribute/google-play) - by publishing this app more people will be able to use it and keep up their motivation.


## Design documentation

   * [Entity-relationship diagram](docs/erd.md)

## [Entity classes](https://github.com/my-fun-run/funrun-service/tree/master/src/main/java/edu/cnm/deepdive/funrun/model/entity)

