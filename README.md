# CXAS WhatsApp Demo - furniture agent

&nbsp;

**Visibility:** Confidential *See [go/data-security-policy](https://goto.google.com/data-security-policy) for definitions if you want to change this.*

**Authors:** [Anton McConville](mailto:antonmc@google.com)

**Last major revision:** Oct 20, 2026&nbsp;

# Objective

*Outline a project and scenarios to create a better demo agent for WhatsApp and Instagram. In tandem use this as a collaborative project for testing CICD.*

# Background

*In developing our WhatsApp offering it was difficult to find a relatable demo. When thinking about WhatsApp agents, and after a trip to Europe which showcased a few real life examples, it makes sense to work with a commerce type agent.&nbsp;*

*In this case, there are a few areas to explore:*

* *Developing an agent to ask questions about furniture and display options for buying*  
* *Add items to a cart*  
* *Remember order history*  
* *Possibly develop an order lifecycle demo back end to work with status and respond back to an account over time*  
* *Link to WhatsApp and explore options for passing identity&nbsp;*  
* *Longer term \- upload a floorplan and ask the agent to suggest a set of furniture&nbsp;*

# Requirements

*List the specific requirements that any successful solution would need to meet. Taken together, these should match the summary above. These will be used as criteria to judge if a proposed solution is complete. These should include non-functional goals such as preventing regressions in performance, privacy, and security.*

* Agent should be able to query and answer questions about furniture store data from a database

# Proposal

Create a mock furniture store called ‘Klar’ which sells minimal, Scandi Danish furniture. This furniture store will ( eventually ) be AI powered, where a customer can upload a floor plan and the agent can recommend furniture to suit the layout, and generate a 3d view of how it will look.&nbsp;

The store agent will recognise the customer, be able to answer questions about their order history or status, make orders, make recommendations, ping when a customer has abandoned a cart, notify when new stock is available etc

<img width="674" height="557" alt="furniture-store-architecture" src="https://github.com/user-attachments/assets/8c5c3087-2372-4e49-83e1-6d4ff05269ab" />

# Alternatives considered

*There are several sets of test data available internally to create a store around instead.*# furniture-agent
