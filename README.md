# C++ Regex Examples

This repository includes three simple C++ programs that show how to use **Regular Expressions (Regex)** with the `<regex>` library.  
Each example demonstrates a different way regex can be used in real programs.

All examples work with C++11 or newer.

---

## 📌 1. match_example.cpp  
**What it does:**  
This program checks if a string is in the correct **email format**.  
It uses `regex_match()`, which only returns true if the *entire* string matches the pattern.

**Why it’s useful:**  
You can use this to validate user input (like emails, usernames, etc.) before accepting it.

---

## 📌 2. search_example.cpp  
**What it does:**  
This program looks for a **phone number** inside a longer sentence.  
It uses `regex_search()`, which finds a pattern *anywhere* inside the text.

**Why it’s useful:**  
Good for scanning logs, reading files, or pulling specific information out of a big chunk of text.

---

## 📌 3. replace_example.cpp  
**What it does:**  
This program replaces the word **"cats"** with **"dogs"** in a sentence.  
It uses `regex_replace()` to automatically change any matching text.

**Why it’s useful:**  
This helps with editing text, cleaning data, or fixing formatting issues.

---

## ▶ How to Run the Programs

If you're using g++:

