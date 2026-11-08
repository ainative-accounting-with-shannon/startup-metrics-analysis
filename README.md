# Investor Books Readiness Check

A free skill for Claude that checks a startup's books against what seed and Series A investors look for, and tells you how healthy the books are.

Connect your accounting software (Xero, QuickBooks or similar), ask Claude to run the check, and get two documents back.

## What you get

**Document 1: your report (private).**

- A scorecard of how the startup is doing: cash and runway, growth, margins, customer spread, and the measures that matter for your business type.
- A scorecard of how healthy the books are: twelve things an investor needs to be able to conclude from your books, each rated Good, Problem or Can't conclude yet.
- A table of the numbers investors ask for (burn, runway, margins, days to be paid, and more), with what is missing and who has it.
- Supporting details: every formula, input and month-by-month table, so you can check the work.

**Document 2: a redacted version you can share.**

- The same scorecards with names and amounts removed (ratios and months only by default).
- A short list of questions you can send to me. 



## What it checks

It starts from a full library of what investors look for, then keeps only the part that applies to you based on your round (seed or Series A) and your business type (software, AI-native, ecommerce, hardware, marketplace).

- Core numbers: cash, net burn, runway, revenue growth, gross and operating margin, customer concentration, days to be paid and days to pay suppliers.
- Records: monthly statements, bank matching, liabilities, month-end close, cap table, categorisation, documents.
- Business-type numbers: for example ARR and net revenue retention for software, inference cost for AI-native, contribution margin and inventory turnover for ecommerce.
- 33 health tests on the books themselves, such as balance sheet balances, cash agrees with the bank, nothing hidden in suspense accounts, old unpaid bills.

The full library and every formula are inside the skill file.

## How to use it

1. Add the skill to Claude. Put `SKILL.md` in a folder named `investor-books-readiness-check` and upload it as a skill (steps vary by plan; see Claude's help pages).
2. Connect your accounting software to Claude, read-only. The skill has links for Xero, QuickBooks and others. If you can't connect, upload exports of your reports instead.
3. Ask Claude: "Run the investor books readiness check."
4. Answer two questions (your round and your business type). Everything else is optional.
5. Read both documents. Read the redacted one before you share it.



## Privacy and safety

- **Read-only.** It never changes your books or sends anything.
- **Nothing leaves your chat.** It does not email, post or upload for you.
- **You decide what to share.** Document 2 is redacted, but redaction can miss details, so read it first.
- **No passwords in the chat.** Sign-in happens in your accounting software's own window.



## Limits

This is general information, not accounting, tax or legal advice. Benchmarks are rough, come from secondary sources, and vary by stage and sector. The check is only as good as the data it can read. Where it can't tell, it says what is missing instead of guessing. Please read the output critically.

## Questions? Want a second opinion?

Send the redacted document (Document 2) and your questions to me.

- Email: [shannonruxin@gmail.com](mailto:shannonruxin@gmail.com)
- Blog: [Shannon Accounting](https://shannonaccounting.substack.com)
- The post this is built on: [The Numbers Investors Expect You to Know](https://shannonaccounting.substack.com/p/numbers-investors-expect-you-to-know)

Made by Shannon Choo, founder of OpenClose, an AI-native accounting firm.