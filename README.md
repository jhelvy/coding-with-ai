# Links

GW Coders: https://gwcoders.github.io/

Chat GPT: https://chat.openai.com/

# Outline

- [5 min.] Welcome and introductions [Jason]
- [10 min.] What is Generative Artificial Intelligence (GAI) and how it works
Visualization of how GAI works.
- [5 min.] Overview of Available GAI tools [Ryan]
Current
- Microsoft Co-pilot [Describe - Ryan]
- OpenAI ChatChatGPT, Free [Justine]
- OpenAI ChatGPT4, Paid [John]
- Google Bard
- IDE integration
- [30 min.] Activity
- [10 min.] Tips for prompting [Jason]
- [10 min.] Pros and cons of strategies [Justine]
- Comparisons
- Limitations
- Ways to improve
- Ethics
- Using in class vs work vs side-projects
- [15 min.] Q&A [everyone]

# Running example

Task: Create a chart summarizing climate change (changing global temperatures over time)

NASA data:

Charts:
https://earthobservatory.nasa.gov/world-of-change/global-temperatures

Raw data (txt file):
https://data.giss.nasa.gov/gistemp/graphs/graph_data/Global_Mean_Estimates_based_on_Land_and_Ocean_Data/graph.txt

Original source:
https://climate.nasa.gov/vital-signs/global-temperature/

# Prompting Strategies

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

This will generate a syllabus with each item in the `$` section completed by chatGPT.

