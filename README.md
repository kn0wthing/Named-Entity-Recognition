# Named-Entity-Recognition

Named entity recognition (NER) is a type of information extraction technique that aids in classifying named entities in text into pre-defined groups, including names of people, organizations, places, expressions of times, amounts, monetary values, percentages, etc. </b> Natural language processing (NLP) uses NER extensively, and it can assist in addressing a wide range of practical inquiries, including the following:
<br>
<ul>1. In which cities did the disaster occur?<br>
2. Was there any mention of specific products in complaints or reviews?<br>
3. Does the post contain the name of the goverment official?<br>
</ul>
<br>

The notebook Main.ipynb implements the standard Named Entity Recogntion using Tensorflow, The model architecture uses standard Embedding Layer,GRU Layer,TimeDistributed Layer and SpatialDropout Layer for regularization<br> and additional TFX API and served a model using Tensorflow-Serve

Dataset can be found on the kaggle
https://www.kaggle.com/datasets/abhinavwalia95/entity-annotated-corpus
