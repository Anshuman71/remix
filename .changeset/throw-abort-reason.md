---
"@remix-run/dev": minor
"@remix-run/server-runtime": minor
---

Add `future.v7_throwAbortReason` flag to instead throw `request.signal.reason` when a request is aborted instead of a custom `new Error()` with a message such as `query() call aborted`/`queryRoute() call aborted`
