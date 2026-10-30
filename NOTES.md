# Learner Notes & Working Preferences

- **Learner Profile:** Self-taught software engineer with strong software fluency, treating this curriculum as a formal, rigorous Computer Science major education.
- **Pedagogical Standard: "Deep CS Edition":**
  - **Zero Hand-Waving:** Never introduce an abstraction (e.g. Hash Maps, dynamic arrays, recursion) as a black box. Always explain the underlying machine mechanics: CPU registers, ALU operations, memory buses, cache lines, heap vs stack, hash functions, and bucket arrays.
  - **Comprehensive & Verbose Explanations:** Deep explanatory prose, physical diagrams, line-by-line CPU state traces, and mathematical derivations without artificial truncation.
  - **ELI5 ("Explain Like I'm 5") Section for Every Concept:** Every single core concept and subtopic must include a dedicated ELI5 box pairing the deep CS rigor with a vivid, physical everyday analogy (e.g. mailboxes, cafeteria trays, odometer roll-overs).
  - **Interactive Verification:** Every lesson features interactive hardware/data structure simulators and strict retrieval practice quizzes.
- **Languages:**
  - Primary code: Kotlin
  - Additional read-along languages: Python and Java
- **Critical Conceptual Anchors:**
  1. **Physical Memory Reality:** RAM layout, contiguous blocks, pointer math, bus latency, and cache hierarchy.
  2. **Data Structure Internals:** Hash functions, modulo compression, bucket arrays, separate chaining collision handling, dynamic array geometric doubling.
  3. **The "Hidden Big O" Trap in Standard Libraries:** Auditing built-in library methods (e.g., Kotlin `contains()`, `removeAt(0)`, string immutability).
  4. **Logarithmic Intuition ($\log n$):** The "Halving Game" as the inverse of exponential doubling, decision tree depths.
  5. **Call Stack vs. Heap Memory:** Stack frames, recursion depth, and auxiliary space accounting.
- **Interview Dynamics Stance:**
  - Modern technical interviews require candidates to verbalize brute force upfront (20–40s) to establish comprehension and pinpoint the algorithmic bottleneck, then gain consensus and code only the optimal solution.
