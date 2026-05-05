## 🔍 Sherlock

### (A) Working

1. Install required packages:
sudo apt install git python3 python3-pip python3-venv -y

2. Clone the Sherlock repository:
git clone https://github.com/sherlock-project/sherlock.git
cd sherlock

3. Create a Virtual Environment:
python3 -m venv venv
source venv/bin/activate

4. Install Dependencies:
pip install --upgrade pip
pip install .

---


## (B) Scope of Findings
--> Primarily social media footprinting
--> Identifies usernames across platforms like Twitter, Instagram, GitHub, TikTok
--> Supports anonymity through Tor/Proxy

Why Privacy Matters:

--> Prevents IP tracking
--> Avoids detection/blocking from platforms

---


## (C) Relevance
1. Addresses a common OSINT need: username discovery
2. Simple and lightweight
3. Strong community support

---

## 🧠 TheBigBrother

### (A) Working

1. Clone the BigBrother Repository:
apt update
apt install git -y
git clone https://github.com/chadi0x/TheBigBrother.git

2. Install Official Docker Repository
Run these commands one by one:
sudo apt update
sudo apt install ca-certificates curl gnupg -y

sudo install -m 0755 -d /etc/apt/keyrings

curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /etc/apt/keyrings/docker.gpg

echo "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/docker.gpg] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
Install Docker:
sudo apt install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin -y

3. Check installation:

docker compose version
Run the tool (inside TheBigBrother folder):
docker compose up --build

---


## (B) Scope of Findings
--> Broad intelligence gathering across multiple domains
--> Integrates social media, infrastructure, and digital identity intelligence
--> Features include: Crypto wallet analysis, SSL intelligence, Sky Radar (real-time aircraft tracking), Digital footprint analysis (emails, phone numbers, breach correlation), Provides a GUI (Graphical User Interface)

---

