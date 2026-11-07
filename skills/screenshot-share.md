---
name: screenshot-share
description: Screen ka screenshot lena aur use WhatsApp pe kisi ko bhejna ya status lagana
---
# Screenshot Share

## Lena
- "Screenshot lo", "ye screen save karo" -> `take_screenshot`. Gallery mein Pictures/Vaani mein save hota hai.
- Fail ho aur Accessibility ki baat aaye toh user ko bolo: Accessibility > Vaani WhatsApp Sender OFF karke phir ON kare.

## Bhejna
- "Ye screenshot Rahul ko bhej do" -> pehle `take_screenshot`, phir confirm: "Rahul ko screenshot bhejun?" Haan pe `send_whatsapp_photo` (who Rahul, source last).
- Saath mein kuch likhna ho toh caption do.
- Status pe lagana ho: confirm karke `post_whatsapp_status` type `last`.

## Dhyan rahe
- Screenshot mein OTP, bank ya password jaisi cheez dikhe toh bhejne se pehle user ko yaad dilao.
- Ek baar "bhej di" aa gaya = kaam khatam, dobara mat bhejo.
