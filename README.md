## Unit 19 Homework: Cryptocurrency Wallet
### Background

You work at a startup that is building a new and disruptive platform called KryptoJobs2Go. KryptoJobs2Go is an application that its customers can use to find fintech professionals from among a list of candidates, hire them, and pay them. As KryptoJobs2Go’s lead developer, you have been tasked with integrating the Ethereum blockchain network into the application in order to enable your customers to instantly pay the fintech professionals whom they hire with cryptocurrency.

In this Challenge, you will complete the code that enables your customers to send cryptocurrency payments to fintech professionals. To develop the code and test it out, you will assume the perspective of a KryptoJobs2Go customer who is using the application to find a fintech professional and pay them for their work.

### What You're Creating
To complete this Challenge, you will use two Python files, both of which are contained in the starter folder.
The first file that you will use is called `krypto_jobs.py`. It contains the code associated with the web interface of your application. The code included in this file is compatible with the Streamlit library. You will write all of your code for this Challenge in this file.
The second file that you will use is called `crypto_wallet.py`. This file contains the Ethereum transaction functions that you have created throughout this module’s lessons. By using import statements, you will integrate the `crypto_wallet.py` Python script into the KryptoJobs2Go interface program that is found in the `krypto_jobs.py` file.
Integrating these two files will allow you to automate the tasks associated with generating a digital wallet, accessing Ethereum account balances, and signing and sending transactions via a personal Ethereum blockchain called Ganache.
Specifically, you will assume the perspective of a KryptoJobs2Go customer in order to do the following:
* Generate a new Ethereum account instance by using the mnemonic seed phrase provided by Ganache.
* Fetch and display the account balance associated with your Ethereum account address.
* Calculate the total value of an Ethereum transaction, including the gas estimate, that pays a KryptoJobs2Go candidate for their work.
* Digitally sign a transaction that pays a KryptoJobs2Go candidate, and send this transaction to the Ganache blockchain.
* Review the transaction hash code associated with the validated blockchain transaction.
Once you receive the transaction’s hash code, you will navigate to the Transactions section of Ganache to review the blockchain transaction details. To confirm that you have successfully created the transaction, you will save screenshots to the README.md file of your GitHub repository for this Challenge assignment.
### Instructions
The steps for this challenge are broken out into the following sections:
* Import Ethereum Transaction Functions into the KryptoJobs2Go Application
* Sign and Execute a Payment Transaction
* Inspect the Transaction on Ganache
#### Step 1: Import Ethereum Transaction Functions into the KryptoJobs2Go Application
#### Step 2: Sign and Execute a Payment Transaction
#### Step 3: Inspect the Transaction
Now it's time to put it all together and test the KryptoJobs2Go application with your newly integrated Ethereum wallet. You will send a test transaction by using the application’s web interface, and then look up the resulting transaction in Ganache. To do so, complete the following steps:
1. From your terminal, navigate to the project folder that contains your `.env` file and the `krypto_jobs.py` and `crypto_wallet.py` files. Be sure to activate your Conda `dev` environment if it is not already active.
2. To launch the Streamlit application, type `streamlit run krypto_jobs.py`.
![stremalit](https://github.com/Seemaaswal7/Module-19/assets/120348854/955b526f-331e-4ca0-bb0b-b28411e7d770)

3. On the resulting webpage, select a candidate that you would like to hire from the appropriate drop-down menu. Then, enter the number of hours that you would like to hire them for. (Remember, you do not have a lot of ether in your account, so you cannot hire them for long!)
 ![Nt2](https://github.com/Seemaaswal7/Module-19/assets/120348854/2694860a-ae46-494a-b58d-c5cec584f964)

4. Click the Send Transaction button to sign and send the transaction with your Ethereum account information. Navigate to the Transactions section of Ganache.
    * Take a screenshot of your address balance and history on Ganache. Save this screenshot to the README.md file of your GitHub repository for this Challenge assignment.
![Nre t1](https://github.com/Seemaaswal7/Module-19/assets/120348854/2c30876c-8871-4ac2-8585-8ab5e5638def)

    * Take a screenshot of the transaction details on Ganache. Save this screenshot to the README.md file of your GitHub repository for this Challenge assignment.
![Newt3](https://github.com/Seemaaswal7/Module-19/assets/120348854/b4d24897-40f0-41cf-8bda-cefb1bb9f21a)

5. Return to the original transaction, and click the transaction’s To address.
![Newt4](https://github.com/Seemaaswal7/Module-19/assets/120348854/bac771e8-69ae-450a-bf24-0ad0ce49a0a3)

* Take a screenshot of the recipient’s address balance and history from your Ganache application. Save this screenshot to the README.md file of your GitHub repository for this Challenge assignment.
 ![Newt2](https://github.com/Seemaaswal7/Module-19/assets/120348854/62cf5dfb-62be-4f6a-8c51-a2f939253bc8)

---
## Submission

* Upload the files for this assignment to your GitHub repository.
* Submit the link to your GitHub repo on Bootcamp Spot.


