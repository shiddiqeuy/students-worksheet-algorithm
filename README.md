# Algorithm Worksheet — Go Programming

**Introduction to Programming · International Class · 2026**  
Instructor: **shiddiqazis** · Language: English · Programming language: Go

> **Predict first. Run second. Explain third.**  
> A compiler checks syntax; your reasoning checks meaning.

This repository is the **official student worksheet and starter-code home** for the Go hands-on exercises in *Programming Fundamentals: From Real Life to Algorithms*. Work through data types, sequential execution, conditionals, mathematical models, number sequences and an optional introduction to genetic algorithms.

## Start here

1. Read **[WORKSHEET.md](WORKSHEET.md)** for the stories, tasks, and acceptance criteria.
2. **Fork** this repository into your own GitHub account (do not edit the instructor's main branch).
3. Clone your fork and open it in VS Code. Check Go with `go version`.
4. Open one lab folder, e.g. `cd student/01_data_types`, and run `go run main.go`.
5. Complete the `TODO` sections, predict the output, test it, and format with `gofmt -w main.go`.
6. Copy **[EXPLANATION_TEMPLATE.md](EXPLANATION_TEMPLATE.md)** to `EXPLANATION.md` in your fork and document your reasoning.
7. Commit and push your solutions to your fork. Then open a **[Submission Issue](https://github.com/shiddiqeuy/students-worksheet-algorithm/issues/new/choose)** in *this* repository with your fork link. The issue form is provided for you.

**Important:** Each folder contains its own `main.go`. Run one folder at a time. No Go module or external dependencies are required for the starter exercises.

## Nine labs

| Lab | Topic | Level | Acceptance evidence |
|---|---|---|---|
| [01](student/01_data_types/main.go) | Data types and identifiers | Required | `19, 62.5, true, 00123` |
| [02](student/02_cafe_sequence/main.go) | Instruction sequencing: campus café | Required | `Subtotal: 36000`, `Total: 31000` |
| [03](student/03_factor_checker/main.go) | Factors, modulo, input validation | Required | `5 20` → `true`; `0 20` → `invalid input` |
| [04](student/04_population/main.go) | Population accounting | Required | `Population: 1011` |
| [05](student/05_number_sequence/main.go) | Additive number sequences | Required | `5, 3` → `8 11 19` |
| [06](student/06_gravity/main.go) | `float64`, mass and weight | Required | `Earth: 686.0 N`; `Mars: 260.7 N` |
| [07](student/07_genetic_intro/main.go) | Genetic algorithm: four-bit demonstration | Optional enrichment | Child `1010` has fitness 2; mutated `1110` has fitness 3 |
| [08](student/08_cube_root/main.go) | Cube roots via multiplication | Required | `-3 -27` → `true`; `12 12` → `false` |
| [09](student/09_bonus_ga_loop/main.go) | Population-based genetic search | Advanced bonus | Print generation and fitness; include stopping condition |

**Note:** Instruction sequencing (order of execution), number-sequence generation, and genetic algorithms are **three different concepts**. The four-bit lab is only a demonstration of GA operators, not a complete evolutionary optimizer.

## How to submit

- Submit the **link to your fork** by opening a [GitHub Issue](https://github.com/shiddiqeuy/students-worksheet-algorithm/issues/new/choose) here (select *Go Lab Submission*). Keep this original repository clean; student work belongs in forks.
- In your fork, include completed Go files, `EXPLANATION.md`, and terminal evidence for **at least three labs**, plus a normal test and an edge/invalid case.
- Be ready for a **two-minute individual mini-defense in English**: What are the inputs? Why those data types? Why that operation order? What case would break?
- This repository is public. **Do not post student ID numbers, private contact details, grades, or other sensitive information** in issues or commits. Use the university LMS if formal identity verification is needed.

**Rubric (10 pts):** outputs 4 · types and logic 2 · tests 2 · code clarity and explanation 2.

© 2026 shiddiqazis — classroom material. Exercises are adapted and expanded from the supplied university review handout; new Go stories and the genetic-algorithm introduction are instructional enrichment.
