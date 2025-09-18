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
