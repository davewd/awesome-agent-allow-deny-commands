# awesome-agent-allow-deny-commands
Repo name says it all - a simple list of allow / Deny list examples to make agents more reasonable.


##  github.copilot.chat.agent.terminal.allowList

### No Drama's everyone agrees
- cd [0-9a-zA-Z.]+
- npm test
- npm run test
- npm run lint
- echo
- ls
- Get-ChildItem
- cat
- Get-Content
- pwd
- Get-Location
- cd
- wget
- ping
- nc
- nslookup
- ps
- ps aux
- grep
- head
- tail
- less
- more
- find
- which
- where
- whoami
- id
- mount
- env
- printenv
- history
- wc
- sort
- uniq
- cut
- awk
- sed
- tr
- xargs
- tee
- diff
- cmp
- file
- stat
- tree
- git status
- git log
- git diff
- git show
- git branch
- git remote
- git config
- git clone
- git pull
- npm test
- yarn test
- pnpm test
- flutter test
- dart test
- cargo test
- go test
- pytest
- python -m pytest
- npm run lint
- eslint
- tslint
- timeout
- sleep
- wait
- mkdir
- touch
- ln
- cp
- mv
  
### Some questions
"dig",
- telnet",
- "Write-Host",
  "Set-Location",
							"fg",
							"bg",
							"jobs",
							"nohup",
							"curl",

							"uname",
							"date",
							"uptime",
							"df",
							"du",
							"free",
							"top",
							"htop",
							"lsof",
							"netstat",
							"ss",
							"lsblk",
### Examples of possibilities - community doesnt suggest they're wise
"git push",
							"git add",
							"git commit",
							
							"npm run",
							"yarn run",
							"pnpm run",
							"flutter build",
							"cargo build",
							"go build",
							"dotnet build",
							"npm install",
							"yarn install",
							"pnpm install",
							"flutter pub get",
							"cargo fetch",
							"go mod tidy",
							"npm start",
							"yarn start",
							"flutter run",
							"cargo run",
							"go run",
  
							"flutter analyze",
							"cargo clippy",
							"go vet",

##   github.copilot.chat.agent.terminal.denyList

### No Drama's everyone agrees
- .*rm -rf.*
- curl .* | sh
- bash

### May cause some harm

### USe at your own peril - no community consensus as to above two lists



Security discussion articles:
- [Cursor AI Security Flaw: Autorun Denylist](https://www.backslash.security/blog/cursor-ai-security-flaw-autorun-denylist)
