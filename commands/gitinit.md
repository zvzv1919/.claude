---
argument-hint: ""
description: "Set git user.name and user.email for the current repo"
---

Ask me which identity to use for this git repo:

1. **Personal** — zvzv1919 / zvzv1919@gmail.com
2. **Work** — xuan.zhao / xuan@modal.com

Once I choose, run the corresponding commands:

For Personal:
```bash
git config user.name "zvzv1919" && git config user.email "zvzv1919@gmail.com"
```

For Work:
```bash
git config user.name "xuan.zhao" && git config user.email "xuan@modal.com"
```

After running, confirm the settings by running:
```bash
git config user.name && git config user.email
```
