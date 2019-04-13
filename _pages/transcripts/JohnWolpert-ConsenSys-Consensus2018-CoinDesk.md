---
title: "TRANSCRIPT: John Wolpert of @ConsenSys talks awesomeness at #Consensus2018 #CoinDeskLIVE"
description: "John Wolpert and Pete Rizzo Discuss the Weakening Distinciton Between Private and Public Blockchain."
permalink: transcripts/JohnWolpert-Consensus2018
header:
  image: "https://i.imgur.com/xjXLMUx.png"
  caption: "May 16, Consensus 2018. [Pete Rizzo](https://twitter.com/pete_rizzo_) of @Coindesk interviews [John Wolpert](https://twitter.com/jwolpert), ConsenSys Studios."
  #thumb: "https://i.imgur.com/Nb95j0G.png"
---

May 16, Consensus 2018. [Pete Rizzo](https://twitter.com/pete_rizzo_) of @Coindesk interviews [John Wolpert](https://twitter.com/jwolpert), Consensys Studios (former head of IBM's blockchain Division).

I found the video at [https://www.pscp.tv/coindesk/1mnGeXaANqEKX](https://www.pscp.tv/coindesk/1mnGeXaANqEKX) then [ported it to youtube](https://www.youtube.com/watch?v=b6hFmXjJgR4) for their autotranscription.

This is a cleaned up version of that youtube transcription. 

{% include video id="b6hFmXjJgR4" provider="youtube" %}

note: I've included my youtube copy here, rather than the original, because periscope videos are not easy to embed.
{: .notice}

## Pete Rizzo Interview with John Wolpert of @ConsenSys formerly IBM.

live we are of course live-streaming to Facebook and periscope all day here at consensus 2018 the world's largest blockchain and cryptocurrency conference taking place in New York I'm your co-host for this session Pete Rizzo editor in chief for Coindesk.

My next guest is Mr John Wolpert, Seeker of Awesomeness at ConsenSys, formerly one of the faces of IBM's early blockchain work, now with the consensus aventure studio for producing blockchain projects. 

Welcome John 

> Thanks Pete 

so John I want to lead into a conversation we were having backstage and I preface this by saying it's probably something we've talked about over the years this idea of interoperability. 

I think you were one of the early prominent representatives of what I would call the enterprise community. The idea that big companies were interested in blockchains, they were interested in the underlying technology of crypto currencies. 

## Enterprise Increasingly Interested in Ethereum and Public Chains

Now we're seeing I think a lot of entities like your former employer IBM, you know, certainly Deloitte, big-name businesses that are interested in blockchains - but they're also interested in crypto assets. 

I think for a lot of people consensus 2018 might be this convergence point. Let's wind back the clock, where did we start and how did we get here? Because I know early on these two communities were a bit like oil and water.

>yeah well in 2015, I was working at Watson and Jerry Cuomo called up he said "hey Louis its Clark" I said "what do you want Jerry?" and he said well "there's this thing called blockchain out there passed the Mississippi go check it out" and I said "well give me a ship and crew and I'll go take a look" and he said "well I got a canoe two dogs in a musket." 

> this the exact conversation, pretty close and yeah I tell it a lot so maybe I've mis-transposed some words, but it's pretty close. and and and we got lucky we just and and we're like oh my god there's Eldorado's out there.

gold in the hills 

> well and more specifically it may be a way of upgrading the Internet right so I was never a coin guy right I was interested more in upgrading the Internet. so smart contracts are interesting and token economics, if you think about it, if a social economist named Galileo and you were trying to like see incentive structures differently, 

>blockchain is like a telescope right it's a way of in fact anything that you try to do with blockchain where you're using it as a hammer doesn't you know you pretty much quickly prove that you don't need it so that's what if you took if you see if you use it to see problems differently then it becomes insanely valuable because you have a rails that allow you to more precisely see, understand, and then instrument incentive systems in a way that the old rails just would collapse under its own weight.

>so that's very exciting but it's more abstract for me than it is like token X or value of coin Y that that was never really the thing for me 

so let's go back to that 2015 I want to take me in to take the audience into your initial thoughts there so it's 2015 you're going on this exhibition and you were sort of looking at the tools of the time trying to apply this into a business framework and what you found was these were internet-based networks that were moving money and it sounds it so you were more interested in the network 

## Not Much Difference Between Enterprise and Startup Needs

>right we were interested in and, I want to say Enterprise, I've never been an enterprise person.. so much as an industrial use person that is a start-up that has to worry about grandma's pension has the same issues as a giant company. so we start read about security privacy hunt I said...

A startup worries about grandmas pension? 

>oh yeah absolutely so I mean I don't care I've been a startups founder 3 times and I've been a IBMer three times, I work for a few other big companies too so I don't see the difference. I think that you have similar problems, and as we as we evolve, and the internet evolves into this transactionally aware internet then the problems of a start-up and the solutions to those problems are accessible to startups and big companies kind of all together 

>so never really thought of it as enterprise so much, but what we did do is... my first job at IBM, in 1997, was on the Java team and sure enough we thought hey "this is the next Java" Ethereum, in particular. In 2015,

You saw it more as a programming language something that developers would use...

>as a standard that was not built by us, that we could get behind everybody's rich uncle about right and again help the internet evolve 

## A Time and a Season

and you ended up sort of going your own way of making your own platform, now part of the Hyperledger umbrella.

>Yes. so 2015 sometimes you know in an innovation and creativity right there's divergent thinking there's convergent that I need right you need both and...  there's a time you know is the whole song right, there's a time for everything, there's a season. right well the season for the divergance...

yes you were talking about the convergence so you know it sounds like there was divergence the enterprise sort of when it did it's early R&D; work and you know recently I think we were talking about the news we've seen some of these companies warm up to this idea that they can use crypto currencies on these networks 

> yes alright, well let me let me take a step back in 2015 the problems that we saw for industry we're not the same problems that the we noticed that in the Ethereum community, in particular, the main net public folks in that in that community they were worried about some other problems, equally important problems, and then equally hard to figure out scaling all the stuff that we were figuring out now and we've decided that if we were to try to like get in there we would distract we would distract

>we needed to diverge right so and we said well wait a minute we're not good at everything, IBM, you know there's some things were terrible at, but we were good at what? databases, distributed systems, crypto, we know a few things about that. so we thought well let's throw in and try to build something that that added to the conversation and focus on the things that we thought were problems: 

>confidentiality being the most important one which is different from privacy I wish everybody would understand this we talk about privacy the public side we're often talking about Zk Snarks or you know of zero knowledge proofs and that's about obfuscating attributes of state changes... you can't do that on a multi-line smart contract with a bunch of conditionals and some loops, it would never complete. that you know 

## Gendalian Architecture

>that kind of encryption and it's not the right thing what you need is smart contract execution segregation in other words and I think Richard Gendal Brown put this well years ago with R3. 

>I would I would say that Fabric and R3 are are examples of what we might call the Gendalian architectures... all came from sort of his brainchild that said "I need a blockchain but if you and I are the only two people in an agreement everybody else should not be executing the code of our agreement" 

> now that's a neat trick because part of what makes a public watching work is everybody executing that code right so how do you get both at the same time? 

>fabric went the way of channels, Corda went another way for doing that, but that meant I can have a channel with you and I can have a channel with him and we have a channel together but it becomes this what we learned is it becomes this factorial nightmare, right, of different channels which none of which actually talked to each other.

>I can't take a smart contractor or a function on channel one and invoke a function on channel two in any way that doesn't get into race conditions and issues of distributed system ...

so I think I've made ask that question a different way I think the enterprises have traditionally wanted to execute this complex business logic but we're also seeing them do some things in the token ecosystem so they're partnering with maybe projects that have launched their own cryptocurrency networks a little bit more experimental of course we've seen this and you know decentralize electricity grids things like mobility and automobiles sharing data in those environments is it something where maybe this is just PR buzz they're just trying to kind of get in on this crypto asset sort of craze or is there are they not understanding sort of you know the attempt to confidential privacy or what's your take on this? 

>well I think that I get the benefit of kind of living a year in the future and the money is living five minutes in the past right so there's a lot of people that are there saying let's build stuff that we can build with the current stack today right and I get to you know they're gonna make more money I get asked to do more panels all right okay because you know I'm thinking about what we could be a year from now.

>from that perspective I think all those ... there are things that are going to be really great ideas and then it's a big tent a lot of people have boneheaded things that won't go anywhere, and and some of those things we thought were boneheaded are going to turn out to be brilliant, and that's the way this works.. and I've seen this play out three times since the 80s it always kind of works out this way it's fun to watch I like to be in the game 

## Working for ConsenSys

coming back to that you know a lot of people are looking at where are we now you said you can see into the future of course you're with ConsenSys, huge production Studios... has attracted a lot of enterprise builders, and one of the things I think that has been ConsenSys' selling point as "come here to build" is that something that you know talked about? what's so appealing about that? 

>oh you know when I was I was pretty happy running product for IBM blockchain, I was the head of products and Joe Lupin said "hey you want to come start businesses on the next Internet" and I was like "I can't say no" right? I mean who would say no to that? and I love my old team they're awesome and I love my new team and I do like this mesh like decentralized hierarchy.

mesh like decentralized hierarchy?

> not hierarchy I should say yeah I mean the fact that you know leadership is a service business, right? yeah even leadership is seen as a service right nobody works for me I don't work for anybody else but if I provide a good service in terms of making a decision about something people you know can keep me on the island or vote me off on that particular thing and if we're in a meeting and you're doing the best listening and I have a dog in the hunt maybe you'll tell me that I'm the one that should make the decision. another meeting I might say hey you should make the decision that's the environment and consensus but as opposed in an enterprise it might be more top-down and I'd say it removes the question mark of okay we're both about the same seniority and we both are interested in the same subject so now we have to figure out who's going to work for whom..

> instead we can just say hey let's team up and let's publish our api's to each other you want this input and make this output and I want this input hey we can work together and that's happened that's not just a platitude that actually has happened to me two or three times I think a lot of people are wondering....

## *it's absurd to say private networks or public networks*

I talked to Richard Gendal Brown about this earlier today.. we saw enterprise become this big news maker, all the headlines, Blythe Masters, JPMorgan, doing all these blockchain things. now we're seeing that pendulum swing over to crypto assets, billions raised... what are we gonna hear more about? enterprise business because they aren't... they're doing things, moving real money on blockchains, when do you expect to see a real breakout? and can that breakout compete with these open or permissionless networks?

> well see now there you there's the interesting thing so what I see at least in my alternative year from now future is, one, we're now where we've gone from this legitimately divergent time, and now we're coming to a convergent time. 

>**I'd like to see a year from now it to be for most people to think it's absurd to say private networks or public networks you know I don't want to have a private network or a public network for my application things I want to build need transactions that are private that terminate in public transactions and might come back around** and the public thing can you know can be a parameter in my private thing I need a smart contract that is confidential but they can also pass parameters into a less confidential one and multilateral and what Gary Singh calls en-lateral. 

>so a bilateral agreement might have a number of conditions in it that rely on a multilateral agreement and it that also might influence that multilateral agreement now here's where convergence could come is to say look you know what there are different protocols like Fabric and others that have our really good at channels really good at doing these, and lateral channels, private channels... 

>if you think about a blockchain security is really two things in both camps today have only one public amazingly good at tamper resistance and collusion resistance right if you're a big established multi-geography public blockchain network of any ilk you have good tamper resistance. 

## Surveillance Resistance

>so what do you say when you're trying to promote yourself you say we've never been hacked which really means you've never you've never had the ledger tampered with in any way right right so but surveillance is the other part of security right and probably networks are useless for surveillance resistance by definition. 

what do you mean by that? 

>it means I can see everything is going on all right and I probably shouldn't know about the fact that you're giving me a special price on those mangoes, and the supply chain problem.. all right on the other hand a purely private network is kind of hamstrung into its own bag and can't break out of that and more importantly it's you know it has less tamper and collusion resistance. 

>you think that ten organizations can't collude against the eleventh? of course they can, and they do. yeah right but in the past we've had to choose one or the other... 

>I think a year from now we're going to be able to say hey I can do private that's especially things with layer two technologies plasma and plasma made architectures that are coming I think that's all going to converge into a pretty nice tight spec for being able to say I'm gonna have billions of n lateral peer-to-peer relationships going on with smart contracts functions you know tokens that are peer to peer or multilateral that are then kind of adjudicated by a main net that is public that gives you the tamper resistance of a public network without leaking any information to it... 

>but the surveillance resistance when that's appropriate of a private network right if we can get both of those at the same time and if we can do that without leaking information from private relationships into the public network while securing the public using the public network to secure it all and to allow coordination.. because computer programmers know the problem is *race conditions* and *non determinism* 

>if you you if you have a function on one ledger you and me that depends on a function of their ledger and we get the timing wrong bad things happen, but if you can use the main net to coordinate them without leaking information then I'm gonna predict that a year from now or some other you know some time eighteen months maybe enterprises and governments will not only be okay with the public network they will demand public network being part of the most private solutions they're working.

## Final Thoughts

final thoughts we were talking a little bit backstage about where we are in this narrative of blockchain \ cryptocurrency history. you think this is a network technology more people are gonna get involved, the industry is getting bigger, we're gonna continue to see people getting engaged, why is that your thesis?

> well so we were talking about Java right earlier, and it's a programming language, and it's not really a network meaning it does actually have an impact on network technologies but you can write Java you don't need other people writing Java to write a useful Java program. So it had faster uptake, but I remember when I came aboard in 97, have gotten involved with Java it was only a year or two since Sun put it together, and got it out there 

you're talking about the speed of these things?

> speed of it yeah but within a couple years it was 2 million developers and Java one went from a little tiny nothing conference to 30,000 people you had to run at the Javits Center for Moscone and I was wondering last year I'm like wow this you know it the consensus events and other events have grown but they I don't see two million developers I don't see 30,000 people in a room and even this year we've grown tremendously but I'm by historical standards I haven't seen those kinds of numbers yet.. 

your thinking maybe we're missing this developer piece?

> well I do think yes I think that what's holding a lot of developers like me and teams I you know I'm looking that's my job is to find really great teams that want to become part of consensus and grow their their their startup within the consensus mesh I get the benefits of teamwork but build their thing right that's our job and a lot of the most interesting use cases 

>I don't like that word but you know the most interesting businesses you know like use cases why it's a word that it's a phrase that turns your brain off you say what's your use case tonight right now where nobody's talking to each other anymore 

>but you know those interesting businesses and business models really require the ability to do things that are private and public and trans private or probably you know that I need to be able to set the scope of my functions appropriately for each part of my application not say ok I'm all in amount of private network or I'm all in on public and until I have that I can't build a lot of really cool things so I think that once we have a little bit of convergence we'll solve lots of divergence but if in the next year we can converge... Hyperledger and EEA can kind of go in a room and make a baby... and get together and if things like fabric and Ethereum can if a win for fabric is a win for Ethereum and a win for Ethereum is win for fabric and other protocols 

>would that be nice if we can have that and get past all that stuff we can get on with a business of writing really cool applications that do what they need to do and that then that are able to not simply do some business-to-business thing privately but it can also contemplate this token economics this if you were a social economist named Galileo right the blockchain certainly public blockchain Ethereum is like a telescope it's a way of seeing differently right and if you can see things differently and if you can instrument really entirely new incentive systems that would have collapsed under the weight of the old rails right I mean the transaction systems today are too heavy to implement these kinds of out novel innovative incentive structures incentive structures or business models the interesting business models that are coming can't live on a private network or even on a public network they have to be trans network and that's convergence so once we have that we're going to have 30,000 people at Javits Center, we're gonna have two million developers or more 

real summer of blockchain love coming up according to mr. Walbert here I want to thank you for joining once again this event plaintiffs live will be a live streaming through the rest of the day at consensus 2018 John thanks for coming on for Channel