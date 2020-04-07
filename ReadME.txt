STEP-1:-
-- Install docker toolbox from below link
-- https://github.com/docker/toolbox/releases

STEP-2:-
-- Run dockerQuick Start(terminal)
-- Naviate to /docker-compose/--> folder
-- Run the command -> docker-compose -f docker-compose.yml up
    -- The above command runs the docker-compose file and pulls and Executes the images of 'KAFKA','ZOOKEEPER','MYSQL' and 'PYSPARK'. (This Process may take time depends on 
    your internet speed).

STEP-3:-
-- open the Jupyter notebook from the link which is produced in doceker terminal by pyspark-notebook 
   Example-'http://127.0.0.1:8888/?token=af591789fb7bcd73f6c0b211619732280e08e6dc36b2eb26'
-- upload jar files to Jupyter notebook   
-- open the terminal in Jupyter notebook and install jar files which is provided in "jar Folder"
    -- by using 'pysark --jars <jar file name>
    -- and install pip install kafka-python tweepy findspark
-- upload IPYNB files which is provided in IPYNB FOLDER.    

STEP-4:-
-- Run the Folder File-1; File-2; File-3 for Docker-Kafka-Twitter-Streaming
-- Please check the Videos for better understanding.
