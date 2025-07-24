# Ethical Hacking Notes – Basic Linux and Python Concepts

This document serves as an introduction to a few key concepts relevant in ethical hacking and cybersecurity, including **obfuscation**, **Linux commands**, **file permissions**, and **Python basics**.

---

## A. Obfuscation

**Obfuscation** means intentionally making something harder to understand or interpret — usually code, data, or communication — to protect it from attackers.

### 🐍 Example in Python:
```python
a = "".join([chr(i) for i in [97, 100, 109, 105, 110, 49, 50, 51]])
print("The password is:", a)
