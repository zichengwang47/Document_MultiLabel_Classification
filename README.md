# Document_MultiLabel_Classification
In this project, I focused on the multi-label classification of research papers from six different fields: Computer Science, Physics, Mathematics, Statistics, Quantitative Biology, and Quantitative Finance. The dataset I used was sourced from the publicly available Kaggle platform. This dataset contained extensive information about each research paper, including its title and abstract.

My approach to the problem involved leveraging advanced Natural Language Processing techniques, specifically using the state-of-the-art Bidirectional Encoder Representations from Transformers (BERT) model. During the data preprocessing stage, I used the BERT tokenizer to efficiently convert the raw text into a format that the model could interpret and effectively learn from.

I enhanced a pre-trained BERT model by adding a custom classification layer, tailored for our multi-label problem. This model was then fine-tuned on the dataset of research papers, leading to improved classification performance.

To evaluate the model, I utilized the Hamming loss, a particularly suitable metric for multi-label classification. This measurement provided an accurate assessment of the model's performance by taking into account both label correctness and completeness. I also employed this performance measurement in the fine-tuning of model hyperparameters. The resultant fine-tuning led to a considerable enhancement in the accuracy of research paper categorization.
