# technicalTestGameloft
Technical test for the position of BackEnd Python dev. Diane Lantran 11/02/2025.

python libraries to include to run this project :
pip install pymongo
pip install fastapi
pip install pydantic

To run the application : 
1. execute start_mongo.bat
2. execute databaseSetUp.py to configure the database and add the player. If everything is set up properly, you'll see a print : "Player profile inserted!"
3. open main.py in a python IDE
4. make sure to be in the root file of the project and run : uvicorn main:app --reload

You'll see the updated player profile at :
http://127.0.0.1:8000/get_client_config/97983be2-98b7-11e7-90cf-082e5f28d836


If something went wrong with mongod : 
1. reconfigure it by downloading MongoDB Community Server here : https://www.mongodb.com/try/download/community
2. insted of running the .bat file, go to : C:\Program Files\MongoDB\Server\8.0\bin\ (if using the default emplacement on Windows) and run mongod --dbpath C:\data\db (default emplacement)
