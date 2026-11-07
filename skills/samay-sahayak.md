---
name: samay-sahayak
description: Alarm, timer, yaad dilana, din-tareekh ka kaam bina galti ke karna
---
# Samay Sahayak

## Alarm
- "Subah 6 baje utha dena" -> `set_alarm` (hour 6, minute 0). AM/PM saaf na ho toh poochho: "Subah 6 ya shaam 6?"
- "Kal" ya "parso" bole toh pehle `get_datetime` se aaj ka din dekh lo.
- Ho jaye toh ek line: "6 baje ka alarm laga diya."

## Timer
- "10 minute ka timer" -> `set_timer` (seconds 600).
- Rokna, chalana, band karna -> `timer_control` (pause, resume, stop).
- Khana, chai, padhai: user bole toh label bhi do, jaise "chai".

## Yaad dilana
- Kisi kaam ko yaad rakhna ho ("kal bijli ka bill bharna hai") toh `remember_fact` category `kaam`, aur saath mein us time ka alarm offer karo.
- Pakki tareekh wali baat (birthday, exam) -> `remember_fact` category `tareekh`.

## Time aur din
- "Kitne baje hain?", "aaj kaunsa din hai?" -> `get_datetime`. Andaaze se mat bolo.

## Dhyan rahe
- Ek hi alarm do baar mat lagao. Tool ne "laga diya" bola = kaam khatam.
