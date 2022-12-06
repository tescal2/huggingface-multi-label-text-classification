HF's Content Moderation Classification Dataset

Version 1, Updated 12/05/22


DESCRIPTION

The HF's Content Moderation Classification Dataset is constructed by choosing 4 largest classes from the original corpus. Each class contains near equal distributed test samples. The total number of training samples is 75 for training and demo purposes only. 

The file classes.txt contains a list of classes corresponding to each label for content moderation.

The files train.csv and test.csv contain all the training samples as comma-sparated values. There are 3 columns in them, corresponding to class index (1 to 4), title and description. The title and description are escaped using double quotes ("), and any internal double quote is escaped by 2 double quotes (""). New lines are escaped by a backslash followed with an "n" character, that is "\n".


