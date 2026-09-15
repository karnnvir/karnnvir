## From Deterministic Bots to Agentic Customer Self-Service

*How I led the transformation of a conversational self-service product from rigid workflows to GenAI-powered customer resolution.*

### The Problem — When Technology Became the Product Constraint

Three years back, my conversational self-service product was held hostage by our technology. Over the years, we had built deterministic, rigid flows that increasingly led to a poor customer experience. Intent identification was particularly weak for complex queries. Customers would often get stuck in circular loops and dead ends, resulting in a high rate of escalation to human agents.

The business was under tremendous pressure to improve resolution rates, but the more I looked at the problem, the clearer it became that this wasn't simply an experience optimization problem. Our deterministic technology was the root cause limiting what the product could do.

### My Proposal — De-risk Before Betting Big

I proposed Generative AI as the solution, but there were understandable concerns from the business about the performance and reliability of a relatively new technology. Rather than asking the organization to make a large bet immediately, I proposed two lower-risk use cases that could prove the value of GenAI from different angles.

The first was a Mexico chatbot focused on a high-volume informational contact category where no order-action APIs were involved. We built a RAG-based solution using our knowledge base and help-center content to resolve informational contacts through GenAI. The result was a 20% improvement in resolution for that category.

The second was an internal agent summary tool. We introduced AI-generated conversation summaries so human agents had the context of the customer's interaction without having to ask repeat questions. This reduced average handle time by roughly 10%.

These two experiments were deliberately different: one demonstrated customer value, the other operational value. Together, they gave us the organizational confidence to make the bigger GenAI bet.

### The Strategic Pivot — When the Platform Became the Problem

With the POCs proven, we moved toward a full platform migration. Our initial direction was to enhance the existing internal deterministic platform to support GenAI flows, while also depending on a parallel internal platform being built by our US counterpart team.

When that platform was taking significant time, I started building GenAI capability independently on our existing deterministic platform. We spent two quarters refining our first flows for the Canada Voicebot, a critical, high-volume channel.

Eventually, we hit a wall. The latency had become unacceptable for a voice experience. I could continue asking the team to optimize the existing architecture, but I no longer believed that was the right product decision.

At the same time, the broader technology strategy had shifted toward a new fully agentic platform, leaving us to solve the immediate problem ourselves.

That forced a strategic decision: continue building, wait for another internal platform, or look outside the organization. I led a structured build-vs-buy analysis, working with our US counterpart team, which was facing a similar challenge. We evaluated third-party options and ultimately selected Sierra.ai as the conversational AI platform.

The key decision wasn't simply to buy technology. It was recognizing when our existing architecture was becoming a bigger constraint than our ability to innovate on top of it.

### The Transformation — From AI That Answers to AI That Acts

We then moved into a disciplined, iterative migration, starting with the highest-impact contact categories and progressively increasing complexity.

We started with Where is my order, followed by cancellations, returns and modifications. But solving these problems required more than a conversational interface. My Walmart team built and externalized the APIs that the platform needed to perform real customer modifications.

That was an important shift in the product. We were no longer building an AI system that could simply answer questions. We were building a system that could understand intent and safely take action on behalf of the customer.

### Building Trust — Evals, Guardrails and Human Oversight

Moving from deterministic flows to GenAI also changed how we defined product quality. Traditional software testing wasn't enough; we needed to evaluate how the AI behaved across a much broader range of possible customer interactions.

We used both LLM-based evaluations and human evaluation. LLM evaluation gave us scale, while human reviewers provided judgment for nuanced and ambiguous cases. Our golden dataset also became a living evaluation system. Whenever we found an issue through testing, monitoring or human review, we added that scenario back into the evaluation set. The test coverage therefore continuously expanded with the product.

Governance started during design, not after launch. We explicitly defined guardrails, human oversight, escalation paths and autonomy limits, particularly around higher-risk actions such as refunds. During development and rollout, we combined the evaluations with strong monitoring, traceability and auditability so we could understand not just whether something went wrong, but what the AI did and when a human should take over.

Every contact category had stage gates as per our Evals Rubric around hallucination, groundedness, resolution improvement and customer satisfaction, with hallucination required to remain below 1% before increasing exposure.

### Scaling the Transformation — A New Way of Working

To move quickly without losing control, I created velocity pods combining product, data science, analytics, engineering and business partners for each market. Each pod had enough autonomy to make decisions and iterate quickly, while maintaining common quality standards and a weekly stakeholder cadence.

This became an important part of the transformation. AI products require a different learning loop: launch in a controlled way, evaluate real behavior, identify failures, improve the system and expand. We were building an operating model for continuously improving AI, not simply launching an AI feature.

### The Impact — Customer, Business and Organization

The customer impact was significant. Voicebot resolution improved 3×, while chatbot resolution increased by 10 percentage points. Customer satisfaction also improved by 0.3 points, demonstrating that we were improving efficiency without sacrificing the experience.

The business impact went beyond resolution. Contacts per order declined by approximately 12.5%, meaning fewer customers needed to contact us in the first place. The cost of an AI-resolved contact was approximately 70% lower than the human-assisted alternative, freeing agents to focus on genuinely complex customer problems.

But the most durable impact was organizational. We developed practical capabilities around AI experimentation, RAG, evaluations, hallucination, groundedness, guardrails, monitoring and AI economics. The velocity-pod model and our approach to AI quality became reusable patterns for future AI initiatives.

### What I Learned — AI Requires a Different Product Discipline

The biggest lesson for me was that AI changes not only what we can build, but how we need to build it. With deterministic products, testing is largely about validating expected behavior. With AI, the range of possible behavior is much broader, so quality has to continuously evolve with the product.

I learned to treat evals, governance and monitoring as part of the product itself, rather than activities around the product. The combination of human judgment, automated evaluation and a continuously expanding set of real-world failure cases gave us a way to improve the system without assuming we could predict every failure upfront.

Most importantly, this experience changed how I think about AI leadership: the goal isn't to make AI autonomous as quickly as possible. It is to earn autonomy progressively through evidence, guardrails and continuous learning.

What This Unlocked

This transformation left the organization confident not just in our ability to deliver customer service through GenAI, but in our capability to apply this thinking across a much broader set of use cases.

For me, this was more than a product transformation. It was a transformation in how we think about AI products—from experimentation, to production, to governed autonomy—and in how an organization builds the muscle to continuously improve them.
