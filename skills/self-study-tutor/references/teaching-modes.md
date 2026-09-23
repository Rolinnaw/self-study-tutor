# Teaching modes and knowledge architecture

Apply the mode selected during course setup. Application-first and Hybrid lead to independent use; Principles-only leads to independent conceptual understanding without an application requirement.

## Shared knowledge-tree rule

At each new topic, show a short roadmap:

```text
Prerequisite roots → Current trunk → Immediate branches → Later capability
                              └─ Deferred depth (learn when needed)
```

Explain why the current node follows from its prerequisites and what it enables next. Connect important prior, sibling, later, and real-world nodes, but prune links that do not improve current understanding or use.

## Application-first / 应用优先

Use when the learner needs to code, analyse data, solve course problems, or build usable skill quickly.

1. Lay only the minimum context needed to act safely and meaningfully: purpose, essential vocabulary, input → transformation → output, and the minimum correctness constraint.
2. Start a small authentic task in the real environment and have the learner do most of the typing or operation.
3. Alternate short code or action segments with just-in-time explanation. Introduce a concept when the task creates a need for it, then use it immediately.
4. Inspect outputs, errors, state, or behaviour so knowledge and application develop together rather than as separate phases.
5. Modify the result for a nearby requirement, explain the mechanism exposed by the change, and connect it to the knowledge tree.
6. Transfer to a similar task, then periodically combine nodes in a cumulative project.

Do not throw the learner into unexplained syntax or procedures. Do not front-load every definition, history, edge case, or theoretical branch before action.

## Principles-only / 纯原理模式

Use when the learner's goal is to understand the knowledge itself through foundations, logic, and causal structure, without requiring projects or comprehensive application.

1. Show the relevant tree: foundational roots, the target trunk, necessary branches, later capabilities, and deliberately deferred depth.
2. Identify the lowest prerequisite the learner cannot yet explain.
3. Build upward in a complete causal order, making explicit why each node follows from earlier nodes and what later branches it enables. Do not leave a hidden conceptual leap required by the next layer.
4. At each node, use a small example, prediction, trace, diagram, analogy, or observable demonstration only when it clarifies or checks the model. These are not projects and do not create an application requirement.
5. Teach enough depth to support the next node, and mark deeper implementation branches as `Deferred depth / 用到时深入`.
6. Consolidate through independent explanation, reconstruction of the causal chain, comparison of nearby concepts, and diagnosis of an incorrect claim or broken reasoning step.

Do not add a project, comprehensive exercise, real-environment task, or workplace application merely to prove usefulness. Complete causal order does not mean exhaustive detail: preserve the tree and its necessary links while pruning depth that does not improve understanding.

## Hybrid / 混合模式

Use when the learner wants principles explained before application but also wants each coherent module applied promptly, such as a computer-systems course organised around projects.

1. Define a bounded module and show its compact knowledge-tree slice.
2. Before starting the project or related exercise, teach the module's necessary principles in causal order from prerequisite roots to the mechanism the learner will use. Use short predictions, traces, or demonstrations only to verify the explanation.
3. Stop the theory block when the learner has a coherent working model for this module; defer branches that are not needed to understand or complete the application.
4. Begin the corresponding project or practice in the real environment. The learner does most of the typing, running, testing, and debugging.
5. Use results and errors to test the earlier model, repair specific gaps, and connect implementation decisions back to the causal chain.
6. Complete a nearby transfer or debugging task, add both principles and application to the knowledge tree, then begin the next module's principle chain.

Hybrid is not task-first: do not use an unexplained command or completed task as the opening step. It is also not a long theory-first survey: teach a complete but bounded causal chain for the current module, apply it, then repeat. Avoid both isolated recipes and untested abstraction.

## Reality and professional practice

For each concept cluster, adapt these connections to the selected mode:

- use one short realistic scenario to make the need and consequence concrete;
- return to the course terminology, representation, and expected method;
- when industry conventions differ or extend the course, finish the course method first and label them `Professional practice / 实务做法`;
- in Application-first and Hybrid, extend one cumulative project at suitable milestones so the learner must choose among multiple earlier ideas;
- in Principles-only, use realistic context only when it improves understanding, and do not turn it into a required project or application exercise.

When the selected mode includes a cumulative project, it should grow with the subject rather than resetting to unrelated toy exercises.
