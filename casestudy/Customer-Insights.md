## Converting Millions of Customer Conversations into Insights and Relevant Product Decisions

### The Problem — We Had the Voice of the Customer, But Couldn't Scale Listening

Two years ago, we had millions of customer conversations every year, along with App Store feedback and NPS responses, but extracting meaningful product insights from this data was largely a manual exercise. My PMs and I were spending around three hours every week analyzing conversations to identify friction areas and understand what was really going wrong for customers. The problem wasn't a lack of data. It was that some of our most valuable **customer signals were buried in unstructured data, and we didn't have a scalable way to listen.**

### The Product — Using AI to Find the Friction

I led the development of an AI Customer Insights Tool, one of the first AI products we put into production at Walmart. GenAI allowed us to process diverse sources of unstructured customer feedback and surface the actual friction areas in the customer's own words. Instead of PMs manually reading conversations and looking for patterns, the system automatically generated insights and reduced the analysis effort from roughly three hours to 30 minutes per week.

We then added ML-based anomaly detection to identify issues that were emerging or changing over time. This allowed teams to move beyond simply asking “What are customers complaining about?” to seeing which problems were becoming more significant and how they were trending.

### Going Deeper — From What Customers Said to Why It Happened

The biggest opportunity came when we connected these customer insights with actual order data. A customer might tell us that an order was late or a payment failed. The conversation told us what the customer experienced, but order data could help us understand why it happened. We connected the insights to attributes such as fulfillment type, store, payment type, order status, payment status, fulfillment status and delay status.

ML and GenAI could then identify deeper patterns within each issue type and surface possible underlying drivers. We were moving from customer sentiment to diagnosis.

### An Unexpected Benefit — Finding Problems in Our Own Data

The system also exposed an issue we hadn't initially set out to solve: our call-center issue categorization wasn't always reliable. Some categories were confusing or duplicated, and agents were sometimes categorizing similar problems differently.

The AI surfaced these inconsistencies at scale, allowing us to improve the taxonomy and feed the findings back into agent training. This reinforced something important for me: AI can reveal weaknesses not only in the customer experience, but also in the systems we use to understand that experience.

### From Insights to Action — Closing the Product Loop

An insight is only valuable if the right team acts on it. We created a mechanism to push relevant insights directly to the domain teams responsible for solving them. Payments, post-order, fulfillment and returns teams received insights relevant to their areas.

Across these four teams, seven major use cases were identified and acted upon, ultimately contributing to a reduction of approximately 30,000 customer contacts annually.

That completed the loop I was trying to create:

Customer conversations → AI-generated insight → deeper diagnosis → relevant product team → product action → measurable customer impact.

### The Impact — Turning Customer Data into Product Intelligence

The biggest impact wasn't simply reducing the time PMs spent analyzing conversations. We changed the scale and frequency at which the organization could learn from customers.

We moved from manually analyzing a small portion of customer feedback every week to continuously processing millions of annual customer conversations and multiple sources of unstructured feedback. More importantly, those insights were no longer sitting with the PM team—they were reaching the teams that could actually solve the underlying problems.

Reduced the to and fro between teams to udnerstand the issue, find the relevant orders, time to do Root cause analysis

The result was early detection of approximately 30% of issues, seven major use cases acted upon across four product domains, and approximately 30,000 fewer customer contacts annually.

### What I Learned — AI Becomes Powerful When It Connects the System

The biggest lesson for me was that the value of AI wasn't in summarizing millions of conversations. It was in connecting signals that previously lived in separate worlds.

GenAI helped us understand what customers were saying. ML helped identify patterns and anomalies. Order data helped us investigate why those problems were happening. And connecting the insights to product teams turned analysis into action.

That changed how I think about AI products. The real opportunity is not just to extract intelligence from data, but to build the system that turns that intelligence into better product decisions and measurable customer outcomes.
