---
layout: essay
type: essay
title: "Akamai Questions"
# All dates must be YYYY-MM-DD format!
date: 2025-09-10
published: false
labels:
  - Questions
  - Answers
  - StackOverflow
---

<img width="300px" class="rounded float-start pe-4" src="../img/askQuestion.jpg">

As we set out to be software engineers, asking questions is a big part of the work. Eric S. Raymond and Rick Moen's "How To Ask Questions The Smart Way" gives us a template for requesting help such as doing your homework, being concise, providing evidence, and asking a precise question.

Here I’ll  compare one "smart" and one "not-so-smart" Stack Overflow question from the past few days, characterize each questioner's conduct, and explain how the community's responses reflect the quality of the question.

## Why smart questions are important

They restrict the area in which to look for answerers by providing a reproducible example, transparent diagnostics, and a transparent question. They create reusable knowledge by using transparent titles and citations so answers may be found and reused. These are the very requirements.Raymond/Moen look for in an intelligent question.

## [A smart question (C++): when a longer implicit-conversion chain succeeds but its subchain fails](https://stackoverflow.com/questions/79756463/how-can-a-longer-c-implicit-conversion-chain-succeed-and-a-strict-subchain-of?)

The user used a concrete, explanatory title that names the phenomenon (operator lookup and implicit conversions). They included context (a tribool include unexpectedly made referenceToClass != nullptr compile). Explained results on more than one compiler and asked an explicit question: "Can anyone explain what is happening?"

The Stack Overflow community responded to the user by explaining C++ overload-resolution rules, for example., why a class type operand forms different candidate sets than an enum in isolation, citing standard text. The thread is short, to the point, and conclusive because of the prompt.

While the heading of his question could be better, it does convey what he’s trying to figure out. Usually something as brief as “python date of previous month” is what other users would enter in as search terms on Google, making it easily found. Another good thing about the question is that it’s not just a question. The asker shows what he or she has done and that he or she has put in some effort to answer the question. And while it may not be as important as the question itself, the asker shows courtesy, which does increase the chance of getting an answer.

## [A not-so-smart question (C++): “Error: lvalue required…” with little context](https://stackoverflow.com/questions/79597020/error-lvalue-required-as-left-operand-of-assignment)

The writer comes up with a generic question title that copied a compiler message but no purpose or intention behind it. A code snippet where there is a clear typo in the for loop, for (int i = 0; i <= n; i + 2 = i), and the ask "I am new to C++ and this community, so please help…". There are no build settings, no comparison of expected vs. actual behavior aside from the error message, and no indication of what was attempted.

The community marked the post as "needs details or clarity". Questions ask for an explanation of what the code is supposed to do and why i + 2 = i matters—i.e., the community must assemble minimal context out of the asker before they can provide long-term assistance. This doesn’t fit the standard because it’s missing a vague title, few details, no small executable code, no environment, and a generic "please help."

## Comparing the two
The first example of a "smart" message had context—short code, clear error, and straightforward request—so people leaped immediately to language principles and closed quickly. The other message lacked the fundamentals, so it wasn’t sorted out and was closed. One provided a clear answer others could learn from; the other did not.

## What I Learned (and Will Do Next Time):
Give the problem a name rather than "it doesn't work."Paste the exact error and the context (compiler, flags). Include a brief sample code one can just run. Explain what I've tried up to now and what has changed and ask for the reason or the exact solution, instead of vague help.

## Conclusion
Smart questions make help faster and better, and they leave a trace for somebody that might be struggling with the same thing. I’ll make sure to keep in mind the right way to ask a smart question, so people can answer quickly without guessing what I meant.
