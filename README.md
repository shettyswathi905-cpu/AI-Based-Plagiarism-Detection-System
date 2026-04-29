# AI-Based Plagiarism Detection System

## Problem Statement

Plagiarism means copying someone else’s work and saying it is your own.  
Nowadays, many students and writers copy content and just change a few words to hide it.  
But most existing tools only check word matching, so they fail to detect this type of plagiarism.

This problem affects students, teachers, researchers, and content writers because it reduces originality and honesty in work.



## My Understanding of the Problem

From what I understood, the main issue is that current tools only check words, not meaning.  
So even if the idea is same but words are changed, it is not detected.

Plagiarism is not only copying text, it is also copying ideas.  
So meaning-based checking is important.



## My Idea

I want to build a system that detects plagiarism based on meaning.  
It will use Sentence Transformers to understand sentence similarity.  
Then it will compare content and give a simple report with percentage and matched content.



## Existing Solutions

I found tools like Turnitin and Grammarly Plagiarism Checker.  
They are good for detecting exact copied content.  
But they are not very good when the content is rewritten in different words.


## What is Missing in Current Systems

Current systems mainly check word matching.  
They do not properly understand meaning.  
So paraphrased plagiarism is not detected properly.


## Problem Decomposition

### Problem in One Sentence
Current plagiarism tools cannot detect copied content if words are changed but meaning is same.

### Sub-Problems
- Finding similarity based on meaning  
- Converting text into vectors  
- Comparing sentences correctly  
- Handling large data  
- Creating clear reports  
- Improving accuracy for difficult sentences  


## Stakeholders

- Students  
- Teachers  
- Researchers  
- Content writers  
- Colleges and universities  


## Impact on Stakeholders

- Students → may lose marks or learn copying habits  
- Teachers → hard to check many assignments  
- Researchers → risk of losing original work  
- Writers → content quality may reduce  
- Colleges → academic honesty may be affected  


## Root Cause Analysis

The main reason is that existing tools use word matching only.  
They do not understand meaning or context.

So paraphrased plagiarism is not detected properly.


## 5 Whys

- Plagiarism is not detected because words are changed  
- Tools only check words, not meaning  
- They use simple methods for fast results  
- Advanced methods are not used because they are complex  
- They need more time, cost, and research  


## Cause Effect Flow

Word matching → No meaning understanding → Paraphrased content missed → More plagiarism → Loss of originality


## Systemic Causes

- Old technology used in tools  
- No semantic understanding  
- Only keyword-based checking  


## Situational Causes

- Students change words to hide plagiarism  
- Lack of awareness about plagiarism  
- Time pressure  
- Weak writing skills  


## Scenarios

### 1. Student Assignment
A student copies content, changes words, and submits it.  
The system checks words only and fails to detect plagiarism.

### 2. Teacher Checking Assignments
A teacher uploads many assignments.  
The system compares them and finds similar answers.

### 3. Content Writer Checking Article
A writer checks an article.  
The system finds similar meaning sentences from other sources.


## Context Variations

- Students → PDF, Word, short or long answers  
- Teachers → many or few submissions  
- Writers → blogs, articles, research papers  


## Assumptions

- Users hide plagiarism by changing words  
- Meaning-based checking is needed  
- Sentence Transformers can help detect similarity  
- System is not 100% perfect  
- Some similar content is common knowledge  
- Accuracy depends on dataset quality  
- Large data needs optimization  


## Assumption Refinement

- Many users hide plagiarism by changing words but keeping meaning same  
- Semantic similarity is better than word matching  
- Sentence Transformers help in detection  
- System gives useful but not perfect results  
- Some matches are not plagiarism  
- Performance may reduce with large data  
- Users prefer simple and clear reports  


## What I Learned

I learned that plagiarism is not only copying words but also copying ideas.  
I understood that current tools are not enough for paraphrased content.  
I also learned that deep learning can help improve detection.


## Challenges and Open Questions

I need to improve accuracy for complex sentences.  
I also need to handle large datasets properly.  
Performance and speed are also challenges.


## Next Steps

I will study Sentence Transformers in detail.  
I will try to improve my model design.  
I will also discuss my idea with teachers for feedback.  


## Final Note

This project is about detecting plagiarism based on meaning instead of only words.  
It will help students, teachers, and writers maintain originality and improve honesty in work.
