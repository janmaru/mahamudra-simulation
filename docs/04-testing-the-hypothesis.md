# 4. Testing the Hypothesis

> **Status:** draft — full text, awaiting review.

## Abstract

An investigation that cannot be settled by observation is not an
investigation. This chapter catalogues every experiment proposed to detect a
simulation, states its assumptions and its expected signal, reviews whatever
data exist, and asks what would count as decisive evidence in either direction.

## Question under investigation

Is there any feasible observation whose outcome would materially change our
credence?

## 4.1 What would count as evidence

Chapter 3 ended with the physics case empty and the probabilistic case
capped in the low tens of percent. The only way out of that position, in
either direction, is an observation. This section sets the bar an observation
must clear.

**Three criteria.** An experiment counts as a test of the simulation
hypothesis if its predicted result is (1) *entailed* by some specific version
of the hypothesis, (2) *not* entailed by standard physics, and (3) observable
with instruments that exist or could be built. Criterion 1 rules out "it
would explain X" — the version must say *what* it predicts and *how much*.
Criterion 2 rules out the entire physics case of chapter 2.1, where every
clue was also a prediction of ordinary physics. Criterion 3 rules out
thought experiments.

**The asymmetry.** A positive result — an artefact found, a seam observed —
would be grade-A evidence and would move credence enormously, because
nothing in standard physics could produce it. A negative result moves
credence very little, because it eliminates only the specific version tested,
and the space of versions is unbounded (chapter 3.2). Tests of the simulation
hypothesis are therefore worth running for their upside, not for their
power to disconfirm.

**The hiding problem.** Any test can be met with "the simulators would hide
it". This reply is always available and always costs the defender the same
thing: it makes the hypothesis unfalsifiable and hands the argument to
chapter 3.2. A test is still worth running if there is a plausible version
of the hypothesis on which the simulators *do not* hide the artefact —
because they are not watching (by-product simulations, chapter 1.2.3),
because hiding is expensive, or because they do not care. The tests below
are all of this kind.

**A caution from computer science.** Gueron and Seifert showed that a program
running inside a virtual machine cannot, in general, determine that it is
doing so if the hypervisor is designed to prevent detection; detection is
possible only when the hypervisor is imperfect or uninterested in hiding
[Gueron & Seifert 2009]. Jonas and Kording applied the methods of
neuroscience to a classical microprocessor running a video game and found
that the methods revealed almost nothing about how the processor actually
worked [Jonas & Kording 2017]. Yampolskiy cites both to make the point that
detecting one's virtual environment is not generally solvable and that the
tools of empirical science may be poorly suited to reverse-engineering a
substrate [Yampolskiy 2022, §3.4]. These results set the expectation: a
*competent and motivated* simulator is undetectable. The tests below bet
on incompetence or indifference.

## 4.2 Proposed tests

### 4.2.1 Lattice anisotropy in ultra-high-energy cosmic rays

**Version tested.** Spacetime is simulated on a regular cubic lattice with
spacing *b*, as in lattice QCD [Beane, Davoudi & Savage 2012].

**Prediction.** Rotational symmetry is broken at scales approaching *b*.
Particles cannot carry momentum above roughly *π/b*, producing a hard cutoff
in the cosmic-ray energy spectrum, and the highest-energy cosmic rays should
arrive preferentially along the lattice axes, producing a characteristic
cubic anisotropy in their arrival directions.

**Data.** The Pierre Auger Observatory and the Telescope Array both observe a
suppression in the spectrum above about 5 × 10¹⁹ eV, consistent with the GZK
mechanism that ordinary physics predicts. Auger's 2017 result shows a
large-scale dipole anisotropy above 8 × 10¹⁸ eV, amplitude about 6.5 %,
pointing away from the Galactic centre and indicating extragalactic sources
[Auger 2017]. That is not a cubic pattern. But neither Auger, the Telescope
Array, nor their joint working group has published an analysis that looks
for the cubic symmetry the lattice version predicts. The data exist; the
specific test has not been run.

**Status.** Proposed; **not directly tested**. Indirectly constrained:
Lorentz-invariance bounds from gamma-ray bursts [Abdo et al. 2009],
[Vasileiou et al. 2013] already exclude a grid coarse enough to produce a
large effect, and Beane and colleagues' own estimate puts the spacing at or
below 10⁻¹² fm if the GZK cutoff is to survive. A dedicated cubic-symmetry
search in the existing Auger and Telescope Array catalogues would be cheap,
would settle the version as stated, and is the most obvious unfinished piece
of work in the field. Even a negative result would not rule out finer,
irregular, or lattice-free simulations.

### 4.2.2 Render-on-demand in quantum measurement

