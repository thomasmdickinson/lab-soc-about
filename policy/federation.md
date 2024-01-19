# Federation Policy

See also:
* [About](../readme.md)
* [Terms of Service](terms.md)
* [Privacy Policy](privacy.md)
* [Invitation Policy](invitation.md)
* [Code of Conduct](conduct.md)

As described in the [Terms of Service](terms.md), I reserve the right to Silence or Suspend ("block") other fediverse instances at my discretion. Here are some further explanations for what that means, and how it works in practice.

## What is Federation?

Essentially, "federation" refers to the process by which this Hometown/Mastodon server interacts with other servers on the wider "fediverse." 

To quote Mastodon's own documentation: 

> Federation is a form of decentralization. Instead of a single central service that all people use, there are multiple services, that any number of people can use. A Mastodon website can operate alone. Just like a traditional website, people sign up on it, post messages, upload pictures and talk to each other. Unlike a traditional website, Mastodon websites can interoperate, letting their users communicate with each other; just like you can send an email from your Gmail account to someone from Outlook, Fastmail, Protonmail, or any other email provider, as long as you know their email address, you can mention or message anyone on any website using their address.


## What is Defederation?

The term "defederation" describes a number of measures that admins can take to restrict 
or block another instance from interacting with their instance. This is commonly done 
to provide a better experience for users by blocking instances run by bad actors, with
lax moderation policies, or that they prefer not to interact with for any number of 
other reasons.

Here are some of the actions I am able to take as the admin to limit entire instances 
from interacting with labyrinth.social.

**"Suspending"** an instance (also referred to as **Blocking**) prevents that instance
and its users from interacting with labyrinth.social in any way. Users from labyrinth.social
and that suspended service can't follow one another, and posts from that service can't be 
viewed via labyrinth.social (and vice versa).

**"Silencing"** an instance (also referred to as **Limiting**) is a less severe form of
defederation. It prevents posts from users on that instance from appearing in the public 
timeline visible on labyrinth.social (which also means those posts will not be visible in 
search results for hashtags). However, it does not prevent users of labyrinth.social from
following or being followed by users of that instance or accessing posts from that instance
in the labyrinth.social interface.

**Rejecting Media** is an additional step that can be taken, for a Silenced server, to prevent
the images posted by users of that server from ever being delivered to or processed by labyrinth.social.

If you're a logged in user of labyrinth.social, you can click
[here](https://labyrinth.social/about/more#unavailable-content) to see a list of all 
instances which have been subject to any of the aforementioned moderation actions. 
The list of moderated servers is not publicly available to non-users, but information 
may be available by request.

## Defederation Decisions

In order to provide the best possible experience for labyrinth.social, I periodically 
review the #FediBlock hashtag, which fediverse admins use to share recommendations of 
servers that other admins may wish to suspend or block. I also occasionally review a 
number of other publicly available resources which list recommendations for server 
blocks.

However, despite using these sources for convenience's sake, labyrinth.social does 
not currently have any sort of automated subscription to an external blocklist, which 
means decisions are made on a case by case basis at the admin's discretion. 

In most cases the decision to block is fairly easy. I often **Suspend** an instance 
if that instance meets any of the following conditions:

- The instance has no moderation policy, or a moderation policy that allows for hate speech and harassment
- The instance allows or encourages illegal material
- The instance has been cited by many other fediverse admins as a vector for harassment and abuse
- The instance is widely used to send automated spam or unsolicited advertising messages

In these cases, I do a quick check to ensure that there are no existing follow 
relationships between labyrinth.social users and users from those instances that 
I would be disrupting by suspending that instance. There virtually never are, but if 
there were, it would be reason to further the block, or to check in with the impacted 
users on labyrinth.social. Otherwise, I simply suspend without seeking further imput 
from the community or making any announcement.

I use the **Silence** feature more infrequently; Usually if an instance is causing problems 
then I will simply suspend it. However, sometimes large instances are not well moderated, 
and in these cases it may be useful to Silence the instance without severing follow relationships. 

Occasionally, an instance may silenced or suspended on a temporary basis, if a situation 
is unfolding on that instance which is resulting in problematic behavior (usually automated 
spam messages). This has happened a few times. These temporary actions are always announced via
the @admin account.

## Reversal of Defederation Decisions

Users of labyrinth.social are of course welcome to inquire about any defederation decisions 
and request a reversal. This has never happened, but if it ever does, I will make the decision
after seeking input from the community. 

Users or admins of other instances who have been suspended are welcome to contact the 
admin to "appeal" the decision to defederate, but should not expect me to consider whether
the decision to defederate was "fair" to their users. My goal is to provide the best possible
experience for myself and the other labyrinth.social users, not to ensure that external parties
are given "fair" access to the labyrinth.social users.

If a previous defederation decision is ever reversed, such a decision will be announced in advance
via the @admin account.

## Large Server Decisions

The decision to defederate from an instance used by, say, a dozen nazis, is fairly simple. 
When considering a larger server, say, one with 100,000 users or more, whose primary problem
is lax moderation, the decision is often more complicated. 

For example, take the example of [mastodon.social](https://mastodon.social), the largest and
most popular Mastodon instance. Naturally, it hosts many accounts that are of interest to 
labyrinth.social users. However, its moderation is not always satisfactory, and for that reason,
some instance admins have chosen to suspend federation with it. This is something labyrinth.social
does not currently intend to do, after weighing the risks of misconduct from that server 
against the fact the interests labyrinth.social's users have in that server's users.

As a counter example, take [threads.net](http://threads.net), the fediverse project created by
the tech company Meta. A vocal contingent of fediverse admins have suspended federation with threads
for a number of reasons, including privacy, content moderation, mistrust of Meta, and lack of interest
in the content posted there. In contrast to the decision we made with mastodon.social, labyrinth.social
has decided not to federate with Threads.

Both of the above decisions were made in consultation with the labyrinth.social users via the [@admin](https://labyrinth.social/@admin), and both are subject to change in the future. As a
general rule, decisions relating to federation with large servers will be made that same way,
with community input, although I reserve the right to make the final decision myself.