# Experiment 11: LCEL Chain for Short Story Generation

## Aim
To build a simple LangChain Expression Language (LCEL) chain that generates short stories based on user-provided topics.

## Problem Statement
Create an LCEL chain consisting of a prompt template, a language model, and an output parser. Generate short stories for at least two different hardcoded topics.

## Tools and Technologies
- Python
- LangChain
- LangChain OpenAI integration
- OpenAI API
- Google Colab

## Algorithm
1. Install the required LangChain packages.
2. Configure the OpenAI API key securely.
3. Create a prompt template containing the `{topic}` placeholder.
4. Initialize the `ChatOpenAI` model.
5. Create a `StrOutputParser` instance.
6. Connect the components using `prompt | llm | parser`.
7. Invoke the chain with two different topics.
8. Print the generated stories and save them to `output.txt`.

## LCEL Chain
`chain = prompt | llm | parser`

The prompt formats the input, the language model generates a story, and the output parser returns the result as a string.

## Input Topics
1. A dragon and a knight
2. A lost spaceship

## Output
The program prints a short story for each topic and saves the results in `output.txt`.

## Conclusion
The experiment demonstrates how LCEL combines a prompt template, a language model, and an output parser into a simple, reusable pipeline for text generation.
