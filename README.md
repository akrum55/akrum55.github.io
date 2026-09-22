# akrum55.github.io

Static pages required by Google's OAuth consent configuration for **Fantasy API
Worker**, a private single-user tool that emails fantasy sports reports to its
own owner.

Google will not let an app leave "Testing" publishing status without a published
home page, privacy policy and terms of service on a registered authorized
domain. These three files satisfy that requirement and nothing else. They
describe the program's actual behaviour — narrow Gmail send plus
self-verification of its own sent message, all state local to the owner's
machine — and make no claims beyond it.

- `index.html` — home page
- `privacy.html` — privacy policy
- `terms.html` — terms of service

No build step, no dependencies, no scripts, no cookies. Served by GitHub Pages
from the default branch root.
