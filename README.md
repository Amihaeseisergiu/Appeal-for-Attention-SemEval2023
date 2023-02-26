# Appeal-for-Attention-SemEval2023


This is the code written by our team **Appeal for attention** for solving the subtask 3 of [Task 3 from the SemEval-2023](https://propaganda.math.unipd.it/semeval2023task3/index.html)  competition,
which focuses on detecting the persuasion techniques used in online news, in a multilingual context. This task is significantly important as it may enable one to identify attempts of manipulation and misinformation, attacks on reputation, persuasive language and logical fallacies in textual data. 

Our solution involves fine-tuning a pre-trained multi-lingual transformer-based model: XLM-RoBERTa-Large. We focused on emphasizing the importance of using augmented and/or
additional training data in influencing the model’s
predictions and performance. 

To do this, we experimented with the following augmentation techniques:

- synonym replacement augmentation 
- translation based augmentation using DeepTranslator API
(*semeval2023_generating_translations_using_DeepTranslator*)

and with the following dataset extension methods:

- extension using a dataset from a [previous competition](https://arxiv.org/pdf/2105.09284.pdf)
- extension using data generated with GPT-3 (*semeval2023_generating_additional_data_with_GPT-3*)





<!-- We have studied different augmentation approaches for [Subtask 3 of SemEval-2023 Task 3](https://propaganda.math.unipd.it/semeval2023task3/index.html) multi-label persuasion techniques classification in a multi-lingual context. The subtask 3 of SemEval-2023 Task 3 focuses on detecting the persuasion techniques used in online news, in a multilingual context. 

We have combined synonym replacement with text translation, an additional dataset used in previous competitions and synthetic data generated using GPT-3.  -->
