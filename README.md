                             Hello, world!

this is the famous ML project is simple it not have, like, missing values or something like that
when i test it, starting with this plot, is consider the Hello world of MLE, the iris dataset.
https://www.kaggle.com/datasets/uciml/iris?select=Iris.csv
is about only get a category with some sizes of the flowers, so here we are going

Are too-artificial values normal? The values in the real world—there is more chaos in the
values. Next I find this
there is like an obvious relationship between sepal width and petal width, which kind of
makes super obvious the relationship for any good model like XGBoost or RF is piece of
cake
The only cleaning that I do is LabelEncoder because the models can't use str.
Personally, I like label encoders more than one-hot encoders because they say basically the
same thing without dummy variables. In the most frequent case of gender, doing 2 columns
to say that a random guy is male, the label encoder can have like 999 different objects and
only do 1, so it just looks cleaner and is basically the same.
so i only drop old species column to not have str error and i train a basic train of the model
i start XGBoost because is fast to test and I put a high learning rate because the dataset
have only 151 rows and random estimator

Finally, I test with classification_report (the best way to evaluate classification, lol)

Oh my, a surprise perfect score!
in the real world this means 2 things: you are have a BIG leak or the dataset is not real
As I said before, this dataset is like "Hello, world." How we see it, the data is not real and
have few flowers
So the first project of '22 is finished. If you read this on GitHub, hiiiiii, this is my self-project of
a famous video of some projects
https://www.youtube.com/watch?v=QlbyGPVaRSE&t=213s
My main language is Spanish, and I am learning by myself.
I have some rules, like having a deadline for every project. All need docs in English and
need to be in GitHub.

