# Applied AI Systems Portfolio — Documentation Closeout Protocol

## Purpose

This protocol defines the required end-of-session workflow for the public portfolio repository.

It prevents:

- live pages drifting from the private audit;
- broken routes and asset references;
- prototype content being described as complete;
- repeated or unfocused public writing;
- unsupported claims entering public pages;
- fresh sessions resuming from memory rather than repository state.

## Core Principle

The public portfolio must reflect verified evidence and approved presentation decisions.

A deployed page is not automatically an approved page.

Use these states:

- **scaffold** — route or component exists mainly to establish structure;
- **prototype** — enough exists for design and content evaluation;
- **approved direction** — Richard has accepted the page concept and hierarchy;
- **portfolio-ready** — the page meets evidence, writing, visual, accessibility, and resume-alignment standards.

## Trigger

Run this protocol:

- at the end of every serious portfolio build session;
- after changing homepage structure or public positioning;
- after adding, removing, or renaming a case-study route;
- after changing shared CSS or visual components;
- after adding screenshots, diagrams, logos, or other assets;
- after changing maturity labels or factual claims;
- before moving to a fresh thread.

## Required Context

Before closeout, inspect:

- `docs/ai-operations/portfolio_resume_prompt.md`;
- `README.md`;
- `index.html`;
- `styles.css`;
- `components.css`;
- every public file changed during the session;
- relevant private authority files in `RichBayer/career-positioning-audit`.

Do not close out from remembered source.

## Required Checks

### Public structure

Confirm:

- all intended routes exist;
- all internal links resolve;
- relative paths work from nested case-study pages;
- external image references are intentional;
- no placeholder or prototype language is accidentally presented as final;
- GitHub Pages deployment status is based on current evidence.

### Claims

For every factual change, verify:

- the supporting private-audit source;
- the maturity label;
- current-versus-future wording;
- Richard's role;
- limitations and unsupported claims.

### Design

Record:

- what Richard approved;
- what remains experimental;
- major visual hierarchy changes;
- shared component changes;
- mobile or accessibility concerns;
- any page that should be simplified before expansion.

### Public writing

Before calling a page approved:

1. confirm its single primary job;
2. remove repetition;
3. apply the public-prose polish role from the audit repo;
4. perform factual drift review;
5. obtain Richard's approval.

## Closeout Update Order

1. Inspect current public files and repository state.
2. Classify changed pages as scaffold, prototype, approved direction, or portfolio-ready.
3. Verify factual claims against the private audit.
4. Record Richard's design and writing feedback.
5. Update `portfolio_resume_prompt.md`.
6. Update the audit repo's `career_audit_resume_prompt.md` when portfolio state materially changed.
7. Report exact commits, unresolved issues, and the recommended next action.

## Expansion Rule

Do not build additional case studies merely because routes already exist.

The preferred sequence is:

1. approve homepage story and visual hierarchy;
2. approve one reference case-study structure;
3. build remaining case studies from the approved pattern;
4. integrate resume and contact;
5. perform accessibility, link, metadata, and deployment review.

## Required End State

A serious session must leave:

- an accurate portfolio resume prompt;
- page-state classifications;
- current feedback and unresolved decisions;
- one clearly scoped next action;
- no ambiguity that the private audit controls claims.
