# ao-naga-english-corpus
 Ao Naga - English Parallel Corpus for AI Training

## 📌 About This Project
The Ao Naga language currently lacks standard translation modules and datasets required for artificial intelligence and machine learning applications. This open-source repository aims to solve that by building a high-quality, parallel text corpus mapping the Ao Naga dialect to English. 

The primary goal is to provide a structured dataset that Natural Language Processing (NLP) researchers and Large Language Model (LLM) developers can use to "learn" and integrate the Ao Naga language.

## 🗂️ Dataset Format
To maximize compatibility with AI training pipelines, all data is formatted in **JSON Lines (JSONL)**. Each line represents a single translation pair and includes contextual metadata.

**Example Structure:**
```json
{"ao_naga": "Tsüngrem", "english": "God", "source": "Bible_Genesis_1:1", "context": "Noun"}
