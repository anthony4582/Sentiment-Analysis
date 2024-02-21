This script uses a few specific field names in order to execute and should be updated according to your use case. 
The most import pieces of this script are (1) each record needs its own ID, (2) the customer feedback can have a maximum limit of 1,000 words or so or else script will default to neutral.
The script was created in google colab so the upload mechanism will need to be rewritten depending on your application
The roBERTa package which this script uses runs against a deprecated version of python to run. 
