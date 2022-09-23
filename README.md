

# Quick Reader

Don't read the  book just use Quick Reader 🤓

<img src="https://thumbs.dreamstime.com/b/person-reader-books-studying-preparing-exam-speed-reading-education-knowledge-concept-woman-fiction-literature-leisure-256904883.jpg"
align="right" 
     title="Quick Reader" width="30%" height="30%">

- Text summarization
- Information retrieval
- Finding similarities 
- Sentence ranking
- Keyword extraction
- and many more in progress...



## More about Project

Keyword extraction is an extremely interesting topic in Information Retrieval- keywords are widely acknowledged to be extremely important in the field of text retrieval, and particularly while developing large scale modern search engines that limit the size of the inverted index used by the system.

In this project we propose to build a system using modern NLP techniques such as Part of Speech Tagging, Brown Clustering and Rapid Automatic Keywords Extraction (RAKE) to use a small initial seed of keywords to generate more candidate keywords in a semi-supervised manner and expose the system as a JSON based web service.





### Installation

  #### Quick Access
 

## How does the library work?

The library has several components:

1. Summarizers
2. Rankers
3. Similarity Algorithms
4. Information Retrievers
5. Keyword Extractors

### Summarization

A technique of transforming or condensing textual information using natural language processing techniques.


#### Types of summarization

<img src="https://user-images.githubusercontent.com/43802499/99897230-d5107a00-2cbd-11eb-8b7a-de7e3e0b7bc3.jpeg" 
align="right"
     title="Summarization" width="50%" height="30%">

**Extractive** 

This technique is very much similar to **highlighting important sentence** while we read a book.

The algorithm finds the important sentences in the corpus (NLP term for raw input text) by reducing the **similarity** between sentence by removing sentences which are very similar to each other by retaining one among them.

Though this method is a powerful it fails to combine 2 or more sentences into a complex sentence, there by not provide optimal result for some cases.


**Abstractive**

This technique unlike extractive is much more complex and robust in producing summaries. The algorithm used for this technique performs **sentence clustering** using **Semantic Analysis** (finding the meaning of sentence).


### Sentence Ranking

Text rankers are algorithms similar to web page ranking algorithms used to rank web pages. These rankers find the importance of the sentence in the document and provide ranks to the sentence, thereby providing us with the information of how important the sentence is.

### Similarity Algorithms

Text similarity algorithms define the similarity between 2 documents (sentences). 

A few classic algorithms for finding similarity are:
1. Cosine Similarity
2. Euclidean Distance

> Note: word2vec is an important transformation step used to convert words into vectors to easily perform mathematical operations.


## Features

Checklist of features the library currently offers and plans to offer.

- [x] Keyword Extraction
- [x] Text Tokenizers 
- [x] Text cleaners
- [ ] Semantic decoder
- Summarization
  - [x]  Extractive
  - [ ]  Abstractive
- Text Rankers
  - [x] Intermediate
  - [ ] Advanced
- Information Retrieval
  - [x] Intermediate
  - [ ] Advanced




## Contribution

Contributions are always welcomed, it would be great to have people use and contribute to this project to help user understand and benefit from library.

### How to contribute
- **Create an issue:** If you have a new feature in mind, feel free to open an issue and add some short description on what that feature could be.
- **Create a PR**: If you have a bug fix, enhancement or new feature addition, create a Pull Request and the maintainers of the repo, would review and merge them.

## Authors

* **Andrew Chan** - [@KrishnanSG](https://github.com/andrewchancgc)
* **Pascal Burume ** - [@Shruthi-22](https://github.com/PascalBurume)
* * **Chin Hao Wong ** - [@Shruthi-22](https://github.com/ChinHaoX3)
* * **Pascl urume ** - [@Shruthi-22](https://github.com/PascalBurume)
* * **Pascal Burume ** - [@Shruthi-22](https://github.com/PascalBurume)
* * **AnushkaBhatnagar ** - [@Shruthi-22](https://github.com/AnushkaBhatnagar)
* * **Pascal Burume ** - [@Shruthi-22](https://github.com/PascalBurume)
* * **Pascal Burume ** - [@Shruthi-22](https://github.com/PascalBurume)
