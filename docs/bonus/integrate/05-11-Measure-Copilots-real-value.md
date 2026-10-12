# Chapter 5.11: Measure Copilot's real value

It's tempting to assume that a task done with Copilot is a task done better. Often it is. Sometimes the time saved on drafting is spent on checking, the errors take longer to fix than the original work would have taken, or the output is produced faster and read by nobody. You can't tell which from impressions. A routine that seems quick may cost you more than the manual version, and one that seems fiddly may be saving an hour a week. In this chapter, you'll record a baseline before you change anything, measure five things during a trial, and use the results to decide whether to keep, improve, or stop a routine. By the end, you'll have evidence about one of your own Copilot routines, and a decision based on it.

> **Sample files**: This chapter uses `value-tracker.xlsx` from the `Book5/Chapter5.11` folder. It has a sheet for the baseline, a sheet for the trial, and a summary that calculates the comparison.

## Understand why impressions mislead

Three things make it hard to judge Copilot's value without measuring.

**The fast part is visible, and the slow part isn't.** You see a draft appear in ten seconds. You don't count the eight minutes spent checking it, the correction you sent to a colleague the next day, or the time you spent adjusting the prompt.

**New tools are more interesting than old ones.** A routine can seem better because it's new. That effect fades, and the routine has to be worth keeping after it has.

**Saved time doesn't always turn into anything.** One analyst quoted by Computerworld warned that organizations "can automate 20 minutes of work but simply spend that time elsewhere." If 20 saved minutes disappear into email, the routine has changed how the time was used and nothing else.

Measuring doesn't need to be elaborate. A few numbers, recorded honestly for a few weeks, tell you more than any amount of impression.

Figure 5.11.1 shows the process.

*Figure 5.11.1: Measure before you change anything, run a trial, measure again, and then decide to keep, improve, or stop.* [Diagram 5.11-A]

## Establish a baseline before automating

A **baseline** is a record of how a task goes now, before Copilot is involved. Without it, you have nothing to compare with. And once you've changed how you do a task, you can't go back and measure the old way accurately.

Record the baseline for one task over at least three occasions. For each occasion, note:

| Measure | What to record | How |
| --- | --- | --- |
| **Time** | Minutes from start to finish, including finding the information | A timer, started when you begin and stopped when you send or save |
| **Rework** | Whether you or anyone else had to correct it afterward, and how long that took | A note at the time, and again a week later |
| **Accuracy** | Errors found, by you or by the recipient | Count them |
| **Satisfaction** | Whether the result did its job for the person who received it | Ask them, with one question |
| **Frequency** | How often the task happens | From your inventory in Chapter 5.1 |

Use a timer. Estimates of how long a task takes are often wrong.

Three occasions give you a range. A weekly report might take 40, 55, and 35 minutes. Record all three. The variation is useful to know.

If you've already started using Copilot for the task, you can still build a baseline. Do the task by hand once or twice more and time it, or measure a similar task that you haven't yet changed.

## Measure time, rework, accuracy, satisfaction, and cost

During the trial, measure the same things, plus the cost of using Copilot. Be thorough about time. Figure 5.11.2 shows what to include.

*Figure 5.11.2: The time a Copilot routine takes includes preparing, waiting, reviewing, and fixing. Compare the whole of it with the manual time.* [Diagram 5.11-B]

**Time.** Count all of it:

- **Preparing**: opening files, filling in the prompt's parameters, and attaching sources.
- **Waiting**: time when you can't do anything else. A two-minute wait that you spend on other work costs nothing. A two-minute wait that you spend watching costs two minutes.
- **Reviewing**: reading and checking the output against its sources.
- **Fixing**: correcting the output, or prompting again.
- **Maintaining**: time spent adjusting the prompt or repairing the automation, spread across the runs.

Net time saved is the baseline time minus the total of these.

**Rework.** Record corrections made after the result was sent or used. Rework is where a quick routine often loses its advantage. A report that takes 10 minutes to produce and 30 minutes to correct after a colleague spots an error has cost more than the 40-minute manual version, and it has also cost some of that colleague's confidence.

