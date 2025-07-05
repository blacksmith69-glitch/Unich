
# 🚀 UNICH - Termux Script

Easily extract and manage your UNICH tokens using this powerful automation script in Termux.

---

## 📥 Step 1: Clone the Repository

Open **Termux** and run:

```bash
git clone https://github.com/blacksmith69-glitch/Unich.git
cd Unich
```

---

⚙️ Step 2: Install Dependencies

Install Node.js and required packages:
```
pkg install nodejs -y
npm install
```

---

🦊 Step 3: Setup Firefox + Greasemonkey

Make sure you have Firefox installed on your phone.

Then, install the Greasemonkey Extension from Firefox Add-ons:

👉 Click here to install Greasemonkey


---

📜 Step 4: Add the UNICH Script in Greasemonkey

1. Open (copy this script)

2. Copy the entire script.

3. Go to Firefox → Tap on the Greasemonkey extension → Create a new script.


4. Paste the copied script and save it.




---

🔐 Step 5: Get Your Token

1. Log in to your UNICH account on Firefox.


2. Wait a few minutes for the extension to fully load.


3. You will see some text saying "Copy" — click and copy that token.




---

📄 Step 6: Save Your Token in Termux

Back in Termux, run:

```
nano token.txt
```

Paste your copied token inside.
👉 One token per line if you're using multiple accounts.

Press CTRL + X, then Y, and hit Enter to save.


---

🌐 Optional: Use Proxy

To use proxies, add them in:
```

nano proxy.txt

```
👉 One proxy per line.


---

▶️ Step 7: Run the Script

Now start the script by running:
```
node index.js
```

---

✅ Done!

Your UNICH token data will now be processed in Termux 🚀
Enjoy and make sure to use it responsibly 🙌

---

