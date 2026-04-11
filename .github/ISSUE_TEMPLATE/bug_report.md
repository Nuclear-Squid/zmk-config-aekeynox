---
name: Bug report
about: Report a malfunctionning key sequence (i.e. crash, key stuck…)
title: 'Bug:'
labels: bug
assignees: ''

---

**Describe the bug**
A clear and concise description of what the bug is.

**To Reproduce**
Steps to reproduce the problem (please be **very** careful about the timing of the sequence):
1. Press <key1>
2. Tap <key2>
3. Wait for tapping-term
3. Release <key1>
4. See error

Note:
- When referencing key names, please use the symbol produced by this key on a Qwerty keyboard, or left / right + tucked / home / reach for the thumb keys.
- Using the names of the underlying zmk behaviors is preferred, but not required.

Tip : try upping drastically the `TAPPING_TERM` value in your `settings.h`, if you struggle to keep a consistent timing when trying reproduce the issue reliably.

**Expected behavior**
A clear and concise description of what you expected to happen.

**Which keyboard(s) and settings do you use ?**
quacken_flex / corne / ferris …

```c
// Please paste the contents of your `settings.h` file in this code block,
// without empty lines or comments
```

**Additional context**
Have you made any changes to your keymap which may be relevant to this issue ? If so then please let us know, a link to your repo along with a quick summary should be enough, in most cases.
