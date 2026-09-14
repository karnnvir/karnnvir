### Product leadership is ultimately a judgment job.

Frameworks can help structure a problem. Data can help inform a decision. Customer research can reveal what people need. But none of them tells you exactly what to do. That's where product judgment comes in. Over my career, I've learned to think about products beyond features and roadmaps — as **systems of customer problems, business outcomes, technology, people and trade-offs.**

These are the principles I use to navigate them.

---

### Start with the problem, not the request

When someone comes to me with a feature request, my first question is usually not “How do we build it?” It's “What problem are we actually trying to solve?”

A business stakeholder, operations team or customer may describe the solution they want, but there is often a more fundamental problem underneath it. I try to understand who is experiencing it, how significant it is, what they do today and what happens if we don't solve it.

That simple shift — from “What should we build?” to “What are we trying to accomplish?” — often opens up a much better solution space.

---

### Product judgment is knowing what could kill the bet

One of my most important product lessons came from Housing.com. We had identified a genuine customer problem and built a product around it. Adoption started around 25%, improved to about 35% through outreach, but then plateaued against our 60% target. We had invested roughly 24 engineer-months.

Looking back, we had validated the need. We hadn't validated the trust. Customers understood the value but weren't sufficiently comfortable sharing their business data. That changed how I approach discovery.

Today, for any significant product bet, I try to identify the assumption that could kill the entire idea and test that assumption early. **Discovery shouldn't just prove that we're right. It should also try to find where we're wrong.**

---

### Systems thinking drives the Strategy

Working in customer care reinforced this for me. I was accountable for reducing customer contacts, but many of the reasons customers contacted us originated elsewhere — fulfilment, payments, post-order experiences and other parts of the journey. Organizations divide problems into functions. Customers don't.

A customer doesn't think, “This is a fulfillment problem.” They think, “My order hasn't arrived.” So when I'm looking at a product problem, I try to understand the entire journey around it. Where did the problem originate? Where does the customer experience it? Which team controls that part of the journey? And what outcome are we actually trying to change?

Instead of optimizing my own product area, I created a common view of the customer journey and the friction points across domains. We then used a common prioritization approach across those problems rather than allowing every organization to optimize its own backlog. That eventually helped drive a 40% reduction across three years.

The principle I took away: **Don't just optimize your piece of the system when the customer experiences the whole system. **

This also led to our strategy update as:

**AVOID** 
Prevent the customer from needing support.

**AUTOMATE**
Resolve the problem through self-service.

**OPTIMISE**
Make the human interaction better when it is still necessary.


### Platform Thinking

When products operate across markets, teams naturally start asking for variations. Different regulations, languages, payment behavior, business processes. The easy answer seems to Build another version. But the platform answer is to understand What belongs in the common core, and what should be configurable?

My platform principles are:

**Build once, serve many**
Avoid duplicating fundamentally similar capabilities.

**Core vs. extension points**
Keep the core stable while allowing legitimate market-specific variation.

**Configuration over code**
Where differences are expected, make them configurable rather than creating forks.

**Platform health ≠ feature success**
A platform needs its own measures of leverage, adoption and time-to-onboard.

This thinking has shaped how I've approached customer-care platforms across markets and how I think about product organizations as well.

### Data tells me where to look. Customers tell me what matters.

I'm a strong believer in metrics, but I've learned not to confuse measurement with understanding. A dashboard can tell you that something changed. Customer conversations can often tell you why.

That thinking led to a customer-insights capability that combined conversation analysis, anomaly detection and GenAI-generated insights. We eventually expanded coverage from roughly 2% of conversations to essentially all of them and reduced manual analysis from about three hours to thirty minutes. The goal wasn't simply to understand what customers were saying. It was to connect:

Customer signal → insight → owner → action

That's where I believe analytics becomes product thinking. **Statistics start arguments. Specific orders start fixes.**

---

### I try to make decisions reversible

Not all product decisions carry the same risk. If a decision is cheap to reverse, I'm comfortable moving with imperfect information and learning from the result. If it's expensive or difficult to reverse, I want stronger evidence before committing. So instead of always asking “Do we know enough?”, I often ask:

“What's the smallest decision we can make that will teach us something?”

This helps teams keep moving without pretending that uncertainty doesn't exist.

My experience moving from deterministic voicebots toward probablistic Gen AI reinforced this. We didn't have years of benchmark data telling us exactly what would work. We had emerging evidence, experiments, technical constraints and customer signals. When latency reached roughly eight seconds, a 1% experiment showed agent requests increasing from 10% to 20% and customer drops from 2% to 10%. That evidence gave us enough confidence to change the strategy and partner externally rather than continue forcing the internal platform to work.

The principle:

**When certainty isn't available, make the decision smaller, make the learning faster, and make the downside survivable.**

---

### AI has expanded the solution space

AI allows software to interpret unstructured information, generate responses, reason over context and increasingly take actions. But that doesn't mean every problem should be solved with an LLM or an agent.

I now think more explicitly about what the system actually needs to do. Does it need to understand something? Predict? Generate? Calculate? Decide? Take an action? Then I ask what is the simplest reliable mechanism for each part. Sometimes that's AI. Sometimes it's deterministic software. Sometimes it should remain with a human.

**AI expands the solution space. It doesn't remove the need for product judgment.**

---

## My mental model

When I face a difficult product problem, I try to:

Understand the business use case → customer problem → the system → find the evidence → identify the assumptions → explore the solution space → make the smallest sensible bet → learn → adjust.

I don't always get it right.

But I think good product leadership is less about being consistently right and more about getting better at being wrong quickly, cheaply and honestly.
