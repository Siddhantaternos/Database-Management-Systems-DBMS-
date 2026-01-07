## 🧩 Database Normalization — Notes

Database normalization is the process of **structuring data to reduce redundancy, avoid anomalies, and preserve data integrity**.
It answers one core question:

> *How should data be split across tables so the database stays correct, scalable, and easy to maintain?*

Normalization is not about memorizing normal forms—it’s about **thinking in dependencies**:
how attributes relate, what truly belongs together, and what must be separated to prevent inconsistency.

These notes focus on:

* **Why normalization exists** (real problems it solves)
* **When to normalize and when not to**
* **How normal forms evolve logically**, not mechanically
* **Interview-relevant reasoning**, not textbook definitions

The goal is to develop **design intuition**, so schema decisions make sense even without naming a normal form.

---

## 🎯 What This Section Covers

```
Redundancy & Anomalies
      ↓
Functional Dependencies
      ↓
1NF → 2NF → 3NF → BCNF
      ↓
Trade-offs & Denormalization
      ↓
Real-world schema decisions
```

---

## 🧠 How to Use These Notes

* Read to **understand relationships**, not rules
* Revisit during **schema design problems**
* Use for **DBMS interviews and system design discussions**

Normalization is a tool—not a goal.
These notes treat it exactly that way.
