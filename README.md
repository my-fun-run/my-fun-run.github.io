# My Fun Run

## Team Roster:

 * Anastasia Hristian - Developer
 * Christie Ryan - Developer
 * Jason Shaner - Developer
 
 Roles : As a team we equally shared responsibilities for development and implementation.   

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
 
## [Overview]()

## Current state 

Currently, we have been able to achieve multiple of our project goals. Our app is able to build and
run. Users can use bottom navigation to move from the Home screen to either view their run histories, 
or select a race or event. At the moment, our Home screen does not provide functions and welcomes 
the user.Our users have the ability to select a race theme, track their run, and store their stats in the 
History.We hvae 2 race options available to choose at this time. Our app stores histories on the 
Android as well as the cloud. Storing locally allows the user to access stats when offline. 
Functionally, the frontend is able to communicate to the backend. This allows users can comment on
each other's races as well as store histories for leaderboard purposes. Our app is hosted in the 
cloud. We also have successfully implemented Google sign-in, authentication and security.
We have tested making and retrieving Race Histories in Postman. We have run our app on two emulators
(Pixel 3A and Pixel 3).
Stretch goals for our project include adding GPS, audio prompts ot users during runs based on theme 
selected, configuring a leaderboard, and adding user goals. 

## User stories

* Race enthusiasts who often compete in multiple runs a year.

    > As an ultra-runner who is always looking to increase my speed and endurance, I need an app to keep track of my daily runs,
      and see how I measure up to other runners in the community.
	
* Someone who is new to running and wants motivation.
	
	> As a runner who lacks motivation, I would love to have an app that provides encouragement and motivation during my runs, to keep me going.
                         
* Runners wgo run regularly but are in need of change to their routine.	

	> As a runner who takes the same route all the time, I would like an app that would give me some new and exciting options, without having to go far from home.
 
 * Runner who is unable to compete in races due to pandemic.          
    > As a runner who competes in fun, themed 5ks and marathons, I would love to be able to still participate in these kinds of runs while observing current restrictions.                                                     


## Design documentation

   * [Wireframe](docs/wireframe.md)
   
   * [Entity-relationship diagram](docs/erd.md)

## [DDL backend](https://github.com/my-fun-run/funrun-service/tree/master/docs/sql)

## [DDL frontend](https://github.com/my-fun-run/my-fun-run-client/tree/master/docs/sql)

## [Rest Controllers/Application Logic](https://github.com/my-fun-run/funrun-service/tree/master/src/main/java/edu/cnm/deepdive/funrun/controller)

## [Outlines of technology stacks](https://github.com/my-fun-run/my-fun-run.github.io/blob/master/docs/technology-stacks.md)

## [Endpoints](https://github.com/my-fun-run/my-fun-run.github.io/blob/master/docs/endpoints.md)

## [User Instructions](https://github.com/my-fun-run/my-fun-run-client/blob/master/docs/basic_user_instructions.md)

## [Build Instructions](https://github.com/my-fun-run/my-fun-run-client/blob/master/docs/build_instructions.md)

## [Copyright/License](https://github.com/my-fun-run/my-fun-run-client/blob/master/docs/Notice.md)

## [Java Docs Frontend]()

## [Java Docs Backend]()






