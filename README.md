# M3-W2-D1-Exercise
Sure! Here is a suggested content for your README.md file to describe the MongoDB exercise project:

### README.md

```markdown
# MongoDB In-Class Exercise

## Overview
This project demonstrates the usage of MongoDB with Node.js. It covers the installation, basic operations such as creating a database, inserting documents, querying data, sorting, updating, and deleting records in a MongoDB database.

## Prerequisites
- Node.js installed on your system
- MongoDB installed and running on your system
- Visual Studio Code or any code editor of your choice

## Project Setup

### 1. Clone the Repository
First, head to your remote Github and create a new repository named `m3-w2-d1-exercise`. Copy the repo URL.

Open your terminal or command prompt and navigate to your project directory, then run:
```bash
mkdir MongoDB
cd MongoDB
git clone <your-repo-URL>
```

### 2. Install Dependencies
Ensure you are in the cloned repository directory. Then, install the required dependencies by running:
```bash
npm install
```

### 3. Run MongoDB
Make sure MongoDB is running on your computer. You can start it from your terminal or command prompt.

## Usage

### Initialize the Project
1. Open a bash terminal and navigate to the project directory.
2. Initialize the project with npm:
    ```bash
    npm init
    ```
3. Install the MongoDB driver:
    ```bash
    npm install mongodb --save
    ```

### Performing Operations
Open the `app.js` file and follow the commented instructions to perform various operations on the MongoDB database.

### Running the App
To run the application and perform the MongoDB operations, use the following command:
```bash
node app.js
```

## Operations Included
1. **Connecting to MongoDB and Creating a Database**:
   - Connect to MongoDB server and create a database.

2. **Inserting Documents**:
   - Insert a single document.
   - Insert multiple documents.

3. **Querying Data**:
   - Find one document.
   - Find documents with specific criteria.
   - Sort documents.

4. **Updating Documents**:
   - Update a single document.

5. **Deleting Documents**:
   - Delete a single document.

## Checking the Database
To verify the operations, you can use the MongoDB shell. For example, to display all databases:
```bash
mongo
> show dbs
```
To switch to the `nodemongo` database and display all collections:
```bash
> use nodemongo
> show collections
```

## Conclusion
This exercise helps in understanding the basic operations of MongoDB using Node.js. Follow the steps and uncomment the respective sections in `app.js` to see the results of different database operations.

## License
This project is licensed under the ISC License.
```

Feel free to customize this README further as per your requirements.