# AI Decisions & Trade-offs

## Why AI Is Needed
Rule-based search and FAQs fail to handle natural language queries
and contextual follow-up questions.

## Options Considered
- Rules-based search
- Zero-shot LLM chatbot
- Fine-tuned LLM
- Retrieval-Augmented Generation (RAG)

## Decision
RAG-based system over approved documentation.

## Rationale
- Keeps answers grounded in source data
- Easier updates without retraining
- Lower hallucination risk

## Trade-offs
- Slight latency increase
- Infrastructure complexity
- Requires document hygiene

