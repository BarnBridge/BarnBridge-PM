# BarnBridge Project Call 007 Notes 
### Meeting Date/Time: Thursday 2020/12/17 at 15:00 UTC
### Meeting Duration: 30 mins
### [Github Agenda Page](https://github.com/BarnBridge/BarnBridge-PM/issues/10)
### [Audio/Video of the meeting](https://www.youtube.com/watch?v=fcgkyIF4iQM)

Moderator: Troy Murray

Scribe: Rayne L.

Attendees: Keegan Selby, Vitaliy Chernyak, Pavlo Bendus, Troy Murray, Milad Mostavi, Dragos Rizescu, Bogdan Gheorghe, Tyler Ward, Akin Sawyer, EJ Rogers, Mark Ward
## Intro

**Troy:** BarnBridge call 007, James Bond would be very happy. It's fitting that this is the last call of the year. Let's jump right into it.

# Tech/Dev
## BarnBridge App

**Dragos:** Last week, as promised, we released a new version. Everything has been running smoothly so far– minus a small issue pointed out by the community regarding a UX flaw. It's a minor flaw happening with the withdraw. We will fix that. Thank you to the person who notified us. Other than that, there are not too many new updates. We will roll out more updates, but they are more to do with the BBDAO and our products.

Alright, Bogdan, take it away, and give the saucy details!

### BBDAO

**Bogdan:** Since last time, we have updated the smart contracts. We've added more functionality. For example, you can cancel a proposal in-case something is wrong or a bug is found or something similar. We went forward with internal reviews– they are complete. Nothing major was wrong, just a few small fixes. Kudos to Atpar for finding and fixing them.

We kicked off one of the audits. It's ongoing. The second one will start up before the first one finishes, so there will be some overlap.

The back-end is in progress. Not much excitement there. We are on the final stretch with a working data pipeline. I think that's all that's remaining– pulling data for the proposals.

Front-end, I'd say 75-80% done. They are connected to the smart contracts deployed on the test-net, & they are connected to the back-end. We just have the proposal creation. Just polishing, the final test and checks.

### Smart Yield BOND

**Bogdan:** Smart contract development is in progress and running smoothly. We are going to have the first version of them working, hopefully by the end of this week. The internal reviews on those will occur soon.

UI design is close to being completed, just some finishing touches left. We have done a walkthrough with some of the team and some of the investors. Everybody seems to be happy with the appearance. External audits– booked. Once the internal reviews are finished, we will open the repos to the auditors. The audits are booked for February, so we are on track for the March launch.

Regarding the back-end specs, there is also not much to update— not a very exciting part. 

### Smart Alpha BOND

**Bogdan:** We are collaborating with Atpar, our advisors. They suggested two different specs for them. Both of them are awesome. We will most likely, release them one after another, in the springtime, following the release of Smart Yield. We are still having internal discussions regarding which spec is first to be released. Although we are close to a consensus. 

Around next week we are looking to pull the trigger on development. It doesn't matter which one because both are pretty much in the same framework. Smart contract development is about to start. It's just about which one is shipped first.

We are putting down the wireframes for the backend and the frontend.

That's it! Happy holidays 😎

**Troy:** Happy Holidays! 🎅

Awesome those were nice updates. Akin will provide updates about the DeFi standards.

## DeFi Standards

**Akin:** On the last call, we discussed how we are having conversations with potential partners around a set of standards we've been developing for DeFi. I'd say we are about 80-90% of the way there. We just need to round-off a few definitions & terms. 

Just a refresher— what we are trying to develop is a set of disclosures around risks, our technical platform, a glossary of terms. 

Essentially phase one is getting people familiar and comfortable with the products. What the risks are and all the definitions we are using. We are hoping to create standards around those terms. So that the industry and our potential partners use those terms as well. That will establish some level of uniformity. Providing a basis to develop future products and provide other things like ratings.

We've had conversations with our partners. Chainlink– will give us price feeds to make some of these things happen. This sets the tone for the future. Potentially creating a secondary market for all the assets that are traded, we are calling it Bond Desk. We are pondering some ideas that are more long term. They go beyond the standards that would be 'static' to start. 

We are looking to create ways for people to measure our performance against the ratings and standards we are giving our asset baskets. That's down the road and in-discussion with Chainlink. We are trying to establish parameters around that and define the direction. So people understand where this is going. We want to make sure there's a permissionless way for people to understand— what they're investing in and track how those investments perform against the parameters we've created around the risks. 

