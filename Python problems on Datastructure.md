# **Python problems on Datastructure**

 **Problem 1: Cryptocurrency Token Data**  
This data structure represents information about different cryptocurrency tokens listed on a decentralized exchange (DEX).

\`\`\`python  
crypto\_tokens \= \[  
    {  
        "name": "Token A",  
        "symbol": "TKA",  
        "blockchain": "Ethereum",  
        "current\_price\_usd": 100.0,  
        "transaction\_history": \[  
            {  
                "date": "2024-01-10",  
                "prices": {  
                    "open": 98.0,  
                    "close": 100.0,  
                    "high": 101.0,  
                    "low": 97.0  
                },  
                "volume": 12000  
            },  
            {  
                "date": "2024-01-09",  
                "prices": {  
                    "open": 97.0,  
                    "close": 98.0,  
                    "high": 99.0,  
                    "low": 96.0  
                },  
                "volume": 15000  
            }  
        \],  
        "supported\_chains": \["Ethereum", "Polygon"\]  
    },  
    {  
        "name": "Token B",  
        "symbol": "TKB",  
        "blockchain": "Binance Smart Chain",  
        "current\_price\_usd": 200.0,  
        "transaction\_history": \[  
            {  
                "date": "2024-01-10",  
                "prices": {  
                    "open": 198.0,  
                    "close": 200.0,  
                    "high": 202.0,  
                    "low": 196.0  
                },  
                "volume": 18000  
            },  
            {  
                "date": "2024-01-09",  
                "prices": {  
                    "open": 196.0,  
                    "close": 198.0,  
                    "high": 199.0,  
                    "low": 195.0  
                },  
                "volume": 17000  
            }  
        \],  
        "supported\_chains": \["Binance Smart Chain", "Avalanche"\]  
    },  
    {  
        "name": "Token C",  
        "symbol": "TKC",  
        "blockchain": "Solana",  
        "current\_price\_usd": 300.0,  
        "transaction\_history": \[  
            {  
                "date": "2024-01-10",  
                "prices": {  
                    "open": 295.0,  
                    "close": 300.0,  
                    "high": 302.0,  
                    "low": 294.0  
                },  
                "volume": 22000  
            },  
            {  
                "date": "2024-01-09",  
                "prices": {  
                    "open": 294.0,  
                    "close": 295.0,  
                    "high": 296.0,  
                    "low": 293.0  
                },  
                "volume": 21000  
            }  
        \],  
        "supported\_chains": \["Solana", "Fantom"\]  
    }  
\]  
\`\`\`

Q1: Read Data    
Task: Display the current price of "Token B".

Q2: Write Data    
Task: Add a new token "Token D" with some initial data to the \`crypto\_tokens\` list.

Q3: Update Data    
Task: Update the current price of "Token C" to 310.0.

Q4: Delete Data    
Task: Remove the transaction history for "Token A" on "2024-01-09".

Q5: Read Nested Data    
Task: Display the closing price of "Token B" on "2024-01-10".

Q6: Update Nested Data    
Task: Change the opening price of "Token A" on "2024-01-10" to 99.0.

Q7: Add Nested Data    
Task: Add a new transaction history entry for "Token C" on "2024-01-11".

Q8: Delete an Item from a List Inside a Dictionary    
Task: Remove "Avalanche" from the supported chains of "Token B".

 **Problem 2: Crypto Investment Portfolio**  
This data structure represents a crypto investment portfolio, including various assets like tokens, stablecoins, and NFTs, along with their holdings and performance metrics.

\`\`\`python  
crypto\_portfolio \= {  
    "investor\_name": "Jane Doe",  
    "portfolio\_id": "JD1234",  
    "assets": {  
        "tokens": \[  
            {  
                "ticker": "ETH",  
                "quantity": 50,  
                "purchase\_price": 2000.00,  
                "current\_price": 2100.00  
            },  
            {  
                "ticker": "BTC",  
                "quantity": 30,  
                "purchase\_price": 40000.00,  
                "current\_price": 41000.00  
            }  
        \],  
        "stablecoins": \[  
            {  
                "identifier": "USDC",  
                "quantity": 10000,  
                "purchase\_price": 1.00,  
                "current\_price": 1.00,  
                "peg\_currency": "USD"  
            }  
        \],  
        "nfts": \[  
            {  
                "name": "CryptoArt 123",  
                "quantity": 1,  
                "purchase\_price": 5000.00,  
                "current\_price": 5500.00  
            }  
        \]  
    },  
    "cash\_holdings\_usd": 10000.00,  
    "investment\_goals": {"retirement": 2035, "education": 2025}  
}  
\`\`\`

Q1: Read Data    
Task: Display the current price of the NFT "CryptoArt 123".

Q2: Write Data    
Task: Add a new token with ticker "ADA", 1000 units, a purchase price of 1.50, and a current price of 1.60 to the tokens in the assets.

Q3: Update Data    
Task: Update the quantity of "ETH" token to 60\.

Q4: Delete Data    
Task: Remove the stablecoin with identifier "USDC" from the stablecoins in assets.

Q5: Read Nested Data    
Task: Display the peg currency of the stablecoin in the portfolio.

Q6: Update Nested Data    
Task: Change the current price of "BTC" token to 41500.00.

Q7: Add Nested Data    
Task: Add a new goal "vacation" set for the year 2028 in the investment goals.

Q8: Delete an Item from a List Inside a Dictionary    
Task: Remove the NFT "CryptoArt 123" from the portfolio.  
 **Problem 3: Blockchain Market Analysis**  
This data structure represents an analysis of blockchain ecosystems, including protocols and their token performance.

\`\`\`python  
blockchain\_analysis \= {  
    "ecosystems": {  
        "DeFi": {  
            "protocols": \[  
                {"name": "Protocol A", "ticker": "PDA", "price\_change": 5.2},  
                {"name": "Protocol B", "ticker": "PDB", "price\_change": \-3.1}  
            \]  
        },  
        "NFTs": {  
            "protocols": \[  
                {"name": "NFT Market A", "ticker": "NMA", "price\_change": 4.0},  
                {"name": "NFT Market B", "ticker": "NMB", "price\_change": 2.5}  
            \]  
        }  
    },  
    "market\_performance": {  
        "Crypto Index": {"change": 1.5},  
        "DeFi Index": {"change": 2.3},  
        "NFT Index": {"change": \-1.2}  
    },  
    "notable\_events": \[  
        ("2024-01-10", "Network Upgrade", "Ethereum completes sharding upgrade"),  
        ("2024-01-15", "Token Launch", "Protocol A launches governance token")  
    \]  
}  
\`\`\`

Q1: Read Data    
Task: Display the price change of "NFT Market B".

Q2: Write Data    
Task: Add a new ecosystem "Layer 2" with one protocol "Layer 2 Protocol A" having a ticker "L2A" and a price change of \-2.0.

Q3: Update Data    
Task: Update the price change of "Protocol A" to 6.0.

Q4: Delete Data    
Task: Remove the "NFT Index" from market\_performance.

Q5: Read Nested Data    
Task: Display the change in "DeFi Index" performance.

Q6: Update Nested Data    
Task: Change the name of "NFT Market A" to "NFT Market Alpha".

Q7: Add Nested Data    
Task: Add a new notable event on "2024-01-20" stating "Partnership", with the description "Protocol B partners with major blockchain".

Q8: Delete an Item from a List Inside a Dictionary    
Task: Remove the first notable event from the list.

 **Problem 4: Cryptocurrency Exchange Rates**  
This data structure tracks cryptocurrency exchange rates relative to a base stablecoin.

\`\`\`python  
crypto\_exchange \= {  
    "base\_currency": "USDT",  
    "exchange\_rates": {  
        "ETH": {  
            "current\_rate": 0.0005,  
            "historical\_rates": \[  
                {"date": "2024-01-10", "rate": 0.00048},  
                {"date": "2024-01-09", "rate": 0.00049}  
            \]  
        },  
        "BTC": {  
            "current\_rate": 0.000025,  
            "historical\_rates": \[  
                {"date": "2024-01-10", "rate": 0.000024},  
                {"date": "2024-01-09", "rate": 0.000026}  
            \]  
        }  
    }  
}  
\`\`\` 

Q1: Read Data    
Task: Display the current exchange rate for ETH.

Q2: Write Data    
Task: Add a new currency "ADA" with a current rate of 0.0015 and two historical rates: 0.0016 on "2024-01-10" and 0.0017 on "2024-01-09".

Q3: Update Data    
Task: Update the current exchange rate of BTC to 0.000027.

Q4: Delete Data    
Task: Remove the historical rates for ETH.  
Q5: Read Nested Data    
Task: Display the exchange rate of BTC on "2024-01-10".

Q6: Update Nested Data    
Task: Change the rate of ETH on "2024-01-10" to 0.00047.

Q7: Add Nested Data    
Task: Add a new historical rate for BTC on "2024-01-11" with a rate of 0.000023.

Q8: Delete an Item from a List Inside a Dictionary    
Task: Remove the historical rate of BTC on "2024-01-09".

 **Problem 5: Crypto Credit Risk Assessment**  
This data structure assesses the credit risk of individuals based on their crypto-related financial profiles.

\`\`\`python  
crypto\_risk\_profiles \= {  
    "individuals": \[  
        {  
            "name": "John Doe",  
            "defi\_score": 750,  
            "staked\_assets": {  
                "eth\_staking": {"amount": 10, "apy": 3.5},  
                "dot\_staking": {"amount": 1000, "apy": 2.8}  
            },  
            "transaction\_history": \[("2024-01-10", "Confirmed"), ("2024-01-01", "Delayed")\]  
        },  
        {  
            "name": "Jane Smith",  
            "defi\_score": 680,  
            "staked\_assets": {  
                "usdc\_lending": {"amount": 5000, "apy": 5.0}  
            },  
            "transaction\_history": \[("2024-01-10", "Confirmed")\]  
        }  
    \]  
}  
\`\`\`

Q1: Read Data    
Task: Display the APY for John Doe's DOT staking.

Q2: Write Data    
Task: Add a new individual "Alice Johnson" with a DeFi score of 720, no staked assets, and no transaction history.

Q3: Update Data    
Task: Update Jane Smith's DeFi score to 700\.

Q4: Delete Data    
Task: Remove the ETH staking entry from John Doe's staked assets.

Q5: Read Nested Data    
Task: Display the latest transaction status of John Doe.

Q6: Update Nested Data    
Task: Change the amount of Jane Smith's USDC lending to 5500\.

Q7: Add Nested Data    
Task: Add a new transaction history entry for John Doe on "2024-01-15" marked as "Confirmed".

Q8: Delete an Item from a List Inside a Dictionary    
Task: Remove the first transaction history entry of Jane Smith.

 **Problem 6: Crypto Hedge Fund Portfolio**  
This data structure represents a crypto hedge fund’s investment portfolio, detailing various types of crypto investments and their performance.

\`\`\`python  
crypto\_hedge\_fund \= {  
    "fund\_name": "Alpha Crypto Investments",  
    "portfolio\_value\_usd": 50000000,  
    "investments": \[  
        {  
            "type": "Tokens",  
            "holdings": \[  
                {"ticker": "ETH", "quantity": 10000, "average\_buy\_price": 2000},  
                {"ticker": "SOL", "quantity": 50000, "average\_buy\_price": 100}  
            \]  
        },  
        {  
            "type": "Stablecoins",  
            "holdings": \[  
                {"coin": "USDT", "amount": 10000000, "apy": 1.5}  
            \]  
        },  
        {  
            "type": "Derivatives",  
            "holdings": \[  
                {"instrument": "Futures", "details": {"underlying": "BTC", "type": "Perpetual", "leverage": 10}}  
            \]  
        }  
    \],  
    "performance\_metrics": {  
        "year\_to\_date\_return": 5.2,  
        "five\_year\_annualized\_return": 7.1  
    }  
}  
\`\`\`

Q1: Read Data    
Task: Display the quantity of "SOL" tokens held in the portfolio.

Q2: Write Data    
Task: Add a new investment type "NFTs" with one holding of an NFT "CryptoPunk 456" valued at 2000000\.

Q3: Update Data    
Task: Update the portfolio value to 51000000\.

Q4: Delete Data    
Task: Remove the "Derivatives" investment from the portfolio.

Q5: Read Nested Data    
Task: Display the APY of the "USDT" stablecoin.

Q6: Update Nested Data    
Task: Change the average buy price of "ETH" tokens to 2100\.

Q7: Add Nested Data    
Task: Add a new token holding for "ADA" with a quantity of 100000 and an average buy price of 1.5.

Q8: Delete an Item from a List Inside a Dictionary    
Task: Remove the first holding (ETH) under the "Tokens" type.

