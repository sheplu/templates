---
name: Internationalization Issue (i18n)
about: Report a localization or internationalization problem
title: "[I18N] Short description"
labels: [i18n, localization]
assignees: []
---

## Summary

Describe the localization/i18n problem.

---

## Locale(s) Affected

(e.g., fr-FR, de-DE, ar, zh-Hant)

---

## Issue Type

- [ ] Untranslated/missing string
- [ ] Incorrect formatting (date/time/number/currency)
- [ ] Pluralization/gender rules
- [ ] Text truncation/overflow
- [ ] RTL/LTR layout or mirroring
- [ ] Locale fallback wrong
- [ ] Sorting/collation
- [ ] Time zone handling
- [ ] Other: …

---

## Steps to Reproduce

1. …
2. …
3. …

---

## Expected vs. Actual

Provide concrete examples in the target locale(s).

---

## Affected Keys/Resources

Message IDs / namespaces / files (if known). Include source text and expected translation/context.

---

## Environment

- App version / commit:
- OS/Device:
- Browser/Runtime:
- Selected locale & time zone:

---

## Evidence

Screenshots or short videos demonstrating the issue.

---

### Checklist

- [ ] Strings are externalized (no hard-coded text)
- [ ] ICU messages/formatters used where needed
- [ ] Correct locale used for formatting
- [ ] RTL/LTR handled (layout, icons, alignment)
- [ ] No string concatenation that breaks grammar
