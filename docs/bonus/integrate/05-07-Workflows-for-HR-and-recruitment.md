# Chapter 5.7: Workflows for HR and recruitment

HR and recruitment work affects people's livelihoods. A decision to hire, promote, discipline, or dismiss someone changes their life, and it has to be fair, explainable, and lawful. That sets a firm limit on how Copilot is used in this role. It can prepare the materials that surround a decision: the job description, the interview questions, the policy summary, the onboarding plan. It shouldn't screen, rank, score, or decide. In this chapter, you'll see workflows for preparing role and interview materials and for summarizing policies and onboarding content, and you'll learn where the boundary around human decisions sits and why. By the end, you'll have prepared materials for one role, and drawn your own line between what Copilot prepares and what people decide.

> **Plan note**: These workflows use Chat, Word, and file uploads, which work with every plan covered in this book. Use your work account for anything that involves employees or candidates. Many organizations and countries have specific rules about AI in employment. Check your organization's policy and take legal advice before you change how you recruit or manage people.

## Where Copilot fits in HR and recruitment

| Copilot helps with | Keep with a person |
| --- | --- |
| Drafting a job description from a list of duties | Deciding what the role requires |
| Checking wording for bias and clarity | Shortlisting and rejecting candidates |
| Preparing structured interview questions | Assessing a candidate's answers |
| Summarizing a policy in plain language | Interpreting a policy for an individual's case |
| Building an onboarding plan and checklist | Any decision about pay, promotion, discipline, or dismissal |
| Drafting standard letters from an approved template | Any conversation about someone's health, conduct, or circumstances |

Figure 5.7.1 shows the boundary that this chapter is built around.

*Figure 5.7.1: Copilot's preparation surrounds the decision. The decision itself, and the conversation with the person, stay inside a human boundary.* [Diagram 5.7-A]

## Workflow 1: Prepare role and interview materials

Clear, fair materials improve a recruitment process before any candidate is involved. This is preparation, and it involves no personal data.

| | |
| --- | --- |
| **When** | A role is being opened or redesigned |
| **Inputs** | The hiring manager's list of duties and requirements, your organization's job description template, and the pay band if it's published |
| **Tool** | Copilot Chat or Copilot in Word (Chapter 2.3) |
| **Check** | Every requirement against what the job needs. Wording for bias. Compliance with your organization's policy and local law |
| **Stays with you** | What the role requires, and approval of the final text |

Ask for a job description that separates what's essential from what's preferred:

```
Draft a job description for [role] using the attached duties and our attached template. Separate essential requirements from desirable ones. For each essential requirement, say which duty it relates to. Use plain language. Don't add requirements that aren't in the duties list, such as a degree or a number of years of experience. Don't describe the ideal candidate's personality.
```

Then ask for a review of the wording:

```
Review this job description. List any words or requirements that could discourage qualified people from applying, or that might disadvantage a group, such as by age, gender, disability, or background. For each one, say why, and suggest neutral wording. List any requirement that isn't linked to a duty.
```

Treat the review as a first pass. Copilot can spot loaded words such as "energetic" or "digital native." It doesn't know your country's employment law, and it can miss problems as well as find them. A person who knows the law still needs to read the text.

For interviews, ask for **structured questions**: the same questions for every candidate, each tied to a requirement of the role, with a description of what a good answer would cover.

```
For each essential requirement in this job description, write two interview questions that ask the candidate to describe what they've done in a relevant situation. For each question, list what a strong answer would include. Don't write questions about age, family, health, nationality, religion, or anything else unrelated to the duties.
```

Structured questions make interviews fairer and easier to compare. The interviewers still listen, probe, and assess. Copilot doesn't score the answers.

## Workflow 2: Summarize policies and onboarding content

Policies are long and written with care, and staff need quick answers. Onboarding needs the same information arranged for someone on their first day.

| | |
| --- | --- |
| **When** | A policy is published or changed, or a new starter is expected |
| **Inputs** | The approved policy documents, and the role's details for onboarding |
| **Tool** | Copilot Chat or Word for summaries. A policy agent for recurring questions (Chapter 4.7) |
| **Check** | Each statement in a summary against the policy's wording. Approval by the policy's owner |
| **Stays with you** | What the policy means for an individual, and any exception |

Ask for a plain-language summary that stays tied to the policy:

```
Summarize the attached [policy name] for employees in plain language, on one page. For each point, give the section number of the policy it comes from. Keep any condition or exception that the policy states. Where the policy says "may" or "at the manager's discretion," keep that wording. Don't interpret, and don't give examples that aren't in the policy. End with: "This summary doesn't replace the policy. If they differ, the policy applies."
```

The instruction to keep "may" and "at the manager's discretion" is important. A summary that turns "may be granted" into "you can have" creates an entitlement that the policy never gave.

Have the policy's owner approve the summary before it's shared. If staff ask the same questions repeatedly, build an agent on the approved policy, with the tests from Chapter 4.7. Its instructions should refuse questions about individual cases and direct people to HR.

For onboarding, ask for a plan by day and week:

```
Using the attached role description and our onboarding checklist, draft a first-month plan for a new [role]. Show what happens on day one, in week one, and in weeks two to four. For each item, say who's responsible. Mark anything that needs setting up before the start date.
```

