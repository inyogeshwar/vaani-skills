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
- Sirf banana ho: `make_ai_image` (shape square, status/wallpaper ke liye portrait). Gallery mein Pictures/Vaani mein save hoti hai.
- Seedha status ke liye: confirm karke `post_whatsapp_status` type `ai`.
- Banne mein 10 se 30 second lagte hain. Ek line bolo: "Ban rahi hai, thoda ruko."

## Step 3: Result
- "[Auto] ... ho gaya" aaye toh: "Status lag gaya!"
- Fail ho (net slow ya server busy) toh ek baar dobara koshish ka offer do, wahi prompt thoda chhota karke.
- Pasand na aaye toh status hatane ke liye `delete_whatsapp_status`, phir naya prompt.

## Share karna
- Kisi ko bhejni ho: confirm karke `send_whatsapp_photo` (source last). Status pe: `post_whatsapp_status` type `last`.
- Dobara mat banao, wahi image bhejo.
