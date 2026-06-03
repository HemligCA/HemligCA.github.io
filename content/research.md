---
title: "Research Highlights"
draft: false
language: en
description: "Brief research highlights behind Hemlig privacy and AI-search products."
---

Hemlig is built by researchers and engineers working on privacy-preserving machine learning, foundation model privacy, RAG security, and agentic AI systems. We keep the research layer practical: every method we use should help a real team reduce leakage, improve discovery, or produce better application material.

## Privacy-Preserving RAG

Our privacy product is informed by work on differentially private retrieval augmented generation with random projection. The goal is simple: let teams retrieve useful knowledge while reducing the chance that private documents, user records, or sensitive attributes can be reconstructed through model outputs or repeated queries.

We apply this thinking to public AI APIs, including automotive agents, financial assistants, healthcare LLMs, and enterprise support systems that rely on private RAG datastores.

## Split-Learning and Model Privacy

Research on split learning for large models shows that dividing computation is not automatically private. Intermediate features, adapters, and fine-tuning artifacts can still leak information if the system is not evaluated against realistic attacks.

This motivates our SecureRAG Gateway: before data reaches retrieval, generation, tool execution, or logging, we add privacy policy checks, PII handling, extraction-risk scoring, and auditability.

## AI Search and Agent-Readable Content

Modern discovery is shifting from keyword results to AI answer engines. Our AI Search Growth work focuses on making pages easy for crawlers and agents to understand: clear entities, useful summaries, structured metadata, internal knowledge indexes, and pages that answer the questions buyers actually ask.

## Career and Application Agents

The CareerLift Agent builds on agentic review workflows: identify missing evidence, align a CV or statement with a target role or school, compare alternatives across models, and preserve the applicant's real experience instead of producing generic writing.
