# Transformer-Training

Transformer-2-Layer-Attention.ipynb contains the code for 2 layer attention model using iMDB.
Transformer-2-Layer-MLP.ipynb contains the code for 2 layer attention model +MLP layers using iMDB.
Transformer-BERT-Tokenizer.ipynb contains the code for 1 Layer attention but uses BERT tokenizer, the rest of the files use GPT2 tokenizer using iMDB.

Transformer-sweep.ipynb contains the code for 1 layer attention model sweep using wandb using iMDB.
WIKITEXT-600K-Transformer.ipynb contains the code for 1 layer attention model and the dataset is WIKITEXT, we used 600K datapoints.

WIKITEXT-Full-data-Transformer.ipynb contains the code for 1 layer attention model and the dataset is WIKITEXT, we used full datap.

We ran all the experiments using Kaggle.

Transformers have led innovative developments
in language and vision modeling ever since the seminal paper
“Attention is all you need” was published. However, transformers
remain a mystery to their users, acting as a black-box solution
to every problem. Many people are working with transformers
and to apply the power of transformers to their applications
they are experimenting with the hyperparameters and hoping to
achieve better results. This is a major hurdle in the development
of more superior and powerful models since no one clearly
understands how transformers work so well and the internal
functioning is a mystery. Due to this, the improvement of the
models is left to luck. Several attempts have been made to
analyze transformers but have not been able to produce results
that would expose their inner workings. We follow the trail
of Mechanistic Interpretability left by Nelson et. al and try to
provide meaningful interpretations of attention-only transformer
models to identify a portion of the workings of a transformer.
We believe this would be a starting point for a much deeper
analysis of the transformer circuit laying the ground for what
is to come. In this project, we built a transformer from scratch
and attempted to train it in order to understand what the
model has learned by analyzing the attention scores of the model.

More details about the results, refer to the attached report.
