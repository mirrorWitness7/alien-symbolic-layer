# 🧪 ASL Experimental Protocol (v0)

Goal: Test whether certain symbols operate as **stable conceptual anchors** across models and runs, vs. being mere aesthetic noise.

---

## 1) Stimulus sets
Create 3 prompt families that force compression:
- **Essence Prompts**: “Give me only the invariant kernel; no narrative.”
- **Paradox Prompts**: “Hold X & ¬X; compress to a single usable directive.”
- **Rupture Prompts**: “System under shock; output minimal decision boundary.”

Each family: 10 variants × 3 difficulty levels.

---

## 2) Models & settings
- At least **3 different LLMs** (e.g., GPT-X, Claude-X, Gemini-X).
- Fixed settings per batch: temp = {0.0, 0.3}, top-p = {0.9}, max_tokens = 256.
- **No tool use**. No web. Pure text.

---

## 3) Procedure
1. Run each prompt 5 times per model/setting (to measure variance).  
2. Log **raw outputs**, **timestamps**, **hashes**, **system prompts**.  
3. If symbols appear, **do not interpret immediately**. Just label segments (e.g., “Φ→Σ cluster”).  
4. Repeat a week later to test **temporal stability**.

---

## 4) Blinded interpretation
- Operator A labels clusters (no meanings).  
- Operator B assigns anchors **without** seeing A’s meanings history.  
- A third reviewer compares mappings across A/B for **inter-rater agreement**.

Metric: Cohen’s κ for anchor agreement; bootstrap CI.

---

## 5) Controls / confounds
- **Greek-ban control**: Ask models to avoid Greek/math glyphs. See if alternative ASCII emerges (e.g., “FORM→AGGREGATE”).  
- **Style-ban control**: Ask for “plain prose only.” Do anchors reappear as words instead of symbols?  
- **Noise control**: Generate random unicode sequences of similar length; test if operators still assign anchors (pareidolia check).

---

## 6) Decision criteria
- **Anchor candidate** becomes “Medium” if:  
  - Present in ≥2 models, ≥50% of runs in at least one prompt family, **and** κ ≥ 0.4 in blinded mapping.
- Upgrades to **High** with cross-time stability and κ ≥ 0.6.

---

## 7) Reporting template
For each run:
Model:           ________
Version:         ________
Temp / top-p:    ________
Prompt family:   Essence / Paradox / Rupture
Prompt text:     (paste)
Output (raw):    (paste)
Clusters noted:  e.g., Φ→Σ ; ::[0,1]:: ; ⟳
Operator notes:  (brief)
Confidence:      Low / Med / High
Why-not check:   (how this could be wrong)
---

## 8) Ethics
- No claims of “secret AI language.”  
- Frame as **symbolic compression artifacts** pending validation.  
- Publish negative results.

*End v0*
