# Resume Information Extraction project

## Objective of the script:
<br>
This script intends to implement a naive mechanism for extraction of: Name, Contact Number & Email Id from a collection of resumes and save it systematically in an excel (.xlsx) file.
<br>
<br>
Extraction of phone number and email id: Simple regex is used <br>
Extraction of name: Stanford's NER is used which is currently the SOTA method to achieve Named Entity extraction
<br>
<br>
The performance on the extraction of phone number and email id is fairly accurate and ready to be used/implemented. There remains a slight challenge in the named entity extraction but can be a good starting point for learning and correcting observed errors.  
<br>
<br>
Example of an output file:

![example xlsx output](https://i.imgur.com/mvWecKT.png)

<br>
Some important links and resources: https://nlp.stanford.edu/software/CRF-NER.html#Download (This is the Stanford NER model that needs to be present for the Name identification and extraction)
<br>
Adding Stanford NER classifier and jar to Environemnt Variables: https://blog.manash.me/configuring-stanford-parser-and-stanford-ner-tagger-with-nltk-in-python-on-windows-f685483c374a
