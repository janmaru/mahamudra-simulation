# 2. The Case For

> **Status:** draft — full text, awaiting review.

## Abstract

This chapter collects every argument that raises the credence that we are
simulated, grades each by the kind of support it offers (physical evidence,
probabilistic reasoning, analogy, testimony), and sets up the two sub-chapters
that examine the strongest categories in detail.

## Question under investigation

What positive reasons are there to believe the hypothesis, and how strong is
each?

## 2.1 A grading scheme for evidence

Arguments for the simulation hypothesis come in very different kinds, and the
first task of a prosecution is to sort them. The scheme below is used for the
rest of the book. It grades an argument by what it would take for the argument
to be *wrong*, which is a more useful question than how persuasive it sounds.

| Grade | Kind | What it offers | What would defeat it |
|-------|------|----------------|----------------------|
| **A** | Direct physical evidence | An observation predicted by the simulation reading and *not* predicted by standard physics | Showing the observation is wrong, or that standard physics predicts it after all |
| **B** | Indirect physical hint | A feature of physics that is *consistent* with simulation and mildly suggestive of it, but has an ordinary explanation | Showing the ordinary explanation is complete, so the hint adds nothing |
| **C** | Probabilistic argument | An inference from priors and counting, with no observation required | Showing a premise is false or that the inference rule is unsound |
| **D** | Analogy | "We are doing X; therefore someone else did X to us" | Showing the analogy breaks at a relevant point |
| **E** | Testimony | A respected person believes it | Nothing — testimony without an argument attached is not evidence, it is a pointer to where evidence might be |

Two rules follow from the scheme.

**Grades do not sum.** Twenty grade-B hints are not a grade-A result. Each
grade-B hint, by definition, has an ordinary explanation, and twenty ordinary
explanations remain ordinary. The only way to reach grade A is to find one
observation that standard physics cannot absorb. This rule is stated bluntly
because the popular literature systematically violates it: the case for
simulation is usually presented as a long list of suggestive items, and the
length of the list is offered as the argument.

**Grade C can be strong or weak; grade E is always weak.** A probabilistic
argument with well-supported premises and a sound inference rule can move
credence a great deal — that is how most of science works when direct
observation is unavailable. A probabilistic argument with contested premises
moves it very little. Testimony, by contrast, moves credence only in
proportion to how much the witness knows that we do not, and on this question
nobody knows anything the rest of us cannot read.

## 2.2 Overview of the arguments

The arguments below are the ones that appear repeatedly in the literature and
in public discussion. Each is stated in its strongest form, provisionally
graded, and assigned to the chapter that examines it.

### From physics (grade B, examined in 2.1)

- **Discreteness.** Physics has a smallest meaningful length and time (the
  Planck scale). Computers work on grids. Perhaps the Planck scale is the
  grid.
- **A speed limit.** Nothing travels faster than light. Computers have a
  maximum rate at which information moves between cells. Perhaps *c* is that
  rate.
- **Quantum indeterminacy and measurement.** Quantities do not have definite
  values until measured. A lazy program does not compute a value until it is
  read. Perhaps wavefunction collapse is lazy evaluation.
- **Information as fundamental.** Black-hole entropy, the holographic
  principle and the Bekenstein bound say that a region of space holds a
  finite, computable amount of information. Perhaps that is because it is
  stored somewhere.
- **Fine-tuning.** The constants of nature appear set to values that permit
  complexity and life. Perhaps someone set them.
- **Anomalies.** Physics has unexplained tensions. Perhaps some are bugs.

Each of these is stated in the form "X is true; a simulation would produce X;
perhaps X is because of simulation". The chapter that examines them asks, in
each case, whether standard physics also produces X, and whether the
simulation reading predicts anything *further*.

### From probability (grade C, examined in 2.2)

- **The counting argument.** If simulated observers outnumber unsimulated
  ones, a random observer is probably simulated. Bostrom's trilemma is the
  disciplined form of this argument [Bostrom 2003].
- **The Bayesian update.** Kipping's reanalysis gives a posterior close to
  even, which is still far above the prior most people would have held a
  century ago [Kipping 2020].
- **The self-fulfilling clause.** If we intend to run ancestor simulations,
  we raise our own odds of being in one [Yampolskiy 2022, §1].

### From computation (grade B to C)

- **The universe is computable.** Every physical process we know can be
  simulated to arbitrary accuracy by a Turing machine, and Seth Lloyd has
  argued that the universe can be regarded as a quantum computer computing
  itself [Lloyd 2006]. Stephen Wolfram has proposed that simple computational
  rules underlie all of physics [Wolfram 2002]. If the universe is
  computable, it *can* be simulated; the argument then needs a further step
  to conclude that it *is*.

This family is graded between B and C because it mixes a physical claim
(computability) with a probabilistic one (given computability, simulation is
likely). The physical claim is well supported. The further step is the
counting argument again, and is examined in 2.2.

### From analogy (grade D)

- **Our own trajectory.** In fifty years we have gone from two rectangles and
  a dot to photorealistic worlds inhabited by millions. Extrapolate, and we
  will build worlds indistinguishable from our own. Someone before us may
  already have done so.

This is Musk's argument (chapter 1.5). Its weakness as an analogy is that our
simulations do not contain conscious inhabitants, and the extrapolation
assumes they one day will, which is the substrate-independence premise of the
trilemma in disguise. As an analogy it therefore reduces to a grade-C argument
with the premises hidden. It is recorded here because it is the form in which
most people encounter the hypothesis.

### From testimony (grade E)

