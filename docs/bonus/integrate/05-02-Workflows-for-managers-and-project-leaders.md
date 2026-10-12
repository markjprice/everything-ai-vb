# Chapter 5.2: Workflows for managers and project leaders

A manager's work is mostly other people's information. You read updates, sit in meetings, and piece together what's happening so that you can decide something, report something, or remove an obstacle. Copilot is well suited to the piecing together. It can gather evidence from many places, set out options, and draft a status report in minutes. The deciding stays with you, and so does everything that concerns the people you manage. In this chapter, you'll see three workflows for preparing decisions and meetings, producing plans and status reports, and tracking risks, dependencies, and commitments. By the end, you'll have set up one of them with your own team's information.

> **Plan note**: These workflows rely on Copilot reaching your team's messages, meetings, and files, so they work best with a work account and a Microsoft 365 Copilot license. With a personal account, you can use the same prompts with files and notes that you upload.

## Where Copilot fits in a manager's work

| Copilot helps with | Keep with yourself |
| --- | --- |
| Gathering what's been said and written about a topic | The decision |
| Setting out options, with the evidence for each | Judging people's performance |
| Drafting plans, reports, and updates | Feedback, praise, and difficult conversations |
| Finding overdue actions and unanswered questions | Pay, promotion, and discipline |
| Preparing you for a meeting | Deciding what your team should stop doing |

Copilot could produce words on every subject in the right-hand column. Keep them with yourself anyway, because your team needs to know that a person considered them.

Figure 5.2.1 shows the pattern behind every workflow in this chapter.

*Figure 5.2.1: A management workflow runs from evidence to a decision that a person has reviewed and owns.* [Diagram 5.2-A]

## Workflow 1: Prepare a decision

Managers are often asked to decide with partial information and little time. A decision brief puts what's known in one place, and says what isn't known.

| | |
| --- | --- |
| **When** | A decision is due, such as whether to delay a project or which supplier to choose |
| **Inputs** | Email, chats, meeting recaps, and files about the topic. Any figures from a workbook you trust |
| **Tool** | Copilot Chat. Researcher, if outside evidence is needed (Chapter 1.9) |
| **Check** | Open the source for each fact you'll rely on. Confirm each person's position with them |
| **Stays with you** | The decision, and explaining it to the people it affects |

Ask for a brief that sets out options without choosing one:

```
I need to decide [the decision] by [date]. Using what's been written about this in email, chats, meetings, and files I can access, prepare a one-page brief with:
1. The decision, in one sentence.
2. Two or three options, with the main benefit, cost, and risk of each, and the evidence for each point.
3. What each person involved has said, with a source.
4. What we don't know, and who could tell us.
Don't recommend an option. Mark anything you're unsure about with [CHECK].
```

Asking Copilot not to recommend keeps the brief from leaning toward one answer before you've thought. If you'd like a second opinion afterward, ask for one separately: `Which option is best supported by the evidence, and what would have to be true for each of the others to be the better choice?`

The same approach prepares you for a meeting. Chapter 3.3 covers briefs and agendas in detail.

> **Watch out**: A brief built from messages reflects who wrote the most. The colleague who sends long emails will seem to have the strongest case, and the one who raised a concern once, in a corridor, won't appear at all. Before you decide, ask yourself whose view is missing from the brief, and go and ask them.

## Workflow 2: Produce a plan or a status report

Plans and status reports follow a fixed shape, which makes them good candidates for a saved prompt or a scheduled draft.

| | |
| --- | --- |
| **When** | Weekly or monthly, on a fixed day |
| **Inputs** | The action list or task board, the project channel, and the previous report |
| **Tool** | A saved prompt (Chapter 4.2), then a scheduled draft (Chapter 4.3). The Planner agent, if your team uses Planner |
| **Check** | Each status against its source. Speak to the owner of anything marked at risk or late |
| **Stays with you** | The summary line, and the conversation with each owner |

Chapter 3.9 gave a full prompt for a status report, including the instruction to write **[NO EVIDENCE]** where Copilot can't find support for a status. Reuse it here.

Two additions help a manager in particular:

- **Compare with last time.** Add: "Compare with the attached previous report. List what changed, and anything that was promised last time and isn't mentioned this time." Dropped items are where problems hide.
- **Write for the reader.** Ask for a second version for your own manager: three lines on progress, risks, and what you need from them.

