# Automated Conversation Maker


### What is Automated Conversation Maker?
As the name suggest this project tries to implement virtual agents who can communicate on there own. The communication is very basic which is introductory communication when two new people meet. The data used for carrying out the communication is extracted from Facebook using Facebook graph search API.		 

### Installation and Setup

#### 1) Install NLTK		
Install the Stanford NLTK. The NLTK and installation guideline can be found at http://www.nltk.org/install.html		

#### 2) Download Stanford Dependency Parser
Download Stanford dependency parser from link below		
http://nlp.stanford.edu/software/lex-parser.shtml		

<b>After downloading Stanford dependency parser follow the steps below			

<b>1) Locate the src folder in the repository		 
<b>2) On line number 12 there is a following code		

command = r'java -mx1200m -cp "_Path__to_/stanford-parser.jar:" edu.stanford.nlp.parser.lexparser.LexicalizedParser -outputFormat "typedDependencies" _path__to_/edu/stanford/nlp/models/lexparser/englishPCFG.ser.gz ' + filename +' > '+outfile 

replace _Path__to_ with respective paths		

#### 3) Download and install Sqlite3
Download and install sqlite3. Use the following link to download and installation guidelines		
https://www.sqlite.org/download.html		


<b>3) Use the following command to run the program		
<b> 			_python_ _main.py_


