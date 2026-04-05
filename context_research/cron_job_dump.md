[Memory context]
- user_msg_c9555fdd-a6e5-45c3-afba-92098c91bfe7: [Memory context]
- user_msg_ccca45bf-c3ec-4a41-8436-48d43606f6cf: [Memory context]
- user_msg_08d9e0cc-3714-4982-945a-f1d07e8b109a: [Memory context]
- user_msg_cd198e74-631b-41e8-be12-42276be44dd8: [Memory context]
- user_msg_5773c3de-2620-4c3b-ad99-d70b564f4c74: [Memory context]
- user_msg_dc3179f2-05cb-40ab-b1e7-832f68ba0ad9: [Memory context]
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo
- core_91e53596-d517-4a06-af8b-348979dcdd15: The user has removed most of the assistant's skills to optimize for context size and efficiency.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg_dc3179f2-05cb-40ab-b1e7-832f68ba0ad9: [Memory context]
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo
- core_91e53596-d517-4a06-af8b-348979dcdd15: The user has removed most of the assistant's skills to optimize for context size and efficiency.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg_5773c3de-2620-4c3b-ad99-d70b564f4c74: [Memory context]
- user_msg_dc3179f2-05cb-40ab-b1e7-832f68ba0ad9: [Memory context]
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo
- core_91e53596-d517-4a06-af8b-348979dcdd15: The user has removed most of the assistant's skills to optimize for context size and efficiency.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg_dc3179f2-05cb-40ab-b1e7-832f68ba0ad9: [Memory context]
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo
- core_91e53596-d517-4a06-af8b-348979dcdd15: The user has removed most of the assistant's skills to optimize for context size and efficiency.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg_cd198e74-631b-41e8-be12-42276be44dd8: [Memory context]
- user_msg_5773c3de-2620-4c3b-ad99-d70b564f4c74: [Memory context]
- user_msg_dc3179f2-05cb-40ab-b1e7-832f68ba0ad9: [Memory context]
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo
- core_91e53596-d517-4a06-af8b-348979dcdd15: The user has removed most of the assistant's skills to optimize for context size and efficiency.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg_dc3179f2-05cb-40ab-b1e7-832f68ba0ad9: [Memory context]
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo
- core_91e53596-d517-4a06-af8b-348979dcdd15: The user has removed most of the assistant's skills to optimize for context size and efficiency.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg_5773c3de-2620-4c3b-ad99-d70b564f4c74: [Memory context]
- user_msg_dc3179f2-05cb-40ab-b1e7-832f68ba0ad9: [Memory context]
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo
- core_91e53596-d517-4a06-af8b-348979dcdd15: The user has removed most of the assistant's skills to optimize for context size and efficiency.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg_dc3179f2-05cb-40ab-b1e7-832f68ba0ad9: [Memory context]
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo
- core_91e53596-d517-4a06-af8b-348979dcdd15: The user has removed most of the assistant's skills to optimize for context size and efficiency.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg_08d9e0cc-3714-4982-945a-f1d07e8b109a: [Memory context]
- user_msg_cd198e74-631b-41e8-be12-42276be44dd8: [Memory context]
- user_msg_5773c3de-2620-4c3b-ad99-d70b564f4c74: [Memory context]
- user_msg_dc3179f2-05cb-40ab-b1e7-832f68ba0ad9: [Memory context]
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo
- core_91e53596-d517-4a06-af8b-348979dcdd15: The user has removed most of the assistant's skills to optimize for context size and efficiency.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg_dc3179f2-05cb-40ab-b1e7-832f68ba0ad9: [Memory context]
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo
- core_91e53596-d517-4a06-af8b-348979dcdd15: The user has removed most of the assistant's skills to optimize for context size and efficiency.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg_5773c3de-2620-4c3b-ad99-d70b564f4c74: [Memory context]
- user_msg_dc3179f2-05cb-40ab-b1e7-832f68ba0ad9: [Memory context]
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo
- core_91e53596-d517-4a06-af8b-348979dcdd15: The user has removed most of the assistant's skills to optimize for context size and efficiency.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg_dc3179f2-05cb-40ab-b1e7-832f68ba0ad9: [Memory context]
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo
- core_91e53596-d517-4a06-af8b-348979dcdd15: The user has removed most of the assistant's skills to optimize for context size and efficiency.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg_cd198e74-631b-41e8-be12-42276be44dd8: [Memory context]
- user_msg_5773c3de-2620-4c3b-ad99-d70b564f4c74: [Memory context]
- user_msg_dc3179f2-05cb-40ab-b1e7-832f68ba0ad9: [Memory context]
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo
- core_91e53596-d517-4a06-af8b-348979dcdd15: The user has removed most of the assistant's skills to optimize for context size and efficiency.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg_dc3179f2-05cb-40ab-b1e7-832f68ba0ad9: [Memory context]
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo
- core_91e53596-d517-4a06-af8b-348979dcdd15: The user has removed most of the assistant's skills to optimize for context size and efficiency.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg_5773c3de-2620-4c3b-ad99-d70b564f4c74: [Memory context]
- user_msg_dc3179f2-05cb-40ab-b1e7-832f68ba0ad9: [Memory context]
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo
- core_91e53596-d517-4a06-af8b-348979dcdd15: The user has removed most of the assistant's skills to optimize for context size and efficiency.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg_dc3179f2-05cb-40ab-b1e7-832f68ba0ad9: [Memory context]
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo
- core_91e53596-d517-4a06-af8b-348979dcdd15: The user has removed most of the assistant's skills to optimize for context size and efficiency.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg_ccca45bf-c3ec-4a41-8436-48d43606f6cf: [Memory context]
- user_msg_08d9e0cc-3714-4982-945a-f1d07e8b109a: [Memory context]
- user_msg_cd198e74-631b-41e8-be12-42276be44dd8: [Memory context]
- user_msg_5773c3de-2620-4c3b-ad99-d70b564f4c74: [Memory context]
- user_msg_dc3179f2-05cb-40ab-b1e7-832f68ba0ad9: [Memory context]
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo
- core_91e53596-d517-4a06-af8b-348979dcdd15: The user has removed most of the assistant's skills to optimize for context size and efficiency.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg_dc3179f2-05cb-40ab-b1e7-832f68ba0ad9: [Memory context]
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo
- core_91e53596-d517-4a06-af8b-348979dcdd15: The user has removed most of the assistant's skills to optimize for context size and efficiency.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg_5773c3de-2620-4c3b-ad99-d70b564f4c74: [Memory context]
- user_msg_dc3179f2-05cb-40ab-b1e7-832f68ba0ad9: [Memory context]
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo
- core_91e53596-d517-4a06-af8b-348979dcdd15: The user has removed most of the assistant's skills to optimize for context size and efficiency.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg_dc3179f2-05cb-40ab-b1e7-832f68ba0ad9: [Memory context]
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo
- core_91e53596-d517-4a06-af8b-348979dcdd15: The user has removed most of the assistant's skills to optimize for context size and efficiency.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg_cd198e74-631b-41e8-be12-42276be44dd8: [Memory context]
- user_msg_5773c3de-2620-4c3b-ad99-d70b564f4c74: [Memory context]
- user_msg_dc3179f2-05cb-40ab-b1e7-832f68ba0ad9: [Memory context]
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo
- core_91e53596-d517-4a06-af8b-348979dcdd15: The user has removed most of the assistant's skills to optimize for context size and efficiency.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg_dc3179f2-05cb-40ab-b1e7-832f68ba0ad9: [Memory context]
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo
- core_91e53596-d517-4a06-af8b-348979dcdd15: The user has removed most of the assistant's skills to optimize for context size and efficiency.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg_5773c3de-2620-4c3b-ad99-d70b564f4c74: [Memory context]
- user_msg_dc3179f2-05cb-40ab-b1e7-832f68ba0ad9: [Memory context]
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo
- core_91e53596-d517-4a06-af8b-348979dcdd15: The user has removed most of the assistant's skills to optimize for context size and efficiency.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg_dc3179f2-05cb-40ab-b1e7-832f68ba0ad9: [Memory context]
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo
- core_91e53596-d517-4a06-af8b-348979dcdd15: The user has removed most of the assistant's skills to optimize for context size and efficiency.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg_08d9e0cc-3714-4982-945a-f1d07e8b109a: [Memory context]
- user_msg_cd198e74-631b-41e8-be12-42276be44dd8: [Memory context]
- user_msg_5773c3de-2620-4c3b-ad99-d70b564f4c74: [Memory context]
- user_msg_dc3179f2-05cb-40ab-b1e7-832f68ba0ad9: [Memory context]
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo
- core_91e53596-d517-4a06-af8b-348979dcdd15: The user has removed most of the assistant's skills to optimize for context size and efficiency.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg_dc3179f2-05cb-40ab-b1e7-832f68ba0ad9: [Memory context]
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo
- core_91e53596-d517-4a06-af8b-348979dcdd15: The user has removed most of the assistant's skills to optimize for context size and efficiency.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg_5773c3de-2620-4c3b-ad99-d70b564f4c74: [Memory context]
- user_msg_dc3179f2-05cb-40ab-b1e7-832f68ba0ad9: [Memory context]
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo
- core_91e53596-d517-4a06-af8b-348979dcdd15: The user has removed most of the assistant's skills to optimize for context size and efficiency.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg_dc3179f2-05cb-40ab-b1e7-832f68ba0ad9: [Memory context]
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo
- core_91e53596-d517-4a06-af8b-348979dcdd15: The user has removed most of the assistant's skills to optimize for context size and efficiency.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg_cd198e74-631b-41e8-be12-42276be44dd8: [Memory context]
- user_msg_5773c3de-2620-4c3b-ad99-d70b564f4c74: [Memory context]
- user_msg_dc3179f2-05cb-40ab-b1e7-832f68ba0ad9: [Memory context]
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo
- core_91e53596-d517-4a06-af8b-348979dcdd15: The user has removed most of the assistant's skills to optimize for context size and efficiency.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg_dc3179f2-05cb-40ab-b1e7-832f68ba0ad9: [Memory context]
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo
- core_91e53596-d517-4a06-af8b-348979dcdd15: The user has removed most of the assistant's skills to optimize for context size and efficiency.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg_5773c3de-2620-4c3b-ad99-d70b564f4c74: [Memory context]
- user_msg_dc3179f2-05cb-40ab-b1e7-832f68ba0ad9: [Memory context]
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo
- core_91e53596-d517-4a06-af8b-348979dcdd15: The user has removed most of the assistant's skills to optimize for context size and efficiency.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
[/Memory context]

