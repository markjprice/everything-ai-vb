# Chapter 5.3: Workflows for administrators and executive assistants

Administrators and executive assistants keep other people's work moving. You prepare the day, guard the calendar, chase the follow-ups, and know where everything is filed. Much of that is gathering and arranging, which Copilot does quickly. The role also has a feature that most others lack: you often act for someone else, with access to their mailbox, their calendar, and their confidences. That changes what Copilot can see and what you should let it do. In this chapter, you'll see three workflows for daily briefings, for calendars, agendas, and follow-ups, and for files and routine communication. By the end, you'll have a daily briefing that works within the limits of your access.

> **Plan note**: These workflows work best with a work account and a Microsoft 365 Copilot license. Copilot in Outlook works in your own main mailbox. It doesn't work in shared or delegate mailboxes, which affects assistants who manage someone else's inbox. This chapter explains how to work within that limit.

## Where Copilot fits in an administrator's work

| Copilot helps with | Keep with yourself |
| --- | --- |
| Assembling a briefing from the calendar, email, and files | Deciding what your manager sees first |
| Drafting agendas, invitations, and routine replies | Anything sent in your manager's name |
| Finding documents and summarizing them | Judging what's confidential |
| Turning meeting notes into follow-up lists | Chasing people, and knowing how hard to push |
| Checking a calendar for clashes and gaps | Trading one commitment against another |

## Understand what Copilot can see when you work for someone else

Chapter 3.1 explained that Copilot searches as you, with your permissions. For an assistant, that has three consequences. Figure 5.3.1 shows them.

*Figure 5.3.1: When you work for someone else, Copilot uses your access, which is only part of theirs.* [Diagram 5.3-A]

**Copilot sees what your account can open.** If your manager has shared their calendar with you, Copilot can usually use what you can see there. It can't see their private appointments, their mailbox, or files that haven't been shared with you, unless you've been given access.

**Delegate and shared mailboxes are a gap.** Copilot in Outlook doesn't summarize or draft in a mailbox you manage as a delegate. For your manager's email, you'll work from messages that are forwarded to you, or copy the text of a thread into Copilot Chat when that's permitted.

**Your prompts are yours.** When you ask Copilot about your manager's affairs, the conversation is stored under your account. Treat those chats as confidential, and think about where you save their results.

Before you set up any workflow in this chapter, agree three things with the person you support:

- Which of their information you may use with Copilot.
- What must never be put into a prompt, such as personal matters or anything about board, legal, or staffing issues.
- What you may send for them, and what needs their eyes first.

## Workflow 1: Prepare a daily briefing

A briefing gives your manager the day on one page. Copilot assembles the draft, and you apply the judgment about what comes first.

| | |
| --- | --- |
| **When** | Each working day, before your manager starts |
| **Inputs** | Their calendar as shared with you, the documents for each meeting, and messages forwarded or flagged for the day |
| **Tool** | A saved prompt, then a scheduled draft (Chapters 4.2 and 4.3) |
| **Check** | Every time, room, link, and name against the calendar. Each document link opens |
| **Stays with you** | The order, what to leave out, and anything sensitive you add by hand |

Ask for a briefing in a fixed layout:

```
Prepare a briefing for [manager's name] for [date], using their calendar as shared with me and the files linked in each invitation.
For each meeting, give: the time and place or link, who's attending, the purpose in one line, what they need to read or decide, and a link to each document.
Then list: gaps of 30 minutes or more, any back-to-back meetings in different places, and anything in the calendar with no agenda.
Keep it to one page. Use only what's in the calendar and the linked files. Mark anything missing with [CHECK].
```

Then edit it. You know things the calendar doesn't: that the 2 PM meeting is the one that counts today, that one attendee is new, or that your manager dislikes being briefed on something they wrote themselves. A briefing that's been through your hands is worth more than one that hasn't.

> **Watch out**: A briefing often travels. It may be printed, forwarded, or opened on a phone in a public place. Keep sensitive details out of it, such as personal appointments, the reason for a confidential meeting, or remarks about attendees. If your manager needs those, tell them in person.

## Workflow 2: Coordinate calendars, agendas, and follow-ups

Scheduling for someone else is a negotiation between several people's time. Copilot can do the searching and the drafting, and you make the trade-offs.

| | |
| --- | --- |
| **When** | A meeting needs arranging, or has taken place |
| **Inputs** | The attendees' calendars, the purpose of the meeting, and the recap or notes afterward |
| **Tool** | Copilot in Outlook for finding times and drafting invitations (Chapter 3.6). Meeting recap for follow-ups (Chapter 3.4) |
| **Check** | Time zones, travel time, each attendee's working days, and every name |
| **Stays with you** | Which meeting gives way when two clash, and sending anything in your manager's name |

