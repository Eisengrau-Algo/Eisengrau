# Repository Structure

This repository uses a **pre-declared, pattern-first directory structure**.

Some directories may initially be empty. This is intentional.

The structure is designed as a **long-term taxonomy** for competitive programming
and algorithmic problem solving, and is expected to be populated progressively
over time as new material is added.

---

## Design Principles

The repository structure is guided by the following principles:

1. **Pattern-first organisation**  
   Content is grouped by algorithmic paradigm or mathematical idea rather than
   by problem number, platform, or difficulty.

2. **Long-term scalability**  
   The structure is designed to support years of incremental growth without
   requiring disruptive refactors or reorganisation.

3. **Pedagogical clarity**  
   Each directory corresponds to a concept that can be taught, explained,
   and reused across many problems.

4. **Contributor consistency**  
   A fixed structure reduces ambiguity, prevents duplicated categories,
   and allows contributors to place material confidently.

---

## High-Level Directory Overview

Top-level directories represent **major domains** in competitive programming
and algorithmic problem solving. Typical examples include:

- `foundations/` — core problem-solving skills and analytical techniques  
- `data_structures/` — fundamental and advanced data structures  
- `sorting_searching/` — ordering, searching, and two-pointer paradigms  
- `math/` — number theory, combinatorics, algebra, probability  
- `dynamic_programming/` — classic DP patterns and optimisations  
- `graphs/` — traversal, shortest paths, flows, trees, connectivity  
- `strings/` — pattern matching, suffix structures, hashing  
- `greedy/` — greedy strategies and correctness reasoning  
- `geometry/` — computational geometry techniques  
- `bit_manipulation/` — low-level bitwise methods and tricks  
- `advanced/` — ICPC-level and specialised techniques  
- `meta/` — problem classification and strategic thinking  

Subdirectories further refine these domains into specific techniques or patterns.

---

## Problem Placement Guidelines

When adding content, place it according to the **dominant idea** used to solve
the problem.

Guiding questions:
- What paradigm is essential to the solution?
- Which technique would you want a reader to recognise and reuse?
- If teaching this problem, which concept would it primarily illustrate?

If a problem spans multiple paradigms:
- choose the most central one, or
- document alternative approaches within the problem’s directory.

Avoid duplicating the same problem across multiple folders.

---

## Folder Contents

A typical problem directory may contain:
- one or more implementations (showing different approaches),
- a `README.md` explaining the reasoning, trade-offs, and pitfalls,
- notes on complexity and constraints,
- optional extensions or generalisations.

Not all directories are expected to follow the same format rigidly.
Clarity and instructional value take precedence.

---

## Empty Directories

Empty directories are expected and acceptable.

They represent:
- planned conceptual areas,
- future expansion points,
- placeholders for upcoming material.

Contributors should not remove empty directories.

---

## Contributions and Evolution

This structure is not static, but it is **intentionally conservative**.

Structural changes (renaming, merging, or introducing new top-level domains)
should be made sparingly and only when they improve clarity or correctness.

If you are unsure where something fits, open an issue or discussion before
adding new structural elements.

---

## Final Note

This repository is intended to function as a **shared, evolving knowledge base**
for algorithmic thinking.

The structure exists to support understanding, reuse, and long-term coherence.
Follow it thoughtfully, and extend it carefully.
