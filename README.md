# newIDEforVSci-ode
#some for experience 
#查看git提交的代码
# git log --format='%aN' | sort -u | while read name; do echo -en "$name\t"; git log --since ==2019-06-01 --until==2019-06-30  --author="$name" --pretty=tformat: --numstat | awk '{ add += $1; subs += $2; loc += $1 - $2 } END { printf "added lines: %s, removed lines: %s, total lines: %s\n", add, subs, loc }' -; done
#VScode 插件
#Auto Rename Tag
#Beautify
#Bracket Pair Colorizer
#Code Runner
#Code Spell Checker
#Debugger for Chrome
#ESLint
#File Peek
#Git History
#GitLens — Git supercharged
#HTML Boilerplate
#HTML CSS Support
#HTMLHint
#indent-rainbow
#Indenticator
#IntelliSense for CSS class names in HTML
#Material Icon Theme
#Monokai++
#npm Intellisense
#One Monokai Theme
#Output Colorizer
#Partial Diff
#Paste JSON as Code
#Path Autocomplete
#Path Intellisense
#REST Client
#Vetur
#vscode-icons
#Vue 2 Snippets
