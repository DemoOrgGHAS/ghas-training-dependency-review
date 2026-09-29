# Safety notice
This repository is a static training fixture for GitHub security scanning.
- No malware, payloads, network listeners, authentication bypass, or working credentials.
- Do not deploy or execute the sample application code.
- All secrets are synthetic and intentionally invalid.
- Use only in a dedicated public training repository with no production data.

# Lab 4: Dependency review in a pull request
Goal: show how a dependency change is reviewed before merge.

The repository is metadata-only. Create a branch and add a dependency to `package.json`, then open a PR. The workflow reviews dependency changes. Do not install or run packages.
