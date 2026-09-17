# SkillGrove / 卡片大师 — Privacy Policy

Public hosting for the privacy policy of the Android app **SkillGrove** (Chinese name
**卡片大师**, package `com.skillgrove.app`).

- Published page: <https://hexna.github.io/skillgrove-privacy/>
- This is the URL declared in Google Play Console → App content → Privacy policy.

## Source of truth

The canonical text lives in the app repository at `docs/privacy-policy.html` (with a
Markdown twin at `docs/privacy-policy.md`). This repo only holds the published copy.

To update the policy, edit it in the app repo first, then re-copy it here:

```bash
cp docs/privacy-policy.html /tmp/skillgrove-privacy-site/index.html
cd /tmp/skillgrove-privacy-site
git commit -am "policy: sync from app repo" && git push
```

## Notes

- The page is a single self-contained HTML file: no external CSS, JS or images.
- It carries both languages, English and Chinese (`#en` / `#zh`).
- Keep the URL stable — changing it after release requires re-review on Google Play.
