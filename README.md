C01 - TypeScript’s Type System and Its Relation to JavaScript’s Dynamic Typing
This repository contains the final project for the Advanced Programming course (Academic Year 2025/2026) at the University of Pisa.

The project explores the architectural tension between TypeScript's static, structural type system and JavaScript's inherently dynamic runtime, focusing on the pragmatic design choices that allow them to coexist.

🎯 Goal
To analyze how TypeScript adds a static type-checking layer on top of JavaScript without changing its underlying runtime semantics. The project investigates key concepts like Type Erasure, Soundness vs. Pragmatism, and Gradual Typing.

📂 Project Structure
Task 1: Theoretical Foundations
An in-depth explanation of the TypeScript type system, covering:

JavaScript’s Dynamic Nature: Analysis of type coercion, silent failures, and latent bugs.

The TypeScript Model: Exploration of static analysis, type erasure, and the "pragmatism over soundness" philosophy.

Key Mechanisms: Detailed breakdown of Gradual Typing (the any vs. unknown dial), Structural (Duck) Typing, Discriminated Unions, and Generics.

Task 2: Practical Scenarios & Mismatches
Code demonstrations illustrating the boundaries of the type system:

Static Error Detection: Examples of the compiler catching missing properties and invalid argument types.

Runtime Mismatches: Scenarios where TypeScript's static assumptions fail at runtime (e.g., out-of-bounds array access and unsafe type assertions).

Task 3: Methodology & AI Orchestration
A documentation of the "Multi-Model" approach used to develop this report:

Prompt Architect: Using Gemini 3 Pro to engineer precise, high-level prompts.

Execution Engine: Using ChatGPT 5.2 to generate technical syntheses based on those prompts.

Human-in-the-loop: Final validation and "semantic glue" provided by the author.

🛠 Validation & Verification
All technical content underwent a rigorous verification process:

The "Playground" Test: Every code snippet was executed in the TypeScript Playground (v5.9.3) to verify compiler errors and runtime outputs.
https://www.typescriptlang.org/play/

Theoretical Cross-Referencing: Definitions were validated against the Official TypeScript Handbook and the ECMAScript (ECMA-262) specification.
https://www.typescriptlang.org/docs/handbook/intro.html
https://ecma-international.org/publications-and-standards/standards/ecma-262/

👤 Author
Francesco Polperio (Student ID: 635406)

University of Pisa - Department of Computer Science
