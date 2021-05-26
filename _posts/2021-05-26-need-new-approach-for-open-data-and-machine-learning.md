---
layout: post
title: need new approach for open data and machine learning
description: Open data, and the ability to collaborate around open data, is critical for machine learning. However the legal uncertainties around the current frameworks for open data are too important for engineers and data scientists to use data to innovate with sufficient legal clarity and security.
date: 2021-05-26
tags: open data, open source, machine learning
comment_issue_id: 2
image: img/christopher-burns-Kj2SaNHG-hg-unsplash.jpg
---

# Open data and machine learning – we need a new approach


Open data, and the ability to collaborate around open data, is critical for machine learning. However the legal uncertainties around the current frameworks for open data are too important for engineers and data scientists to use data to innovate with sufficient legal clarity and security. To illustrate this point, let’s imagine a conversation between Sarah, a data scientist, and Dwayne, her legal contact, about a fairly typical use of open data for machine learning. 

### Open data to train ML models

Sarah had sent Dwayne a first email about using an open dataset for machine learning purposes. She had an uncanny ability to ask questions on which the law was still evolving, and no time-tested (and court-tested) answer was readily available.

“I need to use this dataset with 20 million emails assembled by the Department of Thought Experiments at the University of Absaroka. I have fine-tuned several models on this dataset as the data in there has interesting properties which are not available in other datasets, and the results are really promising. In addition, I intend to share publicly one of the fine-tuned models to demonstrate the added performance and get feedback from the community. The dataset is under CC-BY. This seems fairly low risk, but I wanted to check if you had any legal concerns.”

### Open data to engage with the community

Dwayne asked if it was possible to reverse-engineer the to-be-publicly-shared model to access some of the training data. “Yes of course,” Sarah said. Part of the training data is used for validation and benchmarking, and that data is usually packaged along with the model.” 

At that point, they agreed to discuss the matter over the phone. As expected, Sarah dove right into it. “I don’t understand why you can’t make it more like open source software. Just look at the license and give me an answer.” Dwayne went into a convoluted explanation as to why open data is not like open source software. Review of datasets is often multi-layered and the nature of the data and its lineage matter a lot, so that we cannot evaluate the license alone. Compare to open source software, which is code no matter what, and which has a long and established history of caring mostly about the license. We don’t have such simplicity for data.

### A simpler, more robust approach must be possible for open data and machine learning

But Sarah was having none of it. “If developers had listened to all the possible things that could go wrong, OSS would have never taken off. With 30 years of experience, OSS has shown that open models can advance innovation in a responsible way. It sounds like you need to work on data licenses to make it easier to share and collaborate around open data. That should be your next goal.”

Ouch. Sarah had a point. Existing data licenses have so far taken an approach anchored in copyright, a safe assumption for software but which doesn’t translate well for data. In addition, these licenses are usually silent on the use of the data in a machine learning context, as that was not the main scenario when these data licenses were drafted. These two factors are creating a lot of confusion in the machine learning community and many questions are left unanswered. Why do we have a copyright license if there is no copyright in the data? Is the ML model a derivative work of the training data? It goes on and on. We need a new approach. In addition, we ought to have a solution to address the data lineage issues in a more systematic way, to have a better sense of where the data are coming from. That solution is more likely to be through better data governance mechanisms and technical means rather than through legal instruments per se. Perhaps tools like Apache Atlas are going to help. 

In the meantime, while this story is fiction and Dwayne and Sarah do not really exist, you may experience similar issues as the ones they encountered. Feel free to reach out on Twitter or LinkedIn if you have ideas or suggestions on how to help make open data more practical for machine learning.


