# Finetune-Pre-Trained-Model-for-Text-Summarization
Experiment with pre-trained model to build Text Summarization Model for summarize Indonesia Article (in this project will be using dataset id_liputan6 by [Fajri Koto](https://huggingface.co/datasets/fajrikoto/id_liputan6))


- Used Pre-Trained Model : indolem/indobert-base-uncased [source] (https://huggingface.co/indolem/indobert-base-uncased)
- Used Dataset : id_liputan6 by [Fajri Koto](https://huggingface.co/datasets/fajrikoto/id_liputan6)
- Finetuning Parameter : 
    - batch_size  = 8
    - learning_rate = 2e-5
    - epoch = 8 (with early stoping)
    - weight_decay = 0.01
- Finetuning Evaluation :
    - Rouge1 : 0.33 (+/- 0.14)
    - Rouge2 : 0.15 (+/- 0.12)
    - RougeL : 0.28 (+/- 0.13)
    - RougeLsum : 0.28 (+/- 0.13)
