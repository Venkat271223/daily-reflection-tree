# daily-reflection-tree
# Daily Reflection Tree

This project is my submission for the DT Fellowship assignment.

At its core, this is a simple idea:

Can we help someone reflect on their day — without using AI at runtime, without free text, and without ambiguity?

Instead of a chatbot, I built a **deterministic reflection system** using a decision tree.

---

## What this does

At the end of the day, a user goes through a short structured conversation.

They don’t type anything.  
They only choose from fixed options.

Based on their choices, the system:
- asks the next question
- shows a reflection
- moves them across three layers of thinking

The same answers always lead to the same path.

---

## The three layers

1. Control — how you handled your day  
2. Contribution — what you gave  
3. Perspective — who you thought about  

---

## Why no AI at runtime?

Because reflection needs consistency.

AI can change answers every time.  
This system gives the same quality every time.

---

## Files in this project

- reflection-tree.json → decision tree
- write-up.md → design explanation
- README.md → project overview

---

## Final thought

The hardest part was not coding.

It was writing questions that make someone stop and think.
