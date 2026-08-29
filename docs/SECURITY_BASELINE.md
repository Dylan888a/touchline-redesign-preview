# Security baseline

Active controls in this stage:

- weekly Dependabot updates for GitHub Actions;
- Gitleaks on pull requests, main-branch pushes, manual runs and a weekly full-history scan;
- read-only workflow permissions and fixed action commit references.

Touchline is currently a static preview. This first controlled stage adds weekly GitHub Actions updates and automatic full-history secret scanning. CodeQL, dependency review and browser quality gates will be added when the preview becomes an actively built application.