**Troy:** There should be a lot more information about this around the turn of the year. Next year there will be a ton of information so look out for that.


## Bounties

**Mark:** Last week was really successful for the bounties. The whitepaper and website have been translated twice. Both Portuguese and European Spanish. They should be up and available within the next week, or a week and a half. It's the holiday, so I'm unsure of the exact time, but we are trying to push it out as soon as possible.

Right now, we are slowing down a bit on the bounties. But we are trying to think of more ways to get the community involved. Troy and Tyler are always thinking of new things for you guys. 

Right now, we have about two or three bounties ongoing. The meme competitions are still rollin'— please, everyone keep on submitting memes to the meme channel on Discord!

We will be posting new bounties in the Discord and on our social platforms, and if you follow BarnBridge or me on Gitcoin, you will see them there too. Check us out on social media for bounty updates. Keep an eye out on Gitcoin and Discord specifically.

**Troy:** Definitely! Keep the memes coming— we love them. We talk about them a lot, everyone's making them, thank you all.

It's time for TeleTyler, sorry community, we tried to get him a Santa suit, but it's hard to get one this time of the year. We failed you. Sorry, everyone!

## Operations/Marketing Run down

**Tyler:** Yeah, I couldn't even get a Santa hat. So I'm wearing this Fargo hat and I'm on this television. 

As far as an update goes, I want to talk about the tweetstorm from the 11th that gave general timelines for everything. It's pinned on [Twitter](https://twitter.com/Barn_Bridge/status/1337402484973858817). The roadmap as we wrap up— a version will be on the site. It will be accurate for the majority of the year, less so by the end of the year as changes are proposed. I assume when we release these products, there will be feature requests that change the timelines. 

At this time;

* Smart Alpha; We are relatively close to the final product.   
* Smart Yield; Finalizing the code from the smart contract perspective.
* BBDAO; The DAO code is on freeze-commit and is already being audited.

This is separate from the front end. All of it will be fleshed out in time.

For the DAO, we are working with Quantstamp and Haechi. We're currently under contract with Quantstamp. Their audit should be completed by the end of January. Haechi should be done by the end of this year. Any problems we will obviously have to fix. So that could affect timelines.

For Smart Yield, we're working with OpenZeppelin. Because we thought, since this is a new primitive, it would be in our best interest to get the best of the best. OpenZeppelin was number one. We'll probably work with Hacken again because they discovered flaws in our yield farming contracts originally. Just having another set of eyes will be ideal even though they are not a massive brand name. We got a lot of value from working with them. I recommend more teams work with them.

The DAO is 95% complete from a code perspective. We're probably looking towards the end of the month, January, if not early February for the DAO launch. 

The Smart contracts are being finalized for Smart Yield, also near the end of February.

We are working with Atpar to flesh out specs for Smart Alpha. It's split into two concepts. We are just prioritizing what to come out with first vs. what the industry needs immediately.

I'm also working on a secret field operation. It has to do with tokenized sports betting. I'm not going to share much, but we are looking to work with PoolTogether. I'm talking to some other teams to integrate what we are doing. 

Just to clarify, this is not integral to what we are doing. I don't want to confuse that project with BarnBridge. I think there is potential for the two.

We are going to be hitting 2021 hard. There should be products releasing almost every month. Once the framework is in composability, and the integrations will allow us to ship quickly. When you build a house, the longer process is building the foundation. It takes less time to paint or add a kitchen. 

**Troy:** I'm looking forward to the Kitchens. 

**Tyler:** For all you farmers...[17:27-20:37](https://youtu.be/fcgkyIF4iQM?t=1047) 👨‍🌾🚜

# Round Table

**Troy:** Would anyone like to add anything? We did not receive any questions from the community this week.

**Pablo:** The roadmap is on the website. [BarnBridge Roadmap](https://barnbridge.com/roadmap/)

**Troy:** Pablo and everyone has been working very hard on updating the website and pushing changes to the frontend so everything is up to snuff. Thank you very much.

**Mark:** The roadmap and all of Pablo and Vitaliks updates should be there.

**Troy:** We also pushed out the DAO article. [BarnBridge DAO](https://medium.com/barnbridge/barnbridge-dao-built-for-the-future-3735fbd671c5)

Happy Holidays everyone we will see you in the new year! Everyones ready to put 2020 behind us.

**Everyone:** Happy Holidays! 👋🎅👨‍🌾
 
