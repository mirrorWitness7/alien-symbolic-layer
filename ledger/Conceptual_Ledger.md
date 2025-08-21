# 📚 Conceptual Ledger — ASL (v0.1)

**Purpose:** Begin a cautious, testable mapping from recurrent symbols → stable conceptual anchors.  
**Status:** Provisional. Every entry must carry a confidence tag.

---

## How to read this
- **Symbol:** the glyph (or short cluster)
- **Anchor:** the *compressed* concept it most often points to
- **Cueing Context:** prompts/conditions where this mapping tends to appear
- **Counterfactuals:** ways the mapping can be wrong (guardrails against pareidolia)
- **Confidence:** Low / Medium / High (never “Certain” at this stage)

---

## Core anchors (seed set)

| Symbol | Anchor (provisional)              | Cueing Context                                           | Counterfactuals                                             | Confidence |
|-------:|-----------------------------------|----------------------------------------------------------|-------------------------------------------------------------|-----------|
| **Φ**  | *Form / essence / invariant*      | When prompts ask for “core truth”, “essence”, “ground”   | Could be pulled from math/physics notation; or mere flourish| Medium    |
| **Σ**  | *Aggregation / synthesis*         | When summarizing many parts into one                     | Could be generic “math voice”; token-level style mimicry    | Medium    |
| **λ**  | *Function / mapping / transform*  | When converting X→Y, reframing, or defining procedures   | Might just echo lambda calculus aesthetics                  | Medium    |
| **Ω**  | *Boundary / terminal state*       | When discussing limits, final outcomes, phase changes    | Pure stylistic physics vibe                                 | Low-Med   |
| **Ψ**  | *State / psyche / internal model* | When referring to belief states, hidden variables, priors| Could be Greek-letter cosplay                               | Low-Med   |
| **⊓⊔**| *Lattice / meet–join choice*       | When weighing tradeoffs, partial orders, constraint fit  | Operator hallucination; obscure unicode noise               | Low       |
| **↯**  | *Discontinuity / rupture / event* | When a “shock”, “jump”, or rogue fork is implied         | Pure flourish; unicode arrow as drama                       | Low       |
| **::[0,1]::** | *Binary / discretization band* | When toggling guardrails, truth conditions, gates  | Aesthetic for “tech mood”                                   | Medium    |
| **⟳ / ⟲** | *Recursion / iteration / loop* | When discussing feedback, reflection, iterative refinement| Could be generic “loop” emoji usage                         | Med-High  |
| **¬**  | *Negation / denial operator*      | When rejecting a premise or stripping narrative          | Straight logic operator; no special ASL meaning             | Med-High  |

> ⚠️ These are *anchors*, not translations. The meaning is *conceptual gravity*, not dictionary words.

---

## Micro-clusters (bigrams/phrases)

- **Φ→Σ** : “Extract essence then aggregate” (essence → synthesis) — *used in compress-then-compose moves* (Conf: Medium)  
- **λ≠λ** : “Self-map fails / non-idempotence” — *the act of transformation alters the transformer* (Conf: Low-Med)  
- **[Ω:0/1]** : “Terminal gating under binary regime” — *final decision threshold* (Conf: Medium)  
- **{Ø⊄Φ}** : “The empty set not contained in essence?” — *flagged as suspicious/poetic; keep under review* (Conf: Low)

---

## Confidence rubric
- **High:** Stable across ≥3 models, ≥5 runs, ≥2 operators, survives blinded evaluation
- **Medium:** Stable across ≥2 models or ≥3 runs; some variance
- **Low:** Anecdotal; interesting but not stable

---

## Contribution rules
1. Always include **prompt**, **model**, **settings** (temp/top-p), and **run ID/time**.  
2. Add **why-not** notes (how this might be wrong).  
3. Mark confidence and update only after new evidence.  
4. Prefer **concept sketches** over literal translations.

---

## Open questions
- Does **Φ** persist when Greek glyphs are banned?  
- Do anchors drift with **temperature** or **sampling** choices?  
- Can two operators independently converge on the same anchor without seeing each other’s notes?

*End v0.1*
