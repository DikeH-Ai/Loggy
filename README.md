# Github User Activity CLI:

https://roadmap.sh/projects/github-user-activity

Github User Activity is a simple CLI tool for monitoring user activities.

## How does it work
- Prouduce a user-friendly output for each of these events:
    - Starred Repositories (WatchEvent)
    - Pushes (PushEvent)
    - Forks (ForkEvent)
    - Pull Requests (PullRequestEvent)
    - Issues (IssueEvent)
    - Issue Comments (IssueCommentEvent)

## Requirements
- Provide the GitHub username as an argument when running the CLI.
- Fetch the recent activity of the specified GitHub user using the GitHub API.
- Display the fetched activity in the terminal.

## How to Run

1. **Clone the repository**:
   git clone https://github.com/DikeH-Ai/Python-projects.git

- **Optional**:
    - make file executable
    chmod +x github-usr-activity.py

2. **Run file**
    - option 1:
        - pass CLI argument
        python github-usr-activity.py <username>
        
        - pass argument within program operation
        python github-usr-activity.py