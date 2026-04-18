# Project and Repo Plan

## Part 1: Project Plan

### Goal
Produce a reproducible data analysis document using Quarto that
covers airport passenger traffic trends, Monte Carlo numerical
integration, and GenAI prompting comparison.

### Needs
- R with tidyverse, rvest, knitr, kableExtra installed
- Wikipedia airport data (scraped via public URL)
- Calcium dataset (provided by instructor)
- Claude Sonnet 4.6 for GenAI prompting section
- Quarto installed and configured for PDF output

### Steps
1. Scrape and wrangle airport passenger data from Wikipedia
2. Build airport table and line plot
3. Write generatePoints function for Monte Carlo simulation
4. Build four Monte Carlo plots at n=10, 100, 1000, 10000
5. Develop plan-informed GenAI prompt and capture response
6. Write narrative for all sections
7. Configure YAML header and code chunk options
8. Render to PDF and verify output

---

## Part 2: Repo Plan

### Goal
Set up and maintain a GitHub repo that demonstrates proper
version control practices including branching, issues, commits,
and pull requests.

### Needs
- GitHub account
- Template repo from STAT 184 course
- All HW 4.3 deliverable files (QMD, PDF, images)

### Steps
1. Create repo from course template
2. Create dev-akil branch off main
3. Create at least two Issues and assign to self
4. Upload all deliverable files to dev-akil branch
5. Write README.md covering all required elements
6. Write PLAN.md (this file)
7. Commit all changes with meaningful messages linked to issues
8. Create pull request from dev-akil to main with title and
   description
9. Merge pull request to bring main up to date
10. Verify main branch contains all final files
