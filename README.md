# D.A MAQAM ANALYZER — STABLE UI V2

This package preserves the user's **STABLE** audio processor and GitHub Actions workflow and replaces only the JUCE editor files with a substantial native custom-drawn UI.

## UI implemented
- Dark navy / antique gold dashboard, resizable window
- Four tradition library navigation *labels* (not a complete sourced database)
- Live monophonic pitch trace and current note/frequency
- Start Learn, Stop/Analyze, Copy Results buttons
- Top-three candidate matches and fit scores
- Tuning guidance panel with honest limitations
- Decorative geometric rosette illustration (NOT a photographic oud)

## Critical limits
- The original STABLE pitch and heuristic classifier are unchanged.
- The culture dropdown is currently visual only; it does not filter the classifier.
- Fit scores are not probabilities. No automatic cents tuning, comprehensive maqam catalog, or validated identification accuracy.
- No licensed real oud photograph is included; source one and integrate only with rights to use it.
- This source is not compiled/tested on Windows in this environment; run GitHub Actions and verify inside Studio One.

## Build
Push the extracted *contents* (including `.github/workflows/build.yml`) to a test branch on GitHub. Run **Build Windows VST3** from Actions. Keep the existing working STABLE release backed up.
