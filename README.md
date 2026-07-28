Full-stack engineer, 15+ years in production. Ruby and Rails at the core, TypeScript and Go alongside it. I ship end to end: schema, backend, frontend, deploy pipeline. Coding agents are part of my daily workflow, and I review what they produce the same way I'd review any other contributor's patch.

Based in Yerevan (UTC+4). I work late, so my day overlaps a full US East workday.

### Open source I maintain

The work below is mostly closed-source, so here's the stuff you can actually click into.

**[sec_id](https://github.com/svyatov/sec_id)** - a securities-identifier toolkit: validate, parse, normalize, detect, convert, generate, classify and repair 16 schemes (ISIN, CUSIP, CEI, SEDOL, FIGI, LEI, IBAN, CIK, OCC, WKN, Valoren, CFI, FISN, BIC, DTI, UPI), check-digit math included. My oldest gem: first released in 2019, 18 versions since, now on 7.x. RBS type signatures, a written migration guide for every major bump, and CI across supported Rubies.

**[clsx-rails](https://github.com/svyatov/clsx-rails)** - `clsx`/`cn` view helpers for Rails, a drop-in replacement for `class_names` that benchmarks 2-4x faster and never slower on realistic markup. The framework-agnostic core ships separately as [clsx-ruby](https://github.com/svyatov/clsx-ruby) for ViewComponent, Phlex, or plain templates.

**[oss-kit](https://github.com/svyatov/oss-kit)** - curated agent skills for open-source maintainers. Audit a repo's health and get back only the gaps, each routed to the skill that fixes it: improve the README, bring the project in line with community guidelines and best practices, and publish releases to npm, RubyGems, PyPI and crates.io. Scores both GitHub and GitLab, and holds itself to its own standard. [Docs](https://oss-kit.svyatov.com/).

**[hacker_news_sorted](https://github.com/svyatov/hacker_news_sorted)** - Chrome extension that re-sorts the HN front page by points, time, comments, velocity or heat, marks posts you haven't seen, and highlights repeat comment authors. TypeScript, Manifest V3, zero data collection.

**[oz](https://github.com/svyatov/oz)** - config-driven CLI wizard framework in Go: define prompts in YAML, wrap any tool in a discoverable TUI. golangci-lint, GoReleaser, CI on every push.

<details>
<summary>13 more</summary>

<br/>

**AI & agent tooling**

- **[agentskills-lint](https://github.com/svyatov/agentskills-lint)** - zero-config `npx` linter for the [Agent Skills spec](https://agentskills.io/specification): errors for spec violations, warnings for weak authoring.
- **[agent-toolkit](https://github.com/svyatov/agent-toolkit)** - reusable skills and plugins for Claude Code, Cursor, Codex, and Gemini CLI; the agent setup I actually work with day to day.

**Ruby gems**

- **[candor](https://github.com/svyatov/candor)** - turn a block or callable into a real method with an honest signature.
- **[briefly](https://github.com/svyatov/briefly)** - a terse, curated facade over your application's most reached-for objects.
- **[card_dealer](https://github.com/svyatov/card_dealer)** - a delightful card-dealing companion for your digital table.
- **[http_wrapper](https://github.com/svyatov/http_wrapper)** - a small, ergonomic skin over stdlib `Net::HTTP`.
- **[smsru-ruby](https://github.com/svyatov/smsru-ruby)** - dependency-free client for the SMS.ru API: send SMS, phone-call verification, delivery status. Fully RBS-typed, with constant-time webhook signature verification.

**Frontend for Rails / Tailwind**

- **[clsx-ruby](https://github.com/svyatov/clsx-ruby)** - the framework-agnostic core behind clsx-rails: conditional CSS class strings for ViewComponent, Phlex, or plain templates.
- **[tailwind-merge-typography](https://github.com/svyatov/tailwind-merge-typography)** - a tailwind-merge plugin that resolves `@tailwindcss/typography` `prose-*` conflicts correctly.

**TypeScript libraries**

- **[devto-client](https://github.com/svyatov/devto-client)** - typed, zero-dependency client for the dev.to (Forem) v1 API. Response types come from Forem's own OpenAPI spec; the versioned Accept header and the undocumented rate limits are handled for you, so requests can't silently downgrade to the deprecated v0 API.

**CLI tools & wizards**

- **[create-rails-app](https://github.com/svyatov/create-rails-app)** · **[create-ruby-gem](https://github.com/svyatov/create-ruby-gem)** - interactive wizards for `rails new` and `bundle gem`, so you stop looking up flags.

**Learning by building**

- **[database-transactions](https://github.com/svyatov/database-transactions)** - learn database transactions from verified, runnable examples. Every claim proven against a real PostgreSQL/MySQL database.
- **[deck](https://github.com/svyatov/deck)** - basic operations on a deck of playing cards, in Elixir.

→ [a few more on the repos tab](https://github.com/svyatov?tab=repositories)

</details>

### What I like working on

- **A blank repo and broad ownership** - schema, infra, deploy pipeline, the lot. [`oz`](https://github.com/svyatov/oz) and [`create-rails-app`](https://github.com/svyatov/create-rails-app) both exist because I kept starting from zero and wanted the starting part to be good.
- **Designing good interfaces** - [`candor`](https://github.com/svyatov/candor) and [`briefly`](https://github.com/svyatov/briefly) are entirely about this: the implementations are small, the shape of the API was the whole problem.
- **Making slow things fast** - finding the real bottleneck and killing it. [`clsx-rails`](https://github.com/svyatov/clsx-rails) is the smallest public version of that: 2-4x, measured, with the benchmark in the repo so you can check.
- **Small teams with a short chain of command.** Move fast, but with quality; no long approval chains.
