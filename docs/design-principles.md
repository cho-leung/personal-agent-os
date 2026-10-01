# Design Principles

This document describes the core principles behind Personal Agent OS.

The goal is not to create fully autonomous agents.

The goal is to explore how humans and AI agents can collaborate reliably
over long periods of time.

------------------------------------------------------------------------

# 1. Context != State

Conversation context is temporary.

A chat history may contain useful information, but it should not be
treated as the complete project state.

Important state should be explicitly represented through:

-   documents;
-   artifacts;
-   records;
-   summaries;
-   structured information.

A project should survive changes in conversation or agent instances.

------------------------------------------------------------------------

# 2. Conversation != Memory

A conversation is an interaction.

Memory is accumulated knowledge that can be reused.

Reliable long-term workflows require converting important information
from temporary conversations into durable records.

------------------------------------------------------------------------

# 3. Agent != Identity

An agent represents a role in a workflow.

Examples:

-   researcher;
-   reviewer;
-   learning assistant;
-   operations assistant.

The role can continue even when a specific agent instance changes.

------------------------------------------------------------------------

# 4. Prompt != Knowledge

A prompt defines instructions and behavior.

Knowledge comes from:

-   previous work;
-   artifacts;
-   evidence;
-   validated information;
-   accumulated experience.

A better prompt alone cannot replace preserved knowledge.

------------------------------------------------------------------------

# 5. Ready != Authorized

An agent being technically capable of performing an action does not mean
the action should automatically happen.

Important actions may require:

-   human review;
-   explicit approval;
-   clear ownership.

------------------------------------------------------------------------

# 6. Execution != Commitment

Generating a plan, preparing a draft, or identifying an opportunity does
not mean an external action has happened.

Examples:

-   drafted != sent;
-   proposed != approved;
-   discovered != validated;
-   computed != proven.

------------------------------------------------------------------------

# 7. Agent Change != Project Reset

Long-running projects should not depend on a single agent instance.

A healthy workflow should allow:

old agent → export state → transfer knowledge → new agent → continue
work

The canonical object is the project state, not the individual chat.

------------------------------------------------------------------------

# 8. Human-in-the-loop

AI agents can assist with:

-   exploration;
-   organization;
-   drafting;
-   analysis.

Humans remain responsible for:

-   goals;
-   important decisions;
-   authorization;
-   final judgment.

------------------------------------------------------------------------

# 9. State Before Scale

Adding more agents does not automatically improve a system.

Reliable workflows require:

-   clear roles;
-   explicit states;
-   boundaries;
-   evaluation;
-   feedback loops.

The purpose of architecture is not complexity, but maintainability.

------------------------------------------------------------------------

# Summary

Personal Agent OS explores one question:

How can humans build reliable long-term collaboration systems with AI
agents?

The focus is not replacing human thinking.

The focus is designing better structures for human-AI collaboration.
