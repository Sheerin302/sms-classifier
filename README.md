# sms-classifier
Import pandas as pd import numpy as np from sklearn.feature extraction.text import CountVectorizer from sklearn.model selection import train test split from sklearn.naive bayes import Multinomials
 data pd.read_csv("https://raw.githubusercontent.com/amankharwal/sms-Span-Detection/master/spam.csv", encoding 'latin-1") data.head()
data = data[["class", "message"]]
 x np.array(data["message"])

y np.array(data["class"])
cv CountVectorizer()

Xcv.fit transform(x) # Fit the Data
X train, X test, y train, y test train test split(x, y, test size-0.01, random state-42)
clf MultinomialNB()

clf.fit(x_train,y_train)

MultinomialNe

MultinomialNB()
sample input("Enter a message:")

data cv.transform([sample]).toarray() print(clf.predict(data))

Enter a message: This is the 2nd time we have tried 2 contact ["spam"]
sample input("Enter a message:")

data cv.transform([sample]).toarray()

print(clf.predict(data))

Enter a message: This is the 2nd time we have tried 2 contact ['spam']
Xtrain, x_test, y_train, y_test train_test_split(x, y, test size 0.01, random state 42)
clf MultinomialNB()

clf.fit(X_train,y_train)
MultinomialNg

MultinomialNB()
sample input("Enter a message:')

data cv.transform([sample]).toarray()

print(clf.predict(data))
