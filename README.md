# newIDEforVSci-ode
#some for experience 
#查看git提交的代码
# git log --format='%aN' | sort -u | while read name; do echo -en "$name\t"; git log --since ==2019-06-01 --until==2019-06-30  --author="$name" --pretty=tformat: --numstat | awk '{ add += $1; subs += $2; loc += $1 - $2 } END { printf "added lines: %s, removed lines: %s, total lines: %s\n", add, subs, loc }' -; done
#
