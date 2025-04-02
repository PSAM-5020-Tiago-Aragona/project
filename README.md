# PROJECT 1: Busted Beforehand

## The Data
This is a critical project that uses data from the **Survey of Prison Inmates, 2016** — the most recent and detailed dataset I could find on inmates in the U.S. It includes a substantial amount of information on race, age, level of education, and more. Some sensitive data (which could help identify individuals) is excluded, but that’s not the focus of this project. In fact, that kind of individual identification goes against the point I’m trying to make.

## Bias
This is going to be an *intentionally biased* project. Why? Because the goal is to create a critical artwork that estimates your odds of being arrested — based solely on data from people who have already been incarcerated. This dataset contains one side of the story, and while it reflects statistical trends, it lacks the opposite: data on those who are *not* incarcerated. I plan to collect or synthesize that missing half and combine it with the existing data.

## System
This project will allow users to answer the same survey questions that inmates were asked, and it will calculate their estimated probability of being arrested. It will primarily function as a **classification model**, but also as a reflective mirror of society and police brutality.

## Why?
I live in an area that is predominantly Latina/o. I've seen police officers arrest Latino kids without much justification more than once. It’s a sad image — watching a young Latino kid in handcuffs. This project is a response to that reality.

## Dataset Coding
The dataset uses references in the names of the columns. This columns correspond to different questions in the survay and are specified in data/37692-0001-Codebook.pdf. Also, the answers are indexed. Let's say the question is: "Do you identify as latino/a?". The answers could be:

- No -> Index: 1
- Yes -> Index: 2
- N/A -> Index: 3
