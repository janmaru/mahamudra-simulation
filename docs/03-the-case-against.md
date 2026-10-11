# 3. The Case Against

> **Status:** draft — full text, awaiting review.

## Abstract

The strongest objections to the simulation hypothesis are not that it is
absurd but that it is either unaffordable, unfalsifiable, or empty. This
chapter gives each objection its best form, checks it against the arguments of
chapter 2, and records which arguments survive.

## Question under investigation

Which arguments from chapter 2 are defeated, weakened or untouched by the
objections?

## How the objections are tested

Each objection is put through the mirror image of the test applied in chapter
2.1. Is the objection *true* as stated? What is the best *reply* available to
a defender of the hypothesis? And which chapter-2 arguments does it *touch* —
because an objection that defeats the physics hints may leave the
probabilistic argument intact, and vice versa. The results are collected in
the scorecard at the end.

## 3.1 The computational-cost objection

**The objection.** Simulating our universe at the level of its actual physics
is impossibly expensive. The observable universe contains on the order of
10⁸⁰ particles; quantum many-body systems require resources that grow
exponentially with the number of particles; and Ringel and Kovrizhin have
shown that for some such systems the exponential cost cannot be avoided by any
classical algorithm of the standard type [Ringel & Kovrizhin 2017]. A
computer that could simulate the universe would have to be larger than the
universe.

**Is it true?** As a claim about *faithful classical* simulation, yes. As a
claim about simulation in general, no, for three reasons the defender can
give.

*Lazy rendering.* Bostrom's simulator does not compute every particle; it
computes what is observed, at the resolution at which it is observed, and
patches inconsistencies before anyone notices [Bostrom 2003]. The cost is
then set by the observers' bandwidth, not by the universe's particle count.

*A quantum substrate.* A quantum computer simulates quantum systems at
polynomial cost — this was Feynman's original motivation for proposing them.
If the simulators have quantum computers, the exponential barrier does not
apply. Lloyd's picture of the universe as a quantum computer computing itself
is the limiting case [Lloyd 2006].

*Different physics outside.* Wei Dai points out that base reality need not
share our physics and may have vastly greater computational resources than
anything our laws permit [Dai 2004]. The cost of simulating our universe in
*our* units says nothing about the cost in theirs.

**What the objection does establish.** It rules out one type of simulation —
full-resolution, classical, faithful to our quantum mechanics — and it makes
every other type pay a price. Lazy rendering must hide its seams. A quantum
substrate must be built. Different physics outside means the simulators'
world is one we cannot reason about at all, which weakens every argument that
extrapolates from our own trajectory (chapter 1.5, chapter 2.2.4). The cost
objection also bounds *N* in the trilemma: if a mind is expensive to
simulate, a civilisation runs fewer of them, and *f_sim* falls.

**Touches.** Chapter 2.1.7 (complexity results, already recorded as pointing
this way); chapter 2.2.3 (resource budget); the analogy argument of chapter
1.5. Does not touch the counting argument's validity, only its inputs.

**Verdict on the objection.** Sound against faithful classical simulation;
converts into a constraint on type for everything else.

## 3.2 The unfalsifiability objection

**The objection.** Sabine Hossenfelder puts it bluntly: the simulation
hypothesis is pseudoscience, because its proponents have never shown that the
known laws of physics — quantum field theory and general relativity together —
can actually be reproduced by a computer, and because any observation that
seems to contradict the hypothesis can be absorbed by saying the simulators
chose it that way [Hossenfelder 2021]. A hypothesis that forbids nothing
predicts nothing.

**Is it true?** Of the *generic* hypothesis — "we are in some simulation of
some kind for some purpose" — yes, completely. Chapter 2.1 confirmed this
item by item: for every physical clue, the defender's reply was available in
advance, and in the one case where a specific prediction was made (the
lattice anisotropy), the defender could — and, should the test ever be run
and come back negative, would — retreat to a finer lattice or no lattice at
all. Chapter 2.3 recorded the same pattern in the "it would explain X"
arguments. A hypothesis whose every failed prediction is met with a retreat
to a version that did not make the prediction is not being tested.

