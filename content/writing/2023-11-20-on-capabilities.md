+++
title = 'On Capabilities'
date = 2023-11-20T17:31:34-05:00
slug = 'on-capabilities'
draft = false
+++

>A fox knows many things, but a hedgehog knows one big thing.
>
>-- Archilochus

I use technical language here, but really this is about explaining certain intuitions that I have. While I think that you *could* formalize them in the case of a particular world-model, the map is not the territory, and hence beliefs about the territory must ground out in unformalizable intuitions at some point.

Suppose that the world is some very highly dimensional vector space. \[This isn't too far from what quantum physics supposes.\] Suppose that there are various agents, and that these agents have different capabilities. We might think of the capabilities of an agent as a particular set of vectors that are its action vectors. Each time step, the agent is capable of taking an action that updates the world-vector by adding one of their action vectors to the overall world vector. Suppose also that if agents successfully shift the world into certain states, that they are capable of destroying other agents (by knocking them out of homeostasis). 

\[Note that this model has a number of flaws. In the real world, agents can change their capabilities over time, there are nonlinearities in updates, and agents are generally a part of the world. However, I believe this model still clarifies some real world dynamics.\]

There are two ways to think about the magnitude of an agent's capabilities in this model:

1) The norm of each of the action vectors of an agent. This is the magnitude of change that the agent is capable of exerting in a given timestep. I will refer to this as *power*. 
2) The dimension of the vector space spanned by the action vectors of a given agent. This vector space defines all of the world space that the agent could possibly reach on its own, given enough time. I will refer to this as *variety*.

Let us say that two agents are in conflict. If an agent is "close" to another agent, in the sense that it would take relatively few actions for it to knock the other agent out of homeostasis, then the agent witt the the larger power will generally win out. This is because they can change the world more in each time step, and so if the agents are directly competing, they will win out.

However, if the agents are relatively "far" from each other, in the sense that it would take many time steps for them to affect each other, then the agent with the higher variety will generally win. This is because they can often find some direction that the other agent is incapable of affecting the world in, and if they get far enough in that direction, the other agent will generally not be capable of affecting them.

This is very abstract, so I'll make it more concrete. If you, a human, are swimming in the ocean, and encounter a shark, it can generally win. It is close to you, and much stronger than you, and can bite you and kill you. However, if you are far enough away from the shark, you can swim to land, save money, purchase a fishing boat, and then go hunt as many sharks as you want. Once you get a big enough boat, you are in a part of the world space that sharks cannot reach. Given your much higher variety of actions than a shark (including commandeering a boat), there are likely many things that you can do that a shark can't do. However, if you are in the shark's domain, it can do a few very important things much better than you (swimming and biting).

Another example: suppose you have a highly intelligent but weak hunter-gatherer named Greg, and a relatively unintelligent but strong hunter-gatherer named Grug. If Greg and Grug are in conflict, and Grug is close to Greg, then he can walk over to him and hit him over the head with a rock, thus winning the conflict. However, if Greg has more time than Grug, he can construct a bow and arrow, and then shoot Grug if he tries to approach him. This works because no matter how much time Grug has, he simply won't ever be able to grok how to make a bow and arrow, or how to adequately defend against a bow and arrow.

Note that the reason that I specify that the higher-strength agent kills the higher-variety agent is that the higher-strength agent has no ability to ensure their victory over the higher-variety in the long-term without killing them. If the difference in variety between two agents is high enough, then the higher-variety agent will generally be able to figure out some long chain of actions that the lower-variety agent can't respond to. With enough difference in variety, the lower-variety agent is often not even able to perceive when the higher-variety agent is executing such a series of actions before it is too late. If Grug just kept nearby and menaced Greg, Greg could pretend that he was foraging or doing something otherwise innocuous while actually working towards constructing caltrops or some other tool that Grug can't understand but will allow Greg to escape and then defeat him.

However, if the two agents are close enough in variety, then they will likely both have something that they can do that can counter the other. For example, if Greg can make a bow and arrow, but Grug can make a sling and they are both perceptive enough to see when the other is starting to build some nefarious weapon, then if either starts down the path of trying to kill the other, the other can respond. If they are relatively similar in variety and power, they might not ever be able to be certain that they could destroy the other, and thus they might rationally chose to refrain from initiating direct confrontation. It is even more likely that neither will attempt to destroy the other if there are many other agents of similar capability nearby. If Greg and Grug live in a place with other hunter-gatherers and fight, where one of them destroys the other but is injured in the process, then some other hunter-gatherer might come along and take advantage of the winners injured state for easy victory. Further, there might start to be the possibility of positive sum cooperation, and thus game-theoretic cooperation strategies might prove more successful.

## Hyperintelligent Agents

There is no way to protect yourself against an agent with substantially higher variety than yourself in the long-term. Your only option is to destroy it as quickly as possible, if you can. Intelligence is a major contributor to variety, as it allows you to string together long chains of actions that in conjunction product highly novel effects.

Given the chaotic nature of the physical universe, I am highly skeptical that one can predict what a high variety agent will do in the long run. This includes predictions about constraints on its behavior and influence over others. While one might be able to make such predictions in the presence of known-unknowns, I am highly skeptical that one can ever know anything of this nature in the presence of unknown-unknowns. How can we predict the behavior of agents in situations with dynamics so foreign that we don't even know that we don't know them?

The only slight exception to this is if you have much higher power than the other agent and can take action to improve your own variety. If this is the case, then you could increase your variety to a level commensurate with the other agent by the time it could become dangerous to you. However, this isn't really an exception, as it solves the problem by eliminating the difference in variety, which was the problem in the first place.

If you have commensurate variety with another agent, and exist in a world with many agents at similar levels of variety, you don't need strong guarantees on the behavior and motivations of others, as you can individually and collectively respond to potential threats. And even if you do believe that you have strong guarantees on the behavior and motivations of others, these guarantees cannot be guaranteed to hold in the face of unknown unknowns, which one is likely to encounter if there is an agent with genuinely higher variety than them. \[An agent with higher variety must be able to take higher variety actions -- otherwise it is definitionally not higher variety.\]

## Alignment

I do think that traditional alignment work is very important. However, the way I understand its importance is as the development of novel human capabilities, and as a way to increase human variety. Theory of mind is a powerful capability for humans. The ability to introspect on and interpret models is similarly, if not more, powerful. The ability to anticipate failure modes (such as deceptive alignment) of tools that we rely on is similarly a powerful and important human capability.

With this view, it does not seem that alignment is likely to be any single thing, or to just involve capabilities regarding models, would seem to involve the development of a diversity of novel capabilities for humans involving AI models and the world.