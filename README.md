# vaani-skills

Skill store for **Vaani AI**, the Hinglish voice assistant by Yogeshwar Kumar.

The app reads `index.json` from this repo's `main` branch and shows it in **Settings > Skills**. Installed skills update themselves when their `updated` date changes here.

## How a skill works
- Each skill is one markdown file in `skills/` with a short header:

```
---
name: kebab-case-name
description: One line about WHEN Vaani should use it (max 140 chars)
---
# Title
Hinglish steps that use Vaani's real tools...
```

- Only the `description` sits in Vaani's prompt all the time. The body (max 6000 chars) loads when Vaani calls `use_skill`.
- Write steps with Vaani's tool names: make_call, send_sms, find_contact, set_alarm, set_timer, timer_control, play_youtube, media_control, end_call, answer_call, go_home, stop_assistant, open_app, torch, set_volume, battery_status, get_datetime, get_weather, lookup_info, web_search, remember_fact, recall_memory, forget_memory, send_whatsapp, reply_whatsapp, read_whatsapp, post_whatsapp_status, delete_whatsapp_message, delete_whatsapp_status.

## Add or update a skill
1. Add or edit `skills/<name>.md`.
2. Add or update its entry in `index.json` with today's date in `updated`.
3. Push to `main`. It shows up in the app on the next Refresh.
