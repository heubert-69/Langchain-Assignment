# Mini Prompt Engine (LangChain)

## Overview

This project implements a **Mini Prompt Engine** using LangChain to replace hardcoded prompts with dynamic, reusable, and structured prompt templates.

It demonstrates how to design reliable prompt pipelines with validation, modularity, and testing.

---

## Features

* Dynamic prompt generation using PromptTemplate
* Multi-input prompt system (topic, audience, tone)
* Prompt variations (teaching, interview, storytelling)
* Chat-based prompting with roles (teacher, interviewer, motivator)
* Input validation layer
* Reusable template design

---

## Advanced Testing

### Stress Testing

Evaluates system robustness against:

* Empty inputs
* Long strings
* Noisy/symbolic inputs

### Impossibility Testing

Handles invalid inputs such as:

* None values
* Unsupported audience/tone

### Statistical Testing

Measures consistency of outputs:

* Mean length
* Standard deviation
* Min/Max output size

Result: Low variance, high consistency

---

## Pipeline

User Input → Validation → Prompt Template → Generated Prompt → Output

---

## Example

Input:

* Topic: Neural Networks
* Audience: beginner
* Tone: fun
* Style: storytelling

Output:
Explain Neural Networks for beginner in a fun storytelling style

---

## Key Insight

The system behaves like a **low-variance, high-bias model**:

* Highly consistent outputs
* Limited flexibility in expression

---

## Tech Stack

* Python
* LangChain
* Jupyter Notebook / Google Colab

---

## Future Improvements

* Semantic validation of topics
* Output diversity scoring
* Prompt entropy analysis
* Adaptive prompt generation

---

## Author

Student Project – Prompt Engineering & NLP
