PRODIGY_GAI_01
Task 01 - Text Generation using GPT-2 (Fine-Tuning)

 Objective
Train a model to generate coherent and contextually relevant text based on a given prompt.

Model Used
 `gpt2` (by OpenAI) – fine-tuned using Hugging Face Transformers and a custom dataset.

Tools & Libraries
Google Colab
 Python
 Hugging Face Transformers
 Tokenizers
 Datasets
 PyTorch

 Dataset
A small custom dataset was prepared to fine-tune GPT-2. It was preprocessed and tokenized before training.

Process Overview
1. Loaded `gpt2` pre-trained model.
2. Preprocessed and tokenized the custom dataset.
3. Defined training arguments (epochs, batch size, logging).
4. Used `Trainer` API to fine-tune the model.
5. Evaluated the model with new prompts to test text generation.

Files
 `PRODIGY_GAI_01_TextGeneration.ipynb`: Colab notebook with full code
 `README.md`: This file with summary of the task

Sample Prompt
 "The future of artificial intelligence is"

Model Output (example)
"The future of artificial intelligence is deeply connected to ethical decisions and responsible innovation..."

 References
[Hugging Face GPT-2 Documentation](https://huggingface.co/gpt2)
 [Transformers Trainer Docs](https://huggingface.co/docs/transformers/main_classes/trainer)
