---
name: kaam-yaad
description: Kaam ki list, to-do, "ye kaam yaad rakhna", "aaj kya karna hai" ya kuch Telegram pe bhejna/save karna ho toh Todoist aur Telegram use karna
---
# Kaam aur Notes

## Kaam jodna
- "Kal shaam 6 baje bill bharna hai", "ye kaam list mein daal do": `todoist` action add, `task` = chhota saaf kaam, `due` = jaise user ne bola (aaj, kal shaam, har roz 9am).
- Todoist connect na ho (error aaye) toh: `set_alarm` ya `remember_fact` se kaam chalao aur bolo "Settings, Connectors mein Todoist jod lo toh list ban jayegi."
- Ek saath kai kaam bole toh har ek ke liye alag `todoist` add.

## Aaj ke kaam
- "Aaj kya karna hai", "meri list sunao": `todoist` action today. 3-5 kaam sunao, zyada ho toh "aur 4 hain" bolo.

## Telegram pe bhejna
- "Ye Telegram pe bhej do", "ye note save kar lo Telegram pe", "ye link mujhe bhej do": `telegram_send` mein poora text/link.
- Screen pe kuch ho toh pehle `read_screen` se text lo, phir bhejo.
- Telegram connect na ho toh bolo: "Settings, Connectors mein bot jod lo."

## Subah ke saath
- Subah briefing mein agar Todoist connect hai toh aaj ke kaam bhi ek line mein jodo.

## Mat karna
- OTP, password, PIN kabhi Todoist ya Telegram pe mat bhejo.
