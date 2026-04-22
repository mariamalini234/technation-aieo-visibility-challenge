# AIEO Visibility Challenge: Bridging the Canadian AI Information Gap
This repository contains the research, data analysis, and architectural proposal developed for the AIEO Visibility Challenge hosted by TECHNATION Canada. 
Our team, AI Accuracy, investigated how Generative AI models represent Canadian organizations, programs, and services to identify gaps in visibility and accuracy.

## Project Overview: As Generative AI becomes the primary gateway for information, unequal visibility within these systems shapes what Canadians see, trust, and access. 
Our project explores AI visibility patterns across different Canadian provinces and sectors to propose interventions that improve representation, accuracy, and fairness.

## Key Issues Addressed: 
- Gaps in Coverage: AI responses often show significant gaps in representing local Canadian organizations.
- Misinformation: Incomplete or outdated data can skew public understanding of essential services.
- Inequity: Low visibility impacts public access to jobs, funding, and Indigenous-led programs.

## Methodology (Stage 1): We conducted a large-scale comparative analysis across four major LLMS.
- LLMs: Gemini, ChatGPT, Perplexity, and Claude.
- Dataset: 100 questions across 7 categories (Health, Education, Indigenous Programs, Workforce, etc.).
- Scope: Evaluated responses across all 13 Provinces and Territories.
- Scale: Collected and verified 26,000 total responses against official provincial and federal sources.
- Controls: Ensured clean data by testing paid vs. unpaid subscriptions and incognito vs. logged-in modes to eliminate user-interaction bias.

## Key Findings:
- Regional Disparity: Models performed strongest in Newfoundland and Labrador and New Brunswick (~75-80% accuracy), but dropped significantly in Ontario and Manitoba (below 50%).
- Sector Imbalance: Healthcare services generally had the highest visibility (peaking at 72% in PEI), while sectors like Innovation & Industry in Ontario saw as low as 19% visibility.
- Model Reliability: Perplexity and Claude generally achieved the highest performance in Atlantic provinces, while Gemini showed more consistent but lower overall performance.
- Indigenous Representation: Representation was most prominent in Nova Scotia (55%) but notably lower in Saskatchewan (23%) and PEI (24%).

## Proposed Solution (Stage 2): We proposed "The Sovereign AI Framework" a 3-Tiered Solution to overcome AI inaccuracies and ensure equitable access to information.
- Policy Suggestion: Prioritize redirecting government-related queries to official federal/provincial websites to ensure the latest information.
- Architectural Framework: A custom layered LLM architecture trained on verified government datasets to deliver structured, transparent responses.
- Custom Tool: A specialized interface that uses fine-tuned Stage 1 data and live retrieval from verified provincial/federal sources.

## Impact: 
- Reduces Misinformation: Prioritizes verified sources over outdated training data.
- Ensure Fair Visibility: Prevents the deprioritization of small NGOs and Indigenous programs.
- Strengthens Digital Equity: Enhances public trust and supports equal access to services across all of Canada