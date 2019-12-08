---
title: "Visual Concept-Metaconcept Learning"
excerpt: "Learning Visual Concepts and Relational Metaconcepts with a Language Interface"
collection: portfolio
---

Humans reason with concepts and metaconcepts: we recognize red and green from visual input; we also understand that they describe the same property of objects (i.e., the color).
In this paper, we propose the visual concept-metaconcept learner (VCML) for joint learning of concepts and metaconcepts from images and associated question-answer pairs.
The key is to exploit the bidirectional connection between visual concepts and metaconcepts.
Visual representations provide grounding cues for predicting relations between unseen pairs of concepts.
Knowing that red and green describe the same property of objects, we generalize to the fact that cube and sphere also describe the same property of objects, since they both categorize the shape of objects.
Meanwhile, knowledge about metaconcepts empowers visual concept learning from limited, noisy, and even biased data.
From just a few examples of purple cubes we can understand a new color purple, which resembles the hue of the cubes instead of the shape of them.
Evaluation on both synthetic and real-world datasets validates our claims.
We propose the Neuro-Symbolic Concept Learner (NS-CL), a model that learns visual concepts, words, and semantic parsing of sentences without explicit supervision on any of them; instead, our model learns by simply looking at images and reading paired questions and answers.
