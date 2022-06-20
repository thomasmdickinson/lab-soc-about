# About labyrinth.social

labyrinth.social is a small Mastodon instance for friends of Tom Dickinson. If you are not familiar with Mastodon, this [video explainer](https://www.youtube.com/watch?v=IPSbNdBmWKE) gives you a good basic explanation of what it is.

This server uses Hometown, a fork of Mastodon that has been altered to add some
additional features. See
[the Hometown wiki](https://github.com/hometown-fork/hometown/wiki) for more information on the project and how it differs from regular Mastodon.

## Policies

Users are required to read, at minimum, the [Code of Conduct](policy/conduct.md). It is recommended that you read the other policy documents as well.

* [Code of Conduct](policy/conduct.md)
* [Terms of Service](policy/terms.md)
* [Privacy Policy](policy/privacy.md)
* [Invitation Policy](policy/invitation.md)

## Project Background

### Why does this server exist?

I'll write more about this in the future. My rationale is partially described
in [this thread](https://mastodon.cloud/@nowwearealltom/108193926000733916) and
there is a great [guide by Darius Kazemi](https://runyourown.social) about
running your own social network which overlaps with my thinking in some key
ways. Kazemi is also the creator and maintainer of Hometown (which is the
"fork", or variant, of Mastodon that this server uses).

### Why "Labyrinth?"

It's an interesting image/word that has a lot of different resonances.
Mythology, design, architecture, puzzles, David Bowie in very tight pants, etc

My direct inspiration for using it comes from Jorge Luis Borges' 1941 short
story "[The Garden of Forking Paths](http://mycours.es/gamedesign2012/files/2012/08/The-Garden-of-Forking-Paths-Jorge-Luis-Borges-1941.pdf)"
which is good and you should read it.

But that alone wouldn't have made it a very good name. Not everyone has read
Borges and not everyone will. I wanted to pick something that could mean
different things to different people, or just mean nothing at all and be kind of
a regular word.

So, Labyrinth. Labyrinth social. "lab-soc" for short. You can pronounce it
"lab-sosh" or "lab-sock" or "lab-sose" or "lab-sauce" or make up your own.

### Roadmap

A roadmap for the project is maintained [here](roadmap.md).

## Using labyrinth.social

### How do I join?

labyrinth.social is invite only, and limited to Tom Dickinson's friends. If you're interested, reach out to Tom.

### Local-Only Posting

One of the most important differences between Hometown and vanilla Mastodon is the ability to use Local Only posting. In the context of Hometown, local only posting is a per-post security option that lets you set whether that post can federate out to other servers or not.

A full explanation of the feature can be found on the [the Hometown wiki](https://github.com/hometown-fork/hometown/wiki/Local-only-posting).

When posting with the web interface on labyrinth.social, you will see an icon next to the CW dropdown that looks like a chain link, either unbroken (for federated) or broken (for local-only). On each post you make, you can set whether it's local or not.

![Screenshot of someone clicking the 'link' icon on the compose interface, with a drop down that offers 'federated' and 'local-only' options.](https://camo.githubusercontent.com/f7dfd141bfa4e2302eb77b571b671efc64cdd0e73b3749fe23c9988505b98cfb/68747470733a2f2f74696e7973756276657273696f6e732e636f6d2f706963732f686f6d65746f776e2d6c6f63616c2e706e67)

A local-only post will appear in your timeline with the broken chain icon on it:

![Screenshot of the home timeline with a local post on it bearing the 'broken chain' icon.](https://camo.githubusercontent.com/96e40a539849d5cd7f18884e233a1d69fb7bc746d3a7fc577fbf76518906b2c0/68747470733a2f2f74696e7973756276657273696f6e732e636f6d2f706963732f686f6d65746f776e2d6c6f63616c2d322e706e67)

In your Preferences menu, under "Other", there is an option that says "Allow my toots to reach other instances by default". This is checked by default, which means your posts are normally federated if you don't touch any of the per-post settings. If you uncheck this, then your posts are normally local and you must make an effort to federate your content on each post using the per-post toggle shown above.

Users can tag their posts as "local only" by using the :local\_only: emoji,
which looks like this:
<img
  src="https://labyrinth.social/system/custom_emojis/images/000/008/282/static/aeeb24f12d632bd6.png"
  alt=":local_only:" title=":local_only:"
  style="vertical-align: middle; -o-object-fit: contain; object-fit: contain;
         margin: -.2ex .15em .2ex; width: 16px; height: 16px;"
/>
You can also just type ":local\_only:" in your toot, colons included.
That works as well.

### Emoji

This instance uses <a href='https://mutant.tech'>Mutant Standard emoji</a>,
which are licensed under a
<a href='https://creativecommons.org/licenses/by-nc-sa/4.0/'>Creative Commons
Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

For the moment, I have chosen to add only a small subset of these emoji, most
notably the custom flags and symbols from their Gender, Sexuality, and
Relationships category. Other emojis from that set (or any other source) can be
added by request to the admin.
