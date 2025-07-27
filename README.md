#  Fine-Tuning-BERT-for-Multi-Class-Text-Classification

 **BERT-Based News Topic Classifier** -Classify news headlines into one of four categories - **World**, **Sports**, **Business**, or **Sci/Tech** - using a fine-tuned BERT transformer.

---

## Project Overview

This project uses **Hugging Face Transformers** and the **AG News** dataset to build a **text classification model**. It leverages the power of **BERT (Bidirectional Encoder Representations from Transformers)** for understanding the context of short news headlines and predicting their correct category.

## How It Works 

**For Example** - Think of BERT as a multilingual, highly educated assistant you just hired.

But…

BERT comes with general knowledge (pretrained on all kinds of books, Wikipedia, etc.), not specific expertise like recognizing news topics.

So you did this:

🧠 Pretrained Knowledge (BERT)
➤ You hired a well-educated assistant with general English skills.

📚 Fine-Tuning (AG News)
➤ You gave them a special training course on how to read news headlines and classify them into one of 4 topics (Business, Sports, etc.).

🎯 Prediction (Sample News)
➤ Now, when you give them a new headline like:

"NASA launches a new satellite to Mars."
They confidently answer:
"That's Sci/Tech."

---

 ## 🧠 Model Architecture

- **Model**: ['bert-base-uncased'](https://huggingface.co/bert-base-uncased)
- **Tokenizer**: 'BertTokenizerFast'
- **Head**: Sequence classification layer (4 output labels)
- **Fine-Tuning**: On the AG News dataset for text classification

---

## 📚 Dataset: AG News

- Provided by: [Hugging Face Datasets](https://huggingface.co/datasets/ag_news)
- Contains 120,000 training and 7,600 test samples
- Categories:
  1. **World**
  2. **Sports**
  3. **Business**
  4. **Sci/Tech**
  
  ---

## 🙌 Credits

- 🤗 [Hugging Face Transformers](https://huggingface.co/transformers)
- 🤗 [Hugging Face Datasets](https://huggingface.co/datasets/ag_news)
- 📚 AG News Corpus by Xiang Zhang  
  - Original Source: https://www.di.unipi.it/~gulli/AG_corpus_of_news_articles.html  
  - License: [Creative Commons Attribution 4.0](https://creativecommons.org/licenses/by/4.0/)
