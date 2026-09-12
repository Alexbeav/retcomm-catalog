# Preserved development history

The default branch is the maintained source. The tags below preserve earlier source or separate candidates at exact commits.
No archived candidate gains new build, package, or gameplay acceptance through this cleanup.

A tag is a fixed source snapshot. Existing tree URLs and `git clone --branch <name>` can select these tags.
For local inspection, use `git fetch origin --tags` followed by `git switch --detach refs/tags/<name>`.
To resume development, create a temporary branch from the tag. Do not move an archive tag.

| Tag | Preserved commit | Disposition |
|---|---|---|
| `codex/wave1-wave2-bulk-submission-20260906` | [`257f5db0d984a7e43d1034fb258620547cecaa98`](https://github.com/Alexbeav/retcomm-catalog/tree/257f5db0d984a7e43d1034fb258620547cecaa98) | Contribution source preserved; upstream acceptance remains a separate record. |
| `codex/wave3-submission-20260907` | [`f71ddac1db31f4ed7a74cca9c300d110f9c021d2`](https://github.com/Alexbeav/retcomm-catalog/tree/f71ddac1db31f4ed7a74cca9c300d110f9c021d2) | Contribution source preserved; upstream acceptance remains a separate record. |

Recorded 2026-09-13. Existing version tags and releases remain unchanged.
