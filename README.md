# IR-InvertedMatrix-Workshop

## Who Made This?

- Kapil Bhardwaj  
- Parag Shah
- Preetpal Singh

## Team-3


## What’s This Project About?

This project is all about building an **Inverted Index** — a super useful tool that helps computers find words and phrases quickly inside tons of text. Think of it like an index at the back of a book, but for loads of documents, and it remembers where each word shows up.

We worked on this as part of an **Active Learning Workshop** where we dove into how search engines and AI systems understand and process language.

---

## What Did We Build?

- Loaded over 20 real text documents to work with  
- Cleaned up the text by making everything lowercase, removing punctuation, and cutting out common words like “the” and “is”  
- Used a stemmer to shrink words down to their root forms (so “running” becomes “run”)  
- Created an **inverted index** that doesn’t just note which documents have a word, but also where exactly the words appear — making phrase searches possible!  
- Tested phrase searches like “machine learning” and “artificial intelligence” to see it in action

---

## About the Data

- The texts we used are in the `./Data/` folder — over 20 files in total  
- Our combined vocabulary has over 2000 unique words, which makes the index pretty solid  
- (If you want to know exactly where the texts come from, just ask — we used publicly available sources!)

## How to Use This?

1. Clone this repo to your computer:
   ```bash
   git clone https://github.com/yourusername/IR-invertedmatrix-workshop.git
   cd IR-invertedmatrix-workshop
