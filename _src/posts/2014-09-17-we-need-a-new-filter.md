    Title: We need a new filter
    Date: 2014-09-17T10:43:53
    Tags: Racket, abuse

In the wake of recent events in the gaming sphere, I've been thinking a good hard think. Harassment on the internet is becoming a major societal problem. People's lives are being threatened. Women are bombarded with abuse on an unconscionable scale. Something needs to be done: we can talk until we're blue in the face about why sending someone violent threats and harassment is wrong, but the harassers aren't listening.

What we need, is an abuse filter. 

<!-- more -->
Since the public birth of the internet, millions, possibly even billions of dollars have been spent in pursuit of building a better spam filter. Countless man-hours have been dedicated to finding new ways of identifying and properly filing away to /dev/null the endless torrent of garbage emails about Viagra and Nigerian princes.

And yet, where are the millions spent on solutions for internet harassment? The countless man-or-woman-hours poured into making life on the internet less an endless free-fire zone for abusive sociopaths?

Most existing social media systems rely entirely on user reporting, essentially leaving it to the user to manually report and block each and every abusive message. This is about as ludicrous a task to demand as it would be for spam. Especially for those targeted by concerted campaigns like #gamergate/#quinnspiracy, this is more or less an intractable problem. Props aplenty for the courage of women like Zoe Quinn and Anita Sarkeesian who've stuck it out and even done that work, but they never should've had to do it in the first place, and many choose simply to leave rather than deal with it. Some very talented women and men alike have literally quit gaming entirely over this kind of harassment, and similar incidents have occured elsewhere in any number of fields.

What we need is something that takes the burden of policing one's own timelines and inboxes off of the user, just as spam filters do for advertising and scams.

But there's an important difference here: ignoring spam has little consequence. Ignoring violent threats can be dangerous, and even ignoring mundane harassment often sends the message that such behavior is itself without consequence.

Thus unlike a spam filter which simply consigns a useless message to a dustbin, an abuse filter would need to properly file and report abusive and threatening messages, possibly even for reporting to legal authorities. It needs to be smart enough to know not just what an abusive message is, but what to *do* about it.

This also would require some cooperation from service providers, however, not all of which even provide such avenues. A Twitter client, for instance, would need to be able to report a user as abusive, yet the Twitter APIs, that I can see, do not appear to support reporting a user for abuse, only for spam.

I am just one guy, a relative amateur at that. This is a large problem that will require brilliant minds, lots of man hours, and probably more resources than I have at my disposal. But that doesn't mean I can't get it started. I intend to take a crack at developing a simple filtering engine to file and classify abusive messages given the pair of an identifying username and the text of the message. I'll be doing it in Racket, because I think the tools Racket offers for parsing might offer some clever avenues for solutions to such problems.

It's likely to be unimpressive, and it's likely to bring grumbles about the choice of language, the simplicity of the model, and on and on. That's the point. Consider it my challenge. A first effort to get the ball rolling, with the tacit expectation that you indeed can do better: so prove it.

Work begins soon, announcements and github repo pending. Let's help make the internet a better place to be.
