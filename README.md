# Blockchain based Transparent Donation System for NGOs 
The Blockchain-Based Transparent Donation System for NGOs is a Flask-powered web application that facilitates secure and transparent fund transfers using Ethereum and Web3 technologies. Designed with a philanthropic mission, this platform enables users to donate cryptocurrency to support underprivileged children in need of help from compassionate individuals across the globe.

# Key features include:
- ***Connect Wallet:*** Allows users to connect their wallets with MetaMask.

- ***Get Balance of Wallet:*** Retrieves and displays the balance of the connected wallet.

- ***Transfer Funds:*** Enables users to transfer funds to another Ethereum address. Users need to enter the recipient's address and the transfer amount. Upon successful transfer, a transaction details popup will be displayed with the transaction amount and ID.

- ***QR Code:*** Displays a QR code that can be scanned to access the application using a mobile Ethereum wallet.

# Installation and Setup:

1. **Clone the Repository:**  
   Use the following command to clone the project to your local machine:  
   `git clone https://github.com/Vaswanianmol/Blockchain-based-Transparent-Donation-System-for-NGOs.git`

2. **Open the Main Application File:**  
   Navigate to the project directory and open `app.py`.

3. **Create a Virtual Environment:**  
   Run the following command to create a virtual environment:  
   `python -m venv venv`

4. **Install Dependencies:**  
   Install all the required dependencies using pip:  
   `pip install -r requirements.txt`

5. **Run the Server:**  
   Use the following command to start the server:  
   `./run.sh`

6. **Access the Application:**  
   Open your browser and go to:  
   `http://localhost:5000`  
   The webpage should now be displayed.

# How to Use:
The Payment App offers a user-friendly interface for managing and transferring Ethereum securely. Here’s how users can interact with the application:

1. **Connect Your Wallet:** Start by linking your MetaMask wallet to the application. This step is essential to access blockchain functionalities.

2. **View Wallet Balance:** Once connected, your Ethereum wallet balance is fetched and displayed in real-time using Web3.

3. **Send ETH to Others:** Enter a recipient's Ethereum address and the amount you'd like to send. On successful transfer, a confirmation modal will show:

4. **Amount Sent:** Transaction hash (ID) for reference.

5. **Quick Mobile Access:** A QR code is provided, allowing users to quickly access the application through mobile Ethereum wallet apps by simply scanning the code.
