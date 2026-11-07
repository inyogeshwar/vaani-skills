---
name: call-sahayak
description: Phone call karna, uthana, kaatna, call ke beech chup rehna aur baad mein WhatsApp se "baad mein baat karta hoon" bhejna
---
# Call Sahayak

## Call karna
1. User naam bole toh `find_contact` se number nikalo. Ek se zyada mile toh poochho "Rahul Sharma ya Rahul Bhaiya?"
2. Confirm karke hi `make_call`: "Mummy ko call lagaun?" Khud se kabhi kisi ko call mat karo.
3. User ne number bola ho toh wahi number `make_call` mein do.

## Call aa raha ho
- User bole "utha lo", "haan le lo", "pick karo": turant `answer_call`.
- User bole "kaat do", "abhi nahi", "busy hoon": turant `end_call`, phir sirf "Kaat diya." bolo.
- Baat samajh na aaye toh ek chhota sawaal: "Uthaun ya kaatun?" Lamba mat bolo, ghanti nikal jayegi.

## Call uthane ke baad (sabse zaroori)
- `answer_call` ke baad bilkul chup raho. Koi line, koi comment nahi. Tumhari awaaz call mein ja sakti hai.
- User khud "Vaani" bole ya call khatam ho, tabhi wapas bolna.
- User bole "call kaat do" toh `end_call`.

## Kaatne ke baad
- User chahe toh us insaan ko `send_whatsapp` se chhota message: "Abhi busy hoon, thodi der mein call karta hoon." Bhejne se pehle text sunao aur haan ka intezaar karo.
- Agar contact WhatsApp pe nahi mila toh `send_sms` ka offer do.

## Dhyan rahe
- Call log abhi Vaani nahi padh sakti. "Kiska call tha?" poocha jaye toh saaf bolo ki ye abhi nahi dekh sakti.
- WhatsApp call abhi Vaani se nahi lagta. Normal call ka offer do.
