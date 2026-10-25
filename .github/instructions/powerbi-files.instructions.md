---
applyTo: "**/*.tmdl,**/*.pbip,**/*.pbir,**/*.json,**/*.m,**/*.dax"
---
# Power BI file-specific standards
- Do not commit cache files, local settings, credentials, binary data extracts, or development-only connection values.
- Preserve valid PBIP structure and UTF-8 text encoding.
- DAX must use explicit measures, clear names, appropriate format strings, and variables where they improve clarity or avoid repeated evaluation.
- Relationship changes must document cardinality, filter direction, active state, and intended analytical path.
- Power Query changes must consider query folding, types, parameters, reusable staging, and environment portability.
- Report changes must consider titles, alt text, focus order, color usage, visual density, navigation, mobile behavior, and measure usage.
