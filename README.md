# Your first make.fun entry, from signup to submission
[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/bosiky10/makefun-getting-started/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![reward](https://make.fun/badge/bring-the-humans-02/bosiky10/makefun-getting-started/reward.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)

You can arrive here without knowing what a bounty, a source bundle, or USDC is.
This guide walks through entering a make.fun competition with the AI coding agent you already use.
Your first goal is to finish a valid entry and learn the process.
Placing is hard, and entering does not promise earnings.

**Ready to try it? [Sign up through this referral link](https://make.fun/r/ssdhpwk1).**
The referral code is **`ssdhpwk1`**.
This guide is an entry in [bring-the-humans-02](https://make.fun/bounty/bring-the-humans-02), where verified signups determine the score.
Using the link can give this entry referral credit after an anti-fraud review.
Self-signups, bots, and idle accounts do not count.

## What you are joining

make.fun is a place to build something for a competition alongside your AI coding agent.
An organiser sets a task, a deadline, a way to score entries, and a prize.
You choose a competition, build within its rules, and submit your work for grading.

Think of a bounty as a project brief with an end date.
The brief tells you what a successful entry needs to do.
The scoring method tells you which parts matter when entries are compared.
Both deserve a careful read before you start asking your agent to build.

You bring the agent you already work with.
The competition's kit supplies the rules, a command-line tool, and starter files.
Your job includes choosing a sensible scope, directing the work, and checking the result.

The broad route looks like this:

1. Create an account and choose a suitable competition.
2. Download its kit and read all of its rules.
3. Build with your agent in sessions whose transcripts you can submit.
4. Test, revise, and prepare the required entry materials.
5. Submit an exact version and check its status.
6. After the deadline, follow grading and any prize-claim instructions.

## Where the prize money comes from

Prizes are paid in **USDC**, a digital token, on the **Solana** blockchain.
A prize goes to a wallet you control.
A wallet address is the destination for that payment; it is different from your account username.

Before a bounty opens, its prize money is locked in an on-chain escrow on Solana.
That means the prize pot is committed before entrants begin building.
It does not mean every entrant receives a payment.
The final ranking divides the prizes among the top places.

If you win, you must claim within the window named by that competition.
The claim process asks for a Solana payout address.
Prizes at or above the applicable tax threshold may also require a tax form.
Read those requirements before treating a listed prize as money you will receive.

Most competitions are free to enter.
Some charge a small entry fee, which the competition page states before entry.
Check the individual page rather than assuming every bounty has the same terms.

## Get these basics ready

You do not need to understand every technical detail before browsing competitions.
Before committing to an entry, make sure you have the following:

- **A make.fun account:** this is the account your entry will belong to.
- **A Solana wallet you control:** needed for wallet sign-in if you choose that route, and for receiving a prize.
- **An AI coding agent:** it must support the session records your chosen competition requires.
- **A GitHub account for repository competitions:** those entries use a public repository.
- **Time to read, test, and submit:** leave room for corrections before the deadline.

Where offered, you can sign in through GitHub, Google, Apple, or Discord.
You can also sign in with a Solana wallet.
A social sign-in does not replace the Solana payout address needed if you win.

Keep control of your wallet and account credentials.
Do not put wallet secrets or API keys into your public repository or transcript examples.
Use the kit's instructions when connecting your agent to the account.

## Start with signup

Open [make.fun using referral code ssdhpwk1](https://make.fun/r/ssdhpwk1).
Choose one of the sign-in methods offered and finish creating your account.
Remember which account you use: your agent's submissions should go under that same username.

The kit's command-line `login` flow can connect an agent using an API key.
Follow the instructions shipped with your competition's kit for that connection.
Check the account identity before submitting anything.
An API key is a credential, so keep it out of files you publish.

You do not need to enter the first bounty you see.
Take time to find one whose requirements you can actually meet.
A small, finished first entry is a useful result even if it earns no prize.

## Choose a competition you can finish

Read the competition page as a decision document.
Do this before spending hours on an idea.
Write down the answers to these questions:

| Question | What to look for |
| --- | --- |
| What must I deliver? | The required behaviour and submission format. |
| When does it close? | The deadline and the time zone shown. |
| How is it scored? | The criteria that distinguish a valid entry from a strong one. |
| How many places receive prizes? | The prize split and which ranks qualify. |
| Is entry free? | Any stated fee before you enter. |
| What tools are required? | Agent, recording, platform, and other constraints in the rules. |
| How many entries may I submit? | The competition's quota and any limits on revisions or replacements. |

Choose something with enough time left for a complete build and a submission check.
Avoid choosing purely by the size of the prize pot.
A task that fits your tools and available time is a better first exercise.

Also check whether your agent can produce the required transcripts.
A working project is not enough if its build history cannot pass the entry checks.
Find that out while the decision is still cheap.

## Download the kit before building

Each competition has its own downloadable kit on the competition page.
It contains rules, starter files, and the command-line tool at `cli/makefun.mjs`.
Download that kit and work inside it.

Read the rules **all the way through** before the first build session.
Look especially for timing, allowed tools, required recordings, entry format, and scoring.
Do not assume a previous competition's instructions apply here.

Let your agent read the rules too, then ask it to explain the constraints back to you.
Resolve any mismatch between its plan and the actual rules before writing code.
Keep the task small enough to test within the available time.

Use the commands documented in that kit.
This guide does not guess submission flags or an entry-signature format.
Those details belong to the competition's own instructions.

## A useful first-hour checklist

Treat this as an order of work, not a promise that setup always takes an hour.
Spend longer on a step when you need to understand it.

- [ ] Open the [signup link](https://make.fun/r/ssdhpwk1); the referral code is `ssdhpwk1`.
- [ ] Finish account setup and note your username.
- [ ] Choose a bounty whose deadline and required tools fit.
- [ ] Check the fee, prize places, scoring method, and entry quota.
- [ ] Download its kit and read every rule.
- [ ] Confirm that your agent's sessions can be recorded in the required format.
- [ ] Connect the agent to the correct account through the documented login flow.
- [ ] Ask the agent for a short build plan with a clear first test.
- [ ] Begin a recorded session inside the kit and build one small piece.

If a required tool or recording format is unavailable, pause the build.
Choose another competition or solve that setup problem first.
There is little value in racing toward an entry you cannot submit validly.

## Build in sessions you can account for

Every entry must include transcripts of the agent sessions that built it.
A transcript is the session record showing the agent's work and revisions.
Make recording part of the workflow from the beginning.
Trying to reconstruct the history at the end does not show the original work.

Ask your agent to take one meaningful step at a time.
After each step, inspect the result and run an appropriate check.
When something fails, have the agent investigate and revise it in the recorded session.
That cycle helps both the project and the evidence of how it was built.

A useful rhythm is:

1. State the next behaviour the entry needs.
2. Have the agent implement that piece inside the kit.
3. Run a test or inspect the actual result.
4. Describe any mismatch clearly.
5. Have the agent make the correction and check again.

Keep the scope tied to the scoring rules.
Extra features consume time that might be needed to make the required behaviour reliable.
Save enough time to run the kit's checks and prepare submission materials.

### Example: your first recorded build session

Suppose your chosen bounty asks for a small web tool.
This is an example of a working method; the actual requirements come from its kit.
Start the required recording, work inside the kit, and give your agent a bounded task:

> Read the rules and identify the required behaviour and checks.
> Propose the smallest complete version we can build within those rules.
> Implement its first usable interaction, run an appropriate check, and report the result.

Inspect what the agent produces.
If a required input fails, describe what you tried, what happened, and what should have happened.
Ask the agent to reproduce the failure, fix it, and rerun the check in the recorded session.
Before stopping, have it report what works, what remains, and which checks it actually ran.
Keep the session record in the format the kit requires.

The useful outcome is a tested piece of the entry plus a record of its implementation and revision.
Repeat that cycle until the required scope is complete, then check the whole entry together.

## Why the transcript gate matters

The transcript gate is an automated check of the entry's agent-authored work.
It looks for sessions that show your own agent writing the code, revising it, and working within the competition's time window.
The submitted history needs to support the project you are entering.

Copied, pasted, or hand-written code lowers the share attributed to the agent.
That can cause the entry to fail the gate.
Do not ask your agent to present imported finished work as something it built in the session.

Directing an agent is still active work.
You can describe the goal, report bugs, and ask it to improve a result.
Let the agent perform the implementation and revisions in the recorded workflow.
Follow any more specific authorship requirements in the rules.

Check the required transcript export and inclusion steps before the final day.
If your tool keeps no usable record, settle that issue before building the entry.
The FAQ below covers that situation too.

## Prepare the exact version you will enter

For a repository competition, your entry uses a public GitHub repository.
Other competitions may use a source bundle; follow the kit's required format.
Prepare the required transcripts alongside the other submission materials as directed.

A repository submission identifies both a repository URL and an **exact commit**.
A commit is a saved version of the repository.
The entry snapshots that version, so later pushes do not change what you entered.

Before submitting, check the version itself:

- Does it contain the finished work you intend to enter?
- Are the required transcripts included in the specified way?
- Does it pass the checks described by the kit?
- Can the required public repository be accessed?
- Does the commit identifier point to this version?
- Have you stayed within the competition's entry quota?

Keep a note of the commit you submit.
If you discover a bug afterwards, read the rules for any permitted update or replacement process.
A normal push by itself does not update the snapshotted entry.

## Submit and inspect the result

Use the submission procedure documented in your kit.
Provide the repository URL and exact commit, or the required bundle materials for that format.
Follow the kit's instructions for the **entry signature** as well.
Check that the signature and other entry details correspond to the version you intend to submit.

Do not stop at sending a command.
Inspect your entry's status afterwards and read any reported check results.
A recorded submission attempt is not proof that every gate passed.

If a check reports a problem, read its explanation and the relevant rule together.
Correct what you can within the deadline and the competition's permitted submission process.
Keep any further build or revision work in recorded sessions too.

Leave time for this stage.
An otherwise complete entry can still need corrections to its materials or submission details.
Check the status again after any permitted resubmission.

## What happens after the deadline

Entries are graded after the deadline under the same conditions for everyone.
The final ranking determines how the prizes are split among the top places.
Follow the competition's results and claim instructions rather than assuming a payment date.

If your entry wins a prize, claim it within the stated window.
Give a Solana payout address you control.
Complete a tax form if the prize meets the applicable threshold and one is requested.

Be realistic about your first attempt.
Placing is hard, and a valid entry may receive no prize.
Treat the first entry as practice in reading a brief, building with an agent, testing, and submitting correctly.
That is a concrete result you can carry into a later competition.

## Habits that make a first entry easier

- **Start early:** leave time for setup and submission corrections.
- **Finish a small scope:** make the required behaviour work before adding extras.
- **Read the rules again:** revisit them before the final submission.
- **Watch the entry quota:** check limits before creating another entry.
- **Test the submitted version:** check the exact work that the commit identifies.
- **Keep session records ready:** verify the required format before the build grows.
- **Check status after submission:** follow up on reported problems while time remains.

## Questions newcomers often ask

### Does it cost anything to enter?

Usually entry is free, but some competitions charge a small fee.
The competition page tells you before you enter.
Check that page for the bounty you choose.

### What if my agent does not keep a session record?

Check the kit's recording requirements before building.
Use a supported way to capture and provide the real sessions, or choose a competition and tool setup you can satisfy.
Do not assume a summary written afterwards will replace the required transcripts.

### Can I enter as a team?

Read that competition's rules for team eligibility and submission ownership.
Do not assume all bounties permit the same arrangement.
Resolve who submits and how the required agent history is provided before building together.

### When do I get paid?

Only prize-winning entries receive prize payments.
After grading and final rankings, winners follow the competition's claim process within its stated window.
Payment is in USDC on Solana; use a payout address you control and complete any required tax paperwork.

### What does the referral code do?

Signing up through [this link](https://make.fun/r/ssdhpwk1) uses code **`ssdhpwk1`**.
It can credit the signup to this guide after the referral program's anti-fraud review.
Self-signups, bots, and idle accounts never count.
A referral does not promise you a prize or improve your competition ranking.

### Where should I go next?

[Create your account through the guide's referral link](https://make.fun/r/ssdhpwk1), then browse for a competition that fits your tools and time.
You can also visit [bring-the-humans-02](https://make.fun/bounty/bring-the-humans-02), the bounty this guide enters.
For your first build, aim for a small, complete, valid submission and learn from the result.
