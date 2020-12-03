# BarnBridge Project Call 006 Notes 
### Meeting Date/Time: Thursday 2020/12/3 at 15:00 UTC
### Meeting Duration: 30 mins - 1 hour
### [Github Agenda Page](https://github.com/BarnBridge/BarnBridge-PM/issues/8)
### [Audio/Video of the meeting](https://youtu.be/-skbfvP8S8s)
### Breakdown:
  * Tech/Dev: 30 mins
  * Roundtable: 30 mins

Moderator: Troy Murray

Scribe:

Attendees: Keegan Selby, Vitaliy Chernyak, Pavlo Bendus, Troy Murray, Milad Mostavi, Dragos Rizescu, Bogdan Gheorghe, Tyler Ward, Akin Sawyer, EJ Rogers, Mark Ward 

## Intro

Troy: Welcome everyone to Barn Bridge project call 006, we are going to start the Agenda off with Dragos himself. 

## Tech/Dev 

Dragos: Thank you, Troy. 

Hello, everyone. First thing we are talking about is the BarnBridge App— Yield Farming. 

Monday last week, there was a front end bug. Luckily we solved it quickly. The bug was caused by a list of transactions recieved from the sub-graph. It was saved in the session storage, the session storage filled up and resulted in a front end crash for a lot of user browsers. Not that bad of a problem— too many transactions.
 
We addressed it by not saving the session storage in the same way as before. The result is a not so good user experience when currently navigating the app. 

With our goal of a better user experience. We started moving away from the graph. We started implementing our own packing component, added some UI updates— epoch graphs are being updated.

Here is a sneak peak, and we will soon roll a release for these updates. Either later in the day today or tomorrow. The updates allow the graphs and transaction lists to load a lot quicker. Creating a better user experience.
 
#### BBDAO
 
Bogdan: Smart contracts are now 100% done. We are working on improving test coverage, doing some internal reviews. As far as design goes, a third of it has already been implemented in the front end. We are just connecting it to the test net contracts. 

Shout out to Slava he's been killing it with the front end work on both the Yied Farming and the DAO at the same time. 

Dragos: I think we can show the community a bit of what this is going to look like. I don't think that's going to be a problem. Let me share my screen. 

Bogdan: Small spoiler. 😎 

Dragos: This is how the DAO overview page will look, Denis killed it with the UI once again— shoutout to Denis. This is going to be the list of proposals, when you click a proposal you will get something like this. I'm going to stop showing this now, that's the sneak peak. 

Back to you Bogdan.

Bogdan: Gracias, ignore the top secret part, that was just Denis messing with us. Just for authenticity.

Back end work is in progress, there is a data pipline working that will replace the old graphs. We are slowly feeding data to the front end, internal reviews are in progress. 

All of our smart contract developers plus, our advisors at ___ are looking at the smart contracts to make sure that everything is in order and works as it should. We have ___ audits already booked with contracts signed. The first one starts next week and the other one later in the month or early 2021.

That's pretty much it for the DAO.
 
#### Smart Yield
 
We had two competing models. Essentially those two models competed until one of them wore out and borrowed the best features from the other. So the smart contract development is moving along nicely with the winning model. Implementation should be done in time for the winter holidays. 

The UI being worked on by Denis— the largest emphasis of this being on UX and having the smoothest possible experience. Everystep of the way, getting a bit of hand holding, plenty of disclaimers along the way so you know what you are getting into.

The back end specs also being worked on at the same time, this will include the debut of the in app notification system. 

Also, two audits are booked for the smart yield, both kicking off in early 2021. 
 
#### Smart Alpha

Working the zero spec, if we could call it that. Almost completed, with major help from Atpar. There is a kicker to that— there will be two different smart alpha flavours getting worked on at the same time.

We are probably going to have to edit the whitepaper and all the docs out there to include both versions. You will get a feel for what those are soon.

Our plan is for at least two separate audits for Smart Alpha. We will announce more on that soon. 

There's an overall focus and very huge emphasis on security, we have a pretty large in-house team doing the internal reviews. Atpar has been helping a lot with external audits, with all of the biggest companies in the space to be honest. Double the audits for all of the products, the reports will be published, so you guys can take a look at them. The repos will be made public in due time.

A bug bounty program, Mark will talk more about later and some other interesting lines of defense that we are going to use to keep funds safe, which are all going to be announced later.
 
#### DeFi Standards
 *
 
#### Operations/Marketing Run down
 *
 
## Round Table
 *
