# Blockchains for Business: From Huh to Hype to Meh
**[Casey Kuhlman, Monax - Hyperledger Global Forum](https://www.youtube.com/watch?v=YPuZM1KEZI8)**

<img src="https://i.imgur.com/MtZ7Lal.png"/>

>This talk focuses on the history of blockchains in a business context as lived and told by the CEO of the first company to build a permissioned, smart contract compatible blockchain codebase (the codebase currently known as Hyperledger Burrow).

>There are three phases to the talk and a predominant lesson for the future of blockchain network implementations will be gleaned from each phase. In the first phase the talk will focus on the early days -- when the community of businesses seeking to utilize blockchains were vanishingly small. This phase, known as the \`huh?` phase was formative for where the technology currently is. The second phase of the talk will focus on the hype driven buzz phase of the technology which drove a huge amount of top down activity. Finally, the third phase of the talk will focus on the phase the technology is just entering where all the software folks get to work.

<a href="https://www.youtube.com/watch?v=YPuZM1KEZI8"><img src="https://i.imgur.com/LG2UjZI.png"/></a>\
https://www.youtube.com/watch?v=YPuZM1KEZI8


## Transcript

`lightly edited for readability`

### Introduction

welcome everybody is everybody having a good conference? good. so this talk is step back from other talks that I've been that I've given here with more of a technical band this is.. 

This talk is structured to take a look at essentially how we got here, and where I, at least, think we're going. So this is was on the business side track for a reason. It's more a summary of the last few years of our company, and our life why is that interesting? 

My company, Monax used to be known as Eris Industries, we were the first to market with a permissionable blockchain. We were the first to market with scalable packages of solidity based smart contracts. We're maintainers of Hyperledger Burrow, and we're one of the founders of a network
called the [Agreements Network](https://agreements.network/). 

<img src="https://i.imgur.com/OCjroSC.png"/>

So we've been playing this game of "blockchains for business" for quite a few years now and so I wanted to think through how the last four years have gone, what we have gone through, and what we have learned along the way. 

### Phase 1 - Huh?

<img src="https://i.imgur.com/7YQCm24.png"/>

When this all started for us was **2014**, at that time the idea of leveraging blockchain technology as an enabler for businesses made no sense to anybody, and so this is the beginning phase I like to call the "Huh Phase" - What are you even talking about with this technology? 

In the early days when we first started we would have a lot of meetings, and those meetings were very very costly. I remember, **in early 2015** one of the companies that's quite big in the space at this point told us, "you guys are the most arrogant startup in the whole in the whole ecosystem" and I was confused by that comment because I don't think of myself as an arrogant person, and I said well why? 

They said "you won't do work for the banks for free", which was apparently why we were very arrogant. That didn't actually make a lot of sense to me because at the time, our operating expenditures were being spent, probably on the order of ninety five percent of our operating expenditures were being spent building open source software. So, from my perspective we were doing a heck of a lot of work for the banks for free, and this phase was very Bank focused.

<img src="https://i.imgur.com/kGjjlxl.png"/>

In the very early days of using of this technology banks were were quite interested, but they didn't really know why they were interested, and the most of 2015 was really about education. At that time what we had Monex have been working on was an open source blockchain client and a developer tool, called Eris at that time. We got sued by Eris exchange and had to lose the name. 

This open source tool was essentially a docker composed tool that made it easy for developers to build things on their laptop, and all of that was open source software. That really helped as an educational tool in getting the ideas of what this technology was about out into the market. It made it a little bit easier for folks to work with the technology and so that was effective, to a degree, in terms of education. 

What the whole ecosystem struggled with in these days was really about the value proposition. In this timeframe a lot of the questions that we would get and others in the ecosystem they would say the questions would be "what is this for? what are the use cases for this?" and there was a lot of discovery that was happening little proof of concepts had just just started to be a thing, in 2015. 

But no one in the ecosystem including us, maybe especially us — because I'm a rather long-winded person — was really able to find a core value proposition. This still is one of my biggest concerns with the blockchain technology community. I often say if you ask 10 blockchainers "what's the value proposition of your technology?" you'll get at least eight answers, some of, many of those will conflict with one another.

In this very very early phase even though it was quite a small community at that time, no one really knew how to describe what we were doing in a way that made any sense to anybody. As we fast forward over the course of 2015, more banks started doing more proofs of concept, and it became a little bit easier, and clearer to say, "how do blockchains fit into the technology ecosystem at large" 

### Phase 2 - Hype

<img src="https://i.imgur.com/k8Cb8ra.png"/>

that moved us into about the **middle of 2016** I would say which was when we really moved into the second phase of this three phase outline that I've laid up here. I don't know if it kicked it off I don't know if blockchains exclamation point being on the cover of The Economist was the thing that absolutely kicked off the phase 2 hype cycle but it was certainly a icon in my mind or for this time. 

The biggest problem that we had was that it was incredibly easy to get distracted. I would get emails, or or my business development team would get emails, and they would essentially read like this:

> "hi I'm the innovation manager of company X my board has asked my CEO what our blockchain strategy is and we don't know anything about what blockchain means can you come talk to us and tell us what blockchain means for our business?"

Any of us that had startups at this time would get those emails constantly, and I took to calling those "blockchain exclamation point emails" because everybody was thinking oh we need to do blockchain, but still it wasn't really well founded within the ecosystem what is this technology? What can it do for us? what does it not do for us? and how does it fit in to the ecosystem?  

<img src="https://i.imgur.com/g80OCoK.png"/>

In this phase you started to see a range of consortiums get spun up, including this one, including the Ethereum Enterprise Alliance, and a number of other consortiums. The typical answer that large companies were giving about "what is our blockchain strategy?" is that they would say "we've joined this consortium" that's our blockchain strategy for now which is a very viable answer for a big company to give but it doesn't actually really address what does this technology mean for our business, if anything. 

The second piece of this that we started to see come online during the hype cycle is an increased focus on developer tools. In the earlier phases, when I would tell folks that we really identified as a developer tools company, they would look at me like I was crazy. At that time everybody was really in the consulting game rather than in the tool game. Where we are now, a lot of people are very interested in tooling, and rightly so. It actually matters a lot, developer tools... 

but we were one of the very few companies that was really trying our best to make this technology simple enough that developer with a laptop can spin up a use case in a relatively limited amount of time. This was a phase where other companies started to come on board, and that whole discussion became a lot easier. Truffle was spun up from the Ethereum community, Composer was spun up from the Fabric community, and these tools along with other tools made it much more simple for folks that were interested in this technology to be able to actually do something. 

The third piece of this is what was happening on the open-source side. At this time things were very chaotic, hyperledger was really just getting spun up, and it took some time to get its wheels underneath it. The public blockchain side of things was incredibly chaotic as well and folks were, from both sides of this community, trying to understand not only how does this technology fit into my business, what is my own selfish business interest, what is my own ecosystems  interest in this technology, but also, how do I actually collaborate? 

At this time there's a lot of attention being drove driven towards the technology but there is not yet an increased understanding of how does this actually fit into my business?  This is when an existential crisis started to come up around this technology. How do we use this thing? what does this mean for my business? Why are you telling me that I need to share data at all? 

A lot of questions were being asked that really frankly very few people had the answers to. Oftentimes the reason for why people didn't have an answer was because the use case was probably not very good at all. 

As we are now in the later phases, I would say, of the hype cycle, and moving more towards the third phase... I think we're in a really strong position as a community because now we've overcome a lot of the things that you need to overcome for this technology to really shine. 

From an education perspective, it's relatively clear; a pathway for what this technology is, there's a range of materials that somebody that is curious can go and read. There's a range of tools that a developer can go download and build something very quickly. There's a range of tutorials across many frameworks, and many tools that make it easy for curious developers to get on the initial points of a potential contributor path, or a maintainer path down the road. 

Finally we're we're kind of at the point now from an use case and value proposition perspective where it's relatively straightforward for most people to answer questions around why are you blockchaining? what is the value proposition of this technology? and why does it make sense within a particular use case? 

We have use cases that are in production now, very early production, but production nonetheless those stories are getting told and that creates a visual image for folks as to how they might be able to apply this technology to to their business. 

Those are the in my opinion the three crucial pieces that needed to happen before we could go in to probably what will be the a moneymaker for software companies rather than a moneymaker for event operator companies and that will be the 'meh phase'. 

### Phase 3 - Meh

<img src="https://i.imgur.com/CXD8aja.png"/>

About six months ago someone told me that the only way to make money in blockchain is to run conferences. I'll be really glad when we get beyond that phase. 

Where are we going here? I call this the "meh phase" for a reason. I've always said and felt that this is really low-level infrastructure technology that did not deserve to be on the cover of The Economist, because it's going to fade into the background. 

This is a data management solution that runs across company firewalls. okay great! it solves a lot of problems that companies have in terms of coordination. great! While it's fine that we had to go through a hype cycle, it really isn't that productive to actually getting things done, because it adds more distraction then it actually accomplishes.

<img src="https://i.imgur.com/0BRFnVK.png"/>

So where do I think we're going? I think we're going in a direction where blockchain technology will be used extensively across a range of use cases that basically boil down to current pain points of coordinating across company firewalls 

The second piece is that I don't think anybody's gonna care. Operators will care, developers will care, systems builders will care, CIOs will care... but basically outside of that I think blockchains will just become a thing that we use. It won't become something that desires to have a conference every week.

The other thing that needs to happen, and this is the last piece of the puzzle for me.. is user experiences across both the enterprise side of the game and the cryptocurrency side of the game absolutely have to improve. This is the biggest challenge that we are facing as we move through 2019 into 2020... because using this technology is currently much harder than users are used to dealing with. 

Particularly around key management, and normal users don't really know how to use their keys. blockchains are based on this idea of cryptographic identity as running through a public/private key pair typically, and there's a range of other user experiences.. these systems are slow, they take a while to finalize, depending on what what system you're actually using, and there's a range of other things that don't really map very cleanly, to how users are used to going to a SAS platform, or to a database administration platform, or some other platform that they might use in their daily business existence. 

Those systems if they move to blockchains, have to address a really fundamental issues around user experience... and we have to keep improving developer experience. While the developer experience has come a long way, as a maintainer of a hyperledger framework we have noted that the amount of people that you can really onboard onto a contributor and maintainer pathway is is vanishingly small, and if this technology is really going to shine it needs to be much more addressable by increased numbers of developers.

The final thing, that we've been working on for quite a few years in various flavors, of this is that public, permissioned, private, I think they will all connect to one another. All of these things will be on a spectrum. 

For a lot of the history of this technology to date, various sides of this community have taken strong positions in opposition to one another, and essentially have said you know the cryptocurrency and the enterprise side of this game are apples and oranges these are completely different things they have nothing to learn from one another there's nothing that they can actually contribute to one another. I think that as we see more public permissioned networks come online as we see business networks that are built on hyperledger or other enterprise grade technologies bloom to a much bigger spectrum than they currently are, we are going to start to see a real merging and much greater increase of cross-pollination across, around, these systems.

This is one of the things that I'm very much looking forward to not only cross-pollination of ideas but also cross-pollination of blockchain based data and one of the things that we're very interested in working on and we will be working on over 2019 is the ability to have smaller networks that are programmatically able to move data and information on a smart contract-to-smart contract basis across bridges of various blockchains. 

When we're able to start connecting blockchains to one another, whether those are more closed blockchains, or more public blockchains.. then, at that point we start to get to something that looks like the Internet. People have historically claimed that public blockchain technologies are like the internet because they're permissionless and I've always pushed back on that because it's never really made any sense to me how you can compare something that has a state and history to a routing layer and that is essentially a network of tubes? 

What I think of and the other piece of it that's never really made much sense to me is that the way that we use the Internet today is that it's essentially a routing layer on top of extra-nets that run SAS platforms, or other platforms... behind... within clusters that are managed as extra-nets. 

This idea of public internet routing on top of extra-nets is, at least from my perspective, the reality of what the public internet is. When we're able to connect blockchains into one another and programmatically move and route information across and between via smart contract to smart contract API calls then I think we're going to be in the land of having something approximating that... 

So that's where I think this this ecosystem is going, those are the three things that we at Monax are focused on moving towards. 

That concludes my talk... 

### any questions?

if you think of the world wide web being built on web servers and web pages browsers and HTTP requests those four items what are the parallel items we'll see in the new world?

that's a great question III think that I think that it depends on what you think needs to move across the boundaries what do we need to route certainly one thing that we will need to route in a world of interconnected blockchains is authenticated packets of information and and then assets and I think of those two even though probably at a technical level they would end up being collapsing on one another you would fundamentally treat them very differently in terms of how that bridge operates because if you're trying to essentially move an asset from one domain to another domain that has a lot more complexity than I'm just sending a signal over a bridge but I think those are the basically be the two things that will happen at the routing layer anybody else I had a question what's your in the POC churned land of doom I think I was around for it with you for a bit what's your favorite favorite unmade movie the one that never like actually got made either from Harris or anyone else you've got a pic I think there would be a pretty boring movie because it would be just a bunch of developers sinning  innovation labs but I think that the funnier plot of the movie would would really focus on the insane difference between how innovation teams in big companies operate and how startups operate and the really wide Delta between those those two and I think that would be the main plotline of the of the comedy of it would really have to focus on that and you know innovation teams are in an interesting position because they work with startups all the time but are still very constrained by the bureaucracy and the context in which they find themselves and so they sit at this kind of quasi middle space between the two and the number of times that an innovation manager has looked at me and just roll his eyes and say look we got to do it this way is as many and so I think that would be probably the most comedic thread that I could find thank you for coming everybody [Applause]