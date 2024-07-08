## Whatsapp Chat Summarizer

## Folder Structure
- Notebooks/
  - BART_Large_ChatSummarization.ipynb
  - FLAN_T5_ChatSummarization.ipynb
  - Inference.ipynb
  - Samsumg_samsum_Analysis.ipynb
  - Parser/
    - exported_chat/
      - sample_whatsapp{x}/
        - media.png
        - media.mp3
        - sample_whatsapp.txt
        - summary.txt
      - Preprocessing.ipynb
      - test.json
- Paper.pdf


### Description

In the `Notebooks` folder, you will find all the notebooks used during the project, including BART fine-tuning, T5 fine-tuning, dataset creation, Samsung/samsum dataset analysis and inference.

- **BART_Large_ChatSummarization.ipynb:** Tests on the base model, fine-tuning of the BART model on SamSum, and tests on the fine-tuned model.
- **FLAN_T5_ChatSummarization.ipynb:** Tests on the base model, fine-tuning of the FLAN_T5 model on SamSum, and tests on the fine-tuned model.
- **Inference.ipynb:** Inference using our dataset and evaluation of the results.
- **Samsumg_samsum_Analysis.ipynb:** Contaning a brief analysis about the dataset that we've used for fine-tuning.
- **Preprocessing.ipynb:** Parsing of WhatsApp exported chat and creation of the JSON dataset.

## Run the Models

1. Fine-tune your preferred model (FLAN_T5 or BART) or directly use the ones already uploaded in our Hugging Face repository:
   - [BART](https://huggingface.co/Seba213/bart-large-cnn-samsum)
   - [FLAN-T5](https://huggingface.co/Seba213/flan-t5-base-samsum)
3. Generate a new dataset with a WhatsApp chat, or use the provided one.
4. Run inference on the dataset.