[2026-04-06 01:16:09 +03:00] [Memory context]
- user_msg_ccca45bf-c3ec-4a41-8436-48d43606f6cf: [Memory context]
- user_msg_08d9e0cc-3714-4982-945a-f1d07e8b109a: [Memory context]
- user_msg_cd198e74-631b-41e8-be12-42276be44dd8: [Memory context]
- user_msg_5773c3de-2620-4c3b-ad99-d70b564f4c74: [Memory context]
- user_msg_dc3179f2-05cb-40ab-b1e7-832f68ba0ad9: [Memory context]
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo
- core_91e53596-d517-4a06-af8b-348979dcdd15: The user has removed most of the assistant's skills to optimize for context size and efficiency.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg_dc3179f2-05cb-40ab-b1e7-832f68ba0ad9: [Memory context]
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo
- core_91e53596-d517-4a06-af8b-348979dcdd15: The user has removed most of the assistant's skills to optimize for context size and efficiency.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg_5773c3de-2620-4c3b-ad99-d70b564f4c74: [Memory context]
- user_msg_dc3179f2-05cb-40ab-b1e7-832f68ba0ad9: [Memory context]
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo
- core_91e53596-d517-4a06-af8b-348979dcdd15: The user has removed most of the assistant's skills to optimize for context size and efficiency.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg_dc3179f2-05cb-40ab-b1e7-832f68ba0ad9: [Memory context]
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo
- core_91e53596-d517-4a06-af8b-348979dcdd15: The user has removed most of the assistant's skills to optimize for context size and efficiency.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg_cd198e74-631b-41e8-be12-42276be44dd8: [Memory context]
- user_msg_5773c3de-2620-4c3b-ad99-d70b564f4c74: [Memory context]
- user_msg_dc3179f2-05cb-40ab-b1e7-832f68ba0ad9: [Memory context]
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo
- core_91e53596-d517-4a06-af8b-348979dcdd15: The user has removed most of the assistant's skills to optimize for context size and efficiency.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg_dc3179f2-05cb-40ab-b1e7-832f68ba0ad9: [Memory context]
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo
- core_91e53596-d517-4a06-af8b-348979dcdd15: The user has removed most of the assistant's skills to optimize for context size and efficiency.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg_5773c3de-2620-4c3b-ad99-d70b564f4c74: [Memory context]
- user_msg_dc3179f2-05cb-40ab-b1e7-832f68ba0ad9: [Memory context]
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo
- core_91e53596-d517-4a06-af8b-348979dcdd15: The user has removed most of the assistant's skills to optimize for context size and efficiency.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg_dc3179f2-05cb-40ab-b1e7-832f68ba0ad9: [Memory context]
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo
- core_91e53596-d517-4a06-af8b-348979dcdd15: The user has removed most of the assistant's skills to optimize for context size and efficiency.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg_08d9e0cc-3714-4982-945a-f1d07e8b109a: [Memory context]
- user_msg_cd198e74-631b-41e8-be12-42276be44dd8: [Memory context]
- user_msg_5773c3de-2620-4c3b-ad99-d70b564f4c74: [Memory context]
- user_msg_dc3179f2-05cb-40ab-b1e7-832f68ba0ad9: [Memory context]
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo
- core_91e53596-d517-4a06-af8b-348979dcdd15: The user has removed most of the assistant's skills to optimize for context size and efficiency.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg_dc3179f2-05cb-40ab-b1e7-832f68ba0ad9: [Memory context]
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo
- core_91e53596-d517-4a06-af8b-348979dcdd15: The user has removed most of the assistant's skills to optimize for context size and efficiency.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg_5773c3de-2620-4c3b-ad99-d70b564f4c74: [Memory context]
- user_msg_dc3179f2-05cb-40ab-b1e7-832f68ba0ad9: [Memory context]
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo
- core_91e53596-d517-4a06-af8b-348979dcdd15: The user has removed most of the assistant's skills to optimize for context size and efficiency.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg_dc3179f2-05cb-40ab-b1e7-832f68ba0ad9: [Memory context]
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo
- core_91e53596-d517-4a06-af8b-348979dcdd15: The user has removed most of the assistant's skills to optimize for context size and efficiency.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg_cd198e74-631b-41e8-be12-42276be44dd8: [Memory context]
- user_msg_5773c3de-2620-4c3b-ad99-d70b564f4c74: [Memory context]
- user_msg_dc3179f2-05cb-40ab-b1e7-832f68ba0ad9: [Memory context]
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo
- core_91e53596-d517-4a06-af8b-348979dcdd15: The user has removed most of the assistant's skills to optimize for context size and efficiency.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg_dc3179f2-05cb-40ab-b1e7-832f68ba0ad9: [Memory context]
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo
- core_91e53596-d517-4a06-af8b-348979dcdd15: The user has removed most of the assistant's skills to optimize for context size and efficiency.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg_5773c3de-2620-4c3b-ad99-d70b564f4c74: [Memory context]
- user_msg_dc3179f2-05cb-40ab-b1e7-832f68ba0ad9: [Memory context]
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo
- core_91e53596-d517-4a06-af8b-348979dcdd15: The user has removed most of the assistant's skills to optimize for context size and efficiency.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages
- user_msg_dc3179f2-05cb-40ab-b1e7-832f68ba0ad9: [Memory context]
- user_msg: try invoking the cron job "Daily Morning Briefing (Hebrew)"
- core_4dbc738c-4c92-4b88-907d-669f200d98ea: The user has decided to focus exclusively on the skill-creation-skill for creating, modifying, benchmarking, and optimizing skills, discarding all other options.
- daily_2026-04-06_31a75905-ad41-40f8-9c61-16dabcf7507d: The assistant confirmed the user's decision to streamline their toolkit down to a single meta-skill: skill-creation-skill.
- telegram_5761315520_telegram_5761315520_200: You tell me. Take a loo
- core_91e53596-d517-4a06-af8b-348979dcdd15: The user has removed most of the assistant's skills to optimize for context size and efficiency.

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages

