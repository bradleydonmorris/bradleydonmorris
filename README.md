- 👋 Hi, I’m @bradleydonmorris
- 👀 I’m interested in ... Not doing these boring intros
- 🌱 I’m currently learning ... how to make this go away
- 💞️ I’m looking to collaborate on ... solutions to get rid of this
- 📫 How to reach me ... carrier pigeon

<!---
bradleydonmorris/bradleydonmorris is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

### My Bash Aliases
```bash
alias glog1="git log --graph --abbrev-commit --decorate --format=format:'%C(bold blue)%h%C(reset) - %C(bold green)(%ar)%C(reset) %C(white)%s%C(reset) %C(dim white)- %an%C(reset)%C(auto)%d%C(reset)' --all"
alias glog2="git log --graph --abbrev-commit --decorate --format=format:'%C(bold blue)%h%C(reset) - %C(bold cyan)%aD%C(reset) %C(bold green)(%ar)%C(reset)%C(auto)%d%C(reset)%n''          %C(white)%s%C(reset) %C(dim white)- %an%C(reset)'"
alias glog=glog1
alias gacno="git add .|git commit --amend --no-edit"
alias gst='git status'
alias gp='git push'
alias gpforce='git push --force'
alias gfiles='{ git diff --name-only; git ls-files --others --exclude-standard; } | sort'
alias gl5="git log -n 5 --graph --abbrev-commit --decorate --format=format:'%C(bold blue)%h%C(reset) - %C(bold green)(%aI, %ar)%C(reset) %C(white)%s%C(reset) %C(dim white)- %an%C(reset)%C(auto)%d%C(reset)' --all"
```

```bash
"/c/Program Files/Notepad++/notepad++.exe" $USERPROFILE/.bashrc
"/c/Program Files/Notepad++/notepad++.exe" $USERPROFILE/.bash_profile
```
