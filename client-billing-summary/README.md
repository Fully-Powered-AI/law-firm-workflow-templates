# Client billing summary

Before an invoice goes out, get a client-readable summary tied to the pre-bill, with each guideline breach sent to the attorney to decide.

> [!TIP]
> **Missing a template that is not listed here, or want these customized for your organization? Reach out to us.** This is a template, made to be customized and deployed. FullyPowered AI customizes and builds AI workflows, connects them to your business systems, installs them in your agents and puts them in the hands of the people who own the work. [See Client billing summary on our website](https://fullypowered.ai/workflows/client-billing-summary/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=law-firm-client-billing-summary&from=gh-law-firm-client-billing-summary). Not sure where to start? Email hello@fullypowered.ai and a person will answer.

**Quick start**

1. Read EXAMPLE.md to see what a good result looks like.
2. Copy all of TEMPLATE.md into your assistant, then give it your own inputs, or the sample ones from EXAMPLE.md.
3. Read what comes back. It marks what it checked and what is left for you.

*Workflow template · Law firms · Finance and accounting · version 0.1.0 · [Workflows Directory](https://fullypowered.ai/workflows/client-billing-summary/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=law-firm-client-billing-summary&from=gh-law-firm-client-billing-summary)*

## The outcome

In a fully powered firm, invoices go out right the first time. The client opens a clear account of the month: who worked, on what, at which stage of the matter, and what it cost. The firm finds the entries the client's billing rules would refuse before the client's reviewers do, so fewer invoices come back with deductions and fewer weeks pass between sending and payment. That is 10X what your billing team can do with the hours it has.

The workflow template prepares two things from the pre-bill. The first is the summary for the client, written from the time entries in plain words, with every total tied to the pre-bill. The second is a review for the responsible attorney alone: each entry that breaks a guideline, with the section, the facts and the amount affected, and each time entry description that says more than an invoice should, such as a settlement position. The attorney decides every one. The workflow template writes nothing down, changes nothing in the billing system and sends nothing.

## Who starts the work, and when

The billing coordinator runs it as soon as the pre-bill for a matter is generated, so the responsible attorney reviews the flags and the client summary at the same sitting. It runs again from the updated pre-bill once the attorney's decisions are entered. It comes before the invoice goes out: chasing an unpaid invoice afterward is [Overdue-invoice follow-up preparation](https://fullypowered.ai/workflows/overdue-invoice-follow-up-preparation/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=law-firm-client-billing-summary&from=gh-law-firm-client-billing-summary), and a matter's billing terms are captured earlier, in [Matter-opening checklist preparation](https://fullypowered.ai/workflows/matter-opening-checklist-preparation/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=law-firm-client-billing-summary&from=gh-law-firm-client-billing-summary).

## What they supply

- **The pre-bill** for the matter and period, with its totals.
- **Three exports from the billing system:** the time entries, the expenses, and the write-downs and discounts already decided. The template names the column headings it expects and stops to ask when one does not match.
- **The client's billing guidelines:** approved timekeepers and rates, task and phase codes, limits, expenses the client will not pay, and any budget.
- **The matter's settings:** the responsible attorney, and the fees billed before this invoice, for the budget check.

## What comes out

One document in two parts. Part A, for the client once the attorney approves it: an overview of the period with the totals, then fees by timekeeper, by task and by phase, the expenses with subtotals, and the write-downs with the note the firm chose for the client. Part B, never sent: the tie-out to the pre-bill, the guideline rules checked and those that cannot be checked from the exports, the budget position, the numbered flags with a question for the attorney on each, and the descriptions to reword before the itemized detail prints.

If the exports do not add up to the pre-bill, nothing is drafted until the billing coordinator finds why. A good result lets the attorney clear the month's billing in one review, with no surprises from the client afterward.

See the worked example in [EXAMPLE.md](EXAMPLE.md).

## Where it fits

- [Law firms](https://fullypowered.ai/industries/law-firms/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=law-firm-client-billing-summary&from=gh-law-firm-client-billing-summary): the monthly step between the pre-bill and the invoice, for clients whose billing rules are strict.
- [Finance and accounting](https://fullypowered.ai/functions/finance-and-accounting/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=law-firm-client-billing-summary&from=gh-law-firm-client-billing-summary): the billing team owns the pre-bill, the exports and the tie-out.
- [Growth & scaling](https://fullypowered.ai/situations/growth-and-scaling/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=law-firm-client-billing-summary&from=gh-law-firm-client-billing-summary): when more clients arrive with their own billing rules than one billing coordinator can hold in their head.

More [law firm AI workflow templates](https://fullypowered.ai/industries/law-firms/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=law-firm-client-billing-summary&from=gh-law-firm-client-billing-summary) like this one.

## What has to change for your company

1.  **Your exports.** Map your billing system's column headings once, so every run reads them the same way.
2.  **Your house rules.** Add the checks your firm runs on every matter, whatever the client's guidelines say, such as a daily-hours limit or work the firm never bills.
3.  **Who does what.** Name who rewords a flagged description, who enters the attorney's decisions, and who sends the invoice, by email or through the client's billing portal.

We set this up with the billing coordinator and a responsible attorney, on past months your team remembers. This workflow template is written for ChatGPT, Claude, Copilot and Gemini, and your firm keeps control of how the work gets done.

## What has been checked

FullyPowered AI wrote this workflow template, drawing on a published billing summary method credited in its sources. It was editorially reviewed on 10 November 2026. It was tried on its example on 10 November 2026 in four runs; the instructions were revised after each of the first three, and the record of the fourth is published with it. That run did not reach any stop condition. After that run only the example's own output was edited, to agree with the instructions; the instructions were not changed. It has not yet been tested in a client environment. It has not yet been tested as a packaged version in ChatGPT, Claude, Copilot or Gemini.

Testing in your firm means running it on two or three past pre-bills whose client deductions you already know, plus hard cases written in advance: exports that do not add up to the pre-bill, a rate above the approved rate, two people billing the same internal meeting, a description that names a settlement position. The billing coordinator checks every figure against the pre-bill before anyone relies on it. [Pilot acceptance-test preparation](https://fullypowered.ai/workflows/pilot-acceptance-test-preparation/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=law-firm-client-billing-summary&from=gh-law-firm-client-billing-summary) builds that test set, and [What we test before we call an AI workflow ready](https://fullypowered.ai/insights/what-we-test-before-a-workflow-is-ready/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=law-firm-client-billing-summary&from=gh-law-firm-client-billing-summary) shows the record we keep.

- Written by FullyPowered AI.
- Sources and rights reviewed.
- Editorially reviewed on 10 November 2026.
- Package format checked by script on every release.
- Tried once on its example in Claude on 10 November 2026. The record is in [TRIAL.md](TRIAL.md).
- Not yet tested in a client environment.

## What is in this folder

- [TEMPLATE.md](TEMPLATE.md): the complete workflow template. Roles, inputs, the procedure, exceptions and stop conditions, the output format, a reviewer checklist, acceptance tests, the instructions for an AI assistant and what to customize.
- [EXAMPLE.md](EXAMPLE.md): a worked example.
- [TRIAL.md](TRIAL.md): what came out when the template was tried on its example.
- [SKILL.md](SKILL.md): the technical file, for AI products that load packaged instructions from a folder.
- [SOURCES.md](SOURCES.md): what the workflow template drew on, with licences.
- [LICENSE](LICENSE): MIT. Use it, change it, make it yours.

## Start using it

1. Read [EXAMPLE.md](EXAMPLE.md) to see what a good result looks like.
2. Open [TEMPLATE.md](TEMPLATE.md) and set every item under "What to customize" to your own rules, roles and limits.
3. Give your AI assistant the instruction block and the output format from the template, with your own limits in place of the ones the instructions leave open in square brackets. Paste them in as custom instructions in ChatGPT, Claude, Copilot or Gemini, or copy this whole folder into a product that loads `SKILL.md` packages. This folder stands alone; you do not need the rest of the repository.
4. Run it on past work first, using the reviewer checklist and acceptance tests in the template, before anyone relies on it.

## Related workflow templates

- [Overdue-invoice follow-up preparation](https://fullypowered.ai/workflows/overdue-invoice-follow-up-preparation/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=law-firm-client-billing-summary&from=gh-law-firm-client-billing-summary)
- [Matter-opening checklist preparation](../matter-opening-checklist-preparation/)
- [Weekly receivables summary](https://fullypowered.ai/workflows/weekly-receivables-summary/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=law-firm-client-billing-summary&from=gh-law-firm-client-billing-summary)

## Make it yours

This workflow template is an example and a starting point. FullyPowered AI adapts it to how your company works, proves it on real work and rolls it out to the roles that use it. We can also build any other workflow for your company, including one that runs several steps, in a Workflow Sprint or a scoped implementation. [Talk with us](https://fullypowered.ai/contact/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=law-firm-client-billing-summary&from=gh-law-firm-client-billing-summary).
