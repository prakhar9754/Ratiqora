# Ratiqora — Problem Statement

## 1. Project Overview

**Ratiqora: AI Legal Trainer for Law Students** is an educational AI application designed to help Indian law students strengthen their Constitutional Law case-analysis and legal-reasoning skills.

## 2. Problem Statement

Law students may understand legal principles and read court judgments but still struggle to apply their knowledge to unfamiliar cases. Common challenges include identifying the decisive legal issues, distinguishing material facts from irrelevant information, constructing logically supported arguments, considering counterarguments(opposite side), and connecting conclusions to authoritative legal sources.

Traditional study methods and AI-based learning tools may provide explanations or model answers without necessarily showing whether students can independently apply their knowledge to new legal problems.

Ratiqora will investigate whether an LLM-based system combined with retrieval-augmented generation (RAG), source-grounded feedback, and a structured assessment rubric can support more accurate legal reasoning and measurable improvement on unfamiliar Constitutional Law cases.

## 3. Research Question

Can source-grounded, rubric-based feedback from an LLM + RAG system improve the quality of legal reasoning feedback compared with a baseline LLM tutor, and can practice with this system improve learners' performance on unfamiliar cases?

## 4. Target Users

- Undergraduate law students studying Indian Constitutional Law.
- Law students preparing for examinations, internships, and case-analysis exercises.
- Junior legal learners seeking structured practice in legal reasoning.

## 5. Proposed Solution

Ratiqora will allow learners to practise analysing historical court judgments and case problems. Learners will identify legal issues, distinguish material facts, develop arguments, and submit reasoned answers before reviewing reference material.

The system will retrieve relevant passages from a carefully selected and organised collection of publicly available legal documents(curated) and use them to support feedback. A structured rubric will assess the learner's reasoning, while source references will help learners verify the feedback.

## 6. Research Objectives

1. Build a carefully selected and organised collection of publicly available legal documents, appropriately licensed corpus(Collection of documents or data) of relevant Indian Constitutional Law judgments.
2. Develop a reliable retrieval and source-grounded feedback pipeline.
3. Evaluate retrieval quality, citation(formally) support, unsupported claims, and rubric-based feedback quality.
4. Compare the proposed system with a baseline LLM tutor(basic starting).
5. Where feasible, investigate whether learners improve on unfamiliar cases after practice.

## 7. Proposed Research Contribution

The proposed contribution is a transparent, reproducible evaluation framework for source-grounded legal-reasoning practice, including assessment of feedback quality and transfer to unfamiliar cases.

This contribution is a research hypothesis and will be refined according to competitor analysis, dataset feasibility, expert review, and experimental results.

## 8. Scope and Limitations

The initial scope is Indian Constitutional Law and case analysis. The first version will focus on educational practice rather than providing legal advice, predicting court outcomes, or replacing qualified legal professionals.