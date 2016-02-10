Procedure:
Step 1: After installing all the packages run the tomcat server by double clicking on the "startup.bat" file
	for windows.
Step2: Open Command Prompt and move to the location where "Stanford NER" is installed and paste below command:
	java -mx1000m -cp stanford-ner.jar edu.stanford.nlp.ie.NERServer -loadClassifier classifiers/
	english.muc.7class.distsim.crf.ser.gz -port 8081 -outputFormat inlineXML

Step 3:	Open the "SPYDER" IDE and open file "GetFraudnames_ISO.py" from the attachment.

Step 4: Change "os.environ" variable value with location of excel file which contains text for mining information.

Step 5: Move to RUN menu in the IDE and select "RUN" option or Press F5. 

Step 6: The output of the analysis would be at the Path set up in enviroment variable.
