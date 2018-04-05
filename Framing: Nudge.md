Let's check this out: 
#### Suppose you want to develop a supervised machine learning model to predict whether a given email is "spam" or "not spam." Which of the following statements are true?
> :heavy_check_mark: __The labels applied to some examples might be untrustworthy.__
Definitely. The labels for this dataset probably come from email users who mark particular email messages as spam. Since very few users mark every suspicious email message as spam, we may have a hard time ever knowing whether an email is spam. Furthermore, some spammers or botnets could intentionally poison our model by providing faulty labels.

> :heavy_check_mark: __Emails not marked as "spam" or "not spam" are unlabeled examples.__
Because our label consists of the values "spam" and "not spam", any email not yet marked as spam or not spam is an unlabeled example.

> :x: __We'll use unlabeled examples to train the model.__ We can then run the trained model against unlabeled examples to infer whether the unlabeled email messages are spam or not spam.

> :x: __Words in the subject header will make good labels__ Words in the subject header might make excellent features, but they won't make good labels.

#### Suppose an online shoe store wants to create a supervised ML model that will provide personalized shoe recommendations to users. That is, the model will recommend certain pairs of shoes to Marty and different pairs of shoes to Janet. Which of the following statements are true?

> :heavy_check_mark: __Shoe size is a useful feature.__ Shoe size is a quantifiable signal that likely has a strong impact on whether the user will like the recommended shoes. For example, if Marty wears size 9, the model shouldn't recommend size 7 shoes.

> :heavy_check_mark: __User clicks on a shoe's description is a useful label.__ Users probably only want to read more about those shoes that they like. User clicks is, therefore, an observable, quantifiable metric that could serve as a good training label.

> :x: __Shoe beauty is a useful feature.__ Good features are concrete and quantifiable. Beauty is too vague a concept to serve as a useful feature. Beauty is probAdoration is not an observable, quantifiable metric. The best we can do is search for observable proxy metrics for adoration.ably a blend of certain concrete features, such as style and color. Style and color would each be better features than beauty.

> :x: __The shoes that a user adores is a useful label.__ Adoration is not an observable, quantifiable metric. The best we can do is search for observable proxy metrics for adoration.




