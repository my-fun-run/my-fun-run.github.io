# My Fun Run

## Ground rules

 * [Ground rules](ground-rules.md)

## Project description 

_My Fun Run_ is an Android virtual themed race app. Allowing the user to track and save their
 routes while utilizing themed race mode options to simulate real life themed runs. This
 ultra-immersive running game will get any user motivated to get running and achieve their goals.
 
 How it works- After a user logs in they will select a race (example: Zombie Run).In this race 
 audio that supports the theme will occur throughout a user's run to encourage and engage them
 while simulating the experience of a live themed run. Users will hear audio prompts during their
 runs as a part of this experience.If a user does not want to utilize a theme they can opt for a 
 timed run option. After choosing the desired race the user will begin their run. Users will be 
 able to track their distance, time, and pace for each run. This saved data can be used to track
 their daily, weekly,and monthly progress. These stats can also be used to compete against other 
 users of the app. Runners will choose a skill level; beginner, intermediate, or advanced. Based
 on their skill level choosing their stats will be grouped accordingly and will be ranked based on
 the distance they ran and their time. This will create ranking for users to see where they stand
 against other app users. Also, runners can choose to comment on other user's runs providing further
 encouragement. Runners will repeat this process for each run they complete and choose to publish 
 for others ranking and others to view. Users can choose not to publish run stats and save for
 private viewing and personal tracking purposes.

## User stories

* Seasoned Runners

    > As an active, competitive runner who is always looking to increase my speed and endurance, I need a convenient way to keep track of my daily runs,
      and see how I measure up to other runners in the community.
	
* Novice/Unmotivated Runners
	
	> As someone relatively new to running, and looking to make it part of my regular exercise routine, I need a fun motivator to help me stay interested and focused,
      and a way for friends and family to offer encouragement.

## External services/sources

  
   * __Google Sing In__ - this allows users an easy login process.

     * https://developers.google.com/android/guides/http-auth

   * __Accelerator__ - this will help the app gather user run stats.
   
     * https://developer.android.com/guide/topics/sensors/sensors_motion

   * __Timer/Clock__ - this will be used to track the length of the user's run.

     * https://developer.android.com/guide/components/intents-common#CreateTimer
     
   * __Media Player__ - this will be used to control playback of audio/video files and streams.
   
     * https://developer.android.com/reference/android/media/MediaPlayer
     
   * __GPS__ - this will allow users to track their distance while running.

     * https://developer.android.com/training/articles/wear-location-detection

   * __Push Notifications__ - this will allow users to stay motivated by receiving notification reminders.
   
     * https://developer.android.com/guide/topics/ui/notifiers/notifications
     
   * __Bluetooth__ - this will allow the user the ability to connect for a hands free experience.
     
     * https://developer.android.com/guide/topics/connectivity/bluetooth

   * __Google Play Store__ - by publishing this app more people will be able to see it.
    
     * https://developer.android.com/distribute/google-play
     * https://developer.android.com/distribute/best-practices/launch/launch-checklist


## Design documentation

   * [Entity-relationship diagram](docs/erd.md)

## [Entity classes](https://github.com/my-fun-run/funrun-service/tree/master/src/main/java/edu/cnm/deepdive/funrun/model/entity)

