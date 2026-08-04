## Hey There 👋

Im Sunny, an engineering Grad based in India

I am not into traditional learning, I learn as I build and work on new exciting ideas.

name: Example
uses: lowlighter/metrics@latest
with:
  template: repository
  filename: metrics.repository.svg
  token: ${{ secrets.METRICS_TOKEN_WITH_SCOPES }}
  user: lowlighter
  repo: metrics
  plugin_lines: yes
  plugin_followup: yes
  plugin_projects: yes
  plugin_projects_repositories: lowlighter/metrics/projects/1
