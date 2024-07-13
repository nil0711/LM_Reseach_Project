# Transfer Learning for Hindi and Sanskrit Language Models

This project explores the efficacy of transfer learning in developing language models for Hindi and Sanskrit using a Transformer-based architecture. The primary goal is to demonstrate that a Sanskrit language model can be effectively trained to understand and generate Hindi text, surpassing the performance of a model trained exclusively on Hindi data.

## Project Overview

The project involves:

- Extensive preprocessing of large text corpora.
- Vocabulary encoding.
- Model training using the GPT architecture.
- Efficient data handling techniques, such as memory mapping, to manage large datasets.
- Transfer learning by initially training a Sanskrit model and then fine-tuning it with Hindi data.

### Key Features

1. **Initial Training**: Separate models for Hindi and Sanskrit were developed by training on large, representative text corpora to capture the linguistic intricacies and nuances of each language individually.

2. **Transfer Learning**: A novel transfer learning approach was implemented to enhance the Sanskrit model's performance. This involved:
   - Training the Sanskrit model further using a Hindi dataset.
   - Gradually introducing a mixed vocabulary of both languages.
   - Starting with a majority Sanskrit vocabulary and progressively saturating it with Hindi vocabulary.

3. **Monitoring and Performance**: Detailed logging and notifications were used to monitor training progress and performance metrics.

### Results

- Significant improvements in the Hindi text generation capabilities of the transfer-learned Sanskrit model compared to the baseline Hindi model.
- Demonstrates the potential of transfer learning to enhance the performance of language models across different languages.

## Datasets

- **Hindi**: [Download](https://wortschatz.uni-leipzig.de/en/download/Hindi)
- **Sanskrit**: 
  - [Wortschatz](https://wortschatz.uni-leipzig.de/en/download/Sanskrit)
  - [Kaggle](https://www.kaggle.com/datasets/kartikbhatnagar18/sanskrit-text-corpus)

## Contribution to NLP

This project contributes to the field of natural language processing by:

- Demonstrating the potential of transfer learning to enhance language model performance across different languages.
- Offering valuable insights for future research and applications in multilingual language processing and preservation.

## Further Details

To know full details, refer to the PDF provided.

---

Feel free to reach out for any questions or contributions. Your feedback is highly appreciated!

**Contact:** csz248005@cse.iitd.ac.in

**Acknowledgments:** Thanks to all contributors and the providers of the datasets.
