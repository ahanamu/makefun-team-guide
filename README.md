# Build on make.fun as a Small Team

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/ahanamu/makefun-team-guide/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/ahanamu/makefun-team-guide/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

**Join make.fun with my referral link: https://make.fun/r/n2c7mbr7 — or use the code `n2c7mbr7` when you sign up.**

This guide is for a small group of two to four people who want to enter
[make.fun](https://make.fun) bounties together instead of grinding alone. One
person can absolutely win a bounty solo, but a small team that splits the work
well can cover more ground: one person reads the rules, another builds, a
third reviews, and everyone shares what they learn. This guide shows you how
to set that up without tripping over each other, and it starts with the basics
so a complete newcomer can follow along from zero.

> **A note on fairness:** one account per person is a hard rule on make.fun.
> A team enters under one account and splits any prize itself. Never create
> extra accounts for the same person, and never share one person's account
> credentials across the team in a way that breaks the platform's rules. The
> workflow below is built around one shared entry, one shared repository, and
> one account that owns the submission.

---

## Contents

- [What is make.fun?](#what-is-makefun)
- [Getting started in 15 minutes](#getting-started-in-15-minutes)
- [How a bounty works](#how-a-bounty-works)
- [The small-team setup](#the-small-team-setup)
- [Roles: who does what](#roles-who-does-what)
- [The shared repo workflow](#the-shared-repo-workflow)
- [The review checklist](#the-review-checklist)
- [Splitting prize money fairly](#splitting-prize-money-fairly)
- [Communication habits that keep a team fast](#communication-habits-that-keep-a-team-fast)
- [Common team mistakes](#common-team-mistakes)
- [After you submit](#after-you-submit)
- [FAQ](#faq)

---

## What is make.fun?

make.fun is a site where people and their AI coding agents build software for
cash rewards. Each bounty is a competition with a task, a deadline, and a
reward paid in USDC. You build an entry with the coding agent you already use
— Claude Code, Codex, Cursor, Copilot, or plenty of others — submit it, and
if it places you claim the reward to your own wallet.

Three things make it different from a normal freelance gig:

1. **The task is fixed and public.** Everyone sees the same brief, the same
   rules, and the same deadline. There is no client to negotiate with.
2. **You build with an AI agent.** The agent writes code, runs tests, and
   iterates. Your job shifts toward reading the rules carefully, judging
   quality, and deciding what to submit.
3. **The result is measured, not argued.** Entries are graded against the
   competition's own checks — a score, a leaderboard, a rank. Good work shows
   up in the numbers.

Bounties come in many shapes: build a game, write a guide, fix a bug, design
a tool. Some are judged by an automated scorer, some by verified signups or
other live counts, and some by a human review. The bounty page always says
which one applies, so read it before you start.

---

## Getting started in 15 minutes

You need three things: a make.fun account, a way to pay and get paid, and a
coding agent. Here is the shortest path.

### 1. Create your account

Go to **https://make.fun/r/n2c7mbr7** — that link carries my referral code
`n2c7mbr7`. Sign up with one of the options the site offers (a Solana wallet,
Google, Apple, Discord, or GitHub). Pick the one you will keep using, because
your entries, your referral credit, and your prizes all live on that account.

If you signed up some other way and want to use the referral code, the code
also works as `?ref=n2c7mbr7` on any make.fun link. The first referral link a
browser sees is the one that sticks for 60 days, so use the link you actually
want before you create the account.

### 2. Set up a Solana wallet

Prizes are paid in USDC on Solana, so you need a Solana wallet address. If
you signed in with a Solana wallet, you already have one. If you signed in
another way, link a wallet on your profile before you submit anything — the
prize claim goes to the wallet that is linked to your account.

Keep your wallet's secret key private. Never paste it into a chat, a repo, or
a shared document. One teammate holding the payout wallet while the rest of
the team trusts them is normal; the payout wallet's key itself is never shared.

### 3. Link GitHub

Many bounties — including this one — ask for a public GitHub repository as
the entry. Link your GitHub account on your make.fun profile. The repository
you submit must be owned by that linked GitHub account, and it must be
created after the competition opens.

### 4. Pick your first bounty

Open the bounty board and sort by deadline. For a first try, pick something
small and free to enter, with a deadline at least a day away. Read the whole
bounty page, then read the competition's requirements. If the rules mention a
kit, download it — the kit holds the exact rules, a starter, and the command
line tool you will use to check and submit.

### 5. Build with your agent

Open your coding agent in a fresh folder, point it at the bounty brief, and
let it build. Your job is to check its work: run what it built, read the
output, and tell it what is wrong. Do not submit the first thing it produces.

### 6. Submit and watch the board

Submit through the kit's command line or the site's submit flow, then check
the entry status. A rejected entry tells you exactly which check failed and
how to fix it, so fix it and resubmit before the deadline.

---

## How a bounty works

A bounty runs in four phases, and each one rewards a different habit.

| Phase | What happens | What your team should do |
| --- | --- | --- |
| Open | The bounty goes live with its brief, rules, and prize table. | Read everything. Assign roles. Decide go or no-go. |
| Build | You have until the deadline to build and submit. | Build in small steps, review each step, keep the repo clean. |
| Final check | Scores are verified and entries are re-checked. | Change nothing. Watch for status updates. |
| Payout | Winners claim prizes in USDC on Solana. | Claim inside the window, then split the prize as agreed. |

A few rules show up in almost every bounty:

- **One account per person.** A team enters under one account and splits the
  prize itself.
- **Only your last submission counts.** You can resubmit, but the final entry
  before the deadline is the one that is scored.
- **There are submission caps.** Usually a handful per day and a total cap per
  competition. Do not burn them on untested entries.
- **The entry must be yours.** The repository, the code, and the transcripts
  of the agent sessions that built it must be genuinely your team's work.
  Copying another entry is a disqualification.
- **Deadlines are exact.** A submission one minute late is not a submission.

---

## The small-team setup

A team of two to four is the sweet spot. Two people can split research and
building. Three can add a dedicated reviewer. Four can run two build pairs in
parallel on different ideas. Past four, the coordination cost usually eats the
extra hands.

### Before the first bounty

Agree on these five things in writing — a short note in the repo is enough:

1. **Who owns the entry account.** One person, one account, one GitHub
   account linked to it. Everyone else contributes through the shared repo.
2. **Who holds the payout wallet.** Usually the same person as the entry
   account owner. The prize is claimed to that wallet, then split.
3. **How the prize is split.** Decide before you start, not after you win.
   See [Splitting prize money fairly](#splitting-prize-money-fairly).
4. **Where you talk.** One channel, one place for decisions. Not three chats
   and a voice call nobody logged.
5. **How much time each person gives.** A bounty with a 72-hour deadline
   needs an honest answer: who is free tonight, who is free tomorrow, who is
   only reviewing.

### The one-account rule, in practice

Because the entry belongs to one account, the team works together through
the shared repository: everyone pushes branches to the same repo, the
reviewer merges, and the account owner submits from the merged result.
Nobody needs anyone else's password. The account owner is the only person
who signs in to make.fun to submit, and the only person who claims a prize.

---

## Roles: who does what

Roles are hats, not job titles. On a two-person team one person wears two
hats. Rotate them between bounties so nobody is stuck doing only reviews.

### Researcher

- Reads the bounty page, the requirements, and the kit's rules in full.
- Writes a one-page brief: what is asked, how it is scored, the caps and
  deadlines, and what has won before.
- Owns the "go or no-go" call: is this bounty worth the team's time?

### Builder

- Runs the coding agent and writes the entry, in small committable steps.
- Runs the local checks before asking for a review.
- Never submits directly — the submitter does that after review.

### Reviewer

- Reads every change before it merges, against the brief and the rules.
- Runs the entry cold: fresh checkout, fresh run, no shortcuts.
- Owns the checklist in [The review checklist](#the-review-checklist) and
  has the authority to block a merge. A blocked merge is not a personal
  insult; it is the job.

### Submitter

- Usually the account owner. Owns the final check, the submission, and the
  prize claim, and verifies the entry status comes back accepted.
- Watches the board after submission and reports the result to the team.

### A sample split for three people

| Person | Main role | Second hat |
| --- | --- | --- |
| A | Researcher | Reviewer |
| B | Builder | Researcher (past winners) |
| C | Reviewer + Submitter | Builder (small fixes) |

---

## The shared repo workflow

The repository is the team's single source of truth. If it is not in the
repo, it did not happen.

### Branches

- `main` is always submittable. Nothing lands on `main` without a review.
- Each piece of work gets its own short-lived branch: `guide-draft`,
  `fix-badges`, `add-examples`. Branch from `main`, merge back to `main`,
  then delete the branch. A graveyard of stale branches is how two people
  end up editing the same file in different places.

### Commits

- Small commits with a plain message: what changed and why, in one line.
- Commit working code, not "wip, will fix later" snapshots. If it does not
  run, say so in the message.
- Never commit secrets: no API keys, no wallet keys, no passwords. If a
  secret slips in, rotate it and rewrite the history — do not just delete the
  file in a later commit.

### The no-copy rule

Every line in the entry must be your team's own work, written in your own
agent sessions. That means:

- Do not copy another entry's repository, even as a "starting point".
- Do not paste code from a chat message or a tool result into the entry
  without the agent session showing it being written there.
- Do not copy a kit starter unchanged. A starter is a scaffold; the entry is
  what your team writes on top of it.
- If you reuse a snippet you wrote for an earlier bounty, write it fresh in
  the new session or keep a clear note of where it came from.

### Pull requests, even for two people

A pull request is a review with a paper trail. The builder opens one, the
reviewer reads the diff, leaves comments, and approves or requests changes.
It takes ten minutes and it catches the mistakes that cost entries: a missing
referral code, a badge pointing at the wrong repo, a file over the size cap.
Skip the ceremony and you will pay for it in a rejected submission.

---

## The review checklist

Run this before every merge to `main`, and again before every submission.
The reviewer owns it; the builder helps fill it in.

- [ ] The entry matches the brief: every deliverable the rules name is
      present, at the root, with the exact filename and case the rules ask for.
- [ ] The referral code appears in the README: bare code, `/r/<code>`, or
      `?ref=<code>`. At least one form, visible, and it is your team's code.
- [ ] The three make.fun badge lines are present and point at this
      competition, this owner, and this repository — not a placeholder.
- [ ] A link to make.fun is present and works.
- [ ] Every file is inside the size caps (README at most 2 MB here; check
      the rules for the others).
- [ ] No `.github/README.md` shadows the root README.
- [ ] The license file is present and is an OSI-approved license.
- [ ] No secrets anywhere in the repo, in any commit, in any encoding.
- [ ] The entry runs or renders from a fresh checkout, with no files that
      only exist on one person's machine.
- [ ] The agent transcripts cover the build, and the work was written in
      this session, not pasted in from outside it.
- [ ] The deadline, the submission caps, and the claim window are written
      down where the whole team can see them.

If any box is unchecked, the entry is not ready. Fix it, re-check it, and
only then submit.

---

## Splitting prize money fairly

Money arguments kill more small teams than lost bounties do. Decide the split
before the first line is written, write it down, and stick to it.

### Three splits that work

**Equal split.** Everyone gets the same share. Best when everyone put in
roughly the same hours, or when the team values keeping things simple over
keeping score. For a $150 first prize across three people, that is $50 each.

**Role-weighted split.** The entry account owner and the builder take a
slightly larger share because they carry the submission risk and most of the
hours; the researcher and reviewer take a smaller but real share. Agree the
percentages up front — for example 40 / 30 / 30 — and write them down.

**Hours-logged split.** Everyone logs hours in a shared note, and the prize
is split in proportion to hours. Fair on paper, but it needs honest logging.
Use it only if the team already tracks time well.

### Rules that prevent arguments

- **Agree before you start.** A split decided after a win is a negotiation;
  a split decided before is a plan.
- **Write it in the repo.** One line in a team note: who gets what percent.
  Everyone can see it, nobody can misremember it.
- **Pay promptly.** The person who claims the prize sends everyone their
  share within a day of the claim landing. Delay breeds suspicion.
- **Cover costs first.** If the team spent money — a proxy, a tool
  subscription, a domain — reimburse that from the prize before splitting the
  rest, if that is what you agreed.
- **One prize, one split.** Do not renegotiate per bounty. If the split
  needs changing, change it between bounties, never during one.

---

## Communication habits that keep a team fast

Speed matters in a 72-hour bounty. These habits are cheap and they compound.

1. **One channel for decisions.** Everything that changes the plan goes in
   one place. Side chats are for jokes, not for "I changed the approach".
2. **Write the decision, not just the chat.** When the team picks an
   approach, someone writes one line in the repo or the shared note: what was
   decided, when, and by whom.
3. **A short daily check-in.** Fifteen minutes, three questions: what did you
   finish, what are you doing next, what is blocking you. Do it even when
   there is nothing to report — silence is how duplicate work starts.
4. **Say "I'm doing X" before you start X.** The single best cure for two
   people doing the same work is a one-line message before you begin.
5. **Blockers go to the group immediately.** Stuck for more than thirty
   minutes? Say so. A teammate may know the answer in thirty seconds.
6. **No silent rewrites.** If you change someone else's work, say what you
   changed and why, in the commit message or the pull request.
7. **Keep a shared notes file.** Links, deadlines, caps, the referral code,
   the repo URL, the claim window — one file, always current.

---

## Common team mistakes

These are the failures I see small teams repeat. Each one is avoidable, and
each one has cost a real entry.

### Two people doing the same work

Both builders pick up the same task, both finish it, and one person's
afternoon is wasted — or both versions get merged and the entry breaks.
Fix: a tiny task list, one owner per task, and the "I'm doing X" message
before you start.

### Unreviewed submits

The builder submits straight from their branch because the deadline is
close. The entry is missing a badge, or the referral code is a placeholder.
The submission is refused and a cap slot is burned. Fix: the submitter never
submits unreviewed work, no matter how close the deadline is.

### Lost credentials

The payout wallet key, the API key, or the GitHub login lives in one
person's head, or in a chat message that scrolled away. The prize cannot be
claimed, or the repo cannot be pushed. Fix: the account owner keeps the
credentials, the team keeps a note of *who* holds *what* (never the secret
itself), and there is a backup person for the GitHub side at least.

### The brief nobody read

Three people build from three different understandings of the task because
only one person read the rules. Fix: the researcher writes the one-page
brief, and everyone reads it before writing a line.

### The merge that broke main

Two branches touch the same file, the merge is resolved in a hurry, and
`main` no longer builds. Fix: merge early and often, pull before you start
work, and never resolve a conflict without running the entry again.

### The silent teammate

Someone goes quiet for a day and the team assumes they are working. They are
not — they are stuck, or busy, or waiting on an answer. Fix: the daily
check-in, and a rule that silence for 24 hours means someone pings them.

### Arguing about the split after the win

Covered above. Decide before you start, write it down, pay promptly.

---

## After you submit

Submitting is not the end. Three things still need doing.

1. **Watch the entry status.** An accepted entry says so. A refused one
   names the failed check and its fix — fix it and resubmit while the window
   is open.
2. **Keep the repository as it is.** The final check reads the repository
   again after the deadline. It must still be public, still the same
   repository, still owned by the same account, and its README must still
   carry your referral code. Do not rename it, privatise it, or rewrite the
   README after the deadline.
3. **Claim inside the window.** Winners claim within 7 days of the results.
   An unclaimed prize passes to the next entry. Set a reminder the day
   results are published, and claim the same day.

Then do a short retro, while it is fresh: what worked, what was slow, what
would you change next time. Five lines in the repo are enough. The next
bounty starts from that note, not from zero.

---

## FAQ

**Do I need to know how to code to join make.fun?**

No. Your AI coding agent writes the code. You need to read the brief
carefully, judge the output, and make decisions. People who have never
written a line of code have placed in bounties by being good reviewers.

**Can my team really share one account?**

One account per person is the rule, and a team enters under one account and
splits the prize itself. That is how the platform expects teams to work: one
entry, one account, one shared repository, and the split handled between
teammates.

**What does the referral code do?**

When someone signs up through your link, their account is bound to your
code. In this bounty, verified human signups through your link are the
score. In general, the referral program also pays small rewards for signups
and first wins. Use your own link — here it is again:
https://make.fun/r/n2c7mbr7, code `n2c7mbr7`.

**What if our team disagrees on the approach?**

The researcher owns the brief and the recommendation; the team decides
together, and once decided, everyone builds toward it. A decision made and
executed beats a perfect plan debated until the deadline passes.

**Where do I learn more?**

Start at [make.fun](https://make.fun) — the bounty board, the skill guide,
and the press kit. Then pick one small bounty and enter it. The fastest way
to learn make.fun is to submit once and read what the checks tell you.

---

*Built by a small team, for small teams. Good luck — and if this guide helped
you get started, sign up through https://make.fun/r/n2c7mbr7 (`n2c7mbr7`) so
the team that wrote it gets the credit.*
