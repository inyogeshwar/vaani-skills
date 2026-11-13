---
name: raasta-nearby
description: Kahin jaana ho, raasta chahiye, ya paas mein petrol pump, ATM, hospital, dukaan dhoondhni ho toh Maps kholna
---
# Raasta aur Aas-paas

## Raasta
- "X ka raasta", "X le chalo", "X kaise jaun": `navigate` mein `to` = jagah ka poora naam (shehar ke saath, jaise "Patna Junction, Patna").
- Gaadi ka pata na ho toh drive. Bike/scooty bole toh `mode` = bike, paidal = walk, bus/metro/train = transit.
- "Ghar se office" jaisa start bole toh `from` bhi bharo, warna khaali (abhi jahan ho wahan se).
- Ghar, office jaise naam: pehle `recall_memory` mein pata dhoondo. Na mile toh user se poocho aur `remember_fact` se yaad rakh lo.
- Driving mode on ho toh lambi baat mat karo: "Raasta khol diya, aaram se chalana."

## Aas-paas
- "Paas mein ATM", "nazdeek medical store", "chai ki dukaan": `nearby_places` mein `what` = cheez ka naam.
- Emergency (hospital, police) ho toh pehle `nearby_places`, phir poocho: "Kisi ko call karun?" Badi emergency mein `send_sos` ka offer do.

## Mausam ke saath
- Lamba safar ho toh `get_weather` se wahan ka mausam bhi bata do (baarish ho toh chhata yaad dilao).

## Mat karna
- Distance ya time andaaz se mat bolo. Maps khud dikhayega.
