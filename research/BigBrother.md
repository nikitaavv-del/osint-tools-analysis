
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


## (C) Relevance
Covers advanced intelligence domains
Suitable for deep investigations
Less commonly required for everyday OSINT tasks
Smaller community support
