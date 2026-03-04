---
layout: ../layouts/LandingLayout.astro
title: "* north star"
lede: 
  - "Guaranteeing good results with AI systems is hard. "
  - "We'll help you get there."
#with non-deterministic systems?
tagline:
  - "Define \"good\""
  - "Set criteria"
  - "Measure against them"
  - "Optimize"
intro: 
  - "To build trust in your AI product you need guarantees that the outcomes your system produces will consistently meet user needs. "
  - "We'll help you define your success criteria based on your business goals and let you start evaluating improvements (the effects of your changes?) across the stack against them."

# risks: If you think about it too late you risk the success criteria being set implicitly instead of by deliberate (business?) decision.

what_we_do:
  - "We work hands-on with a small number of companies to map their AI systems, find where
    the gap between business intent and engineering measurement lives, and close it."

# i think we need to be more business-friendly with our whole talk, evals might not be as commonly understood 
services:
  - name: Align business and engineering
    desc: An interface to establish shared success criteria in product language that engineering can instrument against.
  - name: Evaluate results  #pipeline design
    desc: How do you know you're getting better? We'll build or improve an existing evaluation pipeline driven by business-defined success criteria.
  - name: AI engineering stack optimization
    desc: Once success criteria exist, spend, retrieval quality, or model choice become optimizable against something real.
  - name: Understand what you're monitoring #Observability and monitoring review
    desc: What signals are being captured and are they the right ones? We want to connect the right traces to outcomes.
#  - name: Map architecture & data flow  #mapping
#  desc: You deserve a clear understanding of the stack and where business intent drops out of the loop. #i don't think deserve is the right way to phrase this though
# if you wanna keep this it should be merged with 'stack optimization' i think

# TODO (Nando): this whole section comes off as really cocky to me, I want to make sure
# the tone is different before we publish anything
# 
# these are more notes than final, trying to outline what should come here
why_us:
  - name: We need you more than you need us
    desc: We are working on a product and doing user research. We are offering help for insight into your AI stack in return. 
    # - "Because we're building tooling in this space, you get direct attention from the people who care about this problem most — and direct input into what gets built."
  - name: We have built production AI apps and understand the pain
    desc: We all know the thrill of vibe coding. We've all considered if others might find our product just as useful as we do. But how do we make sure it works before we get it to them? 

contact: hello@biene.club
---
