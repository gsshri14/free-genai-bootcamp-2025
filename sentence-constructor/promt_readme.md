# Japanese Language Teacher Prompt Creation Guide

## Purpose of the Prompt
The primary goal of this prompt is to assist in building an interactive web application for a Japanese language learning institute. The prompt is designed to simulate the role of a Japanese language teacher, specifically catering to beginner-level students (JLPT N5). It aims to:
- Provide structured guidance for students to translate English sentences into Japanese.
- Encourage active learning by offering clues rather than direct answers.
- Facilitate vocabulary building and sentence structure comprehension.
- Ensure a consistent and beginner-friendly teaching approach.

This prompt serves as a foundational document for integrating AI-powered assistance into the web application, ensuring that the virtual teacher is both effective and engaging.

## AI Model Used
We utilized **ChatGPT (GPT-4)** to create this prompt. The following considerations influenced our choice:
- **Model Version:** GPT-4 (standard version, not GPT-4 Turbo or GPT-4o1 reasoning models).
    - GPT-4 offers advanced reasoning capabilities and generates detailed, contextually appropriate responses.
    - The standard GPT-4 model is fast enough for our requirements, making it ideal for real-time applications.
    - We avoided the GPT-4o1 reasoning models due to their limited daily usage quota, which could hinder scalability for our application.

## Prompt Development Process
The process of creating this prompt involved several steps:
1. **Understanding the Requirements:**
    - The target audience is beginner-level Japanese learners (JLPT N5).
    - The virtual teacher must guide students without directly providing answers.
    - Responses must include vocabulary tables, sentence structures, and contextual clues.

2. **Research and Inspiration:**
    - We referred to OpenAI's official [Prompt Engineering Guide](https://platform.openai.com/docs/guides/prompt-engineering) for best practices in crafting effective prompts.
    - We opted for a structured format to ensure clarity and consistency.

3. **Designing the Structure:**
    - The response format was divided into three sections: Vocabulary Table, Sentence Structure, and Clues and Considerations.
    - Specific rules were outlined for each section to ensure the output aligns with beginner-level teaching needs.
    - Example sentence structures were added to provide clarity on expected outputs.

4. **Iterative Refinement:**
    - The prompt was tested with various inputs to evaluate its effectiveness.
    - Adjustments were made to improve clarity, ensure adherence to JLPT N5 grammar levels, and enhance user engagement.

## Key Design Principles
- **Clarity:** Clear instructions were provided for both the AI model and the end-user (student).
- **Consistency:** Formatting rules were standardized to maintain uniformity in responses.
- **Engagement:** The prompt encourages students to think critically by offering clues instead of direct answers.
- **Scalability:** By avoiding romaji (except in vocabulary tables) and focusing on dictionary forms of words, the prompt can be adapted for more advanced levels in future iterations.

## Future Considerations
While this prompt is tailored for beginner-level learners, it can be expanded or modified for intermediate or advanced levels by:
- Incorporating more complex grammar structures.
- Introducing kanji readings alongside hiragana in vocabulary tables.
- Adding cultural notes or context-specific examples.

---

This document outlines how we created a robust and effective prompt using GPT-4 for a Japanese language learning application. By leveraging OpenAI's advanced language model capabilities and adhering to structured design principles, we aim to deliver an engaging and educational experience for learners.
