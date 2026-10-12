# Chapter 5.4: Workflows for analysts, finance, and operations

If your work is built on numbers, you already know that a figure is only as good as the data and the method behind it. Copilot can prepare data, write formulas, run an analysis, and draft the commentary that goes with it. It does all of this quickly, and it presents a wrong number as confidently as a right one. In roles where figures feed budgets, forecasts, and operational decisions, accuracy is worth more than speed. In this chapter, you'll see three workflows for preparing and validating data, producing recurring analysis and commentary, and finding anomalies. By the end, you'll have a recurring analysis with checks built in, and a clear point where a person signs it off.

> **Plan note**: Copilot in Excel works with every plan covered in this book. Analyst needs Microsoft 365 Premium or Pro, or a Microsoft 365 Copilot license. Where a workflow uses Analyst, you can use Copilot in Excel instead, with more steps.

## Where Copilot fits in work with numbers

| Copilot helps with | Keep with yourself |
| --- | --- |
| Finding blanks, duplicates, and inconsistent values | Deciding how to treat each one |
| Writing and explaining formulas | Choosing the method |
| Repeating the same analysis each period | Judging whether a change is important |
| Drafting commentary from figures you've checked | The explanation of why a figure moved |
| Listing unusual values for you to investigate | Any figure that's reported, filed, or paid |

Figure 5.4.1 shows the path that every workflow in this chapter follows.

*Figure 5.4.1: Data passes through checks before analysis, and through approval before anyone relies on it.* [Diagram 5.4-A]

## Workflow 1: Prepare and validate data

Getting the data ready often takes longer than the analysis. Chapter 2.4 covered the basics: a tidy table, an audit before any change, and blanks left blank. In a recurring process, add checks that run every time.

| | |
| --- | --- |
| **When** | Each time new data arrives, before any analysis |
| **Inputs** | The new extract, and the previous period's data for comparison |
| **Tool** | Copilot in Excel (Chapter 2.4) |
| **Check** | Row counts, control totals, and date ranges against the source system |
| **Stays with you** | How to treat missing, duplicate, or disputed records |

Ask for a validation report before anything is changed:

```
Validate this table before I analyze it. Don't change anything. Report:
1. The number of rows, and the earliest and latest date.
2. The total of [amount column], so I can compare it with the source system.
3. Blank cells, by column.
4. Duplicate rows, and rows that share [ID column].
5. Values outside the expected range: [state the range, such as negative amounts or dates outside the period].
6. Any category in [column] that didn't appear last period, or that appeared last period and is missing now.
```

Compare the row count and the control total with the figures from the system the data came from. If they don't match, stop. An analysis of incomplete data is worse than no analysis, because it looks finished.

Item 6 catches a common problem. When a cost center is renamed or a new product code appears, the totals still add up, but a category has silently split or vanished.

Keep the validation prompt as a saved prompt, and keep each period's report. Over time, the reports become a record of the data's quality.

## Workflow 2: Produce recurring analysis and commentary

A monthly report asks the same questions of new data each time. That makes it a good candidate for a recurring task, as long as the method stays fixed.

| | |
| --- | --- |
| **When** | Each period, after validation has passed |
| **Inputs** | The validated data, the previous period's report, and the budget or target |
| **Tool** | Copilot in Excel for a workbook you maintain. Analyst for a one-time or cross-file analysis (Chapter 2.5). A recurring Cowork task once the method is stable (Chapter 4.4) |
| **Check** | One figure by hand, the unusual rows, and the totals (Chapter 2.4). Every figure in the commentary against the workbook |
| **Stays with you** | The method, the explanation of each variance, and sign-off |

Three practices keep a recurring analysis dependable.

**Fix the method in writing.** Describe each calculation in the brief, or better, keep the formulas in the workbook and have Copilot refresh the data. "Calculate the variance" leaves room for a different method each month. "Variance equals actual minus budget, shown as a value and as a percentage of budget" doesn't.

**Separate the numbers from the words.** Have Copilot produce the figures first. Check them. Only then ask for commentary, and tell it to use the checked figures:

```
Using only the figures on the "Summary" sheet, draft commentary for the monthly report. For each line where the variance to budget is more than [threshold], state the figure and the size of the variance. Don't explain why it moved unless the reason is recorded in the "Notes" column. Where no reason is recorded, write [REASON NEEDED].
```

**Don't let Copilot explain what it can't know.** A model will readily write "driven by seasonal demand" beside a variance. That's a guess. The reason a figure moved is in the business, in the people who placed the orders or approved the overtime. The **[REASON NEEDED]** marker sends you to ask them.

Use a fact sheet, as in Chapter 2.10, when the same figures appear in a workbook, a report, and a set of slides.

