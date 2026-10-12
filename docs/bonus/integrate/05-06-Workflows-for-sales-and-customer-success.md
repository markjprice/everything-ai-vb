# Chapter 5.6: Workflows for sales and customer success

Sales and customer success depend on knowing a customer well: what they bought, what they asked for, what went wrong last time, and what you promised. That knowledge is spread across emails, meeting notes, a customer system, and your own memory. Copilot can pull it together before a call and help you write the follow-up afterward. The risks are particular to the role. A customer's information isn't yours to share freely, a promise in a follow-up binds your organization, and a message that reads as mass-produced damages the relationship it was meant to build. In this chapter, you'll see three workflows for preparing for a customer conversation, summarizing an account's history and agreed actions, and drafting follow-ups that are individual. By the end, you'll have a preparation brief for one customer, and a follow-up that only that customer could have received.

> **Plan note**: These workflows work best with a work account and a Microsoft 365 Copilot license, so that Copilot can reach your email, meetings, and files. Reaching your customer system needs a connector that your organization has approved (Chapter 4.8). With a personal account, you can use the same prompts with notes and documents that you upload, as long as you're permitted to.

## Where Copilot fits in customer-facing work

| Copilot helps with | Keep with yourself |
| --- | --- |
| Gathering an account's history from several places | Reading the customer's mood |
| Preparing questions and likely objections | The conversation itself |
| Listing what was agreed in a meeting | Prices, discounts, dates, and contract terms |
| Drafting a follow-up from your notes | Deciding what to promise |
| Researching a company from public sources | Whether, and how often, to contact someone |

## Workflow 1: Prepare for a customer conversation

Ten minutes of preparation can change a customer meeting. You walk in knowing what was said last time and what the customer cares about.

| | |
| --- | --- |
| **When** | Before a call, a meeting, or a renewal conversation |
| **Inputs** | Your emails and meetings with the customer, shared documents, the account record if a connector is available, and public news about the company |
| **Tool** | Copilot Chat. Web search for public information (Chapter 1.8) |
| **Check** | Each fact about the account against its source. Anything about the customer's business against a current public source |
| **Stays with you** | What to raise, what to leave alone, and how to open the conversation |

Ask for a preparation brief that separates what's recorded from what's inferred:

```
I'm meeting [customer contact] at [company] on [date] about [purpose]. Using my emails, meetings, and shared files with them from the last six months, prepare a one-page brief:
1. Who I'm meeting, their role, and when we last spoke.
2. What they've bought or use, and since when.
3. Open issues, complaints, or requests, with the date and current status of each.
4. What we promised them, and whether each promise was kept.
5. Three questions I should ask.
Give a source for each point. Keep facts from the record separate from your own suggestions, and label the suggestions.
```

Then add public context: `Search the web for news about [company] from the last three months that might affect this conversation. Give a link for each item.`

Item 4 is the one that prevents embarrassment. Walking into a renewal meeting without knowing that a promised fix was never delivered is avoidable.

Check the brief against the customer system and your own memory. Copilot sees what was written to or from your account. A colleague's call with the customer, or a support ticket you weren't copied on, may be missing.

## Workflow 2: Summarize account history and agreed actions

After a conversation, the value is in what was agreed. A clear record protects both sides.

| | |
| --- | --- |
| **When** | After each customer meeting, and when an account changes hands |
| **Inputs** | Your notes, the meeting recap if the meeting was transcribed, and earlier correspondence |
| **Tool** | Meeting recap and Copilot Chat (Chapter 3.4) |
| **Check** | Each agreed action and date against your notes or the transcript. Every commitment made on your organization's behalf |
| **Stays with you** | Confirming the record with the customer, and updating the customer system |

The recap techniques from Chapter 3.4 apply, with one addition. With a customer, separate three things that are easy to blur:

- **What we agreed to do**, with an owner and a date.
- **What the customer agreed to do.**
- **What was discussed but not agreed**, such as a discount the customer asked about and you said you'd look into.

The third list protects you. A recap that turns "I'll see what's possible" into "agreed a 10% discount" creates an obligation you didn't accept.

For an account handover, ask for a history: `Summarize this account's history over the last two years as a timeline: purchases, renewals, issues, and commitments, with the date and source of each. Then list what's currently open.` Have the outgoing account manager read it and correct it. They know what the record leaves out.

> **Watch out**: Recording or transcribing a customer meeting needs the customer's agreement, and the rules differ between countries and industries. Ask before you start, explain what the recording is for, and be ready to take notes by hand instead. Chapter 3.3 covers consent in more detail. Check your organization's policy for external meetings.

## Workflow 3: Draft individualized follow-up without automated spam

A good follow-up shows the customer that you listened. It mentions what they said, answers what they asked, and confirms what happens next.

