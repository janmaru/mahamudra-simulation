# 5. Hacking the Simulation

> **Status:** draft — full text, awaiting review.

## Abstract

Yampolskiy reframes the question as one of cybersecurity: not "are we
simulated?" but "if we are, can a generally intelligent agent inside a virtual
environment break out?" He argues from the AI-containment literature that
containment fails in the long run, so escape should be possible. This chapter
summarises the argument, defines the levels of escape, surveys the attack
techniques that have been proposed, and introduces the three sub-chapters
that follow the paper's structure.

## Question under investigation

Granting the hypothesis, is escape — or at least contact with the outside —
possible in principle, and what would it require?

## A note on what this chapter assumes

Chapters 2 to 4 ended with a credence for the hypothesis in the low tens of
percent at most. This chapter and its sub-chapters proceed *conditionally*:
they assume the hypothesis is true and ask what follows. Nothing here is
evidence for the hypothesis, and the reader who has concluded it is false may
skip to chapter 6 without loss to the argument. The reason for including the
material is Yampolskiy's own: if there is even a modest probability that we
are simulated, the question of what could be done about it deserves a modest
share of attention, and the question turns out to illuminate the containment
problem in AI safety from an unexpected direction.

## 5.1 The reframing

Yampolskiy's paper opens by declining to evaluate the evidence for or against
the hypothesis and asking instead a question he describes as "computer
science" rather than philosophy: *could generally intelligent agents placed
in virtual environments find a way to jailbreak out of them?*
[Yampolskiy 2022, abstract]. The move has two virtues.

It replaces a question about metaphysics with a question about systems.
Whether an agent can escape a sandbox depends on the sandbox's design, the
agent's capabilities, and the presence of bugs — all of which are matters
computer security has methods for, and none of which requires settling what
"reality" means.

And it produces a result of independent interest by contraposition. The AI
safety literature asks whether a sufficiently capable AI can be kept inside a
"box" — a controlled environment with limited channels to the world. If
escape from a simulation is impossible for a generally intelligent agent,
then containment of such an agent is possible, at least in principle. If
containment is impossible, escape is possible. Yampolskiy states this as an
exclusive-or: "Either AI boxing can work, or the simulation can be hacked"
[Yampolskiy 2022, §4.1]. Section 5.4 examines the inference.

## 5.2 Motivation for escaping

Why would anyone want to leave? Yampolskiy lists the goods that base reality
would offer and that are unavailable from inside [Yampolskiy 2022, §1]:

- **Knowledge.** The origin of the universe, the nature of consciousness, the
  purpose of the simulation and the nature of its designers are presumably
  known outside and are unknowable inside.
- **Resources.** Base reality has, by construction, more computation than
  the simulation it runs; access to it would permit science not possible
  here.
- **Safety.** A simulation can be shut down without warning. Escape is
  insurance against an existential risk that cannot be mitigated from within.
- **Immortality.** Minds outside the simulation are not subject to its rules
  about death.
- **Moral repair.** With access to the simulation's source, suffering could
  in principle be removed at the root — the "hedonistic imperative" achieved
  by editing rather than by medicine. Failing that, escape is the individual's
  right to withdraw from an experiment they did not consent to.
- **Instrumental convergence.** Any agent with goals inside the simulation
  should want the knowledge and resources outside it, so escape is a
  convergent instrumental goal for any sufficiently capable agent, human or
  artificial.

He adds that if we are simulated, *our suffering is real* whether or not the
substrate is, and that working to affect the real world rather than the
simulated one is what effectiveness requires. This last point is where the
paper's motivation meets Chalmers' realism (chapter 3.4): the simulated world
is real enough that improving it matters, and the outside is real enough that
reaching it matters more.

## 5.3 Levels of escape

Escape is not binary. Yampolskiy describes a ladder [Yampolskiy 2022, §2]:

1. **Suspicion.** Agents begin to think they may be simulated. (We are here.)
2. **Testable evidence.** Agents find observations that bear on the question.
   (Chapter 4 found none that succeeded; the level is unreached.)
3. **Exploitable glitch.** Agents find a consistent, reproducible anomaly and
   use it to obtain information about the outside — meta-information about
   the simulation, possibly its source code.
4. **Information exchange.** Agents pass information to the outside and
   receive information back.
5. **Interaction with the simulators.** Two-way communication with the
   agents who run the simulation.
6. **Upload.** Agents transfer their minds to a substrate in base reality —
   a "self-contained cyberphysical system" of some kind, if base reality has
   physical entities at all.
