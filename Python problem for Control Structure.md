**Python problem for Control Structure**

### **LOOPS (Iteration-based problems)**

1. **Daily Gas Fee Average**  
    *Description:* Calculate the average gas fee from a list of daily Ethereum gas fees.  
    *Input:* List of gas fees (e.g., \[30, 40, 35, 50, 45\])  
    *Output:* Average gas fee (e.g., 40.0)

2. **Highest Daily Transaction Count**  
    *Description:* Find the day with the highest number of transactions on a blockchain.  
    *Input:* List of daily transaction counts (e.g., \[1200, 1400, 1350, 1600, 1100\])  
    *Output:* Day with the highest transaction count (e.g., Day 4\)

3. **Find Token Min/Max Price**  
    *Description:* Determine the lowest and highest price of a token over a week.  
    *Input:* List of prices (e.g., \[2.1, 2.5, 2.0, 2.8, 2.6\])  
    *Output:* Min: 2.0, Max: 2.8

4. **Simple Moving Average for Token Price**  
    *Description:* Compute the simple moving average of a token’s price for a given window.  
    *Input:* Prices (e.g., \[1.0, 1.2, 1.3, 1.4, 1.6\]), Window size (e.g., 3\)  
    *Output:* List of moving averages (e.g., \[1.17, 1.3, 1.43\])

5. **Count Profitable Days on DEX**  
    *Description:* Count the number of days a trader had a positive return on a DEX.  
    *Input:* List of daily PnL (e.g., \[0.03, \-0.02, 0.01, 0.04, \-0.01\])  
    *Output:* Number of profitable days (e.g., 3 days)

6. **Average Number of Tokens Held**  
    *Description:* Calculate the average number of tokens held across wallets.  
    *Input:* List of token holdings per wallet (e.g., \[100, 200, 150, 300\])  
    *Output:* Average tokens held (e.g., 187.5)

7. **Wallets Above Holding Threshold**  
    *Description:* Count the number of wallets holding more than 100 tokens.  
    *Input:* List of holdings (e.g., \[50, 150, 120, 80, 200\])  
    *Output:* Number of wallets above threshold (e.g., 3 wallets)

8. **Total Gas Spent by Wallets**  
    *Description:* Calculate total gas used by multiple wallets across transactions.  
    *Input:* List of gas used per wallet (e.g., \[21000, 50000, 32000\])  
    *Output:* Total gas used (e.g., 103000\)

9. **Cumulative Token Airdrop**  
    *Description:* Calculate the total tokens distributed in an airdrop across multiple addresses.  
    *Input:* List of airdrop amounts (e.g., \[50, 75, 100, 25\])  
    *Output:* Total tokens distributed (e.g., 250\)

10. **Average Bridge Fee Across Chains**  
     *Description:* Find the average fee users pay when bridging tokens across chains.  
     *Input:* List of fees (e.g., \[1.2, 0.8, 1.0, 1.5\])  
     *Output:* Average fee (e.g., 1.125)

**CONDITIONAL STATEMENTS (Decision-making problems)**

11. **Token Price Classification**  
     *Description:* Classify a token’s price movement as “Bullish” if it increased, “Bearish” if decreased.  
     *Input:* Previous price (e.g., 2.0), Current price (e.g., 2.3)  
     *Output:* Bullish

12. **Gas Fee Alert System**  
     *Description:* Alert if Ethereum gas fee exceeds a given threshold (e.g., 100 Gwei).  
     *Input:* Gas fee (e.g., 120\)  
     *Output:* "High gas fee alert\!"

13. **Detect Whale Wallet**  
     *Description:* Identify if a wallet is a whale based on token balance (\>10,000 tokens).  
     *Input:* Token balance (e.g., 15,000)  
     *Output:* Whale wallet

14. **Token Transfer Flag**  
     *Description:* Flag a transaction as “Suspicious” if the amount is above 1 million tokens.  
     *Input:* Transfer amount (e.g., 1,200,000)  
     *Output:* Suspicious

15. **DEX Slippage Warning**  
     *Description:* Warn users if the slippage is greater than 5%.  
     *Input:* Slippage percentage (e.g., 6.5)  
     *Output:* "High slippage detected"

16. **NFT Mint Status Check**  
     *Description:* Check if an NFT is sold out or available for mint.  
     *Input:* Total supply (e.g., 10,000), Minted count (e.g., 10,000)  
     *Output:* Sold Out

17. **Stablecoin Health Check**  
     *Description:* Determine if a stablecoin is depegged (if price deviates from $1 by more than ±5%).  
     *Input:* Stablecoin price (e.g., 0.93)  
     *Output:* Depegged

18. **Reward Eligibility**  
     *Description:* Check if a user qualifies for staking rewards (must stake ≥ 500 tokens).  
     *Input:* Tokens staked (e.g., 300\)  
     *Output:* Not eligible

19. **Airdrop Eligibility**  
     *Description:* Check if a wallet is eligible for airdrop (must hold a specific token and have at least 5 transactions).  
     *Input:* Holdings (e.g., 100), Number of transactions (e.g., 6\)  
     *Output:* Eligible

20. **Transaction Fee Efficiency**  
     *Description:* Flag if a transaction fee is greater than 5% of transaction amount.  
     *Input:* Fee (e.g., 3), Transaction amount (e.g., 50\)  
     *Output:* Efficient

