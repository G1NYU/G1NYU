<div align="center">

<img src="assets/banner.svg" width="100%" alt="giinyu. Design meets development. Media software, integrations and interfaces." />

<br/><br/>

[**Portfolio**](https://g1nyu.github.io/) &nbsp;&nbsp;·&nbsp;&nbsp; [**Projects**](#selected-work) &nbsp;&nbsp;·&nbsp;&nbsp; [**Plugin catalog**](https://g1nyu.github.io/harbor-plugins/)

</div>

<br/>

## About me

I'm **giinyu**, an independent builder with a background in graphic design. I work across media software, API integrations, performance optimization and interface design.

I like connecting applications that should work together, developing useful plugins, and making software feel as good as it looks. My process combines hands-on testing, iterative development, reproducible builds and AI-assisted engineering.

<br/>

<div align="center">

## My toolkit

<br/>

<img src="https://skillicons.dev/icons?i=ts,js,react,nextjs,html,css&amp;perline=6&amp;theme=dark" width="570" alt="TypeScript, JavaScript, React, Next.js, HTML and CSS" />

<br/><br/>

<img src="https://skillicons.dev/icons?i=nodejs,python,git,github,githubactions,docker&amp;perline=6&amp;theme=dark" width="570" alt="Node.js, Python, Git, GitHub, GitHub Actions and Docker" />

<br/><br/>

<img src="https://skillicons.dev/icons?i=figma,linux,vscode,tauri&amp;perline=4&amp;theme=dark" width="360" alt="Figma, Linux, VS Code and Tauri" />

<br/><br/>

**Desktop applications · APIs · Plugin development · Design systems · Performance · CI/CD**

</div>

<br/><br/>

## Selected work

<br/>

<a href="https://github.com/G1NYU/RE-Harbor"><img src="https://raw.githubusercontent.com/G1NYU/RE-Harbor/beta-branch/docs/media/harbor-mark.svg" alt="Harbor logo" width="105" align="left" /></a>

### RE-Harbor

**Desktop development & media integrations**

[Repository](https://github.com/G1NYU/RE-Harbor) &nbsp;·&nbsp; [Experiments](https://github.com/G1NYU/RE-Harbor/pulls)

<br clear="both"/>

An experimental fork of Harbor, working across the React/TypeScript frontend, Tauri desktop environment and media integrations.

**[Refract integration](https://github.com/G1NYU/RE-Harbor/pull/4)** — API-key authentication, verified external-ID resolution, persistent retry queues, duplicate protection and inbound watched history. Manual watch logging is verified live; [automatic diary logging](https://github.com/G1NYU/RE-Harbor/tree/feature/snappy-startup-msi) with configurable viewing thresholds is in testing.

**[Snappy](https://github.com/G1NYU/RE-Harbor/pull/5)** — performance experiments with deferred initialization, lazy poster mounting, scroll/render profiling, regression tests and isolated Windows MSI builds.

The long-term Refract goal is a unified media tracker, with watchlist syncing next and games, books and manga dependent on future API capabilities.

**November 2026 milestone** — The Refract contribution was subsequently merged into Harbor as **PR #103** (merge commit `d3847d3`). The [VOID + Refract source branch](https://github.com/G1NYU/RE-Harbor/tree/feature/void-refract-2026-11-installer) includes later playback diary logging, watchlist add/remove work, and the custom music interface. The earlier milestones above document the integration's development stages; full two-way Refract-to-Harbor synchronization remains a separate goal.

**Builds and source continuity** — Published an [unsigned Windows x64 preview installer](https://github.com/G1NYU/RE-Harbor/releases/tag/reharbor-void-refract-2026-11-20) through a checksum-verified GitHub Actions packaging workflow. CI verified silent installation, bundled files, shortcuts and uninstallation; interactive Windows playback still requires device-level testing. Separately [archived Harbor 1.0.4 source through 21 November 2026](https://github.com/G1NYU/RE-Harbor/tree/archive/harbor-official-2026-11-21) for future upstream integration without overwriting the custom build.


<br/>

<a href="https://github.com/G1NYU/harbor-plugins"><img src="assets/plugins-icon.svg" width="105" align="left" alt="Harbor Plugins icon" /></a>

### Harbor Plugins

**Source development & distribution**

[Repository](https://github.com/G1NYU/harbor-plugins) &nbsp;·&nbsp; [Live catalog](https://g1nyu.github.io/harbor-plugins/)

<br clear="both"/>

An actively maintained fork with multilingual manga and Western comics source adapters, alongside the existing plugin infrastructure.

- TypeScript providers in a constrained worker runtime.
- HTML/JSON parsing, pagination, metadata normalization and image extraction.
- Real-client testing of search, catalogs and deep chapter archives.
- Separate main and testing catalogs, esbuild bundling, manifest validation and GitHub Pages deployment.

**Source reliability and catalog QA** — Investigated Kagane/KakaManga metadata, AllManga chapter-image failures, and an unusable Mangakakalot adapter. Weloma, WeebCentral and MangaFire were among the sources reported working in earlier tests. Source behavior can change; those observations describe historical testing rather than permanent compatibility guarantees. Catalog publishing, experimental source validation and user-facing distribution are treated as distinct workflows.

**Ebook integrations** — Published and exercised a Harbor ebook catalog, including entries from the *Inheritance Cycle*. Explored a possible **GinyuBooks** cleanup/alpha with Royal Road, Standard Ebooks and download-only Library Genesis support; a separate alpha release was not confirmed.


<br/>

<a href="https://github.com/G1NYU/RE-Harbor/pull/6"><img src="assets/void-icon.svg" width="105" align="left" alt="VOID theme icon" /></a>

### VOID

**Interface design & performance**

[Native experiment](https://github.com/G1NYU/RE-Harbor/pull/6)

<br clear="both"/>

A custom Harbor theme exploring cinematic interfaces, deep Catppuccin Mocha palettes, bespoke navigation icons, refined typography and multilingual layouts.

Rich-effects experiments evolved into a lighter, static CSS approach guided by real scrolling tests and frame-timing diagnostics. VOID Native is a separate component-level theming prototype.

**Additional client work** — Prototyped centered branding, personalized greeting, larger streaming-service cards, flexible sidebar navigation, poster numbering and a full-page stream selector. Music and library explorations included expanded player views, playback controls, visualizer diagnostics, and CD/cassette-inspired artwork and motion. These span prototypes, tested revisions and design references; individual animations are not all verified as shipped.


**Beautiful software should feel beautiful to use.**

<br/><br/>

## What I do

**Application development** — React, TypeScript, JavaScript, Next.js, HTML/CSS, Tauri/WebView2; desktop and web interfaces, state-driven components and application integration.

**API & data integration** — REST, JSON, authentication, metadata matching, cursor pagination, synchronization, idempotency, retry queues and library migration.

**Extensions & automation** — Node.js, Python, esbuild, Git and GitHub Actions; source adapters, data extraction, testing, CI/CD and packaging.

**Performance & visual design** — DevTools, frame timing, lazy loading, SVG and Figma; profiling, rendering efficiency, accessible dark interfaces and cohesive design systems.

I also work with Docker, Jellyfin, Stremio and AIOStreams for self-hosted media, LM Studio and MCP for local AI workflows, and scripting for repetitive tasks. Tauri/Rust-based applications remain an active area of exploration.

<br/><br/>


## Streaming configurations & debugging

AIOStreams and Stremio work includes configuration design, stream selection, add-on interoperability, and diagnostic comparison of JSON exports across distinct use cases. These are personal setups and experiments, **not claims of maintaining AIOStreams or Stremio themselves**.

| Configuration | Technical scope |
| :--- | :--- |
| `Ultimate` | Anime, K-drama, movies and TV; French/English coverage, Japanese/Korean original-audio priorities, cached results, resolution order, add-on tiers and preserved regex/stream expressions. |
| `ice cream` | Meteor result inclusion, original Japanese audio where applicable, and French/English subtitle matching. |
| French-first bilingual | French with English fallback, anime/K-drama rules, Cometmid/Cometkuu passthrough, Ned's French-language formatter and StreamFusion duplicator exclusions; investigated slower responses. |
| French-audio-only / `finalFRENCH.json` | French/Multi-only audio selection, 4K/1080p priority and frenchio pinning; compared TorBox and AllDebrid routing without conflating service configuration. |
| General TV | Add-on timeout budgets, dynamic fetching, remote-friendly result navigation, cached selection, next-episode precaching and title/year/episode matching. |
| USA profile | One-choice-per-resolution deduplication, Dolby Vision/HDR preferences, and reuse of anime/K-drama rules; sanitized export requested. |
| `aiostreams-config-tuned` | Cached-only behavior for this variant, French/Multi 4K and VOSTFR matching, Japanese/Korean audio preferences and dynamic-fetch rules; end-to-end playback coverage remained unverified. |

**Debugging practice** — Compare known-good and underperforming exports; inspect passthrough filters, stale add-on identifiers, sorting/deduplication, premature termination and overly restrictive requirements. Investigated HTTP 429 responses, IP-bound playback tokens, wrapped instances, proxy/self-hosting constraints and stream-size limits without claiming a universal fix. Also encountered schema mismatches (`streams` versus `totalStreams`) and unsupported `fuzzy` matching; Prowlarr/Jackett were evaluated as possible source approaches, not confirmed deployments.

**Documentation** — Drafted a French beginner guide to Stremio, add-ons and debrid workflows, with guidance on sharing configurations without credentials.

## More projects

| Project | Focus |
| :--- | :--- |
| [mihon-to-anymex](https://github.com/G1NYU/mihon-to-anymex) | Manga-library migration and AniList metadata matching |
| [hondana (ほんだな)](https://github.com/G1NYU/hondana) | Personal Mihon fork; explored shelf-based reading-library organization (implementation not independently verified) |
| [g1nyu-shelf](https://github.com/G1NYU/g1nyu-shelf) | Personal media catalog using Next.js, AniList and Last.fm |
| [GINpuccin](https://github.com/G1NYU/GINpuccin) | Catppuccin-inspired YASB Reborn desktop customization |
| [SignalStack](https://github.com/G1NYU/SignalStack) | Interactive history visualization, inspired by Spotify Wrapped |
| [tools-and-media-library](https://github.com/G1NYU/tools-and-media-library) | Curated resource directory and automated publishing |
| [wc2026-value-bracket](https://github.com/G1NYU/wc2026-value-bracket) | Squad market-value-driven tournament simulation |

<br/><br/>


## Libraries, catalogs & other experiments

**Manga-library interoperability** — The [mihon-to-anymex](https://github.com/G1NYU/mihon-to-anymex) workflow explores Python-based conversion, AniList lookups, and direct Mihon/Tachiyomi `.mihon` or `.backup` inputs alongside CSV and an AnymeX template. Komikku backups were used in migration tests; Mangayomi support and anime-versus-manga import classification were investigated, with separate totals requested after anime entries appeared as manga. Not every proposed format or correction is verified as shipped.

**Readers and library tools** — Work with Komikku was personal reading and backup testing, not a claim of contributing to Komikku's code. Maintained the [hondana](https://github.com/G1NYU/hondana) Mihon fork and experimented with custom shelves. Also worked with a generated Cubari manga-source repository, and configured Jellyfin as a personal media library; specific server deployment details are not public here.

**Harbor client QA** — Tested v1.0.1-beta manga and ebook loading, including intermittent BatCave and Royal Road behavior, verification prompts, absent covers and failed series navigation. Mihon backup import/export was requested as a priority, not established as a shipped Harbor feature.

**Community tools and prototypes** — The [tools-and-media-library](https://github.com/G1NYU/tools-and-media-library) / Sentai toolbox concept is an anonymous, FMHY-inspired directory of shared community resources, with concise listings, GitHub star counts and optional curated picks. Earlier TVFlix collection-builder ideas informed explorations around Nuvio accounts and collections; a standalone TVFlix repository was not verified. Other work includes personal web presence and a portfolio/CV, a blog repository with unverified contents, and private TypeScript/Vly experiments without a public feature specification.

**Additional areas** — PC and audio troubleshooting, local AI/agent experiments, Office/Excel automation, content management and graphic/web design. These describe areas of practice rather than individually verified released products.

<div align="center">

## GitHub activity

<br/>

<img src="https://github-readme-stats.vercel.app/api?username=G1NYU&amp;show_icons=true&amp;hide_border=true&amp;bg_color=181825&amp;title_color=89B4FA&amp;icon_color=89B4FA&amp;text_color=CDD6F4" alt="GitHub statistics" height="155" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=G1NYU&amp;layout=compact&amp;hide_border=true&amp;bg_color=181825&amp;title_color=89B4FA&amp;text_color=CDD6F4&amp;langs_count=8" alt="Repository language statistics" height="155" />

<br/><br/>

## Find me

<br/>

<a href="https://github.com/G1NYU"><img src="https://skillicons.dev/icons?i=github&amp;theme=dark" width="60" alt="GitHub" /></a>&nbsp;&nbsp;
<a href="https://discord.gg/giinyu"><img src="https://skillicons.dev/icons?i=discord&amp;theme=dark" width="60" alt="Discord" /></a>&nbsp;&nbsp;
<a href="https://instagram.com/icecoldwill"><img src="https://skillicons.dev/icons?i=instagram&amp;theme=dark" width="60" alt="Instagram" /></a>

<br/><br/>

[Portfolio](https://g1nyu.github.io/) &nbsp;·&nbsp; [YouTube](https://www.youtube.com/@ginyuTV) &nbsp;·&nbsp; [Discord](https://discord.gg/giinyu)

<br/><br/>

**giinyu.**

</div>
