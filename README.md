# Data Science Nanodegree - Pipelines project

The is the third project of the Data Science Nanodegree course of Udacity.
The scenario is explained bellow:

> Scenario: Fashion Forward Forecasting
> 
> You've recently joined "StyleSense", a rapidly growing online women's clothing retailer, as a data scientist. StyleSense is known for its trendy and affordable fashion, and its customer base has exploded in recent months. This influx of new customers is fantastic for business, but it has created a challenge: a backlog of product reviews with missing data. Customers are still leaving valuable feedback in the text of their reviews, but they aren't always indicating whether they recommend the product.
>
> Your first task at StyleSense is to leverage the existing data– those reviews with complete information – to build a predictive model.
> 
> This model will analyze the text of a review, the customer's age, the product category, and other relevant information to predict whether or not the customer would recommend the product. By automating this process, you'll help StyleSense gain valuable insights into customer satisfaction, identify trending products, and ultimately provide a better shopping experience for their growing customer base.
> 
> The future of fashion forecasting is in your hands!

The instructions are:
1) You will be using the provided data to create a machine learning model pipeline.
2) You must handle the data appropriately in your pipeline to predict whether or not a customer would recommend a product based on the other features. Note the data includes numerical, categorical, and text data.
3) You should ensure you properly train and evaluate your model.

## Getting started

- All the development, from pre-processing to model evaluation, is summarized in the Jupyter notebook `starter/starter.ipynb`. Run all cell in order, that that should be fine.
- The data used in the analysis is stored in `stater/data/reviews.csv`.
- The chosen machine learning model is stored in a pickle file in the `/starter` folder, and it is generated at the end of `starter/starter.ipynb`.

Note that the notebook is commented with the reasoning behind all choices.

## Dependencies

```
pandas
sklearn
matplotlib
seaborn
spacy
numpy
time # for performance
```

Also, you must download `python -m spacy download en_core_web_sm`, if you're not done yet.

## License

[License](LICENSE.txt)
