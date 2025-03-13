---
title: "CI failure: {{ sha | slice(7) | first }} on `main`"
labels: "CI failure"
---

Commit {{ sha }} by @{{ payload.sender.login }} did not pass CI.
See also: {{ payload.status.target_url }}
