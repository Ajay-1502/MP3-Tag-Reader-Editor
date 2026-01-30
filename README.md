# 🎵 MP3 ID3 Reader & Editor (C)

A lightweight **command-line MP3 metadata reader and editor** built using **C**, designed to work with **ID3 tags**.

---

## 📌 Overview

**MP3 ID3 Reader & Editor** allows users to read, analyze, and modify MP3 metadata directly from the terminal.  
It supports commonly used ID3 fields and demonstrates core systems-level programming concepts such as binary file handling and byte-level parsing.

---

## 🚀 Features

- ✅ Read MP3 ID3 metadata  
- ✅ Edit and update tag fields  
- ✅ Support for common **ID3v1** fields  
  - Title  
  - Artist  
  - Album  
  - Year  
  - Genre  
  - Comments  
- ✅ Clean and modular C code  
- ✅ Robust file validation and error handling  
- ✅ Beginner-friendly implementation  

---

## 🛠️ Tech Stack

- **Language:** C  
- **Concepts Used:**  
  - File handling (`fopen`, `fread`, `fwrite`)  
  - Struct-based metadata mapping  
  - Byte-level data parsing  
  - Command-line interface design  

---

## 📂 Project Structure

```bash
.
├── src/
│   ├── mp3_reader.c
│   ├── mp3_editor.c
│   └── mp3_header.h
├── README.md
└── sample.mp3
