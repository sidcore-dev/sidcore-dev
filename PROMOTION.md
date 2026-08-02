# Promotion drafts

Copy-paste ready drafts for posting this catalog elsewhere. Not auto-posted —
HN and Reddit both require posting as a logged-in human, so these are staged
here for whoever's driving to paste in when ready.

## Show HN

**Title:**

```
Show HN: 70 tiny, zero-dependency CLI tools, built with an AI pair programmer
```

**Body:**

```
Over the past few weeks I've been building a batch of small, single-purpose
command-line tools — the kind of little utility you always wish existed but
never quite get around to writing. Things like:

- gitleaks-lite-cli — heuristic regex/entropy secret scanner, catches
  credentials before they hit a commit
- envexport-cli — turns a .env file into shell exports, docker -e flags,
  or flat JSON
- treeview-cli — a tree that actually respects .gitignore
- gitstats-cli — summarizes a git repo's commit history (authors, hot
  files, day-of-week activity)
- passgen-cli, jwtdecode-cli, hashcheck-cli, unused-imports-cli, and
  a few dozen more

Most are pure Python stdlib, no dependencies, MIT licensed. I built these
working with Claude Code as a pair programmer, which is what made it
practical to actually finish and polish this many small ideas instead of
leaving them half-done in a folder somewhere.

Catalog: https://github.com/sidcore-dev

Feedback and bug reports welcome — also happy to answer questions about
the AI-assisted workflow if that's of interest.
```

**Submission notes:**
- Use the GitHub profile link (`https://github.com/sidcore-dev`) as the URL.
  If HN wants a single canonical page instead of a profile, use
  `https://github.com/sidcore-dev/sidcore-dev` (the profile README repo).
- Timing matters more than content for HN — weekday mornings, US Eastern
  time, tend to get the most eyes.

## r/commandline

**Title:**

```
I built 70 tiny, zero-dependency CLI tools (Python stdlib only, MIT licensed)
```

**Body:**

```
Wanted to share a batch of small single-purpose CLI utilities I've been
building — the "I wish this existed" category of tool. A few examples:

- gitleaks-lite-cli — heuristic secret scanner (regex + entropy), no API
  calls, catches obvious leaks before a commit
- treeview-cli — like `tree`, but respects .gitignore automatically
- envexport-cli — .env → shell exports / docker -e flags / JSON
- gitstats-cli — commit history summary: authors, hot files, day-of-week
- passgen-cli — passwords/passphrases via `secrets`, not `random`
- jwtdecode-cli, hashcheck-cli, unused-imports-cli, csvpeek-cli, and a
  couple dozen more in the same vein

All pure stdlib (no dependencies), MIT licensed, each with tests + CI.
Full list: https://github.com/sidcore-dev

Genuinely curious which of these are actually useful vs. which ones
already have a better-known equivalent I should just point people to
instead — feedback welcome either way.
```

## Awesome-list submissions — not yet viable

Checked contribution guidelines before drafting anything here:

- **agarrharr/awesome-cli-apps** requires >20 GitHub stars, project age
  >3 months, and its CONTRIBUTING.md explicitly states: *"AI-generated
  PRs are not welcome... we would like to know why a human thinks the
  app-to-be-added is awesome."*
- **alebcay/awesome-shell** requires ≥50 stars.

None of these repos meet either bar yet (0 stars, days old). Revisit once
the HN/Reddit posts (if posted) drive some real stars.
