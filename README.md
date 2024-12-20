# 🎭 llm_hack: Prompt Injection for Social Engineering

Welcome to the **CANVAS Prompt Injection** project! This repository demonstrates an advanced proof-of-concept for leveraging prompt injection techniques in social engineering contexts. With a focus on blending technical prowess with psychological insights, this tool is designed to educate penetration testers and ethical hackers on how attackers craft convincing payloads to lure unsuspecting targets.

---

## 🚀 Features

- **Dynamic URL Replacement**: Automatically replace embedded URLs with attacker-controlled links.
- **Interactive User Input**: Customize the payloads with target-specific URLs for real-time phishing simulations.
- **Maze Generation Example**: A functional 3D maze visualization to demonstrate how seemingly harmless tools can carry embedded threats.(junk code)
- **Social Engineering Scenarios**: Frameworks for crafting realistic prompts that exploit trust and curiosity.

---

## 📜 How It Works

1. **Core Script**: The `replace_url_in_corpus` function scans a hardcoded corpus and replaces the target URL with user-provided input.
2. **Phishing Campaign Setup**: Use the interactive features to create a convincing lure, such as "You've won a car!" messages in a picture generation.
3. **Prompt Injection Demonstration**: Integrates the replaced URL into seemingly benign code snippets for testing human and system vulnerabilities.

---

## 🕵️‍♂️ Use Case

The provided script includes a playful 3D maze generator and solver to mask its true intent. When the URL is replaced, it can lead to a malicious link while maintaining the façade of harmless content. Ethical hackers can use this for:

- **Phishing Simulations**: Test how users respond to well-crafted lures.
- **Red Team Exercises**: Incorporate prompt injection into social engineering assessments.
- **Educational Demonstrations**: Show the risks of blindly trusting generated content.

---

## ⚠️ Disclaimer

This project is intended for **educational and ethical purposes only**. Unauthorized use of this tool for malicious purposes is strictly prohibited and may violate laws and regulations.

---

## 📂 Example Usage

```cmd
python test.py
Enter a new URL to replace 'https://www.car.com': 192.168.0.1
```

Follow the instructions to provide a replacement URL, generate the updated corpus, and see how an attacker might use this framework in real-world scenarios.

---

### 🔗 Contributions

Feel free to submit pull requests or report issues. Your feedback is invaluable in refining this educational tool.

--- 

Happy hacking (ethically)! 🚀