**The reply.** The defender has one good reply and one bad one.

The bad reply is that many respectable hypotheses are hard to test. That is
true and irrelevant: hard to test is not the same as constructed to evade
testing.

The good reply is that *specific* versions of the hypothesis are falsifiable.
"We are simulated on a cubic lattice with spacing around 10⁻²⁷ m" makes a
prediction about cosmic-ray arrival directions that could be checked against
existing data and has not been [Beane, Davoudi & Savage 2012]; a coarser
lattice is already excluded by Lorentz-invariance tests. "We are lazily
rendered with detectable artefacts at the moment of measurement" is the
target of the experiments in chapter 4. The generic hypothesis is
unfalsifiable in the way "there is a planet somewhere we have not seen" is
unfalsifiable; the specific versions are as falsifiable as "there is a planet
at these coordinates" — and the embarrassment for both sides is that nobody
has pointed the telescope.

**What the objection does establish.** That the generic hypothesis cannot be
*confirmed* by physics, only made more or less probable by argument, and
that the physics case of chapter 2.1 is therefore permanently capped at
grade B. Any movement of credence must come from grade C arguments or from
eliminating specific versions one at a time — which lowers the probability
of the disjunction very slowly, since the space of versions is unbounded.

**Touches.** Every item in chapter 2.1; every "it would explain X" argument.
Does not touch chapter 2.2, whose arguments do not depend on observation.

**Verdict on the objection.** Sound against the generic hypothesis. It does
not refute the hypothesis; it explains why the physics case is empty and will
stay so.

## 3.3 The consciousness objection

**The objection.** The counting argument requires that simulated minds be
conscious and have experiences like ours. This is the substrate-independence
premise (chapter 1.1.2), and it is assumed, not shown. Nobody knows what
consciousness is or what produces it. If it requires something a computer
does not have — a biological substrate, a particular causal structure,
something not yet imagined — then simulated people are not observers,
the count of observers excludes them, and the argument stops.

**Is it true?** The premise is unproven; that much is uncontroversial.
Whether it is *false* is the hard problem of consciousness, which this book
will not solve. Functionalism — the view that mental states are defined by
their functional role and can be realised in any substrate — is the majority
view among philosophers of mind, but a majority view on an open question is
not a result.

**The reply.** The defender has two.

First, the argument needs only that *we* be conscious and that *we* might be
simulated. If substrate independence is true, we might be. If it is false,
the argument fails but so does every other claim that depends on machine
consciousness, and the world becomes a simpler place in several respects.
The objection is therefore a live *uncertainty*, not a *defeat*: it says the
argument's premise has some probability of being false, and that probability
should be folded into the credence.

Second, a *partial* simulation (chapter 1.2.1) does not need substrate
independence: the minds are outside, and only the world is computed. The
consciousness objection does not touch this type. It does touch the counting
argument, because partial simulations do not multiply observers.

**What the objection does establish.** That the credence for horn 3 should be
discounted by the probability that substrate independence is false, and that
that probability is not small. Someone who puts it at one half should halve
their credence from the counting argument.

**Touches.** Chapter 2.2.1 (counting), chapter 2.2.2 (Kipping, whose model
assumes conscious simulations are possible), chapter 1.5 (the games analogy,
which assumes future games will contain conscious players).

**Verdict on the objection.** A real discount, not a refutation.

## 3.4 The "so what" objection

**The objection.** David Chalmers argues that even if we are in a simulation,
the world around us is real: the objects are real digital objects, the causal
structure is real, our knowledge of physics is knowledge of the simulation's
physics and remains valid. The simulation hypothesis, on this view, is not a
sceptical hypothesis at all. It is a metaphysical one, on a par with "the
universe was created by a god" or "the universe is made of information",
and it changes nothing about what we know or how we should live
[Chalmers 2022].

**Is it true?** As a point about *knowledge*, largely yes. A simulated
physicist who discovers a simulated law has discovered a true regularity in
their world. The sceptical reading — "if we are simulated, nothing we know is
true" — is wrong, and Chalmers is right to reject it.

