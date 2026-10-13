---
argument-hint: ""
description: "Set git user.name, user.email, and GitHub credential account for the current repo"
---

Ask me which identity to use for this git repo:

1. **Personal** — zvzv1919 / zvzv1919@gmail.com (GitHub account: zvzv1919)
2. **Work** — Joshua Zhao / xuan@modal.com (GitHub account: joshua-zhao20)

Once I choose, run the corresponding commands:

For Personal:
```bash
git config user.name "zvzv1919" && git config user.email "zvzv1919@gmail.com" && git config credential.username "zvzv1919"
```

For Work:
```bash
git config user.name "Joshua Zhao" && git config user.email "xuan@modal.com" && git config credential.username "joshua-zhao20"
```

After running, confirm the settings by running:
```bash
git config user.name && git config user.email && git config credential.username
```
