# 🔐 CRYPTO-VAULT

A browser-based password strength analyzer that calculates entropy, estimates brute-force crack times, and detects common breached passwords. Built to demonstrate practical cryptography and threat modeling concepts.

## 🚀 Live Demo

**[Try it here](https://adamanuhu-star.github.io/crypto-vault)**

## 📊 Features

| Feature | Description |
|---------|-------------|
| **Entropy Calculator** | Real-time Shannon entropy calculation in bits |
| **Crack Time Estimator** | Brute-force duration at 100 billion guesses/second |
| **Breach Detection** | Flags passwords found in common breach databases |
| **Character Analysis** | Visual breakdown of character types used |
| **Password Generator** | One-click strong password generation |
| **Security Feedback** | Actionable recommendations for improvement |

## 🛠️ Tech Stack

- **Frontend:** HTML5, Tailwind CSS
- **Logic:** Vanilla JavaScript (no frameworks)
- **Security:** Client-side only — no data leaves your browser

## 🎯 Cryptography Concepts Demonstrated

- **Entropy:** Measuring password randomness using `log₂(poolSize ^ length)`
- **Key Space:** Total possible combinations based on character pool size
- **Offline Brute-Force:** Assumes attacker has password hash and unlimited compute
- **Password Hygiene:** Why length beats complexity for memorability

## 🚀 Getting Started

1. Clone the repository
2. Open `index.html` in any modern browser
3. No build step or server required

## 📁 Project Structure
