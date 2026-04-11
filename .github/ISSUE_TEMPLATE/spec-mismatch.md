---
name: 'Spec mismatch'
about: Report a key that produces the wrong symbol
title: 'Mismatch: '
labels: ''
assignees: ''

---

**Checklist before opening**
- [ ] You have read the docs regarding the affected layer : https://onedeadkey.github.io/selenium/
- [ ] The `KB_LAYOUT_*` setting matches the keyboard layout on your computer
- [ ] The `KB_EMULATION_*` setting is enabled only if needed

**The mismatch itself**
- physical keys⁽¹⁾ + layer affected :
- what your keyboard produced :
- what you expected :

(1): Physical key names should correspond to the symbol produced by this key on a Qwerty keyboard, or left / right + tucked / home / reach for the thumb keys.

**Why did you expect this ?**
- Did you notice the correct symbol using different settings ?
- Did the docs show a different symbol ?
- When emulating a layout, is a key misplaced or not defined correctly ?

**Which keyboard(s) and settings do you use ?**
quacken_flex / corne / ferris …

```c
// Please paste the contents of your `settings.h` file in this code block,
// without empty lines or comments
```

**Additional context**
Have you made any changes to your keymap which may be relevant to this issue ? If so then please let us know, a link to your repo along with a quick summary should be enough, in most cases.
