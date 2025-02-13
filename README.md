## Installation
```bash
git clone https://github.com/husenxyz30/b-reff
```
### Requirements installation
```bash
cd blockpad-autoref
```
#### Windows and Termux:
```bash
pip install -r requirements.txt
```
## Run the Bot
- Insert your IMAP credentials to .env, example:
```bash
EMAIL_ADDRESS = "youremail@gmail.com"
PASSWORD = "xxxx xxxx xxxx xxxx"
```
- Replace the proxies ```proxies.txt``` to your own proxies, with the format example is like:
```bash
http://127.0.0.1:8080
http://user:pass@127.0.0.1:8080
```
>Only http proxies supported for now
- Windows and Termux:
```bash
python main.py
```

