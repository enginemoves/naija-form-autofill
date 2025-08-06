# naija-form-autofill
A Chrome extension that autofills online forms with realistic Nigerian data including names, phone numbers, addresses emails, and more. Built for QA engineers and testers working on Nigerian web platforms. Includes a floating autofill button and instant form clearing.

# 🇳🇬 Nigerian Autofill – Chrome Extension

A simple but powerful Chrome extension that **autofills forms** with realistic Nigerian user data for **QA, testing, and form validation purposes**.

## ✨ Features

- ✅ Auto-generates and fills:
  - First Name
  - Last Name
  - Full Name
  - Email Address
  - Nigerian Phone Number
  - Residential Address
  - City, LGA, State, Country
  - Username
  - Date of Birth (DOB)
  - BVN & NIN
  - Postal Code (ZIP)
- ✅ Works on any form – intelligently detects input types
- ✅ Draggable Floating Autofill Button (toggleable)
- ✅ Popup UI with:
  - Autofill Now button
  - Enable/Disable floating button toggle
  - Clear all fields button
- ✅ Supports standard `<input>`, `<select>`, `<textarea>` elements
- ✅ Smart detection using `name`, `id`, `placeholder`, `aria-label`, and `autocomplete`
- ✅ Fully offline – no data is sent to any server
- ✅ Randomized on every click (no repeats unless reloaded)



## 📦 Installation

1. Download the source folder (or clone it)
2. Go to `chrome://extensions`
3. Enable **Developer Mode**
4. Click **Load unpacked**
5. Select the extension folder (`QAFill` or whatever you named it)
6. Extension will appear in your Chrome toolbar


## 🧪 Usage

- Open any form on the web
- Click the **Autofill Now** button in the extension popup to fill the form
- Or enable the **Floating Button** toggle and click the draggable **Autofill** button that appears on the page



## 🧹 Clear Form Fields

Click the **Clear All Fields** button in the popup to instantly wipe all input, textarea, and select fields on the page.



## 💡 Ideal For

- QA Engineers
- Testers
- Developers working with Nigerian forms
- Anyone who needs **realistic and localized test data**

---

## 📁 Folder Structure

```

QAFill/
├── icons/
├── popup/
│   └── popup.html
├── autofill.js
├── content.js
├── popup.js
├── manifest.json
└── README.md

```



## 🛠 Technologies

- HTML/CSS/JS
- Chrome Extension APIs (`scripting`, `storage`, `activeTab`)
- DOM scripting



## 📌 Notes

- This extension is open-source and customizable
- No user data is collected or transmitted
- All logic and data generation happen entirely in the browser



## ✅ Made with ❤️ for Nigerian Testers
Armstrong Prince
Linkedin: https://www.linkedin.com/in/enginemoves/
```

