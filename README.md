# Hanafuda Auto Deposit

Make automated transactions in the form of ETH deposits to certain contracts on the HANA Network.

## Register with HanaFuda (Hana Network)

- Register here : https://hanafuda.hana.network
- 𝗨𝘀𝗲 𝗮𝗰𝗰𝗲𝘀𝘀 𝗰𝗼𝗱𝗲: V4EEV0
- Deposit $1- $2 in BASE network for low gas fees
- Go to dashboard
- Earn points through Grow and Draw Hanafuda
- Make 5,000 transactions to earn 300/hour (to unlock cards and get points).
- Make 10,000 transactions to earn 643 Garden Rewards boxes (to unlock collection cards).

## Features

- Automatically send transactions from multiple addresses
- Track and update nonce for each private key to avoid conflicts when sending transactions.
- Catch exceptions when the transaction fails and handle nonce-related errors (e.g. nonce is too low).
- Provide language options (Vietnamese or English) for users.
- Display transaction status notifications (successful or failed) along with detailed information.
- Calculate and display the completion time of all transactions.

## Module:

- Python 3.7 or later
- `pip` (Python package installer)

## Installation

1. **Clone this repository:**
- Open cmd or Shell, then run the command:
```sh
git clone https://github.com/thog9/Hanafuda-testnet.git
```
```sh
cd Hanafuda-testnet
```
2. **Install Module:**
- Open cmd or Shell, then run the command:
```sh
pip install -r requirements.txt
```
3. **Run:**
- Open cmd or Shell, then run the command:
```sh
python bot.py
```
