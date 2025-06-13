# 🔥 Smoke-Data: A New Behavioral Indicator in Digital Forensics

> Coined by Robert K. McMichen  
> First published: June 2025

---

## 📘 What Is Smoke-Data?

**Smoke-data** is a term used to describe reactive telemetry artifacts and forensic traces left behind not by an initial attack, but by the **attacker’s response to being watched, investigated, or analyzed**.

Where traditional Indicators of Compromise (IOCs) confirm that an attack occurred, **smoke-data appears before, during, or after surveillance is detected — often reflecting tampering, sanitization, or suppression that is *strategically timed*.**

---

## 🔍 Origin of the Term

The term was coined during a forensic investigation into suspected long-term device tampering and surveillance. The pivotal moment came when analytics files appeared **partially preserved but stripped of key identifying fields**, such as:
- `userIdentifier`
- `deviceName`
- `sessionContext`

These fields were not deleted — they were blanked, replaced with “null,” or left as `"UNKNOWN"` — confirming a **deliberate attempt to manipulate log visibility while preserving appearance of normality**.

---

## 💡 Why It Matters

Smoke-data highlights:
- **Live counter-forensics activity**
- **Scripted tampering in analytics**
- The emotional response of adversaries under scrutiny
- Weaknesses in modern detection tools that overlook behavioral anomalies

It provides a framework for:
- 📁 **Behavioral forensics**
- 🔎 **Surveillance detection**
- ⚖️ **Legal cybercrime defense**
- 🧠 **Tool evasion modeling**

---

## 📄 White Paper

📎 [Download the PDF](https://your-upload-url.com/Smoke-Data_WhitePaper_FINAL_RobertKMcMichen.pdf)

Includes:
- Formal definition
- Timeline of discovery
- Examples of tampering
- Use cases and legal relevance

---

## 🛠️ Examples

See the `/examples` folder for:
- Redacted log entries showing smoke-data behavior
- Timing patterns and analytics wipe traces
- Disk write overload events tied to forensic activity

---

## 📣 Community Feedback

Feel free to:
- Open a discussion
- Submit issues
- Propose additional case types

This term is proposed as a **new category in behavioral digital forensics**. It is based on real-world, legally documented events.

---

## 🧾 License

[MIT License](LICENSE)
