# agents

Custom reviewer agents in this repository:

- `fullstack-docker-php-js-mysql-reviewer.md` - Senior fullstack reviewer for PHP, JavaScript, MySQL, Docker, and Docker Compose changes before merge.
- `git-workflow-reviewer.md` - Senior Git workflow reviewer for branch hygiene, commit quality, PR readiness, and release safety.
- `job-search-cv-agent.md` - Job-search agent that tailors Rubén's CVs to specific job postings using `FINDWORK_HOME`.

## Environment

For the job-search agent, define the local workspace path:

```bash
export FINDWORK_HOME="/home/ruben/Documents/Obsidian/10_Projects/FindWork"
```
