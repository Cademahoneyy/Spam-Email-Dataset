# Spam-Email-Dataset
The dataset chosen looks to classify spam emails. This CSV document comprises data on
5172 randomly selected email files, along with their corresponding labels indicating whether
they are classified as spam or non-spam. The CSV file includes 5172 rows, representing
individual emails, with each row containing 3002 columns. The initial column designates the
email name, safeguarding privacy by using numbers instead of recipient names. The final
column contains labels for prediction: 1 denotes spam, while 0 signifies non-spam. The
remaining 3000 columns represent the most prevalent words found in all the emails. Our goal
was to clean the data and find different ways of classifying the spam emails.
During the data cleaning of our email dataset, we had decided to focus on concerns
associated with the first column and NaN values. The initial column, initially comprising email
names anonymized with numbers for privacy reasons, was considered unnecessary to keep for
our data set and was removed. Additionally, we wanted to improve the reliability of our dataset
and any rows containing NaN values were removed. This thorough data cleaning strategy
establishes a more reliable and error-free basis for our dataset, Making it easier to better
understand which emails are spam and which ones are not.
We added a visual confusion matrix diagram to evaluate the performance of a
classification model by summarizing the counts of true positive, true negative, false positive, and
false negative predictions. Our classification data set had ended up with a 97.2% accuracy and
the model predicted 734 non-spam and 301 spam.
