# 🐹 Moving to Golang

After some thought, I have decided to switch the Token Monster codebase over to Golang instead of Python. This is because of the following:
* Golang is very fast, ideal for a token grabber.
* The compiled file is smaller in size.
* There are fewer token grabber written in Golang.

If anyone still wants a Python version, I will be releasing a Python one line token grabber shortly after the release of the Golang version of Token Monster.

---

## :alien: Token Monster
An advanced Discord token grabber thats easy to use and extremely reliable.

#### :trophy: Features
- Decently small amount of code.
- No local caching, undectectable.
- Tokens and other data can be sent through a Discord webhook.
- Very Small amount of AV's flag this as a virus.
- Scans 15+ Sources for tokens.
- Gathers most computer data.
- Can easily be obfuscated and packaged into an EXE.
- Determines if alt-accounts are logged into the same PC, and snipes their tokens as well.
- Verifies tokens to prevent request/webhook spam.
- Fetches general information from a user (*username, phone number, etc*).
- Displays a neat embed that gives you all information that you need.

#### 🦊 What about Firefox?
At the moment, grabbing tokens from FireFox is a bit complicated, but I plan to add this soon.

#### :mega: Just a note
I created this sofware for an assingment in my CyberSecurity class. Our job was to create our own malware. I highly discourage using this against someone else. I am responsible for creating it, but not responsible for its use against another user.

#### :coffee: Installation & Usage
1. Download or Clone the files from the repo.
2. Make sure you have Python 3+ on your machine
3. Open the destination folder and run `pip install requests` to install the needed package.
4. Open `main.py` and adjust config values as needed.
5. [ OPTIONAL ] Run `auto-py-to-exe` to compile this program into an EXE.
6. [ TIP ] If you want to compile Token Monster into an EXE, ZIP it to download it on Chrome.

#### :rocket: Where to go from here?
To prevent the further use of token grabbers, I will be working on an anti-token grabber. This will take a while.

#### 🙏 Acknowledgments
Thanks to [Nexuzzzz](https://github.com/Nexuzzzz) for the extra harvesting paths.
