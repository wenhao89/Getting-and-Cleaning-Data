# README

Wen Hao Wong## Description of Original Dataset
Measurements from the acclerometer and gyroscope of Samsung Galaxy SII smartphone were taken when 30 subjects performed six activities (Walking, Walking Upstairs, Walking Downstairs, Sitting, Standing, Laying). Measurements were taken at 50Hz and were "sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window)." Measurements along each axis were reported separately.
A number of mathematical transformations were applied on the raw dataset. These are described in the **features_info.txt** file included with the original dataset. In addition to these transformations, because there were a large number of samples per observation window, additional variables were created to obtain summary figures for each observation (e.g. mean, std, min, max, etc.).
The subjects were split into two groups. The training group consisted of 70% (21) of the subjects. The test group consisted of 30% (9) of the subjects.
The original dataset was divided among multiple text files. Training and test data were in separate files. Additionally, subject and activity labels were also in separate files.
## Tidy Dataset
The tidy dataset consists of observations from both training and test datasets merged together. Descriptive labels of features were added. Subject and descriptive activity indicators were also added to each observation. Select features were retained while the rest were discarded.
## Transformations
* Training and test data were merged.* Descriptive variable labels attached to the columns.* Subject and activity labels were included for each observation.* Activity factors were applied.* Mean and standard deviation of variables in each sample window/observation period were extracted* The mean of each variable was obtained, grouped by activity and subject. These means are reported in the tidy dataset in wide form.