# GitHub Actions CI/CD Pipeline Flask App 
Objective: To Implement a CI/CD workflow using GitHub Actions for a Python application.
GitHub Links: https://github.com/SamDonald-A/flask_app_CI-CD 

# Stage 1: Setup github for pipeline
# Go to Provided Git Link for Forking

<img width="976" height="496" alt="image" src="https://github.com/user-attachments/assets/2fd1a76e-6ed5-403f-bfc3-a43368634c91" />

# Click Fork and continue creating by giving name

<img width="976" height="498" alt="image" src="https://github.com/user-attachments/assets/9e0c7bd6-f0e0-4def-97d5-861d859082ad" />

<img width="976" height="493" alt="image" src="https://github.com/user-attachments/assets/5339e206-ae41-40be-916a-b1d1b4f14e44" />

# Go to the branch and create branch by clicking New Branch

<img width="976" height="497" alt="image" src="https://github.com/user-attachments/assets/ca93e95a-2448-4e54-bc36-910220c22e7d" />

<img width="976" height="492" alt="image" src="https://github.com/user-attachments/assets/4e13d746-125c-410d-ab83-e3c6f317db72" />

<img width="976" height="460" alt="image" src="https://github.com/user-attachments/assets/83d3b3ac-880f-4fa5-bb29-f45a7bccb103" />

<img width="976" height="492" alt="image" src="https://github.com/user-attachments/assets/e49c13da-d6b7-42ab-89ff-7c83588178e4" />

# Then Create main.yml (file name can be anything)

<img width="973" height="219" alt="image" src="https://github.com/user-attachments/assets/574be756-01d5-471f-9c18-a29841cb7c34" />

# Open this in the VS Code by Cloning the repo So that we can Edit easily

<img width="976" height="528" alt="image" src="https://github.com/user-attachments/assets/17e7242e-621a-426c-b501-3f2828693848" />

# Type your CI/CD main.yml file here

# Source Code: https://github.com/SamDonald-A/flask_app_CI-CD/blob/staging/.github/workflows/main.yml 

<img width="976" height="492" alt="image" src="https://github.com/user-attachments/assets/ff874cdd-63aa-4076-9d3e-f47b22f84135" />

# Step 2: Lets setup EC2 instances for staging and production environments

<img width="976" height="292" alt="image" src="https://github.com/user-attachments/assets/9f72e436-c505-4da3-97f0-a1a43137255a" />
<img width="976" height="308" alt="image" src="https://github.com/user-attachments/assets/29f5ae92-548b-4f13-b04a-89a69fea626a" />

# Make sure the Inbound rules are allowing the 8000 Port globally

<img width="976" height="481" alt="image" src="https://github.com/user-attachments/assets/97cd77dd-c532-4ce8-9060-8105680c441b" />

# Go to MongoDB and create connection string

<img width="976" height="493" alt="image" src="https://github.com/user-attachments/assets/6a0201a8-df30-41c6-b59c-d98ce3eeb1c5" />

# Create New Project 

<img width="976" height="498" alt="image" src="https://github.com/user-attachments/assets/1eb43796-3f6d-4192-bdc2-b325cfb31a83" />

# Click Create to create cluster

<img width="616" height="468" alt="image" src="https://github.com/user-attachments/assets/11692048-9b28-4ac4-9920-aa13b8d030f1" />

<img width="976" height="494" alt="image" src="https://github.com/user-attachments/assets/5e8f68a3-22d7-4b8a-b730-ebd3bf4cd3a7" />

# Create user and save the user & password and connection method

# Select Drivers

<img width="688" height="621" alt="image" src="https://github.com/user-attachments/assets/2b0738db-2023-4cae-a8cd-8591c071787a" />

# Select python and Versions

<img width="661" height="566" alt="image" src="https://github.com/user-attachments/assets/80907af0-b122-44db-928d-9b8f260ca9ba" />

# And copy the link and save that provided below and save it

<img width="625" height="559" alt="image" src="https://github.com/user-attachments/assets/e52622a4-8030-4e30-835b-e88437649aee" />

# Go to network access and update the IP

<img width="510" height="593" alt="image" src="https://github.com/user-attachments/assets/81d9e0fd-7d55-4efc-8c86-21e5c15fb1a3" />

# Click Add IP Access

<img width="976" height="261" alt="image" src="https://github.com/user-attachments/assets/c974ecb2-8872-4619-9268-c006e441234e" />

# And Click Allow Access from Anywhere and Click Confirm

<img width="974" height="541" alt="image" src="https://github.com/user-attachments/assets/fb70acc6-dba0-466e-b13a-ca6e827a086c" />

# Use the string to connect with your MongoDB compass – Click New connection 

<img width="976" height="575" alt="image" src="https://github.com/user-attachments/assets/a211489d-1fe5-4b0a-a7ea-196718d444c7" />

# Past your URI – Save and connect

