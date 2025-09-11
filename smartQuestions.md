---
layout: essay
type: essay
title: "To be or not to be Smart Question"
# All dates must be YYYY-MM-DD format!
date: 2025-09-10
published: true
labels:
  - Questions
  - Answers
  - StackOverflow
---

<img width="300px" class="rounded float-start pe-4" src="../img/smart-questions/rtfm.png">

As we set out to be software engineers, asking questions is a big part of the work. Eric S. Raymond and Rick Moen's "How To Ask Questions The Smart Way" gives us a template for requesting help such as doing your homework, being concise, providing evidence, and asking a precise question.

Here I’ll  compare one "smart" and one "not-so-smart" Stack Overflow question from the past few days, characterize each questioner's conduct, and explain how the community's responses reflect the quality of the question.

## Why smart questions are important

They restrict the area in which to look for answerers by providing a reproducible example, transparent diagnostics, and a transparent question. They create reusable knowledge by using transparent titles and citations so answers may be found and reused. These are the very requirements.Raymond/Moen look for in an intelligent question.

[A smart question (C++): when a longer implicit-conversion chain succeeds but its subchain fails] (https://stackoverflow.com/questions/79756463/how-can-a-longer-c-implicit-conversion-chain-succeed-and-a-strict-subchain-of?)

The user used a concrete, explanatory title that names the phenomenon (operator lookup and implicit conversions). They included context (a tribool include unexpectedly made referenceToClass != nullptr compile). Explained results on more than one compiler and asked an explicit question: "Can anyone explain what is happening?"


The Stack Overflow community responded to the user by explaining C++ overload-resolution rules, for example., why a class type operand forms different candidate sets than an enum in isolation, citing standard text. The thread is short, to the point, and conclusive because of the prompt.


While the heading of his question could be better, it does convey what he’s trying to figure out. Usually something as brief as “python date of previous month” is what other users would enter in as search terms on Google, making it easily found. Another good thing about the question is that it’s not just a question. The asker shows what he or she has done and that he or she has put in some effort to answer the question. And while it may not be as important as the question itself, the asker shows courtesy, which does increase the chance of getting an answer.







## Conclusion

When we rely on others’ generosity and expertise to provide answers to our questions, it should hold that the question we ask should be one that leads to efficient and effective help that not only benefits us, but also the people we ask and others who might ask the same question in the future. Thus, if you have a question… make it a smart one! Asking questions may not always get you the best answer, but asking them in a way that will make others want to answer them will increase the success of finding a good solution and make it a positive experience on all sides.
