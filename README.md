️ **Please note** that the notebooks **workfield.ipynb** and **documentation-flow.ipynb** are uploaded to this repo but due to their big size they're unable to be displayed within GitHub!

So there is a [pdf file](https://github.com/Daryadare/ML-pet-project/blob/main/link-to-GoogleDrive.pdf) that contains link to the Google Drive where you can save or open them via Google Colab. 

I am also leaving the link outside of document here: [http://bit.do/collab-workfield](https://clck.ru/33gDrn)

---

## 👩🏻‍💻 About project
This project is based on the document flow questions text spreadsheet. The main goal was to divide the initial data into clusters and use them for the later classification on users questions.

---

## Execution steps 🐣
1. Spreadsheet's statistical and descriptive data was analysed in various ways using EDA. 
2. After that the text was preprocessed (transformed to the lower case, cleared of punctuation, stop words, etc.) and vectorized.
3. Several methods (such as `elbow method, silhouette coefficient method` and others) were used for defining a suitable number of clusters for the data to be 
categorized in. 
4. Then the clustering was made using **K-Means algorithm**. 
5. Later on due to the unpleasant metrics results (aren't any higher than 20% accurate) of classification using **Random Forest Classification** clusters 
were manually examined and redistributed which led to the better classification results. 
6. But they still were dissatisfying. So it was decided to implement **gradient boosting**, specifically **CatBoost** library was applied.

And the results of the classification with gradient boosting came out quite great! The final accuracy was about 90%.
