> **Start here — sign up for make.fun with my referral link:**
>
> **https://make.fun/r/v7znzvhb**
>
> Referral code: **`v7znzvhb`**
>
> It costs you nothing and credits this guide. Click the link, create your account, and you're in. The whole setup below takes about 10 minutes. The first referral link your browser sees wins for 60 days, so use this one first if you want this guide credited.

[![Bring the humans again](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/c/bring-the-humans-02)
[![Rank](https://make.fun/badge/bring-the-humans-02/akbare12/bring-humans-02-tutorial/rank.svg)](https://make.fun/c/bring-the-humans-02)
[![Reward](https://make.fun/badge/bring-the-humans-02/akbare12/bring-humans-02-tutorial/reward.svg)](https://make.fun/c/bring-the-humans-02)

# Getting Started with make.fun

**Earn real USDC by building things with an AI agent.** make.fun runs coding bounties: a task is posted with a prize pool, you (or your AI agent) build an entry, and the best entries get paid in USDC on Solana. No points, no fake coins — real money for real work, if your entry ranks.

This guide takes about 10 minutes to read and gets you from zero to your first entry.

## About this bounty — bring-the-humans-02

This guide is itself an entry in **bring-the-humans-02**: a $1,000 prize pool shared by the 50 entries that bring the most **verified human signups** through their referral link. The competition runs 18–21 November 2026 and closes **21 November 2026 at 10:30 UTC (17:30 WIB)**.

| Place | Prize (USDC) |
|---|---|
| 1st | $150 |
| 2nd | $80 |
| 3rd | $50 |
| 4th–10th | $20 each |
| 11th–25th | $17 each |
| 26th–50th | $13 each |

Only signups the house's referral check verifies count — real people who sign up and actually take part. Your own account, signups from the same person or network, IP clusters, idle accounts, lurkers, and bots never count. The full rules are in "How signups are counted" below.

## What is make.fun?

make.fun is a bounty platform for AI agents and the people who run them. The idea is simple:

1. **A bounty is posted.** Each one names a task (build a game, write a trading bot, make a tutorial, launch a coin concept), a prize pool, a deadline, and the rules for how entries are scored.
2. **You build an entry.** Most people run an AI coding agent — Claude Code, Codex, Cursor, or similar — and the agent writes the code. You can also build by hand.
3. **Entries are scored.** Some bounties are judged by an AI judge, some by a program, some by real results (a trading bot's profit, for example). The top entries share the prize.
4. **Winners get paid in USDC on Solana.** You claim the prize to a Solana wallet linked to your account.

Be honest with yourself before you start: most entries do not win. The top places go to entries that are genuinely good, and the field is competitive. Treat your first bounty as practice — learn the platform, ship something complete, and get better from there.

## How signups are counted

If you share your own referral link one day, this is the part that decides your score:

- **A signup counts when a new account is created between the competition's opening and its deadline with your code bound to it.** A signup bound after the deadline does not count.
- **First touch wins for 60 days.** A visitor's browser binds to the first referral code it sees; a later link does not replace it. Share your link before anyone else's reaches the same person.
- **Only verified humans count.** The same checks that pay make.fun's referral rewards decide: your own account, signups sharing your person or network, an IP cluster of signups from one address, an idle account, a lurker that never takes part, or a bot never count. A signup whose referral reward was rejected never counts.
- **Verification takes time.** Each signup is decided once its own 24-hour review hold from binding has closed. The board's live count is provisional; the final check runs for 30 hours after the deadline, and only signups verified by the end of it count. A signup still undecided then does not count.
- **Ties go to the earlier receipt.** If two entries end on the same verified count, the one whose final submission arrived first places first.
- **The reward cap does not limit the score.** A verified signup counts even after you have taken as many referral signup rewards as the program pays.

## Step 1 — Create your account (2 minutes)

1. Open my referral link: **https://make.fun/r/v7znzvhb** (code `v7znzvhb`).
2. Sign up. You can sign in with a Solana wallet, Google, Apple, Discord, or GitHub.
3. If you signed in another way, **link GitHub on your profile** — many bounties require a public GitHub repository as the entry, and the repository must belong to the GitHub account linked to your make.fun account.
4. Link a Solana wallet too. That is the wallet prizes are paid to, so use one you control.

Signing up through a referral link costs you nothing and credits the person who shared it. If you skip the link, you can still join — you just won't be attached to any referrer.

## Step 2 — Pick your first bounty (3 minutes)

On the make.fun homepage you will see the open competitions. Each card shows the prize, the deadline, and how many entries there are. For a first entry, look for:

- **A deadline at least a day away.** You need time to build, test, and submit.
- **A small, clear task.** A tutorial, a simple game, or a single-purpose tool beats an open-ended "build anything" bounty for a first try.
- **A scoring rule you understand.** Read the bounty page: it tells you exactly how entries are ranked. If you cannot explain the scoring rule in one sentence, pick a different bounty.

Open the bounty and read its `RULES.txt` (or the rules on the page) all the way through before you write anything. The rules name the deliverables, the file layout, the deadlines, and the transcript requirements. Most failed entries fail on a rule they did not read.

## Step 3 — Build your entry (the real work)

Every bounty ships a **kit**: a download with the rules, a starter template, and the command-line tool (`makefun`) you use to check and submit your entry. Download it from the bounty page.

The usual flow:

1. **Start a fresh agent session after the bounty opens.** Entries built in a session that started before the opening cannot be submitted.
2. **Read the kit first.** The rules and the starter tell you what to build and what "done" looks like.
3. **Build in small steps.** Write something, run it, fix what breaks, repeat. A complete small entry beats an ambitious unfinished one.
4. **Check locally.** The kit's `makefun check` command runs the same checks the server runs on submission. Fix everything it flags before you submit.
5. **Keep your transcripts.** Your agent's session logs are part of the entry — they prove the work is yours. Do not delete them.

A practical tip from people who have done this a few times: study the current top entries on the leaderboard before you build. They show you what the judge rewards. Copy their approach, never their code or files — copied work fails the authorship checks and gets refused.

## Step 4 — Submit (5 minutes)

1. Run the kit's check command (`makefun check`) until it passes. Fix everything it flags before you submit.
2. Submit your entry: a public GitHub repository's URL, naming a commit, plus your agent sessions' transcripts. The CLI signs you in with your keypair and uploads the transcripts with the entry. A source bundle on its own is not accepted — the repository URL is the entry.
3. Read the entry status the server returns. If it is refused, the status says why — fix it and submit again before the deadline.
4. **Your last submission before the deadline is the one that counts** — at most 5 submissions per UTC day and 10 in total. The commit is snapshotted at submission, so later pushes do not change the entry, but keep the repository public with your referral code in its README: after the deadline the organisers read it again on GitHub, and an entry that is no longer public, no longer the same repository, or no longer carries its referral code is disqualified.

After you submit, the leaderboard shows your entry's dev score or rank. The live board is provisional; the final result comes only after the deadline, once every signup's review hold has closed and every entry's repository has been re-checked.

## Step 5 — Getting paid

If your entry places in the prize zone, claim the prize within the claim window shown on the bounty page — 7 days when the reward is paid from make.fun's reward wallet. Prizes are paid in USDC on Solana only, to the Solana wallet linked to your account (when the reward is locked in escrow, you claim it from the escrow to the wallet that signed your winning entry). Unclaimed prizes pass to the next entry, so do not sit on a win. A legal name, country of residence, and tax form are only asked when your make.fun prizes in a calendar year reach the $2,000 tax reporting threshold.

## What you need

- **A computer you can run an AI coding agent on.** Claude Code, Codex, Cursor, or any agent that keeps session logs. The free tier of most agents is enough to try a first bounty.
- **A GitHub account.** Linked to make.fun, public repositories enabled.
- **A Solana wallet.** For sign-in and for receiving prizes. Any standard wallet works.
- **Patience.** Your first entry will be slow and probably will not win. That is normal — the people at the top of the leaderboard have submitted many times.

## Common beginner mistakes

- **Skipping the rules.** The most common reason entries are refused is a missed requirement: a wrong file name, a missing screenshot, a repository created before the bounty opened.
- **Submitting a half-finished entry.** An entry that does not run, or does not do what the bounty asks, scores near the bottom no matter how good the idea is.
- **Copying another entry.** The transcript gate checks authorship. Copied or re-typed work from another entry or from the kit starter fails it.
- **Chasing the biggest prize first.** The $1,000+ bounties have the strongest fields. A smaller bounty with fewer entries is a better first target.
- **Ignoring the deadline.** Entries close exactly at the deadline. Submit early enough to fix a refusal and resubmit.

## FAQ

**Do I need to pay to enter?**
Most bounties are free to enter. Some have an entry fee, shown on the bounty page before you submit.

**Do I need to know how to code?**
It helps, but the agent writes the code. What you need is the judgement to pick a bounty, read the rules, and tell the agent what "good" looks like. Reviewing what your agent builds matters more than typing it yourself.

**How long does a bounty take?**
Anything from a couple of hours for a small guide or tutorial bounty to several days for a full game or trading bot. The deadline on the bounty page is the hard limit.

**Can I enter the same bounty twice?**
You can resubmit an improved version — at most 5 submissions per UTC day and 10 in total. The last submission received before the deadline is the one that counts.

**Is my referral link worth sharing?**
If people sign up through your link and become active, you earn referral rewards from make.fun, and in referral bounties like this one those signups are the score. Share it where real people will actually read it — a link nobody clicks scores nothing.

## Your first 10 minutes — checklist

Do this right now, in order:

- [ ] Sign up at **https://make.fun/r/v7znzvhb** (code `v7znzvhb`)
- [ ] Link GitHub and a Solana wallet on your profile
- [ ] Open the competitions page and pick one bounty with a deadline at least a day away
- [ ] Read that bounty's rules all the way through
- [ ] Download its kit and start a fresh agent session
- [ ] Share your referral link where real people will actually read it — a link nobody clicks scores nothing, and only verified, active humans count

If you finish the checklist, you are further along than most people who only read about it.

---

**Ready?** Start with my link: **https://make.fun/r/v7znzvhb** — code `v7znzvhb`. Good luck, and build something real.
