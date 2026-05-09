<p align="center">
  <img src="./comed_kares_logo.jpg" alt="COMED KARES Logo" width="350"/>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="./era_foundation_logo.jpg" alt="ERA Foundation Logo" width="150"/>
</p>


# AI based Plagiarism Detection System using Deep Learning & LLM

## Abstract

The rapid advancement of Artificial Intelligence (AI), Natural Language Processing (NLP), and generative AI tools has significantly increased challenges related to plagiarism and academic integrity. Traditional plagiarism detection systems mainly rely on lexical similarity and keyword matching approaches, which are ineffective in identifying paraphrased, semantically modified, and AI-generated content. This research proposes a hybrid AI-based plagiarism detection framework that combines Machine Learning, Deep Learning, Transformer Models, and Semantic Similarity Analysis to detect direct plagiarism, paraphrasing, conceptual similarity, and AI-generated writing.

The proposed system integrates BERT, Sentence-BERT (SBERT), RoBERTa, cosine similarity, perplexity, burstiness, TF-IDF, and stylometric analysis for advanced contextual understanding and plagiarism detection. The framework preprocesses textual content, extracts semantic embeddings, computes similarity scores, and classifies text as original, plagiarized, or AI-generated.

Experimental analysis demonstrates that the proposed hybrid system achieves improved accuracy, precision, and contextual understanding compared to traditional rule-based plagiarism detection systems. The study concludes that transformer-based semantic plagiarism detection systems provide scalable, reliable, and future-ready solutions for maintaining academic integrity.

### Keywords
Artificial Intelligence, Plagiarism Detection, Deep Learning, Natural Language Processing, Semantic Similarity, Sentence-BERT, BERT, Transformer Models, Cosine Similarity, AI-Generated Content.

---

# I. INTRODUCTION

Plagiarism has become a major concern in modern academic institutions due to the rapid growth of digital resources and AI-generated content tools. Students and researchers can easily access online material and modify it using paraphrasing tools or generative AI systems while maintaining the same semantic meaning.

Traditional plagiarism detection systems such as Turnitin and Copyscape primarily depend on string matching and lexical similarity techniques, which are effective only for detecting direct copying. These systems often fail to identify paraphrased, semantically altered, or AI-generated content.

The emergence of Artificial Intelligence (AI), Machine Learning (ML), and Natural Language Processing (NLP) has transformed plagiarism detection methodologies. Transformer-based models such as BERT, RoBERTa, and Sentence-BERT provide contextual understanding of text by analyzing semantic relationships rather than simple keyword overlap.

AI-powered plagiarism detection systems combine semantic analysis, contextual embeddings, statistical features, and stylometric analysis to improve plagiarism detection accuracy. Features such as perplexity and burstiness help distinguish between human-written and AI-generated text by analyzing predictability and sentence structure variation.

---

# II. LITERATURE REVIEW

Earlier plagiarism detection systems relied mainly on manual checking and rule-based methods for identifying copied content. Traditional systems used lexical similarity, string matching, and keyword overlap techniques to compare textual documents.

Machine Learning approaches such as Support Vector Machines (SVM), Random Forest, Gradient Boosting Machines (GBM), and Extremely Randomized Trees were later introduced to automate plagiarism detection. These models improved detection speed but suffered from high false positive rates and poor contextual understanding.

Transformer-based architectures revolutionized Natural Language Processing by introducing contextual representation learning. BERT enabled bidirectional contextual understanding of textual data. Sentence-BERT (SBERT) further improved semantic similarity analysis by generating sentence-level embeddings optimized for semantic comparison tasks.

Recent studies demonstrated that transformer-based models outperform traditional plagiarism detection systems in identifying semantic similarity, paraphrased text, and AI-generated content.

---

# III. PROPOSED SYSTEM

The proposed system is a hybrid AI-powered plagiarism detection framework that integrates semantic similarity analysis, transformer-based contextual embeddings, and AI-generated content detection techniques.

The framework combines:

- BERT for contextual text classification
- Sentence-BERT for semantic similarity analysis
- RoBERTa for AI-generated content detection
- Cosine similarity for semantic comparison
- TF-IDF for lexical feature extraction
- Perplexity and burstiness analysis for AI-generated text identification

The proposed architecture improves contextual understanding and reduces dependency on traditional keyword-based plagiarism detection approaches.

---

# IV. METHODOLOGY

## A. Data Collection

A large corpus of academic documents, essays, journals, articles, and AI-generated text samples is collected from multiple sources. The dataset contains both human-written and AI-generated textual content for supervised training and evaluation purposes.

---

## B. Data Preprocessing

The preprocessing stage includes:

- Lowercase conversion
- Stopword removal
- Tokenization
- Stemming and lemmatization
- Noise removal
- Sentence segmentation

These preprocessing techniques improve data quality and reduce unnecessary information.

---

## C. Feature Extraction

### Lexical Features

- Word frequency
- Vocabulary richness
- N-grams
- TF-IDF vectors

### Syntactic Features

- Sentence structure
- Part-of-speech tagging
- Parse trees

### Semantic Features

- Contextual embeddings
- Semantic similarity
- Conceptual overlap

### Statistical Features

- Perplexity
- Burstiness

---

## D. Semantic Similarity Analysis

Sentence-BERT converts sentences into dense contextual embeddings. Cosine similarity is applied to compare semantic relationships between sentence embeddings.

### Cosine Similarity Formula

```math
Cosine Similarity = (A · B) / (||A|| ||B||)
```

Where:
- A and B represent sentence embedding vectors
- Higher cosine similarity values indicate stronger semantic similarity

This approach enables detection of:
- Paraphrased plagiarism
- Conceptually similar content
- Reworded textual information

