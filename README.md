<div align="center">

  ![Full-Stack Engineer · Open-Source Maintainer · AI-Augmented Builder](title.svg)

  Shipping end to end - backend, frontend, infra - with agentic AI in the loop. Ruby at the core, 15+ years in production.

</div>

<br/>

### Languages & Frameworks

![Ruby](https://img.shields.io/badge/Ruby-0d1117?style=flat-square&logo=ruby&logoColor=58a6ff)
![Rails](https://img.shields.io/badge/Rails-0d1117?style=flat-square&logo=rubyonrails&logoColor=58a6ff)
![Hotwire](https://img.shields.io/badge/Hotwire-0d1117?style=flat-square&logo=stimulus&logoColor=58a6ff)
![Sidekiq](https://img.shields.io/badge/Sidekiq-0d1117?style=flat-square&logo=sidekiq&logoColor=58a6ff)
![TypeScript](https://img.shields.io/badge/TypeScript-0d1117?style=flat-square&logo=typescript&logoColor=58a6ff)
![React](https://img.shields.io/badge/React-0d1117?style=flat-square&logo=react&logoColor=58a6ff)
![Next.js](https://img.shields.io/badge/Next.js-0d1117?style=flat-square&logo=nextdotjs&logoColor=58a6ff)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-0d1117?style=flat-square&logo=tailwindcss&logoColor=58a6ff)
![Python](https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=58a6ff)
![Go](https://img.shields.io/badge/Go-0d1117?style=flat-square&logo=go&logoColor=58a6ff)

### Data & Infrastructure

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0d1117?style=flat-square&logo=postgresql&logoColor=58a6ff)
![Redis](https://img.shields.io/badge/Redis-0d1117?style=flat-square&logo=redis&logoColor=58a6ff)
![Docker](https://img.shields.io/badge/Docker-0d1117?style=flat-square&logo=docker&logoColor=58a6ff)
![AWS](https://img.shields.io/badge/AWS-0d1117?style=flat-square&logo=amazonwebservices&logoColor=58a6ff)
![Ansible](https://img.shields.io/badge/Ansible-0d1117?style=flat-square&logo=ansible&logoColor=58a6ff)
![Linux](https://img.shields.io/badge/Linux-0d1117?style=flat-square&logo=linux&logoColor=58a6ff)
![CI/CD](https://img.shields.io/badge/CI%2FCD-0d1117?style=flat-square&logo=githubactions&logoColor=58a6ff)

### AI & Dev Tools

![OpenAI](https://img.shields.io/badge/OpenAI-0d1117?style=flat-square&logo=openai&logoColor=58a6ff)
![Claude Code](https://img.shields.io/badge/Claude_Code-0d1117?style=flat-square&logo=anthropic&logoColor=58a6ff)
![Cursor](https://img.shields.io/badge/Cursor-0d1117?style=flat-square&logo=cursor&logoColor=58a6ff)

### Open source I maintain

The work below is mostly closed-source, so here's the stuff you can actually click into:

**AI & agent tooling**

- **[oss-kit](https://github.com/svyatov/oss-kit)** - a 46-rule open-source standard shipped as agent skills: audit a repo, get back only the gaps, each routed to the skill that fixes it. Scores GitHub and GitLab, covers release publishing for npm, RubyGems, PyPI and crates.io. [Docs](https://oss-kit.svyatov.com/).
- **[agentskills-lint](https://github.com/svyatov/agentskills-lint)** - zero-config `npx` linter for the [Agent Skills spec](https://agentskills.io/specification): errors for spec violations, warnings for weak authoring.
- **[agent-toolkit](https://github.com/svyatov/agent-toolkit)** - reusable skills and plugins for Claude Code, Cursor, Codex, and Gemini CLI; the agent setup I actually work with day to day.

**Ruby gems**

- **[sec_id](https://github.com/svyatov/sec_id)** - a securities-identifier toolkit: validate, parse, normalize, detect, convert, generate, classify and repair 16 schemes (ISIN, CUSIP, CEI, SEDOL, FIGI, LEI, IBAN, CIK, OCC, WKN, Valoren, CFI, FISN, BIC, DTI, UPI), check-digit math included. My oldest gem.
- **[candor](https://github.com/svyatov/candor)** - turn a block or callable into a real method with an honest signature.
- **[briefly](https://github.com/svyatov/briefly)** - a terse, curated facade over your application's most reached-for objects.
- **[card_dealer](https://github.com/svyatov/card_dealer)** - a delightful card-dealing companion for your digital table.
- **[http_wrapper](https://github.com/svyatov/http_wrapper)** - a small, ergonomic skin over stdlib `Net::HTTP`.
- **[smsru-ruby](https://github.com/svyatov/smsru-ruby)** - dependency-free client for the SMS.ru API: send SMS, phone-call verification, delivery status. Fully RBS-typed, with constant-time webhook signature verification.

**TypeScript libraries**

- **[devto-client](https://github.com/svyatov/devto-client)** - typed, zero-dependency client for the dev.to (Forem) v1 API. Response types come from Forem's own OpenAPI spec; the versioned Accept header and the undocumented rate limits are handled for you, so requests can't silently downgrade to the deprecated v0 API.

**Frontend for Rails / Tailwind**

- **[clsx-rails](https://github.com/svyatov/clsx-rails)** - `clsx`/`cn` view helpers for Rails; a drop-in `class_names` replacement that benchmarks 2-4x faster.
- **[clsx-ruby](https://github.com/svyatov/clsx-ruby)** - the framework-agnostic core: conditional CSS class strings for ViewComponent, Phlex, or plain templates.
- **[tailwind-merge-typography](https://github.com/svyatov/tailwind-merge-typography)** - a tailwind-merge plugin that resolves `@tailwindcss/typography` `prose-*` conflicts correctly.

**Browser extensions**

- **[hacker_news_sorted](https://github.com/svyatov/hacker_news_sorted)** - Chrome extension that re-sorts the HN front page by points, time, comments, velocity or heat, marks posts you haven't seen, and highlights repeat comment authors. TypeScript, Manifest V3, zero data collection.

**CLI tools & wizards**

- **[oz](https://github.com/svyatov/oz)** - config-driven CLI wizard framework in Go: define prompts in YAML, wrap any tool in a discoverable TUI.
- **[create-rails-app](https://github.com/svyatov/create-rails-app)** · **[create-ruby-gem](https://github.com/svyatov/create-ruby-gem)** - interactive wizards for `rails new` and `bundle gem`, so you stop looking up flags.

**Learning by building**

- **[database-transactions](https://github.com/svyatov/database-transactions)** - learn database transactions from verified, runnable examples.
- **[deck](https://github.com/svyatov/deck)** - basic operations on a deck of playing cards, in Elixir.

→ [a few more on the repos tab](https://github.com/svyatov?tab=repositories)

### What I like working on

- **A blank repo and broad ownership** - schema, infra, deploy pipeline, the lot. Building something from zero is the part that actually energizes me.
- **Small teams with a short chain of command.** Move fast, but with quality; no long approval chains.
- **Designing good interfaces** - clean APIs for the people who call them, sharp CLIs and libs for the people who build with them.
- **Untangling messy code** into something you can reason about. Decomposition is the fun part, not the chore.
- **Making slow things fast** - finding the real bottleneck and killing it: N+1 queries, missing indexes, counter caches, hot-path denormalization. Measured wins, not guesses.
- **Ruby/Rails** by default, **Go** for CLIs and small services, **TypeScript** on the front end - increasingly AI-augmented across all of it.

<br/>

<div align="center">

  ![](http://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=svyatov&theme=github_dark)

</div>
