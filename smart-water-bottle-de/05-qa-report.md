# Taktflasche prototype QA

**Verdict** Pass for a standalone concept demonstration. No blocking findings.

## Passed

| Area | Result |
| --- | --- |
| LED demo | In headless Chrome, mouse click, Enter, and Space turned on the cap light. The light reset automatically and the live status reported activation and completion. |
| Keyboard | Tab reached the navigation link and demo button in order. The button showed a visible focus outline. |
| Responsive layout | At 320, 375, 480, 760, 768, 1024, and 1440 CSS pixels, measured page and element bounds stayed within the viewport horizontally. |
| Motion and contrast | Reduced-motion emulation disabled the LED transition. The sampled muted text and CTA text contrast ratios were 7.04:1 and 9.82:1. |
| Offline behavior | The file loaded and the demo worked in an offline browser context. No external requests, JavaScript errors, or data-entry forms were observed. |
| German copy and claims | The hero and benefits match the approved German copy. The page labels the product as a concept and leaves specifications and availability open. The demo follows the agreed scope without pricing, checkout, or medical claims. |

## Recommended

For a moderated mobile test, verify whether participants at 320–375 CSS pixels can see the illustration when they activate the button. The visual sits below the copy at these widths, and the demo light resets after 3.5 seconds. If participants miss the preview, move activation closer to the illustration or offer a persistent state.

The browser check covered the standalone file. Screen-reader announcements were checked through status markup and text changes. Assistive technology devices and physical product claims were outside this test.
