# Python WhatsApp Automator

## 📌 About The Project
This is an automation script written in Python. It allows the user to schedule and send WhatsApp messages automatically at a specific time without manual typing. It is a great way to learn Python automation.

## 🛠️ Built With
* **Language:** Python
* **Library:** `pywhatkit`

## 🚀 How It Works
The script uses `pywhatkit` to open WhatsApp Web in the default browser and sends a specific message to a target number at the time you choose.

### ⚠️ Important Notes for Users:
1. You must be logged into WhatsApp Web in your default browser before running the script.
2. The scheduled time must be at least 2 to 3 minutes in the future, or the script will fail.
3. The phone number must include the country code (e.g., +212 for Morocco).

## 💻 Code Example
```python
import pywhatkit

# Sends "Hello" to the number +212600000000 at 19:15 (7:15 PM)
pywhatkit.sendwhatmsg("+212600000000", "Hello", 19, 15)