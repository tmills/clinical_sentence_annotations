# Clinical Sentence Annotations Repository

This repository contains gold standard annotations for a small corpus of sentence segmentation annotations used in an abstract presented at the 2015 American Medical Informatics Association Symposium.

This data is completely anonymous -- there is no PHI (Protected Health Information) in it -- but is a set of xml files with character offsets into the raw text of the original data. In order to use this for training, you would need a few things:

1) The original MIMIC Corpus, which contains the raw text that these offsets point into
2) Some software to read the anafora xml and put it into a format that you can use to train machine learning models

For more information on obtaining the MIMIC II Corpus see here: http://physionet.org/mimic2/

Software for extracting MIMIC into the correct format and reproducing my experiments will be made public shortly.
