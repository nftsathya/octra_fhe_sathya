# Octra terminal client - How to install and run transactions (step by step)

## 1.  Open terminal in gitpod and install Python

```bash
sudo apt install python3 python3-pip python3-venv python3-dev -y
```

## 2.  Run these commands :

```bash
git clone https://github.com/octra-labs/octra_pre_client.git
cd octra_pre_client
python3 -m venv venv
source venv/bin/activate # for windows use: venv\Scripts\activate
pip install -r requirements.txt
cp wallet.json.example wallet.json
```

## 3.  Open wallet.json 
```bash
nano wallet.json
```

## 4.  Edit it (change placeholders to your wallet data):

```json
{
  "priv": "private-key-here",
  "addr": "octxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx",
  "rpc": "https://octra.network"
}
```

## 5.  Run to open frontend UI to make transaction

```bash
./run.sh
```

## 6.  Now you can send transaction to other wallets, Some of my address given below to make transactions...

octAiVmSKRY8dT1kbw5VFLu6xRmxaKcxfNrzYMAVGNXbHnE

octFSbsiNmMZ5B5NJCh6tzfphVZ6p8LEP5dBd8x9jVWP1JP

octHyHaL53U2oNLZMSqFfWWckzEFYX49VK6Xp3YVzkUfTqT

oct7TYAaRX9pdTv1TYEn7XsnUuku95Gr9WTjhkukxexHsys

oct419SqtxrgXLyAuUybPKRMAniDMuAzy7kBQ5bFYubDwKt

octFjXfCRgWYpnnmNLLbVvzA1U8pbQEFZtFQRnjmNiUNvor

## 7.  verify your transaction history on https://octrascan.io

