MYSTIC RIVER TRIVIA V13 — NAME FILTER ENTER-KEY FIX

The issue was an Enter-key bypass:
pressing Enter in the nickname box called start() directly and skipped the
nickname filter entirely.

V13 routes Enter through the same validation as the ENTER THE RIVER button.

Tests to try:
- Ass -> blocked
- asshole -> blocked
- bitch -> blocked
- F U C K -> blocked
- sh1t -> blocked
- Cassidy -> allowed

Upload only index.html to GitHub.
