# About labyrinth.social

labyrinth.social is a small Mastodon server for friends of Tom Dickinson, using the Hometown fork of Mastodon. 

## What is this?

Let's break that down into three different questions, increasingly granular as we go.

  1. **What is Mastodon?** 
  2. **What is Hometown?**
  3. **What is labyrinth.social?**

### What is Mastodon?

Mastodon is a social networking app. It's a little like Twitter, in that you make short posts and follow/reply to other users. But it's nothing like Twitter, in that it's open source, decentralized, and has no ads. 

If you don't understand what I'm talking about, I get it. It's a little hard to explain. But here are two pretty good explanations.

* A good, short video [video explaination](https://www.youtube.com/watch?v=IPSbNdBmWKE) from the official Mastodon youtube channel
* A better, longer [written explanation](https://www.nowwearealltom.com/what-is-mastodon/) by me

There are many Mastodon servers out there, all talking to one another. This is one of them.

### What is Hometown?

This server uses Hometown, an alternate version of Mastodon created by [Darius Kazemi](@https://friend.camp/@darius). Hometown has been altered to add some additional features that aren't in the main version of Mastodon. Yeah, you can do that! It's one of the cool things about open source software.

The most major differences are local-only posting, and exclusive lists. See [the Hometown wiki](https://github.com/hometown-fork/hometown/wiki) for more information on the project and how it differs from regular Mastodon.

### What is labyrinth.social?

Labyrinth.social is a deliberately small Hometown instance created by Tom Dickinson, for a few friends. Currently there are five active users. I intend to invite more people but I don't think there will ever be more than around 25.

An informal roadmap for the future of the project is maintained [here](roadmap.md).

The name "labyrinth" was chosen because it is an interesting image/word that has a lot of different resonances, Mythology, design, architecture, puzzles, David Bowie in very tight pants, etc. My direct inspiration for using it comes from Jorge Luis Borges' 1941 short story "[The Garden of Forking Paths](http://mycours.es/gamedesign2012/files/2012/08/The-Garden-of-Forking-Paths-Jorge-Luis-Borges-1941.pdf)", which is good and you should read it.


## Using labyrinth.social

### How do I join?

labyrinth.social is invite only, and limited to Tom Dickinson's friends. If you want to know moree about how I'm deciding who to invite, check out the [Invitation Policy](policy/invitation.md). The general gist is that I am only planning on inviting a small number of people I know pretty well. If that describes you and you're interested in joining, let me know!

That said, and you may already know this: even if you haven't joined labyrinth.social, you can still follow me and the other labyrinth.social users. All you need is an account on *any* Mastodon server. Actually there are some other kinds of servers that work too, but if you're new to all this then I recommend Mastodon.

If you're looking for some other server to join, skip to [this section in the middle of my "What is Mastodon?" post](https://www.nowwearealltom.com/what-is-mastodon/#09), which has some advice on how to find one to join

### Who is already using labyrinth.social?

As of this writing, five people including Tom. Plus an admin account which is just Tom again tbh. 

You can browse the [Profile Directory](https://labyrinth.social/explore) to see the users who have opted in to appearing in it. But not everybody necessarily has!

### Policies

Users are required to read, at minimum, the [Code of Conduct](policy/conduct.md). It is recommended that you read the other policy documents as well.

* **[Code of Conduct](policy/conduct.md)**: This document details the standards of behavior. Reading this is **mandatory** for all users of labyrinth.social.
* **[Terms of Service](policy/terms.md)**: This document contains general information about the operation of the service, including Admin rights, availability of service, and blacklisting/silencing of other instances. It's **highly recommended** that you read this.
* **[Privacy Policy](policy/privacy.md)** This document explains what kind of data is collected by labyrint-social, how it is used, and how it is protected. It's **highly recommended** that you read this.
* **[Invitation Policy](policy/invitation.md)**: This document provides some information about how I will decide whether or not to invite someone.

These are **not** just boilerplate documents, they are largely original documents written by me, so my goal is for them to be clear and readable. Although some of them do have some boilerplate language in them. 

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


### Moderated Servers

A list of moderated (silenced or suspended) servers can be found [here](https://labyrinth.social/about/more#unavailable-content).