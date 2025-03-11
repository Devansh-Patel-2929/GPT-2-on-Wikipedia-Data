This project fine-tunes a GPT-2 model on a subset of the English Wikipedia dataset to generate encyclopedia-style text. The implementation includes data loading, preprocessing, model fine-tuning, perplexity evaluation, and text generation examples, demonstrating improved performance and style consistency compared to the pre-trained GPT-2 model. The fine-tuned model and tokenizer are saved for future use.

## Model Architecture
* GPT-2 employs a decoder-only transformer architecture with 12 layers, 12 attention heads, and 768-dimensional embeddings in its base configuration.

## Training Details

*   **Dataset:** A subset of the English Wikipedia dataset (10,000 articles for training, 1,000 for validation).
*   **Tokenizer:** GPT2Tokenizer
*   **Optimizer:** AdamW
*   **Learning Rate:** 5e-5
*   **Epochs:** 3
*   **Batch Size:** 4 (adjust based on GPU memory)
*   **Sequence Length:** 512
*   **Gradient Clipping:** 1.0
