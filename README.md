# Cyber Magic Toolkit

A single-page, browser-based toolkit for common CTF and cybersecurity tasks: encoding, classical and modern ciphers, steganography, and lightweight file forensics. Everything runs 100% client-side - no servers, no uploads, no tracking.

## Features

### Encoding & Decoding
- **Base64** — Encode and decode standard Base64 text.
- **Hexadecimal** — Convert between text and hex.
- **URL Encoding** — Percent-encode and decode URL-safe strings.
- **Binary** — Translate text to and from binary.
- **ROT13** — Classic letter-rotation cipher.
- **ASCII** — Convert between characters and ASCII codes.
- **Morse Code** — Encode and decode Morse.
- **HTML Entities** — Escape and unescape HTML entities.

### Encryption & Decryption
- **Caesar Cipher** — Shift cipher with configurable offset.
- **Vigenère Cipher** — Keyword-based polyalphabetic cipher.
- **AES Encryption** — Symmetric encryption via CryptoJS.
- **XOR Cipher** — Bitwise XOR with a key.
- **Rail Fence Cipher** — Zig-zag transposition cipher.

### Steganography
- **Image LSB Steganography** — Hide and extract messages in the least-significant bits of image pixels.
- **Text Steganography** — Conceal messages using zero-width characters.

### Forensics
- **EXIF / Metadata Viewer** — Inspect image metadata.
- **File Header Analysis** — Magic-byte detection, hex dump, and printable-strings extraction.

## Getting Started

No build step, no install — just open the file.

Drag `index.html` onto any modern browser window.

## Tech Stack

- **HTML / CSS / Vanilla JavaScript** — no framework, no bundler.
- **[CryptoJS 4.2.0](https://cdnjs.cloudflare.com/ajax/libs/crypto-js/4.2.0/crypto-js.min.js)** — loaded via CDN for AES and hashing primitives.
- **No backend, no dependencies to install** — all computation happens in the browser.

## Privacy

All operations are performed locally in your browser. Files you load for steganography or forensics never leave your device.
