# 100 Days Of Code - Log

### Day 1: Monday, January 27, 2020

**Today's Progress:** I formalized the code I currently have 
which is calling the metro api and began the process of abstracting
away the details of that API. I also selected a license, added the
project to github, and did some quality of life improvements 
on the project itself.

**Goals for tomorrow:**
1. I'd still like to get the code running on a websocket.
2. I'd like to have the details of my first bus stop & route
hard-coded in (e.g. route: "number 2", stop: "112") so I have
something with which to get started.

### Day 0: Wednesday, January 22, 2020
**Today's Progress**: Today I spent the entire day sleuthing around
the Omaha Metro Bus Tracker website. I'm glad to report that I was
able to find (and immediately) profit from their API calls. Now
that I've determined they have no security and also no session,
I have verified that my dream of having my phone buzz when the bus
is on the way could _actually_ happen.


**Thoughts:** This was my first reverse-engineering of an API that
I've done by myself. I was inspired by the Personal Capital 
API that I found for my first HDOC failure below. That said,
this looks way easier than that one looks.

**Goals for tomorrow:**
1. Get first draft of websocket created which can push updates
for the #2 bus line to consumers.

### First attempt below

### Day 3: Thursday, January 9th, 2020
**Today's Progress**: Today was split between learning more about 
Google Cloud Functions/Firebase/Dialogflow and between some actual
coding/API sniffing for Personal Capital. Since I've decided to 
attempt creating an interaction which can check your Personal Capital
account balance for you, I spent some time examining the network 
traffic on their site. I am painstakingly translating what I see there
into Javascript code. I have completed about 1/2 of the login flow 
currently.

**Notes:** 
1. I'm not doing the above task alone. I found a 
[Github repo](https://github.com/haochi/personalcapital) that has
been an _amazing_ starting point. 

**Thoughts:** I am enjoying learning more about Google's cloud suite.
It's nice to see a contrasting approach to Docker, and Firebase's 
ability to run `firebase deploy` and have everything just work is
super cool for rapid pace development like this project. Cracking 
Personal Capital's API is a new experience for me, and at least for 
now I think it is going well.

**Goals for tomorrow:**
1. Get an integration test up and running for the Personal Capital 
API object that I'm building.

2. Test log in flow for hardcoded username and password.

**Links to work:** 

[100 Days of Code homepage](https://github.com/ewhite/100-days-of-code)

[dialogflow-fulfillment](https://github.com/ewhite/dialogflow-fulfillment)

### Day 2: Wednesday, January 8th, 2020
**Today's Progress**: Got my first custom Google assistant intent &
response functioning in a test envnironment! 

Currently, you can say "hello test api", and it will say back 
"Welcom to a different agent!". Yes, you read that right. Apparently, 
even my "test to see if changes get persisted" code has typos. 
Very on-brand, that.

**Notes:** 
1. In the process of figuring out the above, I ended up going with a 
simpler example I found. As a result, I've deleted the aforementioned
`smart-home-nodejs-repo` project and the body of my code now resides in 
`dialogflow-fulfillment`. Pretty uninspired name. Maybe I'll change it.

2. I'm switching the order of these log messages today so that the 
latest is always visible at the top. Just seems more readable that way.

**Thoughts:** I'm feeling really good this evening. I'm excited to have
been able to successfully deploy a function using Firebase, and then have
that function field requests from Google's Dialogflow (the service that 
Google uses to parse user intent and pass it along to APIs like my
function). I even noticed a dirt simple way to deploy a static hosted 
website on Firebase as I did the tutorials. May be something I should 
revisit if one of the other 1 billion solutions to this problem doesn't
catch my attention first.

**Goals for tomorrow:**
1. Learn more about Dialogflow and it's ability to decipher user intent.

2. Pick a functionality that I'd like my Google action to be able to do.
Current idea is an automated way to check my PersonalCapital account
balances/trends since I do that often.

**Links to work:** 

[100 Days of Code homepage](https://github.com/ewhite/100-days-of-code)

[dialogflow-fulfillment](https://github.com/ewhite/dialogflow-fulfillment)


### Day 1: Tuesday, January 7th, 2020
**Today's Progress**: Researched Google Home API and Google Actions API. 
Forked and tried (and failed) to get some prebuilt Smart Home actions 
running.

**Thoughts:** There is a lot involved in Google's deployment 
infrastructure. The whole Google Cloud Suite is unfamiliar to me, and 
although I had hoped to accomplish more today, I'm beginning to realize
that using this new stack will consume a not insignificant portion of
my time. We'll see, I suppose. I'm eager to do some actual coding.

**Goals for tomorrow:**
1. Either get something working with the prebuilt smart home actions or
create a minimal setup of my own talking with Google's servers.

**Links to work:** 

[100 Days of Code homepage](https://github.com/ewhite/100-days-of-code)

[smart-home-nodejs repo](https://github.com/ewhite/smart-home-nodejs)

### Day 0: Monday, January 6th, 2020

**Today's Progress**: Set up terminal and local development environment.
1. Created iTerm profile and customized to my hearts content. See 
[iterm view](./log-resources/iterm-setup.png) image if you are curious.
2. Updated Intellij to use the same settings.

**Thoughts:** Although it may not feel like much, it is really exciting to 
have a fully custom set up for the first time.

**Link to work:** [100 Days of Code homepage](https://github.com/ewhite/100-days-of-code)