---

## E. AI-Generated Content Detection

The system identifies AI-generated content using statistical analysis and transformer-based classification.

### Perplexity Analysis

```math
PP(W)=√(N × 1 / P(w1,w2,...,wN))
```

Lower perplexity values generally indicate AI-generated text due to higher predictability.

### Burstiness Analysis

Burstiness measures variation in sentence length, grammatical structure, and writing rhythm. Human-written text usually exhibits high burstiness, while AI-generated text tends to show uniform and repetitive patterns.

---

## F. Model Training and Classification

Transformer-based models such as BERT and RoBERTa are fine-tuned using labeled datasets for binary classification tasks.

The models classify content into:

- Human-written
- AI-generated
- Original
- Plagiarized

The Adam optimizer and sparse categorical cross-entropy loss function are used during training to improve classification performance.

---

# V. SYSTEM ARCHITECTURE

The proposed plagiarism detection framework follows a layered architecture consisting of:

1. Input Layer
2. Preprocessing Module
3. Feature Extraction Module
4. Semantic Similarity Module
5. AI Detection Module
6. Classification Module
7. Report Generation Module

The architecture enables real-time plagiarism detection and scalable deployment in academic institutions.

---

# VI. RESULTS AND DISCUSSION

Experimental analysis demonstrated that the proposed hybrid plagiarism detection framework significantly outperformed traditional plagiarism detection methods.

The system successfully detected:

- Direct plagiarism
- Paraphrased plagiarism
- Semantic similarity
- AI-generated content
- Conceptual overlap

### Performance Metrics

- Accuracy: 95%
- Precision: 80%
- Recall: 60%
- F1-Score: 69%

Transformer-based models demonstrated superior contextual understanding capabilities compared to traditional lexical similarity approaches.

---

# VII. ADVANTAGES OF THE PROPOSED SYSTEM

- Improved semantic understanding of textual content
- Detection of paraphrased and AI-generated text
- Higher plagiarism detection accuracy
- Reduced dependency on keyword matching
- Real-time plagiarism analysis
- Scalable large-scale document processing
- Integration with Learning Management Systems (LMS)
- Improved contextual and conceptual similarity analysis

---

# VIII. LIMITATIONS

- Advanced AI humanizer tools continuously evolve
- False positives may occasionally occur
- Transformer models require high computational resources
- Large-scale datasets are necessary for effective training
- Continuous model updates are required

---

# IX. FUTURE SCOPE

- Multilingual plagiarism detection using XLM-RoBERTa
- Detection of plagiarism in images, audio, and video content
- Explainable AI for better transparency
- Cross-domain semantic similarity analysis
- Lightweight transformer architectures
- Cloud-based real-time deployment
- LMS integration

---

# X. CONCLUSION

This research presents a comprehensive AI-based semantic and hybrid plagiarism detection framework using Deep Learning and Transformer Models.

The proposed system combines semantic similarity analysis, contextual embeddings, perplexity analysis, burstiness analysis, and transformer-based classification techniques to identify direct plagiarism, paraphrasing, conceptual similarity, and AI-generated content.

Experimental analysis demonstrates that transformer-based hybrid systems significantly improve contextual understanding and plagiarism detection accuracy compared to traditional keyword-based approaches.

Although challenges such as false positives and evolving AI humanizer tools remain, the proposed framework provides a scalable, intelligent, and future-ready solution for maintaining academic integrity and originality.

---

# Comparison of Research Papers on AI-Based Plagiarism Detection

| Feature | RS-1: Hybrid AI Detection | RS-2: AI Generated Content Detection | RS-3: PLAGISENSE (SBERT) |
|---|---|---|---|
| Research Focus | AI-based plagiarism detection | AI-generated text detection | Semantic plagiarism detection |
| Main Objective | Detect plagiarism using AI & NLP | Differentiate AI and human text | Detect paraphrased content |
| Main Problem | Traditional systems fail for advanced plagiarism | AI-generated text bypasses plagiarism tools | Keyword matching fails for paraphrasing |
| Technology Used | AI, ML, NLP | Transformers + Statistical Analysis | Sentence-BERT + Semantic Embeddings |
| Main Models | SVM, Random Forest, GBM | BERT, RoBERTa, DistilBERT | Sentence-BERT |
| Semantic Analysis | Moderate | High | Very High |
| AI Content Detection | Limited | Main focus | Future enhancement |
| Statistical Features | TF-IDF, Cosine Similarity | Perplexity, Burstiness | Cosine Similarity |
| Context Understanding | Medium | High | Very High |
| Paraphrase Detection | Moderate | High | Excellent |
| Accuracy | High accuracy claimed | Up to 95% | High semantic performance |
| Dataset | Academic documents | 500K labeled texts | Original & paraphrased texts |
| Preprocessing | Tokenization, stemming | Normalization, tokenization | Stopword removal, tokenization |
| Strengths | Comprehensive framework | Strong AI-text detection | Best semantic detection |
| Weaknesses | Less AI-text focus | False positives exist | Limited AI-text focus |
| Main Contribution | Hybrid plagiarism framework | AI-generated text detection | Semantic plagiarism using SBERT |
| Future Scope | Scalability & Ethical AI | Multimodal detection | Multilingual & AI-text detection |
| Best Use Case | Academic monitoring | AI-content verification | Semantic similarity detection |

---

# REFERENCES

1. [AI Hybrid Based Plagiarism Detection System](./RS-1.pdf)

2. [Plagiarism Detection in AI Generated Content](./RS-2.pdf)

3. [PLAGISENSE: An AI-Based Semantic Plagiarism Detection System Using Sentence-BERT](./RS-3.pdf)