For a new plan, start from the goal, as in Chapter 3.9, and ask for deliverables, milestones, dependencies, and proposed owners. Then take the draft to the team. A plan that people helped to shape is one they'll follow.

## Workflow 3: Track risks, dependencies, and commitments

A manager carries a long list of open items in their head: what was promised, who's waiting on whom, and what might go wrong. Copilot can keep the list for you, built from what people have written and said.

| | |
| --- | --- |
| **When** | Weekly, before your team meeting or one-to-ones |
| **Inputs** | Meeting recaps, the project channel, email, and the action list |
| **Tool** | Copilot Chat, or a project Notebook that holds the recaps and plans (Chapter 3.7) |
| **Check** | Each commitment against the message or recap where it was made |
| **Stays with you** | Raising each item with the person concerned |

Ask for commitments and risks, with the evidence for each:

```
From meeting recaps, the project channel, and email about [project] in the last two weeks, make three lists:
1. Commitments: who promised what to whom, and by when. Mark any that are past their date with no update.
2. Dependencies: work that's waiting on something from another person or team.
3. Risks: concerns that anyone has raised, whether or not anyone responded.
Quote the source for each item. Include commitments that I made.
```

The last line is easy to leave out. Your own promises to your team count as much as theirs to you, and they're the ones you're most likely to forget.

Use the lists to prepare your conversations. They tell you what to ask about. They don't tell you why something is late.

## Handle information about people with care

Managing people brings you information that needs more protection than a project plan.

- **Don't ask Copilot to assess a person.** A prompt such as "Summarize how Sam has performed this quarter" produces a confident paragraph from fragments of messages. It isn't a fair or complete record, and in a work account, the prompt and the answer are stored.
- **Write feedback yourself.** You can ask Copilot to check a draft for clarity or tone. The observations and the judgment have to be yours.
- **Keep sensitive notes out of shared spaces.** One-to-one notes, absence details, and personal circumstances don't belong in a team Notebook or a shared Page.
- **Remember what Copilot can now find.** Chapter 3.1 explained oversharing. As a manager, you probably hold files that your team shouldn't see. Check where they're stored and who can open them.

Chapter 5.7 covers employment decisions in more detail, and Chapter 5.10 sets out the general rules.

> **Good practice**: Tell your team how you use Copilot. Say that you use it to gather updates and draft reports, that you check what it produces, and that you don't use it to judge anyone's work. People are more open in channels and meetings when they know how their words will be used.

## Try it now

Set up one management workflow with your own team's information:

1. Choose the workflow that would help you most this week: a decision brief, a status report, or a commitments list.
2. Copy the prompt for that workflow from this chapter or from Chapter 3.9, and fill in your own project and dates.
3. Run it in Copilot Chat.
4. Check three items against their sources. For a commitment or a position, find where the person said it.
5. Write down one view or fact that you know is missing, because it was never written down.
6. Use the result to prepare one conversation or one decision. Don't forward it as it stands.
7. If the prompt worked, save it, and add the routine to your one-page system from *Chapter 5.1*.

You should now have one checked brief, report, or list, a note of what it missed, and a saved prompt.

> **What to ask next**: Ask Copilot to test the brief for balance: `Does this brief give more space to some people's views than others? Whose position is supported by the least evidence, and who hasn't been heard from at all?`

### Check the result

- [ ] Did you open the source for each fact, position, or commitment you plan to rely on?
- [ ] Does the result include your own commitments, as well as other people's?
- [ ] Did you identify at least one view that wasn't written down?
- [ ] Is the decision, or the conversation, still yours to make?

> **Real-world example**: A project leader at a construction firm asks Copilot for the commitments made in the last two weeks of site meetings. The list shows that she herself promised a subcontractor a revised schedule ten days ago, and never sent it. It also marks a delivery as "confirmed," based on a message that said, "Should be fine for Thursday." She sends the schedule that afternoon, and phones the supplier to ask whether Thursday is certain.

A manager's information often arrives through the person who organizes their diary, their meetings, and their correspondence. [*Chapter 5.3, Workflows for administrators and executive assistants*](05-03-Workflows-for-administrators-and-executive-assistants.md), looks at Copilot from that side of the desk.

[Go to next chapter >>](05-03-Workflows-for-administrators-and-executive-assistants.md)
