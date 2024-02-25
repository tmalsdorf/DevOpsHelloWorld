## Fast API app
This is a simple FastAPI application that defines a single GET endpoint ("/") that returns a JSON response.
### Running 
The fast api application is in a folder called "app" and is named main.py.  
Running the app is as simple as:   
```
uvicorn app.main:app --host 0.0.0.0 --port 8000"
```

This command tells Uvicorn to look for a FastAPI instance named app in the main.py file inside the app directory.
Access the Application: Once the server is running, you can access your application by going to http://127.0.0.1:8000 in your web browser. You should see the JSON response {"message":"Hello, World!"}.

## Notes
If an error occurs when running the app make sure you have the requirements installed by running the following in you python environment:
```
pip install -r requirements.txt
```