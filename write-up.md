# Daily Reflection Tree — Design Write-up

## 1. What I was trying to build

The goal of this assignment was not just to ask questions, but to design a system that makes someone pause and think about their day.

Not advice. Not motivation.

Just structured reflection.

I approached this as a deterministic conversation — where every answer leads somewhere specific. No guessing. No AI interpretation. The same answers always produce the same path.

---

## 2. How I thought about the structure

I didn’t design this as three separate sections. I designed it as one flow.

The idea was simple:

First → help the user see how they handled their day  
Then → shift them to what they contributed  
Then → expand their thinking beyond themselves  

That naturally maps to the three axes:
- Locus (control)
- Contribution
- Radius (perspective)

Each axis builds on the previous one.

If someone recognizes their role in events, they are more open to thinking about contribution.  
If they think about contribution, they are more likely to think about others.

---

## 3. Axis 1 — Locus (Control)

I started with a very simple question: *How was your day?*

Not because it’s deep — but because it’s real. Everyone can answer it without thinking too much.

From there, I split the flow:

- “Productive / Mixed” → leads to internal reflection  
- “Tough / Frustrating” → leads to external reaction  

The idea here was not to judge the user, but to surface how they *frame events*.

The reflection is intentionally soft:
- If internal → reinforce agency  
- If external → gently point toward choice  

This sets the foundation for the rest of the flow.

---

## 4. Axis 2 — Contribution

After control, I shift the focus to contribution.

This is where things usually get uncomfortable — because people don’t naturally think in terms of “what did I give?”

So I framed the options in a way that feels real:
- Helping others
- Doing assigned work
- Expecting recognition
- Feeling others should do more

Instead of labeling behavior as “good” or “bad”, I route it into two directions:
- Contribution
- Entitlement

The reflection here doesn’t criticize. It just makes the pattern visible.

---

## 5. Axis 3 — Radius (Perspective)

This is where the reflection expands.

The question becomes:
*Who were you thinking about today?*

This moves from:
- Self → tasks → team → customers

The goal is to show that:
As perspective widens, meaning increases.

Again, no forcing. Just showing the difference.

---

## 6. How the branching works

Every decision is fixed.

There is:
- No randomness  
- No interpretation  
- No “AI guessing what you meant”  

Each answer maps directly to a node.

For example:
- “Productive” always goes to internal reflection  
- “Tough” always goes to external reflection  

This makes the system:
- Predictable  
- Testable  
- Easy to understand  

---

## 7. Why I wrote reflections this way

I avoided:
- Moral tone  
- Advice  
- “You should…” statements  

Instead, reflections:
- Acknowledge what happened  
- Slightly reframe it  
- Leave space for the user to think  

It should feel like a colleague, not a teacher.

---

## 8. Trade-offs I made

I kept the tree relatively simple.

I could have added more branches, but that would make it:
- Harder to follow  
- Harder to debug  

I also used fixed reflections instead of dynamic ones.

That limits personalization, but ensures consistency.

---

## 9. What I would improve

If I had more time, I would:

- Add more depth within each axis (especially follow-up questions)
- Use accumulated signals to generate a more personalized summary
- Add multiple entry points depending on how the day started

Right now, the tree works as a solid base, but it can be expanded.

---

## 10. Final thought

The hardest part of this assignment was not writing code.

It was designing questions that feel real at 7 PM — when someone is tired and not interested in a “system”.

If the question doesn’t make them pause for even a second, the tree fails.

That’s what I tried to focus on.