# Prerequisite Instructions & Installation Guide (Ubuntu)

😂⚠️ Disclaimer ⚠️😂  

This session may cause:
- Excessive typing ⌨️  
- Broken code 💥  
- Learning 📈  

🍿 Popcorn is not required.  
💻 Laptops are mandatory.



## 🧰 Required Software & Tools

The session/project requires the following:

1. Google Antigravity
2. Node.js (LTS)

5. Git
6. Postman

---

## Installation Guide

Always start by updating your system:

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

sudo apt install antigravity
echo "✅ Installation completed!"


