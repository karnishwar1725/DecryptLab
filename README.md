🔐 Cryptography & Digital Forensics Analysis

⸻

📌 Overview

This project demonstrates the application of cryptography, hash analysis, and steganography techniques in a digital forensic context.

The investigation uses practical tools to:
	•	Decrypt ciphertext
	•	Crack hashed values
	•	Extract metadata from images
	•	Analyze hidden data in files

👉 As explained in the introduction (page 3), the work combines multiple forensic techniques to simulate real-world cybersecurity investigations  ￼

⸻

🎯 Objectives
	•	Apply cryptanalysis techniques to decode encrypted messages
	•	Identify and crack hash values
	•	Extract hidden information from multimedia files
	•	Use industry tools for forensic analysis

⸻

🛠️ Tools & Technologies
	•	CyberChef – Cryptography & data transformation
	•	Kali Linux – Forensic environment
	•	Audacity – Audio analysis
	•	ExifTool – Metadata extraction
	•	CrackStation – Hash cracking

⸻

🧩 Tasks Breakdown

⸻

🔤 Task 1 – Substitution Cipher Decryption
	•	Cipher type: Simple substitution cipher
	•	Technique:
	•	Frequency analysis
	•	Pattern recognition (e.g., common words like “the”)
	•	Tool used: quipqiup

✅ Result: Decrypted paragraph (literary text)

👉 Page 3 shows the decoded output and tool usage for solving substitution cipher  ￼

⸻

🔄 Task 2 – ROT Cipher Decryption
	•	Cipher type: ROT (Caesar shift)
	•	Clue: Shift between 3–6
	•	Method:
	•	Used CyberChef with reverse rotations (-3, -4, -5)

ROT -3 / -4 / -5

✅ Result:
	•	Decoded academic text about cybersecurity learning

👉 CyberChef screenshots (pages 4–5) show step-by-step decoding process  ￼

⸻

🔑 Task 3 – Hash Identification & Cracking
	•	Hash identified using CyberChef
	•	Cracked using CrackStation

✅ Result:

examtime

👉 As shown on page 7, the hash was identified (likely SHA-1) and successfully reversed  ￼

⸻

🖼️ Task 4 – Image Metadata Analysis
	•	Tool used:

exiftool gps2.jpg

🔍 Extracted Data:
	•	📷 Camera: Nikon COOLPIX P6000
	•	📅 Date: 2008-10-23
	•	🌍 Coordinates:
	•	Latitude: 43°28’1.76” N
	•	Longitude: 11°53’7.42” E

👉 Pages 8–9 show metadata extraction and GPS mapping of the image location  ￼

⸻

🎧 Task 5 – Audio / Hidden Data Analysis
	•	Focus: Extract hidden information from audio files
	•	Tool: Audacity

👉 The final section (page 9) indicates analysis of multimedia data for hidden content  ￼

⸻

🧠 Key Learnings
	•	Practical use of:
	•	Cryptographic techniques
	•	Hash cracking methods
	•	Metadata forensics
	•	Importance of:
	•	Pattern recognition
	•	Tool selection in investigations
	•	Understanding how:
	•	Small clues lead to complete solutions

⸻

🚀 How to Reproduce
	1.	Open CyberChef
	•	Apply ROT / substitution decoding
	2.	Identify hash:
	•	Use CyberChef → “Analyse Hash”
	3.	Crack hash:
	•	Use CrackStation
	4.	Extract image metadata:

exiftool image.jpg


	5.	Analyze audio:
	•	Open in Audacity and inspect waveform
