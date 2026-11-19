# AI workflow templates for law firm operations and paralegals

FullyPowered Workflow Templates for law firms turn the AI your firm already pays for into a team that knows how the work is done: a billing coordinator with every awkward prebill entry marked for review, a paralegal with a draft case chronology prepared from the approved documents, a legal assistant with a court-order deadline notice drafted for the attorney. 24 workflow templates, made to be customized and deployed. All plain Markdown, all free, MIT license.

We are FullyPowered AI. We build AI workflows for companies, and these are the templates we start from. We publish them because a good starting point should be open to everyone. Copy one. Change it. Make it yours.

> [!TIP]
> **Missing a template that is not listed here, or want these customized for your organization? Reach out to us.** These are templates, made to be customized and deployed. FullyPowered AI customizes and builds AI workflows, connects them to your business systems, installs them in your agents and puts them in the hands of the people who own the work. [See more examples for law firms](https://fullypowered.ai/industries/law-firms/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=law-firm-readme&from=gh-law-firm-readme) · [Have one built for your team](https://fullypowered.ai/pricing/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=law-firm-readme&from=gh-law-firm-readme) Not sure where to start? Email hello@fullypowered.ai and a person will answer.

**Who this is for**

- Managing partners who want the firm's AI preparing routine work the same careful way every time.
- Practice and operations managers who want something their team can run on open matters this week.
- The paralegal or associate who prepares the work, while a named attorney decides every legal question.

**What these are for**

- **Your best way of doing it, for the whole team.** One piece of work, written down precisely enough that an assistant prepares it the same way every time.
- **Work you can check.** Every template says what it needs, what it produces, what it checked and what it could not.
- **A person decides.** Anything that sends, posts, pays or changes a record waits for someone to approve it.
- **Tied into your business systems.** A workflow can be designed to pull from the systems your company already runs, and even push data back into them, with guardrails and a person approving. [Browse the Connectors Directory](https://fullypowered.ai/connectors/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=law-firm-readme&from=gh-law-firm-readme).
- **Free, open and portable.** MIT-licensed plain instructions that run in the assistant or agent your team already uses: ChatGPT, Claude, Claude Code, Claude Cowork, Codex, Copilot, Gemini, Grok, Perplexity.

**Quick start**

1. **Turn your last consultation notes into a fact record.** Open ChatGPT, Claude, Copilot or Gemini. Copy the text below into a new chat and replace the square brackets with your own notes. Use notes you already have and remove anything you would not paste into an assistant your firm has not approved.

   ```text
   Act as a preparation assistant for a law firm's intake attorney. Below are the notes from one first consultation. Prepare a draft fact record. Mark each statement as first-hand, secondhand, the client's assumption, or basis not stated. Mark each date as confirmed, approximate or unknown, using only what the notes say. Quote exact words. Set apart the outcome the client wants. List every document mentioned but not supplied. Show contradictions and gaps without choosing between them. End with factual follow-up questions for the attorney to choose from. Name no legal issue, give no legal advice, count no time limit and clear no name. Leave out the note-taker's own comments. The attorney verifies and decides everything. Send nothing and change no record. Notes: [paste notes]. Who was present: [names and roles]. Attorney who verifies: [name].
   ```

2. Read what comes back. It marks what it checked and what is left for you. What comes back, from an invented consultation:

   ```text
   DRAFT CONSULTATION FACT RECORD · FOR THE INTAKE ATTORNEY TO VERIFY
   Not legal advice. Names no legal issue and gives no view on the matter.
   Decides nothing about legal meaning, merit, validity, privilege,
   conflicts or deadlines: no name is cleared and no time limit is counted.
   Nothing has been sent, filed, signed, calendared or added to the matter
   file.

   Prospective client: Ines Varga
   Matter label: Varga / Contractor B, ventilation works
   Consultation: 4 November 2026, video, 10:00 to 10:50
   Present: Ines Varga, prospective client; Tomas Reyhill, intake attorney;
     Priya Lund, paralegal (notes)
   Source: notes by Priya Lund, 15 paragraphs
   Prepared for: Tomas Reyhill, to verify
   ```

3. Stop there. You will know if this is for you. When you want it fitted to your company, or built into your agents, [that is what we do](https://fullypowered.ai/pricing/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=law-firm-readme&from=gh-law-firm-readme).

These templates prepare the work and a named attorney decides; nothing here is legal advice, and no template has been reviewed by a lawyer.

These are examples and a starting point, made to be changed to fit how your firm works. Work that is not here can be built too, as one step or many.

## The workflow templates here today

- **[Authority comparison table](authority-comparison-table/)**: From the opinions, statutes and regulations counsel selected, and only those, the researching lawyer gets one side-by-side table: each authority's court, date, stated issue, operative words, posture and separate opinions, quoted with pinpoints, and a list of every quotation to check. The lawyer decides what applies.
- **[Case chronology from the matter documents](case-chronology/)**: From the document set the handling attorney approved, the paralegal or associate prepares a draft chronology for that attorney: each event with its source and Bates number or page, document dates kept apart from event dates, conflicting accounts side by side, and the gaps. What matters is left to the attorney.
- **[Citation and quotation check](citation-and-quotation-check/)**: Before a draft is filed or relied on, the associate or paralegal has one worksheet: every citation, quotation and record cite counted, then set against the sources supplied, and every good-law check left for the lawyer. No result calls anything confirmed; each says only what was compared.
- **[Client billing summary](client-billing-summary/)**: Before an invoice goes out, the billing coordinator has a summary the client can read: fees by timekeeper, task and phase, expenses and write-downs, tied to the pre-bill. Every entry that breaks the client's billing guidelines reaches the responsible attorney as a decision, with the amount at stake.
- **[Closed-file retention review](closed-file-retention-review/)**: When closed matter files are ready for records review, the records officer has a draft list for supervising counsel in four groups: files whose period has run under the firm's own schedule, files under a hold, client originals not yet returned, and files that cannot be assessed. Nothing is destroyed or moved.
- **[Conflict search record](conflict-search-record/)**: Before the responsible attorney decides on a new matter, the conflicts clerk has a draft search record: every name searched with its aliases and related entities, every possible match with its source matter and why it matched, the names still to search, and the limits of the search. It clears nothing.
- **[Consultation fact record](consultation-fact-record/)**: After a first consultation, the intake attorney gets a draft fact record: each statement marked by how the client knows it, each date by how exactly it was given, the outcome the client wants set apart, every document mentioned but not supplied, and questions to choose from. It names no legal issue.
- **[Court-order deadline notice preparation](court-order-deadline-notice-preparation/)**: When a court order arrives, the legal assistant has a draft notice ready for the attorney: every directive in the court’s own words, every date copied from the order or proposed under the firm’s own written rule file, and a list for the attorney to confirm. Nothing is calendared or sent until the attorney confirms.
- **[Deposition transcript summary](deposition-transcript-summary/)**: Before the next deposition, a motion or trial, the attorney has a draft page-line summary of the transcript, arranged by the topics they named: every point cited, every exhibit and objection logged, and every place the testimony differs flagged without a label. The attorney decides what it means.
- **[Discovery requests and commitments register](discovery-commitments-register/)**: Through discovery, the litigation paralegal keeps one register for the handling attorney: each request and its response in the exact words served, the Bates ranges produced against it, every supplement promised in correspondence with its date as written, and the promises now overdue. The attorney decides what it means.
- **[Filing package check](filing-package-check/)**: Before a filing goes to the attorney for signature, the paralegal gets every item on the firm’s own checklist for that court and judge marked pass or open: caption against the docket, length and format, certificates, exhibits, signature blocks and service. The attorney decides and signs.
- **[Hearing preparation pack](hearing-preparation-pack/)**: Before a set hearing, the arguing attorney has one draft pack: the hearing as the notice states it, the docket history, each order's directives quoted, each witness's prior statements with page cites, exhibit and checklist status as the firm records them, and an open-items list. The attorney decides every argument.
- **[Inquiry handoff](inquiry-handoff/)**: Every new inquiry reaches the firm’s conflict review and the responsible attorney as one complete packet on the day it arrives, with each missing item named and someone assigned to supply it.
- **[Matter budget and status summary](matter-budget-and-status-summary/)**: The responsible partner sees one matter whole: scope, phases against their dates, the budget against fees to date and the projected total, a red, amber or green status with the rule behind it, risks and next actions with owners. Built from the time export and the matter plan, never a view on the merits.
- **[Matter closing checklist preparation](matter-closing-checklist-preparation/)**: When the handling lawyer flags a matter for closure, the firm's closing checklist is filled from the matter record: final billing as recorded, open tasks, unreturned items and the handoffs billing and records must accept.
- **[Matter coverage plan for absences](matter-coverage-plan/)**: When leave or a staffing change takes someone away from active matters, the practice manager gets a draft coverage plan: a proposed cover for each matter, the attorney-confirmed dates in the absence, the access each cover needs and every handoff that is blocked. The practice lead and responsible attorneys decide.
- **[Matter-opening checklist preparation](matter-opening-checklist-preparation/)**: Every accepted matter goes into setup and billing with one checklist: the fields each system needs, the terms that drive the first invoice, the documents on file and an owner for every open item.
- **[Outgoing work sign-off log](outgoing-work-sign-off-log/)**: Every item that needs a responsible attorney's sign-off before it leaves the firm sits in one log, in the order it has to go out: waiting, approved or returned, with the attorney's own note. Anything close to its date with no decision is flagged first. The log tracks status and never touches the legal substance.
- **[Prebill exception review](prebill-exception-review/)**: Before the billing attorney opens a prebill, the billing coordinator has every awkward entry marked: rates that differ from the firm's rate table, possible duplicates, entries outside the client's billing guidelines, unclear narratives and expenses without support, each sent to the person who acts next.
- **[Privilege log entry check](privilege-log-entry-check/)**: Before a draft privilege log goes to review counsel, the paralegal gets an entry-by-entry check against counsel’s approved format and role map, and a list of logged documents’ attachments with no entry. It checks metadata only: review counsel makes every privilege call and writes or approves every description.
- **[Document production index and summaries](production-document-index/)**: From a production review counsel has cleared, the paralegal prepares a draft for that counsel: an index of every document by Bates range, a short summary of each, every statement cited to its Bates page, missing documents and differing passages listed, and anything matching counsel's screen list held by number only.
- **[Referral source follow-up](referral-source-follow-up/)**: The day after a partner meets someone who sends the firm work, they have a follow-up draft and a list of every promise made at the table, by both sides. The draft uses only approved materials and nothing said in confidence; the partner checks it, chooses the next step and sends it.
- **[Research plan for counsel](research-plan-for-counsel/)**: Before an associate or paralegal starts on a partner's research question, they hold a one-to-two-page plan: the question split into sub-questions, the stated facts against each, the firm's own notes to read first, where to search and with what terms, and the gaps. Leads, not authorities: nothing is named from memory.
- **[Weekly open-matter check](weekly-open-matter-check/)**: Every Monday the operations manager sees every open matter: which tasks are overdue, which have no owner, and which matters could not be checked at all. The managing partner gets one summary, and each responsible attorney gets a note that is drafted and ready for the manager to send.

## How to use one

Open a folder and start with its README. Every folder stands alone, so copy the one you want and leave the rest. The templates are written for ChatGPT, Claude, Copilot and Gemini: paste the instruction block and the output format in as custom instructions, or load the folder in a product that reads `SKILL.md` packages.

To take the whole collection, press **Use this template** at the top of this page: it copies every folder into a repository in your own account, yours to change.

In every template a person starts the work, supplies the inputs and decides. The template prepares and checks. Anything that sends, posts, pays or changes a record waits for a person to approve it.

## What SKILL.md is

Each folder holds a file named `SKILL.md`. It is the technical file: the same instructions and output format as the template, in the packaged form that AI products which load instructions from a folder read. It is generated from `TEMPLATE.md`, so the two always agree. The workflow template is the whole folder; `SKILL.md` is one way of loading it. If your AI product does not read that format, use `TEMPLATE.md`.

## What "checked" means here

Each folder says exactly what was checked and when: who wrote it, that its sources and rights were reviewed, the date of its editorial review, and whether it has been tried on its invented example in a named AI product. Nothing is described as tested for a client unless it was. Test a template on your own past work before your team relies on it; each one comes with acceptance tests for that.

## More workflow templates

The [FullyPowered Workflows Directory](https://fullypowered.ai/workflows/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=law-firm-readme&from=gh-law-firm-readme) lists every workflow template across functions and industries, with search. A machine-readable list of this repository is in [index.json](index.json).

For the work these templates come from, by practice area and by task, see [AI workflow examples for law firms](https://fullypowered.ai/industries/law-firms/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=law-firm-readme&from=gh-law-firm-readme).

In-house teams have their own page: [AI workflow examples for legal and contracts teams](https://fullypowered.ai/functions/legal-and-contracts/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=law-firm-readme&from=gh-law-firm-readme).

## Licence and credits

MIT, in [LICENSE](LICENSE) and in every folder. Each folder's SOURCES.md names what the workflow template drew on. Published by [FullyPowered AI](https://fullypowered.ai/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=law-firm-readme&from=gh-law-firm-readme).
