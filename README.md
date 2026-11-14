# PhotoTaiyaar

**NEET · JEE Live Photo Practice Tool** — form bharne se pehle, ghar baithe live photo ki poori taiyaari.

🔗 **Live:** https://weakcoderash.github.io/phototaiyaar/

## Kya karta hai ye tool?

NTA forms (NEET, JEE) me ab ek **live photo** camera se khinchti hai jo **Aadhaar card ki photo se match** hoti hai. Match fail matlab form atka. PhotoTaiyaar usi step ki pehle se practice karata hai:

- 📷 **Camera practice** — form jaisa oval guide, live jaanch
- 🔍 **8 checks** — chehra mila ya nahi, chehra ka size (50–75%), sir seedha, aankhen khuli, dono kaan, chehre ki roshni, background halka-saada, photo sharp
- 🖼️ **Upload check** — purani photo dal kar bhi wahi jaanch
- ⬇️ **Taiyaar photo** — sahi size (700×900) aur 200 KB ke andar JPG download
- 👀 **Example photos** — sahi vs galat photo, dekh kar samjho

## Privacy

Saari jaanch **browser ke andar** hoti hai (MediaPipe face detection, on-device). Photo kisi server par **nahi jati**.

## Note

Ye ek free practice tool hai — NTA/UIDAI ka official tool nahi hai. Asal match form portal par hi hota hai; guarantee koi tool nahi de sakta, lekin reject hone wali aam galtiyan yahan pehle pakad sakte ho.

## Tech

Single-file HTML · MediaPipe FaceLandmarker (client-side) · Canvas image analysis

## License

MIT
