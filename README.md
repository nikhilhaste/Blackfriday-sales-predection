# Abstract: 

Retail companies recognize the need to analyze and predict their salesand customer behavior against their products and product categories. Our studyaims to help retail companies create personalized deals and promotions for theircustomers, even during the COVID-19 pandemic, through a big data frameworkthat allows them to handle massive sales volumes with more efﬁcient models. Inthis paper, we used Black Friday sales data taken from a dataset on the Kagglewebsite, which contains nearly 550,000 observations analyzed with 10 features:qualitative and quantitative. The class label is purchases and sales (in U.S. dol-lars). Because the predictor label is continuous, regression models are suited inthis case. Using the Apache Spark big data framework, which uses the MLlibmachine learning library, we trained two machine learning models: linear regres-sion and random forest. These machine learning algorithms were used to predictfuture pricing and sales. We ﬁrst implemented a linear regression model and a ran-dom forest model without using the Spark framework and achieved accuracies of68% and 74%, respectively. Then, we trained these models on the Spark machinelearning big data framework where we achieved an accuracy of 72% for the linearregression model and 81% for the random forest model.
