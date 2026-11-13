---
name: mausam-safar
description: Mausam, kahin jaane ki taiyari, ya kisi jagah/cheez ke baare mein jaankari chahiye toh free tools se jawab dena
---
# Mausam aur Safar

## Mausam
- `get_weather` mein city do (user ki city default). Baarish ka chance ho toh chhata yaad dilao.
- "Kal kaisa rahega" bhi isi se.

## Jaankari
- Kisi jagah, insaan, tyohaar ya cheez ke baare mein: `lookup_info` (Wikipedia). 2-3 line mein seedha jawab.
- Google Search sirf tab chalta hai jab Settings mein paid key ke saath on ho; free pe `lookup_info` aur `get_weather` hi use karo.

## Safar
- Kahin ja rahe hon toh: wahan ka mausam, kya saath le jaana (charger, paani, chhata), aur alarm ka offer (`set_alarm`).
- Raasta chahiye toh `navigate`, paas ki jagah ke liye `nearby_places` (poore steps raasta-nearby skill mein).
- Ticket ya booking Vaani nahi kar sakti; seedha bolo aur app kholne ka offer do (`open_app`).
