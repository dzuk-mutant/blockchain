# BLOCKchain (not that kind)

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
- You want to defend the freedom of people to choose their pronouns, what religion they practice, how they want to represent themselves, who they want to fuck and to defend the right of these people to speak without fear of inane, hateful bullshit.
- You don't want to allow cults and hate groups to recruit vulnerable people.

This blocklist isn't prescriptive too. Each instance has a list of reasons of why you might want to block an instance for and you can take the action that is most appropriate for your instance.

Don't know what a hate group is really like, or confused about which groups are hate groups? Don't worry! I've included links to many reputable resources that can help you understand in this readme.

---

## Updates

You can follow [@blockchain@monsterpit.net](https://monsterpit.net/@blockchain) for updates.


---

## Contributions

Feel free to contribute either here or on Mastodon via [@blockchain@monsterpit.net](https://monsterpit.net/@blockchain).

Unless it's really obvious how bad an instance is by looking at their front page, it's important that you bring evidence. Links are especially preferred becuase it means I can verify, archive and screencap them myself.

---

## Issues?

I was accepting issues on this GitHub, but there were too many people who either didn't care about why they were blocklisted and just wanted to poison the atmosphere or who weren't willing to actually directly address why they were blocked in the first place and I don't really have the time or energy to deal with that.

I made [an FAQ](http://telegra.ph/MastodonOStatus-Instance-Blocking-FAQ-06-24) a while back that tries to address some of the common issues some people have with blocklists. It doesn't necessarily cover everything, but it might help.

---

## Structure

So the blocklist is basically just one array with the instances in it.

Each instance has a URL and a list of [reasons](info/reasons.md) as to why they are on the blocklist. I'm not that much of a programmer, but I assume you can use those to filter which instances you want to block and how severe you want it to be.

---

## Reasons

Every instance has a list of reasons of why you might want to block them for. [Check this doc](info/reasons.md) for a list with detailed explanations.

