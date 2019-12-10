# toxic_comments

## requirements: 

pandas

numpy

matplotlib

sklearn

tqdm

tensorflow



download glove model from here. https://www.kaggle.com/terenceliu4444/glove6b100dtxt

## how to run

##### start jupyter notebook or lab

jupyter notebook or (jupyter notebook --ip=0.0.0.0 --port=2929)



## NOTE

##### toxic_text_classification.ipynb :

will contains machine learning approach for this problem. it will use scikit-learn's multiclass module for tackle this multi-label classification. manly it convert multi-label to normal classification by converting this problem into multiple classifications. it uses LogisticRegression to classify, 

accuracy is pretty high, i think its because more then 80% data is unlabelled, so algorithm will get more accuracy by predicting more 0s  as output. 

i have used TfIDF for word-embedding  using sk-learn.

##### keras_model.ipynb :

will contains deep learning approach for this problem. it uses tensorflow's keras module to construct.

i have used glove module for embedding,  full model didn't fit on my machine so i tried this custom mini version of glow with 100 D.

in 5 - epoch =  i got acc: 0.97 and loss: 0.05 in training and acc: 0.97 and loss: 0.05 in testing.

in 8 - epoch = i got acc: 0.98 and loss: 0.04 in training and acc: 0.98 and loss: 0.05 in testing.

in 15 - epoch = i got acc: 0.98 and loss: 0.04 in training and acc: 0.98 and loss: 0.05 in testing.



with removing stop words

in 5 - epoch =  i got acc: 0.97 and loss: 0.05 in training and acc: 0.96 and loss: 0.05 in testing.







