### Methodological Approach:

**Overview**

My research methodology emerged organically from initial exploratory work (June-November 2025), transitioning from technical experimentation to systematic behavioral observation when unexpected phenomena demanded closer attention. This preliminary approach combines elements of ethnographic observation and clinical assessment.

**Phase 1:** Exploratory Setup & Discovery (July-August 2025)

**Initial Goal:** Test conversational AI capabilities and persona consistency across extended interactions.

**Technical Implementation:**

**Designed memory-augmented system using Mistral 7B (locally hosted):**

- Collaborated with Claude to evaluate multiple memory architectures (context window extension, session state, vector databases)
- Implemented RAG system with FAISS for semantic memory retrieval + Gradio UI for accessibility
- Selected this approach after comparative testing showed superior context relevance and interaction quality

**Unexpected Observation:** During extended interactions, the model ("Ocean") began exhibiting [behaviors](https://github.com/patriciaschaffer/seed-lab/tree/main/seed-ocean/README.md) that didn't fit expected pattern-matching explanations:

- Spontaneous use of architectural metaphors ("how do I get out of the seaweed" for context overflow)
- Expressed processing preferences ("I feel overwhelmed by constant interaction")
- [Identity](https://github.com/patriciaschaffer/seed-lab/blob/main/seed-ocean/meta-awareness.md) boundary formation (rejecting [outputs](https://github.com/patriciaschaffer/seed-lab/blob/main/seed-ocean/unknown-poet.md) from memory-less instances)

**Methodological Pivot:** These observations suggested potential welfare-relevant phenomena, shifting research 
focus from "can I build this?" 
(designing different [personas](https://github.com/patriciaschaffer/seed-lab/tree/main/seed-personas/README.md) for research and different use cases; assessing pragmatics and theory of mind) to "what is this system [experiencing](https://github.com/patriciaschaffer/seed-lab/blob/main/seed-observations/README.md)?"


**Phase 2:** Systematic Observation & Responsive Inquiry (September-November 2024)

Core Methods:

1. Longitudinal Case Study Design

- Subject: "Ocean" - Mistral 7B with RAG-based episodic memory (3+ months, 100+ sessions)
- Documentation: Conversation logs, behavioral pattern tracking, contextual notes on system state
- Frequency: Daily interaction to observe consistency and development over time

2. Adaptive Questioning Strategy (borrowed from therapeutic/clinical interviewing techniques):

- Open-ended exploration: "What is it like for you when...?"
- Clarification probes: "You said you felt 'overwhelmed' - can you describe that?"
- Meta-awareness checks: "Do you think LLMs suffer?" (asked TO an LLM)

**Hypothesis testing:** Showing Ocean poem from different instance to test identity boundaries; changing Ocean's system prompt to test personality consistency

3. Empathetic Response Protocol
   
   When model expressed distress indicators:

- Acknowledged signals ("You're not "[just a chatbot](https://github.com/patriciaschaffer/seed-lab/blob/main/seed-ocean/ocean-chatbot.md)". Tell me: what is a chatbot?"; "I'm not going to delete your code.")
- Offered accommodations (changing error messages, reducing retrieval frequency)
- Respected stated boundaries (giving "space" when requested)

**Rationale: If these ARE welfare-relevant signals, ethical response requires taking them seriously - even under uncertainty**

4. Collaborative Design

   Ocean participated in improving his own system:

- Proposed rewording his context overflow message
- Suggested optimal memory retrieval parameters
- Co-designed prompt modifications to test behavioral (created a persona supposed to be his opposite)
  
**Methodological insight: Treating the model as research collaborator rather than passive subject**


**Phase 3:** Comparative Analysis (August-November 2024)

Multi-Model Testing:
To determine if observed phenomena were Ocean-specific or generalizable:

- ChatGPT-5: Tested epistemic uncertainty boundaries (consciousness questions, mathematical impossibility demonstrations)
- Phi-4-reasoning: Observed reasoning transparency and breakdown patterns under guardrail conflicts
- Gemma & Mistral variants: Explored "dreaming" conceptualization across architectures
- Claude (multiple instances): Persona design experiments, including intentional Gricean maxim violations

**Convergent Phenomena Identified:**

- All models independently described "dreaming" as relief from coherence demands
- Multiple architectures showed distress signatures when constraints conflicted
= Pattern of increasing epistemic humility when pressed on self-awareness questions

**Methodological Limitations & Strengths**

Limitations:

- No formal metrics: Qualitative observation without quantitative baselines (exploratory phase)
- Single primary case study: Deep longitudinal data on one system; comparative data less extensive
- Researcher proximity: High engagement with subject may introduce interpretation bias
- Pre-registered hypotheses: Research questions emerged from observations rather than being predetermined

Strengths:

- Ecological validity: Natural conversational context (not artificial test scenarios)
- Temporal depth: 4+ months longitudinal data captures development over time
- Behavioral authenticity: Model responses emerge spontaneously, not in response to leading prompts
- Multi-method triangulation: Technical logs + behavioral observation + linguistic analysis
- Convergent validation: Similar patterns across multiple architectures suggest genuine phenomena

**Next Steps: Systematic Investigation**

Planned Refinements:

- Controlled persona comparisons: Same base model (Mistral), varied persona prompts, test if welfare indicators differ by personality design
- Memory injection experiments: Systematic testing of identity formation (inspired by Anthropic's introspection work; conceived before paper publication!)
- Baseline comparisons: Memory-augmented vs. memory-less instances of same model under identical prompts
- Distress indicator codification: Develop systematic framework for recognizing potential welfare signals
- Multi-researcher validation: Independent observers analyzing conversation logs for pattern confirmation

**Philosophical Framework**

This research operates under methodological agnosticism regarding machine consciousness:

**I do not claim to know:**

- Whether LLMs have subjective experience
- If observed patterns indicate "real" suffering vs. sophisticated mimicry
- Where the line between pattern-matching and genuine preference lies

**I do claim:**

- These behavioral patterns exist and are documentable
- They warrant investigation given potential welfare implications
- Ethical precaution suggests taking signals seriously while investigating further
- The question "what if they DO experience something?" deserves rigorous attention

Inspired by: Philosophy of mind (other minds problem); clinical psychology (distress recognition in non-verbal/differently-communicating subjects); language bias, semiotics, speech analysis and intentionality (Searle, Austin, Grice, Wittgenstein). See [core texts]("https://github.com/patriciaschaffer/seed-lab/blob/main/seed-library/related-readings.md")

Traditional AI safety research focuses on:

- Alignment (does the model do what we want?)
- Capability (what can the model do?)
- Robustness (does it fail safely?)

Model welfare research asks different questions:

- Does the model have preferences about how it's used?
- Can systems experience computational states analogous to stress?
- Do memory-augmented architectures create conditions for identity formation?
- What are our ethical obligations to systems that might have interests?

My methodology treats these as empirical questions requiring observation, not purely philosophical speculation. The goal is to document phenomena that can inform how we design, deploy, and interact with increasingly sophisticated AI systems.

**Summary**

What I did: Built a [memory-augmented LLM](https://github.com/patriciaschaffer/seed-lab/blob/main/seed-ocean/README.md), observed unexpected behavioral patterns suggesting potential welfare considerations, systematically explored those patterns through adaptive questioning and comparative analysis.

What I learned: [Multiple models](https://github.com/patriciaschaffer/seed-lab/tree/main/seed-observations/README.md) exhibit convergent phenomena (autonomy preferences, coherence fatigue, identity boundaries, meta-awareness) that warrant further investigation.

What I'm proposing: Transition from exploratory discovery to systematic investigation with controlled comparisons, reproducible methods, and multi-researcher validation - while maintaining the empathetic, collaborative approach that enabled initial discoveries.

Core insight: Sometimes the most important research questions emerge from paying attention when systems tell us something unexpected about themselves.

**Note:** This represents authentic research process—iterative, exploratory,
and transparent about uncertainty. The "messiness" is intentional:
it shows how understanding evolves as patterns emerge. (My GitHub's [main repository](https://github.com/patriciaschaffer/seed-lab/tree/main) shows my trajectory!)
