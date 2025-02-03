<!--[title|A status update: what i've been working on]-->
<!--[description|Hardware, software and the future]-->
<!--[author|Lena]-->
<!--[timestamp|1738615699]-->
<!--[tag|status]-->
<!--[tag|hardware]-->
<!--[tag|software]-->
<!--[tag|OpenBikeComputer]-->

It's been a while since i wrote my last blog post, and i must say i'm sorry for not writing more, even when i really really wanted to.

These past few months have had a LOT happen, (and those of you who follow me on [fedi](https://social.treehouse.systems/@lena) already know), i've not been idle.

In fact, i've worked on a lot of stuff, from writing (and almost upstreaming) a linux driver, to writing an (incomplete) [UnifiedPush](https://unifiedpush.org) distributor server that is lightning fast and efficient, to lots of various patches and things i can't remember or am not allowed to tell about just yet.

On the hardware side, i've started OpenBikeComputer, an attempt to bring my autistic data-analysis problem to yet another thing i enjoy (cycling), and i'm having lots of fun designing it, although i'll soon dread the amount of 0402 (and 0201) hand soldering it'll need (for anyone who doesn't know, they're 0.6x0.3mm), all crammed onto a tiny circuit board. Lots of fun nonetheless.

I've also been trying to arrange things to self host everything on my own hardware, but that'll take a long time before i actually get there.

But the reason why i haven't been writing in here for a while, is that everything i've been talking about is unfinished. And i generally don't feel like unfinished stuff is deserving of a spot here.

I do generally have pretty high standards for myself, and while this means i don't like putting out unfinished stuff, i also don't want to leave this space empty.

## Moving forward

From now on, i'll try to write smaller bits about things i find and do in my daily life, as opposed to the tight wall of technical text (which will still be a thing though!).

I also want to try posting monthly updates on things i'm working on, and the challenges i face when doing this.

Oh, i also need to finish this blog (e.g. the links section is unimplemented at the moment, and i want to make a proper compliant Atom feed (as opposed to the regular [RSS feed](https://lena.nihil.gay/blog/rss.xml) which already exists - and you should use -)

Also, i'll try to finally add filtering posts by tag and lots of other goodies (and yes, still working and looking good in new, old, fun, quirky web browsers and screen readers)

## Let's start here

The last few weeks i've been working on mostly on OpenBikeComputer, mostly still going after the excitement i first had when the idea came up to me.

I like cycling. A lot, actually. I also like knowing mostly useless information about things. Why not combine the two?

Obviously the featureset must be greater than any old piece of junk you can get on amazon, so obviously:

- speed
- trip distance
- acceleration

But also non-trivial stuff, such as:

- slope
- energy
- braking power

and a bunch of other physics-adjacent values you absolutely didn't need to know about your bike.

It should also be able to turn on/off any bike lights or any other device you may have, should be able to interact with other bike sensors you may have, be easily expandable, be able to control the media playing on your phone, and many other small things.

Is this feature creep?

Yes.

Do i care?

No. Apart from losing my sanity, that is. But i'm merely at the hardware, so that'll be a problem for Future Me.

Anyway, all the hardware files are hosted [here](https://github.com/adryzz/OpenBikeComputer), currently working on the rev2 branch on a new board layout.

Anyway, i'm super excited to finally get a hardware project working, and i'll see you in the next blog post, which will hopefully be pretty soon.

Thanks for listening to my incoherent ramblings, yet again.
