# Thunder Warriors
#### Technologies: C#, Unity, Nunit

## Index
* [Task](#Task)
* [Usage](#Usage)
* [Approach](#Approach)
* [User Stories](#Stories)
* [Video Presentation](#Video)

## <a name="Task">Task</a>
This was our final project at Maker's Academy.

Our group wanted to prove to ourselves that we could take what we had learnt over the last 10 weeks and apply it to completely new stack of technologies.
We settled on making a simple tower defence gaming, using Unity and C#.

## <a name="Usage">Usage</a>
In this repo you will only find the scripts we wrote, most of the assets we used can't be put on a public github for licensing reasons.
However if you'd like to try the game, you can find a quick demo of it [here](http://thunder-warriors.herokuapp.com/).

## <a name="Approach">Approach</a>
We started the week by mapping out what we envisioned the MVP of our game would be, resulting in us creating a series of user stories.
From there, we decided on what technology we were going to use and then split of to research. Every couple of hours we'd regroup and present to the others what we'd found.
This took us up to Tuesday evening, where we decided we were comfortable enough with the domain to begin working towards MVP.
We hit MVP by the weekend, and continued to add a few extra features. At the start of the following week we had a meeting to plan the second sprint.
Here we took a step back and looked at our code. We realised that we'd left behind some of the practices we'd been taught during makers and that our code was in dire need a of a good refactor.
It was a tricky task, as a game requires so many messages between different objects. However we believe by the end of the week we came out with a far better codebase that better adheres to the principles of SOLID and is something to be proud of.

## <a name="Stories">User Stories</a>
```
As a player,
So that I can play a game,
I want to be able to start a game.

As a player,
So that I can play for more than one level,
I want to be able to select the number of levels to play.

As a player,
So that I can defend the route,
I want to be able to place a tower along the route.

As a player,
So that my towers have something to shoot at,
I want to enemies to spawn at the start of the route.

As a player,
So that I can prevent enemies from reaching the end of the route
I want to be able to destroy enemies with my towers.

As a player,
So that I can win a game
I need to be able to kill all enemies (of n waves).

As a player,
So that I can lose a game,
The game will stop  / I will lose when an enemy makes it to the end of the route.

As a player,
So that I can see how many enemy waves remain,
I want to be able to see the number remaining on the screen.

As a player,
So that I can enjoy this awesome game even more,
I want to be able to hear some funky music.
```

## <a name="Video">Video</a>
[Here](http://www.youtube.com/watch?v=nKK-ov95Q9E&t=18m21s) is a link to an 8 minute presentation about the project and it's development.
