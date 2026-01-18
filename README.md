# 🛠️ VaultGen: Advanced Password Architect

![Python Version](https://img.shields.io/badge/python-3.8%2B-blueviolet)
![License](https://img.shields.io/badge/license-MIT-green)
![Security](https://img.shields.io/badge/security-entropy--focused-orange)

**VaultGen** is a robust, Python-powered security tool designed to generate high-entropy, unpredictable passwords. Stop using "password123" and start forging cryptographic-grade access keys tailored to your exact specifications.

---

## ✨ Key Features

* **Customizable Complexity:** Fine-tune length and character sets (Uppercase, Numbers, Symbols).
* **Guaranteed Inclusion:** Logic ensures at least one character from every selected category is present.
* **Entropy Shuffling:** Uses professional-grade shuffling to prevent predictable pattern sequences.
* **Clean Interface:** A beautiful, easy-to-read command-line interface with visual feedback.
* **Strength Assessment:** Built-in logic to evaluate the security level of your generated keys.

---

## 🚀 Quick Start

### 1. Prerequisites
Ensure you have Python 3.8 or higher installed on your system.

### 2. Installation
Clone the repository to your local machine:
```bash
git clone [https://github.com/taniishaa/VaultGen.git](https://github.com/taniishaa/VaultGen.git)
cd VaultGen
```

### 3. Usage

```bash
Run the script directly from your terminal:
```

## 🛠️ Technical Breakdown
CipherForge utilizes a "Mandatory Seed" algorithm to ensure security requirements are met before filling the remaining length with random noise.

1. **Pool Construction**: Dynamically builds a character set based on user flags.
2. **Mandatory Seeding**: Specifically selects one of each required type to guarantee complexity.
3. **Random Expansion**: Fills the remaining length using random.choice.
4. **Fisher-Yates Style Shuffle**: Randomizes the final list to eliminate "category-position" bias.

## 📂 Project Structure

```bash
CipherForge/
├── main.py              # The core application logic
├── requirements.txt     # List of dependencies (Standard Library)
├── .gitignore           # Keeps your repo clean of junk files
└── README.md            # You are here!
```

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

1. Fork the Project
2. Create your Feature Branch (git checkout -b feature/AmazingFeature)
3. Commit your Changes (git commit -m 'Add some AmazingFeature')
4. Push to the Branch (git push origin feature/AmazingFeature)
5. Open a Pull Request
