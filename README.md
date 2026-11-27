# AllOnScreen Quiz data

Quiz files read by the **AllOnScreen** Android app (read-only, public).

- `categories.json` : category list (`id`, `name.ko`, `name.en`, `file`). Add or remove a line to add or remove a category. The app detects changed files by itself (no version number needed); changes show up within ~5 minutes (GitHub cache).
- `*.txt` : one quiz = two lines (English, then Korean). Blank lines and lines starting with `//` `#` `$` `%` `&` `!` are ignored.
- `privacy.html` : privacy policy (served with GitHub Pages).

The hospital file is for language study only and is not medical advice.
