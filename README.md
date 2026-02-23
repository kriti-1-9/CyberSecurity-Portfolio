🛡️ Cybersecurity Portfolio

Hi — I’m a cybersecurity enthusiast focused on practical security engineering, digital forensics, and automation.

This repository documents my hands-on work solving Capture The Flag (CTF) challenges, building recovery scripts, and strengthening low-level security concepts through applied practice.

My goal is not just solving challenges — but understanding the underlying systems and engineering resilient solutions.

🔍 Focus Areas

🧠 Digital Forensics (Disk images, logs, file carving)

🔐 Steganography & Data Recovery

🧰 Security Tooling & Automation (Python + Bash)

📊 Log Analysis & Incident Investigation

🧬 Binary & Encoded Data Analysis

📁 Repository Structure  
cybersecurity-portfolio/  
│  
├── picoCTF/  
│   ├── Forensics/  
│   │   ├── Corrupted_file/  
│   │   ├── Disk_1/  
│   │   ├── Flag_in_Flame/  
│   │   ├── Hidden_in_plain_sight/  
│   │   └── Riddle_Registry/  
│  
├── general_skills/  
│  
├── Leetcode_bash_solutions/  
│  
└── automation_scripts/  

🧪 Highlighted Projects
🔥 Flag in Flame (Log Forensics / Data Carving)

Identified Base64-encoded payload hidden in logs

Reconstructed PNG from decoded binary

Carved embedded Zlib stream using binwalk

Wrote a custom Python streaming decompression script to recover truncated compressed data

Demonstrated resilient recovery beyond standard CLI tools

💾 Disk Image Forensics

Analyzed FAT32 raw disk image (.dd)

Investigated partition structure

Understood deleted file remnants

Extracted flag directly from raw disk sectors using strings

Applied forensic methodology over manual browsing

🖼️ Corrupted File (Steganography)

Inspected metadata with exiftool

Decoded Base64-embedded password

Extracted hidden data using steghide

Recovered embedded flag from image container

🛠️ Tools & Technologies

Kali Linux

binwalk

exiftool

steghide

zlib (Python)

strings

grep

Bash scripting

Python scripting

🧠 Engineering Philosophy

I approach security challenges in layers:

Identify surface encoding

Verify file signatures (magic bytes)

Carve embedded data

Handle corruption manually when tools fail

Automate recovery with scripting when necessary

Understanding why something works is more important than just making it work.

🚀 Ongoing Goals

Improve low-level file format understanding

Build reusable forensic automation tools

Strengthen reverse engineering skills

Develop production-ready security scripting habits

📌 Note

All writeups are for educational purposes and reflect my personal learning journey in cybersecurity and digital forensics.