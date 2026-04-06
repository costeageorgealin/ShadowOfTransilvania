# 🏰 Shadow of Transylvania

I documented my process and created a guide for the challenges I solved.

---

 <h1 align="center"> Level 1 - The Perimeter </h1>

<p align="center">
  <img width="381" src="https://github.com/user-attachments/assets/f753c8b2-6e5e-446e-bf67-0fdf2aa85b1e" width="60%" alt="Level 1" />
</p>

---

<h2> Challenge #1: Lantern Log </h2>

<p align="center">
  <img width="377" src="https://github.com/user-attachments/assets/222b6941-ec7e-4ba9-a2c4-72222b065f64" width="60%" alt="Challenge 1" />
</p>

**Proof Of Concept:**
The text from the note (`L7bQT7hmWdz5AUzt3XNYE4WgxgJQj6`) was encrypted with Base58. I used CyberChef to decrypt it and found the flag: `Flag{follow_the_light}`.

---

<h2> Challenge #2: The Gatekeeper's Note </h2>

<p align="center">
  <img width="380" src="https://github.com/user-attachments/assets/6f16dc91-2d32-40d0-b1ac-ce09feabf11c" width="60%" alt="Challenge 2" />
</p>

**Proof Of Concept:**
I used an OSINT tool named 4QRCode to scan the QR code and decoded it from Base64. The result was: `FLAG(scan_the_gate)`.

---

<h2> Challenge #3: Watchful Eye </h2>

<p align="center">
  <img width="382" src="https://github.com/user-attachments/assets/461e717f-f12b-4a6f-b8a9-a6f564001ae0" width="60%" alt="Challenge 3" />
</p>

**Proof Of Concept:**
The text in the image was upside down. After rotating it, the result was: `FLAG{the_eye_sees_all}`.

---

<h2> Challenge #4: Broken Chains </h2>

<p align="center">
  <img width="380" src="https://github.com/user-attachments/assets/13923ccf-3468-469e-b480-0945ac4731cc" width="60%" alt="Challenge 4" />
</p>

**Proof Of Concept:**
The SHA-256 hash from this challenge belongs to a file named `Dracula.txt`. I checked it on VirusTotal and discovered the flag: `Flag{Dracula}`.

---

<h1 align="center"> Level 2 - The Hall Of Deception </h1>

<p align="center">
  <img width="379" src="https://github.com/user-attachments/assets/acfd084f-ca77-47f6-870d-b6c0428dfd4d" width="60%" alt="Level 2" />
</p>

---

<h2> Challenge #5: The Cyphered Chronicle </h2>

<p align="center">
  <img width="387" src="https://github.com/user-attachments/assets/da198119-c8b5-48cd-980c-664b31bae7cc" width="60%" alt="Challenge 5" />
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

---

<h2> Challenge #7: Lights on the Network </h2>

<p align="center">
  <img src="https://github.com/user-attachments/assets/a1ab2883-021e-4ef4-bf37-2dca00025a49" width="60%" alt="Challenge 7" />
</p>

**Proof Of Concept:**
Everybody should know that opening Telnet is very bad for any security system.

---

 <h1 align="center"> Level 3 - The Network Observatory </h1>

<p align="center">
  <img width="380" src="https://github.com/user-attachments/assets/0aeaacfd-30e5-4912-ae0a-f81a10a9bbba" width="60%" alt="Level 2" />
</p>

---


<h2> Challenge #8: DNS Exfiltration Log </h2>

<p align="center">
  <img src="https://github.com/user-attachments/assets/3106cb6b-0644-4fca-ba08-d400ba93a3eb" width="60%" alt="Challenge 8" />
</p>

**Proof Of Concept:**

I noticed a pattern in the DNS queries. The subdomains contained Base64 encoded strings. After extracting and joining the segments `ZmxhZ3tkbnNfZXhmaWxfZm91bmR9`, I decoded the full string from Base64 and found the flag: flag{dns_exfil_found}.

---

<h2> Challenge #9: The Coded Page </h2>

<p align="center">
  <img src="https://github.com/user-attachments/assets/8ef591b5-93c1-4472-a279-0c63a8a1d81b" width="60%" alt="Challenge 9" />
</p>

**Proof Of Concept:**

The QR code contained the following message: icai{vplorsq_uyd_ycaf}. This was encrypted using the Vigenère cipher. After decrypting it, I found the flag: flag{bellaso_and_vlad}.

---

<h2> Challenge #10: Melted Password Policy  </h2>

<p align="center">
  <img src="https://github.com/user-attachments/assets/1f037c4e-ce5f-4792-ae52-d64b38634712" width="60%" alt="Challenge 10" />
</p>

**Proof Of Concept:**

I used a tool called MD5 Reverse to crack the hash `1c020611e3b753925ffc8af8745c0556`. I found the word 'vampire', so the flag was: vampire.

---

<h2> Challenge #11: Secrets Revealed  </h2>

<p align="center">
  <img src="https://github.com/user-attachments/assets/eaec9abb-efd8-4df6-ba8d-94986d4943ee" width="60%" alt="Challenge 11" />
</p>

**Proof Of Concept:**

I decoded the given Base64 message `QW8obWdIWk86O0VjYll0QVM+ZHFBNydGbEFSQk0jRGYwLTc=` and got the following result: `Ao(mgHZO:;EcbYtAS>dqA7'FlARBM#Df0-7`. After that, I decoded it again using Base85, which meant it was a double-encoded message. The flag was: flag{start_behind_the_stone}.

---

 <h1 align="center"> Level 4 - Dracula's Command & Control </h1>

 <h2> Challenge #11: Secrets Revealed  </h2>

<p align="center">
  <img src="https://github.com/user-attachments/assets/eaec9abb-efd8-4df6-ba8d-94986d4943ee" width="60%" alt="Challenge 11" />
</p>

**Proof Of Concept:**



---