<img width="974" height="539" alt="image" src="https://github.com/user-attachments/assets/864fcead-28d4-447b-92e8-4a5bd09902cf" />

# Mongo Connected and we can see the DB’s in the left menu

<img width="482" height="515" alt="image" src="https://github.com/user-attachments/assets/04c102c6-be62-4377-9949-25e18c59ed45" />

# Step 3: Setup Secret in the Git

# Go to settings and Under secret and variables click Actions

<img width="976" height="518" alt="image" src="https://github.com/user-attachments/assets/c2a0380a-9e31-4617-bcbf-7dc8d8052d1e" />

# Click New repository secret

<img width="976" height="498" alt="image" src="https://github.com/user-attachments/assets/9aaa5a22-d140-40b8-89ba-e059cdc3ac38" />

# Past your both Ec2 IP Address in separate secret also mongo URI and secret

<img width="974" height="487" alt="image" src="https://github.com/user-attachments/assets/30bfe9b8-c0e1-4c8a-a364-8744f1cd4e5b" />

<img width="974" height="659" alt="image" src="https://github.com/user-attachments/assets/f870139b-af1f-4ab2-8a27-6a567e0e688b" />

# And we can use this in YML file for the automation

<img width="743" height="256" alt="image" src="https://github.com/user-attachments/assets/982fc583-3430-47f1-81a1-eb5346dbf2fc" />

# After that commit the changes to the git branch staging

<img width="974" height="490" alt="image" src="https://github.com/user-attachments/assets/54828869-1568-4d30-aa4b-57c491449138" />

# My case – Initially it was failure  

<img width="976" height="457" alt="image" src="https://github.com/user-attachments/assets/7c206523-9b25-448c-b40f-8e2d14b361a1" />

# After debugging the YML and other deployment environment, were able to deploy staging successfully

<img width="976" height="498" alt="image" src="https://github.com/user-attachments/assets/bfb51902-48ec-4c40-8ea3-27a97c358312" />

# We see that the files are copied to the EC2 instance and deployed

<img width="577" height="659" alt="image" src="https://github.com/user-attachments/assets/ed5599d7-c922-4be1-8eb9-9fad659a9be9" />

# Server is running the file

<img width="976" height="501" alt="image" src="https://github.com/user-attachments/assets/87d2e32c-8e96-4ebc-9560-ec6f9c5cd56c" />

# Let’s add the data and check its fully functional

<img width="976" height="494" alt="image" src="https://github.com/user-attachments/assets/0d1614e0-a9c3-404c-b1eb-f1e1df03575a" />

# It’s all working

<img width="976" height="326" alt="image" src="https://github.com/user-attachments/assets/dc8a1efa-9c20-48ac-a24f-b990ac9d722c" />

# We can see the data in the compass as well in the compass

<img width="976" height="391" alt="image" src="https://github.com/user-attachments/assets/5dfbec90-5fe7-4af4-b4a4-b990c90382e4" />


# Pushing the code once again with small change to check the continue integration

<img width="974" height="363" alt="image" src="https://github.com/user-attachments/assets/530862e9-f575-46e9-8478-0165adbefdde" />

<img width="974" height="515" alt="image" src="https://github.com/user-attachments/assets/1175097f-ef39-4bd5-b228-3ea7467a4798" />

<img width="976" height="497" alt="image" src="https://github.com/user-attachments/assets/d5900faf-a03e-4fad-b6ac-c2b9bb84da31" />

# We see it updating instantly

<img width="746" height="221" alt="image" src="https://github.com/user-attachments/assets/3f18646a-1fd6-4069-8df8-1796c8e0f64a" />

# Step 4: Production Deployment 
# Let’s add tag to deploy production – Click Tags in your repo

<img width="816" height="429" alt="image" src="https://github.com/user-attachments/assets/16a1e1d8-0b0b-4436-8727-2c4ae3160101" />

# Click - Create New Release

<img width="976" height="498" alt="image" src="https://github.com/user-attachments/assets/89e72b2c-0090-439d-ad57-0136edde8040" />

# Make sure target is your staging branch

<img width="976" height="501" alt="image" src="https://github.com/user-attachments/assets/72193e27-2a84-42e9-911d-80f4a86fbb72" />

# Create Tags

<img width="976" height="497" alt="image" src="https://github.com/user-attachments/assets/09f7fbab-a054-4f88-bf07-a059a6e55c5e" />

# Tag created -  Now the action must be triggered 

<img width="974" height="347" alt="image" src="https://github.com/user-attachments/assets/53c45fd4-20bd-4015-9940-ad81e0b56343" />

# Deployed to the production server

<img width="976" height="496" alt="image" src="https://github.com/user-attachments/assets/91f3748a-d5e4-4f2f-9b17-f263d4a98e71" />

# Files are copied and server is running

<img width="973" height="279" alt="image" src="https://github.com/user-attachments/assets/88aff750-3a38-47fc-be19-df5af64afe24" />

