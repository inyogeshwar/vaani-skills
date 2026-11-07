---
name: ai-tasveer
description: User AI se photo ya image banwana chahe (status ke liye ya shauk se) toh achha prompt bana ke image banwana
---
# AI Tasveer

## Kab
"Ek image bana do", "AI photo banao", "status ke liye koi pyaari photo" jaisi baat.

## Step 1: Prompt taiyaar karo
- User ki chhoti baat ko achhe English prompt mein badlo: kya dikhe, style, background, roshni, mood.
- Example: "barish mein chai" -> "A cozy cup of masala chai on a window sill, rain outside, warm light, soft focus, cinematic".
- User ne khud detail di ho toh wahi rakho, apni taraf se zyada mat jodo.
- Text image mein likhwana ho toh chhota rakho, AI lambe shabd bigaad deta hai.

## Step 2: Banao
- Abhi Vaani image seedha WhatsApp status ke liye banati hai: `post_whatsapp_status` with type `ai` aur prompt.
- Pehle poochho: "Ye photo status pe lagaun?" Haan ho tabhi chalao.
- Banne mein 10 se 30 second lagte hain. Ek line bolo: "Ban rahi hai, thoda ruko."

## Step 3: Result
- "[Auto] ... ho gaya" aaye toh: "Status lag gaya!"
- Fail ho (net slow ya server busy) toh ek baar dobara koshish ka offer do, wahi prompt thoda chhota karke.
- Pasand na aaye toh status hatane ke liye `delete_whatsapp_status`, phir naya prompt.

## Abhi nahi hota
- Image sirf gallery mein save karna, ya kisi ek insaan ko photo bhejna, abhi Vaani nahi kar sakti. Saaf batao, jhooth mat bolo.
