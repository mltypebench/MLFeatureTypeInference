## Benchmark Labeled Data


* data_train and data_test contains the base featurization split of the raw CSV files

* Feature types are indexed as follows:


Numeric: 0,
Categorical: 1,
Datetime:2,
Sentence:3,
URL: 4,
Embedded Numbers: 5,
List: 6,
Not-Generalizable: 7,
Custom Object: 8

* Metadata/ contains the record id and the source details of the raw CSV files.

* Our-Base-Featurization-Split/ contains the additional features extracted from the base featurized files for the ML models

* The raw data files that we used to create the base featurized files is available here for [download](https://drive.google.com/file/d/1ZPZY2wvDvsmnpQBABLz9ZyZRGvkEmo7B/view?usp=sharing).

