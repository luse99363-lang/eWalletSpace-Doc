# How eWalletSpace Works

When you open eWalletSpace, you are presented with a ready-made database of analyzed wallets. This may create the impression that the platform simply collects data from other analytics services.

In reality, this is not the case. All analytics are based on proprietary calculations performed using blockchain data.

### Data Source

eWalletSpace receives data directly from the blockchain. We do not import data from GMGN, DexScreener, Arkham, DEXTools, or any other services. Every new token, every trade, and every wallet is analyzed by our own system. This allows us to calculate metrics that are not available in most existing tools while keeping the database continuously up to date.

### Supported Networks

At the moment, eWalletSpace analyzes three networks:

* Ethereum
* Base
* BNB Smart Chain

Each network operates independently but uses the same analysis engine. The list of supported networks will be expanded in the future.

### What the System Analyzes

When a new token appears, the platform automatically begins analyzing all events related to it.

This includes:

* Buy transactions;
* Sell transactions;
* Token transfers;
* The trading history of every participating wallet.

In other words, if a wallet has traded a new token, information about its trades will be processed by the system.

### How a Wallet Profile Is Built

After processing transactions, the platform gradually builds the trading history of each wallet. For every wallet, the following key metrics are calculated:

* Trading Volume;
* Number of Trades;
* ROI;
* PnL;
* Win Rate;
* Average Potential;
* Average Holding Time;
* Other supporting metrics.

As a result, the user receives not just a wallet address, but a complete trader profile that can be analyzed in just a few minutes.

<figure><img src=".gitbook/assets/3.png" alt=""><figcaption></figcaption></figure>

### Data Updates

The market never stands still. Every new block can change a wallet's statistics. That is why eWalletSpace continuously updates its data.

Whenever a new trade appears:

* The trader's history is updated;
* Their metrics are recalculated;
* If necessary, the wallet becomes available in search;
* If it matches the user's conditions, a notification can be sent through Telegram Alerts.

<figure><img src=".gitbook/assets/4.png" alt=""><figcaption></figcaption></figure>

This ensures that the platform always works with up-to-date information.

### Why the Database Includes Scam Wallets

This is one of the most common questions from new users. The answer is very simple. Because we analyze the entire market. If a wallet performs trades on the supported networks, it will be included in the database.

This includes:

* Regular traders;
* Beginners;
* Snipers;
* Trading bots;
* Arbitrage wallets;
* Scam addresses.

That is why the platform provides filters and sorting tools.

<figure><img src=".gitbook/assets/5.png" alt=""><figcaption></figcaption></figure>

### Why It Is Impossible to Remove All Scam Wallets

Sometimes users suggest keeping only "good" wallets. Unfortunately, this approach does not work. First, it is impossible to automatically determine the quality of every wallet.

Second, the market is constantly changing. Every day, new trading strategies, new bots, and new trading methods appear. If the market is filtered too aggressively, genuinely interesting traders may be removed together with scam wallets.

That is why we use a different approach. We help reduce the amount of manual work, but we do not make decisions for the user.

### Why the Final Decision Always Belongs to the User

No single metric is capable of determining the quality of a trader on its own. A high ROI may simply be the result of one successful trade.

<figure><img src=".gitbook/assets/11.png" alt=""><figcaption></figcaption></figure>

A high Win Rate may be the result of short-term scalping.

<figure><img src=".gitbook/assets/12.png" alt=""><figcaption></figcaption></figure>

Even a high Potential score does not guarantee that a wallet matches your particular trading strategy.

That is why eWalletSpace provides analytical tools rather than ready-made trading signals.

The best results are achieved when users combine the platform's statistics with their own analysis of charts, tokens, and trader behavior.

### Product Philosophy

When developing eWalletSpace, we followed one simple idea. We do not want to replace a trader's experience. We want to eliminate the most routine part of their work.

Finding strong wallets should take minutes, not hours. Everything else—evaluating projects, analyzing charts, and making trading decisions—remains the user's responsibility.

That is why eWalletSpace does not try to tell you which wallet is the "right" one. It simply helps you find the ones that deserve your attention much faster.

### What's Next

Now you understand how the platform obtains its data and why it works the way it does.

In the next chapter, we will move on to practice and show you how to start using eWalletSpace in just a few minutes.

You will learn:

* How to search for wallets;
* Why searching through a token is more effective than searching the entire market;
* How to use filters;
* And how to perform your first trader analysis.
