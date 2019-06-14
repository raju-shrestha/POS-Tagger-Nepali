
POS Tagger For Nepali Text Using Support Vector Machine 
Dataset used:
->Nepali National Corpus(NNC) from NElRALEC(Napali Language Resources and Localization for Education and Communication) contains 14 millions Nepali words.
->Trained with 80,000 lemmatised words collected from Nepali National Monolingual Written Corpus (NNC) annotated mannually using 112 tags.
-> The 80,0000 training sample served as training dataset for automatic tagger
-> 20% (10% + 10%) dataset are used for training and testing purpose.
-> Total Datasize: 684 MB 

Accuracy:
88% for lemmatized words
72% from unprocessed raw text 
  
Steps to run:
1. Place the nnc_updated_ah folder at correct location
2. Run the ParseXMLCorpus.py to parse the tags from Nelralac 
3. Run ExtractFeatures.py to extract the features from tagset
4. Run getFeatures.py to get the extracted features of tagset
5. Run test.py to test the result
6. Run pou-ui.py to dislpy in browser
