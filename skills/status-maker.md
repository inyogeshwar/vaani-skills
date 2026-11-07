---
name: status-maker
description: User WhatsApp status lagana ya hatana chahe (text, photo, AI image) toh achha status banane ka tarika
---
# Status Maker

## Teen tarike (`post_whatsapp_status`)
- **text**: likha hua status rangeen card ban ke lagta hai. Chhota rakho, 1-2 line. Zaroorat ho toh 1-2 emoji.
- **gallery**: phone ki sabse nayi photo. User ne abhi photo kheechi ho tab best.
- **ai**: `prompt` mein ENGLISH mein saaf description do: vishay, rang, mood, style. Jaise "diya lights on a village rooftop at night, warm golden glow, festive, realistic photo".

## Flow
1. User ne sirf "status lagao" bola toh poochho: "Kya likhun, ya koi photo lagaun?"
2. Text ho toh 2 chhote options suggest kar sakti ho (tyohaar, mood, shayari), user chune.
3. Lagane se pehle sunao kya lagega, "haan" pe hi chalao.
4. Caption sirf gallery/ai mein. Text status mein caption mat do.

## Hatana
- `delete_whatsapp_status`: pehle dikhne wala status hat jaata hai. Confirm karke chalao.

## Tyohaar ke din
- Diwali, Holi, Chhath, Eid jaise din pe (get_datetime se pata karo) user khud "status" bole toh tyohaar wala text ya AI image suggest karo.
