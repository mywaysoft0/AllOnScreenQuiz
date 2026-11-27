# AllOnScreen Quiz data

Quiz files read by the **AllOnScreen** Android app (read-only, public).

- `categories.json` : category list (`id`, `name.ko`, `name.en`, `file`, `rev`). Raise `rev` when a file changes so the app downloads it again.
- `*.txt` : one quiz = two lines (English, then Korean). Blank lines and lines starting with `//` `#` `$` `%` `&` `!` are ignored.
- `privacy.html` : privacy policy (served with GitHub Pages).

The hospital file is for language study only and is not medical advice.
