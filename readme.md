# Data Science Assignment
## Task
Science is a core part of what we do. Can you make a bot which can understand science?

Given a question and 4 possible answers, of which **exactly one** is correct, build a bot to choose the correct option.

The bot should find out the correct answer to the questions in `test.csv`, on which it will be evaluated.

Like any other competition, it is acceptable to use pre-trained models/external open sources of data.


## Data
| Column        | Explanations            						  | Type    |
| ------------- |:-----------------------------------------------:| :------:|
| id            | Question ID   								  | integer |
| question      | The question  								  | text    |
| correctAnswer | The correct answer, one of (A, B, C or D)       | category|
| answerA       | Option A 									      | text    |
| answerB       | Option B 									      | text    |
| answerC       | Option C 									      | text    |
| answerD       | Option D 									      | text    |


## Files
`train.csv` contains the training data, with all of the above columns.
`test.csv` contains all of the above columns except `correctAnswer`. Predict the correct answer to the questions present and submit.
Finally, `sample_submission.csv` contains the sample submission format.


## Submission format
1. The submitted **(.csv)** file will contain 2 columns, `id` and `correctAnswer`.
Example present in `sample_submission.csv`
2. Submit a `Readme` file to explain in detail your assumptions and thinking. Why did you choose to solve problem the way you did.
3. Submit all your code (with detailed documentation) and required libraries. Instructions how to run your code.

## TIP
- We would really suggest you to solve problem by giving your best shot in thinking from NLP fundamentals.