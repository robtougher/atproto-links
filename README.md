# Bluesky Troubleshooting

This page contains info for Bluesky troubleshooting.

Items with a ⭐ are most used.

&nbsp;

## Getting Started

When I'm debugging issues with Bluesky, I start with the below links.

- atproto-browser.vercel.app
  - [atproto browser robtougher.com](https://atproto-browser.vercel.app/at/robtougher.com)
- bsk-debug.app
  - [bsky-debug robtougher.com](https://bsky-debug.app/handle?handle=robtougher.com) ⭐
- github.com
  - [mary-ext/atproto-scraping/state.json](https://github.com/mary-ext/atproto-scraping/blob/trunk/state.json)
- internect.info
  - [internect robtougher.com](https://internect.info/did/did:plc:watmxkxfjbwyxfuutganopfk)
- pds01
  - [pds01.threddy.social/xrpc/_health](https://pds01.threddy.social/xrpc/_health) ⭐
  - [pds01.threddy.social/xrpc/com.atproto.server.describeServer](https://pds01.threddy.social/xrpc/com.atproto.server.describeServer) ⭐
  - [pds01.threddy.social/xrpc/com.atproto.sync.listRepos](https://pds01.threddy.social/xrpc/com.atproto.sync.listRepos)
- pdsls.dev
  - [pdsls.dev/pds01.threddy.social](https://pdsls.dev/pds01.threddy.social) ⭐️
  - [pdsls.dev/at/did:web:threddyrex.org](https://pdsls.dev/at/did:web:threddyrex.org)
  - [pdsls.dev/at/did:plc:watmxkxfjbwyxfuutganopfk](https://pdsls.dev/at/did:plc:watmxkxfjbwyxfuutganopfk)
- plc.directory
  - [ResolveDid](https://plc.directory/did:plc:watmxkxfjbwyxfuutganopfk)
  - [GetPlcOpLog (log)](https://plc.directory/did:plc:watmxkxfjbwyxfuutganopfk/log)
  - [GetPlcAuditLog (log/audit)](https://plc.directory/did:plc:watmxkxfjbwyxfuutganopfk/log/audit)
  - [GetLastOp (log/last)](https://plc.directory/did:plc:watmxkxfjbwyxfuutganopfk/log/last) ⭐
  - [GetPlcData (data)](https://plc.directory/did:plc:watmxkxfjbwyxfuutganopfk/data)
  - [Export](https://plc.directory/export?count=10&after=2024-12-08T20:33:04Z)
- public.api.bsky.app
  - [app.bsky.actor.getProfile robtougher.com](https://public.api.bsky.app/xrpc/app.bsky.actor.getProfile?actor=robtougher.com) ⭐
  - [com.atproto.identity.resolveHandle robtougher.com](https://public.api.bsky.app/xrpc/com.atproto.identity.resolveHandle?handle=robtougher.com) ⭐
- well-known (did:web)
  - [threddyrex.org/.well-known/did.json](https://threddyrex.org/.well-known/did.json) ⭐


&nbsp;

## General Links

General info about Bluesky.

- Self-hosting (PDS + all)
  - [github/bluesky-social/pds](https://github.com/bluesky-social/pds) ⭐
  - [bnewbold: Migrating PDS Account with 'goat'](https://whtwnd.com/bnewbold.net/3l5ii332pf32u) ⭐
  - [Adversarial ATProto PDS Migration](https://www.da.vidbuchanan.co.uk/blog/adversarial-pds-migration.html) ⭐
  - [Two-factor auth does not work (issue #99)](https://github.com/bluesky-social/pds/issues/99)
  - [Two-factor auth feature request (issue #1071)](https://github.com/bluesky-social/social-app/issues/1071)
  - [Can't deactivate old account via goat - do it with web instead](https://github.com/bluesky-social/atproto/issues/3149)
  - [How to self-host all of Bluesky except the AppView](https://alice.bsky.sh/post/3laega7icmi2q)
  - [Notes on Running a Full-Network atproto Relay (July 2024)](https://whtwnd.com/bnewbold.net/entries/Notes%20on%20Running%20a%20Full-Network%20atproto%20Relay%20(July%202024))
- did:web
  - [account creation with bsky-did-web](https://github.com/afternooncurry/bsky-did-web) ⭐
  - [AT Protocol DIDs](https://atproto.com/specs/did)
  - [Resolving Identities | Bluesky](https://docs.bsky.app/docs/advanced-guides/resolving-identities)
  - [known issue with CORS - fixing PDSls](https://github.com/notjuliet/pdsls/issues/5)
- Discussion
  - [Discord: AT Protocol PDS Admins](https://discord.gg/h3B9ZjYm) ⭐
  - [Discord: ATProto Touchers](https://discord.gg/3srmDsHSZJ) ⭐
  - [Github: atproto discussions](https://github.com/bluesky-social/atproto/discussions)
  - [Github: pds discussions](https://github.com/bluesky-social/pds/discussions)
- Record browsers
  - [PDSls (pdsls.dev)](https://pdsls.dev/) ⭐
  - [internect.info](https://internect.info/)
  - [atproto browser](https://atproto-browser.vercel.app/)
  - [clearsky.app](https://clearsky.app/)
  - [bsky-debug.app](https://bsky-debug.app/)
- Building on AT Proto
  - [atproto.com](https://atproto.com/) ⭐
  - [docs.bsky.app](https://docs.bsky.app/docs/get-started) ⭐
  - [Quick start guide to building applications on AT Protocol](https://atproto.com/guides/applications)
  - [AT Protocol XRPC API](https://docs.bsky.app/docs/api/at-protocol-xrpc-api)
  - [PDS Entryway](https://docs.bsky.app/docs/advanced-guides/entryway)
  - [Federation Architecture Overview - Bluesky](https://bsky.social/about/blog/5-5-2023-federation-architecture)
  - [Bluesky and the AT Protocol: Usable Decentralized Social Media (arxiv.org)](https://arxiv.org/pdf/2402.03239)
  - [Fission Tech Talks: Bluesky and PLC](https://www.youtube.com/watch?v=m9AVUAUDC2A)
  - [Call for Developer Projects](https://github.com/bluesky-social/atproto/discussions/3049)
  - [atproto/lexicons](https://github.com/bluesky-social/atproto/tree/main/lexicons)
  - [beeman/awesome-atproto](https://github.com/beeman/awesome-atproto)
  - [What does a PDS implementation entail?](https://github.com/bluesky-social/atproto/discussions/2350)
  - [What does an AppView implementation entail?](https://github.com/bluesky-social/atproto/discussions/2961)
- Stats
  - [Bluesky User Count (bsky-users.theo.io)](https://bsky-users.theo.io/)
  - [Bluesky service status (status.bsky.app)](https://status.bsky.app/)
  - [bsky.jazco.dev/stats](https://bsky.jazco.dev/stats)
  - [blue.mackuba.eu](https://blue.mackuba.eu/)
- User Tips and Fun Stuff
  - [Using a domain handle to verify your account](https://bsky.social/about/blog/4-28-2023-domain-handle-tutorial)
  - [Generating a recovery key](https://whtwnd.com/did:plc:xz3euvkhf44iadavovbsmqoo/3laimapx6ks2b)
  - [Debbie's Unofficial Guide To Bluesky](https://publish.obsidian.md/debbieohi/bluesky)
  - [fishttp/awesome-bluesky](https://github.com/fishttp/awesome-bluesky)
  - [Bluesky Roast](https://blueskyroast.com/)
  - [The Fediverse Report](https://fediversereport.com/all-posts-archive/)
  - [skeet-tools](https://dame.blog/skeet-tools/)
- Github repos
  - [did-method-plc/did-method-plc](https://github.com/did-method-plc/did-method-plc)
  - [bluesky-social](https://github.com/bluesky-social/)
  - [bluesky-social/indigo](https://github.com/bluesky-social/indigo/)
  - [bluesky-social/indigo/cmd/goat](https://github.com/bluesky-social/indigo/tree/main/cmd/goat)
  - [bluesky-social/jetstream](https://github.com/bluesky-social/jetstream)
  - [bluesky-social/pds](https://github.com/bluesky-social/pds)
  - [aendra-rininsland/xblock](https://github.com/aendra-rininsland/xblock)
  - [mary-ext/atproto-scraping](https://github.com/mary-ext/atproto-scraping)

&nbsp;

## Commands

Commands to run.

- PDS (Linux)
    - Docker logs (watch events as they happen)
        - docker logs -f pds
    - Docker container stats (cpu/etc.)
        - docker container stats
    - Request crawl
        - pdsadmin request-crawl
    - Restart PDS
        - systemctl restart pds
    - Update PDS installation
        - sudo pdsadmin update
    - Check WS
        - wsdump "wss://<host>/xrpc/com.atproto.sync.subscribeRepos?cursor=0"
- Windows
    - Listen to jetstream ([websocat](https://github.com/vi/websocat/releases), [jetstream](https://github.com/bluesky-social/jetstream))
        - .\websocat4 wss://jetstream2.us-east.bsky.network/subscribe?wantedCollections=app.bsky.feed.post
    - Resolve username ([goat](https://github.com/bluesky-social/indigo/tree/main/cmd/goat))
        - .\goat.exe resolve <username>

&nbsp;


## PDS Notes


**Error: no matching certificate to load for...decoding certificate metadata: invalid character**

delete $PDS/caddy/data/caddy/certificates and restart