> **Watch out**: Commentary drafted by Copilot can state a cause as though it were a finding. "Costs rose because of supplier price increases" reads as fact. If nobody has confirmed it, it's an invention with your name on it. Check every "because," "due to," and "driven by" in a draft. Each one needs a source that a person can name.

## Workflow 3: Identify anomalies without delegating final judgment

An **anomaly** is a value that doesn't fit the pattern of the others. Copilot and Analyst are good at finding them in a large table, which would take a person a long time to do by eye.

| | |
| --- | --- |
| **When** | Each period, or when something looks wrong |
| **Inputs** | The validated data, and enough history to show what's normal |
| **Tool** | Analyst for larger or multi-file data. Copilot in Excel for one table |
| **Check** | Each flagged item in the source records |
| **Stays with you** | Whether an item is an error, a problem, or a legitimate exception, and what to do about it |

Ask for a list of leads, with the reasoning for each:

```
Look for unusual values in this data, compared with the previous 12 months. Consider: amounts much larger or smaller than usual for that category, duplicate payments or entries, round-number amounts that are unusual for that supplier, activity on unusual dates, and sudden changes in trend. List each item with why it stands out and how far it is from normal. Don't say whether it's an error. Don't change or remove anything.
```

Treat the result as a list of things to look into. An anomaly might be a data entry mistake, a problem that needs action, or a perfectly good exception, such as a large annual payment. Copilot can't tell which. It can only tell you that the value is unusual.

Two cautions:

- **The absence of anomalies isn't assurance.** Copilot may miss items, especially in a large file. A clean result doesn't mean that the data is clean.
- **A flag about a person or a supplier is serious.** If the list suggests that someone made a duplicate claim, don't share it or act on it until you've checked the records yourself. An unfounded suspicion can do lasting harm.

## Keep a trail that someone else could follow

In finance and operations, you may be asked months later how a figure was produced. Build the answer as you go.

- **Keep the raw data unchanged**, on its own sheet or in its own file.
- **Keep the validation report** for each period.
- **Keep calculations as formulas** in the workbook where you can, so that anyone can see how a number was reached.
- **Record what Copilot did.** In Excel, **Show Changes** on the **Review** tab shows edits made with Copilot. For Analyst, save the steps and row counts it reports.
- **Record who approved the result**, and when.

Some figures carry legal weight: statutory accounts, tax returns, payroll, and regulatory filings. For these, follow your organization's controls, and don't use an automation that those controls haven't approved. Ask a qualified person to review anything you're unsure about.

> **Good practice**: Agree a threshold for what you'll investigate, before you look at the results. For example: any variance over 5% or over a set amount. A threshold set in advance stops you from explaining away an awkward figure, and it tells Copilot exactly what to list.

## Try it now

Add checks and a sign-off point to one recurring analysis:

1. Choose an analysis you produce regularly. Take the latest data and the previous period's.
2. Adapt the validation prompt from this chapter with your own column names and expected ranges, and run it in Excel.
3. Compare the row count and the control total with the source system. If they differ, find out why before you continue.
4. Run your analysis as usual, or ask Copilot to produce the summary figures. Check one figure by hand, and check that the parts add up to the total.
5. Send the commentary prompt from this chapter, with your own threshold.
6. Find every statement of cause in the draft. Replace any that you can't support with **[REASON NEEDED]**, and note who could supply the reason.
7. Run the anomaly prompt. Choose two flagged items, and look each one up in the source records.
8. Write down where the method, the validation report, and the approval are recorded.

You should now have a validation report that agrees with the source, checked summary figures, commentary with unsupported causes marked, and two anomalies that you've investigated yourself.

> **What to ask next**: Ask Copilot what could make this analysis wrong without anyone noticing: `What changes in the source data, such as renamed categories, new codes, or a different export layout, would make this analysis produce wrong results while still looking normal?`

### Check the result

- [ ] Did the row count and control total match the source system?
- [ ] Is each calculation defined in writing or held as a formula in the workbook?
- [ ] Does every stated cause in the commentary have a source that a person can name?
- [ ] Is there a named person who signs off the result, and a record that they did?

> **Real-world example**: A management accountant at a furniture maker uses Analyst to review a year of supplier payments. It flags a payment that's exactly twice the usual monthly amount. She doesn't mention it to anyone until she has opened the invoices. The supplier had sent one invoice covering two months, at the company's own request. She notes the reason against the item. The same review flags a second payment she can't explain, and that one turns out to be a duplicate.

Numbers support decisions inside an organization. The next role speaks to people outside it, where a wrong claim can be seen by thousands. [*Chapter 5.5, Workflows for marketing and communication*](05-05-Workflows-for-marketing-and-communication.md), covers research, repurposing approved material, and checking what you publish.

[Go to next chapter >>](05-05-Workflows-for-marketing-and-communication.md)
