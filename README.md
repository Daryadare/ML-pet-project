# ML-pet-project
Please note that file 'links.pdf' contains the link to the notebooks 'workfield.ipynb' and 'documentation-flow.ipynb' in Google Colab because of their big size. For convinience the same link's also beign displayed here: [http://bit.do/collab-workfield](https://clck.ru/33gDrn)
 

  Project based on the text spreadsheet. Spreadsheet's statistical and descriprional data was analysed in various ways. After that text was preprocessed an vectorized.
  Several methods (such as elbow method, silhouette coefficient method and others) were used for defining a suitable number of the clasters for the data to be 
categorized in. 
  Then the actual clasterization was made with K-Means clustering. Later on due to the unpleasant metrics values of classification using random forest clusters 
were reanalayzed and redistributed manually which to better results. But they still were dissatisfying. So the gradient boosting, specifically CatBoost, was applyed.
And the results of classification came out quite great.
