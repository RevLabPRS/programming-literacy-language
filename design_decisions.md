PLL - Design Decisions

0.1

1. Language Purpose

PLL is a real, structured programming language designed to develop programming literacy.

Its primary objective is not to make learners proficient in PLL itself, but to develop an understanding of programming concepts that transfers to conventional programming languages.

2. Language Structure

PLL will use a small, defined collection of sentence patterns.

Learners will have enough freedom to express ideas and construct programs while maintaining predictable language behavior.

Each pattern must have a clearly defined meaning.

3. Educational Explanations

PLL will include built-in educational explanations.

Initially, each supported language pattern and error condition should have an associated explanation.

Explanations should help learners understand what happened and why, rather than simply telling them what to change.

4. Programming Terminology

PLL will introduce conventional programming terminology alongside its own language patterns.

As learners become more comfortable with programming concepts, these supporting labels and explanations should gradually become less prominent.

The objective is to develop independence rather than permanent reliance on PLL-specific terminology.

5. Language Translation

A future feature will provide a read-only view showing how PLL instructions correspond to conventional programming languages.

Initial reference languages:

- Python
- JavaScript
- C

Language patterns should be designed with these conceptual relationships in mind from the beginning.

6. Language Complexity

PLL should support programs of meaningful, mid-sized complexity.

New language features should only be introduced when they teach a transferable programming concept or provide a necessary capability.

The objective is educational usefulness, not feature parity with established programming languages.


Syntax Design Requirements

Every PLL sentence pattern must have:

1. One clearly defined meaning.
2. A plain-English reading.
3. An associated conventional programming term.
4. A built-in educational explanation.
5. A conceptual counterpart in conventional programming languages.

Patterns that cannot satisfy these requirements must be reconsidered or excluded.

Development Principle

PLL will be designed around the learner and the concepts being taught.

Traditional programming conventions should not be adopted simply because they are familiar to experienced programmers.

Every design decision should support the project's educational purpose.
