---
title: "CI failure: main {{ github.sha }}"
labels: "CI failure"
---

[Test failure on main]({{ github.server_url }}/{{ github.repository }}/actions/runs/{{ github.run_id }}) while testing {{ github.sha }} by @{{ payload.sender.login }}
