# ssb handbook ![](assets/hermes.png)

A work-in-progress guide to the ssb-verse and key concepts and influences

## What is Scuttlebutt?

Historically, sea-slang for gossip - a scuttlebutt is basically a watercooler on a ship.

Scuttlebutt is a decent(ralised) secure gossip platform.

> This seems like a silly name, but I assure you, this is real science. Read this: http://www.cs.cornell.edu/home/rvr/papers/flowgossip.pdf
>
> Or, if you're lazy: http://en.wikipedia.org/wiki/Scuttlebutt (laziness will get you nowhere, btw)

## About This Handbook

You can build and serve this with gitbook. The following assumes you're running a scuttlebot server and are in the follow neighbourhood of mixmix or his pub.

```bash
npm install gitbook-cli git-ssb -g
git clone ssb://%lJsDWwnF4bDxHWYuSjw/bW37xg+saF8WtPZYZsefKj0=.sha256 ssb-handbook

cd ssb-handbook
gitbook install
gitbook serve
```

The `SUMMARY.md` is the manifest on which the compiled gitbook is based. Edit that if you want content in/out of the book.