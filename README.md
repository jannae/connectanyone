# Connecting Anyones [@ConnectAnyones](https://twitter.com/ConnectAnyones)

### It turns out a lot of people will talk to anyone. Let's bring them together.

Inspired by Steve Lambert's ["I will talk with anyone..." project](http://visitsteve.com/made/talkwithanyone/), I began to wonder how many people regularly express a desire to connect with others by casting such a large net into society to see who bites.

Turns out, quite a few people do.

### Initial Exploration / Process

I decided to use Twitter because it provides an easy, anonymous, recordable interface for meeting and interacting with strangers. At first, I decided to simply tweet at the universe to see what stuck. I decided to utilize current trending topics to cast a larger net than my own followers. 

<blockquote class="twitter-tweet" lang="en"><p>So what are you guys doing after this? <a href="https://twitter.com/hashtag/Drumline2?src=hash">#Drumline2</a></p>&mdash; jannae (@jannae79) <a href="https://twitter.com/jannae79/status/526931572608729090">October 28, 2014</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

I had very little success.

Next, I decided to try and find people that wanted to talk. I figured if I engaged on a personal level, it might spark conversation.

<blockquote class="twitter-tweet" lang="en"><p><a href="https://twitter.com/JamesIsGinger">@JamesIsGinger</a> was just twitter-searching for the meaning of life, actually. lay it on.</p>&mdash; jannae (@jannae79) <a href="https://twitter.com/jannae79/status/526940926711988224">October 28, 2014</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

Multiple attempts at this also had little success. I got a couple of followers, and a favorited tweet or two, but no responses. Hmmm.

Maybe I'm not as approachable or outgoing as I need to be. Maybe the people on twitter aren't either. 

### Current Exploration

I decided to experiment with taking a back seat and letting the people who actively ask to connect connect with others.

[@ConnectAnyones](https://twitter.com/ConnectAnyones) is a Twitter Bot I created to accomplish this.

**Full disclosure**: Currently the "bot" is just me. This is totally manual for a number of reasons which I will ideally be able to work out through code and launch as a real "connection" bot to live out in the wild.

The bot watches these search streams:

* ["I want to talk to anyone"](https://twitter.com/search?f=realtime&q=%22I%20want%20to%20talk%20to%20anyone%22&src=typd)
* ["I will talk to anyone"](https://twitter.com/search?f=realtime&q=%22I%20will%20talk%20to%20anyone%22&src=typd)
* ["I'll talk to anyone"](https://twitter.com/search?f=realtime&q=%22I%27ll%20talk%20to%20anyone%22&src=typd)
* ["I'd talk to anyone"](https://twitter.com/search?f=realtime&q=%22I%27d%20talk%20to%20anyone%22&src=typd)
* ["I want to talk to someone"](https://twitter.com/search?q=%22I%20want%20to%20talk%20to%20someone%22&src=typd)

When two people are discovered having tweeted any of these exact phrases within a reasonable time difference, they are matched together with the following tweet:

<blockquote class="twitter-tweet" lang="en"><p><a href="https://twitter.com/adhd79">@adhd79</a>, please meet <a href="https://twitter.com/JasmineCTate">@JasmineCTate</a>, you will both talk to anyone, perhaps you might like to talk to each other. :)</p>&mdash; Connecting Anyones (@ConnectAnyones) <a href="https://twitter.com/ConnectAnyones/status/527478095675412480">October 29, 2014</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>


### TODO / Project Goals

* Make this into an actual bot. 
* Bot will keep up with tweetIDs which have led to a connection in order to not connect people multiple times.
* Bot must recognize time difference between tweets so that we don't connect people who asked for contact more than 24 hours ago. (too much/little?)
* Follow people who have been connected. 
* Make lists based on tweet context (debatable)
* Maaaaybe let people tweet me asking to be connected, in which case they'd be added to a random pool available to be connected during some time frame they specify.... oooh. fancy.