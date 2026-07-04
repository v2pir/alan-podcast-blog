# Beevr × Alan — Podcast → SEO Blog, fully automated

This repository is a **live demo** of what Beevr does for your podcast network:
it listens to your episodes, understands them, writes SEO-optimized articles from
the actual transcripts, and **publishes them straight to your website** — with no
human in the loop.

## What you're looking at

- **Live website:** https://v2pir.github.io/alan-podcast-blog/
- **This repo:** https://github.com/v2pir/alan-podcast-blog
- **Commit history** (every post here was committed by Beevr):
  https://github.com/v2pir/alan-podcast-blog/commits/main

The two articles on the site were generated end-to-end by Beevr from a real
Megaphone-hosted podcast (*Decoder with Nilay Patel*) as a stand-in for your shows:

1. **"The CMO Is a Dying Role: Digitas CEO Amy Lanzi on Why Marketing Leadership
   Must Evolve or Die"** — from the episode with Amy Lanzi.
2. **"Weber's New CEO Reveals the Deal That Almost Didn't Happen — And Why Grill
   Prices Are About to Drop"** — from the episode with Roger Dahle (published
   fully autonomously by a Beevr agent, zero human input).

Every quote in those posts is pulled from the **real transcript** — Beevr does not
make things up, and it won't publish a claim it can't ground in what was actually said.

## The exact flow (what happens automatically)

1. **Ingest** — Beevr connects to your Megaphone feed and pulls each new episode.
2. **Transcribe** — the audio is transcribed verbatim into the company brain.
3. **Analyze** — Beevr reads the transcript and picks the strongest blog angle —
   the most search-worthy, quotable, high-intent topic in that episode.
4. **Write** — it drafts a complete, SEO-optimized article (title, meta description,
   keyword tags, headings, real quotes).
5. **Publish** — it commits the article to your website's GitHub repo, which makes
   the post go live. Works with Jekyll, Hugo, Next.js, Astro, Gatsby, 11ty, etc.

This runs on demand ("blog our latest episode") or on a schedule ("every Monday,
turn last week's episodes into posts").

## Pointing it at YOUR podcast + YOUR website

Send us these and you're live on your real content — it's a 2-minute swap on our side:

1. **Your podcast:** your Megaphone RSS feed URL (or Megaphone API access).
2. **Your website repo:** the GitHub `owner/repo` and the folder posts live in
   (e.g. `_posts/`, `content/blog/`, `src/content/blog/`, `posts/`).
3. **Write access to that repo** — the one thing needed from you. Either:
   - connect **your** GitHub to the Beevr workspace (one-click OAuth), so posts
     commit as you; **or**
   - add our publishing account as a **collaborator** with write access.

That's it — Beevr handles discovery, transcription, writing, and publishing.
Works with Jekyll, Hugo, Next.js, Astro, Gatsby, and 11ty out of the box.

## Roadmap for your network (the paid tier)

- **Live Google Trends + search-demand signals** to rank blog opportunities by real
  keyword demand (this demo uses transcript-driven topic analysis; Trends is the upgrade).
- **Multi-show orchestration** across your whole network from one workspace.
- **Editorial review gate** (optional) — approve posts before they publish, or let
  it run fully autonomous per show.
- **Internal linking + series clustering** for SEO authority.

*Built by Beevr. Questions → let's talk.*
