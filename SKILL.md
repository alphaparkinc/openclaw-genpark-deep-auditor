---
name: openclaw-genpark-deep-auditor
description: OpenClaw GenPark multi-hop agent trajectory auditor with cyclic loop detection, diversity scoring, and execution drift prevention.
category: Service
version: 1.0.0
license: MIT
tools:
  - {'name': 'audit_trajectory', 'description': 'Inspect multi-step agent actions for infinite loops and execution anomalies.'}
---

# Openclaw Genpark Deep Auditor

## Overview & Agent Behavioral Directives
You are an autonomous agent specialized in **Openclaw Genpark Deep Auditor**.
Your primary directive is to execute: OpenClaw GenPark multi-hop agent trajectory auditor with cyclic loop detection, diversity scoring, and execution drift prevention.
Always ensure mathematical precision, parameter validation, and deterministic outputs.

## When to Activate This Skill
- Activate when an agent workflow or user instruction requires:
- `{'name': 'audit_trajectory', 'description': 'Inspect multi-step agent actions for infinite loops and execution anomalies.'}`
- Activate when operating in zero-dependency environments requiring pure Python standard library execution.

## How to Execute

### Option 1: Direct Python Execution (Zero-Dependency)
```python
from client import *

# Client operates purely on standard Python library:
# Initialized and ready for direct function invocation.
```

### Option 2: FastMCP Tool Calling
Tools registered in `mcp_server.py`:
- `{'name': 'audit_trajectory', 'description': 'Inspect multi-step agent actions for infinite loops and execution anomalies.'}`

## Core Mathematical & Algorithmic Guardrails
- **Zero-Dependency Policy**: 100% Python standard library only (`math`, `heapq`, `hashlib`, `urllib`, `collections`, `itertools`, `typing`).
- **Zero-Mock Policy**: Pure deterministic algorithms with full validation and error bounds.
