# 🤖 DeepushBot – A Simple Rule-Based Chatbot

DeepushBot is a command-line Python chatbot that uses rule-based logic to answer frequently asked questions about Tamizhan Skills courses. It's a beginner-friendly project designed to help you understand how chatbots work and how AI logic can be implemented using simple Python structures.

---

## 📘 Problem Statement

Students often struggle to understand how chatbots process and respond to messages. This project demonstrates how a simple chatbot can be built using `if-else` or dictionary-based logic to match user input with predefined responses.

---

## 🎯 Objective

Design a **rule-based chatbot** that:
- Accepts user messages
- Detects key topics (like courses, fees, duration)
- Responds with appropriate predefined answers
- Helps beginners understand basic AI response logic

---

## 🛠️ Features

- CLI (Command Line Interface) chat experience
- Keyword-based response system
- Friendly greetings and fallback message
- Easy to modify and expand
- Educational project for learning chatbot logic

---

## 🧠 How It Works

### 🔹 Function: `get_response(message)`
- Converts user input to lowercase
- Checks if any predefined keyword exists in the input
- Returns a matching response from the `response_map` dictionary
- Returns a fallback message if no match is found

### 🔹 Function: `run_deepushbot()`
- Welcomes the user and loops for continuous input
- Exits when the user types `'exit'`
- Calls `get_response()` and prints the reply

---

## 💬 Example Interaction