Three practices help in this role:

- **Give Copilot your manager's rules.** Add them to the prompt, or keep them in a saved prompt: "No meetings before 9 AM or after 5 PM. Keep Friday afternoons free. Leave 15 minutes between meetings, and 30 minutes when the location changes."
- **Ask for options.** "Find three possible times" gives you something to choose from. One suggestion gives you nothing to compare.
- **Track follow-ups in one list.** After a meeting, ask for the actions with owners and dates, mark the unclear ones, and add them to one tracker. Then ask weekly: `Which actions from the last month's meetings are overdue or have no update?`

When you send a meeting invitation for your manager, check whether it will go out under your name or theirs, and whether the wording suits the sender. Read it once more as the most senior person on the attendee list would.

## Workflow 3: Organize files and routine communication

Assistants are often the person who knows where things are. Copilot can find and summarize documents, and it can draft the routine messages that fill a day.

| | |
| --- | --- |
| **When** | A document is needed, or a routine message has to go out |
| **Inputs** | Shared folders and sites you can open. For messages, the facts and the recipient |
| **Tool** | Copilot Chat and Copilot in OneDrive for finding and comparing files (Chapter 3.8). Copilot in Outlook for drafts (Chapter 3.5) |
| **Check** | That a file is the current version. Names, dates, and attachments in every message |
| **Stays with you** | What's confidential, who may receive a file, and the tone for each recipient |

For files:

- `Find the latest version of the board paper on [topic]. Tell me where it's stored, who last changed it, and when.`
- `Compare these two versions of the agenda, and list what changed.`
- `List the documents in this folder that haven't been changed in over a year.`

For messages, keep a few saved prompts for the ones you send most: confirming a meeting, declining an invitation, asking for papers, thanking a visitor. Mark the parameters, as in Chapter 4.2, and add your manager's preferences for tone.

A request to tidy a shared folder needs care. Ask Copilot to list what it would move or rename, and review the list. Don't let an automation move or delete files in a space that other people rely on.

> **Good practice**: Keep a short, private page of your manager's standing preferences: meeting rules, the people who always get a quick reply, how they like papers prepared, and phrases they'd never use. Paste the relevant part into a prompt when you need it. It saves you from correcting the same things in every draft.

## Try it now

Set up a daily briefing that respects the limits of your access:

1. Write down what you may use with Copilot on your manager's behalf, and what's off limits. If you haven't agreed this with them, ask.
2. Check what you can see of their calendar. Note any private appointments that appear only as "busy."
3. Adapt the briefing prompt from this chapter with their name and tomorrow's date, and run it in Copilot Chat.
4. Check every time, place, link, and attendee against the calendar. Open each document link.
5. Reorder the briefing so that the most important item comes first. Remove anything sensitive. Add one thing that you know and the calendar doesn't.
6. Note what Copilot couldn't see, such as items in their mailbox, and decide how you'll cover those.
7. Save the prompt. When it has worked for a week, consider scheduling it as a draft for you to edit.

If you don't support another person, do the same for your own day, and use the result as your starting point from *Chapter 5.1*.

You should now have a one-page briefing that's been checked and edited by you, a list of what Copilot couldn't reach, and an agreed set of limits.

> **What to ask next**: Ask Copilot to look for problems in the day itself: `Looking at tomorrow's calendar, where is the day most likely to go wrong? Consider travel between locations, meetings with no break, and meetings with no agenda or papers.`

### Check the result

- [ ] Have you agreed with the person you support what may and may not go into a prompt?
- [ ] Did every time, place, and link in the briefing match the calendar?
- [ ] Did you remove anything that shouldn't be seen if the briefing were forwarded?
- [ ] Do you know which of their information Copilot can't reach with your account?

> **Real-world example**: An executive assistant to a hospital director drafts each day's briefing with a saved prompt. One morning, the draft lists a 4 PM meeting with its full title: a review of a named consultant's conduct. The title had been typed into the calendar entry by someone else. She removes the line from the briefing, tells the director in person, and asks the meeting's organizer to rename the entry. She adds a line to her prompt: "Don't include meetings marked private, or any meeting whose title names an individual."

Briefings and diaries depend on words. Many roles depend on numbers. [*Chapter 5.4, Workflows for analysts, finance, and operations*](05-04-Workflows-for-analysts-finance-and-operations.md), looks at preparing data, producing recurring analysis, and finding anomalies without handing over the final judgment.

[Go to next chapter >>](05-04-Workflows-for-analysts-finance-and-operations.md)
