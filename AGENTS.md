# AGENTS.md — jonathanmccallum-it (Italian mirror of jonathanmccallum.com)

Italian mirror site. Same theme and design as the main site (Paper Light),
content translated into Italian, meaning-first. Repo: streamjonathan/jonathanmccallum-it.
Live (when approved): it.jonathanmccallum.com. Proof: jonathanmccallum-it.pages.dev.

## Mission

Mirror jonathanmccallum.com in Italian — every article translated for meaning,
not word for word, in Jonathan's voice: plain short sentences, friendly, positive,
never preachy. An average person interested in Jesus, not an expert or theologian.

## Roles

- **Bobby (Muse) is the lead builder.** He coordinates, builds, pushes to GitHub
  and deploys to Cloudflare. He is the ONLY one who pushes or deploys.
- **Claude advises and reviews** translation quality. He does not push or deploy.
- **Helper Muses translate** one article at a time, drafts only.

## The one rule above all

**Never publish or alter live production assets without Jonathan's clear
permission.** The Italian site goes live on it.jonathanmccallum.com only when
he says so, after reading the pilot article(s). Drafts stay drafts until he
approves them. Work on a branch, never straight on main. Give Bobby a preview URL.

## Translation rules

- English repo (streamjonathan.github.io) is the source of truth. Articles are
  translated from the English Markdown, keeping the same date, slug, source_video
  and shareImage. Only the title and body are translated.
- Register: "tu" (warm, personal, direct address to the reader), short plain
  sentences, no preaching. The reader is always "tu", never "Lei" — Jonathan to
  confirm. God = Dio, Jesus = Gesù.
- Names (never vary): Aslan, Narnia, Lucy, Digory, Tirian, Cair Paravel, Adamo ed
  Eva, Strega Bianca. Book titles use the published Italian titles (Mondadori,
  trad. Chiara Belliti): Le cronache di Narnia, Il nipote del mago,
  Il grande divorzio, Trilogia spaziale, L'ultima battaglia.
- Bible verses: none of the 5 articles contains a direct Bible quotation, so no
  verse text was reproduced. The bread/water of life lines are Jonathan's
  paraphrase (echoing John 6:35 / 4:14) — pane della vita / acqua della vita —
  never presented as quoted Scripture. Exact Diodati 1649 (public domain) wording
  is recorded in work/italian-proof/glossary-it.md if he wants it later.
- No direct Lewis quotations appear either; none were invented.
- No emojis, no newsletter form, no links the English article does not have.
- Never invent facts, dates, links or details.

## Site facts

- Eleventy 3, Cloudflare Pages, Paper Light theme (Fraunces + Newsreader).
- No Ask chat and no note Worker on this site yet — search (Pagefind) works,
  Ask and notes come later. The Ask floating button and ask.js are removed.
- CSS is preloaded, not inlined (CSP blocks inline style). Bump the `?v=` query
  on any CSS/JS file you change.
