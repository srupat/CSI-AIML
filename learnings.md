## Text Summarization with Transformer Models

#### Two types of text summarization 
- Extractive
- Abstractive

##### Easiest way to summarize
- summarization pipeline
    - from transformers import pipeline
    - just provide a summarization task to it

### Using Pre-trained models
- Google's T5 model
    - various types of models in t5, we are going to choose t5-base

#### Limitations
- limit of 512 tokens
- the model sometimes adds sentences on its own because it is pretrained which may change the context of the text

***

## Decision Tree for Iris Flower Classification

##### Gini Impurity
- measure of randomness(entropy)
- calculated at each step of the decision tree 
- GI = 0(node is pure)
- GI = 1(highly impure or the data points are evenly distributed)

