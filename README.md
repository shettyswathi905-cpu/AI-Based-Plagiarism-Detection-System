# AI-Based Plagiarism Detection System

## Problem Statement

Plagiarism means copying someone else’s work and showing it as your own.  
Nowadays, many students and writers copy content and change a few words to hide it.  
But existing tools mostly check exact word matching, so they fail to detect paraphrased content.

This problem affects students, teachers, researchers, and content writers because it reduces originality and academic honesty.


## My Understanding of the Problem

The main issue is that current tools only check words, not meaning.  
So even if the idea is copied but words are changed, it is not detected.

Plagiarism is not only copying text, it is also copying ideas.  
So meaning-based detection is important.


## My Idea

I want to build a system that detects plagiarism based on meaning.  
It will use Sentence Transformers to understand sentence similarity.  
It will generate a simple plagiarism report with percentage and matched content.


## Existing Solutions

- Turnitin  
- Grammarly Plagiarism Checker  

These tools are good for direct copy detection.  
But they fail when content is paraphrased or rewritten.


## Gap in Existing Systems

Current tools do not properly detect meaning-based plagiarism.  
They depend mostly on word matching.  
So paraphrased content is often missed.


## Sub-Problems

- Detecting meaning-based similarity  
- Converting text into vectors  
- Comparing sentences correctly  
- Handling large data  
- Generating clear reports  
- Improving accuracy for complex sentences  


## Stakeholders

- Students  
- Teachers  
- Researchers  
- Content writers  
- Educational institutions  


## Impact on Stakeholders

- Students may lose marks or learn copying habits  
- Teachers find it difficult to check many assignments  
- Researchers may lose originality  
- Writers may lose trust in content  
- Institutions may face low academic integrity  


## Root Cause

The main reason is that existing systems use word matching only.  
They do not understand meaning or context.  

So paraphrased plagiarism is not detected properly.


## 5 Whys Summary

- Plagiarism is not detected because systems check words only  
- They use simple methods for fast results  
- Advanced semantic methods are not used  
- Because they are complex and require more resources  


## Scenarios

### 1. Student Assignment
A student copies content and changes a few words.  
The system checks words only and fails to detect plagiarism.

### 2. Teacher Checking Assignments
A teacher uploads many assignments.  
The system compares them and finds similar answers.

### 3. Content Writer Checking Article
A writer checks originality of content.  
The system detects similar meaning sentences.


## Assumptions

- Users hide plagiarism by changing words  
- Meaning-based checking is needed  
- Sentence Transformers can detect similarity  
- Reports are useful but not 100% accurate  
- Some similar content is common knowledge  
- Accuracy depends on data quality  
- Large data needs optimization  


## Final Note

This project focuses on detecting plagiarism based on meaning instead of word matching.  
It helps improve originality, academic honesty, and content quality using deep learning techniques.
