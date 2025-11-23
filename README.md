# NERMAAN-INTERSHIP

# 1. Problem Understanding

The task is to build a small tool that evaluates a student’s spoken introduction using the given transcript and assigns a score based on the provided rubric.

The goal is not just scoring but showing structured thinking, product design, and appropriate tool selection.

The input will be:

A student's spoken introduction transcript (text)

The output will be:

A structured evaluation score based on rubric parameters

Feedback highlighting strengths and areas of improvement

# 2. Proposed Solution Overview

I propose building an AI-based Transcript Evaluation Tool that automatically analyzes the transcript and scores it across multiple parameters such as:

Clarity of Introduction

Confidence Level (language structure)

Relevance of Content

Grammar & Fluency

Overall Communication Effectiveness

# 3 Tool Stack & Technology

I chose the following stack for simplicity and efficiency:

Language: Python

Framework: Streamlit (for simple UI)

AI Engine: OpenAI API / NLP-based rule logic

Data Handling: Pandas (for rubric Excel processing)

Reason for this choice:

Fast prototyping

Easy user interface

Scalable

Beginner-friendly and effective

The tool will simulate how a human evaluator would score using the given rubric.

# 4 Workflow Design

Step-by-step process:

User pastes the transcript into the input box

System reads the Rubric Excel file

NLP model analyzes transcript for:

Key content

Sentence structure

Keywords

Tone

Each rubric parameter is scored from 1–5

Final score is calculated automatically

Feedback is generated

# 5. Scoring Logic (Example)
Parameter	Score (1-5)	Remarks
Introduction Clarity	4	Clear self-introduction
Content Relevance	3	Some points could be more focused
Grammar & Fluency	4	Minor grammar issues
Confidence Indicators	3	Slight hesitation noticed
Overall Communication	4	Good overall presentation

✅ Final Score: 18 / 25

# 6. Expected Input
Hi, my name is Rahul. I am a student of computer science. I like AI and want to work in this field because it is future technology. I have done some projects and I am learning every day.

# 7. . Expected Output
Evaluation Result:

Introduction Clarity: 4/5  
Content Relevance: 3/5  
Grammar & Fluency: 4/5  
Confidence: 3/5  
Overall Communication: 4/5  

Final Score: 18/25  

Feedback:
The introduction is clear and concise. The candidate shows good interest in AI but can improve specificity while

# 8. Product Thinking

This tool can be expanded for:

Automated interview practice platform

Student communication skill improvement app

AI mock interview evaluator

Personalized feedback system

Future improvements:

Voice input integration

Real-time scoring

Dashboard for progress tracking

Detailed suggestions

# 9. Why This Approach?

Ensures every student gets equal evaluation

Focuses on skill instead of resume

Demonstrates practical AI usage

Scalable for large number of candidate

# 10 Conclusion

This solution demonstrates a structured approach to problem-solving by combining AI analysis with rubric-based evaluation. The tool is designed to be efficient, fair, and user-friendly while focusing on core communication skills assessment.
