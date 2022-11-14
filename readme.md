# About labyrinth.social

labyrinth.social is a small Mastodon instance for friends of Tom Dickinson, using the Hometown fork of Mastodon. 

## What is this?

Let's answer that at three differenty levels of granularity.

### What is Mastodon?

To answer this, here is:

* A good, short video [video explaination](https://www.youtube.com/watch?v=IPSbNdBmWKE) from the official Mastodon youtube channel
* A better, longer [written explanation](https://www.nowwearealltom.com/what-is-mastodon/) by me

### What is Hometown?

This server uses Hometown, an alternate version Mastodon by [Darius Kazemi](@https://friend.camp/@darius). Hometown has been altered to add some additional features that aren't in the main version of Mastodon. The most major differences are local-only posting, and exclusive lists. See [the Hometown wiki](https://github.com/hometown-fork/hometown/wiki) for more information on the project and how it differs from regular Mastodon.

### What is labyrinth.social?

Labyrinth.social is a deliberately small Hometown instance created by Tom Dickinson, for a few friends. Currently there are five active users. I intend to invite more people but I don't think there will ever be more than around 25.

A roadmap for the future of the project is maintained [here](roadmap.md).

The name "labyrinth" was chosen because it is an interesting image/word that has a lot of different resonances, Mythology, design, architecture, puzzles, David Bowie in very tight pants, etc. My direct inspiration for using it comes from Jorge Luis Borges' 1941 short story "[The Garden of Forking Paths](http://mycours.es/gamedesign2012/files/2012/08/The-Garden-of-Forking-Paths-Jorge-Luis-Borges-1941.pdf)", which is good and you should read it.




## Using labyrinth.social

### How do I join?

labyrinth.social is invite only, and limited to Tom Dickinson's friends. If you're interested, reach out to Tom.

You don't have to have an account on labyrinth.social in order to follow and interact with users on this server. An account on any Mastodon server will work (and some other kinds of servers will work too!) You may want to refer to my post [What is Mastodon? Why is Mastodon? How is Mastodon](https://www.nowwearealltom.com/what-is-mastodon/) to find out more about how this works and how to pick another server you can join.

### Policies

Users are required to read, at minimum, the [Code of Conduct](policy/conduct.md). It is recommended that you read the other policy documents as well.

* **[Code of Conduct](policy/conduct.md)**: This document details the standards of behavior. Reading this is **mandatory** for all users of labyrinth.social.
* **[Terms of Service](policy/terms.md)**: This document contains general information about the operation of the service, including Admin rights, availability of service, and blacklisting/silencing of other instances. It's **highly recommended** that you read this.
* **[Privacy Policy](policy/privacy.md)** This document explains what kind of data is collected by labyrint-social, how it is used, and how it is protected. It's **highly recommended** that you read this.
* **[Invitation Policy](policy/invitation.md)**: This document provides some information about how I will decide whether or not to invite someone.

Any significant updates to any of these policies will be announced from the [@admin@labyrinth.social](https://labyrinth.social/@admin) account.

### Local-Only Posting

One of the most important differences between Hometown and vanilla Mastodon is the ability to use Local Only posting. In the context of Hometown, local only posting is a per-post security option that lets you set whether that post can federate out to other servers or not.

A full explanation of the feature can be found on the [the Hometown wiki](https://github.com/hometown-fork/hometown/wiki/Local-only-posting).

#### How to post a Local-Only post from the web

When posting with the web interface on labyrinth.social, you will see an icon next to the CW dropdown that looks like a chain link, either unbroken (for federated) or broken (for local-only). On each post you make, you can set whether it's local or not.

![Screenshot of someone clicking the 'link' icon on the compose interface, with a drop down that offers 'federated' and 'local-only' options.](https://camo.githubusercontent.com/f7dfd141bfa4e2302eb77b571b671efc64cdd0e73b3749fe23c9988505b98cfb/68747470733a2f2f74696e7973756276657273696f6e732e636f6d2f706963732f686f6d65746f776e2d6c6f63616c2e706e67)

#### How to post a Local-Only post from an app

If you use an third-party app to post, there is unlikely to be a menu option for local-only posting, since apps have not generally added this functionality. Therefore, users can also tag their posts as "local only" by using the :local\_only: emoji,
which looks like this:
<img
  src="https://labyrinth.social/system/custom_emojis/images/000/008/282/static/aeeb24f12d632bd6.png"
  alt=":local_only:" title=":local_only:"
  style="vertical-align: middle; -o-object-fit: contain; object-fit: contain;
         margin: -.2ex .15em .2ex; width: 16px; height: 16px;"
/>
You can also just type ":local\_only:" in your toot, colons included. That works as well. It even works on the web too, if you don't want to use the broken chain icon.

#### How to tell if a post in your timeline is local-only

A local-only post will appear in your timeline with the broken chain icon on it:

![Screenshot of the home timeline with a local post on it bearing the 'broken chain' icon.](https://camo.githubusercontent.com/96e40a539849d5cd7f18884e233a1d69fb7bc746d3a7fc577fbf76518906b2c0/68747470733a2f2f74696e7973756276657273696f6e732e636f6d2f706963732f686f6d65746f776e2d6c6f63616c2d322e706e67)

It also may have the above mentioned emoji in the post. But just because it *doesn't* have the emoji doesn't mean it *isn't* local-only.

#### Posting local-only by default

In your Preferences menu, under "Other", there is an option that says "Allow my toots to reach other instances by default". This is checked by default, which means your posts are normally federated if you don't touch any of the per-post settings. If you uncheck this, then your posts are normally local and you must make an effort to federate your content on each post using the per-post toggle shown above.

If you use a third-party app, your posts should still abide by these defaults. More info can be found on the [Hometown wiki](https://github.com/hometown-fork/hometown/wiki/Local-only-posting#sensible-defaults).

### Emoji

This instance uses <a href='https://mutant.tech'>Mutant Standard emoji</a>,
which are licensed under a
<a href='https://creativecommons.org/licenses/by-nc-sa/4.0/'>Creative Commons
Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

For the moment, I have chosen to add only a small subset of these emoji, most
notably the custom flags and symbols from their Gender, Sexuality, and
Relationships category. Other emojis from that set (or any other source) can be
added by request to the admin.
