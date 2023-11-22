---
title: "Evolution of an Idea"
subtitle: "Started from an idea, now we here."
thumbnail: "https://www.chapliboy.com/ideas/thumbnail.png"
date: 2023-11-22T20:58:00+05:30
---

I had an idea. And I was convinced that it was the greatest idea ever idead.

In three words: [Zachtronics](https://www.zachtronics.com/)... _but ants_!

---

Here's the premise. In a colony of ants, a single ant has a very basic set of
instructions that it follows. A finite set of "states" that it can be in
and a few methods of interacting with other ants in the colony. But when you
have thousands of ants following the same ruleset, something emerges that is
greater than the sum of its parts. Something like a _SuperOrganism_, where the
colony as a whole seems to have an intelligence. A _Hivemind_ in the most literal
sense.

One of the most common examples of this is the food collection process. When an
ant finds food, it lays a trail of pheromones pointing to that food source,
and very quickly, a large number of ants will be able to find and collect that
food.

Here was the idea that I had. What if the player could write that simple ruleset
that an ant follows. Just the exact _if-statements_ and _state_machines_,
that each ant would follow, and explore how that would impact the intelligence of the hivemind.

And a prototype emerged, where I got the basic food collection working.

### A Promising Prototype

<div class="youtube">
  <iframe class="inframe" src="https://www.youtube.com/embed/nYGg4BhQbSk" title="Antgineering Prototype 1" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>

It was a prototype, so a lot of things are a little more complicated and wordy
than what it would be in the final version, and it definitely felt like there was
something there.


I shared it with a few other game devs, and there seemed to be consensus on a couple of things:
1. The idea is promising.
2. The block-based programming is limitting.

The next set of ideas was a long and knotted journey exploring a whole lot
of different unique paradigms. There were some ideas that I think were pretty unique
and pretty out there. 

### Bespoke Programming Paradigms

There was one which was a geometric approach, based on the _excellent_ talk given by
Brett Victor, [Stop Drawing Dead Fish](https://www.youtube.com/watch?v=ZfytHvgHybA)
([clip of relevant excerpt](https://youtu.be/od9pz-ue3h4)).

Then there was another, where all information was encoded as a direction, so
you would do checks that were all directional.

<div class="youtube">
  <iframe class="inframe" src="https://www.youtube.com/embed/LW4fjvk-LK4" title="Antgineering Prototype 1" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>

Two things from that video:
1. It's called Loomy 4, so it's the _4th_ iteration of _this_ interface.
2. At the end, I said it was fairly easy to understand...

Needless to say, I had dived in very deep, head-very-much-first.

The deeper I got, however, the more the voice in my gut resisted. There was something
_off_ about it all, but I just couldn't figure out what it was. So I kept making more
prototypes, and exploring more paradigms.

### A Moment to Reflect

Eventually, I spoke to Radu, my mentor from Astra, and he got me back on the right
path.

The issue was that all of my design had been bottom-up. I liked the idea of programming
ants, so I was figuring out new ways that programming could be done, just so that it
could be used in this game about programming ants.

He asked me to take a top-down look as well. Why are we programming these ants? What
are they going to be doing?

I made a list; and here's some of the cooler ideas:
- An enemy clan of ants attacks us, so we move  dirt around, and create a funnel for the enemy ants to come through,
where we can hold our ground, and defeat superior numbers, like Gerard Butler and the other 299 Spartans held off the Persians.
- Wood has fallen into a deep pit, which we cannot climb down, so move some dirt around to create
a canal, and then fill up the hole with water, and collect the wood once it floats to the top.
- In order to break a large piece of stone into smaller pieces, we move dirt around to create
a small cliff, then throw the stone off the top so it falls down and breaks apart.

And a bunch more.
It took some mental flexing, but there were a few ideas there.

### A Moment to Realize

And that's when I realised what my gut had been saying all along. All of those ideas, when broken
down into mechanics, were just two things:
- Ants following trails
- Ants picking up and putting down things. Rocks to break, or dirt to terraform.

If all the ants are doing is going to be following trails and moving things, then
what was the point of creating a programming game in the first place?

I guess I had misunderstood what was exciting about the idea and prototype. Maybe it was not the
programming that had been cool.  Maybe it was seeing the large number of ants impact change on
the enviorment that had been interesting all along. 

And it seems like all of that is built on two simple "mechanics". So why not go ahead
and make a _different_ game, and just focus on those two mechanics.

---

So now, I have another idea. And I am convinced that it is the greatest idea ever idead.

In three words: [Factorio](https://www.factorio.com/)... _but ants_!