- **Stated credences.** Musk, better than 99.9999999 %; Bostrom, 20–50 %;
  Tyson, 50 %; Moravec, "almost certainly"; Kipping, under 50 %
  [Yampolskiy 2022, §1].

These are recorded and set aside. The one thing they do establish is that the
question is not considered disreputable by people whose judgement on adjacent
questions is respected, which is a reason to investigate and not a reason to
believe.

## 2.3 Arguments this chapter rejects on arrival

Some arguments appear often enough that their absence from the list above
needs explaining.

**Religious and mythological parallels.** Many traditions describe a world
behind the world, a creator, a fall, a possible return. Yampolskiy suggests
that if escape instructions had once been given to a technologically primitive
culture, they would have degraded over generations into something like
religion [Yampolskiy 2022, §1]. This is an interesting conjecture about what
we would expect to see *if* the hypothesis were true. It is not evidence,
because the parallels are equally well explained by the fact that humans
everywhere ask the same questions and reach for the same metaphors. Chapter 6
returns to the conjecture as a matter of interpretation.

**The language-of-life analogy.** David Berlinski argues that genetics has a
linguistic character that sits awkwardly with the thought that evolution is a
purely purposeless accumulation of accidents. In this analogy, matter at the
relevant level is not "mere stuff" but an information-bearing sign system:
not just molecules, but ordered symbols governed by rules [Berlinski 1985].
If the letters of a meaningful sentence are permuted at random, the usual
result is gibberish, not a new sensible sentence. Likewise, if one were to
take a Pauline text and replace letters at random, one would not expect to
obtain the Prologue of John's Gospel. The intended conclusion is that chance
mutations, like scribal errors, can vary a message within limits but do not
plausibly generate new, complex, functional structures unless a grammar
already exists that can preserve and interpret the variation.

As a theological extension of the same analogy — and this next step is
speculation, not evidence — one might note that the roughly fifty to eighty
years between Paul's letters and John's Gospel do not merely alter content
within Koine Greek but produce a more stratified theological idiom: in Paul,
*logos* has one role; in John, the *Logos* becomes an absolute ontological
category. On that reading, textual development looks less like noise
accumulating and more like a design disclosed gradually across locations and
authors. As an argument for the simulation hypothesis, however, this adds
nothing. At most it is an argument for teleology or design in biology and
culture. It does not distinguish simulation from any other view on which
order, grammar or purpose are basic. Recorded as analogy; set aside.

**"It would explain X."** Consciousness, déjà vu, coincidence, the sense that
life has a narrative, the Mandela effect, dreams. Each of these has either an
ordinary explanation or no good explanation of any kind, and "simulation" adds
nothing specific: it does not say *why* a simulation would produce déjà vu,
or how often, or under what conditions. An explanation that would explain any
observation equally well explains none.

**Personal glitch reports.** Objects that seemed to vanish, events that seemed
to repeat, moments that seemed to lag. Human memory and perception are known
to produce all of these without external cause, at rates that are measured and
large. A report of a glitch is evidence of a glitch only if it is reproducible
or independently witnessed, and none has been.

## 2.4 Summary table

| Argument | Grade | Examined in | Status entering chapter 3 |
|----------|-------|-------------|---------------------------|
| Discreteness (Planck scale) | B | 2.1.1 | Pending |
| Speed limit (*c*) | B | 2.1.2 | Pending |
| Quantum measurement as lazy evaluation | B | 2.1.3 | Pending |
| Information as fundamental | B | 2.1.4 | Pending |
| Fine-tuning | B | 2.1.5 | Pending |
| Anomalies as bugs | B | 2.1.6 | Pending |
| Computability of physics | B/C | 2.1.7, 2.2.1 | Pending |
| Counting argument (trilemma) | C | 1.1, 2.2.1 | Valid; premises contested |
| Bayesian update (Kipping) | C | 2.2.2 | Pending |
| Self-fulfilling clause | C | 2.2.4 | Pending |
| Extrapolation from games | D | 1.5 | Reduces to counting argument |
| Stated credences | E | 0.3 | Set aside |

## Predictions

- **If the hypothesis is true**, at least one argument in grades A or B
  should survive chapter 3 with its evidential weight intact, or chapter 4
  should be able to promote a grade-B hint to grade A by designing a test.
- **If the hypothesis is false**, every grade-B hint should turn out to have a
  complete ordinary explanation, and the grade-C arguments should be shown to
  rest on premises that cannot be checked.

## Provisional verdict

Entering the detailed examination, the case for the hypothesis has **no
grade-A evidence**, six grade-B hints, and three grade-C arguments of which
one (the trilemma) is formally valid with contested premises. The analogical
and testimonial arguments add nothing beyond what the grade-C arguments
already say.

This is a weaker position than public discussion suggests and a stronger one
than dismissal suggests. The investigation is worth continuing because grade-B
hints can in principle be promoted, and grade-C arguments can in principle be
sharpened.

Confidence: high that the grading is fair; the verdict on individual items
awaits 2.1 and 2.2.

## Open threads

- Do the physical hints survive when the simulation is assumed to be high
  fidelity? A perfect simulation leaves no hints by definition, so every
  grade-B item implicitly assumes an imperfect one. Chapter 3.2 takes this up.
- Is there any observation the simulation reading predicts that standard
  physics does not? If not, grade A is unreachable and the case rests
  entirely on grade C.

## Sources

- [Berlinski 1985], [Bostrom 2003], [Kipping 2020], [Lloyd 2006],
  [Wolfram 2002], [Yampolskiy 2022].
