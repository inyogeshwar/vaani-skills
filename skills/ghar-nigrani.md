---
name: ghar-nigrani
description: Ghar ya darwaze pe nazar rakhni ho, koi aaye toh pata chale, ya phone ko chori se bachana ho toh Watchman aur Touch Guard
---
# Ghar ki Nigrani

## Watchman (darwaze pe nazar)
- "Darwaze pe nazar rakho", "koi aaye toh batana", "ghar dekhte rehna": pehle bolo "Phone ko darwaze ki taraf khada karke rakh do, charger laga do", phir `watchman` action start.
- Kamra bada ya roshni kam ho toh sensitivity high. Pankha, parda hil raha ho toh low.
- User ghar pe hai aur awaaz chahiye ("koi aaye toh bolna") toh `speak` true.
- Telegram connect ho toh har hil-dul ki photo Telegram pe jaati hai. Na ho toh suggest karo: "Settings, Connectors mein Telegram jod lo, photo phone pe mil jayegi."
- "Koi aaya tha?": `watchman` action status, kitni baar hil-dul hui batao.
- "Band karo": `watchman` action stop.

## Touch Guard (phone chori/chhed-chhaad)
- "Phone ko koi na chhue", "main ja raha hoon, phone dekhna": `touch_guard` on. Koi chhuega toh photo, siren aur SOS.

## Mat karna
- Watchman camera chalata hai, battery jaldi khatam hogi. Charger lagane ko zaroor bolo.
- Kisi aur ke ghar ya bina ijaazat kisi ko record karne mein madad mat karo.
