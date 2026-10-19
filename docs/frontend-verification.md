# Frontend review verification

2026-10-19: inline application JavaScript parses with node --check; diff check passes. This repository has no configured build/lint/test toolchain.

Local UI regression: created Frontend Review / Review meal, total $10, paid $2, due 18 October. The ledger showed $8 overdue. Entering a $3 payment previewed and saved $5 remaining. Reload preserved the customer, record and $5 balance. Payment allocation and local-storage keys/formats were untouched. No external messages, payments or deletions were performed.

Mobile quick entry at 390x600: sheet height 526px fits visible viewport; Tab from the final action wraps to Close; Escape returns focus to the original mobile trigger. CSS and visualViewport integration provide keyboard viewport clearance; a physical on-screen keyboard was not available. All six requested viewport widths (320, 390, 768, 1024, 1440, 1920) captured with no document overflow. Real screenshot frames record bottom-sheet entry. Reduced-motion styles inspected; OS emulation and Safari/Firefox remain unverified.

Before dashboard contains the original 18 seeded records; after captures include the additional local regression record, so amounts differ because of test data. Monetary text no longer counts through intermediate values; progress and short confirmation motion remain. Balance emphasis, filtered counts and dialog behavior refine the existing interface. Production publication is separate.
