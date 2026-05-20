1) Answer: Within a Github action that runs whenever code is pushed

Why: Automated tests belong in CI so they run consistently in a clean environment on every push. This provides fast, repeatable feedback, catches regressions before code is merged, and enforces quality across the team. Running locally is useful as a developer hygiene step, but relying on manual runs or waiting until development is finished delays detection of bugs.

2) Answer: No

Why: End-to-end tests validate full user flows and system integration; they are slower and more brittle. For verifying a single function's output, unit tests are faster, isolated, and give clearer failure signals.

3) Navigation mode analyzes a full page load. It starts from a fresh load, records everything from first request to settled state, and gives performance metrics. 

Snapshot mode analyzes the page in its current state without reloading it. It captures the current DOM, which makes it useful for inspecting a page after a specific interaction. Can't measure performance metrics. 

4) We could add a language attribute to html elements to let screen readers know what language the content is in. 

The diagnostics section says we we could save around 1127 kB of unused JS. 

We could also add meta descriptions to help improve search engine optimization by helping crawlers understand the page. 