# picoCTF – Corrupted File

## Challenge Type
Forensics / Steganography

## Description
A corrupted file is provided. The goal is to recover hidden data and extract the flag.

## Tools Used
- Kali Linux
- exiftool
- base64
- steghide
- strings

## Steps

### 1. Inspect metadata

We used:

```bash
exiftool image.jpg