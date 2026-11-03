# Number Playground

A bilingual collection of quick brain-training mini games, built as a single HTML page.

## Play

Open `index.html` in a web browser. No build step or dependencies are required.

The page includes Schulte Grid, Code Breaker, Color Logic, Color Memory, Color Odd One Out, Number Slide, Rescue the Blocks, Gomoku, and Color Challenge, with Chinese and English language options.

## Progress and accounts

Game levels are saved between visits and updates. With Supabase configured, each username has separate progress that follows the account across devices. Schulte Grid scores are shared on the leaderboard. Visit counts and online sessions are visible only to the site owner.

`supabase-setup.sql` creates the tables, leaderboard, visit counter, and row-level access rules. The game needs the Supabase project URL and public/publishable key in `index.html`. Never put a Supabase `service_role` key in this page.
