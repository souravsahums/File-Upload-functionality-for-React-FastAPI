# Steps to run locally

- Install all required python packages by running the command ```pip install -r requirements.txt``` in terminal.
- Navigate to the folder where '''main.py''' is present, and run this command in command prompt: ```uvicorn main:app --reload```. This will start running the backend in [http://localhost:8000](http://localhost:8000).
- In another terminal navigate to file-demo folder (can use ```cd file-demo```), and run this command: ```npm run start```. This will start running the frontend in [http://localhost:3000](http://localhost:3000).
- Once the web page is up, click on "Choose File" button, select a file, then click on "Upload" button. Upon successful event, you should see a pop-up of "File uploaded successfuly!", and can find the file under the "uploads" folder in the file explorer, else "File upload failed." pop-up will appear.