Add the things only you know: who should take them to lunch, which meeting to skip in the first week, and who to ask about the things nobody writes down.

## Keep employment decisions and sensitive judgments human-led

This is the firmest boundary in this book. Keep the following with people, every time.

**Screening and shortlisting.** Don't ask Copilot to rank applications, score them, or recommend who to reject. A model can reproduce bias from patterns in its training or in your past decisions, and it can't explain its ranking in a way that would satisfy a rejected candidate or a tribunal. A person should read each application against the published criteria.

**Assessment.** Don't ask Copilot to judge a candidate's interview, a colleague's performance, or the truth of a complaint.

**Decisions.** Hiring, pay, promotion, discipline, dismissal, redundancy selection, and adjustments for health or disability are decisions for accountable people, following your organization's process.

**Individual cases.** Don't put details of a grievance, a health condition, a disciplinary matter, or a personal circumstance into a prompt to ask what should be done.

Four reasons stand behind this boundary:

- **Fairness.** People are entitled to have decisions about them made on relevant grounds, by someone who has considered their case.
- **Explanation.** You need to be able to say why a decision was made. "The AI ranked them lower" doesn't answer that.
- **Law.** Many countries regulate automated decision-making, discrimination, and the processing of personal data in employment. Some give people a right not to be subject to decisions made only by automated means.
- **Trust.** Staff and candidates need to believe that a person looked at their case.

What Copilot may do near a decision is limited and specific. It may put the documents for a case in date order, without commenting on them. It may check a draft letter against an approved template. It may list which steps of a process have been completed. Even then, check your organization's policy, and use your work account.

> **Watch out**: Summarizing applications is closer to screening than it appears. A summary decides what to leave out. If Copilot's summary omits a career break, or highlights a prestigious employer, it has shaped the reader's view before they've seen the application. If you use summaries at all, have a person read every full application, and never let a summary be the only thing a decision-maker sees.

## Protect the information you hold

HR holds some of the most sensitive data in any organization.

- **Use only your work account**, with the protections your organization has set.
- **Give Copilot the minimum.** Most preparation needs no personal data. A job description, a policy summary, and an onboarding template involve no named individual.
- **Check where files are stored.** HR files in a widely shared location are the oversharing problem from Chapter 3.1 at its most serious.
- **Remember that prompts are records.** Chapter 3.1 explained that work prompts are stored. A prompt about a named employee may be disclosable if that person asks to see their data.
- **Follow retention rules.** Candidate and employee data must be deleted on schedule. Notes and summaries made with Copilot are part of that data.

> **Good practice**: Write your team's rule in one paragraph, and share it with hiring managers: what Copilot may prepare, what it may not do, and who to ask. Managers under time pressure will be tempted to paste twenty applications into a chat and ask for the best five. A clear rule, given before the vacancy opens, is easier to follow than a correction afterward.

## Try it now

Prepare materials for one role, and write down where your boundary sits:

1. Choose a role, either one that's open or one you know well. Write its duties as a list.
2. Send the job description prompt from this chapter, with the duties and your template.
3. Check each essential requirement against a duty. Remove any that the job doesn't need.
4. Send the wording review prompt. Consider each suggestion, and accept the ones you agree with.
5. Send the interview questions prompt. Check that every question relates to an essential requirement.
6. Choose one approved policy, and send the summary prompt. Compare three statements in the summary with the policy's wording, looking for any "may" that has become "will."
7. Write one paragraph that states what Copilot may prepare in your recruitment process, what it may not do, and who decides.
8. Before you use any of these materials, have them reviewed by the person responsible for employment policy in your organization.

If you don't work in HR, do steps 1 to 5 for a role in your own team, and share the result with your HR contact.

You should now have a job description with requirements tied to duties, a set of structured interview questions, a policy summary checked against the original, and a one-paragraph statement of your boundary.

> **What to ask next**: Ask Copilot to test your boundary statement: `Here is our rule for using AI in recruitment: [paste your paragraph]. Describe five situations where a busy hiring manager might be unsure whether something is allowed. For each one, suggest wording that would make the rule clearer.`

### Check the result

- [ ] Is every essential requirement in the job description linked to a duty?
- [ ] Do the interview questions avoid personal topics that are unrelated to the role?
- [ ] Does the policy summary keep every condition and every "may" from the original?
- [ ] Does your boundary statement keep screening, assessment, and decisions with people?

> **Real-world example**: A recruitment lead at a logistics firm uses Copilot to redraft a warehouse supervisor's job description. The review flags "must be physically fit" as a requirement that isn't tied to a duty. She asks the hiring manager, who explains that the job involves regular lifting. She replaces the phrase with the specific task and weight, which is fairer to candidates and clearer about the job. When the hiring manager later asks whether Copilot could "do a first sift" of the 80 applications, she says no, and arranges for two people to read them against the criteria.

HR prepares people for their work inside an organization. Teaching and training prepare people more broadly, and they bring their own duties of accuracy and care. [*Chapter 5.8, Workflows for educators and trainers*](05-08-Workflows-for-educators-and-trainers.md), covers planning, adapting materials, and checking them before they reach learners.

[Go to next chapter >>](05-08-Workflows-for-educators-and-trainers.md)
