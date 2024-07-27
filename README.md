# Excel to Firebase Application

## 🛠️ Description
This Python project provides integration to eliminate the need for manual data entry and facilitates the quick and accurate transfer of data from Excel to Firebase. Push thousands of records from Excel to Firebase in minutes.

**Key Feature:**

* **Excel Data Parsing:** This feature parses Excel spreadsheets, extracting structured data to be used in the Firebase Realtime Database. It supports various Excel formats, ensuring compatibility with a wide range of data sources.

## ⚙️ Languages or Frameworks Used
- **Python:** The primary programming language used for the project.
- **Flask:** A micro web framework for Python that is lightweight and easy to use.
- **Pandas:** A popular open-source Python library for data manipulation and analysis.

## 🌟 How to Run
1. **Install all the requirements:**
   - Run `pip install -r requirements.txt` to install all dependencies.

2. **Firebase Setup for the Project:**
   - Create a [Firebase](https://firebase.google.com/) project, set up a web project, and obtain all the `Project Configurations` from `Project Settings`.
   - Navigate to the **Authentication** section in your Firebase project and enable `Email and Password` authentication.
   - Your `Project Configurations` will look like this:
     ```bash
     "apiKey": YOUR_API_KEY,
     "authDomain": YOUR_AUTH_DOMAIN,
     "databaseURL": YOUR_DATABASE_URL,
     "projectId": YOUR_PROJECT_ID,
     "storageBucket": YOUR_STORAGE_BUCKET,
     "messagingSenderId": YOUR_MESSAGING_SENDER_ID,
     "appId": YOUR_APP_ID,
     "measurementId": YOUR_MEASUREMENT_ID
     ```

3. **Setup Environment for the Project:**
   - Create a `.env` file in your project directory and include the following parameters:
     ```bash
     FIREBASE_APIKEY=YOUR_API_KEY
     FIREBASE_AUTHDOMAIN=YOUR_AUTH_DOMAIN
     FIREBASE_DATABASEURL=YOUR_DATABASE_URL
     FIREBASE_PROJECT_ID=YOUR_PROJECT_ID
     FIREBASE_STORAGE_BUCKET=YOUR_STORAGE_BUCKET
     FIREBASE_MESSAGING_SENDER_ID=YOUR_MESSAGING_SENDER_ID
     FIREBASE_APP_ID=YOUR_APP_ID
     FIREBASE_MEASUREMENT_ID=YOUR_MEASUREMENT_ID
     ```

4. **Setup a Virtual Environment:**
   - Run `python -m venv myenv` to create a virtual environment.
   - On Windows, navigate to the virtual environment's Scripts directory: `cd myenv/Scripts`.
   - Activate the virtual environment:
     - On Windows: `activate`
     - On macOS/Linux: `source activate`
   - Move back to your project directory: `cd ..`.
   - Install necessary packages if not present: `uvicorn`, `Flask`, `pandas`, `numpy`, `openpyxl`, `firebase`.

5. **Run the Project:**
   - Execute `python main.py` to start the application.
   - You should see output indicating that the Flask app is running, typically on `http://127.0.0.1:5000/`.
   - Open your web browser and visit the URL specified in the output to access your Flask application.



## 📺 Demo
![Home Page](/Screenshots/1.png?raw=true "Home Page")
![Upload](/Screenshots/2.png?raw=true "Upload")



## References

Github - [OM YADAV](https://github.com/Om25091210)