**Accuracy.** Count the errors you find in review, and the errors found by others afterward. The second number is the one that counts most. Errors that reach other people are the ones that damage trust.

**Satisfaction.** Ask the people who receive the output. One question is enough: "Is this more useful, less useful, or about the same as before?" Ask what they'd change. If you're the only recipient, ask yourself whether you read it and act on it.

**Cost.** Record what the routine uses:

- For Cowork tasks, type `/cost` after a run, and note the credits used.
- For features that use AI credits on personal plans, note how many each run takes, if your account shows it.
- Add a share of your subscription or license, if you're judging whether a plan is worth paying for.

On a work account, ask your administrator what a Copilot Credit costs your organization, so that you can turn credits into money.

> **Watch out**: Measuring only the time to produce a first draft will make almost any Copilot routine look good. The draft is the fastest part. Include review and rework every time, or your figures will tell you what you hoped to hear.

## Run a fair trial

A trial is a fixed period in which you use the new routine and record what happens. A few rules make it fair.

- **Run it for long enough.** At least four occasions for a weekly task, or two weeks for a daily one. The first one or two runs are slower while you learn, and they shouldn't decide the result.
- **Change one thing.** If you change the prompt, the data source, and the report's format in the same month, you won't know which change made the difference.
- **Keep reviewing properly.** Don't shorten your review to make the numbers look better. A trial with careless review measures a routine you shouldn't be running.
- **Record the bad runs.** The week when the file was missing and you did the task by hand counts. So does the hour you spent fixing the prompt.
- **Decide your test in advance.** Before you start, write down what would make you keep the routine, and what would make you stop. For example: "Keep it if it saves at least 15 minutes a week with no more errors reaching the reader."

Writing the test first protects you from talking yourself into a result afterward.

## Decide whether to keep, improve, or stop

At the end of the trial, compare the figures and make one of three decisions.

| Decision | When | What to do |
| --- | --- | --- |
| **Keep** | Time is saved after review and rework, errors reaching others haven't risen, recipients are at least as satisfied, and the cost is justified | Add it to your system, and set a date to measure again |
| **Improve** | It's close, or one measure is poor while the others are good | Change one thing, and run another short trial |
| **Stop** | It costs more time than it saves, more errors are reaching people, recipients find it less useful, or nobody uses the output | Go back to the manual method, or drop the task |

A worked example, for the weekly health check from Book 4:

| Measure | Baseline (manual) | Trial (recurring Cowork task) |
| --- | --- | --- |
| Time each week | 40 minutes | 3 preparing, 9 reviewing, 4 fixing: 16 minutes |
| Rework after sending | Once in three weeks, 10 minutes | Once in four weeks, 15 minutes |
| Errors found by the reader | 1 in three weeks | 1 in four weeks |
| Reader's view | Useful | About the same, and it arrives earlier |
| Cost each run | None | [Credits from `/cost`] |
| Maintenance | None | 30 minutes in the month, to fix a folder name |

Net time saved is about 24 minutes a week, less roughly 8 minutes a week of maintenance, with similar accuracy. That's a routine to keep, with a note to reduce the fixing time. If the review had taken 30 minutes, or if two errors had reached the reader, the decision would be different.

The decision to stop is as valuable as the decision to keep. A routine that doesn't work uses your time, your attention, and your credits. Stopping it frees all three for one that does. Chapter 4.12 listed the signs that an automation should be switched off, and this chapter gives you the evidence.

Some results point to improvement:

- **Review takes too long.** Add checks to the prompt that make errors visible, such as row counts, as in Chapter 4.2.
- **Fixing takes too long.** Find the correction you make most often, and build it into the prompt.
- **Recipients don't value it.** Ask what they need. The answer may be a shorter report, or none.
- **The cost is high.** Lower the reasoning effort, narrow the sources, or run it less often, as in Chapter 4.4.

