# Predicting drug side effects from Twitter
Analyzing data-mined drug and side effect relationships extracted from Twitter to predict adverse side effects of drugs.

<a href="https://github.com/yomnagenina/predicting-drug-side-effects-from-twitter/blob/main/predicting-adverse-side-effects-paper.pdf"><img src="https://user-images.githubusercontent.com/95329530/144175692-d48aaad9-dc54-4887-9894-db312abdeb4a.png"/></a> <a href="https://github.com/yomnagenina/predicting-drug-side-effects-from-twitter/blob/main/predicting-adverse-side-effects-paper.pdf">predicting-adverse-side-effects-paper.pdf</a>

## Abstract
Adverse drug reactions (ADR’s) are among the leading causes of death in the United States. Due to the shortcomings of ADR identification during the drug development process, in
addition to a lack of post-market patient reporting – almost 90% of cases go unreported – exploring alternative sources such as social media platforms with millions of posts per day is growing in popularity.

This paper focuses on analyzing data-mined drug and side effect relationships extracted from Twitter by R. Eshleman and R. Singh [2016, BMC Bioinformatics]. Drug and side effect links from the SIDER database were taken as ground truth. This paper shows that machine learning models trained on Twitter data can predict already known adverse side effects found in SIDER with an accuracy of up to 85%, with a precision and recall of 86% and 90% respectively, leading to and F1 measure of 88%. In addition to that, it was shown that when compared to semantic features, topological features have a higher information gain, providing a stronger capability to distinguish adverse side effects from non-adverse ones. Nevertheless, semantic features increased predictive accuracy by about 3%, and it was shown that effect context features were overall more informative than drug context features.
