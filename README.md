# naivebayes-vs-logreg

This is a simplified reproduction of the paper [On Discriminative vs. Generative classifiers: A comparison of logistic regression
and naive Bayes](https://papers.nips.cc/paper/2001/file/7b7a53e239400a13bd6be6c91c4f6c4e-Paper.pdf) by Andrew Y. Ng and Michael I. Jordan.

The paper - and this code - show how logistic regression (discriminative approach) exhibits better asymptotic performance when compared to a naive bayes clasifier (generative approach), but that, at the same time, naive bayes approaches its asymptotic error faster.
This suggests that a scenario with limited data might be better suited for naive bayes, whereas an abundance of data will lead to better performance using logistic regression.

This exercise was given as an assignment in the course "Machine Learning" by Phil Blunsom and Ani Calinescu at the University of Oxford.
