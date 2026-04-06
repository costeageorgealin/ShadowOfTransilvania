# 🏰 Shadow of Transylvania

I documented my process and created a guide for the challenges I solved.

---

 <h1 align="center"> Level 1 - The Perimeter </h1>

<p align="center">
  <img width="381" src="https://github.com/user-attachments/assets/f753c8b2-6e5e-446e-bf67-0fdf2aa85b1e" alt="Level 1" />
</p>

---

<h2> Challenge #1: Lantern Log </h2>

<p align="center">
  <img width="377" src="https://github.com/user-attachments/assets/222b6941-ec7e-4ba9-a2c4-72222b065f64" alt="Challenge 1" />
</p>

**Proof Of Concept:**
The text from the note (`L7bQT7hmWdz5AUzt3XNYE4WgxgJQj6`) was encrypted with Base58. I used CyberChef to decrypt it and found the flag: `Flag{follow_the_light}`.

---

<h2> Challenge #2: The Gatekeeper's Note </h2>

<p align="center">
  <img width="380" src="https://github.com/user-attachments/assets/6f16dc91-2d32-40d0-b1ac-ce09feabf11c" alt="Challenge 2" />
</p>

**Proof Of Concept:**
I used an OSINT tool named 4QRCode to scan the QR code and decoded it from Base64. The result was: `FLAG(scan_the_gate)`.

---

<h2> Challenge #3: Watchful Eye </h2>

<p align="center">
  <img width="382" src="https://github.com/user-attachments/assets/461e717f-f12b-4a6f-b8a9-a6f564001ae0" alt="Challenge 3" />
</p>

**Proof Of Concept:**
The text in the image was upside down. After rotating it, the result was: `FLAG{the_eye_sees_all}`.

---

<h2> Challenge #4: Broken Chains </h2>

<p align="center">
  <img width="380" src="https://github.com/user-attachments/assets/13923ccf-3468-469e-b480-0945ac4731cc" alt="Challenge 4" />
</p>

**Proof Of Concept:**
The SHA-256 hash from this challenge belongs to a file named `Dracula.txt`. I checked it on VirusTotal and discovered the flag: `Flag{Dracula}`.

---

<h1 align="center"> Level 2 - The Hall Of Deception </h1>

<p align="center">
  <img width="379" src="https://github.com/user-attachments/assets/acfd084f-ca77-47f6-870d-b6c0428dfd4d" alt="Level 2" />
</p>

---

<h2> Challenge #5: The Cyphered Chronicle </h2>

<p align="center">
  <img width="387" src="https://github.com/user-attachments/assets/da198119-c8b5-48cd-980c-664b31bae7cc" alt="Challenge 5" />
</p>

**Proof Of Concept:**
To decrypt `WKH IODJ LV FWI{ERRN_RI_VHFUHWV}`, I used a brute-force method for the Caesar cipher on dcode.fr and found: `THE FLAG IS CTF{BOOK_OF_SECRETS}`.

---

<h2> Challenge #6: Time of Attack </h2>

<p align="center">
  <img src="https://github.com/user-attachments/assets/975abda1-be31-445c-98df-35a9e15b70d6" width="60%" alt="Challenge 6" />
</p>

**Proof Of Concept:**
In the authentication logs, I identified multiple failed password attempts from IP `10.10.14.8`. The brute-force attack was successful at the exact timestamp: `2025-03-14 19:41:27`.
