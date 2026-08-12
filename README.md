# Runway — financial resilience simulator

**If your income stopped today, how long could you last — and what breaks you first?**

Most people can't answer that. Runway does, in three numbers.

## The problem
A single "runway" figure (how long your savings cover your expenses) is the clearest
measure of financial safety — but working it out means a spreadsheet, and it tells you
nothing about *what would break you*. A lost client, a medical bill, a rent hike: each
shortens your runway differently, and no simple tool shows you which.

## What Runway does
1. **Baseline** — enter income, expenses and savings; get your exact zero-cash date, a
   0–100 resilience score, and one concrete next step.
2. **Stress test** — one click applies a real shock (lose your main income, a $2,000
   emergency, a 30% income drop, a recession combo) and shows the new runway, the new
   zero-cash date, and how many months you just lost.
3. **Extend your runway** — ranked, *quantified* actions ("cut $200/mo → +1.4 months")
   computed by re-running the model, so you see the real payoff of each move.

## Why it's trustworthy
- **Provable privacy:** everything runs in your browser. Open the network tab and
  reload — **zero** requests. There is no server to send anything to.
- **Honest by design:** a positive-income earner with $0 savings reads **Critical**, not
  "Resilient" — the score comes from reserves, not wishful trajectory.

## Impact
Financial resilience for the people who need it most and have it least — gig workers,
freelancers, and farmers with irregular, seasonal income — as a free, private, offline
decision tool, not a bank product that wants their data.

## Tech
Vanilla JavaScript, zero dependencies, works fully offline from a single folder.
Pure, deterministic engine (`runway.js`) with a **104-check** test suite.

## Run it
- **Use it:** open `index.html` in any browser.
- **Test the engine:** `node runway.test.js`

Built during QuantumHacks 2026.
