# Local-Only Posting

As mentioned on the [about page/readme](readme.md), labyrinth-social is on an alternate version of Mastodon called Hometown. One of the most important differences between Hometown and vanilla Mastodon is the ability to use Local Only posting. In the context of Hometown, local only posting is a per-post security option that lets you set whether that post can federate out to other servers or not.

A full explanation of the feature can be found on the [the Hometown wiki](https://github.com/hometown-fork/hometown/wiki/Local-only-posting).

## How to post a Local-Only post from the web

When posting with the web interface on labyrinth.social, you will see an icon next to the CW dropdown that looks like a chain link, either unbroken (for federated) or broken (for local-only). On each post you make, you can set whether it's local or not.

![Screenshot of someone clicking the 'link' icon on the compose interface, with a drop down that offers 'federated' and 'local-only' options.](https://camo.githubusercontent.com/f7dfd141bfa4e2302eb77b571b671efc64cdd0e73b3749fe23c9988505b98cfb/68747470733a2f2f74696e7973756276657273696f6e732e636f6d2f706963732f686f6d65746f776e2d6c6f63616c2e706e67)

## How to post a Local-Only post from an app

If you use an third-party app to post, there is unlikely to be a menu option for local-only posting, since apps have not generally added this functionality. Therefore, users can also tag their posts as "local only" by using the :local\_only: emoji,
which looks like this:
<img
  src="https://labyrinth.social/system/custom_emojis/images/000/008/282/static/aeeb24f12d632bd6.png"
  alt=":local_only:" title=":local_only:"
  style="vertical-align: middle; -o-object-fit: contain; object-fit: contain;
         margin: -.2ex .15em .2ex; width: 16px; height: 16px;"
/>
You can also just type ":local\_only:" in your toot, colons included. That works as well. It even works on the web too, if you don't want to use the broken chain icon.

## How to tell if a post in your timeline is local-only

A local-only post will appear in your timeline with the broken chain icon on it:

![Screenshot of the home timeline with a local post on it bearing the 'broken chain' icon.](https://camo.githubusercontent.com/96e40a539849d5cd7f18884e233a1d69fb7bc746d3a7fc577fbf76518906b2c0/68747470733a2f2f74696e7973756276657273696f6e732e636f6d2f706963732f686f6d65746f776e2d6c6f63616c2d322e706e67)

It also may have the above mentioned emoji in the post. But just because it *doesn't* have the emoji doesn't mean it *isn't* local-only.

## Posting local-only by default

In your Preferences menu, under "Other", there is an option that says "Allow my toots to reach other instances by default". This is checked by default, which means your posts are normally federated if you don't touch any of the per-post settings. If you uncheck this, then your posts are normally local and you must make an effort to federate your content on each post using the per-post toggle shown above.

If you use a third-party app, your posts should still abide by these defaults. More info can be found on the [Hometown wiki](https://github.com/hometown-fork/hometown/wiki/Local-only-posting#sensible-defaults).