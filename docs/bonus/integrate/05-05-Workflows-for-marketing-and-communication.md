# Chapter 5.5: Workflows for marketing and communication

Marketing and communication work produces a great deal of text: posts, emails, web pages, press releases, newsletters, and the many versions of each. Copilot writes quickly and adapts tone well, so the temptation is to let it write everything. The trouble is that what you publish is public, permanent, and attributed to your organization. A made-up statistic in a chat is a private mistake. The same statistic in a press release is a public one. In this chapter, you'll see three workflows for researching audiences and competitors, repurposing approved material for different channels, and reviewing what you produce before it goes out. By the end, you'll have turned one approved source into several channel versions, each checked against the original.

> **Plan note**: These workflows use Chat, file uploads, and web search, which work with every plan covered in this book. Researcher needs Microsoft 365 Premium or Pro, or a Microsoft 365 Copilot license. Image generation limits vary by plan.

## Where Copilot fits in marketing and communication

| Copilot helps with | Keep with yourself |
| --- | --- |
| Gathering public information about audiences and competitors | Deciding what the evidence means for your strategy |
| Adapting approved content for different channels and lengths | The claims your organization makes |
| Producing several versions of a headline or subject line | Choosing which one sounds like you |
| Checking a draft against a style guide or a source | Approval to publish |
| First drafts of routine content | Statements in a crisis, apologies, and anything sensitive |

The safest pattern in this chapter starts from material that's already been approved. Copilot changes its form. It doesn't add new facts.

## Workflow 1: Research audiences and competitors

Good communication starts with knowing who you're talking to and what else they're hearing.

| | |
| --- | --- |
| **When** | Before a campaign, a launch, or a change of message |
| **Inputs** | Public sources on the web. Your own research, survey results, and customer feedback, with personal details removed |
| **Tool** | Copilot Chat with web search (Chapter 1.8). Researcher for a fuller study (Chapter 1.9). Analyst for survey data (Chapter 2.5) |
| **Check** | Every source opened. Dates checked. Each claim about a competitor traced to the competitor's own published material |
| **Stays with you** | What you conclude, and how you describe competitors in public |

Ask for a competitor summary built only on what each competitor has published:

```
Research how [three named competitors] describe their [product or service] to [audience]. Use only their own websites, published materials, and official announcements from the last 12 months. For each one, give their main message, the three benefits they stress, their stated prices if published, and the exact wording of their headline claim. Give a link for every point. If you can't find something, say so. Don't use review sites or opinion pieces.
```

For audience research, start with your own data. Ask Copilot to find themes in survey comments or feedback, and to quote examples. Then ask what the data doesn't cover, such as people who didn't respond.

Be wary of one thing in particular. If you ask Copilot to "describe our typical customer," it will write a convincing portrait from general knowledge. It looks like research, and it's a stereotype. Insist on evidence from your own data or from named sources.

> **Watch out**: Statements about competitors carry legal risk. Copilot may summarize a competitor's product inaccurately, or repeat an old price. Before you use any comparison in public, check it against the competitor's current published material, and ask your legal or compliance contact to review it.

## Workflow 2: Repurpose approved source material

Your organization probably has more good content than it uses. A report, a case study, or a recorded talk can become a dozen smaller pieces. This is where Copilot saves the most time for the least risk, because the facts are already approved.

Figure 5.5.1 shows the pattern.

*Figure 5.5.1: One approved source becomes several channel versions. Each version is checked against the source before it's published.* [Diagram 5.5-A]

| | |
| --- | --- |
| **When** | A piece of content has been approved and is ready to share more widely |
| **Inputs** | The approved source, your style guide, and a few examples of your past content for each channel |
| **Tool** | Copilot Chat, or a Notebook that holds the source and the style guide (Chapter 1.11) |
| **Check** | Each version against the source, line by line. Each version against the style guide |
| **Stays with you** | Which version to use, and the approval to publish |

Ask for channel versions that add nothing to the source:

```
Using only the attached approved case study, write:
1. A 150-word summary for our newsletter.
2. Three short social posts, each making a different point from the case study.
3. A 60-word version for our website's home page.
Follow the attached style guide. Use only facts, figures, and quotations that appear in the case study, with the same wording for any quotation. Don't add benefits, statistics, or claims that aren't in it. After each version, list the sentences in the case study that it's based on.
```

The last instruction makes checking quick. For each version, you can go straight to the source sentences and compare.

Shortening changes meaning. A case study that says "response times fell by 20% in the first quarter for this customer" can become "cuts response times by 20%" in a social post. The first is a fact about one customer. The second is a promise to every reader. Look for this in every short version.

