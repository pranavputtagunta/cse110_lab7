1) Answer: Within a Github action that runs whenever code is pushed

Why: Automated tests belong in CI so they run consistently in a clean environment on every push. This provides fast, repeatable feedback, catches regressions before code is merged, and enforces quality across the team. Running locally is useful as a developer hygiene step, but relying on manual runs or waiting until development is finished delays detection of bugs.

2) Answer: No

Why: End-to-end tests validate full user flows and system integration; they are slower and more brittle. For verifying a single function's output, unit tests are faster, isolated, and give clearer failure signals.