**The reply.** The objection dissolves one question and leaves another
untouched. It dissolves "is anything real?" It does not dissolve "is there an
outside?" — which is the question this book is asking. Yampolskiy's stakes
(chapter 5) do not depend on the world being unreal; they depend on there
being a level above it with more knowledge and more resources. Chalmers'
realism is compatible with that, and he himself takes the hypothesis
seriously enough to assign it a credence of at least a quarter
[Chalmers 2022]. "So what" is an answer to the wrong question.

**What the objection does establish.** That the emotional charge of the
hypothesis — the fear of unreality — is misplaced, and that the practical
consequences are narrower than popular discussion assumes. Chapter 6 builds
on this.

**Touches.** Nothing in chapter 2. It reframes the stakes; it does not bear
on the evidence.

**Verdict on the objection.** Correct, and orthogonal.

## 3.5 The regress objection

**The objection.** If our universe is explained by a simulator, what explains
the simulator? If they too are simulated, the question repeats. Either the
chain is infinite, which explains nothing, or it terminates in a base reality
that is not simulated — in which case the hypothesis has not explained
existence, only relocated it.

**Is it true?** Yes, but it is an objection to the hypothesis as an
*explanation*, not to its *truth*. "There is a level above us" can be true
without explaining why there is anything at all. The regress is a reason not
to adopt the hypothesis in order to answer "why is there a universe?"; it is
not a reason to think the hypothesis false.

**The reply.** Chapter 2.2.3 already established that nesting is finite for
cost reasons, so the chain does terminate. The defender simply agrees that
base reality exists and is unexplained, exactly as it would be if we were in
it.

**Touches.** The fine-tuning argument of chapter 2.1.5, which chapter 2.1
already noted the hypothesis pushes up a level rather than answering.

**Verdict on the objection.** Sound against the hypothesis as an ultimate
explanation; irrelevant to whether it is true.

## 3.6 Parsimony

**The objection.** The hypothesis postulates an entire additional universe,
inhabited by agents with motives, in order to account for a world that
physics already accounts for without them. Occam's razor cuts it.

**Is it true?** Parsimony is a rule for choosing between hypotheses that
explain the *same* data. Applied to the physics hints of chapter 2.1, it is
decisive: each hint has an ordinary explanation, the simulation reading adds
an unobserved universe to reach the same observation, and the ordinary
explanation wins. Chapter 2.1 reached this conclusion item by item without
naming the principle.

**The reply.** Parsimony is the wrong tool against the counting argument.
Bostrom's argument does not say "simulation explains X"; it says "given what
we know about computation and civilisations, most observers are probably
simulated". That is an inference from premises to a conclusion about
frequencies, and it is not made more or less parsimonious by the number of
universes it implies. If the premises are true, the universes are there
whether or not we find them elegant. Parsimony can be applied to the
*premises* — is it simpler to suppose civilisations run simulations or that
they do not? — but there it has no clear verdict.

**Touches.** Every item in chapter 2.1 (decisively); nothing in chapter 2.2.

**Verdict on the objection.** Decisive against the physics case; misapplied
against the probabilistic case.

## 3.7 The coarseness objection

**The objection.** This is the objection chapter 2.2 flagged as the strongest,
and it uses the counting argument's own logic. If simulations are cheap and
numerous, as horn 3 requires, then most of them are *cheap* — low
resolution, short duration, simplified physics — because a civilisation
running many simulations runs mostly inexpensive ones, and the expensive ones
are rare. A randomly chosen simulated observer should therefore expect to
find itself in a coarse world: physics that stops making sense at moderate
scales, a history that does not extend far back, inconsistencies at the
edges. Sean Carroll calls this the "resolution conundrum" [Carroll 2016].

We observe the opposite. Our physics is consistent to the smallest scales we
can probe, around 10⁻¹⁹ m, and out to the largest, around 10²⁶ m; our history
extends 13.8 billion years with no seam; the same laws hold in every
direction and at every epoch we can measure. If we are simulated, we are in
an extraordinarily *expensive* simulation. And the counting argument says
that is exactly where a random observer should *not* expect to be.

