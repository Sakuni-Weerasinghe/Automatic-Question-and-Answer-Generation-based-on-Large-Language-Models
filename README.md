# Automatic-Question-and-Answer-Generation-based-on-Large-Language-Models
This is automatic question and answer generation system based on large language models for the General Certificate of Education (Advanced Level) Biology examination in Sri Lanka, which is part of the university selection examination.

The research uses large language models to generate multiple-choice questions (MCQs) under two modules automatically. 
1. The question-and-answer generation approach involves using T5-Small, T5-Base, and GPT-2. The models are fine-tuned on biology past paper MCQ datasets in a paired format to generate questions and answers.

2. In the case of distractor generation, a fusion approach combines a domain-specific dataset with insights from the pre-trained T5 model. The model is strategically adjusted on an encoded input that includes the correct answer, question, and context information relevant to the relevant biology syllabus. 

The research seeks to automate the question-generation process by integrating reinforcement learning to optimise question-specific rewards. It aims to improve the linguistic quality and content relevance of the generated questions and answer
