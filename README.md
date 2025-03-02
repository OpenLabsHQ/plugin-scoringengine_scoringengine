# plugin-scoringengine_scoringengine
Playbook to install https://github.com/scoringengine/scoringengine using Docker.

Current plan:
1) Install Docker using: https://github.com/geerlingguy/ansible-role-docker
2) Git clone scoringengine/scoringengine
3) Copy in user's competition.yaml file
4) docker compose up
5) Replace sponsors with custom images?
6) Connectivity checks
  - Web Login: White, Red, Blue teams
