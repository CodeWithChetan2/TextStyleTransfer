# TextStyleTransfer
Overview:
In this project, we explore formal text style transfer using GPT-2, a powerful language model by OpenAI. We fine-tuned the GPT-2 model on the GYAFC dataset, aiming to transform informal text into formal text while preserving meaning.

Methodology:
Fine-tuning GPT-2: We fine-tuned the GPT-2 model using the GYAFC dataset. The notebook TextStyleTransfer(3)(1).ipynb contains the code for this fine-tuning process.
Evaluation Metrics:
Formality Score: We fine-tuned a BERT model on the same GYAFC dataset to evaluate the formality of generated text.
Meaning Preservation: To assess meaning preservation, we calculated the cosine similarity between the input and output sentences. Higher similarity indicates better preservation of meaning.
Files:
TextStyleTransfer(3)(1).ipynb: Jupyter notebook containing the code for fine-tuning GPT-2 on the GYAFC dataset.
(Add any other relevant files or directories here)
Results:
Formality Score: (Insert formality score results here)
Meaning Preservation Metric: (Insert cosine similarity results here)
Usage:
Clone the repository.
Run TextStyleTransfer(3)(1).ipynb to fine-tune the GPT-2 model on your dataset.
Evaluate the formality score and meaning preservation metric using formality_model.ipynb
