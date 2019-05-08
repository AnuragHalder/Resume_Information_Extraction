# Resume Information Extraction project

## Objective of the script:
<br>
This script intends to implement a naive mechanism for extraction of: Name, Contact Number & Email Id from a collection of resumes and save it systematically in an excel (.xlsx) file.
<br>
<br>
Extraction of phone number and email id: Simple regex is used 
Extraction of name: Standford's NER is used which is currently the SOTA method to achieve Named Entity extraction
<br>
<br>
The performance on the extraction of phone number and email id is fairly accurate and ready to be used/implemented. There remains a slight challenge in the named entity extraction but can be a good starting point for learning and correcting observed errors.  
<br>
<br>
![example xlsx output](https://i.imgur.com/mvWecKT.png)
