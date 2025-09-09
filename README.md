# Python Project 13: WhatsApp Message Automation 💬🤖  

## 📌 Problem Statement:  
Build a Python script that automatically sends WhatsApp messages — ideal for reminders, greetings, or updates.

## 🧠 What You'll Learn:  
- Using pywhatkit for WhatsApp automation  
- Scheduling messages  
- Handling real-time delays and browser automation

## ✅ Python Code:  
```
import pywhatkit

#Send message at a specific time
pywhatkit.sendwhatmsg("+911234567890", "Hello! This is an automated message.", 17, 30)
```

## 📤 What It Does:  
1. Opens WhatsApp Web in browser  
2. Waits till the scheduled time  
3. Sends the message to the specified number

## 🛠️ Requirements:  
bash
pip install pywhatkit


## 🔧 Try Modifying:  
- Send messages instantly with sendwhatmsg_instantly()  
- Send images or files  
- Automate birthday wishes from a list  

## 💡 Use Cases:  
✅ Auto greetings or reminders  
✅ Promotional messages to clients  
✅ Notify team members on project status  

## ⚠️ Note: Requires WhatsApp Web login and active internet connection.
