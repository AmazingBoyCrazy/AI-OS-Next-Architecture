# 🇺🇸 English Version

## 1. Background: From Tool-Using AI to AI Operating Systems

AI systems are evolving through multiple stages:

- Prompt-based systems
- Tool/Skill invocation systems
- Agent loop systems
- Multi-agent collaborative systems

However, they still share a limitation:

> ❌ Capabilities are treated as isolated tools, not composable system structures.

Thus, AI today behaves more like a function library than an operating system.

------

## 2. Core Idea: The Next Stage of AI Systems

The next-generation AI system is no longer centered around “skills”, but around:

> **Capability Graphs**

and

> **Skill Graphs**

Together, they form a semantic, programmable cognitive operating system.

------

## 3. System Architecture

```
Prompt / Goal
      ↓
Capability Compiler
      ↓
Skill Graph Builder
      ↓
Execution Planner
      ↓
Runtime Executor
      ↓
Tools / APIs / Devices
```

------

## 4. Core Abstractions

### 4.1 Skill (Atomic Capability)

A Skill is a minimal execution unit:

- Device drivers
- Protocol parsing
- File processing
- API invocation

Properties:

- deterministic IO
- composable
- reusable
- embeddable in vector space

------

### 4.2 Skill Graph

Skills are no longer isolated functions, but a graph:

Two types of edges:

- Semantic similarity edges
- Execution dependency edges

Skill Graph =

> Semantic space + execution topology

------

### 4.3 Capability Layer

A Capability is:

> A subgraph of skills + execution policy

Examples:

- Device driver capability
- Serial communication capability
- Software delivery capability
- Testing capability

Capability = Skill Subgraph + Policy

------

## 5. Capability Compiler

Input:

> Natural language goal

Output:

- Capability set
- Skill graph subset
- Execution strategy

Function:

> Compiles semantic intent into executable structures

------

## 6. Execution Planner

Responsible for:

- DAG construction
- skill path planning
- fallback strategies
- multi-agent coordination
- cost/token control

Core idea:

> Converts capability graphs into executable workflows

------

## 7. Runtime Executor

Handles execution:

- Skill invocation
- Tool/API calls
- Agent scheduling
- state management
- error recovery
- dynamic replanning

------

## 8. Key Innovations

### 8.1 From Skill Selection to Capability Generation

Old paradigm:

> Users select skills

New paradigm:

> System generates capabilities

------

### 8.2 From Workflow to Graph-based Cognition

Old systems:

- static pipelines

New systems:

- dynamic graphs
- semantic planning

------

### 8.3 From Deterministic Calls to Semantic Selection

Skill selection evolves from:

- rules
- prompts

to:

> embedding + graph traversal + planning

------

## 9. System-Level Shift

| Traditional AI     | AI OS                   |
| ------------------ | ----------------------- |
| Tool calling       | Capability composition  |
| Prompt engineering | Capability compilation  |
| Agent loop         | Cognitive runtime       |
| Workflow           | Skill graph             |
| API                | Semantic execution unit |

------

## 10. Future Directions

### 10.1 Skill Graph as Cognitive Infrastructure

Similar to:

- Linux filesystem
- Kubernetes mesh
- Cloud runtime systems

------

### 10.2 Capability as the New Development Unit

Developers define capabilities instead of skills:

- Device capabilities
- Engineering capabilities
- Medical capabilities
- Data capabilities

------

### 10.3 AI OS as Cognitive Operating System

Core abilities:

- automatic planning
- skill composition
- execution optimization
- dynamic graph rewriting

------

## 11. Final Insight

> The future of AI is not larger models, but structured capability systems.

The final form is:

> **A Capability-driven Cognitive Operating System**