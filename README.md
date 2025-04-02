# Solana-AI-Demo
# Solana AI Analyzer

An AI-powered tool for analyzing security vulnerabilities in Solana smart contracts written in Rust.

## 🎯 Purpose

This tool leverages machine learning to detect common smart contract vulnerabilities automatically. It's designed to assist developers and auditors in identifying high-risk patterns early during the development cycle.

## 🧠 Features

- Detection of:
  - ❌ Missing access control
  - ➗ Unchecked arithmetic
  - 🔐 Hardcoded seeds
  - ⚠️ Dangerous `unwrap()` usage
- FastAPI backend with RESTful API
- Integration with a custom Keras deep learning model
- Designed for Solana's Anchor framework-based contracts

## ▶️ Demo Video

Watch the full demonstration on YouTube:  
📺 [https://youtu.be/rw2thGokEks](https://youtu.be/rw2thGokEks)

Disclaimer:
This tool is for educational and research purposes only. It should not be solely relied upon for smart contract auditing in production environments.
