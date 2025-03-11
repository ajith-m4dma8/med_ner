# Medical Named Entity Recognition (NER) using BERT

## Overview
This project involves developing a custom BERT-based model for Named Entity Recognition (NER) in the medical domain. The model is designed to accurately identify and classify medical terms, including diseases, treatments, medications, and anatomical entities. By leveraging transfer learning, the BERT model has been fine-tuned on specialized medical datasets to enhance entity recognition accuracy in healthcare texts.

## Features
- **Custom BERT-based NER model** optimized for medical text.
- **Fine-tuned on specialized medical datasets** for better accuracy.
- **Identifies and classifies key medical entities** such as:
  - Diseases
  - Treatments
  - Medications
  - Anatomical terms
- **Useful for healthcare NLP applications**, including:
  - Clinical documentation automation
  - Medical research information extraction
  - Biomedical text processing

## Datasets
The model has been fine-tuned on two different medical datasets:
1. **BC5CDR** - A dataset for biomedical named entity recognition, focusing on chemicals and diseases.
2. **i2b2** - A dataset containing clinical text annotated with medical entities.

Both datasets have been used to train separate models, each with its own Jupyter Notebook.


Open the relevant notebook based on the dataset:
- `bc5cdr_med_ner.ipynb` - For BC5CDR dataset training and testing.
- `i2b2_final_med_ner.ipynb` - For i2b2 dataset training and testing.

## Results
- Achieved high accuracy in recognizing medical entities.
- Improved entity classification in clinical and biomedical text.
- Can be further fine-tuned on domain-specific corpora for better performance.

## Future Improvements
- Experiment with **BioBERT** or **ClinicalBERT** for enhanced domain-specific performance.
- Implement **active learning** to continuously improve entity recognition.
- Extend the model to support **multi-label classification** for overlapping entities.

## Contributing
Contributions are welcome! Feel free to fork the repository, make changes, and submit a pull request.

## Contact
For any questions or collaborations, feel free to reach out at **ajithkadakam@gmail.com**.


