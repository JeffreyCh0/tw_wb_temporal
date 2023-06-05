# tw_wb_temporal
Dataset for paper: A Cross-cultural Examination of Temporal Orientation Through Everyday  Language on Social Media

There are two datasets publicly available:
* Annotated dataset for message level Twitter/Weibo posts.
* Predicted dataset for user level Twitter/Weibo posts.

Annotated datasets have the same schema, those are:

* index: index of rows
* message_id: unique id for posts.
* platform: the platform of origin. Rather Twitter or Weibo.
* message: message of the posts (available upon request)
* future, past, psychological_present, factual_present: annotations for each category.
* to_discrete: discrete value of the annotations.

Predicted datasets have a slightly different schema:

* user_id: unique id for users.
* age: age of the user.
* isFemale: gender of the user. 1: female, 0: male.
* future, past, psychological_present, factual_present: predicted value for each category.


Raw data would be available on request only.
