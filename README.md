# Predicting Concert Season Subscription Purchases

### Objective
We have received several data files to use in our model. Our goal is to predict whether the patrons listed in the `test.csv` file will purchase subscriptions for the 2014-15 concert season. The target label for this classification task is a probabilistic prediction that a patron will purchase a subscription, rather than a binary outcome, since the evaluation metric for this competition is AUROC.

### Files Description
Below is a summary of the provided files:

- **`train.csv`**: The training dataset containing account IDs of patrons along with a target label (0 or 1), indicating whether they purchased a subscription for the 2014-15 concert season.
- **`test.csv`**: The test set of accounts for which we need to make a prediction.
- **`sample_submission.csv`**: A sample submission file with the correct format for predictions. Ensure that your output file matches this format, including the same column headings.
- **`account.csv`**: Location information for each patron and donation history.
- **`tickets_all.csv`**: Information on previously purchased tickets by account.
- **`subscriptions.csv`**: Information on previously purchased subscriptions by account.
- **`concerts.csv`**: Details about previous concerts by season.
- **`concerts_2014-15.csv`**: A list of planned concert sets for the 2014-15 season.
- **`zipcodes.csv`**: Location and demographic information for various zip codes.

### Output Requirements
Your output should be a file that matches the format of `sample_submission.csv` exactly, including column headings. The submission should consist of "soft predictions" (i.e., your probabilistic estimate of subscription purchases) rather than discrete 0/1 predictions, as the scoring metric for this competition is AUROC.
