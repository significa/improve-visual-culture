# Phase Three (Weeks 7–10)
## Interaction & Motion Discipline

### 🎯 Goal

Learn to use motion as **feedback and hierarchy**, not decoration.

This phase focuses on:
- Using motion to explain state changes
- Improving clarity and perceived performance
- Avoiding unnecessary or distracting animation
- Building calm, purposeful interactions

This is **not** about flashy animations.
It is about making interfaces easier to understand.

---

## 🔁 Daily Practice (10–15 mins)

Observe interaction states on **one real product** per day  
(app or marketing site).

Focus **only** on:

- Hover states
- Focus states
- Entry and exit transitions
- Loading and feedback states

Ignore:
- Large page transitions
- Marketing-only animations
- Decorative or purely aesthetic motion

---

### Daily Notes

Write short answers to:

- What interaction changed state?
- What visual property changed?
  - (opacity, color, position, scale, shadow)
- Did the motion **explain what happened**, or was it decorative?

Keep this factual and brief.

---

## 📅 Weekly Build Tasks

Each week, build **one small interaction**.

Keep scope intentionally limited.
The goal is control and restraint.

---

### Week 7 → Button Interaction States

**Build**
- Default
- Hover
- Focus
- Disabled

**Rules**
- No movement on hover
- Prefer color, shadow, or opacity changes
- Transition duration under 200ms
- Maintain accessible contrast

---

### Week 8 → Modal or Drawer Entry

**Build**
- Open transition
- Close transition
- Backdrop interaction

**Rules**
- Motion should explain spatial change
- Avoid scaling from zero
- Use consistent easing
- Keep duration short and predictable

---

### Week 9 → Feedback Interaction (Toast or Inline)

**Build**
- Success state
- Error state
- Dismiss interaction

**Rules**
- Motion should draw attention briefly, then stop
- Avoid looping or persistent motion
- Prioritize readability over flair

---

### Week 10 → Loading & Skeleton States

**Build**
- Loading placeholder
- Content reveal transition

**Rules**
- Prefer skeletons over spinners
- Skeletons should match final layout
- Motion should reduce perceived wait time
- Avoid sudden layout shifts

---

## 🧠 Motion Rule of Thumb

> If removing the animation does not reduce clarity,  
> the animation is unnecessary.

Use this rule aggressively.

---

## 📚 Recommended Resources

- Framer Motion documentation
- Apple Human Interface Guidelines — Motion
- Material Motion Guidelines

---

## ✅ Completion Criteria

After completing Phase Three, you should be able to:

- Use motion to communicate state changes clearly
- Avoid unnecessary or distracting animation
- Improve perceived performance with subtle transitions
- Justify every animation decision with user impact

You are now ready to apply these skills in:

- **Monthly Reverse-Engineering Exercises**
- Real product work