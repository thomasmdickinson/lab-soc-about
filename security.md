Privacy and Security
====================

As I work toward eventually "launching" lab-soc (by inviting users), I have been
thinking about privacy and security. I will want to write something formal, but
for now here are some scattered notes.

Something I want to point out up front is that we don't usually consider uptime
or longevity of service as "security" considerations, but they are. I took a
grad school course on cybersecurity and they told me that the three pillars of
cybersecurity are Privacy, Integrity, and Availability, and grad school cant be
wrong. So these notes talk not just about privacy but also about availability
of service.

I Only Kind of Know What I'm Doing
----------------------------------

I will admit that I am a hobbyist, not a professional sysadmin. I only kind of
know what I am doing here. The design of the platform makes it unlikely that I
will, through incompetence, make your private data available, but it does leave
some possibility that it could accidentally be destroyed in whole or in part, or
rendered temporarily inaccessible because of unexpected downtime. I don't think
this will happen, and the linode server running this instance is periodically
backed up, but I'm just one guy and this is an experimental hobby project for
me so I ask you to bear in mind that it may not work out perfectly.

Do You Trust Me?
----------------

Usually when you sign up for a big corporate platform, you don't have to worry
about any particular individual person there being a threat to your privacy.
With a small social network hosted by someone you personally know, you do have
to worry about that.

For instance, whatever social platform you are using, a person with sufficiently
high levels of access can, in theory, read your DMs (unless they are end-to-end
encrypted, and on most platforms they are not). This isn't usually something you
worry about with, say, Twitter. I think this is because of a "security through
obscurity" principle, where it's presumed that nobody at the company cares
enough about you personally to violate your privacy in that way. (They are busy
violating your privacy en masse in other ways.) That's not something you can be
assured of when signing up to a social network run by someone you know.

Basically you have to decide how much you trust me not to access anything
private you put on this server.

What Specifically Are The Points of Vulnerability?
--------------------------------------------------

I think it's a good idea to be transparent about where the vulnerabilities are,
particularly where they differ from the expectations we tend to have from
decades on corporate platforms.

As I mentioned above, I can in theory read any message sent on the server,
including Direct Messages that don't involve me, and "followers only" posts from
people who have not let me follow them. I don't think there is actually an
interface for me to do these things this in the Mastodon administrative
settings, but your DMs, like everything else, are stored in the server, and if
it's there, I can access it via the command line. I have no idea how to do that
at present and I am not planning on trying to learn.

By the way, the nonprofit that maintains Mastodon is planning an update that
will add end-to-end encryption, making that a moot point. But I don't know when
that will be.

Then there's images. Any image you upload to Mastodon is stored in an Amazon s3
bucket. This includes public posts, local-only posts, private follow-only posts,
and DMs. I could in theory browse the bucket and see all those images (although
I don't intend to do that). uploaded images are also publicly available to
anyone who knows the image url, so images can be best described as "unlisted" in
the sense that there is no public facing way to browse for images in the s3
bucket but any given image can be accessed by its url.

The biggest vulnerability on mastodon, though, is also its biggest strength:
federation. Because mastodon is federated, you will be interacting with people
on other servers, whose admins you do not know and trust, and which may have
different rules or different software. For instance you may post a followers-
only toot, which per the basic mastodon functionality cannot be boosted beyond
its original audience. But once that toot is visible on another server, there is
no guarantee that that server is running mastodon as you and I know it. It may
be running a forked version that does not respect privacy. This goes for DMs
too. This is not a security hole in this server, it is a structural feature of
the fediverse.

Therefore, please think of the privacy measures of Mastodon/Hometown as barriers
and impediments, not unbreakable forcefields, and do not use this or any other
non-encrypted fediverse service to exchange pictures or images that you would
find devastating if they were made public.

Is This Gonna Be Forever?
-------------------------

Nothing is forever but I don't know how long this is gonna exist. It's possible
that I will burn out, or not be able to justify the (currently small) expense at
some point, and there will be no one to take over for me, so it'll shut down. I
could also just become completely unable to keep things going for health or, uh,
death reasons.

When I invite people to join me here I'll be doing so in the hopes that they
can build a social presence that will be meaningful and important to them, and
that is a commitment that I take seriously. This is an experimental project and
I cannot guarantee that it will go well but I will try my best to do right by
that commitment, which means I won't just get bored one day and pull the plug
without warning.
