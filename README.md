# Prerequisite Instructions & Installation Guide (Ubuntu)

## 🧰 Required Software & Tools

The session/project requires the following:

1. Google Antigravity
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


