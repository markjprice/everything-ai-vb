# Chapter 5.10: Protect people, information, and professional trust

Throughout this book, you've met warnings one at a time: check the source, don't paste confidential files, keep decisions about people with people. Each belonged to a particular feature or role. This chapter gathers them into one method that you can apply to any piece of work, in any job. The reason to do so is practical. Your colleagues, your customers, and your employer trust you with information and rely on what you tell them. Copilot can help you do more with that trust, and it can help you lose it faster. In this chapter, you'll learn four gates that every piece of Copilot-assisted work should pass, how to be open about your use of AI, and what to do when something goes wrong. By the end, you'll have a one-page code of practice for your own work.

## Pass every piece of work through four gates

Before a piece of Copilot-assisted work leaves your hands, it should pass four checks. Figure 5.10.1 shows them as gates.

*Figure 5.10.1: Four gates between your work and the people who'll rely on it: privacy, rights, accuracy, and consequences.* [Diagram 5.10-A]

| Gate | The question | When it applies |
| --- | --- | --- |
| **Privacy** | Should this information be going into Copilot, and should the result be going where I'm sending it? | Before you prompt, and before you share |
| **Rights** | Am I allowed to use this material, and to use the result in this way? | Before you upload, and before you publish |
| **Accuracy** | Is it right, fair, and suitable for this reader? | Before anyone relies on it |
| **Consequences** | If this is wrong, who's affected, and has a person taken responsibility? | Before you send, decide, or act |

The first two gates come before and after the work. The last two come at the end. A routine summary for your own use passes all four in seconds. A report to a regulator needs time at each one.

## Gate 1: Minimize confidential and personal information

The safest information is information that you never put into a prompt. The principle is called **data minimization**: use the least information that the task needs.

**Before you prompt, ask whether the detail is needed.** Many tasks work as well without it.

| Instead of | Try |
| --- | --- |
| Pasting a complaint with the customer's name, address, and account number | "A customer complained that a delivery was three days late and nobody called them. Draft a reply." |
| Uploading a spreadsheet of staff with salaries | A copy with names replaced by codes, and only the columns you need |
| Describing a colleague's health condition to get advice on a rota | "One team member can't work mornings for the next month." |
| Uploading a whole contract to ask about one clause | The clause, with the parties' names removed |

**Use the right account.** Work information belongs in your work account, where your organization's protections apply. Chapter 1.2 explained the difference.

**Know what needs most care.** Some kinds of personal information are protected more strictly in law in many countries, and cause more harm if exposed. They include health, race or ethnic origin, religion, political views, sexual orientation, trade union membership, criminal records, and information about children. Keep these out of prompts unless your organization has approved a specific use, in a specific tool.

**Think about where the result goes.** Chapter 3.8 showed that a summary can carry information to people who couldn't open the source. Before you share a result, ask who could open the sources it came from, and whether your readers are among them.

**Never enter these**, whatever the account:

- Passwords, security codes, and private keys.
- Payment card numbers and bank details.
- Information you've been told, or have agreed in a contract, not to share.

> **Watch out**: Information can be confidential without being labeled. A colleague's remark in a private chat, a draft that hasn't been announced, or a customer's plans mentioned in a meeting may carry no marking at all. Ask yourself how the person it concerns would react if they saw it in your prompt. If they'd object, leave it out.

## Gate 2: Check your rights to use the material and the result

This gate has two sides: what goes in, and what comes out.

**What goes in.** You need the right to use material before you give it to Copilot.

- **Other people's published work.** A paid report, a book chapter, or a subscription article has a license. Uploading the whole thing may breach it. A short quotation, with its source, is usually acceptable.
- **Other people's confidential work.** A competitor's document that reached you by accident, or a previous employer's files, shouldn't be used at all.
- **Images and recordings of people.** You need consent to use someone's photograph, voice, or words, and the consent has to cover what you're doing with it.

**What comes out.** You're responsible for what you publish or deliver.

