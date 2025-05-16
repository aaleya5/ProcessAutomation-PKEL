# ProcessAutomation-PKEL

# 📬 Power Automate Flow: Email Task Extractor 🪄

> Because humans shouldn't manually copy-paste tasks from emails. That's what robots are for. 🤖

---

## 🚀 What is this?

This is a Microsoft Power Automate (Flow) setup that reads incoming emails with a specific subject (`Task`) and magically extracts:

- ✅ Task name  
- 📅 Due date  
- ⏳ Duration  
- 🧑‍💻 Assigned to (default: NULL)  
- 📍 Status (default: Pending)

It then neatly stuffs all of that into an Excel sheet. Like a digital assistant... minus the salary.

---

## 🛠️ How It Works

1. **Trigger**: Listens for new emails with subject containing `Task` (because "Urgent!!!" is just too vague).
2. **HTML Parsing**: Converts the email body to plain text using 🧼 `Html to Text`.
3. **Extraction Logic**: Uses a sprinkle of `Compose` and `Filter` actions to find relevant lines.
4. **Excel Entry**: Plonks the extracted data into a sweet pre-formatted Excel Online table.

---

## 📁 Files Included

| File               | Purpose                                      |
|--------------------|----------------------------------------------|
| `definition.json`  | The brain of the flow 🧠                     |
| `apisMap.json`     | API references for used connectors 🔌       |
| `connectionsMap.json` | Connection IDs (don’t worry, no secrets!) 🔐 |

---

## 🧪 Setup

1. Open Power Automate
2. Import the flow via "Import → Logic App Template"
3. Reconnect your Excel, Office365, and ConversionService connectors
4. Point it to your Excel file and table
5. Trigger an email and watch the magic happen ✨

---

## 🔐 Security Note

Don't worry — all sensitive credentials were scrubbed before upload. This repo is safer than your incognito history.

---

## 💡 Fun Fact

This project was crafted during a caffeine-fueled internship sprint ☕  
Yes, we *did* high-five when it worked on the first try. (Okay, third try. But still.)

---

## 👨‍💻 Author

Built with 💙 by an intern who's clearly a wizard in disguise.

---

## ⭐ Star This Repo

If this made your life easier, star it 🌟  
If it made your day better, star it twice (okay, once is fine).