**Version tested.** The simulation computes the definite state of a quantum
system only when the result is about to be *recorded* by something the
simulation treats as an observer, and otherwise propagates a cheaper
description [Campbell et al. 2017].

**Prediction.** Campbell and colleagues propose a family of experiments built
on delayed-choice and quantum-eraser setups, designed so that the
information about which path a particle took is either made available to an
observer or destroyed, under conditions where standard quantum mechanics
predicts identical statistics but a render-on-demand simulation might not —
because the simulation decides what to compute based on whether the
information *will be* observed, not on whether a physical which-path record
exists.

**Data.** The standard delayed-choice quantum eraser [Kim et al. 2000] gives
results exactly as quantum mechanics predicts; it does not test the
render-on-demand version because both readings predict the same outcome for
that setup. The specific variants proposed by Campbell and colleagues were
the subject of a crowdfunding campaign in May–June 2018 that raised about
$237,000; the work was assigned in 2019 to a university laboratory in
California. As of September 2026 no experimental result has been published
in any journal or preprint server, and the project's own site says the
results are still out.

**Status.** Proposed; not yet run in a form that discriminates. The main
difficulty is that the proposal's notion of "observer" is doing work that
standard physics does not recognise, and the experiments must be designed so
that the two readings actually diverge. If a divergence is found it would be
grade-A. If not, the version is eliminated and the defender retreats to a
renderer that keys on physical records rather than observers — which is
indistinguishable from ordinary decoherence.

### 4.2.3 Information-theoretic signatures

**Version tested.** The simulation optimises its data storage, and this
produces measurable regularities in the information content of physical
systems [Vopson 2023].

**Prediction.** Vopson's "second law of infodynamics" holds that the
information entropy of a closed system decreases over time, and he argues
this is what a data-compressing simulation would show. Specific predictions
concern genetic mutations, symmetry in nature, and the behaviour of digital
information.

**Data.** The claimed evidence consists of reinterpretations of existing
data. No independent group has reproduced the claimed regularities. The one
peer-reviewed response argues that the statistical-entropy basis is ill
defined and unsuitable for stating a physical law [Crecraft 2025], and the
author has published a correction acknowledging a weakness in the
cosmological derivation [Vopson 2025].

**Status.** Claimed; not independently confirmed; criticised in print. Grade
E pending replication. Recorded because it is the one recent proposal that claims a
*positive* result, and positive results are what the asymmetry of 4.1 makes
valuable — if they hold.

### 4.2.4 Computational artefacts in fundamental constants

**Version tested.** The simulators used finite-precision arithmetic or
compressed representations, and the values of dimensionless constants carry
the fingerprints — rounding at a particular bit depth, unexpected simple
rational relations, periodicities.

**Prediction.** Dimensionless constants (the fine-structure constant, mass
ratios) should show statistical regularities inconsistent with their being
arbitrary real numbers.

**Data.** No such regularity has been reported in the measured constants,
which are known to between six and twelve significant figures. Numerology
about the fine-structure constant has a long and unproductive history and no
proposed relation has survived improved measurement.

**Status.** Informally run over a century; negative. The version is weak in
any case: a simulator using finite precision would most naturally show it as
a *cutoff* in the precision of physical quantities, which is what 4.2.1
tests, not as patterns in the values.

### 4.2.5 Resource-consumption attacks

**Version tested.** The simulation runs on finite hardware without unbounded
headroom, and sufficiently demanding computation inside it produces
measurable degradation — slowdowns, dropped checks, inconsistencies
[Yampolskiy 2022, §3.1, §3.5].

**Prediction.** Gwern Branwen argues that we can force the simulators to
spend more compute by running expensive computations of our own — dovetailing
through every possible program, brute-forcing open mathematical problems,
launching self-replicating probes — and that by Rice's theorem the simulators
cannot in general optimise away nested layers of abstraction
[Branwen 2012]. Caleb Scharf asks whether building nested simulations of our
own could produce the equivalent of a stack overflow [Scharf 2020]. Murat
Demirbas, in a proposal published on the first of April, suggests a
coordinated attack on the simulation's load balancing: everyone does nothing,
then everyone does something computationally intense simultaneously, and one
looks for dropped consistency checks in the overloaded window
[Demirbas 2019]. Yampolskiy also notes the theoretical ultimate version:
generating an incomputable paradox to force a crash [Yampolskiy 2022, §3.5].

**Data.** Yampolskiy's own inventory of what has been tried without effect
includes bitcoin mining, which by 2022 consumed on the order of a small
country's electricity, and the Large Hadron Collider at its current energies
[Yampolskiy 2022, §5]. Neither produced any observable degradation. He notes
that these may simply not be demanding enough.

