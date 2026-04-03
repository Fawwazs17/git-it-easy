# Git It Easy

**Difficulty:** Beginner
**Skills practiced:** Forking, cloning, editing files, staging, committing, pushing

---

## The Scenario

You're building your very own portfolio page! The page is already set up — all you need to do is **replace the placeholders with your own info** and use Git to save and upload your changes.

No coding knowledge needed. You're just editing text.

---

## What You'll Fill In

Open `index.html` in any text editor (VS Code, Notepad, TextEdit — anything works). Look for the `ALL_CAPS_PLACEHOLDERS` and replace them with your own info:

| Placeholder | What to write |
|---|---|
| `YOUR_NAME_HERE` | Your name (appears in 2 places) |
| `YOUR_ROLE_HERE` | Your role, major, or title (e.g. "Student", "Designer") |
| `YOUR_HOBBY_HERE` | A hobby or interest (e.g. "Football Fan") |
| `YOUR_FUN_FACT_HERE` | Something fun about you (e.g. "Cat Person") |
| `WRITE_A_SHORT_BIO_ABOUT_YOURSELF_HERE` | 1–2 sentences about yourself |
| `YOUR_PROJECT_1` | A project, skill, or interest |
| `YOUR_PROJECT_2` | Another one |
| `YOUR_PROJECT_3` | One more |
| `DESCRIBE_IT_HERE` | A short description for each one above |
| `YOUR_EMAIL_HERE` | Your email (appears in 2 places) |

### Profile Picture

Your portfolio comes with a default profile picture. To use your own:

1. Add your photo to the `profile/` folder
2. Rename it to `profile.png` (replacing the existing file)

> **Tip:** Open the file in your browser to see your changes live — just refresh after each save!

---

## Your Mission

### Step 1 — Fork & Clone

1. **Fork** this repo to your own GitHub account (click the **Fork** button at the top-right)
2. **Clone** your fork to your machine:
   ```bash
   git clone https://github.com/YOUR-USERNAME/git-it-easy.git
   cd git-it-easy
   ```

### Step 2 — Edit, Stage, Commit, Repeat

Open `index.html` in your text editor. Instead of replacing everything at once, **make small edits and commit after each one**. This way, each commit tells a clear story of what you changed.

**Optional:** Add your own profile picture by replacing the file at `profile/profile.png` with your own photo (keep the same filename).

> **Tip:** Open the file in your browser to preview — just refresh after saving!

Here's an example workflow:

**Edit 1 — Add your name and tagline**

Replace `YOUR_NAME_HERE`, `YOUR_ROLE_HERE`, `YOUR_HOBBY_HERE`, and `YOUR_FUN_FACT_HERE`. Then:

```bash
git add index.html
git commit -m "Add my name and tagline"
```

**Edit 2 — Add your bio**

Replace `WRITE_A_SHORT_BIO_ABOUT_YOURSELF_HERE`. Then:

```bash
git add index.html
git commit -m "Add my bio"
```

**Edit 3 — Add your projects**

Replace `YOUR_PROJECT_1`, `YOUR_PROJECT_2`, `YOUR_PROJECT_3`, and the `DESCRIBE_IT_HERE` placeholders. Then:

```bash
git add index.html
git commit -m "Add my projects and interests"
```

**Edit 4 — Add your contact info**

Replace `YOUR_EMAIL_HERE`. Then:

```bash
git add index.html
git commit -m "Add my contact email"
```

**Edit 5 (Optional) — Add your profile picture**

Replace `profile/profile.png` with your own photo. Then:

```bash
git add profile/profile.png
git commit -m "Add my profile picture"
```

> **Why small commits?** Each commit should describe one thing you changed. This makes it easy to look back at your history and understand what happened at each step — a good habit for real projects too!

### Step 3 — Push

Once you're happy with all your commits, upload them to GitHub:

```bash
git push origin main
```

---

## Bonus Challenges

Done early? Try these:

- **Make a second edit** — change your bio or add another interest, then `add`, `commit`, and `push` again
- **View your history** — run `git log --oneline` to see your commits
- **Check your GitHub** — visit your fork on github.com and see your changes live

---

*Part of the **Git It Good Innit** workshop series.*
