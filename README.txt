MYSTIC RIVER TRIVIA V15 — SUPABASE QUESTION BANK

What changed:
- Questions are no longer loaded from a hard-coded JavaScript bank.
- The game now looks up the active game with slug: mystic-river-falls
- It then loads active questions from public.questions in Supabase.
- Existing 4 Easy / 4 Medium / 2 Hard random mix is retained.
- Existing leaderboard, name protection, random river names, scoring, and design are retained.
- The start button shows LOADING QUESTIONS while fetching.
- A guest-friendly error appears if Supabase cannot load enough questions.
- Footer shows V15 so you can confirm the correct build is live.

UPLOAD:
Replace only index.html in your GitHub repository.
The existing mystic-river-falls.png can remain unchanged.

TEST:
1. Confirm footer says V15.
2. Start a game and make sure questions appear.
3. Complete at least one game and make sure leaderboard still works.
4. After that, changing a question in Supabase can update the game without replacing index.html.
