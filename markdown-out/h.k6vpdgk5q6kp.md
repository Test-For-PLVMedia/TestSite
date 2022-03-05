Live Streaming
==============

Crew Roles
----------

![](images/image40.png)

### Uniforms

The uniform that has been set in place in years past is…

*   black pants or black/khaki shorts that come to your knees
*   along with your PLV Media uniform shirt and or sweatshirt/jacket.

 We want our name/logo to be seen so that we can go wherever we need to without people questioning who we are or if we are where we are supposed to be. It is a really big convenience and also helps people to see who we are and what organization we are a part of and can help with recruitment and getting our name out there. Of course each year, it is up to the production students to determine if they want to keep this uniform as it was or if they want to make any changes to it.

### [Producer](#h.pyglj5jqa01q)

See [\[Producing\]](#h.pyglj5jqa01q).

### Tech Director (TD)

\[TODO\]:

### Switcher

This section is for the role switcher. For actual switcher operation and setup, see \[TODO: Link section in guide\]

\[TODO\]:

### Replay

This role is responsible for setting up the equipment, prepping it for the stream, operating it during the stream, downloading the highlights at the end of the stream, and proper shutdown and storage of the equipment. A specific guide to operation can be found here.

It is critical to remain in clear communication with the TD throughout the stream so that replays can be played in a timely manner (hopefully after each major play in FB).

### GFX/Wirecast

This section is for operation instructions of the software wirecast. For what you need to connect to the wirecast hardware/computer, see either the [MOAC Setup](#h.f2yn2rzgnbzh) or [BOAC Setup](#h.kwhq4y8y0apo) sections. For more technical details or making a new template/title, see [MOAC - Wirecast](#h.cuvnzrlfv5n8).

#### Starting Wirecast & Titler Live

Navigate to the server by opening up File Explorer, going to “This PC” in the sidebar, and choosing the PLV Media (M:) drive. Then, go to Wirecast Files.

You will see either BOAC\_Wirecast or MOAC\_Wirecast. Use the appropriate one by double clicking it.

![](images/image59.png)

![](images/image43.png)

Once it opens, you will see 4 primary layers. They are as follows:

1.  Titler Source. (scores, down, etc.)
2.  Thumbnail/Graphics
3.  PLV Media Logo Bug
4.  Video Input (From Switcher)

You will have to delete everything currently in layer #2 (assuming it was left over from a previous stream), and put in the graphics for whichever stream you happen to be doing. To add new graphics, hover over the layer. A plus button will appear. Click that, and on the leftmost side select “media files.” Double-click “browse disk,” find the graphic(s) you want to insert. And click open.

To show something, click on it. (e.g. Monarchs\_Win.png). To hide it, click the “Clear Layer” button (leftmost side of each layer).

![](images/image7.png)

Initially, it will only go to Preview, the left-hand video stream. To push the Preview view to the Live view, press the ➨○ button.

Now, you have to set up titler. Click on Titler Source in layer #1.

![](images/image52.png)

Something like this should show up on the left-hand side of the screen. (Or, if you have a different looking page, keep reading until it looks familiar.)

![](images/image25.png)

If it looks like this:

![](images/image28.png)

Double click on the arrows >> to open the view panel.

Click on Titler Live Source.

![](images/image19.png)

![](images/image29.png)

Click on the three dots ··· (The rightmost option, as shown selected above)

![](images/image65.png)

Click on the big “Titler Live” button. (It’s thinner on MOAC, but still there).

![](images/image64.png)

Titler should open up. If the title for the game you’re already using is there—rejoice! Otherwise:

![](images/image37.png)

Delete the title currently there (if one exists, there may not). (Right click on the title).

![](images/image20.png)

Right click, select Open… (from disk).

Navigate to The Server -> Wirecast Files -> Titler\_Files, and open the title for the game you’re doing.

![](images/image47.png)

Now, there should be an “attributes” panel that shows up. If you don’t see it, go to the topbar, View -> Attributes.

![](images/image87.png)

Set up all the stuff for your game. (Note: Logos for other teams are most likely in The Server -> Logos -> High Schools -> Class A High Schools)

\[TODO: PLACEHOLDER INSTRUCTIONS - WORK IN PROGRESS\]

While using the Attributes folder is great for changing the colors, team names, and logos, it will NOT be used for streaming during the game.

Instead, you will use the scoreboard tool for whatever sport you are streaming.

To access the scoreboard tool, you go to the top bar and click Inputs-> Sports-> Scoreboard Tool-> \[TODO: Fix This\] (or smth like that IDK IM DOING IT FROM MEMORY SORRY) and then select the sport. For softball, use the baseball option.

If your Inputs button is greyed out, your Titler file is probably live. To take it off live, press the red arrow next to your design in the Playlist area (it will be a white arrow when not live). Then you can access the Inputs panel! Good job! (Note: by saying “live” I dont mean that you are LIVESTREAMING just that Titler is actively sending the source to Wirecast.)

Specific Sport Instructions

Most everything with the scoreboard tool is intuitive, which makes sense considering its whole purpose is to make things easy!!

*   FOOTBALL: \[TODO:\]
*   VOLLEYBALL:
*   SOFTBALL:

If the scoreboard tool isn’t sending information to the actual scoreboard (aka it’s not working)...

*   Cry
*   Go into Edit Title Design, or right click on your design in the playlist. This will open a new Titler window. You cannot be live while you edit your design
*   This is where you edit the makeup of your scoreboards! This is where we created them and add new features, all stuff that we’ll add to the guide eventually. For now, you’ll focus on whats already there.
*   Click on any text/shape that SHOULD be changing when you input things in the scoreboard tool (for example, the home score or the quarter)
*   This will open a little section with a whole lot of settings. You’re going to find the tab that says “Global”
*   In Global, scroll down to the section that says Text Variable. There should be a little box checked. If not, check it.
*   With the box checked, you will be given two option boxes for where the variable is connected to and what its name is. If the one of the left reads “None” then you just found the problem!
*   Click on that option box and scroll down until you find “Scoreboard Tool: \[Sport\]” (Note: it won’t actually say \[Sport\], it’ll be the name of various sports. Choose the one you’re working on. duh)
*   Next click on the righthand option box and scroll until you find the correct output for what text/shape you selected (for example it might say Visitor Score). It might have already done it for you because sometimes the program decides to be smart.
*   All other variable elements should have automatically updated to the new output but just to be sure, check all other elements and make sure they’re sending out to the correct scoreboard tool under the correct name
*   SAVE!!! Clicking the green checkmark will automatically save and exit from the window.
*   If none of that worked…
*   Cry (loudly)

#### Output Settings and Restream.io

Before you start streaming, you need to set up the output settings.

#### Template Requirements

Fall

*   Football

*   Teams, team logos, scores, time-outs, down & distance, ball on, clock, penalty indicator, sponsor logo (on left or right side)

*   Softball

*   Teams, logos, runs, hits, errors, balls, strikes, pitch count,

*   Volleyball

*   Teams, logos, scores, sets, match score, game score, clock (sometimes)

Winter

*   Basketball

*   Teams, logos, scores, quarter, fouls, clock, bonus

*   Wrestling

*   Teams, logos, individual score, weight, period, sponsor logo AND extra scoreboard with just team score (total)

Spring

*   Soccer

*   Teams, logos, scores, half, sponsor logo, pk shootout ( separate thing with dots green for score red for miss/block)

*   Baseball

*   Teams, logos, scores, inning, hits. runs. errors, pitch count sponsor logo

### Camera Operator

\[TODO:\]

### Camera Spotter

\[TODO:\]

### Commentator(s)

#### Pre-Season

*   Pre-season is very important because if done correctly, sets you up for the rest of the season. During this time is when all the research needs to be done; Learn the coaching staff, rosters, expected key players, positions, overall expectations, where seniors are looking/committing for school, etc. This is very easy stuff to talk about on-stream because it is indisputable and nice facts people enjoy to hear. This stuff is not very difficult to do and makes life easier when the season starts.

#### During Season

*   Once the season has begun, it's time to release your inner statistician. Well, stat finder more so. The most reliable place is MaxPreps ([https://www.maxpreps.com](https://www.google.com/url?q=https://www.maxpreps.com&sa=D&source=editors&ust=1646472726664407&usg=AOvVaw3GNqWcikli49AqmSt4wCLm)). Here you can find all the stats for all the sports. On a day-to-day basis it is really important to follow the in-season teams for both schools.

5 CRUCIAL stats for each sport:

Football: Offense - TD, Total yards, Yards per “attempt”, Yards per game, Total points

                   Defense - Total tackles, Tackles per game, Tackles for loss, Sacks Takeaways          (interceptions or fumbles)

        Basketball: Points per game, Assists per game, Rebounds per game, Blocks per game, Steals per game

        Volleyball: Kills, Kills per set, Aces, Service errors, Blocks

#### Post-Season

*   Once the season has ended for a particular sport, there is not really anything that needs to be done, as your attention turns to the next in-season sport.

#### Pre-Stream

*   The first thing that needs to be done once the van is unpacked, is to set up the Commentator mic, mute, and monitor (See pic below). This is very important to get done as soon as possible so you can; help everyone else with stream setup, and more importantly make sure your audio is working and properly leveled, and if not it has plenty of time to get fixed.

#### During Stream

*   During the stream is when you commentate the game. For football/volleyball, you need to play-by-play as the ball is in play. In between snaps/serves, and/or stoppage of play is when you can integrate the stats that you have collected. Basketball is a different story; since the ball is in play much more, you will need to integrate the stats while the ball is live, and not constantly call the play-by-play. This will require you to have more knowledge of your stats and be able to weave them in as they apply.

#### Post-Stream

*   Your job post stream is very simple, you get all of the commentator stuff packed up and put away as soon as the stream has ended. Once your job is done you ask the producer what can be done to help get everything cleaned up and put away.

Producing
---------

\[TODO: Create a general guide for FB, volleyball, SB/BB, wrestling, basketball, soccer, track

Include physical set-up diagram for each location; where to stage and store cases while streaming; order to set up/tear down; things to prepare in advance; packing list (if different for your sport than the usual set up); crew assignment considerations\]

### Creating Live Streams (on Youtube)

\[TODO:\]

### Football

These are probably the most extravagant streams we do based on the time involved, the size of crew needed and that kind of stuff, but I would also argue that these are the funnest streams!

#### Note: (& this goes for producing ANY stream)

The first (and possibly most important) thing to note when you are going to produce football games (or any live streams) is that problems are going to come up and that’s ok. No one expects you to be perfect. Now I know this is a manual and this isn’t really an instruction but it is important as a producer to know that every stream is not going to be perfect. It’d be great if it was but that is not realistic, and that’s ok. What is important is how you handle the situation and adapt to the problems that may arise. But in the end make sure you have fun, that’s what this academy is about and if you as the producer aren’t having a good time then that will affect you and your team as well. Trust yourself, and enjoy it.

#### Crew

Training crew takes place at the scrimmage games that both high schools have. This is a great time to have as close to a game experience without all of the pressure of being live and having an actual audience. It also helps you and your crew feel more comfortable about the upcoming season and streams. What we have done in the past is break up the studies kids into groups with a production member leading them around. Take them down onto the field to show them where the roaming cam will be at (if it is used), go up in the press box onto both decks and the booth so that they can get a more general idea of where things are and how set up should look. This night is also a great time to start building relationships between production and studies kids. We all remember what it was like to be in their position and have no idea what to do or what to expect, so building those relationships early on can help bring your crew together and make the year go by a lot smoother and a lot more fun.

There are 13 positions to fill at a football stream, including you as the producer. You can use this [crew assignment sheet](https://www.google.com/url?q=https://docs.google.com/document/d/1doFWHWDPeLHgkT0VobISPC9Nunav_cPnoaojwMRd-mc/edit?usp%3Dsharing&sa=D&source=editors&ust=1646472726667173&usg=AOvVaw36yhNDsrRtd0P0Rv4elsm2) to fill out everyone's positions for the game. Those positions are cams 1-5 (and 2 spotters for roaming cam), wirecast/gfx, spotter for GFX and video board, director, switcher, replay, and then producer of course (14/15 if you include commentator(s)). It is important to know everyone on your crew to be able to fit them with the right jobs to help the stream run as smoothly as possible. It is also important as the season goes on, to train people in different positions so that you don’t have only one person who knows how to do replay. Because if they are gone you don’t want to have to be calling them to fix stuff for you. You will also want to switch people around during the game that way they aren’t doing the same thing for the entire game. Makes the time go by a little faster for everyone and is more fun.

When considering who to put in what positions, you have to think about a couple of things...

#### Pre-Stream

The very very very first thing to do when producing a stream is [create the video](#h.28ysxkdyzh6q) on the PLV Media YouTube page so that when you go into restream.io later the video is already made and you just have to click on it. This can be done as soon as you find out that you are producing, then you don’t have to worry about forgetting it later. Before you head over to the stadium you also have to make the [crew assignment sheet](https://www.google.com/url?q=https://docs.google.com/document/d/1doFWHWDPeLHgkT0VobISPC9Nunav_cPnoaojwMRd-mc/edit?usp%3Dsharing&sa=D&source=editors&ust=1646472726667790&usg=AOvVaw3qkChaUlfXNqxGlxCCO6si). It’s best to do this on the day of the stream because you might have some cancellations or some switching around of people working so I wouldn’t recommend doing it until the day of. I would recommend doing it the day of in class. When you get to the stadium you can tape this paper up on the PLV Media booth door that way everyone can see the jobs they will be doing during the stream. Another thing you will want to do before you leave the school is get in contact with the video board producer and ask them to print you off a script. This script has everything that is happening and at what times for the entire night. This is extremely useful during the stream and can help you know if there is stuff added during pre-game or halftime like homecoming court, or senior night, for example. This information also helps you know when you will need to start the stream.

Something else you need to do before the stream is ask your gfx designer to make some gfx for the game. You’ll want a thumbnail to put up at the beginning of the stream, a halftime gfx, and a “\_\_\_ wins” for each team since you can’t predict the future and know which team you will need it for. Please please please ask the gfx designers well in advance that way they don’t have to rush and get things done, like 3-4 days ahead of time. It’s just common courtesy.  You’ll also want some kind of lower third gfx for the dance team, NJROTC, P-Town twirlers, and the band so that you can put those up when they are performing and on the field. These can be generic though for each school and used at each game instead of making a new one each time. There are some made in the Other folder that you can use or you can make new ones instead, it’s up to you. When they have made the gfx you’ll want to put them in the StreamGFX-->Football (and then you can make subfolders here for each individual game) folder on the PLV Media server. I highly recommend putting everything you need for the stream in that folder. That way when you get to the stadium everything you need is in one spot and you don’t have to go searching for it.

So before you leave the media room...

1.  Make the stream on YouTube
2.  Ask your gfx designer to make the gfx for the game (Make sure that they actually get done, because people are busy and mistakes happen so double check that they are done. Don’t just assume that they are, because if they aren’t done it’s easier to fix before you leave the school.)
3.  Fill out the crew assignment sheet
4.  Make sure all of your crew is there and in [uniform](#h.7iv8dy6ci56v).
5.  Print off the script (that you get from the video board producer) and remember to take it with you
6.  This is also a good time to figure out ride situations just so that you know who’s riding with who and can make sure everyone is getting over to the stadium together
7.  Then load up a flatbed and to the van!

Before you even go over to the stadium you have to load EVERYTHING up on the flat beds, load them into the van, and then you can drive over to the stadium to unload and carry everything up into the press box. You’ll want to pack everything during your class period (if okay with Hoch, of course) that way after school all you have to do is load it in the van. Things to pack include camera cases (inside each camera case is the camera, camera power cord which is two pieces, remote, and should be a rain coat for the camera incase it happens to rain during a stream-take these just incase with Nebraska weather you never know), monitor case, toolbox, radios, headphones/earpieces, monitors (which only need to be taken out once because they can stay in the storage closet from week to week instead of being taken back and forth), switcher, casket (the storage container that hold all of the tripods and cords), gaff tape (it’s nice to keep some of this in the PLV Media booth and a roll in the casket, you’ll always need it and for some reason it always seems to go missing), … Then once everything is loaded up you can make your way over to the stadium!

You’ll first want everyone to start setting up cameras, the reason being you want to be able to get them up and running and into MOAC so that way you can troubleshoot any problems before the game starts. Then once people are on that the commentators get their area ready and the rest can help set up in the booth. Setting up in the booth is really more about getting programs up and running and not as much physical set-up (since that room is ours, and we can lock it, we can keep monitors and MOAC up in the booth all season-unless otherwise needed of course). After people are done setting up cameras, radios need to be put together and ready to go. You’ll also need to set up the sideline camera. Once commentators are done setting up you also need to check their audio. The main theme before the stream is to be on top of things. You don’t want to be rushing around as the game is starting trying to fix all of these issues that more than likely could have been avoided if it was checked beforehand.

It’s also important to talk to your crew before the stream starts about what you are looking for and make sure that everyone is on the same page. As the producer you should have an idea of what you want the stream to look like and what the cameras should be doing, etc. Remember: people can’t read your mind so if you want cam 2 to get on the referee whenever he is saying the penalty, then you need to tell the camera people that. Communicate with your team and it will benefit everyone.

If everything is ready to go, you’ve checked everything and it’s all good then the rest of the time until the game is up to you. Free time to get to know everyone and this is also the time to get food/eat. Make sure that everyone is back and ready to go about 15-20 minutes before the game starts though. This seems like a lot of time still but this gives people a little bit of wiggle room in case someone is running late or what not, that way if they are late they technically “aren’t late”, if that makes sense. This time is also good to go to the bathroom that way you don’t have to during the game. Then about 5 minutes before the stream starts, tell everyone to grab their radios (which should already be set up), and get to their positions.

#### Set Up

There are 6 main locations you should be familiar with…![](images/image15.png)

The 5 locations for cameras and the PLV Media booth. This is where you will be spending your time: in the press box and on the field. It’s important to be familiar with these locations so you know where everything is for set up and storage, etc. Make sure your team also is familiar with the space so that they feel more comfortable.

#### Starting the Stream

(For technical reference, use [Wirecast operating](#h.8f6jnighke35)).

At football games you will want to start the stream before ROTC goes out on the feild and the national anthem is played. This typically happens about 8 minutes before the game starts (and usually all games start at 7pm so you’re looking at about 6:52pm). You’ll want to probably start it at about 6:50 so that way you can have the thumbnail up to begin with. Any other gfx or videos that need to be played before the game also need to be figured in when trying to decide when to start the stream so it’s important to have a script from the video board producer and keep it with you so that you know the schedule for the night. But typically for regular games, with no other events, the stream should be started around 6:50. You’ll want to make sure that you press record on the MOAC so that we can use this footage later on for different things, then tell the tech director to start the stream, who will tell the wirecast operator to press the “go live” button (not the technical name but you get the jist). That should light up green, I believe, to know that you are streaming live to whatever platforms you are going to (we do Facebook and YouTube for our streams) and you should be all set. There is more information on how to set up to start the live stream under [Wirecast operating](#h.8f6jnighke35). Then you can just check on your phone and go on YouTube to make sure the stream is up and running!

#### During Stream

Like I said before the very first thing to do when the stream starts is [press record](#h.ltn5gr4fhuiq) on the MOAC! If you don’t do this then you have basically failed your job as producer. No pressure :)

Other than that the producer’s job during the stream is pretty much a need to do basis. You become the problem solver during the stream and run around fixing whatever problems come up. If there aren’t any problems then you get to sit back and relax for a little bit, until something does come up. It’s ok to walk around and make sure everyone is doing ok during the stream, don’t feel like you have to stay in the booth the whole time. In fact, I recommend walking around if there are no pressing matters; that way you actually see how things are going. This is a good time to drop compliments to crew members and ask if they need a break or drink (especially when it’s hot). Now this part of the job sounds easy, but it might actually be one of the most challenging (not to scare you or anything). The reason I say this is the hardest is because you can’t know what is going to come up during the stream. No matter how much you prepare, something is going to come up, but what’s important is how you handle those situations.

#### Half Time

Even though the players on the feild get a break at this time, you and your crew don’t get a break just yet. Sideline cam, and the spotters can come back up if you want them to but the dance team and the band (and sometimes the P-Town twirlers) have their half time performances that need to be filmed. So make sure you radio to your crew letting them know about 2 minutes before half and at the beginning of half time, reminding them to stay in their spots and continue to do what they are doing. Then when they are done you can put up the halftime gfx, and let your crew know they have \_\_\_ amount of time to get a drink, go to the bathroom, do whatever they need to do before the second half starts. Once again give them a time to be back, probably at about 5 minutes left till the 3rd quarter they should be going to their spots.

#### Post-Stream

When the stream is about to end make sure that the commentators finish talking before you end the stream! Last thing you want is to end the stream in the middle of a sentence. Once they stop talking then you can end the stream and stop recording on the MOAC. After the stream is ended let all of your crew know that they can start tearing down. Also need to export all of the replays, I recommend doing this as soon as possible because it can take a LONG time and no one wants to be waiting around for those to finish exporting when they could be heading to their nice warm beds to sleep. Get everything packed up, and loaded into the van (remind Hoch to go move the van before the game is over). Make sure you take out the garbage from each of the decks and the two booths that we use (PLV Media booth and announcer’s booth) and then put in new garbage bags. It’s just important to leave everything better than you found it, which includes the van, the gyms, the stadium, the studio, the media room, etc. You get the jist.

At the end of every stream, after everything is packed up, driven back over to PLHS and put back in the media room (you can just put everything in the room, the only thing that should be put away before you go home that night is someone should put the radios back on the charger) it is the producer's job to do a break-down and talk about the stream. Talk about what went well, what could be better, and I also suggest giving some individual feedback because in the end our goal is to be better than we were the last time and we can only do that by reflecting on ourselves. Also ask if there is any feedback for you because 1. You are no better than anyone else even though you have the title of producer and 2. You can always improve as well. Then after that is done make sure you thank everyone for helping make the stream possible and go home!

\*\*I would also recommend writing down what went well and what to fix because, once again, we want to get better and produce the best quality stuff that we can. We can’t do that without taking the time to evaluate what we have done. Plus, once you write down what happened and can see it you can use that as a checklist to help at the next stream so that you make sure you don’t make the same mistakes again. You can use a checklist on your phone so that you have it with you at every single stream and can look at it. Now this is not required at all, but I believe that it is very beneficial to anyone wanting to improve their work and performance (and overall leadership).

#### Common Issues/Troubleshooting

It’s hard to prepare for all of the issues that are going to come up at every stream because it is very unpredictable. There are some things that you can try and prepare for though so here is my advice:

1.  Camera isn’t showing up in switcher

1.  This has been a common issue in the past at the stadium with the cameras on each outside deck. The problem was that the SDI wall connectors were bad so the cameras weren’t showing up or they were flashing in and out, which are both bad. There are a few things you can try. First, make sure that everything is connected to what it is supposed to and follow each and every cord to make sure each connection is tight and connected to what it should be. Worst case scenario you might have to scratch the wall connections and run a direct line from the camera on the deck to MOAC. It’s a lot more work but sometimes it's necessary. Hopefully you won’t have to deal with that though. Crossing my fingers for you :)

### Volleyball

Here you can find the [Crew Assignment Sheet](https://www.google.com/url?q=https://docs.google.com/document/d/1KwPFzB1ac6aaYzyDot6F9RrFF7cib5i35WttLQYmalA/edit?usp%3Dsharing&sa=D&source=editors&ust=1646472726671956&usg=AOvVaw3LBhQl6P0ZxewH3dNVg6Dn). The producer will want to use this form preferably before the stream to place your crew in positions you want them to be in. Here you can see the camera layout used at Volleyball streams.

![](images/image8.png)

#### PLHS

Streams at PLHS are a lot easier than streams at PLSHS because it’s in our school. During class we load up a flatbed that is outside of the classroom. Then, at the end of the school day, when everything and everyone is ready, we bring the equipment directly from our classroom to the North Gym.

Just like at every other stream the first thing to get set up is the cameras and then have one person (usually producer but doesn’t have to be) setting up moac (or boac) in the South entrance under the crows nest. Keep the bags and casket on the West side of the doors and set moac up on the east side. The reason we set it up with moac on this side (closer to cam 4 for reference in the graphic above) is because the wall ports are located back behind on this side so if we set up MOAC over here then we don’t have to worry about cords going across the walkway and trying to cover them up so that people don’t trip. Really it's for convenience, just easier that way.

#### PLSHS

Streams at PLSHS are a tad bit more difficult because we have to be more prompt. During class periods we gather our equipment on the flatbed which should be brought to the room, then when we have everything and everyone ready, we bring the equipment outside to load the van. Students who don’t drive or don’t get a ride get to ride in the van with Hoch (an experience that you should do at least once).

#### Crew

Unfortunately, there aren't any specific streams where people are trained during volleyball, however, we can bring an extra person or two to each stream so they can shadow more intensive positions like switcher, gfx, etc. At volleyball streams, there are 11 positions (excluding a second commentator). Producer, 4 Cameras, Director, Graphics, Tech Director (TD), Replay, and Commentator(s). Refer to the [Crew Roles](#h.shjmzttdcvd7) graphic for position directions. As long as each role is performed correctly, volleyball streams typically are easy and run very smoothly. As the season progresses, it is important to train people in different positions so that, for example, not only one person knows how to use the switcher. Also, for each set of the game, it is important to move positions around. Although you will always be the producer and the director will typically be the same person throughout the stream, you should change who is working what camera and who is working graphics, switcher, etc. In between sets you would call on the radio for everyone to switch in the little bit of down time we are given. MAKE SURE everyone arrives at where they are supposed to be.

#### Pre-Stream

The first step to producing a stream is to [create the video](#h.28ysxkdyzh6q) on the PLVMedia YouTube page so that when you go into restream.io later the video is already made and you just have to simply click on it. This can be done as soon as you find out that you are producing that way you don’t forget about it and you don’t have to worry about it down the long road. Before you head to either gym, you should also make sure that your c[rew assignment sheet](https://www.google.com/url?q=https://docs.google.com/document/d/1KwPFzB1ac6aaYzyDot6F9RrFF7cib5i35WttLQYmalA/edit?usp%3Dsharing&sa=D&source=editors&ust=1646472726673209&usg=AOvVaw3tNasXXFN50maErakIvRgB) is complete. It’s best to do this the day of the stream because you might have some cancellations or no-shows. When you get to either gym, it’s important to tape the crew sheet on the door/wall to insure that everyone knows what role they are doing.Unlike football there is no script for the streams so just keep in touch with the ADs from whatever school you are streaming and at and make sure you know what the night is going to look like and if there are any extra events going on that you need to be aware of.

Another important thing to do prior to the stream is ask your GFX to make some GFX for the game. You’ll want a thumbnail to put up at the beginning of the steam and a “\_\_\_ wins” for each team since you can’t predict the future and know which team you will need it for. Please ask the GFX designers WELL in advance that way they don’t have to rush some kind of lower third GFX for the dance team, NJROTC, P-Town twirlers, and the band so that you can put those up when they are performing. These can be generic though for each school and used at each game instead of making a new one each time (can also be used between sports so you could use the same one from football for volleyball, basketball and so on-it is nice though to have one for fall then winter and then spring so that it spices things up throughout the year). There are some made in the “Other” folder that you can use or you can make new ones instead. When they have made the GFX you’ll want to put them in the “StreamGFX → Volleyball” (and you can make subfolders in here for each individual game) folder on the PLVMedia server. I highly recommend putting everything you need for that specific stream in that folder that way when you get to either gym everything you need is in one spot.

Before you leave the media room…

1.  Make the stream on YouTube
2.  Ask your GFX designer to make the GFX for the game (Make sure to check up on them and make sure they are actually done. Don’t just assume they are, because it is much easier to fix in our classroom)
3.  Fill out the crew assignment sheet
4.  Make sure all of your crew is present and in uniform
5.  If the VB game is at our school we won’t need rides, however if the game is at PLSHS this is the time that we find out the rides to PLSHS

### Softball/Baseball

[Crew Assignment Sheet](https://www.google.com/url?q=https://docs.google.com/document/d/1gPG4AFki0ssJHI9MhOP8klkdrgd5Wa1i66EmhQX8kxA/edit?usp%3Dsharing&sa=D&source=editors&ust=1646472726674284&usg=AOvVaw3ZTQuPe55WKAKHgsKbGufa)

### Wrestling

[Crew Assignment Sheet](https://www.google.com/url?q=https://docs.google.com/document/d/1a8qDUdq3y2Tgs3FWA8-WsPq5a-5lRTwlKueM0oEMIgo/edit?usp%3Dsharing&sa=D&source=editors&ust=1646472726674685&usg=AOvVaw16y42hbuK2_b5UzPbBb81m)

### Basketball

Here you will find the [Crew Assignment Sheet](https://www.google.com/url?q=https://docs.google.com/document/u/0/d/1opHl4_Pg-mzkFVkZtpBTP7JhI_6APcSMh_SkWdnUWWs/edit&sa=D&source=editors&ust=1646472726675005&usg=AOvVaw0elIFBP8WR0zHBN7LmS1TI). The producer should fill this out the day of the stream but before you actually head to the gym at either high school. Here you can see the camera layout used at basketball streams.

![](images/image5.png)

#### PLHS

This stream is a little bit simpler because you’ll still want to load all of the equipment up on flatbeds but you only have to roll it down to the gym, which saves a lot of time and energy. You’ll want to take it to the…

#### PLSHS

### Soccer

[Crew Assignment Sheet](https://www.google.com/url?q=https://docs.google.com/document/d/1XwWXFy_VFyCDwVoZLf0vOkuWeFHY6aVbrW2vQDeOvIg/edit?usp%3Dsharing&sa=D&source=editors&ust=1646472726675587&usg=AOvVaw1sVqE_13gnXzdiizKWmPi6) 

### Track

[Crew Assignment Sheet](https://www.google.com/url?q=https://docs.google.com/document/d/1DsMBsv5-B1dQzAPtO5g7waqcwMMhHn0DdjrJrzojwgU/edit?usp%3Dsharing&sa=D&source=editors&ust=1646472726675912&usg=AOvVaw3onnLPecccFaU0i1-o_sNV) 

There are actually two crews going on for track streams. There is the EDITING side and then the STREAM side.

* * *

BOAC (Baby of all Cases)
------------------------

BOAC, the MOAC’s little brother, powers streams that don’t need (or can’t have) the full MOAC. It lacks a replay machine, a hub, an external switcher (though you could theoretically use it), and some of the niceties of the MOAC. It is, however, still a powerful machine, and you can easily produce a great stream with it nonetheless.

### Setting up During a Stream

\[TODO: Pictures\]

1.  Take off the front and back panels.
2.  Find the power plug for Wirecast (already connected in the case), and plug it in. It should be labeled TO WIRECAST on the plug.
3.  Plug in wirecast monitor and peripherals (mouse, keyboard). Don’t forget monitor power.
4.  Plug in the barrel plug (power) for the switcher. It should be hanging just below its port, we unplug it so it doesn’t get crushed when we close the case.
5.  Find the UPS power plug in the back, and plug it into a surge strip. It should be labeled TO WALL on the plug.
6.  On the UPS (front side, bottom), open up the little clear plastic cover and press the power button. This turns BOAC on.
7.  If it doesn’t start up with the UPS, turn Wirecast on (open up the front panel, flip the black switch).
8.  Plug wall ethernet into the WAN1 port on the network switch.
9.  Plug in ethernet for Wirecast, Switcher, and the Laptop.

1.  The cables for this should already be connected to the network switch. Simply find the loose ethernet ends and plug them into wirecast/switcher.

10.  Connect the PROG SDI BNC port on the switcher (right side) to the Wirecast input BNC port (wirecast only has one BNC port, it’s that one).
11.  Plug cameras into Switcher (left side, read labels).
12.  Reference [Wirecast operating](#h.8f6jnighke35) for Wirecast software setup.
13.  Operate Switcher on laptop \[TODO: Link to section\]

#### Tearing Down

Tearing down is effectively the same as setting up but in reverse, but please keep in mind that:

1.  You must unplug the power for:

1.  Switcher
2.  Wirecast (after shutting down properly from software or front panel)

2.  You must disconnect the program SDI going between Switcher and Wirecast
3.  You must disconnect ethernet for Wirecast

We do this so that the back case does not crush these connections when we close it.

### General Layout and Case Setup

![](images/image26.png)![](images/image63.png)

![](images/image80.png)

Above you can see the internal connection layout of the BOAC. See [Connections](#h.cmf4ipk4m8bg) for more information on what you need to connect.

### Connections

To get the BOAC up and running, you will need to connect:

*   Network (detailed above in [Setting up During a Stream](#h.x8s3v51tqysz))
*   Cameras to Switcher
*   Power to Wirecast (we unplug this because it doesn’t fit in the case).
*   Switcher PROG OUT to Hyperdeck (this is the light blue cable coming from the top)
*   Switcher PROG OUT to Wirecast SDI In

### Switcher - ATEM TV Studio

Everything is effectively the same as the [MOAC](#h.o4vwz0fr8yte), just instead of using the physical switcher control surface you use the virtual one on the laptop.

* * *

MOAC (Mother of all Cases)
--------------------------

The MOAC is the heart of a stream. It handles pretty much everything, and it’s a complex beast. It’s important to get comfortable working in and around the MOAC, as you’ll be using it a lot.

### General Layout and Case Setup

![](images/image78.png)

Going from top to bottom, the MOAC is made up of:

*   {Top Shelf}

*   Computer Patch Panel (HDMI, USB, etc.)
*   Power Bar
*   [Hyperdeck](#h.ykr8z6k1c2lx)

*   [The Hub](#h.4lkofo2glp7a)
*   [X32](#h.nljzdzixaid2)
*   [Wirecast (+ Graphics)](#h.cuvnzrlfv5n8)
*   [Network Switch](#h.abe6w33jta81)
*   [Replay](#h.yd6xqnrnyxmd)
*   Drawer
*   [UPS (Uninterruptible Power Supply)](#h.ffw26c5wsu6u)

On the backside, all you need to worry about are the [patch panels](#h.vsalxlvegdls). ![](images/image41.png)

The top patch panel (CAM1 through RPLY) is the “Camera Output” patch panel. This is the patch panel you use to get video OUT to the switcher. \[aka “Output Patch Panel”\]

The middle patch panel is the “Camera Input,” it also handles switcher program input \[aka “Input Patch Panel”\]. THIS IS THE ONE YOU PLUG CAMERAS INTO!

The bottom patch panel is the Audio Input \[aka “Audio Patch Panel”\]. This gets plugged into the commentator’s cable snake.

Peripheral to the MOAC, you have:

*   Monitors (3x)

*   2x Wirecast
*   1x Replay
*   1x Switcher multiview

*   Replay Control Surface
*   The Switcher (Control Surface)
*   Switcher Laptop (plus power cord and ethernet dongle)
*   Various keyboards & mice (2x each, one for replay and one for wirecast/graphics)

### Still-In-Room Testing - Checklist

It’s good practice to test that the MOAC is fully functional before taking it out to the stream site.

A good checklist is:

*   Does the UPS turn on without complaints?
*   Can you connect to every display?

*   Wirecast (+Graphics), Replay, Switcher Multicam

*   Is every connection on the patch panel solid? Can you get every camera to show up on multicam?
*   Are you getting the PROG IN video signal in wirecast?
*   Can you create a replay file? Does the replay surface work?

*   Can you see replay on switcher multiview?
*   Can you get every camera in?

*   Can you connect to the internet?

### Setting Up In Practice

#### Setting up monitors and stands

Take off the top panel first, and set it to the side. Unclip the side panels. If you’re at the gym, set them up as tables on the side of the MOAC, using the built-in ‘hooks’ (make sure to lock the legs). If you’re at Foundation Field, just put up one of the side panels and put the other away.

It’s up to the stream producer how they want to set it up, but effectively just ensure that you have the 2x Wirecast, 1x Replay, and 1x Switcher monitors set up in a way where replay can easily communicate with both when they plan to play their clips, and where you can easily get power and all required cables to them.

#### Cables and Connections

In total, you need to wire up:

*   UPS

*   It’s the main power cable coming out the back of the MOAC. Plug it into the wall.

*   [Network](#h.abe6w33jta81) (Link to images and further explanation)

*   Taking the building’s ethernet from a wall, plug it into the WAN1 port on the front.

*   Wirecast

*   HDMI Connections are on the computer patch panel, marked in yellow as “WC”
*   USB (mouse and keyboard) are marked on the computer patch panel.
*   All video connections are handled through the hub. No setup or work needed.

*   Replay

*   HDMI Connections are on the computer patch panel, marked in yellow as “RPLY”
*   USB (mouse and keyboard) are marked on the computer patch panel.
*   The Control Surface also plugs in through USB. (This handles power & data)
*   All video connections are handled through the hub. No setup or work needed.

*   Switcher

*   The control surface uses the same cord as monitors do for power.
*   HDMI is onboard the control surface, plug it directly into the monitor.
*   Use the SDI coming from the [output patch panel](#id.xptcmhybmajf) to plug in cameras.
*   Switcher control surface’s Program Out goes to the input patch panel’s “SW IN”

*   [X32](#h.ivey1as9f8k0) (Audio, click link for detailed setup)

*   Connect audio to the back of the MOAC, using the audio patch panel.

You’ll also need to [turn on the UPS](#h.2mbwo6xyei1e).

Once everything is plugged in, ensure that everything else (replay, wirecast, X32) is turned on. If something isn’t turned on in the MOAC, open up its front panel and flip the power switch.

(More Below, the picture is just giant and throws off formatting)

![](images/image34.png)

#### Getting the Computers Working

Mainly, you’ve got:

*   Switcher + Laptop

*   [Load in the Configuration](#h.3q602jvfu35) (if needed—in some cases you won’t have to do this)

*   Only do this if you are using a special replay animation (which you should be doing at most sports matches)

*   Wirecast

*   [Wirecast Setup](#h.8f6jnighke35)
*   [Restream.io and output settings](#h.j437p4c5qafw)
*   [Titler setup](#h.ov0048n65p0j)

*   Replay

*   [Setting up Replay](#h.zbgg8gpatkar)

*   HyperDeck

*   [Start Recording](#h.ltn5gr4fhuiq)

### Patch Panels

![](images/image41.png)

The patch panels are your main camera and audio interface for the MOAC. All of the ins and outs are labeled, so it shouldn’t be too difficult to find what you’re looking for.

As shown above, we have the “output patch panel” on TOP—this goes to the switcher and out to the commentators/other switcher monitors, and that’s it. (Don’t worry about switcher into wirecast—that’s taken care of.)

The middle patch panel is the input patch panel.

Camera inputs should go into the CAM inputs, and the switcher’s final program output goes to SW IN. Make sure you plug switcher output into the SW IN port on the right!

The final patch panel is the Audio Patch panel. This plugs into the commentator's cable snake.

### Network Switch & Access Point

#### Stream Setup

This is super easy to set up during a stream. Simply plug wall ethernet into WAN1, as shown below.

![](images/image60.jpg)

And you’re done.

If you need to connect the switcher laptop, just use one of the three ports on the right (but don’t use the port labeled CONS).

### Hyperdeck

#### Start a Recording

Make sure an SSD is connected. The record button is the circle in the top-middleish. Press it, and you’re good to go.

### The Hub

The HUB is the control center for the MOAC’s video signals. It handles routing all of the cameras into where they need to go in an easy-to-use manner.

#### Using the Software Interface

\[TODO:\]

#### Using the Hardware Interface

\[TODO:\]

### X32 Audio Rack

#### Setup

First, you have to set up the commentator mics. Find:

*   The two headsets
*   The two power mutes (plus their power bricks)
*   The cable snake
*   The audio splitter cable (XLR -> Aux)

Then:

*   Plug power into the audio mutes
*   Plug the headsets into each power mute
*   Using XLR cables, take the direct out ports from the power mutes and plug them into ports 1 and 2 on the cable snake
*   Ensure the power mutes are turned on (switch on back).

To get talkback to work:

*   Take the cable splitter’s XLR end and plug it into port A on the cable snake (port A has pins instead of holes)
*   Plug either aux end of the cable splitter into each of the headsets’ aux cables.

Now, route the end of the cable snake to the back of MOAC.

Find:

*   Black cables 1 and 2 (labeled on the end of the XLR)
*   Red cable A

Plug black cables 1 and 2 into COM1 and COM2 on the back of MOAC ([audio patch panel](#h.vsalxlvegdls)), respectively. Plug red cable A into TLKBK.

Now, you must connect the X32 to the switcher. Using two XLR cables (not the cable snake), connect SW L and SW R from the audio patch panel to the switcher’s Analog Audio In 1 & 2, in the back.

You should now be getting commentator audio in Wirecast (assuming that switcher video is being properly sent).

#### Adjusting Audio Level

For COMMENTATORS:

*   On the x32 rack, use the top-left jog wheel to select the channel. (Channel mappings are labeled further to the top left)
*   Use the fader (the jog wheel below the channel select one) to increase/decrease audio level

For Ambient:

*   If you’re using ambient into x32, see above. If you’re using a camera for ambient, ensure that the camera being used has “ON” on the switcher for audio, and adjust the relevant jog wheel ON SWITCHER. See [switcher audio](#h.ulhkbm2a5xk5) for more information.

### Wirecast

Back when Wirecast got its name, that’s all we used it for—the program Wirecast. Now, even though we still call the physical box “Wirecast,” it has multiple purposes.

You can find instructions for TitlerLive [here](#h.ov0048n65p0j), and miscellaneous YouTube things [here](#h.7wmrx0npljrh).

Restream.io is included in this section.

This section is on creating templates, setting stuff up, etc.—technical details. For a regular stream, reference [Wirecast operating](#h.8f6jnighke35).

#### Restream.io

\[TODO:\]

#### Scene Setup

\[TODO:\]

### Titler

While physically a part of Wirecast, TitlerLive is a beast of its own.

*   Scoreboard

*   Edit title design
*   Creating a scoreboard
*   Troubleshooting in titler

*   Scoreboard Controller

### Switcher (ATEM TV Studio Pro 4K)

If you want operational instruction, skip to the [operating](#h.a0o793m13mrk) section. These beginning sections deal primarily with configuration. I recommend taking a look at the [loading](#h.3q602jvfu35) instructions first though, so that you can load in the correct settings.

#### Network setup and configuration

To connect ATEM setup to the switcher for configuring network settings, use a [USB 2.0 A to B](#h.9zerk3otrabg) cable. You can then launch ATEM Setup, click on the switcher, and set network parameters (as well as device name).

As of December 2020, the network settings should be:

*   IP Address: 10.11.8.203
*   Subnet Mask: 255.255.255.0
*   Gateway: 10.11.8.254

Then, with the laptop also on the PLCS Secure network, you can launch ATEM Software Control and input the same IP Address set above to access the device.

You can also configure this from the control surface menu by going to the settings tab. (Menu button on top left, scroll using the wheel next to the screen, click “set” to select the settings tab, then scroll down to the bottom of the menu.)

[Video Example.](https://www.google.com/url?q=https://youtu.be/5j-ljKuCL10&sa=D&source=editors&ust=1646472726693899&usg=AOvVaw3_q-Okh8fG2Sj9yJON5HzF)

#### Loading and Saving Switcher Configuration

Most of the time, you only need to do this if you are planning on using a game-specific replay graphic. If you aren’t, you can likely ignore this and move on with other setup.

To load a configuration, first, ensure you are connected both to the [switcher](#h.5gur8847nmep) and to the server. Go to the menu bar, select “File -> Restore” and navigate to the Switcher folder in the server. Click on one of the setup folders (i.e. Basketball, Volleyball, etc.), click on the .xml file, and click Restore.

Path: (PLV Media -> Switcher -> \[Game\] -> example.xml)

NOTE: It may take a few minutes for all media files to fully load. Be patient!

[Video example of loading](https://www.google.com/url?q=https://youtu.be/YUu5kEANvd4&sa=D&source=editors&ust=1646472726694901&usg=AOvVaw0pmYhVq8w254yQAzRwYhxA)

To save, simply click “File -> Save As,” and select the location to save it in. You will be presented with options of what to save, and unless if you have a specific purpose for doing otherwise, just make sure all are selected. I would recommend removing old configuration files to avoid confusion, but it is up to you what is best in your situation (at the very least, store new configurations in a sub-folder). It will take a minute or two to save.

(In the current version, as of December 2020, it will show 1% completion almost the entire time—don’t worry about that bug.)

#### Configuring Switcher Multiview & Routing

In the bottom left of the ATEM Software Control panel, there’s a settings gear. Clicking on that, the main menus you care about are MultiView and Labels.

A good default setup is:

![](images/image51.png)

![](images/image81.png)

The Input number is the # SDI on the back, and the label is what will show up in multiview.

On the multiview screen, you can select the audio bars button to toggle on/off showing the audio coming from the camera (or the master audio track on program), as well as some guide lines in the preview.

(Remember, you have to click save before any changes appear in the labels menu.)

#### Creating and Using Macros

In ATEM Software Control, open the macro menu from the top bar![](images/image9.png)

In the window that appears, use the plus button to add a new macro. Name it, and it will begin recording.

To record a macro, simply perform the actions you wish for it to do, and then end the recording. Keep in mind, everything you do will happen immediately after the previous action, unless you manually add a pause. To add a pause, click the red “Add Pause” button in the top-middle of the switcher area—it may be hidden behind the macro panel!

![](images/image13.png)

The pause time is measured in \[seconds\]:\[frames\], or you can select a user wait—however if you plan to run the macro from the switcher surface and not the Software Control, I wouldn’t recommend using the “user wait” setting (Citation Needed, I just haven’t been able to find a way to advance past a User Wait on the switcher control surface). If you need functionality of this type, use two seperate macros, one being the first part of the sequence and the other being the following. (Or just use the laptop. Depends on your setup.)

#### Advanced - Editing Macros After Creation

You should be particularly computer-literate, and preferably know XML, before attempting this.

To edit a macro, we have to edit our configuration file as a whole. First, [save](#h.3q602jvfu35) the configuration somewhere, and then locate it. Open it with any text editor, and find the heading <MacroPool>. It is beyond the scope of this project to detail the syntax, but the most common thing to change is time delays, and so the line for that is:

<Op id="MacroSleep" frames="\[NUMBER OF FRAMES\]"/>

You can add this in or edit the frame number at leisure. For more advanced xml editing, you can find some community documentation [here](https://www.google.com/url?q=https://github.com/imorrish/ATEMConfigSnippets&sa=D&source=editors&ust=1646472726697029&usg=AOvVaw1XSlp0UWf2-Ic7cOMevuJF).

Once you [load the config back in](#h.3q602jvfu35), your macro will be edited.

#### Troubleshooting

\[TODO:\]

#### Operation

[\[Playlist with all operation video examples\]](https://www.google.com/url?q=https://www.youtube.com/playlist?list%3DPLDdTRHGk2-VHekl2vE2OTNvZ2PZ_qt7cS&sa=D&source=editors&ust=1646472726697670&usg=AOvVaw1nZtKPZI90RIPjxrAxVlOd)

First, ensure you have the proper switcher configuration [loaded in](#h.3q602jvfu35) for the event, and all cables are connected properly. You should have power and ethernet connected first. Use the camera output patch panel (the top one) and connect all your cameras and replay (Replay goes into CAM6 on switcher).

Have the final program video output going to the input patch panel connector labeled “SW IN.”

Hopefully, now you’ll see something like this (usually with more than just the one video source):

![](images/image75.jpg)

##### Preview and Program keys (Choosing Camera)

The red row is the “Program” row - it dictates what’s directly being output.

It’s fairly self-explanatory, the button labeled “1” will be Camera 1, “2” is Cam 2, etc. All other mappings can be edited and found in [configuring routing](#h.orx665k35z0s). We usually have replay mapped to “Camera 6”.

[Video example for program row.](https://www.google.com/url?q=https://youtu.be/pJGsH0jxYYk&sa=D&source=editors&ust=1646472726698583&usg=AOvVaw0WJXQG9jI5dEyAPKuW4KFz)

If you make a mistake, it goes live immediately. If you need to quickly cut away from an injury or are just setting stuff up you may use this row, but for the most part you’re going to want to use the preview row.

With the preview row, you get a few more options. Once you click one of the buttons to view a camera, it comes up larger on the multiview for you to decide if it's worth cutting to. Once you decide to cut to a view, you can push it to live in a few ways. The most basic way, and the way you’re going to use most often, is the cut button. Pretty self-explanatory, it just cuts to whatever you have in preview.

If you want to get more fancy, we have a few options. If you want to fade, you can either click “auto” for a smooth fade or control the transition yourself using the slider bar.

[Cut Example.](https://www.google.com/url?q=https://youtu.be/Rx-1buJKa1Y&sa=D&source=editors&ust=1646472726699045&usg=AOvVaw0_C4L91ZUBEGME2mKSgIsU)

[Fade Example](https://www.google.com/url?q=https://youtu.be/IHnbdENvH9c&sa=D&source=editors&ust=1646472726699231&usg=AOvVaw0MK6QvzgEiG0UwpjMWfPsy)

We use hard cuts for:

*   Switching between shots in sports games
*   \[TODO:\]

We use fades for:

*   \[TODO:\]

##### Macros

Assuming that you either are using a [loaded in](#h.3q602jvfu35) setup with a macro, or you’ve [created](#h.dnug90jijlq1) a macro, all you have to do to trigger it from the control surface is hit the “macro” key (located at the rightmost side of the row above the program keys), and then hit its corresponding number. (On the row directly below that).

[Macro Example.](https://www.google.com/url?q=https://youtu.be/NahRnWEBVew&sa=D&source=editors&ust=1646472726699997&usg=AOvVaw11gAgGyUdd8m5__knmB-Gg) (The zooming in on screens indicates that you don’t have to switch to the replay camera manually—it switches for you from whatever camera you’re already on.)

Macro 1 will usually be the replay animation, but your mileage may vary depending on what you’re streaming. Become familiar with the specific setup BEFORE the stream begins.

##### Audio

As well as handling video, the switcher control surface can level (change the volume of) and toggle (on/off) audio.

Quick rundown: If you need an audio source on, click the “on” button for its corresponding camera (cam 1 is left, cam 2 is next to it, etc.). For the rest, read on.

![](images/image82.png)

This is your audio panel. It has four major parts:

*   Knobs - Turn clockwise to increase audio level, turn counterclockwise to decrease
*   Indicators - Shows ROUGHLY the decibel level (loudness) of the audio source
*   AFV - Not America’s Funniest Home Videos, rather, “Audio Follow Video.” This means that whenever you have the camera selected as the program output, it’s audio will be on, and whenever it isn’t it will be off.
*   On - If this is lit up, the audio from this camera is coming through. If not, it’s not (unless AFV is on).

You also have an indicator on the left side of the camera’s view on the multiview screen, which has a lot more detail than just the 4 bars on the mini indicators.

### Replay (3Play) Deck

Replay is exactly what it sounds like—it’s the system we use to get replays up on screen.

#### Setup - Creating a Replay File

This section assumes you have everything properly hooked up and a drive in \[See: [Cables and Connections](#h.3w8y6r8zqch2) & the above section\].

After startup, you should be on the 3Play software screen.

![](images/image58.jpg)

The session name should be the current date AND the event, and include no spaces. E.g. “Mar-25-2021\_BB-PLHS-PLS”.

All 4 cameras should be assigned to different input streams.

Leave session volume, video standard, and resolution default. (D:, NTSC, 1080i)

Once these are set, you can start the session.

After it loads in, assuming that you’re ready (don’t do this if the stream is still an hour or two away, that’ll just waste space, but make sure to do it when it starts), press the record button.

#### Operation

\[TODO:\]

### Uninterruptible Power Supply (UPS)

![](images/image83.png)

#### Turning On

You press the primary power button once. It should beep. It’s on now.

#### Turning Off

MAKE SURE EVERYTHING ELSE IS OFF FIRST.

Wirecast, replay, etc. all off—otherwise you could lose or corrupt data.

Then, press the primary power button, a menu appears on the screen, saying “Turn UPS off.” Press the up arrow once so it says “Yes.” Press Select.

Then, navigate to “Off-No Delay.” Select that, and it will turn off.

Wireless Cameras
----------------

![](images/image89.png)

We have two wireless transmitter/receiver pairs. These have been labeled pair A and pair B, and all of their associated parts are labeled as such. We have (not all pictured):

*   One pair of transmitters/receivers
*   One charger associated with each
*   Two “floating” chargers (not A/B)
*   5x Antenna each (Unlabeled, but should be returned in full)
*   One camera mount each (We use the ones already on the JVCs, though)
*   One DC power converter each
*   Four batteries (total)

The units are fully compatible, but do try to keep them seperate—it makes life easier for everyone.

### Operation

1.  Plug in the battery for the transmitter. Use DC power for the receiver.
2.  Turn both on by holding down the power button. They can take a minute or two to start.
3.  Ensure both are on the same channel. They should already be, but it’s good to do a sanity check. (We keep pair A on channel 1 and pair B on channel 3).
4.  Plug in the SDI ins and outs.

If it says RTSP, click and hold “mode” until it goes away. We want regular point-to-point (which the display will show nothing for).        

Football Setup
--------------

\[TODO:\]

Basketball Setup
----------------

\[TODO:\]

Volleyball/Wrestling Setup
--------------------------

\[TODO:\]

Softball Setup
--------------

\[TODO:\]