# ShadowOfTransilvania

I documented my process and created a guide for the challenges I solved. </br>

<h1> Level 1 - The Perimeter </h1> </br>

<img width="381" height="350" alt="1" src="https://github.com/user-attachments/assets/f753c8b2-6e5e-446e-bf67-0fdf2aa85b1e" /> </br>

<h2> Chellange #1 : Lantern Log </h2> </br>

<img width="377" height="416" alt="3" src="https://github.com/user-attachments/assets/222b6941-ec7e-4ba9-a2c4-72222b065f64" />  </br>

Proof Of Concept:  </br>

The text from the note(L7bQT7hmWdz5AUzt3XNYE4WgxgJQj6) was encrypted with Base58. I used CyberChef to decrypt it and I found the flag: Flag{follow_the_light}. </br>

<h2> Chellange #2 : The Gatekeeper's Note </h2></br>

<img width="380" height="542" alt="4" src="https://github.com/user-attachments/assets/6f16dc91-2d32-40d0-b1ac-ce09feabf11c" /> </br>

Proof Of Concept:  </br>

I used an OSINT named 4QRCode to scan the QR and decoded brom base64. The result was FLAG(scan_the_gate) </br>

<h2> Chellange #3 : Watchful Eye </h2> </br>

<img width="382" height="557" alt="5" src="https://github.com/user-attachments/assets/461e717f-f12b-4a6f-b8a9-a6f564001ae0" /> </br>

Proof Of Concept:  </br>

The text in image was upside down. The result was FLAG{the_eye_sees_all} </br>

<h2> Chellange #4 : Broken Chains </h2> </br>

<img width="380" height="363" alt="6" src="https://github.com/user-attachments/assets/13923ccf-3468-469e-b480-0945ac4731cc" /> </br>

Proof Of Concept:  </br>

The SHA-256 hash from this challenge is from a file named Dracula.txt. I checked it on VirusTotal and discovered the flag: Flag{Dracula}.  </br>

<h1> Level 2 - The Hall Of Deception </h1> </br>

<br>  <img width="379" height="364" alt="7" src="https://github.com/user-attachments/assets/acfd084f-ca77-47f6-870d-b6c0428dfd4d" />  </br>

<h2> Chellange #5 : The Cyphered Chronicle </h2> </br>

<img width="387" height="527" alt="9" src="https://github.com/user-attachments/assets/da198119-c8b5-48cd-980c-664b31bae7cc" /> </br>

Proof Of Concept:  </br>

To decrypt 'WKH IODJ LV FWI{ERRN_RI_VHFUHWV}', I used a brute-force method for the Caesar cipher on dcode.fr and found: THE FLAG IS CTF{BOOK_OF_SECRETS}.

<h2> Chellange #6 : Time of Attack </h2> </br>

**<p align="center">
  <img src="https://github.com/user-attachments/assets/975abda1-be31-445c-98df-35a9e15b70d6" />" width="45%" />
  <img src="https://github.com/user-attachments/assets/55924bc1-969b-4a9e-8e9b-825324d1f9c7" />" width="45%" />
</p>**

Proof Of Concept:  </br>



