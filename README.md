# Money and budgeting in South Africa

How to manage everyday money in South Africa, taught by your AI assistant: budgeting on a low or
irregular income, bank accounts, credit and your credit record, loan sharks, getting out of debt,
saving and stokvels, insurance and scams.

> [!WARNING]
> **Under development. Do not rely on this course yet.** The lessons have not been reviewed by a
> qualified financial professional and may contain mistakes. Confirm anything important with the
> [National Credit Regulator](https://www.ncr.org.za) or the [FSCA](https://www.fsca.co.za).
>
> **Are you a financial professional, such as a registered debt counsellor or financial adviser?**
> We're looking for professionals to review these lessons.
> [Offer to review](https://github.com/things-they-dont-teach-you/south-african-money/issues/new?template=volunteer-reviewer.yml)
> or use the [contact form](https://things-they-dont-teach-you.github.io/#contact).

Part of [Things They Don't Teach You in School](https://github.com/things-they-dont-teach-you).
Easiest start: the [enrol](https://github.com/things-they-dont-teach-you/enrol) repo, which sets
up this course for you.

## Start on its own

```sh
git clone https://github.com/things-they-dont-teach-you/south-african-money.git
cd south-african-money
claude
```

Codex and Gemini CLI work too. Say hello and the tutor takes it from there.

## Lessons

1. [Making a budget that works](lessons/01-making-a-budget.md)
2. [Bank accounts and fees](lessons/02-bank-accounts.md)
3. [How credit works, and what it costs](lessons/03-how-credit-works.md)
4. [Your credit record](lessons/04-your-credit-record.md)
5. [Loan sharks and payday loans](lessons/05-loan-sharks-and-payday-loans.md)
6. [When debt gets too much](lessons/06-when-debt-gets-too-much.md)
7. [Saving, emergency funds and stokvels](lessons/07-saving-and-stokvels.md)
8. [Insurance, funeral policies and scams](lessons/08-insurance-and-scams.md)

Figures live in [facts.md](facts.md), each with its official source and the date it was checked.
Tax-free savings accounts are covered in [south-african-tax](https://github.com/things-they-dont-teach-you/south-african-tax),
and investing in [south-african-investing](https://github.com/things-they-dont-teach-you/south-african-investing).

## This is not financial advice

This course explains how things work. For your own situation, see an NCR-registered debt
counsellor or an FSCA-authorised financial adviser. Always confirm figures on the official sites
in [facts.md](facts.md) before you act.

## Known gaps

Things we could not confirm from an official source when the course was written (2026-11-11).
The lessons avoid relying on them; help filling them is welcome.

- **Interest rate limits after 2016.** The caps in `facts.md` come from the 2015 regulations
  (Government Notice 1080). We found no newer replacement, but could not confirm on the NCR site
  that none exists.
- **Short-term credit definition.** The maximum amount and term that make a loan "short-term"
  under the regulations were not checked, so lessons don't state them.
- **Credit life insurance limits.** The regulations capping its cost were not checked.
- **How long information stays on a credit record.** Retention periods for judgments, defaults
  and paid-up accounts were not checked, so lesson 4 doesn't give them.
- **Prescribed debt and collectors.** Whether the National Credit Act stops collectors from
  collecting or reviving prescribed debt (reported as section 126B) was not checked against the
  amended Act.
- **Stokvel rules after 2014.** The Banks Act designation in `facts.md` is from 2014; we could not
  confirm it hasn't been amended, or which self-regulatory bodies the Reserve Bank currently
  approves.
- **Insurance rights source.** The 31-day cooling-off and 15-day grace period come from an FSCA
  consumer guide published in 2020, not the current Policyholder Protection Rules text.
- **FSCA phone number.** FSCA pages list several different call-centre numbers, so `facts.md`
  links to its search page instead.
- **Bank fees and low-cost accounts.** No official comparison of bank fees was found; lesson 2
  explains how to compare instead of giving figures.
- **Ombud changes.** The FAIS Ombud is expected to merge into the National Financial Ombud Scheme
  at some point; contact details may change.

## Contributing

Figures change, especially when the repo rate moves. If one is out of date,
[report it](https://github.com/things-they-dont-teach-you/south-african-money/issues/new?template=fix-lesson.yml)
with the official link, or send a pull request. To build or change courses, start with the
[staff-room](https://github.com/things-they-dont-teach-you/staff-room).
