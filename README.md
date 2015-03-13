# What the duece is Fingr?
Fingr is a Camping mini-app that Web 2.0-ifies Finger.

In other words, it takes something that works just fine and makes it kinda lame :).

The idea is that you can create a jabber account and link it to your Fingr install, send messages to said jabber account and VOILA! They appear as though by magic in your browser.

# I liked this better when it was called Twitter!
Yeah, I know. In fact, it uses xmpp4r-simple, which was written by the Twitter folks. Think of Fingr as an anti-social version of Twitter: it's for you and you alone, unless you choose to share the URL.

# How?
Well, like I said before, it uses Camping and xmpp4r-simple. By association, it requires Ruby. It also needs rss/maker, but I think that's included with the price of Ruby.

All in all, it's pretty simple. Copy config.yml.sample over to config.yml, enter the proper info and start it up:

    camping fingr.rb

By default, it'll start up on port 3301. If you want it to run somewhere else, just drop the --port option on it:

    camping --port 1234 fingr.rb

# Where's the Screenshots, man?
Sorry, but I aint gots no time for screenshots, fool.

Goodbye and good luck!
