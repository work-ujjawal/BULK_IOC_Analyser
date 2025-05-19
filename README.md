# BULK_IOC_Analyser

# 🛡️ IOC Reputation Checker using VirusTotal API

This Python-based tool helps cybersecurity analysts bulk-check the reputation of IOCs (Indicators of Compromise) using the [VirusTotal API](https://www.virustotal.com/). Whether you're triaging alerts or deep-diving into incident response, this tool saves time by eliminating repetitive lookups.

---

## 🚀 Features

- Upload a CSV file with IOCs (first row must be `entry`)
- Lookup reputation data from VirusTotal
- Export results to an `.xlsx` Excel file
- Easy GUI interface – no need to touch code
- API key can be provided via text file or manually entered

---

## 🧭 How to Use

1. **Run the Application**
   - Launch the GUI Python script.

2. **Upload the CSV File**
   - Click **Browse** next to **"CSV File"**.
   - The CSV must have a header row containing `**entry**`.

3. **Enter VirusTotal API Key**
   - Click **Browse** to select a `.txt` file containing the API key (no extra text), or type it manually.

4. **Name Your Output File**
   - Provide a name for the output file (no extension needed).
   - Output will be a `.xlsx` file saved in the same directory as the input CSV.

---

## 🌐 Coming Soon: Web-Based Version
No installations. Just open in your browser and go. Stay tuned!

---

## 🤝 Contributing
- Found a bug? Open an issue.
- Want to improve functionality? Fork and submit a PR.
- Suggestions and feedback? Drop me a message or open a discussion!

---

## 🙌 Acknowledgments
Thanks to [VirusTotal](https://www.virustotal.com/) for providing the API that powers this project.
