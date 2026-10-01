# Start Here

Welcome to Personal Agent OS.

This document explains how to understand and experiment with the
framework.

## What is Personal Agent OS?

Personal Agent OS is an experimental framework for organizing
long-running AI-assisted workflows.

It is not a replacement for existing AI models.

It is a way to structure collaboration between humans and AI agents.

The main idea:

> Agents can change. State and knowledge should survive.

------------------------------------------------------------------------

# Basic Workflow

A simple workflow contains:

Human Goal

↓

Agent Role

↓

Project State

↓

Artifacts

↓

Next Action

------------------------------------------------------------------------

# Step 1: Define a Project

Create a project state file.

Record:

-   objective;
-   current phase;
-   completed work;
-   blockers;
-   next action.

------------------------------------------------------------------------

# Step 2: Create an Agent Role

An agent should have:

-   a clear mission;
-   boundaries;
-   expected outputs;
-   ownership.

Do not create agents without a specific purpose.

------------------------------------------------------------------------

# Step 3: Preserve State

Important information should not only exist inside conversations.

Save:

-   summaries;
-   decisions;
-   artifacts;
-   evidence;
-   unfinished questions.

------------------------------------------------------------------------

# Step 4: Handoff

When changing agents:

Export the current state.

A new agent should be able to understand:

-   what happened;
-   what remains;
-   what should happen next.

------------------------------------------------------------------------

# Using With ChatGPT

A simple workflow:

1.  Prepare your agent description.
2.  Prepare project state.
3.  Upload relevant files.
4.  Ask the AI to continue from the current state.

Example:

"Read these project files. Continue from the current state. Do not
change objectives without explicit approval."

------------------------------------------------------------------------

# Philosophy

The purpose is not maximum automation.

The purpose is reliable long-term human-AI collaboration.
