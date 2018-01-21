Linear Classifers
Decision boundaries

For linear classifiers
    When two weights are non-zero -> Decision boundary is line
    When three weights are non-zero -> Decision boundary is plane
    When n weights are non-zero -> Decision boundary is hyper plane

For more general classifiers
    Decision boundaries are more complicated shapes


Evaluating Classficiation Models:
    Error measures fraction of mistakes
        error = number of mistakes/ total number of sentenses
    Best possible value is 0.0

    Accuracy is 
        number of corrects/total number of sentenses
    Best possible value is 1.0

    Error = 1 - accuracy


Types of predictions:
    True label positive and Predicted label positive -> True positive (correct prediction)
    True label negative and Predicted label negative -> True negative (correct prediction)
    True label positive and Predicted label negative -> False negative (wrong prediction)
    True label negative and Predicted label positive -> False positive (wrong prediction)


Confusion matrices: - multi class classification


Learning Curves:
    More the training data lesser the test error (Assuming data has quality)
    test error will never be zero even with infinite data.. This error is called bias

Class probabilities:
    Many classifiers will also provide confidence level
        p(y|x) -> Probability of output y given input x