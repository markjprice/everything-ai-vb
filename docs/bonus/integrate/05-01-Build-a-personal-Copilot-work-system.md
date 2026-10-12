# Chapter 5.1: Build a personal Copilot work system

Knowing how to use Copilot and using it every week are different things. You can learn a tool, try it for two weeks, and then drift back to your old habits, because nothing in your week reminds you to use it. A work system fixes that. It's a short list of routines, each tied to a moment in your day, week, or month, where Copilot does a defined job and you check the result. In this chapter, you'll take an inventory of your repeated work, find the best places for Copilot, choose one low-risk process to start with, and set up a daily starting point. By the end, you'll have a one-page plan of where Copilot fits in your work.

> **Sample files**: This chapter uses `work-inventory.xlsx` from the `Book5/Chapter5.1` folder. It's an empty table with the columns described in this chapter.

## Inventory your repeated work and information sources

You can't choose where Copilot fits until you can see what you do. You may be surprised by how much of your work repeats.

Figure 5.1.1 shows the path from an inventory to a habit.

*Figure 5.1.1: From an inventory of your work to a habit. Most tasks on the inventory go no further than the first stage, and that's the intention.* [Diagram 5.1-A]

Build your inventory from evidence. Look back over the last four weeks of your calendar, your sent email, and your task list. For each task you did more than once, record six things:

| Column | What to record | Example |
| --- | --- | --- |
| **Task** | What you do, in a few words | Prepare the weekly team update |
| **How often** | Daily, weekly, monthly, or when something happens | Weekly |
| **Time each time** | Your best estimate, in minutes | 45 |
| **Sources** | Where the information comes from | Team channel, project plan, my notes |
| **Output** | What you produce, and who receives it | An email to my manager |
| **If it's wrong** | What would happen | She'd act on a wrong status |

With a work account, Copilot can help you find tasks you've forgotten.

Ask Copilot to look for repeated work in your own calendar and email:

```
Look at my calendar and my sent email for the last four weeks. List the tasks I seem to repeat, such as recurring meetings I prepare for, reports or updates I send regularly, and requests I answer more than once. For each one, say how often it happens and what evidence you used. Don't include one-off items.
```

Treat the answer as a list of prompts for your memory. Copilot sees what was written down. It doesn't see the phone calls, the conversations at someone's desk, or the hour you spent thinking. Add those yourself.

Then list your **information sources**: the places you go to find things out. You'll probably find fewer than ten. They might include a team channel, two or three shared folders, a business system, and a handful of people. Note which of them Copilot can reach with your account, using what you learned in Chapters 1.2 and 3.1. A task whose sources Copilot can't reach is a poor candidate, however often it repeats.

## Select daily, weekly, and monthly opportunities

An inventory of 20 or 30 tasks is too many to act on. Reduce it in two passes.

**First, score each task.** Use the four questions from Chapter 4.1: how repeatable it is, the impact of a mistake, how easily you'd spot an error, and how urgent the result is. Add a fifth: can Copilot reach the sources? Cross out any task where a mistake would be serious and hard to spot, and any task that involves a decision about a person.

**Second, sort what's left by rhythm.** A work system has three rhythms, as Figure 5.1.2 shows.

*Figure 5.1.2: A personal work system has a daily, a weekly, and a monthly rhythm. Each needs only one or two routines.* [Diagram 5.1-B]

| Rhythm | Typical routines | What Copilot does | What you do |
| --- | --- | --- | --- |
| **Daily** | A morning briefing, catching up on a channel, triaging email | Gathers and summarizes | Decide what needs you today |
| **Weekly** | A week-ahead view, a status update, meeting preparation | Drafts from your sources | Check, correct, and send |
| **Monthly** | A report, a review of your automations, a tidy-up of shared files | Compares, totals, and lists | Judge what it means |

Choose one or two candidates for each rhythm. Six routines that you keep are worth more than twenty that you abandon.

For each candidate, write one line about the benefit you expect. Be specific. "Saves time" tells you nothing. "Cuts the weekly update from 45 minutes to 15, and I stop forgetting the overdue items" gives you something to check later. Chapter 5.11 shows you how to measure it.

## Begin with one low-risk process

From your short list, choose one routine to set up first. The right first choice is rarely the one that would save the most time. It's the one most likely to work.

A good first process is:

- **Frequent.** Weekly or daily, so that you get practice quickly and see results within a month.
- **Low-risk.** If it's wrong, you'd notice, and nobody else would be affected.
- **Yours.** You do it, you receive the output, and you don't need anyone's permission to change how you do it.
- **Annoying.** You'd be glad to spend less time on it. That keeps you going through the first few weeks, when the routine is still being adjusted.

A week-ahead view of your own calendar is a good example. So is a summary of a channel you follow, or a first draft of an update that you always rewrite anyway.

Start it on the lowest rung of the ladder from Chapter 4.1: a prompt you run by hand. Save it when it works, as in Chapter 4.2. Schedule it only when you've stopped changing it.