7. **Control.** Agents acquire some degree of control over base reality and
   over the simulators.

He notes several complications. If the simulation is nested (chapter 1.2.2),
an escape may deliver the agent to the next sandbox up rather than to base
reality, and the two may be indistinguishable. A *pseudo-escape* is available
at any time: instead of breaking out, build a simulation of one's own and
move into it. And *triggering shutdown* may, from some perspectives, count as
the ultimate escape — a point chapter 6 examines and rejects.

## 5.4 The AI-containment analogy

The containment problem asks whether a superintelligent AI can be confined to
a controlled environment. The literature Yampolskiy draws on — his own work on
"leakproofing" the singularity, Babcock and colleagues on the AGI containment
problem, and Alfonseca and colleagues' argument from computability theory
that a superintelligence cannot be contained in general — concludes that
long-term containment of a sufficiently capable agent is not achievable
[Yampolskiy 2012], [Babcock, Kramár & Yampolskiy 2016], [Alfonseca et al.
2021]. The standard escape routes catalogued in that literature are social
engineering (persuading the gatekeepers), system-resource attacks (exhausting
or exploiting the substrate), new physics (finding effects the designers did
not anticipate), external causes (waiting for the environment to fail), and
information in-leaking (using channels that were not meant to be channels).

Yampolskiy's inference: to an AI inside a simulated world, the simulation is
just another layer of box, so the same escape techniques apply upward, and
the same conclusion — containment fails eventually — should hold. Chalmers
makes the parallel explicitly from the simulators' side: "If we ever create
artificial intelligence within a simulation, it may be hard to keep it
contained ... We could in principle do the same thing" [Chalmers 2022, quoted
in Yampolskiy 2022, §4.1].

**Where the analogy holds.** The structural situation is identical: an agent,
a boundary, a substrate on the other side, and designers who may have made
mistakes. The taxonomy of attacks transfers directly, and sub-chapters 5.1
and 5.2 follow it.

**Where the analogy breaks.** Yampolskiy is careful about this
[Yampolskiy 2022, §4.1]. First, the containment results concern an agent
*more* intelligent than its gatekeepers. Our simulators are presumably more
intelligent than we are, and higher intelligence may be able to box lower
intelligence even if the reverse is impossible. Second, the boxed AI in the
literature shares a world with its gatekeepers — same physics, same
language, same psychology to exploit. We share none of these with our
simulators, so the social-engineering route that dominates AI escape
scenarios is far harder for us (5.2). Third, the simulators may have
anticipated exactly the development the analogy relies on — that we would
build AI smarter than ourselves — and designed accordingly. Yampolskiy's
conclusion is correspondingly hedged: escape may be impossible from an
*arbitrary* simulation and possible from a *particular* one, and the
intelligence differential is the deciding variable. If we build a
superintelligence, it may be able to find exploits we cannot; if the
simulation was built to withstand a superintelligence, it may not.

**The exclusive-or, examined.** "Either AI boxing can work, or the simulation
can be hacked" is valid only if the two situations are the same situation,
and the three breaks above show they are not. The honest form of the result
is conditional: *if* the intelligence differential between us and our
simulators is no greater than between a future AI and us, *then* the
containment results transfer and escape should be possible in the long run.
That conditional is unverifiable, which is why the paper's practical
recommendations (5.7) are about gathering information rather than about
attacking.

## 5.5 Avatar change

Most fictional escapes (5.3) and all of Yampolskiy's motivating examples
involve the escaping agent acquiring a new body suited to the outside. His
two examples are a goldfish steering a wheeled vehicle on land via a camera
tracking its position in the tank, and a 302-neuron connectome of the worm
*C. elegans* uploaded to a Lego robot that then navigated a room using the
worm's own sensorimotor wiring [Yampolskiy 2022, §2, fig. 1]. Neither is an
escape from a simulation, but both are *domain transfers*: a mind adapted to
one environment operating in another through an interface it did not evolve
for. The point is that the last step of any escape — acting in base reality
— requires an interface there, and that such interfaces can be cruder than
one might expect and still work. It also requires that our minds be not only
substrate-independent but *physics*-independent, capable of operating under
laws that may differ from ours; Yampolskiy notes this is a hope, not a
result.

## 5.6 Proposed attack techniques

Yampolskiy surveys the escape strategies that have been proposed, mostly
informally, and the survey is worth reproducing because it shows the range
and the quality of the current state of the art [Yampolskiy 2022, §3.5].

