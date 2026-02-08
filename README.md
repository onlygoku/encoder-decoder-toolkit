# Universal Encoder & Decoder Toolkit

## Overview
This project is a Python-based encoder and decoder toolkit designed for security analysis, SOC workflows, DFIR tasks, and CTF practice.

It supports multiple encoding and hashing techniques using only the Python standard library and runs fully offline.

---

## Key Features
- Base64 encode and decode
- Hex encode and decode
- URL encode and decode
- ROT13 encode and decode
- Cryptographic hashing (MD5, SHA1, SHA256)
- Simple auto-detection of encoding format
- JSON output generation
- Modular and extensible design

---

## Project Structure
encoder_decoder_toolkit/
├── codecs/
│ ├── init.py
│ ├── base64_codec.py
│ ├── hex_codec.py
│ ├── url_codec.py
│ ├── rot_codec.py
│ └── hash_codec.py
├── detector/
│ ├── init.py
│ └── auto_detect.py
├── reports/
│ └── output.json
├── main.py
└── README.md

---

## How It Works

### Encoding and Decoding
The toolkit supports common encoding schemes frequently encountered in security investigations such as Base64, Hex, URL encoding, and ROT13.

### Hashing
Hashes are generated using MD5, SHA1, and SHA256 for identification and integrity verification.

### Auto Detection
A simple heuristic-based detector attempts to identify the encoding format of the input text.

---

## Technologies Used
- Python
- base64
- hashlib
- urllib
- codecs
- re
- json

All components use the Python standard library only.

---

## How to Run

From the project root directory:

```bash
python main.py