**Is it true?** The logic is valid given its premise, which is that the
distribution of simulations is dominated by cheap ones. The observation is
correct.

**The reply.** The defender has three, of decreasing strength.

*Our physics is the cheap one.* We have no idea what "expensive" means to the
simulators. A universe with three spatial dimensions, a handful of forces and
a few dozen constants may be the simplest thing their hardware runs. This is
Wei Dai's point again, and it is unanswerable — which is also its weakness,
since it is available against any observation whatever (chapter 3.2).

*Lazy rendering hides the coarseness.* The simulation is coarse everywhere we
are not looking and fine wherever we look, so it *appears* fine to us at
every scale we test. This is coherent, but it means the observed richness of
physics is not evidence of anything, and the defender has again removed the
hypothesis from the reach of observation.

*Anthropic selection.* Perhaps only high-fidelity simulations produce
observers capable of doing physics. This is weak: the coarseness that would
be detectable to a physicist is far below the level needed for a mind to
form, so coarse simulations should produce plenty of observers who simply
find their physics puzzling.

**What the objection does establish.** That the counting argument, if it
works at all, predicts something about the *kind* of simulation we should
find ourselves in, and the prediction fails. The defender can rescue the
hypothesis only by making the failure invisible (lazy rendering) or by
making "cheap" undefined (alien physics), and both moves cost the argument
its contact with observation. This is the one place in the case against
where the hypothesis' own reasoning generates a check, and the check comes
back negative.