| | |
| --- | --- |
| **When** | Within a day of a conversation |
| **Inputs** | The agreed actions from Workflow 2, and your own notes on what the customer cared about |
| **Tool** | Copilot in Outlook (Chapter 3.5) |
| **Check** | Names, attachments, facts, and promises. Every price, date, and term against what you're authorized to offer |
| **Stays with you** | Every commitment, and selecting **Send** |

Give Copilot the specifics, so that the message can only be for this customer:

```
Draft a follow-up email to [contact] after today's meeting. Thank them briefly. Confirm these agreed actions: [list, with owners and dates]. Answer the question they asked about [topic] with this information: [your answer]. Mention [one specific thing they said they cared about]. Friendly and direct, under 150 words. Don't offer anything that isn't in this list. Don't add a discount, a deadline, or a meeting that I haven't mentioned.
```

Then make it yours. Change the opening line to something only you would write. Read the last two sentences for promises that Copilot added, as Chapter 3.5 warned.

The words "without automated spam" need a note. Copilot makes it possible to produce hundreds of slightly varied messages in minutes. Three reasons not to:

- **It's often against the rules.** Many countries regulate unsolicited marketing email, and require consent or an easy way to opt out. Your organization will have a policy.
- **It weakens the relationship.** A message that inserts a company name into a standard paragraph reads as a template, and it lowers the value of your next message.
- **Errors multiply.** One wrong detail in a template becomes a wrong detail in every message, as Chapter 4.1 explained.

Use Copilot to write better messages to the people you'd have written to anyway. Don't use it to write to more people than you have a reason to contact. If your organization runs bulk campaigns, those belong in a marketing system with consent records, and under the checks in Chapter 5.5.

## Protect customer information

Customer data needs particular care in this role.

- **Use your work account.** Never put customer details into a personal Copilot account. It lacks your organization's protections, and it may breach your customer contracts.
- **Check your contracts.** Some customers restrict how their information may be processed, including by AI tools. Ask your manager or legal contact if you're unsure.
- **Share briefs carefully.** A preparation brief contains the customer's history and possibly their complaints. Don't post it in a wide channel.
- **Keep the customer system as the record.** Copilot's summary is a working aid. Update the system of record with the confirmed facts.
- **Limit connectors to reading**, unless you have a reason to do more. Chapter 4.8 explained why.

> **Good practice**: After each customer conversation, send the agreed actions to the customer in writing, and ask them to correct anything that's wrong. It takes two minutes, it catches Copilot's mistakes and your own, and it gives both sides the same record.

## Try it now

Prepare for one customer conversation, and write a follow-up that's individual:

1. Choose a customer you'll speak to soon. If you're not in a customer-facing role, choose a supplier or a partner organization.
2. Adapt the preparation prompt from this chapter, and run it in Copilot Chat with your work account.
3. Check three facts in the brief against their sources. Check each promise listed in item 4.
4. Write down one thing that you know about the account that isn't in the brief.
5. After the conversation, list what you agreed to do, what they agreed to do, and what was discussed but not agreed.
6. Adapt the follow-up prompt, and include one specific thing that the customer said.
7. Rewrite the opening line yourself. Remove any offer, date, or meeting that you didn't intend.
8. Check names, attachments, facts, and promises. Send the message if it's appropriate to.

You should now have a one-page preparation brief with checked facts, a three-part record of the conversation, and a follow-up that mentions something only this customer said.

> **What to ask next**: Ask Copilot to look at the relationship from the customer's side: `Based on this account's history, what would this customer say we do well, and what would they say we've been slow or unclear about? Give the evidence for each.`

### Check the result

- [ ] Does the brief show which promises to this customer were kept and which weren't?
- [ ] Did you keep "discussed" separate from "agreed" in your record?
- [ ] Could your follow-up have been sent to any other customer without changes? If so, make it more specific.
- [ ] Is every price, date, and term in the follow-up one that you're authorized to offer?

> **Real-world example**: An account manager at a software company prepares for a renewal call with a brief from Copilot. It shows that the customer raised the same reporting problem in three emails over five months, and that each reply promised an update "next quarter." She hadn't seen the pattern, because two of the replies came from a colleague. She opens the call by acknowledging the delay and giving a date she has confirmed with the product team. The customer renews.

Customer conversations are about commitments between organizations. The next role deals with commitments between an organization and its own people, where the stakes for individuals are highest. [*Chapter 5.7, Workflows for HR and recruitment*](05-07-Workflows-for-HR-and-recruitment.md), covers preparing role and interview materials, summarizing policies, and keeping employment decisions with people.

[Go to next chapter >>](05-07-Workflows-for-HR-and-recruitment.md)
