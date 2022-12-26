1. Clone this repo
2. Create your private repo for the project, e.g. on bitbucket 
3. Create 2 access tokens at https://bitbucket.org/%username%/%reponame%/admin/access-tokens: with read rights (for pulling on remote) and with read+write rights (for local push) 
4. Create .env in the root
5. Add lines to the .env: 
REPO_PUSH_URL="https://x-token-auth:xxx"
REPO_PUSH_AUTHOR="xxx@bots.bitbucket.org"
REPO_PULL_URL="https://x-token-auth:xxx"
6. Run "npm install" 
7. Run "npm run export" - that will create folder "project" and export workflow and creds there
8. 