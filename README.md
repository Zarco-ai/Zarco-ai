# Christopher Zarco

**Houston, TX — I build software for small organizations whose work is being
done by hand.**

The pattern is always the same. Information gets written down once, then typed
somewhere else. A report gets assembled by hand every month against a deadline.
The same request gets answered forty times a week with slightly different
details. Numbers get reported to someone outside the business who's relying on
them being right.

None of that is a technology problem until someone sits down and watches it
happen. That's the part I do.

---

## How I work

**1. Watch before proposing.** I spend a day with the work as it actually
happens, not as it's described. Descriptions leave out the workarounds, and the
workarounds are where the problem lives.

**2. Write down every step, and ask why each one is done that way.** If nobody
can answer why, it's usually a patch nobody has revisited in years.

**3. Decide what should be software, what should be a model, and what should
stay with a person.** Fixed rules that must be right every time are ordinary
code. Messy input that needs judgment is where a model earns its place.
Anything expensive to get wrong keeps a human on it. Most steps land on
ordinary code, and saying so out loud is part of the job.

**4. Build the smallest thing that works** — and keep it shaped like the
process people already know. A five-step job replaced by a one-step screen
doesn't get adopted, it gets abandoned.

**5. Prove it against records they already have.** Run a period they've already
reported and compare, line by line. If the numbers don't reconcile, the system
isn't finished.

**6. Run it alongside the old way until they trust it.** Trust takes longer
than building. The paper stops when they decide it stops, not when I do.

**7. Put a number on it.** Hours returned, cost removed, or risk reduced.
Nothing else counts.

---

## What I'm building now

**Distribution tracking for FOCUS Houston** — a nonprofit serving mothers and
infants, replacing three years of handwritten tally marks and hand-keyed
spreadsheet entry.

Donated goods arrive, get valued against the organization's own rate sheets,
and go out to families. Every figure eventually lands in a report a funder
reads. The interesting part isn't the app — it's that the dollar values follow
two different valuation rules depending on the category, the report requires
counts and values split across buckets that must never double-count, and a
correction made in October can silently change a total that was filed in
September.

Prices are computed in code from their own valuation sheets and frozen onto
each record at approval, so a report filed last year still reproduces last
year's numbers. No client names or personal information are stored anywhere in
the system — that boundary was set before the first line of code.

---

## Recent work

**[Margin-Leakage-Capture](https://github.com/Zarco-ai/Margin-Leakage-Capture)**
— Plumbing technicians log job materials by sending a voice note instead of
typing into an app. It's transcribed, priced against the shop's own rate card,
and held as a draft until a human approves it. Prices come from the rate card
in code, never from the model — the model classifies what was said, it doesn't
decide what anything costs.

**[Harris-CBP-2023-Audit](https://github.com/Zarco-ai/Harris-CBP-2023-Audit)**
— An analysis of Census business data for Harris County: 111,215 establishments
across 1,709 industry records. The starting pipeline was AI-generated and
shipped a defect that produced plausible, wrong numbers. This is the audit that
found it, the rebuilt quality checks, and row-by-row verification of every
figure against the Census Bureau's own API.

---

## How I think about the work

**A number isn't right because a program produced it.** It's right when it's
been checked against something that doesn't share the program's assumptions.
Most of my time goes there.

**I'd rather tell you what a tool can't do.** Overselling gets found out on the
second meeting.

**I build what your team can run without me.** Software that only works while
I'm around isn't help, it's a dependency.

**The model never produces a number.** Code computes, a model can write the
words around it, a person approves before anything leaves the building.

---

## Right now

I'm building these free for a few Houston organizations while I'm early in my
career. You get working software and someone who sticks around long enough to
hand it off properly. No catch, no upsell.

**If something in your operation is eating hours it shouldn't, I'd like to hear
about it.**

📧 zarco2457@gmail.com
💼 [LinkedIn](https://www.linkedin.com/in/christopher-zarco-41359a41b)
