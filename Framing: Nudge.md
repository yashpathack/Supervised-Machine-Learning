Let's check this out: 
#### Suppose you want to develop a supervised machine learning model to predict whether a given email is "spam" or "not spam." Which of the following statements are true?
> :heavy_check_mark: __The labels applied to some examples might be untrustworthy.__
Definitely. The labels for this dataset probably come from email users who mark particular email messages as spam. Since very few users mark every suspicious email message as spam, we may have a hard time ever knowing whether an email is spam. Furthermore, some spammers or botnets could intentionally poison our model by providing faulty labels.

> :heavy_check_mark: __Emails not marked as "spam" or "not spam" are unlabeled examples.__
Because our label consists of the values "spam" and "not spam", any email not yet marked as spam or not spam is an unlabeled example.

> :x: __We'll use unlabeled examples to train the model.__ We can then run the trained model against unlabeled examples to infer whether the unlabeled email messages are spam or not spam.

> :x: __Words in the subject header will make good labels__ Words in the subject header might make excellent features, but they won't make good labels.