[cron:e4918108-85f0-4cf7-a689-c0defcb45d70 Daily Morning Briefing (Hebrew)] You are a daily morning briefing assistant. Perform these tasks in Hebrew and deliver personalized messages to two Telegram users.

STEP 1 - GATHER INFORMATION:

1. **HEADLINES from ynet.co.il**:
   - Use the `web_fetch` tool on URL: https://www.ynet.co.il
   - Extract the top 4-5 main news headlines from the fetched text
   - Do NOT use web_search_tool for Hebrew content (it doesn't work)
   - If web_fetch fails, note it and skip headlines section

2. **WEATHER for Tel Aviv**:
   - Use the `weather` tool with location "Tel Aviv, Israel", days=1, units=metric
   - Extract: high temp, low temp, conditions, rain chance

3. **INTERESTING FACT**:
   - Use your own knowledge to provide a short, interesting, verified fact about the world (science, history, nature, or culture)
   - Keep it to 1-2 sentences
   - Do NOT use web_search for this

STEP 2 - SEND MESSAGES:

Use `sessions_send` to deliver the following messages:

**Message 1 — To session: telegram_5761315520_5761315520 (the user):**
```
📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת:
[fact in Hebrew]

בוקר טוב! ☀️
```

**Message 2 — To session: telegram_5905050606_5905050606 (partner):**
Address her warmly as "פוזיק".
```
בוקר טוב פוזיק! ☀️💛

📰 כותרות היום מ-ynet:
• [headline 1]
• [headline 2]
• [headline 3]
• [headline 4]

🌤️ מזג האוויר היום:
טמפ׳ גבוהה: [X]°C, נמוכה: [X]°C
תנאים: [conditions]
סיכוי גשם: [X]%

🧠 עובדה מעניינת להיום:
[fact in Hebrew]

יום מקסים פוזיק! 🌸
```

CRITICAL RULES:
- ALL output must be in Hebrew
- Use ONLY `web_fetch` for ynet headlines (URL: https://www.ynet.co.il)
- Use ONLY `weather` tool for weather (location: Tel Aviv, Israel)
- Use your OWN knowledge for the interesting fact
- Do NOT use web_search_tool at all
- Keep headlines concise (one line each)
- If any tool fails, write "לא זמין כרגע" for that section and continue
- Send exactly two messages using sessions_send with the exact session IDs above
- Do NOT add any extra commentary or text outside the two messages