For voice, examples work better than adjectives, as Chapter 1.5 explained. Give Copilot three pieces you've published and liked, and ask it to match their sentence length and tone.

## Workflow 3: Review evidence, claims, consent, and brand voice

Every piece needs a review before it's published, whether a person or Copilot wrote it. Copilot can do a first pass, which makes the human review quicker and more focused.

| | |
| --- | --- |
| **When** | Before anything is published or sent |
| **Inputs** | The draft, the sources behind it, the style guide, and your record of permissions |
| **Tool** | Copilot Chat |
| **Check** | The four checks below, with a person making the final call on each |
| **Stays with you** | Approval, and the decision to publish |

Ask Copilot for a first-pass review that lists problems without rewriting:

```
Review the attached draft against the attached sources and style guide. Don't rewrite it. List:
1. Every factual claim, statistic, and comparison, and whether a source supports it. Quote the source sentence, or write [NO SOURCE].
2. Every quotation, testimonial, named person, named customer, and image of a person.
3. Words that promise a result, such as "guarantees," "proven," "best," or "always."
4. Places where the tone or wording doesn't follow the style guide.
```

Then make the four checks yourself:

- **Evidence.** For each claim, is there a source, and does it say this? Remove anything marked **[NO SOURCE]**, or find the source.
- **Claims.** Would a regulator or a customer read this as a promise? Many countries have rules about advertising claims, and stricter ones for health, finance, and products for children. Ask your legal or compliance contact when a claim is new.
- **Consent.** Do you have permission, in writing, for each quotation, testimonial, customer name, and photograph? Is the permission still current, and does it cover this channel?
- **Brand voice.** Does it sound like your organization? Read it aloud.

Images need the same care. Chapter 2.8 covered the checks for rights, accuracy, branding, and accessibility. Add one for this role: never use a generated image of a person as though it showed a customer or a member of staff.

> **Good practice**: Keep a record of each published claim, with its source and the date it was checked. When a customer or a journalist asks where a figure came from, you can answer within minutes. The record also tells you when a claim is due for rechecking.

## Know what not to hand over

Some communication needs a person's judgment from the first word:

- **A crisis or an incident.** Facts are changing, and a wrong statement makes things worse.
- **An apology.** An apology that reads as assembled does more harm than good.
- **News that affects staff or customers personally**, such as redundancies or a data breach.
- **Anything about a named individual.**

You can use Copilot to check such a message for clarity after you've written it. The words should start with you, and a senior person should approve them.

Also decide, with your organization, whether and how to tell your audience that AI helped to produce content. Some channels and some countries expect disclosure, especially for generated images. Follow your organization's policy.

## Try it now

Turn one approved source into channel versions, and review them before use:

1. Choose a piece of content that's already been approved and published, such as a case study, a report, or a long article.
2. Gather your style guide, or three examples of content you've published in the voice you'd like.
3. Upload them, and send the repurposing prompt from this chapter, adapted to the channels you use.
4. For each version, find the source sentences that Copilot listed, and compare them with the version.
5. Look for any place where shortening has turned a specific fact into a general promise. Correct it.
6. Send the review prompt from this chapter for one of the versions.
7. Make the four checks yourself: evidence, claims, consent, and brand voice. Note who would need to approve it.
8. Record each claim in the version, with its source and today's date.

You should now have three or more channel versions of one approved source, each compared with the original, and one that has been through all four checks.

> **What to ask next**: Ask Copilot to read the content as a skeptical outsider would: `Read this post as a journalist or a regulator would. Which statement would you challenge first, and what evidence would you ask for?`

### Check the result

- [ ] Does every fact, figure, and quotation in each version appear in the approved source?
- [ ] Did you find and correct any place where a specific fact had become a general promise?
- [ ] Do you have current, written permission for every quotation, name, and image of a person?
- [ ] Is there a named person who approves the content before it's published?

> **Real-world example**: A communications officer at a regional water company asks Copilot to turn an approved annual report into social posts. One post says the company "has eliminated leaks across the region." The report says leakage fell by 12%. She corrects the post, and adds a line to her saved prompt: "Don't strengthen any claim. If the source gives a number, use the number." She also records the claim and the page of the report it came from.

Marketing speaks to many people at once. Sales and customer success speak to one customer at a time, where the details of a single relationship count. [*Chapter 5.6, Workflows for sales and customer success*](05-06-Workflows-for-sales-and-customer-success.md), covers preparing for customer conversations, summarizing account history, and writing follow-ups that are individual.

[Go to next chapter >>](05-06-Workflows-for-sales-and-customer-success.md)
