
# recordName

> This is the feed's ID which can be letters, numbers, or dashes. Spaces are not allowed. Maximum length is 15 characters.

akam-list

# displayName

> This is the title of the custom feed. Maximum length is 24 characters.

赤安（跡地）

# description

> This is the description of the feed.

「赤安」が含まれているPostのフィードの跡地

現在はこちら https://bsky.app/profile/did:plc:vhzahfkwxz7x3hdx6wktxnom/feed/aaaiqofponcsq

# searchTerms

> There are three types of search terms:
>
> - Keywords: Test these in [https://bsky.app/search](https://bsky.app/search). `AND` is implicit, so `cat dog` on one line will require both `cat` and `dog`. You can use quotes as well `"hot dog"`.
> - Users: links such as `https://bsky.app/profile/why.bsky.team` will pull in the user's posts. To include replies and reposts, you can add the following flags: `https://bsky.app/profile/why.bsky.team +replies +reposts`.
> - Pinned posts: links such as `https://bsky.app/profile/saddymayo.bsky.social/post/3jxju2wwap22e` will pin at the top of the feed. One link per line, please.

- https://bsky.app/profile/hibiki-palm.bsky.social/post/3kl3bftyrzw2j

# denyList

> Deny list will exclude any results from a given user. You can provide the username or DID.
>
> - did:plc:1234
> - @spamspamspam.bsky.social

- did:plc:vhzahfkwxz7x3hdx6wktxnom/app.bsky.graph.list/3kkypuchtyp2w

# safeMode

> Safe mode limits the total number of API calls coming from Cloudflare.
> true or false
> Set to `false` if you have higher limits via a paid Cloudflare plan.

true

# avatar

> This must link to an image (PNG or JPEG) in the same directory as this CONFIG.md. It doesn't have to be called `avatar.png`, but just be sure this CONFIG.md points to the correct file.

![](avatar.png)
