## Introduction

To run this scripts, you will need to have node.js installed on your computer. You can download the latest version of node.js from the official website: https://nodejs.org/.

You will also need to install the required dependencies for these scripts. To do this, navigate to the root directory of the project in your terminal and run the following command:


`npm install`
This will install the dependencies specified in the package.json file.

You will also need to create a .env file in the root directory of the project. This file should contain the following environment variables:


`NODE_URL=<URL of your Inery node>`
`PRIVATE_KEY=<your private key>`
`INERY_ACCOUNT=<your Inery account name>`
`TOKEN_TRANSFER=<number of tokens to transfer>`
Replace the placeholders in angle brackets with the appropriate values for your setup.

Once you have set up your environment and installed the dependencies, you can run the scripts by using the following command:

______________________
## Install Package
```
git clone https://github.com/Herzarika/Inery-Solution.git
```
______________________

## How to Run

```
cd ~/inerysolution
```

#### Create New Data 
```
npm run Create_New_Data
```

#### Read Contract 
```
npm run Read_Crud_Contact
```

#### Update Contract 
```
npm run Update_Crud_Contract
```

#### Create Token 
```
npm run Create_Token
```
#### Transfer Token 
```
npm run Transfer_Token
```

______________________