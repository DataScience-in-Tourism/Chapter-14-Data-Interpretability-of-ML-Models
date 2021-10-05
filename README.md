# Chapter 14: Interpretability of Machine Learning Models

## How can one explain machine learning models?

***Urszula Czerwinska***

This is code for "Data Science in Tourism" book, Chapter 14: Interpretability of Machine Learning algorithms.

### Abstract

Machine Learning (ML) or Artificial Intelligence (AI) models have become a common tool in business and research over the past years. Models, for example, assist our decisions on which hotel to book or set the optimal price for a flight ticket based on real-time demand, and recommendation apps advise us where to eat or which sights are worth seeing. However, not all decisions taken by automated systems are easily understandable by human beings. How can one make sure that the model does not encompass unwanted bias or discriminate clients? How can one explain to the CEO that the price should be less than what the concurrence proposes?

In rule-based systems, it is possible to track the coded decision tree and explain that decisions come from a combination of known facts. Machine learning systems use a different strategy, and it is not trivial to define how the system computed the outcome. Fortunately, ML models that are explainable do indeed exist, and there is also active research on how to make unexplainable models interpretable. The most popular methods involve Lime and Shapley values, allowing researchers to identify the importance of the input variables and, in turn, to add an interpretation to the model prediction. In this regard, this chapter will describe how to use interpretability tools with ML models and will also provide intuition on the usefulness and limitations of these tools.

