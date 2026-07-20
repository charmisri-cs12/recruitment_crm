# 🤖 Agentforce Local Info Agent

A sample Salesforce Agentforce DX project demonstrating how to build AI-powered agents using Agentforce. The Local Info Agent provides guests with local weather updates, local event information, and resort facility hours.

---

## 🚀 Features

- 🌤️ Current Weather Information
- 🎉 Local Event Recommendations
- 🏨 Resort Facility Hours
- 🧠 AI-powered Agent Script
- 🔀 Deterministic Reasoning with If/Else Logic
- 🔄 Flow Control using Available When
- 📝 Mutable Variables
- ⚡ Invocable Apex Actions
- 💬 Prompt Templates
- 🔄 Salesforce Flows

---

## 🛠 Technologies Used

- Salesforce DX
- Agentforce DX
- Salesforce CLI
- Apex
- Flows
- Prompt Templates
- VS Code
- Salesforce Extensions Pack

---

## 📋 Prerequisites

- Salesforce Developer Edition
- Salesforce CLI (`sf`)
- Visual Studio Code
- Salesforce Extensions Pack
- Agentforce DX Extension

---

## 🔑 Login to Salesforce Org

```bash
sf org login web --alias my-de-org --set-default
```

---

## 📂 Project Structure

```
force-app/
│
├── main/
│   └── default/
│       ├── aiAuthoringBundle/
│       ├── classes/
│       ├── flows/
│       ├── promptTemplates/
│       ├── permissionsets/
│       └── permissionSetGroups/
│
├── config/
├── manifest/
├── sfdx-project.json
└── README.md
```

---

## 🧩 Components

| Component | Type | Purpose |
|-----------|------|---------|
| Local_Info_Agent.agent | Agent Script | Defines the Agent |
| CheckWeather | Apex Class | Weather Information |
| CurrentDate | Apex Class | Current Date |
| WeatherService | Apex Class | Mock Weather Service |
| Get_Event_Info | Prompt Template | Local Events |
| Get_Resort_Hours | Flow | Resort Hours |
| Resort_Agent | Permission Set | Agent Permissions |
| Resort_Admin | Permission Set | Admin Permissions |

---

## 🤖 Agent Capabilities

- Check current weather
- Provide local event information
- Return resort timings
- Execute Apex Actions
- Invoke Salesforce Flows
- Use Prompt Templates
- AI-powered conversations

---

## ▶️ Demo Video

Watch the complete project demo here:

🔗 **Demo:**  
https://drive.google.com/file/d/1HVIIvHC11c069TTl4XqVjT55mkuNoshf/view?usp=drive_link

---

## 📸 Project Proof

View screenshots and project proof here:

🔗 **Proof:**  
https://drive.google.com/file/d/1jRDCMYGVP6ecHzKILNqy682-speAflfP/view?usp=drive_link

---

## 📖 Documentation

Complete project documentation:

🔗 **Documentation:**  
https://drive.google.com/file/d/1QoJptVvHOfuoLZuLPBX0q9amyLuzzPcz/view?usp=drive_link

---

## 🧪 Preview the Agent

Open:

```
force-app/main/default/aiAuthoringBundle/Local_Info_Agent/Local_Info_Agent.agent
```

Right-click the file and select:

```
AFDX: Preview This Agent
```

Click **Start Simulation** to interact with the agent before deployment.

---

## 🏗 Create a Scratch Org

```bash
sf org create scratch \
--definition-file config/project-scratch-def.json \
--alias AgentScratchOrg \
--set-default \
--target-dev-hub DevHub
```

---

## 📦 Deploy the Project

```bash
sf project deploy start
```

---

## 📚 Resources

- Agentforce DX Developer Guide
- Salesforce DX Developer Guide
- Salesforce CLI Documentation
- Salesforce Extensions for VS Code
- Agentforce Vibes Extension

---

## 👨‍💻 Author

**Charmi Sri**

- GitHub: https://github.com/charmisri-cs12
  

---

## ⭐ Support

If you found this project helpful, please consider giving it a ⭐ on GitHub.
