# Prerequisite Instructions & Installation Guide (Ubuntu)

## 🧰 Required Software & Tools

The session/project requires the following:

1. VSCode
2. Node.js (LTS)

5. Git
6. Postman

---

## Installation Guide

```bash
echo "🔄 Updating system..."
sudo apt update

echo "🟢 Installing Node.js (LTS)..."
curl -fsSL https://deb.nodesource.com/setup_lts.x | sudo -E bash -
sudo apt install -y nodejs npm

echo "🌱 Installing Git..."
sudo apt install -y git

echo "📮 Installing Postman..."
sudo snap install postman
sudo apt remove docker.io docker-compose docker-compose-v2 docker-doc podman-docker containerd runc
sudo apt update
sudo apt install ca-certificates curl gnupg lsb-release -y

sudo install -m 0755 -d /etc/apt/keyrings
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /etc/apt/keyrings/docker.gpg
sudo chmod a+r /etc/apt/keyrings/docker.gpg
echo "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/docker.gpg] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
sudo apt update
sudo apt install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin
sudo docker run hello-world
sudo usermod -aG docker ${USER}

echo "✅ Installation completed!"


```

# Installing VS Code on Ubuntu (.deb Method)

1. **Download the Package**  
   Download the **.deb package** from the [official VS Code download page](https://code.visualstudio.com).

2. **Navigate to Downloads**  
   Open your terminal and move to your Downloads folder:  
   ```bash
   cd ~/Downloads

3. **Install the Package**  
 ```bash
sudo apt install ./code_amd64.deb


