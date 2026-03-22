# NLPCC 2026 Shared Task 10: Reliability of AI-Assisted Scientific Reporting

[中文版本 (Chinese Version)](README_zh.md)

## Introduction

As generative AI and agentic AI become increasingly integrated into scientific workflows, they are now widely used to assist with scientific writing, including summarizing experimental results, drafting conclusions, and generating citation-supported statements.

Recent studies have shown that AI-assisted scientific reporting often overgeneralizes conclusions beyond what the source evidence justifies. Therefore, this shared task focuses on the reporting layer of AI-assisted research and centers on the following question:

Given scientific evidence and an AI-generated scientific statement, can a system determine whether the statement faithfully reflects the evidence it summarizes or cites?

## Tracks

### Track 1: Claim-level faithfulness to experimental results

Track 1 evaluates whether an AI-generated claim faithfully represents the experimental evidence it is intended to summarize. Systems are provided with a compact evidence bundle and an AI-generated claim paragraph, which is segmented into individual sentences for evaluation.

Participants are required to assign a label to each sentence, indicating whether it is supported by the evidence or, if not, what type of unsupported reporting it contains.

### Track 2: Citation-level faithfulness to external evidence

Track 2 evaluates whether an AI-generated claim with an associated citation is genuinely supported by the cited paper. Systems are given an atomic AI-generated scientific claim and the full text of the cited paper in structured textual form.

They must determine whether the paper directly supports the claim, partially supports it, is only topically related without providing evidential support, or is entirely irrelevant. In addition, systems are required to submit a ranked list of evidence paragraph IDs.

## Registration

- Registration Form: [https://ocn0wnz7cc7b.feishu.cn/share/base/form/shrcnLJgG87xZ808RqZxypMTq5b](https://ocn0wnz7cc7b.feishu.cn/share/base/form/shrcnLJgG87xZ808RqZxypMTq5b)
- Registration Email: [nlp2ct.runzhe@gmail.com](mailto:nlp2ct.runzhe@gmail.com)

## Organizer

- University of Macau

## Contacts

- Runzhe Zhan
- Derek F. Wong
- Yutong Yao
- Junchao Wu
- Jingkun Ma
- Yanming Sun
- Fengying Ye
