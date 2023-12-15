# investmenthcatbot
follow the following steps to make it run on your local host
1. clone repo
2. download any open source model, i am using llama2-uncensored.ggmlv3.q8_0.bin they can be dowloaded from thebloke hugging face repo
3. add the data into the data folder. this can be CSV or anyother form. i am using PDF but you can use others too but make sure when you use something else to change the loader in the main.py to the respective file format.
4. run ingest to create vector store
5. run main.py
6. run command chainlit run main.py 
( make sure to run and install the requirments first)
