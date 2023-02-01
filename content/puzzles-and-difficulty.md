---
title: "Puzzle Games and Difficulty"
subtitle: "How developing a game changed my understanding of the role of difficulty in puzzle games."
thumbnail: "https://www.chapliboy.com/pad/thumbnail.png"
date: 2023-02-01T06:49:50+05:30
---

I love [Stephen Sausage Roll](https://www.stephenssausageroll.com/).

It was the first puzzle game that I played, and it will always be the gold standard for me.
It was brutally difficult at times.
Just manoeuvring around the levels can be difficult, and my playthrough spread out over more than a year.
I would face a difficult puzzle, break my head over it for a while, and be completely stuck. 
Then I would take a long break.

Finishing SSR was such a triumph for me.
Reading through the credits was my victory lap.
Stephen Lavelle, the creator of SSR, doesn't love me.
But he would, if he could.

<img id="love" class="essay-image" src="/img/SSR_Finale.PNG"></img>

So when it came to developing [Konkan Coast Pirate Solutions](https://www.konkancoastpiratesolutions.com/), I thought I knew what I had to emulate.
I would make brutally difficult puzzle game as well.

## Scaling Difficulty

KCPS (that's my game) is fundamentally different from SSR.

SSR is a sokoban game.
You control the character, and decide when to move them.
So a level can have separate elements, and the player gets to move around, and see how the different elements of a level interact.
The player can break down the level that way, and work their way through.

Difficulty in this case could be increasing the number of elements, and setting them up in a way that forces a specific interaction.
That could just be one "piece",
and you could have a level with two such pieces, which in turn interact with each other, and that would be a more difficult level than figuring out just one of the pieces.
But since the player is making their way through, even though it is more difficult to solve, it is not neccessarily more difficult to _understand_.

KCPS, on the other hand, is a "setup and then play"(?) game. 
It's a relatively newer genre. 
When I started, the closest things that I could find were some [Zachtronics](https://www.zachtronics.com/) Games.
They're more focussed on solving problems, so they have multiple solutions, and sandbox-y things, whereas KCPS is more focused on puzzles and specific solutions.

Since that time a few more games of the same genre have come out. 
Games like [Railbound](https://afterburn.games/railbound/), and the pair of thinky collective games [Lab Rat-ional Thinking](https://thinkycollective.itch.io/lab-rational-thinking) and [Flying Crowbar Factory Simulator 2022](https://thinkycollective.itch.io/flying-crowbar-factory-simulator-2022).
There is also the upcoming [Sushi for Robots](https://store.steampowered.com/app/2160240/Sushi_For_Robots/).

In these types of games, the player sets up the game and _then_ hits play.
- The level will have a space with fixed constraints (hazards, goals, starting points etc.).
- Setting up will include placing some tokens (rails, commands etc.) in the space. Tokens will generally be limited.
- Hitting play will generally start the movement of some agents (trains, ships, crowbars etc).

The puzzle is to figure out how all the agents interact with the constraints, the tokens and each other.

Since everything has to be set up in the beginning, the player has to predict how the different elements will interact with the space, in the "future".
After 5 steps, where will this agent be, and how will it affect the other tokens?
That's the puzzle.

Here we can increase difficulty by adding more agents, constraints and limitting tokens.
When you try to put two "pieces" in the same level, the difficulty is increased by a far larger amount.
It then becomes a game of figuring out which tokens are for which piece, as well as making the agents from different pieces avoid each other when they need to, and interact when they need to.

The complexity grows at a much faster rate than a similar interaction between two pieces of a sokoban, because you don't have to deal with "time" in the same way.
So there was definitely scope to make some deviously difficult levels.

## Designing the levels

For me level design is the most diffucult part of game development.
Programming I had learnt by programming other things.
I had drawn and graphic-designed other things.
I had used sound and music for other things.
The only way to learn level design is to do level design.
And often you have to learn it again from scratch for every game.

So I did.
I made a lot of levels.
A lot were trash.
A lot more just felt like trash.
And there were the difficult levels.
They were so difficult.

<video class="gif" muted autoplay loop>
  <source src="/pad/complex_af.mp4" type="video/mp4">
Your browser does not support the video tag.
</video>

I mean, just look at that.
_Dizzying_.
It's so deviously complex.
I'm sure it will make a crazily difficult level.

And then I made some more levels.
Mostly still trash.
But some were definitely in the realm of decent.
And slowly I got better.
Better at playing the game, and at designing the levels.

Games take time to make.
But progress was definitely constant.
And so was growth.
Better at the game.
Better at levels.

The more I made, the more things felt a little off though.
Something that was _just_ not quite right.

So a lot of puzzle design advice goes something like this.
1. Find an interesting mechanic / interaction of mechanics.
2. Make a puzzles where the player is forced to use that mechanic to solve it.

So every time I found a mechanic, I stored it away in the "force to use" folder.
But to actually store the mechanic, I would have to make the simplest version of it that I could.

More time. More game. More levels.

Eventually I got back to _Dizzying_.
By now I probably had a thousand hours in the game.
I looked at the level, and couldn't really figure it out.
Then I just started throwing things at it.
A lot of random experimentation and trial and error.
Finally, the solution popped out, and the level was complete.
I felt no happiness. No pride. Just relief.

The game is supposed to be fun. Right?

## Difficulty and Fun

So we have avoided actually discussing the meaning of the word difficulty for long enough.
Let's see what we can find.

Elyot Grant has a [talk](https://youtu.be/oCHciE9CYfA?t=2173) about two different kinds of difficulty for games in general.
He calls them __Eureka__ and __Fiero__.

__Eureka__ is the moment something clicks.
When you understand how two elements come together to create a new interaction.
It arises from a new point of understanding.
That's the whole point of puzzle games.

__Fiero__ is the emotion of overcoming a tough challenge.
Finally beating a boss who has spent the last few hours destroying you.
It arises from an executional challenge.
That's not neccesarily involved in puzzles.

Solving a puzzle should evoke __Eureka__.
__Fiero__ is optional.
Fiero elevates Eureka. If there's no Eureka, the Fiero is not useful (for a puzzle).

A well designed puzzle should therefore have a few features.
1. A clearly tangible "conflict" that the player can immediately spot as the pain point.
2. An interesting interaction that resolves that conflict. Eureka!
3. The harder the interaction is to find, or the more that the player has to work to reach that point, the more the fiero.

Point number three is just the "difficulty modifier".
Difficulty is not a necessary condition for a good puzzle.

Coming back to KCPS and _Dizzying_, what I felt on solving it was definitely not Eureka.
It wasn't even Fiero either.
Fiero needs a source of constant feedback as to what you've been doing wrong, and how you can improve your execution.
It needs a measurable improvement in skill.
Randomly trying things out is not really Fiero material.

Arbitrarily increasing difficulty does not make a puzzle better.
It just makes it complicated.
In the case of games like KCPS, it makes everything chaotic.
It makes solving puzzles a chore instead of a joy.

Puzzles are fun to solve when they are __interesting.__
Sometimes difficulty is required to make the puzzle interesting, other times it is not.
But the focus is always on finding the interesting thing.

## Back to Level Design

So now, _Dizzying_ and all of its siblings had to be trashed or massively reworked.
Luckily I had that folder full of the mechanics to explore.
I just now had to convert those into levels.
Let me play through them first, to see what we have.

And that was the most fun I had playing my own game.
The levels were old enough that I had forgotten the solutions.
So I had to work out exactly how to make the interactions happen.

I thought I would have to add these as pieces of levels, but once the obsession of chasing difficulty disappeared, I realised that they were great puzzles just by themselves.
I had been chasing difficulty because I thought that's what would make a good game.
The systems I had designed were actually hiding a good game already.
A game much easier than I had set out to make, but a good game nonetheless.

So another round of level design started.
This time, taking levels and stripping them down to their simplest representation.
_Reject Complexity. Embrace Simplicity._
All the new mechanics now had to audition to be in the game.
They had to have multiple simple joyful or surprising interactions.

This game, and these systems work best when presented as a few tasty snacks that you can poke around at.
The solutions aren't generally that hard to find. But that doesn't decrease the joy in finding them.

KCPS is now a "cozy puzzle game about helping pirate ships do pirate things". That's definitely
quite far away from the original _brutally difficult_ vibe I was going far. That's just how it goes
I suppose.

## Difficulty as an Ingredient.

The "future prediction" factor, which created all the complexity in the first place, was now a tool I could use in level design.
I found that some good levels had a touch of surprise arising from that lack of prediction, but since it was so simple to find, it elicits joy instead of frustration.

Of course some traditionally difficult levels still do exist.
Now that I knew what was interesting about the game, I could sprinkle in some difficult levels again.
And these are difficult in an interesting way.
It's mostly optional content, because the best levels are still mostly the simpler ones.

I now see difficulty as an ingredient that a puzzle designer can use.
The Fiero certainly helps make some puzzles more memorable, but it also makes some experiences worse.
Difficulty also has a different relationship with each genre / system.
Something that works in Sokoban needn't work across other puzzle genres.

So that's my answer I guess. It depends.

## Back to SSR

So as my puzzles became easier, I thought back on SSR.
Sure I remember the difficulty, and the accomplishment, but I also really remember the final world.

Don't worry. No spoilers.

The final world of SSR introduces a mechanic that exponentially increases the difficulty ceiling.
But the final world is not actually that difficult.
Sure, there are some difficult levels there, but on the whole, it's really not that bad.

If that final world had been implemented in the same way the the first world was, that would have been insanely difficult.
All that coulda-shoulda-woulda [love](#love) would have been mightily one sided.

Instead, the final world is focussed on exploring ideas.
Each level is a small parcel, specifically designed to explore one fun idea.
Some of these are really difficult, but the difficulty is incidental.
The focus remains on that idea.

Upon reevaulation, it feels like the rest of game is designed just so that you can learn the mechanics well enough.
It's all so that you can come and enjoy the final world.

Wow. Now that is something that is worth emulating.

Oh man, I love Stephen Sausage Roll.

---

KCPS will release on 1st March 2023.
[You can wishlist on Steam now.](https://store.steampowered.com/app/2156410/Konkan_Coast_Pirate_Solutions/)