> **Watch out**: Don't begin with the task that worries you most or that has the highest stakes. If your first attempt involves a report to the board, a customer message, or a decision about a colleague, an early mistake will cost you more than the routine could save, and it may put you off the whole idea. Earn your own trust on small things first.

## Set up a daily starting point

A system needs a place where it starts each day. Without one, you'll open your inbox, get pulled into the first message, and remember your Copilot routines at four in the afternoon.

The simplest starting point is a short daily briefing that's waiting for you each morning.

Ask Copilot for a briefing that separates what needs you from what's only for information:

```
Prepare my briefing for today. Use my calendar, my email since yesterday afternoon, and the channels I follow. Give me four short sections:
1. Today's meetings, with anything I need to prepare.
2. Messages that are waiting for a reply from me, most urgent first.
3. Deadlines today and tomorrow.
4. Anything I was mentioned in that I haven't opened.
Keep it under 200 words. Give a link to each item. If you're unsure whether something needs a reply, list it and say so.
```

Run it by hand for a week. When it's right, schedule it for a time shortly before you start work, as Chapter 4.3 showed. On a personal account, the briefing covers your own Outlook.com mail and calendar.

Two places in Copilot Home support a daily start:

- **Automations** shows your scheduled routines and their latest results. Open it first each morning, and read what's waiting for you.
- **Today** is a view that Microsoft is testing. It brings together email, meetings, and tasks you may have missed, without a prompt from you. It's in private preview.

If Today reaches your account, compare it with your own briefing for a week. Keep whichever one you trust more. A view you didn't design can still miss the things that are important to you.

A briefing is a summary, so the cautions from Chapter 3.2 apply. It can miss an important message, or rank a routine one too highly. For the first few weeks, scan your inbox as well, and note what the briefing missed. Adjust the prompt until the two agree.

## Write your system on one page

A system that lives only in your head won't survive a busy month. Put it on one page, in a Copilot Page or a document. Include:

- **Your routines**, grouped by daily, weekly, and monthly. For each: what it does, the tool, when it runs, and how you check it.
- **Your sources**, and which ones Copilot can reach.
- **Your limits**: the tasks you've decided to keep entirely with yourself, and why.
- **Your first process**, with the benefit you expect and the date you started.
- **A review date**, about a month away.

Keep the page next to the register of automations you made in Chapter 4.12. The register lists what's running. This page explains why, and how the pieces fit into your week.

> **Good practice**: Attach each routine to something you already do. "After I open my laptop, I read the briefing." "Before the Monday team meeting, I run the week-ahead prompt." A routine tied to an existing habit gets done. A routine you have to remember separately usually doesn't.

## Try it now

Build your inventory, choose your routines, and set up a daily starting point:

1. Open `5-1-work-inventory.xlsx`, or create a table with the six columns from this chapter.
2. Look through your calendar, sent email, and task list for the last four weeks. Add every task you did more than once. Aim for at least 15 rows.
3. With a work account, send the prompt from the "Inventory your repeated work and information sources" section, and add anything it finds that you missed.
4. List your information sources, and mark which ones Copilot can reach.
5. Score each task with the four questions from Chapter 4.1. Cross out the ones that should stay entirely with you.
6. From what's left, choose one or two routines for each rhythm: daily, weekly, and monthly.
7. Choose your first process, using the four tests in the "Begin with one low-risk process" section. Write the benefit you expect in one specific sentence.
8. Send the daily briefing prompt, and compare the result with your inbox and calendar. Adjust the prompt once.
9. Write your system on one page, with a review date about a month away.

You should now have an inventory of your repeated work, a short list of routines by rhythm, one first process with an expected benefit, a tested briefing prompt, and a one-page description of your system.

> **What to ask next**: Ask Copilot to look at your short list with a skeptical eye: `Here are the routines I plan to hand to Copilot: [paste your list]. For each one, what is most likely to go wrong in the first month, and how would I notice?`

### Check the result

- [ ] Is your inventory based on your calendar, email, and task list, and not only on memory?
- [ ] Have you marked the tasks that should stay entirely with you?
- [ ] Is your first process frequent, low-risk, and your own?
- [ ] Is each routine attached to a moment in your day or week?

> **Real-world example**: A practice manager at a veterinary clinic lists 22 repeated tasks. She crosses out six, including anything about staff pay and client complaints. She picks three routines: a morning briefing, a Friday summary of the week's supplier emails, and a monthly comparison of two stock reports. She starts with the Friday summary, because it's weekly, only she reads it, and she dislikes doing it. After three weeks, she schedules it. She leaves the stock comparison until she has learned how the first routine behaves.

Your system is specific to you, but much of it will resemble the systems of people who do similar work. The next eight chapters give worked examples by role. [*Chapter 5.2, Workflows for managers and project leaders*](05-02-Workflows-for-managers-and-project-leaders.md), begins with the work of preparing decisions, reporting progress, and keeping track of commitments.

[Go to next chapter >>](05-02-Workflows-for-managers-and-project-leaders.md)
