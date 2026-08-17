# Contributing to Awesome DeepSeek Harness Use Cases

Thanks for considering a contribution. The bar is strict about verification and fast about merging: the
target is a first response on every pull request within 7 days.

## What belongs here

This list answers **"what can I do with `dsh`"**, not "what plugins exist". The
[awesome-dsh-plugin](https://github.com/awesome-dsh-plugin/awesome-dsh-plugin) list already answers the
second question, and answers it well.

So an entry is a **use case** first and a project second:

- Good: "See what is in your context window, and what got compacted away"
- Not this list: "A context visualization plugin"

If you can't phrase it as something a person wants to do, it probably belongs in a plugin list instead.

## The one hard requirement

**It has to install.** Every entry carries a real, published command taken from the project's own
documentation. If there is no working path into `dsh` yet, we cannot list it, no matter how good or how
popular the project is.

This is the whole reason the list is useful, so we hold it strictly. See
[What we left out](README.md#what-we-left-out): most repositories carrying the `dsh-plugin` topic do not
currently meet it.

If your project ships a DSH install path *after* being left out, please open a pull request. We would
genuinely like to add it.

## Format

```
- **The thing you want to do** with [project](repo-url) by [author](author-url). What it does in one or
  two sentences. Stars, license.
  ```sh
  dsh plugin --profile web add <package>
  ```
```

## Acceptance bar

We merge when all of these hold:

1. **The command works** and comes from the project's own docs, not invented.
2. **The repository is real, public and maintained**, not empty, not archived.
3. **It is genuinely about DeepSeek Harness.** Carrying the `dsh-plugin` topic is not by itself evidence.
4. **It is not already listed**, and the use case is meaningfully different from an existing entry.
5. **The category is right.** If it spans two, pick the primary use case. Maintainers will move it rather
   than bounce your pull request over placement.

We reject only for: no install path, dead or empty repository, pure spam, or an exact duplicate.
**We always reply**, including when we close something. Silence is not an outcome we use.

Small formatting problems are fixed on merge rather than sent back to you.

## Style

- One entry per use case. No sub-bullets.
- Write the description plainly. Say what it does, not that it is powerful or revolutionary.
- No affiliate links, no tracking parameters, no redirects.
- Do not use em dashes or en dashes. Commas, colons and parentheses do the job.
- Star counts and licenses are refreshed by maintainers from the GitHub API. You do not need to keep
  them current in your pull request.

## Disclosure

The maintainer of this repository also builds and sells developer tools
([TranscriptAPI](https://transcriptapi.com), [StayingAPI](https://stayingapi.com),
[Zillapi](https://zillapi.com)).

**As of 2026-08-17, none of them are listed here.** None currently has a clean install path into `dsh`,
so by the rule above none qualifies. That is the rule working as intended, and it applies to us first.

If that changes, any entry of ours will appear at most once per category, in exactly the format every
other entry uses, held to a **higher** bar than a contributed entry, and disclosed at the point it
appears. We will **never** reject or downrank a competing entry to protect one of ours. This list has to
stay fully useful with every entry of ours deleted, and today that test is trivially passed.
