# Module-Challenge-19: Fintech Finder
## Step 1
### Here we needed to import generate_account, get_balance, and send_transaction from the crypto_wallet.py file, through the code: from crypto_wallet import generate_account, get_balance, send_transaction. Later, this is followed by including the generate_account() function and assigning it to a variable as shown: account = generate_account(). Lastly as part of Step 1, we call the get balance_function with parameters of w3 and account.address, and then display it in the sidebar through the following code: 
### ether_balance = get_balance(w3, account.address)
### st.sidebar.write(ether_balance)
### st.sidebar.markdown("# Client Balance") 

## Step 2 
### We first calculate a wage variable by assigning it to hours * hourly_rate, followed by the streamlit command to write the wage in the sidebar st.sidebar.write(wage). In part 2, in the if st.sidebar.button("Send Transaction") statement, we add a transaction_hash variable assigned to end_transaction(w3, account, candidate_address, wage). Lastly, in the get_people() function at the end of the statement, we add w3 as the internal variable. 

## Step 3
### ![transaction](https://user-images.githubusercontent.com/95319421/167298816-917854be-7158-4b5a-b4dc-44e1762dbc27.PNG)

### ![accounts](https://user-images.githubusercontent.com/95319421/167298830-095d4457-7b74-4ac6-8dcb-10d9a1179ff8.PNG)

### ![blocks](https://user-images.githubusercontent.com/95319421/167298846-781ba8d8-e2c5-456e-b443-935014865963.PNG)
