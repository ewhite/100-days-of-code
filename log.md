# 100 Days Of Code - Log

### Day 0: Monday, January 6th, 2020

**Today's Progress**: Set up terminal and local development environment.
1. Created iTerm profile and customized to my hearts content. See 
[iterm view](./log-resources/iterm-setup.png) image if you are curious.
2. Updated Intellij to use the same settings.

**Thoughts:** Although it may not feel like much, it is really exciting to 
have a fully custom set up for the first time.

**Link to work:** [100 Days of Code homepage](https://github.com/ewhite/100-days-of-code)

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
