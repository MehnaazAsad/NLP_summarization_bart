# Welcome to my NLP project repository! :robot::abc:



## Table of Contents

- [:package: Repo Content](#repo-content)
- [:film_strip: Accessing the data](#accessing-the-data)
- [:crystal_ball: Playing with the model](#playing-with-the-model)
- [:pray: Conclusion](#conclusion)



## :wave: Introduction 

This repo contains code for a summarization task performed using the Bart LLM. 

The goal of this project was to fine-tune the model on scientific paper abstracts and have it generate paper titles. 

This code makes use of the `transformers` Python library and tutorials from the awesome [Hugging Face](https://huggingface.co/huggingface){:target="_blank"} community!



## :package: Repo Content <a name = "repo-content"></a>

This repo contains a folder called `src` inside which you can find 4 scripts:

1. `prepare_dataset.ipynb` : This notebook contains code for preparing train, validation and test splits.
2. `modeling.ipynb` : You will find code related to model training in this notebook.
3. `inference.ipynb` : This notebook contains code for model inferencing and hyperparameter tuning using the test set.
4. `app.py` : This script contains code for deploying the model using [gradio](https://gradio.app/).



## :film_strip: Accessing the data <a name = "accessing-the-data"></a>

You can find the dataset used for modeling [here](https://huggingface.co/datasets/mehnaazasad/arxiv_astro_co_ga). It consists of all 3 splits: train, validation and test. The original dataset was obtained from [Kaggle](https://www.kaggle.com/Cornell-University/arxiv) and it contains metadata for papers sourced from arXiv. For the purposes of this project, only the `abstract`,  `title`  and `categories` fields were used. 



## :crystal_ball: Playing with the model <a name = "playing-with-the-model"></a>

Feel free to interact with the model [here](https://huggingface.co/spaces/mehnaazasad/give-me-a-title) and use it to generate a title given your abstract! This Hugging Face space was set up using gradio. 



## :pray: Conclusion <a name = "conclusion"></a>

This project would not have been possible without the [NLP Course](https://huggingface.co/learn/nlp-course/chapter1/1?fw=pt) on Hugging Face that taught me so much about transformers!! I can't stress enough how amazing the documentation is that exists on Hugging Face. :fire: They make it really easy to pick up a model and just get going with all the tutorials, detailed code snippets and explanations available! 

In addition, I found this [article on hyperparameters](https://huggingface.co/blog/how-to-generate) extremely useful when learning about tuning your model and it gave me a good place to start.

This project has gotten me really hyped about the world of LLMs :eyes: and I'm excited to explore this area of ML! :raised_hands:
