Backlog / Next tasks (from latest origin/main)

Context: latest commit merged init-workflow and created progress-state.json (bootstrap). Project provides a PDF merge web UI + API.

Proposed tasks:

1) Add API tests
- Create unit/integration tests for PDF merge endpoints
- Validate file uploads, error handling, and status codes

2) Improve CI
- Ensure pipeline runs tests and lints on PRs
- Add build badge to README

3) Enhance UI
- Add progress indicator that reads progress-state.json
- Improve error messages and upload UX

4) Workflow automation
- Complete init-workflow: ensure bootstrap steps write/read progress-state.json correctly
- Add retry/cleanup steps for failed jobs

5) Docs
- Add CONTRIBUTING.md and PR template
- Document API endpoints with examples

6) Dev ergonomics
- Add .env.example and README setup steps

Priority suggestions:
- High: 1,4,2
- Medium: 3,5
- Low: 6

If you want, I can create GitHub issues for each of these (requires permission/gh auth) or open local issue files. Tell me which you'd prefer.