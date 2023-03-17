# HealthDapp
HealthDapp is a decentralized application (DApp) that provides a patient-centric system where patients have control over their own data. Patients can decide who can view their profiles and data. The system classifies users into five categories: owner, hospitals, insurance companies, doctors, and patients.

Patients can grant or revoke data access permissions to and from any doctor. They can also add files to their profile, such as reports and X-rays, which will be stored over IPFS. These files can help doctors who have been granted access to review and treat patients accordingly. Patients can also view their past consultation records.

Doctors have the facility to view the patient records to which they have been granted access. They can view their patients' files and previous consultations and provide consultation or treatment accordingly.

![](https://imgs.search.brave.com/-4BwLV_WM3wmY6iDkrFMw2fTgBIHKhp4akt9G3VvWbc/rs:fit:1000:667:1/g:ce/aHR0cHM6Ly9hcnRl/emlvLmNvbS93cC1j/b250ZW50L3VwbG9h/ZHMvMjAxOS8wNS9z/aHV0dGVyc3RvY2tf/MTAzOTQwODM0OC5q/cGc)

# Prerequisites
Truffle v5.1.20

solc v0.5.16

Node v12.16.1 (install following with npm)

antd v3.9.0

axios v0.19.2

bootstrap v4.4.1

bs58 v4.0.1

ipfs-api v26.1.2

react v16.11.0

react-bootstrap v1.0.0

react-dom v16.11.0

react-scripts v3.2.0

web3 v1.2.2
# Installation
Install Metamask as a browser extension
Install Ganache for deployment of contracts
Add truffle-config.js file in Ganache
Create a new network in Metamask with the same port number as in truffle-config.js
Configure Ganache with the same port number
Go to the project directory and run truffle migrate on the command prompt
Go to the 'Client' directory using the prompt and use npm install or yarn install (if your system has yarn)
Run npm start to start the React server
The project will be open in your browser
Import Ganache account(s) in Metamask and use it for user login/register purposes
Execution will start from App.js file in the client directory
