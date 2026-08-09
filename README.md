# Oraculus

**An AI-Powered Voice Scientific Calculator | HarvardX CS50 Final Project**

## Overview
Oraculus is an end-to-end Python desktop application that processes and solves complex mathematical equations through natural voice commands and text input. Built as a capstone project for Harvard's CS50x, it bridges the gap between hardware audio input, Large Language Models, and programmatic math execution.

Instead of relying on rigid, hard-coded keyword triggers, Oraculus uses AI to contextually understand conversational speech and extract accurate mathematical intent.

## Features
* **Real-Time Voice Input:** Captures high-quality audio directly from the user's microphone.
* **AI Speech-to-Text:** Transcribes spoken equations accurately using the OpenAI Whisper API.
* **Intelligent NLP Parsing:** Leverages the Qwen LLM to clean, interpret, and format messy conversational text into strict mathematical syntax.
* **Robust Math Engine:** Safely evaluates advanced algebra, trigonometry, and scientific expressions using SymPy.
* **Graphical Interface:** Provides a clean, accessible desktop GUI built with Tkinter.

## Tech Stack
* **Language:** Python
* **Audio Processing:** `sounddevice`, `scipy`
* **AI & NLP:** OpenAI Whisper API, Qwen LLM
* **Math Execution:** `sympy`
* **Frontend GUI:** `tkinter`
