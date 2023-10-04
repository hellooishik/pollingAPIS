# POLLING SYSTEM API By coding Ninja

A simple polling system api where anyone can create questions with options and can also add votes to those options.

## Technology I used 
1. Node.js
2. Postman (API Fetching)
3. express
4. Mongodb Compass
5. Morgan JS 

## Getting Started
You can clone my Repository and Setup Postman to see the api Changes Which been GET request
- Clone the repository
git clone https://github.com/hellooishik/pollingAPIS.git
- Type Npm install to install all the required dependencies
- Open "config/mongoose.js" and add MongoDB URI, local or Atlas
- Build and run the project using npm start

- Navigate to `http://localhost:8000/`

## Endpoints

- /questions/create (To create a question)
- /questions/:questionId/options/create (To add options to a specific question)
- /questions/:questionId/delete (To delete a question)
- /options/:optionId/delete (To delete an option)
- /options/:optionsId/add_vote (To increment the count of votes)
- /questions/:questionId (To view a question and it’s options)
- /questions/ (To list down all the questions)
If you like this , make sure to star this repo to give love and support
