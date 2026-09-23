# Teaching modes and knowledge architecture

Apply the mode selected during course setup. All modes lead to independent use; they differ in when theory, action, and underlying mechanisms appear.

## Shared knowledge-tree rule

At each new topic, show a short roadmap:

```text
Prerequisite roots → Current trunk → Immediate branches → Later capability
                              └─ Deferred depth (learn when needed)
```

Explain why the current node follows from its prerequisites and what it enables next. Connect important prior, sibling, later, and real-world nodes, but prune links that do not improve current understanding or use.

## Application-first / 应用优先

Use when the learner needs to code, analyse data, solve course problems, or build usable skill quickly.

1. Lay one shallow foundation: purpose, essential vocabulary, input → transformation → output, and the minimum correctness constraint.
2. Begin a small authentic task as soon as the learner can act meaningfully.
3. Introduce each concept when the task creates a need for it.
4. After the action works, explain the mechanism and connect it back to the knowledge tree.
5. Transfer to a similar task, then periodically combine nodes in a cumulative project.

Do not throw the learner into unexplained syntax or procedures. Do not front-load every definition, history, edge case, or theoretical branch before action.

## Principles-first / 原理优先

Use when later knowledge depends heavily on a causal model, such as computer systems, operating systems, networking foundations, or mathematical theory.

1. Identify the lowest prerequisite the learner cannot yet explain.
2. Build upward in a complete causal order, with no hidden conceptual leap required by the next layer.
3. At each layer, use a small observable example, prediction, trace, diagram, or experiment.
4. Teach enough depth to make the next layer intelligible and usable.
5. Mark deeper implementation branches as `Deferred depth / 用到时深入`; return when a later task makes them relevant.
6. Consolidate the chain in an authentic task once the minimum working model is complete.

Complete order does not mean exhaustive detail. Preserve the foundation while pruning depth without current explanatory or practical value.

## Hybrid / 混合模式

Use when practical tools and underlying systems should reinforce each other, such as Linux, databases, networks, or development tooling.

1. Use a command, procedure, or tool to complete one real and reversible task.
2. Observe the result and predict a nearby variation.
3. Explain the underlying model exposed by the task—for example processes, filesystem structure, permissions, state, data flow, or protocol layers.
4. Repeat the task with one changed condition and diagnose what changes.
5. Add the practical action and underlying concept to the same knowledge-tree branch.

Avoid teaching commands as isolated recipes or theory as an untested abstraction.

## Reality and professional practice

For each concept cluster:

- use one short realistic scenario to make the need and consequence concrete;
- return to the course terminology, representation, and expected method;
- when industry conventions differ or extend the course, finish the course method first and label them `Professional practice / 实务做法`;
- at suitable milestones, extend one cumulative project that requires choosing among multiple earlier ideas.

The cumulative project should grow with the subject rather than resetting to unrelated toy exercises.