**Status.** Informally run; negative at the scales tried. The version is
hard to eliminate because "demanding enough" has no upper bound. It is also
the one class of test that is *dangerous* (4.5): a successful
resource-consumption attack that crashes the simulation is not a result
anyone would be around to publish.

### 4.2.6 Glitch reports

**Version tested.** The simulation is imperfect and its errors are sometimes
noticed by inhabitants.

**Prediction.** Reproducible, independently witnessed events that violate
the laws of physics as they actually operate.

**Data.** Turchin and Yampolskiy surveyed reported "glitches in the matrix"
and found them consistent with known failures of memory, perception and
attention, with no case meeting the standard of reproducibility or
independent witness [Turchin & Yampolskiy 2019]. The paper's inventory of
failed approaches adds that breaking one's routine, travelling somewhere new,
and behaving unethically all fail to produce unexpected observations
[Yampolskiy 2022, §5].

**Status.** Run at scale by the entire human population for its entire
history; negative.

## 4.3 Tests that do not work

Some proposals fail criterion 1 or 2 so completely that they do not belong in
the table above.

**Personal experience.** Déjà vu, the Mandela effect, the sense of narrative
in one's life. No version of the hypothesis predicts these at any particular
rate, and ordinary psychology predicts them at the observed rate.

**Meaning and purpose.** "The universe seems designed for us to understand it"
is not a prediction of the hypothesis (a by-product simulation predicts the
opposite) and is not an observation (it is an attitude toward observations).

**Announcements.** Yampolskiy records that publishing papers arguing we are
simulated does not terminate the simulation, that praying and other attempts
at magical communication produce no measurable effect, and that saying "I no
longer consent to being in a simulation" has been tried [Yampolskiy 2022,
§5]. He reads the absence of a response as weak evidence that we are not
being watched, or not by anyone who cares what we say. Chapter 5.2 treats
these as social-engineering attempts; as *tests* they fail because the
hypothesis makes no prediction about whether the simulators respond.

**Consensus attacks.** Robert Lanza's biocentrism holds that observers
collectively fix the structure of reality, and Yampolskiy notes that if the
simulation were "client-authoritative" — if the state were determined by a
majority of local observer models — changing enough minds might change the
world [Yampolskiy 2022, §3.5]. There is no version of this that makes a
prediction differing from ordinary physics; the psychological literature
cited in its support is about how beliefs shape perception, not how they
shape particles.

## 4.4 Data review

| Test | Version | Status | Result | Moves credence? |
|------|---------|--------|--------|-----------------|
| Lattice anisotropy | Cubic lattice, *b* ≳ 10⁻²⁷ m | Proposed; data exist; not analysed | Coarse grid excluded indirectly | Little either way; cheap to run |
| Render-on-demand | Observer-keyed lazy evaluation | Proposed; funded 2018; unpublished | — | Would move a great deal if positive |
| Infodynamics | Data-compressing simulator | Claimed positive | Not reproduced; criticised | Not until replicated |
| Constant artefacts | Finite-precision arithmetic | Informal, century-long | Negative | Little |
| Resource attacks | Finite hardware, no headroom | Informal (mining, LHC) | Negative at scales tried | Little; unbounded retreat |
| Glitch reports | Imperfect simulation | Population-scale, historical | Negative | Little |

No test has produced a positive result that survives scrutiny. The one
worked-out physical prediction has never been directly checked, despite a
decade of suitable data. Every negative result eliminates a specific version
and leaves the generic hypothesis where chapter 3 left it.

## 4.5 The termination risk

Preston Greene argues that experiments designed to detect a simulation carry a
risk the experimenter cannot discount: if we are in a simulation run for a
purpose, discovering that fact — or making the simulation more expensive to
run — might cause the simulators to terminate it. His conclusion is stark:
"Unless it is exceedingly improbable that an experiment would result in our
destruction, it is not rational to run the experiment" [Greene 2020].
Yampolskiy accepts the concern, notes that both Bostrom and he himself have
taken "some risk with the whole of humanity" by publishing, and observes
that the simulation may already have been shut down and restarted with
patches and wiped memories without our being able to tell
[Yampolskiy 2022, §3.7]. Turchin and colleagues catalogue simulation types by
their termination risk [Turchin et al. 2019].

The expected-value analysis has three inputs: the probability that we are
simulated (low tens of percent at most, after chapter 3); the probability
that a given experiment would trigger termination *conditional* on being
simulated (unknown, but the empirical record of 4.2 and 4.3 — including
publication of the hypothesis itself — suggests low for anything tried so
far); and the value of the information gained (large if positive, small if
negative, per 4.1). For observational tests like 4.2.1 and 4.2.2 the
termination probability is negligible: they consume no unusual resources and
announce nothing the simulators do not already know. For resource-consumption
attacks (4.2.5) at scales far beyond anything tried, Greene's caution
applies with full force, and the fact that the attack's *success condition*
is our own destruction makes it hard to justify under any decision theory.