<img width="976" height="457" alt="image" src="https://github.com/user-attachments/assets/60a86a15-019f-4b92-b49d-b793be3c42ff" />

# The page is also loaded successfully in the production

<img width="976" height="505" alt="image" src="https://github.com/user-attachments/assets/e75874fb-78de-47d8-a3f9-9a22d8a67823" />

# Let’s check once again if the integration is working automatically

<img width="749" height="419" alt="image" src="https://github.com/user-attachments/assets/73cd0479-75db-4c71-8522-03c59ee87c91" />

# Committing the small changes in staging 


<img width="976" height="316" alt="image" src="https://github.com/user-attachments/assets/3b9f5b03-cae5-40fb-80ce-25a527441ce4" />


<img width="976" height="543" alt="image" src="https://github.com/user-attachments/assets/02dec909-96eb-420c-a105-3f36fee2de8c" />


<img width="976" height="548" alt="image" src="https://github.com/user-attachments/assets/a220ec3e-1560-465f-95e1-bc6930cd05e9" />

#  We see the staging is updated instantly with the change

<img width="976" height="543" alt="image" src="https://github.com/user-attachments/assets/7761b467-a46c-49f3-97b0-0b5add71a47f" />

# Go to Got tags and releases and click Draft New Release


<img width="976" height="548" alt="image" src="https://github.com/user-attachments/assets/815ce780-3306-433f-8f26-8f353de5c236" />



<img width="976" height="579" alt="image" src="https://github.com/user-attachments/assets/2f2608be-cacf-447b-b3a8-156b2248587f" />



<img width="976" height="548" alt="image" src="https://github.com/user-attachments/assets/1ec644e3-6d31-4434-bda7-3bfb5d363a6b" />


# We see the Production is updated instantly after add the Tag in git


<img width="976" height="548" alt="image" src="https://github.com/user-attachments/assets/1153a73d-2591-4732-ba3b-6d795f30ed83" />


# Let’s add one more data on check 


<img width="976" height="548" alt="image" src="https://github.com/user-attachments/assets/b640b90f-2ab4-4180-bced-c334af33b77f" />



<img width="976" height="548" alt="image" src="https://github.com/user-attachments/assets/e0ef2dac-e491-49ae-b05f-d21fee5bbf4c" />

# We can Even see that in the MongoDB


<img width="985" height="497" alt="image" src="https://github.com/user-attachments/assets/63dffae4-c77f-4588-beac-82c3b0abcf40" />


Now the CI/CD Pipeline is running Deploying successfully.

---

# Student Registration System

A simple **Flask** web application to manage student records with **MongoDB** as the backend database. Users can **add, view, update, and delete** student details.

---

## Features

* List all students on the home page
* Add a new student
* Update existing student details
* Delete a student with confirmation
* Simple and responsive UI using Bootstrap

---

## Tech Stack

* **Backend:** Python, Flask
* **Database:** MongoDB (via Flask-PyMongo)
* **Frontend:** HTML, Jinja2 templates, Bootstrap 5
* **Environment Variables:** Managed via `.env` file

---

## Setup Instructions

### 1. Clone the repository

```bash
git clone <your-repo-url>
cd <repo-folder>
```

### 2. Create and activate a virtual environment

```bash
python -m venv venv
# Activate venv
# Windows:
venv\Scripts\activate
# Linux / Mac:
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

**`requirements.txt` example:**

```
Flask
Flask-PyMongo
python-dotenv
bson
```

### 4. Configure environment variables

Create a `.env` file in the project root:

```
MONGO_URI=<your-mongodb-connection-string>
SECRET_KEY=<your-secret-key>
```

### 5. Run the application

```bash
python app.py
```

Open your browser at: [http://localhost:8000](http://localhost:8000)

---

## Project Structure

```
project/
│
├── templates/
│   ├── base.html
│   ├── index.html
│   ├── add_student.html
│   ├── update_student.html
│
├── app.py
├── requirements.txt
└── .env
```

---

## Screenshots

**Home Page**
Lists all students with Edit/Delete buttons.
- <img width="1902" height="607" alt="image" src="https://github.com/user-attachments/assets/a58a6a6d-4978-4769-8074-232e4d31e69d" />


**Add Student**
Form to add a new student.
- <img width="1897" height="801" alt="image" src="https://github.com/user-attachments/assets/d65d25c3-ebb5-410a-adb1-e130ad7c5878" />


**Update Student**
Form pre-filled with student details.
- <img width="1905" height="897" alt="image" src="https://github.com/user-attachments/assets/04febf01-879f-431f-ab07-abcfb993acf1" />



---

## Notes

* Make sure MongoDB is running and accessible via the URI in `.env`
* Delete action includes a confirmation page to prevent accidental deletion
* Uses `ObjectId` from `bson` to work with MongoDB document IDs

---

## License

MIT License

---







