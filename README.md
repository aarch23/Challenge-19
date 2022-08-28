
# FINTECH TALENT CONNECTOR

This Python script creates a Streamlit application to assist in hiring and paying FinTech professionals via Ethereum. 

---
## Technologies

This application leverages Python 3.7.2.

---
## Running the Code

* While in your terminal in this cloned repo, enter the following command:

```python
streamlit run fintech_finder.py
```
* A web browser window or tab will open. You will now be able to interact with the application.
---
## Usage

There are two Python scripts contained within this repo: **fintech_finder.py** and **crypto_wallet.py.** The first script runs the Streamlit code and imports various Etherum-based wallet functions from **crypto_wallet.py.**

The application first generates a new Ethereum account instance using the user's mnemonic seed phrase (created during the Installation section of the README.md detailed above). Next, the account balance associated with the user's Ethereum account address is fetched and displayed.

After the user selects their candidate to hire and how many hours they wish to hire them for, the total value of the Ethereum transaction, including the gas fee, is calculated.

The user then digitally signs the transaction to pay the candidate, and sends this transaction to the Ganache blockchain.

A transaction hash code associated with the validated blockchain transaction is generated below in the Streamlit sidebar.

For further confirmation, the user can navigate to the Transactions section of Ganache to review the blockchain transaction details. Here is an example of a successful transaction of this application and the balance deducted from the user's account in Ganache:

![transaction example.] <img width="1187" alt="transaction" src="https://user-images.githubusercontent.com/100783805/187078142-73408de9-c795-4896-815f-fc7dcb87d919.png">
<img width="1195" alt="account" src="https://user-images.githubusercontent.com/100783805/187078175-a3f16069-52c6-4255-8f00-26eec67d9f6f.png">



---
## Contributors

Aarchit Malhotra

---

## License

[BSD 3](https://choosealicense.com/licenses/bsd-3-clause-clear/): BSD 3-clause is a permissive licence, allowing nearly unlimited freedom with the software as long as BSD copyright and license notice is included.