- **Similarity.** Generated text or images can resemble existing work. For anything public, check distinctive phrases, and don't ask Copilot to imitate a named living writer, an artist, or a brand.
- **Attribution.** If a result draws on a source, credit the source. Chapter 1.8 showed how to trace a claim to its origin.
- **Ownership.** The law on who owns AI-assisted work varies between countries, and it's still developing. If ownership is important, for a client deliverable or a product, take advice.
- **Your organization's rules.** Many organizations have a policy on generated images, on disclosure, or on using AI for published content. Follow it.

When you're unsure whether you have the right to use something, the answer is to ask the owner, or not to use it.

## Gate 3: Check factual accuracy, bias, and suitability

Accuracy has been a theme since Chapter 1.1. This gate adds two more questions.

**Is it accurate?** Apply what you've learned:

- Open the source for every fact you'll rely on (Chapter 1.8).
- Check figures by hand, and make totals agree (Chapter 2.4).
- Find each quotation in its original.
- Look for claims of cause that nobody has confirmed (Chapter 5.4).

**Is it fair?** A model learns from text written by people, and it can reproduce their assumptions. **Bias** in an answer may appear as:

- **Who's assumed.** A draft about "a manager and his assistant," or examples that are all from one country.
- **Who's missing.** A summary that reflects the people who wrote the most and leaves out those who weren't in the conversation.
- **What's treated as normal.** Advice that assumes a full-time office worker with a car and no caring responsibilities.
- **How people are described.** Different words for the same behavior, depending on who's doing it.

Ask Copilot to look, and then look yourself:

```
Review this draft for unstated assumptions about the reader or the people described, such as their gender, age, location, working pattern, or ability. List each one, and suggest more neutral wording. Then tell me whose point of view is missing.
```

**Is it suitable?** A result can be accurate and fair, and still wrong for the occasion.

- **For this reader.** Is the level right? Does it assume knowledge they don't have?
- **For this purpose.** Is a generated summary acceptable here, or does the situation call for your own words?
- **For this moment.** Would it read differently to someone who's worried, grieving, or angry?

For medical, legal, financial, safety, and employment questions, Copilot's output is a starting point for a conversation with a qualified person. Don't pass it on as advice.

## Gate 4: Retain human ownership of high-impact communication and decisions

The last gate asks who's responsible. For most work, the answer is plain: you wrote the prompt, you checked the result, and you're answerable for it. The gate is there for the cases where that could slip.

**High-impact communication** needs to start with a person and be sent by a person:

- Bad news, complaints, apologies, and condolences.
- Anything about an individual's job, health, conduct, or money.
- Public statements, especially in a crisis.
- Commitments on behalf of your organization.

**High-impact decisions** need a named person who has considered the case and can explain the decision:

- Decisions about people: hiring, pay, discipline, access to a service.
- Decisions with legal, financial, medical, or safety consequences.
- Decisions that can't be reversed.

For both, apply one test. If the person affected asked, "Who decided this, and why?", could you give a name and a reason? If the answer would be "Copilot suggested it," the gate hasn't been passed.

Ownership also means not hiding behind the tool. "The AI got it wrong" explains how a mistake happened. It doesn't change who's responsible for it.

> **Good practice**: For anything that passes Gate 4, write one line in the document or its covering message that says who reviewed it, such as "Reviewed and approved by [name], [date]." It tells the reader that a person stands behind the work, and it reminds you to do the review before you write the line.

## Be open about how you use AI

Trust depends on people knowing what they're dealing with. You don't need to label every email. You do need to be honest when it's relevant.

- **Tell people when it changes what they should assume.** If a draft recap was generated from a transcript, say so, because readers should check it more carefully (Chapter 3.4).
- **Answer truthfully when asked.** If a client or a colleague asks whether you used AI, tell them, and tell them how you checked the result.
- **Don't present generated content as something it isn't.** A generated image isn't a photograph of an event. A generated quotation isn't something a person said.
- **Follow the rules of your setting.** Some employers, clients, publishers, courts, and schools require disclosure. Some forbid AI for certain work.
- **Tell people when they're dealing with an agent.** Chapter 4.10 made this point about Autopilot. It applies to any agent that answers on your behalf.