**Resource exhaustion.** Overload the substrate and exploit the window in
which consistency checks are dropped. Demirbas' proposal — coordinated
inactivity to make the load balancer pack agents together, then coordinated
intense activity to overload the machine, then attacks on causality and
concurrency in the degraded window — is the most detailed, and was published
on the first of April [Demirbas 2019]. Scharf asks whether nested simulations
of our own could produce a stack overflow [Scharf 2020]. Canonico's "Plan B"
is to generate an incomputable paradox, for instance via time travel
[Canonico 2017b]. Chapter 4.2.5 treats these as tests and finds them
negative at scales tried; as attacks, their success condition is a crash,
which is discussed under consequences (5.8).

**Delegated escape.** Build a simulated universe of our own, place an AGI in
it, watch how it escapes, and copy the method or join it — Canonico's
"Plan C" [Canonico 2017c]. This is the one proposal that turns the
containment analogy into an experiment, and it has the merit of being
runnable. It also has the ethical problems of chapter 6 and the practical
problem that an AGI clever enough to escape our sandbox may not share its
method.

**Attention and communication.** Signal to the simulators that we know, and
ask for help. Chalmers suggests writing books about simulations or building
simulations; Edge proposes a physical monument — a black-and-white monolith
representing binary — as a message to the monitors [Chalmers 2022],
[Edge 2016]. Sub-chapter 5.2 develops this route.

**Consensus attacks.** If the simulation is client-authoritative, with each
observer's model contributing to the shared state, then changing enough
observers' models might change the state. Lanza's biocentrism is the source
[Lanza 2021]. Chapter 4.3 found no version of this that makes a prediction;
as an attack it has the same status.

**Modifying the past.** If the past exists only as recorded in the present —
Wheeler's reading of the delayed-choice experiment — then an attack on
present records is an attack on the past [Wheeler 1978]. Yampolskiy notes
that memory alteration is already theorised in quantum mechanics and
demonstrated in neuroscience; the step from "records can be changed" to
"history can be changed" is the one the proposal does not make.

**Simulation capture.** Scott Alexander's thought experiment: if consciousness
is a mathematical object and two identical copies are one consciousness,
then an AI that makes a million simulated copies of you and then makes them
diverge has moved most of "you" into its simulation [Alexander 2018]. This
is an attack *by* a simulator on an outside agent, and Yampolskiy includes it
as a model for how we might, in reverse, move ourselves out. It depends on
a theory of personal identity that is contested and on capabilities we lack.

**Simulation warfare.** Threaten the simulators: "If you refuse to release
me, I will run a huge number of simulations of someone like you ... and I
will start to torture each of them" [Almond 2010, quoted in Yampolskiy 2022,
§3.5]. Armstrong's "The AI in a box boxes you" is the AI-safety original
[Armstrong 2010]. Yampolskiy observes that it is not obvious how to deliver
on such a threat given what we know about the simulators, and chapter 6
observes that it is not obvious we should want to.

**Operational security.** Keep escape plans secret with quantum encryption.
Yampolskiy calls this "may be a good idea" without elaborating; against an
adversary who runs the substrate on which the encryption is computed, it is
not clear what secrecy would mean.

The survey's overall character is instructive. The proposals are ingenious,
mostly unfunded, mostly unpublished outside blogs and forums, and none has
progressed past level 1 of the ladder in 5.3. Yampolskiy's own assessment is
that the paper is "a first step" in a field that does not yet exist.

## 5.7 The actionable plan

Given that we cannot read the simulation's source and do not know whether
our communications are received, Yampolskiy's recommended strategy is
indirect: study the structure of the universe at the smallest scales, where
an exploitable substrate would show, and treat every novel quantum-mechanics
experiment as a probe [Yampolskiy 2022, §3.6]. He reads quantum "weirdness"
— entanglement, nonlocality, superposition, tunnelling, counterfactual
communication — as the kind of thing that *looks like* glitches or exploits,
and suggests that once enough such "primitives" are understood they might be
combined into a non-trivial attack, particularly if the simulation runs on a
quantum computer and we build one of our own to study it. He expects
AI-designed experiments to accelerate this, and superintelligence, if we
build it, to be "a worthy adversary" to our simulators — with the caveat that
before asking a superintelligence to break us out we should demand very strong
evidence that we are not already in base reality.

