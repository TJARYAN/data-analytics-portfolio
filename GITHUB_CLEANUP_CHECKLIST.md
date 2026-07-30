# GitHub Profile Cleanup Checklist

I can't log into GitHub for you, so here's exactly what to click, in order. ~20 minutes total.

## 1. Profile README (5 min)
- [ ] Create a repo named exactly your GitHub username → Public → check "Add a README"
- [ ] Paste in the content from `PROFILE_README_TEMPLATE.md` (fill in your name, LinkedIn, email)
- [ ] Commit — it now shows at the top of your profile automatically

## 2. Audit your existing repos (10 min)
Go to `github.com/yourusername?tab=repositories` and sort by "Last updated." For each repo, ask:

| Keep as-is | Archive | Delete |
|---|---|---|
| Actively used / part of this portfolio | Old coursework/tutorial repos with some historical value, not embarrassing, but not worth showing | Broken/empty repos, forked-but-untouched repos, duplicate test repos, anything with committed secrets or personal data |

- **Archive** (Settings → General → Danger Zone → Archive this repository) keeps it visible but read-only and clearly marked "archived" — good for old-but-not-shameful work.
- **Delete** (Settings → General → Danger Zone → Delete this repository) — permanent, use for genuine clutter.
- Rename repos with vague names ("test," "untitled," "project1") to something descriptive before deciding, since a bad name alone can make a repo look like clutter when the content is fine.

## 3. Pin your best repos (2 min)
- Go to your profile → click "Customize your pins"
- Pin (in order of priority):
  1. This portfolio repo (once pushed)
  2. Your username/username profile-README repo (optional, but shows intentionality)
  3. Any other genuinely strong individual project (max 6 total pins)
- Unpin anything unrelated to the DA track (old full-stack experiments, etc.) — recruiters look at pinned repos first.

## 4. Commit hygiene going forward (ongoing)
Since there isn't much history yet, this is the easy part — build good habits from here:
- [ ] Write commit messages as short present-tense actions: `Add cleaned data scaffold for Project 1`, not `update` or `final final v2`
- [ ] Commit in logical chunks (e.g. one commit per project stage) rather than one giant commit per week
- [ ] Add a `.gitignore` (included in this package) so you never accidentally commit temp files, `.DS_Store`, or Excel lock files (`~$*.xlsx`)

## 5. Bio & profile basics (2 min)
- [ ] Add a one-line bio under your name: e.g. "Data Analyst in training | BFSI background | Spreadsheets → SQL → Power BI → Python"
- [ ] Add location: Bangalore, India
- [ ] Add your portfolio repo link in the profile "Website" field once pushed
