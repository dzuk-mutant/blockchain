# BLOCKchain (not that kind)

The space of decentralised social networking is relatively new territory, and while many of us who would otherwise face abuse on standard centralised social media services are enjoying our new found ability to define our own boundaries, it does not come without new risks and downsides.

While many of us came to Mastodon to set up more egalitarian social networks, there are also other people who are setting up their own spaces to share illegal content and hate.

<br/>

The recent turmoils of our traditional social networks and the wider internet have revealed to many the internet is not a neutral space. It is not something that automatically produces prosperous outcomes. We have to shape our technology to create the spaces and the kind of internet we want to see in our daily lives.

<br/>

BLOCKchain aims to address the unique issues presented by federated social networking by giving instances tools to understand, identify and push out hate and other social media threats through research and exposition.

---

**BLOCKchain is currently quite a fragmented project, in need of restructuring.**

**It's currently divided into two parts:**

- **Machine-readable** (this GitHub) - a JSON file you can use to automate blocking with scripts via [reasons](info/reasons.md) tags.
- **Human-readable** ([http://telegra.ph/Instances-to-silencesuspend-on-Mastodon-06-23](http://telegra.ph/Instances-to-silencesuspend-on-Mastodon-06-23)) - a frequently updated page that documents in detail what the instances on the list have done to be on the blocklist, complete with screen captures of some of their posts.


If you're new to this list and the kinds of instances that get blocked from Mastodon, I recommend you check the human-readable one first for all these instances first just so you know what you're doing and who you're blocking. I also try to explain what the reasons are below too because this JSON blocklist is structured a bit differently.

---

## Why blocklist?

In short...

- You want to keep illegal content (eg. child porn) off your servers.
- You want to promote healthy discussion and interactions between people that isn't poisoned by shitty, violent ideologies and dangerous conspiracy theories.
- You want your users to enjoy your instance and not have to worry about being harrassed or have shit flinged at them from people who don't know better.
- You want to defend the freedom of people to choose their pronouns, what religion they practice, how they want to represent themselves, who they want to have sex with, etc. etc. and to defend the right of these people to speak without fear of inane, hateful speech.
- You don't want to allow cults and hate groups to recruit vulnerable people.

Think of it as a spam filter for harassment, hate and illegal content.

This blocklist isn't prescriptive too. Each instance has a list of reasons of why you might want to block an instance for and you can take the action that is most appropriate for your instance.

Don't know how to identify hate speech? Don't worry! I've included links to many reputable resources that can help you understand in this readme and in the [reasons](info/reasons.md) section.

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

---

## FAQ

[There's an FAQ here](info/faq.md).

---


## Useful links

If you're interested in understanding hate groups, speech and rhetoric, here's a bunch of places that specialise in tracking these subjects.

Sorry that this is very anglophone-centric right now ¯\\\_(ツ)_/¯

**Also content warning! All of these are going to contain lots of unhappy things from the start!**

<br/>

#### [Southern Poverty Law Center](https://www.splcenter.org)

American hate group watch dog, anti-hate campaigner. They are also legal non-profit fighting hate, discrimination and threats to civil liberties. 

They have been meticulously tracking individual hate groups in the US meat space since 1990.

- [**Hatewatch**](https://www.splcenter.org/hatewatch): A blog with regular news about the happenings of American hate groups and well-established figures in these movements.

- [**Extremist Files - Ideologies**](https://www.splcenter.org/fighting-hate/extremist-files/ideology): Neat summaries of common/well-established hate ideologies they tend to encounter in their research and investigations.

<br/>

#### [Hope Not Hate](https://www.hopenothate.org.uk)

British hate group watchdog, and anti-racist political campaign group. They use a combination of standard research, undercover operatives and political counter-campaigning to fight hate groups in the UK.

- [**Blog**](https://www.hopenothate.org.uk/updates/blog/)

<br/>

#### [Hope Not Hate (US)](https://hopenothate.com) 

American branch of Hope Not Hate, focusing on the Alt-right.




- [**The International Alternative Right**](https://alternativeright.hopenothate.com): A special mini-site dedicated to the alt-right and alt-light. Featuring an extensive undercover investigation of many of their IRL meetings annd movements, which is in the process of being compiled into a documentary right now.

- [**Control Alt-Right Delete**](https://hopenothate.com/ctrl-alt-right-delete/) A weekly blog/newsletter dedicated to understanding how the alt-right works and developing strategies to fight back.

<br/>

#### [We Hunted The Mammoth](https://www.wehuntedthemammoth.com)

A blog tracking and exposing the commentary and ideological trends among the Male Supremacy/'Manosphere' movements, such as PUA, Red Pill, Incel, MGTOW and more.

<br/>

#### [Searchlight](http://www.searchlightmagazine.com)

A magazine investigating racism, fascism and antisemitism in Britain and elsewhere.

<br/>


#### [ShitRedditSays](https://www.reddit.com/r/ShitRedditSays/)

A Reddit community dedicated to showcasing the worst (re: bigoted, creepy, sexist, racist, homophobic, transphobic etc. etc. etc.) commentary across Reddit.

Contains more of a humorous tone compared to the other links, and the community is more of a venting place (not to say it diminishes it's quality, just that it's different in tone). An easy way to get an insight into the latest trends in typical anglophone internet hate speech discourse at a glance.

<br/>

#### [Right Wing Watch](http://www.rightwingwatch.org)

Blog dedicated to tracking far-right movements, figures and rhetoric in the US.