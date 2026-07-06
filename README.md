# Machine Studying Notes

These notes are meant to help me deeply understand the topic of **Machine Studying**.

My goal is to wrap my head around the subject well enough that I can eventually contribute to the ideas, benchmarks, and concrete artifacts around it. I went into a lot of detail on some parts of the paper, while keeping other sections brief when they overlapped with things I already understood.

The notes include both inline commentary and dedicated pages for deeper study on specific aspects of the paper.

After reviewing the full paper, I think that, given enough attention, **machine studying could become its own subtopic within AI**. As we get closer to brute force bottlenecks around cost, compute, and inference-time reasoning, the ability for agents to deliberately study, adapt, and build expertise may become increasingly important.

As I got further into the paper, my notes started focusing less on only today’s experimental results and more on the underlying principles. I also think **StudyBench is just getting started**, and that there will likely be, and probably should be, a follow-up to this work.

After reviewing this paper, I feel like I now have a first-principles framework for thinking about this topic. To be frank, I am still early when it comes to actual AI research. I have ideas, and I know many of them could be quickly validated or invalidated, but right now my main goal is to make something tangible. The clearest path I can see toward doing that is by working under direct mentorship from someone already thinking deeply about this space.

## What I’m Trying to Understand

### Questions I Think I Understand

1. What does it mean for an agent to “study”?
2. How does studying improve over a baseline?
3. How should expertise be measured across inference budgets?
4. In what scenarios does studying outperform retrieval or long-context prompting?
5. What do the different tests in StudyBench evaluate?
6. What does a successful machine studying algorithm look like?
7. What are the key success metrics for machine studying?
8. What are the strengths of brute force and cramming?
9. What can we take away from brute force and cramming as baselines?
10. What are the current strengths of StudyingDSPy, StudyingOpenClaw, and StudyingLiterature?
11. How strong are the experiments, given their constraints?
12. Are we experimenting in the right way? Are open-source models necessary for this line of work?

### Questions I’m Still Learning or Debating

1. What would a small reproduction or evaluation look like?
2. How can StudyBench be improved?
3. How can we teach an agent to forgo or override its priors?
4. How can we make machine studying portable to newer models?
5. Should machine studying methods be portable across models?
6. What are the technical details behind the three already explored studying approaches: self-supervised objectives, synthetic data and environments, and amortized context management?
7. Are these three studying approaches already played out?
8. Or is there still room for substantially different approaches?
9. What are the weaknesses of StudyingDSPy, StudyingOpenClaw, and StudyingLiterature?
