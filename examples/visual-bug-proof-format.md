# Visual Bug Proof Format

This is the buyer-safe format MAXIM Ultra uses for visual/UI bug proof before a UI/UX audit is shared.

## Required Evidence

A valid visual bug proof should include:

- target URL or app screen
- screenshot or reproducible viewport
- visible issue description
- expected behavior
- actual behavior
- reproduction steps
- impact on user or buyer
- limitation note if evidence is incomplete

## Example Structure

```text
Target: [public URL or app screen]
Viewport: desktop 1440px or mobile 390px
Finding: button text wraps into adjacent control
Impact: user may miss primary action
Reproduction: open page, resize to mobile, inspect hero controls
Suggested fix: constrain button width and allow two-line label
Proof: screenshot path or public image URL
```

## Claim Limits

Do not claim a bug is business-critical unless there is evidence.
Do not claim a fix is accepted unless the target accepted it.
Do not include private screenshots, private account data, or sensitive buyer information.

## MAXIM Boundary

MAXIM can prepare visual proof locally. Browser automation, public publishing, paid vision calls, account login, and buyer outreach remain owner-gated.
