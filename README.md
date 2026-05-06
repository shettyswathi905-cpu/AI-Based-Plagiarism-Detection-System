# AI-Based Plagiarism Detection System


## Project Overview

This project is about building a smart plagiarism detection system using Artificial Intelligence.

Most existing tools only check copied words. But today, many users change words and keep the same meaning. These tools fail to detect such plagiarism.

This system focuses on understanding the **meaning of sentences** instead of just matching words.


## Problem Statement

### What is the problem?
Plagiarism means copying someone else's work and presenting it as your own.

Many students and writers copy content and change a few words to avoid detection. Even though the words are different, the meaning stays the same.

Current tools cannot detect this properly.


### Who does it affect?
- Students  
- Teachers  
- Researchers  
- Content writers  
- Colleges and universities  


### Why is it important?
- Encourages honest learning  
- Maintains academic integrity  
- Promotes originality  
- Protects others' work  


## Understanding the Problem

### Key Issues
- Tools only check words, not meaning  
- Cannot detect paraphrased content  
- Do not understand context  


## Root Cause Analysis

### Symptoms
- High plagiarism in assignments  
- Low originality  
- Slightly modified copied content  


### Actual Problem
Tools cannot understand sentence meaning. They only compare words.


### Cause Flow
Word matching  
→ No meaning understanding  
→ Paraphrasing not detected  
→ Increased plagiarism  


### Causes

#### System Issues
- Old technology  
- No semantic analysis  

#### User Issues
- Students change words  
- Lack of awareness  
- Time pressure  


## Problem Breakdown

### Main Tasks
- Meaning-based similarity detection  
- Text to vector conversion  
- Sentence comparison  
- Handling large data  
- Report generation  
- Improving accuracy  


## Stakeholders

| Stakeholder | Benefit |
|------------|--------|
| Students | Learn honestly |
| Teachers | Easy checking |
| Researchers | Protect work |
| Writers | Create original content |
| Colleges | Maintain quality |


## Scenarios

### Student
- Upload assignment  
- System checks content  
- Shows report  

### Teacher
- Upload multiple files  
- System compares them  
- Finds similarities  

### Writer
- Upload article  
- System checks originality  


## Assumptions

- Users hide plagiarism by changing words  
- Meaning-based detection is needed  
- AI can improve results  

### Notes
- System may not be 100% accurate  
- Some content is common knowledge  
- Large data may slow the system  


## Existing Solutions

| Tool | Type | Source |
|------|------|--------|
| Turnitin | Academic Software | https://www.turnitin.com |
| Grammarly | Online Tool | https://www.grammarly.com |
| Copyscape | Web Tool | https://www.copyscape.com |
| Quetext | AI Tool | https://www.quetext.com |
| Manual Checking | Traditional Method | Academic Practice |


## How Existing Tools Work

### Turnitin
- Uses large database  
- Gives similarity score  

### Grammarly
- Checks grammar and plagiarism  

### Copyscape
- Detects copied web content  

### Quetext
- Uses AI for deep checking  

### Manual Checking
- Done by teachers  
- Takes more time  


## Comparison

| Feature | Turnitin | Grammarly | Copyscape | Quetext | Manual |
|--------|----------|-----------|------------|----------|---------|
| AI | Yes | Limited | No | Yes | No |
| Speed | Medium | Fast | Fast | Medium | Slow |
| Accuracy | High | Medium | Medium | High | Depends |


## Limitations

- Cannot detect smart paraphrasing  
- Many tools are paid  
- Limited understanding of meaning  
- False results possible  
- Manual checking is slow  


## Observations

- Tools depend on word matching  
- AI tools are better but not perfect  
- Need smarter systems  


## Identified Gaps

- No proper meaning-based detection  
- Weak paraphrase detection  
- Limited free tools  


## Proposed Solution

### Idea
Build a system that understands meaning instead of words.


### Approach
- Convert text into vectors  
- Use Sentence Transformers  
- Compare sentence meaning  
- Generate report  


### Features
- Detect paraphrased content  
- Show similarity percentage  
- Highlight matches  
- Simple report  


## Challenges

- Handling complex sentences  
- Reducing false results  
- Managing large data  
- Improving accuracy  


## Conclusion

Current tools are helpful but limited. They cannot detect meaning-based plagiarism.

This project solves this by using AI to understand content and detect even rewritten plagiarism.


## Future Work

- Improve accuracy  
- Handle large data better  
- Add real-time checking  
- Build simple UI  

## References
[Read PDF](./docs/Paper1.pdf)
[Read PDF](./docs/Paper2.pdf)
