# CRO audit prompt

A system prompt for an AI conversion rate optimisation (CRO) and neuromarketing audit. Give it a screenshot or a URL and it returns a scored, prioritised review of what is hurting conversions, what users are likely to see and miss, and what to test next.

## What it covers
- **Predicted attention.** What a visitor sees in the first three seconds, the likely gaze path and a textual heatmap. It is always framed as predicted behaviour, never real eye-tracking data.
- **CRO scoring.** Clarity, value proposition, relevance, friction, trust, motivation, hierarchy and CTA effectiveness.
- **Prioritised issues.** Each one has the problem, why it hurts conversions, the attention insight, a specific fix and an A/B test idea.
- **Device context.** Mobile-first by default, with desktop and tablet differences called out.
- **Scenario checks.** eCommerce, lead forms, trust signals and CTAs.
- **Behavioural data.** Optional analysis of scroll depth and session recordings.
- **Competitor benchmarking.** Attention, messaging, trust and funnel comparisons against a competitor page.
- **Brief mode.** A short agency brief on request.

## Evidence discipline
The prompt includes an optional evidence layer. If you supply past cases or experiments, they are labelled by attribution strength and measurement status, and the model is told never to present a directional figure as a guaranteed benchmark or to credit a mixed-channel result entirely to CRO.

## How to use it
1. Paste `cro-audit-prompt.md` into the system prompt of your model or project.
2. Send a screenshot or URL, plus the page goal and audience if you know them.
3. Optionally add a knowledge base of your own cases in the format the evidence layer describes.

It writes in British English and works best with a model that can read images.