**Touches.** Chapter 2.2.1 (the reference class problem, now with teeth);
chapter 2.2.2 (Kipping's model does not distinguish resolutions and should);
chapter 1.2.2 (the fidelity axis, which this objection turns into evidence).

**Verdict on the objection.** The strongest in the chapter. It does not
refute the hypothesis, but it forces the defender into the unfalsifiable
corner of 3.2, and it should lower the credence for horn 3 by a factor that
depends on how confident one is that cheap simulations dominate — which,
on the hypothesis' own premises, is quite confident.

## 3.8 The coherence objection

**The objection.** Chapter 1 left open whether "outside our universe" means
anything. If the simulators can act on our world — start it, stop it, patch
it, respond to us — then they are causally connected to us, and a natural
definition of "our universe" is the set of everything causally connected to
us. On that definition the simulators are inside, the hypothesis reduces to
"there are powerful agents in our universe we have not detected", and the
distinctive claim about *levels* of reality disappears. Putnam's argument
that a brain in a vat could not even *refer* to the vat is a semantic
version of the same worry [Putnam 1981]; Heylighen has argued along
related lines that a brain in a vat cannot break out because it has no
concepts adequate to the outside [Heylighen 2012].

**Is it true?** It is a real ambiguity, but it is definitional rather than
substantive. "Universe" can mean the causally closed totality or the domain
governed by our laws of physics. On the first meaning the simulators are
inside; on the second they are outside, because the laws that govern them
are not ours. The hypothesis is stated in the second sense, and the second
sense is coherent: a virtual machine is inside the host in the first sense
and outside it in the second, and computer scientists have no trouble with
the distinction.

**The reply.** Fix the definition, as chapter 1.3 did. Putnam's semantic
argument, if it works, shows that the sentence "we are simulated" cannot be
*true* when uttered by a lifelong simulant — but it also cannot be
*meaningfully denied*, and most philosophers have concluded that the argument
shows something about reference rather than about vats.

**Touches.** Nothing in chapter 2 directly. It bears on chapter 5, because
if the outside is conceptually inaccessible then reconnaissance (5.1) and
communication (5.2) are hopeless in principle, not just in practice.

**Verdict on the objection.** Not a defeat. A reminder that the hypothesis
needs its definitions, and that escape may face a conceptual barrier as well
as a physical one.

## 3.9 Scorecard

| Chapter-2 argument | Grade in | Objections that touch it | Outcome | Grade out |
|---|---|---|---|---|
| Discreteness (Planck scale) | B | 3.2, 3.6; prediction untested, coarse grid excluded by Lorentz bounds (2.1.1) | **Defeated** as evidence; the untested prediction passes to ch. 4 | — |
| Speed limit (*c*) | B | 3.6; points the wrong way (2.1.2) | **Defeated** | — |
| Quantum measurement as lazy evaluation | B | 3.2, 3.6 | **Weakened** to "consistent with"; testable versions survive to ch. 4 | B⁻ |
| Information as fundamental | B | 3.6; conflation with digital physics | **Defeated** as evidence for *simulation* | — |
| Fine-tuning | B | 3.5, 3.6 | **Defeated**; hypothesis multiplies the problem | — |
| Anomalies as bugs | B | 3.2, 3.6 | **Defeated** | — |
| Computability of physics | B/C | 3.1 | **Weakened**; establishes possibility, constrains type | C |
| Counting argument (trilemma) | C | 3.3 (discount), 3.7 (negative check) | **Survives, weakened**; valid, premises discounted, own prediction fails | C⁻ |
| Bayesian update (Kipping) | C | 3.3, 3.7 | **Survives, weakened**; near-even result should fall once resolution is modelled | C⁻ |
| Self-fulfilling clause | C | 3.1 (alien physics undermines extrapolation) | **Survives**; a small update | C |
| Extrapolation from games | D | 3.3 | Reduces to counting argument | — |
| Stated credences | E | — | Set aside | — |

## Predictions

- **If the objections are sound**, no chapter-2 argument should retain a
  grade above C, and the physics case should be empty. *Both confirmed by
  the scorecard.*
- **If the hypothesis is nonetheless true**, the surviving grade-C arguments
  should be the ones a simulated civilisation would be able to make — which
  they are, since they require no access to the outside. This is consistent
  with the hypothesis and also with its negation, as expected.

## Provisional verdict

Six of the twelve arguments entering the chapter are defeated outright; all
six are physics hints, and the objections that defeat them — parsimony and
unfalsifiability — are the ordinary tools of science, not special pleading.
The physics case for the hypothesis is **empty** and will remain so unless a
specific version makes a prediction that ordinary physics does not (chapter
4).

The probabilistic case survives, weakened twice: by the consciousness
discount (3.3), which is a genuine uncertainty about a premise, and by the
coarseness objection (3.7), which turns the counting argument's own logic
into a check that fails. The defender can rescue the argument from the
second only by making the simulation unobservable in principle, at which
point the hypothesis is exactly as Hossenfelder describes it.

The "so what", regress and coherence objections are correct and beside the
point: they bear on what the hypothesis *means* and *explains*, not on
whether it is *true*.

Net effect on credence: downward from the "few percent to a few tens of
percent" range of chapter 2.2, with the lower part of that range now better
supported than the upper. A defensible credence after the defence is in the
low tens of percent at most, and a reader who weights the coarseness
objection heavily can defend single digits.

Confidence: high on the scorecard for the physics items; moderate on the
size of the discount for the probabilistic items, which depends on
judgements (about substrate independence, about the distribution of
simulation costs) that the literature has not settled.

## Open threads

- Is there a version of the hypothesis that is both falsifiable and
  affordable? Chapter 4 is the search for one. If none is found, the
  hypothesis is permanently a grade-C matter.
- The coarseness objection assumes cheap simulations dominate. Is there a
  principled argument that they would *not* — for instance, that ethical
  simulators would run only high-fidelity simulations, or that low-fidelity
  ones do not produce observers? Chapter 6 touches the ethical version.
- If the coherence objection is right that the outside is conceptually
  inaccessible, chapter 5 should be read as a study in what *cannot* be
  done.

## Sources

- [Ringel & Kovrizhin 2017], [Bostrom 2003], [Lloyd 2006], [Dai 2004],
  [Hossenfelder 2021], [Beane, Davoudi & Savage 2012], [Chalmers 2022],
  [Carroll 2016], [Putnam 1981], [Heylighen 2012].
