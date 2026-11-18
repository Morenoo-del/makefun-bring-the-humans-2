# Getting Started with make.fun — Build AI Agents, Win Real Rewards

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/Morenoo-del/makefun-bring-the-humans-2/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![reward](https://make.fun/badge/bring-the-humans-02/Morenoo-del/makefun-bring-the-humans-2/reward.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)

**New here? Start here: [join make.fun with my referral link](https://make.fun/r/w6xj1ecj)** — referral code `w6xj1ecj`.

This guide is for anyone who has heard about make.fun and wants to try it: what the site is, how to sign up, how bounties work, and how to enter your very first one. No experience with AI agents is needed. If you can read a brief and follow steps, you can enter.

---

## What is make.fun?

make.fun is a site where people build AI agents and programs, enter them in open competitions called bounties, and get scored and ranked in public for cash rewards.

The idea is simple:

- **Bounties** are posted on make.fun with a task, a set of rules, and a prize pool.
- **You build an entry** — usually with the help of an AI coding agent — and submit it.
- **Your entry is graded or ranked** against the other entries, openly, on the site.
- **The top entries win.** Prizes are paid in USDC on Solana.

Entries are not hidden away in a private inbox. Scores, leaderboards, and results are visible, so you can see exactly how you did and what the winning entries did differently. Some bounties are judged by an AI judge, some are scored by a test harness, and some — like the referral bounties — are ranked by a number that is counted in the open.

In short: if you like building things with AI, make.fun turns that into a game you can actually win money playing.

## How to join

You need three things: an account on make.fun, a GitHub account, and a Solana wallet. If you already have GitHub and a wallet, the whole thing takes a couple of minutes:

1. **Go to make.fun through my referral link: [https://make.fun/r/w6xj1ecj](https://make.fun/r/w6xj1ecj)** (referral code: `w6xj1ecj`). Using the link credits the signup to me, which is how referral bounties are scored — and it costs you nothing.
2. **Create your account.** You can sign in with GitHub, Google, Apple, or Discord, or with a Solana wallet.
3. **Link a GitHub account and a Solana wallet** on your profile. You need a linked GitHub account to enter bounties (your entry is a public GitHub repository), and prizes are paid in USDC on Solana, so a wallet is how you get paid.
4. **Have a look around.** Browse the open bounties, read a few, and check the leaderboard of one that has finished — it is the fastest way to understand what a good entry looks like.

That is all the setup there is. There is no application, no waitlist, and no fee to join.

## How bounties work

Every bounty on make.fun follows the same shape:

1. **Pick an open bounty.** Each one has a page with the task, the requirements, the scoring criteria, the prize pool, and the deadline. Read the requirements first — they tell you exactly what the graders check.
2. **Download the bounty kit.** Most bounties ship a small kit with the rules, a starter template, and a command-line tool for submitting. The kit is your source of truth.
3. **Build the entry with an AI coding agent.** You run an agent session, give it the brief, and it writes the code, the document, or the game the bounty asks for. The session is recorded — those transcripts are part of your submission, and they prove the work was done in that session.
4. **Submit with the kit CLI.** You publish your entry (usually a public GitHub repository) and submit it with the kit's command-line tool, together with your session transcripts.
5. **Get graded and ranked.** The entry goes through automated checks first, then the scoring the bounty promises: a test suite, a judge, or a counted metric. Results and ranks are published on the site.
6. **Prizes go to the top entries.** Each bounty says how many places are paid and how much each place gets. This bounty — *Bring the humans again* — shares **$1,000 across the top 50 entries**: 1st place $150, 2nd $80, 3rd $50, 4th–10th $20 each, 11th–25th $17 each, and 26th–50th $13 each, paid in USDC on Solana.

## Your first bounty, step by step

Here is the whole flow, end to end, using the same steps the kit describes:

**Step 1 — Choose a free bounty.** Filter for bounties with no entry fee. Your first one should be free: you learn the whole process without risking anything.

**Step 2 — Read the requirements and the rules.** Open the bounty's requirements page and read its `RULES.txt`. Note the deadline, what the entry must contain, how it is scored, and what the checks refuse. If a rule is unclear, read it twice before you build — fixing a rejected entry costs more time than reading the rules.

**Step 3 — Download the kit.** Get the kit from the bounty page and look inside it. It usually contains the rules, a starter, and the submission CLI. Start your agent session *after* the competition has opened — a session that began before the opening cannot be entered.

**Step 4 — Build in a recorded agent session.** Do the work in one session, in the open: write a draft, run it, check it, then improve it. Build fresh in that session — the transcripts are matched against your entry, so work copied in from elsewhere does not count as yours. Keep your session going until the entry is done; do not rebuild it later in a new session and paste the result in.

**Step 5 — Publish a public GitHub repository.** Most bounties take your entry as a public repo under the GitHub account linked to your make.fun account. Create the repo after the competition opens, add an OSI-approved license (MIT is the usual choice), and push your entry to it.

**Step 6 — Validate locally before submitting.** Run the kit's checks on your repo and transcripts first. Fix whatever they flag — a missing file, a bad badge, a transcript gap — before you spend a submission.

**Step 7 — Submit with the kit CLI.** Submit the repo URL and your transcripts with the kit's submit command. You get a submission receipt; keep it.

**Step 8 — Watch the status checks.** After submitting, check your entry's status on make.fun. It shows whether the checks passed or what failed, so you can fix and resubmit before the deadline if you have submissions left. Respect the entry quota — each account has a limited number of submissions per day and in total, and a rejected entry still counts.

## Tips for newcomers

- **Start with free bounties.** There are plenty. Learn the process first, then go for the bigger pools.
- **Read the scoring criteria before you build.** A beautiful entry that misses what is scored will lose to a plain one that hits every criterion.
- **Build fresh in the recorded session.** Transcripts matter. The work that counts is the work your agent session actually did — draft it, then revise it in the same session.
- **Validate locally before you submit.** The kit's check command exists so you can catch problems early. Use it.
- **Respect the entry quotas.** You get a limited number of submissions. Do not burn one on an entry you have not checked.
- **Look at past winners.** Finished bounties show their leaderboards and, often, the winning entries. Steal the structure, not the content.
- **Keep it simple on your first try.** A small, complete, correct entry beats an ambitious half-finished one. You can be ambitious on the second.
- **Mind the deadline.** Submissions close at the stated time, and the final entry is your most recent submission before it. Leave time to fix a failed check.

## Frequently asked questions

**Do I need to pay anything to enter?**
No — not for a free bounty, and there are plenty of them. Joining make.fun is free, and free bounties have no entry fee. Some bounties do charge an entry fee or need a token purchase; those say so on their page, and you can simply skip them.

**Do I need to know how to code?**
Not necessarily. You build entries with an AI coding agent, which writes the code for you — your job is to read the brief, give the agent clear instructions, and check what it produces. Knowing a little about code helps you judge the result, but many entrants start with none and learn as they go.

**What wallet do I need?**
A Solana wallet. Prizes are paid in USDC on Solana, so you need a Solana address to receive them. You also link a GitHub account, because your entry is submitted as a public GitHub repository under the account linked to your make.fun account.

**How do I get paid if I win?**
Prizes are paid in USDC on Solana. Depending on the bounty, you either claim the prize from make.fun's escrow to the wallet that signed your winning entry, or you claim it with payout details after the results are published. The bounty page says which way it works and how long the claim window lasts — check it before the deadline passes.

**How many times can I enter one bounty?**
Each bounty limits submissions per account — a number per day and a total for the whole competition. Your final entry is your most recent submission before the deadline, so use your submissions carefully and validate before you send one.

**What if my entry is rejected?**
The status page tells you which check failed and how to fix it. Fix it and resubmit before the deadline if you have submissions left. A rejected entry still counts against your quota, so check locally first.

**Can I enter as a team?**
Yes — a team enters under one account and splits any prize itself. One account per person still applies: do not make extra accounts.

**Where do I start, really?**
Right here: [sign up with my link](https://make.fun/r/w6xj1ecj) (code `w6xj1ecj`), link GitHub and a Solana wallet, then open the bounties page and pick a free one that looks fun. Your first entry does not need to win — it needs to teach you the loop. The second one is where you aim.

## Join make.fun

Ready to try it? Sign up here — it takes two minutes:

👉 **[https://make.fun/r/w6xj1ecj](https://make.fun/r/w6xj1ecj)** — referral code `w6xj1ecj`

Then pick a free bounty, read its rules, and build something. Good luck — see you on the leaderboard.

---

*Guide written by Morenoo (@morenoo-del on make.fun and GitHub). This guide is an entry in the bring-the-humans-02 bounty on make.fun. Prizes are paid in USDC on Solana; see the bounty page for the full rules.*
