# Support-Vector-Classification
SVM applied on DonorsChoose Dataset

Under support vector Machine popularly known as SVM has two sub_types Support Vector classifier and Support Vector Regression.

SVC have two forms :
                    * Primal Form (not popular)
                    * Dual Form (mostly used )
                    
Dual Form with linear kernal is similar to Logistic Regression only difference is that it finds a plain which maximize margine ,
the loss which is minimized here is Hing loss.

Dual Form with polynomial kernal which finds a plain in higher dimension (feature get transformed to higher dimension implicitly)
this has two paramater K(x,y) = (x^T . y + c)^d ,c and d ,if we find the right one model performs very good.

Dual Form with RBF kernal is Generalized kernal ,which has two hyper paramater C and gamma.
C is multiplied with Loss .Gamma is like K in KNN

>C is high overfits

>C is low it Under fits 

>Gamma is high it underfits 

>Gamma is low it overfits

When C is high the Margine will be thin and when gamma is high the margine will be smooth.
can use GridSearchCV to find these Hyper paramaters.

# Facing error while loading IPYNB "Sorry, something went wrong. Reload?"

please click the following link https://nbviewer.jupyter.org/github/prassena/Support-Vector-Classification/blob/master/Support%20Vector%20Classifier.ipynb