Being open also helps you. A colleague who knows that your summary came from Copilot will tell you when it's wrong. One who thinks you wrote it may assume that you know something they don't.

## Know what to do when something goes wrong

Sooner or later, something will go wrong. A wrong figure will go out, or a file will be shared with someone who shouldn't see it. What you do in the next hour decides how much damage follows.

Follow these steps when you find a mistake that has reached other people:

1. **Stop.** Pause any automation involved. Don't send anything further.
2. **Contain.** Recall the message if you can, remove the sharing link, or correct the shared document.
3. **Tell.** Tell the people who received the wrong information, plainly and quickly. If personal or confidential information has gone to the wrong place, tell your manager and your organization's data protection or security contact at once. Many countries set short legal deadlines for reporting a data breach.
4. **Fix.** Send the correct version, and say what changed.
5. **Learn.** Work out which gate the mistake passed through, and change your routine so that it's caught next time. Add a line to your prompt, a check to your review, or an approval to your automation.

You should now have limited the damage and closed the gap that allowed it.

Don't delete the evidence, and don't wait to see whether anyone notices. A mistake that's corrected quickly is easier to forgive than one that was hidden.

## Write your own code of practice

The four gates are general. A code of practice makes them specific to your work. Keep it to one page, and keep it where you'll see it.

A code of practice answers six questions:

- **What do I never put into Copilot?**
- **Which account do I use for what?**
- **What do I always check before I share a result?**
- **Which communication and decisions do I keep entirely with myself?**
- **When do I tell people that I used AI?**
- **Who do I tell when something goes wrong?**

If your organization has an AI policy, your code should fit inside it. If you lead a team, write the code together, as Chapter 5.7 suggested for recruitment.

## Try it now

Pass one piece of work through the four gates, and write your code of practice:

1. Choose a piece of work that you've produced with Copilot's help and haven't yet shared.
2. **Privacy.** List the personal or confidential information that went into the prompts. For each item, decide whether the task needed it. Check who could open the sources, and who'll receive the result.
3. **Rights.** List any material that you uploaded which wasn't yours. Check that you were allowed to use it. Look for any text or image in the result that might resemble someone else's work.
4. **Accuracy.** Check three facts against their sources. Send the bias review prompt from this chapter, and consider each point it raises.
5. **Consequences.** Write down who would be affected if the work were wrong, and who has reviewed it. Add a review line if the work needs one.
6. Note which gate took the longest, and which found a problem.
7. Write your code of practice on one page, answering the six questions.
8. Find out who your organization's data protection or security contact is, and add their details to the code.

You should now have one piece of work that has passed all four gates, a note of what the gates found, and a one-page code of practice with a named contact.

> **What to ask next**: Ask Copilot to test your code against hard cases: `Here is my code of practice for using AI at work: [paste it]. Describe five realistic situations where I might be tempted to break it, or where it doesn't say what to do. For each one, suggest a clearer rule.`

### Check the result

- [ ] Could you have done the task with less personal or confidential information than you used?
- [ ] Did you have the right to use every piece of material that you uploaded?
- [ ] Did the bias review, or your own, find an assumption that you hadn't noticed?
- [ ] If someone asked who decided or approved this work, could you give a name?
- [ ] Do you know who to tell if confidential information goes to the wrong place?

> **Real-world example**: A team leader at a housing association asks Copilot to draft a letter to a tenant about rent arrears, and pastes in the tenant's payment history and a case note that mentions a recent bereavement. The draft is accurate. At the privacy gate, she sees that the task needed only the amount owed and the dates. At the consequences gate, she sees that this is a letter about someone's home, to a person who is grieving. She writes the letter herself, uses Copilot only to check that the figures in it match the account, and phones the tenant before sending it.

You now have a method for doing this work responsibly. One question remains, and it's the one your manager or your own bank balance will ask: is it worth it? [*Chapter 5.11, Measure Copilot's real value*](05-11-Measure-Copilots-real-value.md), shows you how to find out with evidence.

[Go to next chapter >>](05-11-Measure-Copilots-real-value.md)
