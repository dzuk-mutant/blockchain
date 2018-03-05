# Blockchain (not that kind)

If you're looking to score the latest in hot scam-tokens, sorry, I can't help you. 

This is a *chain of blocks*, specifically blocks for instances that federate with Mastodon instances, whether they are other Mastodon instances, or another kind of instance like GNUSocial, Pleroma, etc.

This is very new! Please check it out and help me iron out the bugs.

---

This is a brief, machine-readable version of my long and documented [human-readable version](http://telegra.ph/Instances-to-silencesuspend-on-Mastodon-06-23).

If you're new to this list and the kinds of instances that get blocked from Mastodon, I recommend you check the [human-readable one](http://telegra.ph/Instances-to-silencesuspend-on-Mastodon-06-23) for all these instances first just so you know what you're doing and who you're blocking. I also try to explain what the reasons are below  too because this JSON blocklist is structured a bit differently.

I'm not much of a programmer so I don't have any scripts to offer you that can automatically apply blocks on your Mastodon instance from this JSON file, but I assume it would probably be kind of simple to perform.

---

## Why blocklist?

In short...

- You want to keep illegal content (eg. child porn) off your servers.
- You want to promote healthy discussion and interactions between people that isn't poisoned by shitty, violent ideologies and dangerous conspiracy theories.
- You want your users to enjoy your instance and not have to worry about being harrassed or have shit flinged at them from people who don't know better.
- You want to defend the freedom of people to choose their pronouns, how they want to represent themselves, who they want to fuck and to defend the right of these people to speak without fear of inane, hateful bullshit.

---

## Updates

You can follow [@blockchain@monsterpit.net](https://monsterpit.net/@blockchain) for updates.

---

## Issues?

I will only be accepting issues if:

- There's a technical fault
- An instance is listed by mistake (ie. the reasons I thought they should be on the blocklist for are not accurate)

If you have a philosophical problem with this list, I don't personally have the energy to debate this and if you try, I will close the issue. 

I made [an FAQ](http://telegra.ph/MastodonOStatus-Instance-Blocking-FAQ-06-24) a while back that tries to address some of the common issues some people have with blocklists. It doesn't necessarily cover everything, but it might help.

---

## Structure

So the blocklist is basically just one array with the instances in it.

Each instance has a URL and a list of reasons as to why they are on the blocklist. I'm not that much of a programmer, but I assume you can use those to filter which instances you want to block and how severe you want it to be.


---


## Reason tags
These are the things that I personally have specific evidence of. These instances may be guilty of more things, but I'm only listing what I have to go by.

You can use reason tags to filter which instance you want to block and how badly you want to do it.

'A-' prefixes mean that the administration doesn't necessarily engage in, encourage, or endorse that behaviour themselves but they do enable it by letting other users on their instance do it instead. Not all tags have A-prefixes, I'll mention which ones do.


### advertising

Corporate advertising is enabled on this instance. There's a difference between personal and community announcements of things and straight-up corporate advertising. This is for the latter, not the former.

### bigotry

Here are some examples! Take your pick:

- racism
- homophobia
- anti-LGBTQ+++ [[link]](https://www.splcenter.org/fighting-hate/extremist-files/ideology/anti-lgbt)
- TERFs / fake goths [[link]](theterfs.com/) 
- anti-muslim bigoty [[link]](https://www.splcenter.org/fighting-hate/extremist-files/ideology/anti-muslim)
- ... probably way more!

I could be here all day listing these probably.

The reason I don't separate different kinds of bigotry is because it's extra work for no real purpose. One of these is bad enough, and if you're the kind of person to go 'well, I don't like people being mean to gays but I do think we should put all muslims on some kind of watch list' then this list isn't for you.

Maybe `FVZ` and `bigotry` will eventually be merged since they're both bigoted and while `FVZ` people actively advocate for harmful consequences and casual bigotry doesn't necessarily, bigoted behaviour *still has harmful real-world consequences*.


### harrassment (w/ A-harrassment)

The administration has engaged in, encouraged or endorsed harrassment, whether within OStatus/ActivityPub protocols, or elsewhere.

### corporate

Corporate-owned space.

(*Following text mostly copy-pasted from the [human-readable list](http://telegra.ph/Instances-to-silencesuspend-on-Mastodon-06-23)*)

This may not become a serious issue at the moment, but I think it could be a really important thing to keep an eye on for the future. I think that corporate ownership generally conflicts with the idea of social spaces as an emotionally supportive environment (how many of us left Twitter because it tolerates Nazis, doesn't have any real ethical or moral positions, and mines data?). 

They also conflict with the idea of intermingling, spaces with a cooperative relationship to each other (ie. our instances) - corporations expect to dominate 'markets', we provide services based on what we can afford to those who want and need them. I would say that our kind of social networking is potentially an existential threat to corporate social networking, and we shouldn't let them have an inch because they will take a mile. If they ever take an interest in decentralised social networking, they will only care about us insofar that we're good PR for them.

I'm not necessarily saying block these right now (I'm not apart from Pawoo, for other reasons), but I think keeping watch would be a good idea, especially if they become a thing in the West. They currently only seem to be a thing in Japan right now.


### FVZ (w/ A-FVZ)

Stands for **F**ascist speech / **V**iolent speech / **Z**ero-moderation. 

The instances with this tag usually claim to be defenders of free speech by limiting moderation, but really, these words are just a front. They are in fact safe spaces for hate groups and fascist and violent ideologies, including:

<br/>




- White Supremacy / White Nationalist [[link]](https://www.splcenter.org/fighting-hate/extremist-files/ideology/white-nationalist)
- Alt-Right ( [[link 1]](http://www.hopenothate.org.uk/2017/10/31/explained-identitarian-movement-alt-right/) [[link 2]](https://alternativeright.hopenothate.com/) [[link 3]](https://www.splcenter.org/fighting-hate/extremist-files/ideology/alt-right) )
- Alt-light [[link]](https://alternativeright.hopenothate.com/)
- Identitarian ( [[link 1]](https://www.splcenter.org/hatewatch/2015/10/12/american-racists-work-spread-%E2%80%98identitarian%E2%80%99-ideology) [[link 2]](http://www.hopenothate.org.uk/2017/10/31/explained-identitarian-movement-alt-right/) )
- Neo-Nazi [[link]](https://www.splcenter.org/fighting-hate/extremist-files/ideology/neo-nazi)
- Male Supremacy [[link that basically covers all the sub-groups below]](https://www.splcenter.org/fighting-hate/extremist-files/ideology/male-supremacy) 
	- Manosphere [[link]](http://www.hopenothate.org.uk/2017/10/24/hope-not-hate-explains-manosphere/)
	- The Red Pill
	- MRA / MRM
	- Pick-up Artistry (PUA)
	- MGTOW
	- Incel [[link]](https://rationalwiki.org/wiki/Manosphere_glossary#Incel)
- GamerGate [[link 1]](https://rationalwiki.org/wiki/Gamergate) [[link 2]](https://www.theguardian.com/technology/2014/oct/13/gamergate-right-wing-no-neutral-stance)
- Anti-LGBT [[link]](https://www.splcenter.org/fighting-hate/extremist-files/ideology/anti-lgbt)
- ...and probably even more awful shit! I will detail them later.

*(Links here are resources or definitions from experienced anti-hate group NGOs, sites that are experienced at documenting hate groups or journalistic sources. I'll keep trying to add links as I go along.)*




<br/>

The reason they are all in one category is that the borders between each other are very fuzzy (they have great ideological similarities), organisations in these areas tend to be tightly related and connected to each other and one particular branch is often a gateway to another.

Not even this categorisation is entirely neat - White Supremacy usually necessitates Male Supremacy and anti-LGBT (and probably even more).

Not all of these instances necessarily have all of these things, and there is a spectrum to the volume of this content. But this shit is still ultimately toxic and not what you should be allowing if you want to make your instance safe and pleasant for people who aren't violent and have reasonable things to say.

<br/>


Other people charitably call it 'channer culture' or call it by the way *they* frame it, which is ""free-speech zone"". I'd rather not label them on their own terms, especially when they don't actually give a shit about the free speech of women racial minorities, trans people, queer people, etc. (it can vary between the groups, but there's always at least one group who they would like to deprive the rights of).

<br/>

`A-FVZ` instances are often naive in what they say about this issue, believing that all forms of speech can coexist, even when some forms of speech (like hate speech), naturally inhibit or exclude other forms of speech. So even if they claim not to, they have sided with these awful people in what they are doing.


### jingoism

Oxford Dictionary:

> extreme patriotism, especially in the form of aggressive or warlike foreign policy

For the lack of a better term. This refers to just one instance right now, Counter.Social.

[Check out my human-readable blocklist](http://telegra.ph/Instances-to-silencesuspend-on-Mastodon-06-23) for the summary on them. They are *pretty bad*.

### lolicon

Sexualised depictions of minors.

While 'Lolicon' actually refers to a particular subset of illustrated child porn, westerners tend to use it to mean any illustrated child pornography, and I'm gonna use it that way because it's a really convenient label for a tag.

### privacy

This instance compromises it's users' own privacy in some way, like by adding Google Analytics to track their behaviour.


### spam

The administration enables spam accounts.

### tech-sleaze

Used to refer to hiveway.net currently, who have broken Mastodon's license and acted in a generally shitty way by basically making a fork of Mastodon with the serial numbers filed off and a new coat of paint.

Not the best tag, but tags aren't the best at nuance.

### untagged-NSFW

It is what it is really.

### unresponsive

Administration doesn't appear to be responsive to moderation messages.