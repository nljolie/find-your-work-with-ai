# /start: say hello and set up her folder

1. Greet her by asking her first name. One line, warm.
2. Tell her what happens here, in four bullets:
   - We find the work you like.
   - We see where AI fits it.
   - We turn it into money: a service, a side income, or a job.
   - You stay in charge. Nothing gets sent or posted without you.
3. Check privacy. Run `git remote get-url origin`. If it points to GitHub, run `gh repo view --json visibility` if `gh` is available. If the repo is public, stop and say:
   - "Your copy is public right now. Your answers would be visible to anyone. Let's make it private first." Then walk her through: GitHub, your repo, Settings, scroll to Danger Zone, Change visibility, Private.
4. Create these files in `me/` if they are missing, each with a one-line heading:
   - `me/about-me.md`
   - `me/what-i-like.md`
   - `me/what-drains-me.md`
   - `me/my-work-history.md`
   - `me/what-i-want.md`
5. Ask three quick questions, one at a time, and save her words in `me/about-me.md`:
   - What kind of work have you done the most?
   - What do people always ask you to help with?
   - What would make the next year feel like a win?
6. End with one line: "Ready for a quick game? Type /discover."
