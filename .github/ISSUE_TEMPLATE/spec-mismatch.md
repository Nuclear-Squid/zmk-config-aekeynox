---
name: 'Spec mismatch'
about: Report a key that produces the wrong symbol
title: 'Mismatch: '
labels: ''
assignees: ''

---

## Checklist before opening
- [ ] You have read the docs regarding the affected layer: https://onedeadkey.github.io/selenium/
- [ ] The `KB_LAYOUT_*` setting matches the keyboard layout on your computer
- [ ] The `KB_EMULATION_*` setting is enabled only if needed

## The mismatch itself
- physical keys⁽¹⁾ + layer affected:
- what your keyboard produced:
- what you expected:

(1): Physical key names should correspond to the symbol produced by this key on a Qwerty keyboard, or left / right + tucked / home / reach for the thumb keys.

## Why did you expect this?
- Did you notice the correct symbol using different settings?
- Did the docs show a different symbol?
- When emulating a layout, is a key misplaced or not defined correctly?

## Which keyboard and what settings do you use?
- keyboard: quacken_flex, corne, ferris…
- settings: list of enabled options in `settings.h`
- link to the commit that stardet the GitHub Action