## 4.6 A research programme

Ranked by expected information gain divided by cost and risk:

1. **Render-on-demand experiments (4.2.2).** Cheap, safe, and the only
   proposal with a plausible route to a grade-A positive. The prerequisite is
   a design on which the simulation reading and standard quantum mechanics
   actually diverge, and that design does not yet exist in a form both sides
   accept. The most useful next step is theoretical, not experimental.
2. **A dedicated cubic-symmetry search in existing cosmic-ray catalogues
   (4.2.1).** The data are public, the analysis is a modest project, and it
   would convert the field's one physical prediction from "untested" to
   "tested". Continued Lorentz-violation searches, funded for other reasons,
   tighten the indirect constraint at no marginal cost.
3. **Independent replication of infodynamics claims (4.2.3).** Cheap; either
   kills the one live positive claim or promotes it. Worth doing precisely
   because the claim is currently ignored rather than refuted.
4. **Theoretical work on what "cheap" means (chapter 3.7).** Not an
   experiment, but the coarseness objection is the most powerful lever on the
   credence and it turns on an unanalysed notion of simulation cost.
5. **Resource-consumption attacks (4.2.5).** Last, and only at scales where
   Greene's condition is met. As a by-product of computation we would do
   anyway (large-scale physics, AI training), monitoring for degradation is
   free; as a deliberate programme it is not justified.

Yampolskiy's own "actionable plan" is to treat every novel quantum-mechanics
experiment as an attempt to hack the simulation, on the grounds that the
smallest scales are where an exploitable substrate would show, and to expect
AI-designed experiments to accelerate the search [Yampolskiy 2022, §3.6].
This book agrees with the priority on quantum mechanics and dissents on the
framing: the experiments are worth running as physics, and if they show
something the simulation reading predicts and physics does not, that is when
the word "hack" becomes appropriate.

## Predictions

- **If a specific, imperfect simulation:** one of the tests in 4.2 eventually
  returns a reproducible positive. *None has.*
- **If a competent, motivated simulation:** no test ever returns a positive,
  by construction (Gueron & Seifert). *Consistent with observation.*
- **If not simulated:** no test ever returns a positive. *Consistent with
  observation.*

The last two predictions are identical, which is the problem in one line.

## Evidence for

- None from any test to date.

## Evidence against

- Every specific version that has been checked, directly or indirectly, has
  come back negative or constrained, and the historical record of
  glitch-hunting is a population-scale negative.
- The weight of this is small, per the asymmetry of 4.1, but it is not zero:
  the cumulative elimination of *natural* versions — the ones a simulator
  would build if they built the obvious thing — leaves only versions
  designed, or lucky enough, to be invisible. The lattice version is the
  exception: it is natural, it is checkable, and it is simply unchecked.

## Provisional verdict

There is one feasible observation whose outcome would materially change the
credence: a positive result from a render-on-demand experiment, if one can be
designed on which the two readings diverge. No other proposed test has that
property. Negative results, including all those obtained so far, move the
credence only slightly, because the hypothesis retreats to untested versions.

The hypothesis is therefore **falsifiable in its specific forms and
unfalsifiable in its generic form**, and the accumulated negatives push it
toward the generic form — which is exactly the form chapter 3.2 identified
as scientifically empty. Credence should move a little further downward from
chapter 3, mostly on the grounds that the "natural" versions are gone.

Confidence: high on the inventory and the asymmetry. The status of the
render-on-demand experiments and of the cosmic-ray anisotropy searches was
verified against the literature in September 2026 and should be rechecked
periodically.

## Open threads

- Can a render-on-demand experiment be designed on which the simulation
  reading and decoherence actually predict different statistics? If not,
  the one route to grade-A evidence closes.
- Is there any version of the hypothesis that predicts a *positive*
  observation and has not yet been tested? The chapter found none beyond
  those listed, but the search was not exhaustive.
- Greene's condition is stated for our own experiments. Does it also bear
  on computation we do for other reasons — training large AI systems, say —
  and if so, does anyone have standing to stop it?

## Sources

- [Beane, Davoudi & Savage 2012], [Auger 2017], [Abdo et al. 2009],
  [Vasileiou et al. 2013], [Campbell et al. 2017], [Kim et al. 2000],
  [Vopson 2023], [Crecraft 2025], [Vopson 2025], [Branwen 2012],
  [Scharf 2020], [Demirbas 2019],
  [Turchin & Yampolskiy 2019], [Turchin et al. 2019], [Greene 2020],
  [Gueron & Seifert 2009], [Jonas & Kording 2017], [Yampolskiy 2022].
