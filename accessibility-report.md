# Accessibility Report — Clinton Hamisi

**Page audited:** `index.html`
**Tools used:** Chrome Lighthouse, WAVE Web Accessibility Tool
**Date:** 19th September 2026

---

## Tools Used

- **Chrome DevTools Lighthouse** — built-in audit
- **WAVE** — https://wave.webaim.org/

---

## Issues Found

### Issue 1: Missing Alt Text

- **Severity:** High
- **Location:** `<img>` tag in `index.html`
- **Problem:** The image had no `alt` attribute.
- **Fix:** Added `alt="Clinton Hamisi's profile photo"`

### Issue 2: Missing Language Attribute

- **Severity:** Medium
- **Location:** `<html>` tag
- **Problem:** The `<html>` tag was missing `lang="en"`.
- **Fix:** Changed to `<html lang="en">`

### Issue 3: Heading Hierarchy

- **Severity:** Low
- **Location:** Body content
- **Problem:** Needed to confirm headings go `h1 → h2` without skipping.
- **Fix:** Verified: `<h1>Clinton Hamisi</h1>` followed by `<h2>` sections. ✅

### Issue 4: Non-descriptive Link Text

- **Severity:** Medium
- **Problem:** Avoided generic "click here" text.
- **Fix:** Used descriptive text: "MDN Web Docs" and the email address itself.

---

## Fixes Applied

| Issue | Before | After |
|---|---|---|
| Image alt | `<img src="...">` | `<img src="..." alt="Clinton Hamisi's profile photo">` |
| Language | `<html>` | `<html lang="en">` |
| Link text | "click here" | "MDN Web Docs" |
| Headings | Mixed | `h1 → h2` hierarchy |

---

## Screenshots

### Lighthouse Accessibility Score
![Lighthouse score](./images/lighthouse.png)

### WAVE Results
![WAVE results](./images/wave.png)

---

## Conclusion

After fixes, the Lighthouse accessibility score is now **100**.
All images have alt text, headings follow proper hierarchy, links are
descriptive, and the page has the correct `lang` attributes.

---

