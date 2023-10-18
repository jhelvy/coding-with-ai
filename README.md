# Links

GW Coders: https://gwcoders.github.io/

Chat GPT: https://chat.openai.com/

# Summary

This repo contains several examples of prompting strategies for using AI tools like ChatGPT to improve your coding capabilities. It remains a living document that we update from time to time for workshops or presentations, demos, etc.

# Running example

Challenge: Create a chart summarizing climate change (changing global temperatures over time). Can you work with different AI tools to write the code to complete this task?

NASA data:

Charts:
https://earthobservatory.nasa.gov/world-of-change/global-temperatures

Raw data (txt file):
https://data.giss.nasa.gov/gistemp/graphs/graph_data/Global_Mean_Estimates_based_on_Land_and_Ocean_Data/graph.txt

Original source:
https://climate.nasa.gov/vital-signs/global-temperature/

# Prompting Strategies

## Take a Deep Breathe

In [this paper](https://arxiv.org/pdf/2309.03409.pdf) published by Google, they explain that there is a phrase that systematically increases the accuracy in the answers (+71%) of their LLM (PaLM 2):

> Take a deep breath and work on this problem step by step

Often times just simply adding this simple phrase to the end of your prompts can produce better results.

## Go Deeper

- Provide context
- Provide language, packages in use, etc.
- Include the “role” you want AI to play.
- Be clear and specific with what you want in return.
- Anticipate ambiguity.
- Ask about required packages/libraries, they are sometime forgotten.

## Broader/Bigger

- Initially ask about the problem you are trying to solve.
- Take a step back and ask if you are asking the right question (e.g., should I be using JSON or something else for this task?)

## Ask for multiple solutions

- Ask for two or three options.
- Ask it to provide the simplest solution first.

## Ask for explanation of the reasoning
 
- Ask for step-by-step instructions.
- Add that you want comments in the code.

## Templating

Often times you can provide a template and chatGPT will follow it. Example:

```
You are an expert course designer and extensive experience developing college courses. We will co-design a course on using python to analyze data, assuming that students are total beginners to programming and using python. Provide an outline of the course syllabus using the following template:

---

# Course title
$course_title

# Course abstract
$course_abstract

# Learning objectives
$learning_objectives

# Grading
$grading

# Schedule of topics
#schedule_of_topics
---
```

[Link to chat example](https://chat.openai.com/share/496e461b-b6ff-4c10-b715-7228c89ab280)
This will generate a syllabus with each item in the `$` section completed by chatGPT.

