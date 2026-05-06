# Mission IIT - Project Context

## Project Goal
This repository is a comprehensive question bank and syllabus tracker for students preparing for the IIT JEE (Physics, Chemistry, and Mathematics). The goal is to make the learning journey steady and interesting.

## Pedagogy: Question-Based Pedagogy (QBP)
When generating content, always adhere to the QBP framework. Instead of passive theory, students learn through guided inquiry:
1. **Elicit Curiosity:** Start with a problem that challenges existing intuition or introduces a real-world scenario.
2. **Build Concepts:** Guide the student through the derivation and application of core principles via sequential questioning.
3. **Ensure Mastery:** Provide varying levels of difficulty to solidify understanding.

Each QBP module must have:
- An **Objective**.
- Sequenced questions (Q1.1, Q1.2...) that lead to a concept.
- A **Concept Takeaway** summarizing the principle derived from the questions.

## Directory Structure
- `/syllabus`: Markdown files defining the curriculum for Physics, Chemistry, and Maths.
- `/subjects`: The main question bank organized by subject and chapter (e.g., `subjects/physics/kinematics/qbp-kinematics.md`).
- `/tests`: Sample mock papers and concept-specific quizzes.
- `/references`: Recommended books.

## Instructions for the AI Agent
- **Loading State:** Treat this `GEMINI.md` file as the absolute source of truth for the project's pedagogical style. You do not need to be re-prompted about "Question-Based Pedagogy".
- **Expanding Content:** When asked to create a new module, navigate to the corresponding directory in `/subjects`, read the template placeholder `qbp-<topic>.md`, and populate it using the detailed QBP framework.
- **Generating Tests:** Pull concepts from the existing `qbp` modules and always create a separate answer key file in `/tests`.
- **Formatting:** Use rich Markdown (MathJax `$ $` for equations, bolding for emphasis, clear lists).