> **Good practice**: Decide what the saved time is for. If a routine saves you 30 minutes a week, put a 30-minute block in your calendar for something that has been waiting, such as a conversation with a customer, a piece of planning, or leaving on time. Time that isn't assigned to anything is absorbed without trace.

## Look beyond time

Time is the easiest thing to measure, and it isn't always the most important. Record these as well, in words if not in numbers:

- **Quality.** Is the work better? A briefing that's more complete, or a report that reaches people a day earlier, has value even if it takes as long.
- **Things you now do that you didn't before.** If Copilot lets you prepare for every meeting when you used to prepare for half, the gain doesn't show up as time saved.
- **Reliability.** A task that used to be forgotten one week in four, and now always happens, is worth more than its minutes.
- **Your own energy.** If a routine removes a job you dreaded, that counts.
- **What you've stopped practicing.** Be honest about this too. If you no longer write a certain kind of document yourself, notice whether you could still do it well without help.

## Measure for a team

If you lead a team or run a pilot, the same method applies, with three cautions.

- **Measure tasks, and avoid measuring people.** Compare how long a task takes with and without Copilot. Don't rank individuals by how much they use it. That encourages use for its own sake.
- **Count the whole cost.** Include licenses, credits, training time, and the time colleagues spend reviewing each other's Copilot-assisted work.
- **Ask the people on the receiving end.** A team may produce reports faster while the readers find them less useful.

Your organization's administrators have reports on Copilot usage and credit consumption. They show how much the tools are used. They don't show whether the work is better. For that, you need baselines and trials for specific tasks.

## Try it now

Measure one routine against its baseline, and decide what to do with it:

1. Open `value-tracker.xlsx`. Choose one routine from your system in Chapter 5.1, ideally one that you haven't yet handed to Copilot.
2. Write your test in advance: what result would make you keep the routine, and what would make you stop.
3. Do the task by hand, and time it. Record the time, any rework, any errors, and the recipient's view. Repeat on two more occasions if you can. If the task is already automated, do it by hand once to get a figure.
4. Run the task with Copilot. Time each part separately: preparing, waiting, reviewing, and fixing.
5. Record the cost, with `/cost` or from your account.
6. Repeat for at least four occasions, or two weeks. Record every run, including the ones that go badly.
7. Ask the recipient the one question: more useful, less useful, or about the same?
8. Compare the trial with the baseline on the summary sheet. Apply the test you wrote in step 2.
9. Decide: keep, improve, or stop. If you're keeping it, decide what the saved time is for, and set a date to measure again.

You should now have a baseline, a trial record, a comparison, and a decision with a reason.

> **What to ask next**: Ask Copilot to look at your figures for what you might have missed: `Here are my baseline and trial measurements for a routine: [paste them]. What costs or effects might I not have counted? What would you want to know before agreeing with my decision?`

### Check the result

- [ ] Did you record a baseline before you changed how you do the task?
- [ ] Does your trial time include reviewing, fixing, and maintaining, and not only producing?
- [ ] Did you ask at least one recipient whether the result is more or less useful?
- [ ] Did you apply the test that you wrote before the trial began?
- [ ] Have you decided what the saved time is for?

> **Real-world example**: An operations manager at a catering company believes that her daily Copilot briefing saves her half an hour each morning. She times it for two weeks. The briefing takes two minutes to read, but she still scans her inbox for 20 minutes afterward, because she doesn't trust it to catch supplier changes. Net saving: almost nothing. She adds a line to the prompt that lists any message from a supplier about a delivery, checks it against her inbox for a week, and finds that it catches them all. Her inbox scan drops to five minutes. Without the measurement, she'd have kept both habits.

You have a system, the checks to run it responsibly, and a way to measure it. The final chapter puts them on a calendar. [*Chapter 5.12, Complete a 30-day Copilot adoption plan*](05-12-Complete-a-30-day-Copilot-adoption-plan.md), takes one recurring problem from first idea to a measured, working routine in four weeks.

[Go to next chapter >>](05-12-Complete-a-30-day-Copilot-adoption-plan.md)