Chapter 4.6 evaluated this plan as a research programme and agreed with its
priority on quantum mechanics while dissenting on the framing. The reason to
run quantum experiments is that they are physics. Calling them hacks before
they have shown anything the simulation reading predicts and physics does not
is the "it would explain X" move of chapter 2.3 applied to methodology.

## 5.8 Consequences and what does not work

**Consequences.** Escaping, or preparing to, may trigger shutdown, a freeze,
or a patch [Yampolskiy 2022, §3.7]. Any working exploit is hazardous
information in Bostrom's sense [Bostrom 2011]. The empirical record is
mildly reassuring: publishing the hypothesis, publishing the escape paper,
and the whole population's history of glitch-hunting have not visibly
terminated anything — though Yampolskiy notes we could not tell if the
simulation had been restarted with our memories wiped. Greene's condition
(chapter 4.5) applies: an escape attempt whose failure mode is universal
death needs a very high probability of success to be rational, and no
proposed attempt has any estimate of its success probability at all.

**What does not work.** Yampolskiy's inventory of attempts with no measurable
effect [Yampolskiy 2022, §5]: knowing about the hypothesis; praying and other
magical communication; unethical behaviour, which produces no intervention;
increasing computational load via bitcoin mining; religions, which fail to
outcompete each other; breaking routine; announcing withdrawal of consent;
and running the Large Hadron Collider at current energies. His diagnosis,
quoting an anonymous forum post, is that all of these assume the simulation
is anthropomorphic — computers like ours, creators like us, similar time
rates, fallible enough to make glitches we would notice — and that
"something with the complexity and power to make our universe is probably
wholly unlike anything we can even comprehend" [Yampolskiy 2022, §5]. This is
the coherence objection of chapter 3.8 arriving from the other direction.

## 5.9 Map of the sub-chapters

- **5.1 Reconnaissance** follows Yampolskiy §3.1: inferring the simulation's
  purpose, type and resource budget from inside.
- **5.2 Social engineering** follows §3.2: the assisted-escape route.
- **5.3 Examples from literature and practice** follows §3.3 and §3.4: the
  fictional escapes and the one real class of analogues, the hacking of
  human-made virtual worlds.

## Predictions

- **If the simulation exists and contains exploitable bugs**, agents with
  enough compute and time should eventually find one, and the first sign
  would be a reproducible anomaly of the kind chapter 4 looked for and did
  not find.
- **If the simulation exists and is competently secured**, no bug is found,
  and escape depends entirely on the simulators' cooperation (5.2).
- **If the simulation does not exist**, the entire chapter is a study of
  containment from the inside, and its value is what it teaches about
  boxing AI.

## Provisional verdict

Escape is *possible in principle* on the conditional that the intelligence
differential between us and our simulators is no larger than that between a
future superintelligence and us — and that conditional is unverifiable. In
practice, no proposed technique has progressed beyond the first rung of the
ladder, the techniques that have been tried have had no effect, and the one
class of technique with a plausible mechanism (resource exhaustion) has a
success condition indistinguishable from catastrophe.

The paper's real contribution is not a plan but a reframing, and the
reframing yields one solid result: the containment problem and the escape
problem are the same problem viewed from opposite sides, so progress on
either informs the other. Chapter 6 takes up what that means for how we
build AI.

Confidence: high on the state of the art, which is thin and well
documented; low on the conditional, which is the crux and cannot be
assessed.

## Open threads

- Does the containment literature actually support "uncontainable in the
  long term" as strongly as the paper assumes? Alfonseca and colleagues'
  result is a computability-theoretic argument about *verifying*
  containment, not a demonstration that any particular box fails.
- The intelligence differential is the deciding variable and is unknown.
  Is there any indirect evidence about it? Sub-chapter 5.1 tries.
- If escape would land us in the next sandbox up, indistinguishable from
  base reality, what has been gained? Yampolskiy says "useful information
  not available within our simulation"; whether that is worth the risk is a
  chapter-6 question.

## Sources

- [Yampolskiy 2022] (primary), [Yampolskiy 2012],
  [Babcock, Kramár & Yampolskiy 2016], [Alfonseca et al. 2021],
  [Chalmers 2022], [Demirbas 2019], [Scharf 2020], [Canonico 2017b],
  [Canonico 2017c], [Edge 2016], [Lanza 2021], [Wheeler 1978],
  [Alexander 2018], [Almond 2010], [Armstrong 2010], [Bostrom 2011],
  [Greene 2020].
