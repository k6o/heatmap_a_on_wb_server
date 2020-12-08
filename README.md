#  Files for the heatmap 

Using geocode API. 
you need your own google API key for maps related API access 

















# heatmap_a_on_wb_server
files on webarena server

log 

git init  main
git add .
git commit -m "First commit"
git remote set-url origin https://<ユーザ名>@github.com/<ユーザ名>/<リポジトリ名>.git

///necessary ? 
git remote add origin remote repository URL

[k6o@doserate heatmap_a]$ git status
"# On branch master" 
nothing to commit (working directory clean)
[k6o@doserate heatmap_a]$ git push origin main
Password: 
error: src refspec main does not match any.
error: failed to push some refs to 'https://k6o@github.com/k6o/heatmap_a_on_wb_server.git'
[k6o@doserate heatmap_a]$ git push origin HEAD:master
Password: 
Counting objects: 7, done.
Compressing objects: 100% (7/7), done.
Writing objects: 100% (7/7), 50.84 KiB, done.
Total 7 (delta 0), reused 0 (delta 0)
To https://k6o@github.com/k6o/heatmap_a_on_wb_server.git
 * [new branch]      HEAD -> master
 
 nothing added to commit but untracked files present (use "git add" to track)
[k6o@doserate heatmap_a]$ git push origin HEAD:master
Password: 
To https://k6o@github.com/k6o/heatmap_a_on_wb_server.git
 ! [rejected]        HEAD -> master (non-fast-forward)
error: failed to push some refs to 'https://k6o@github.com/k6o/heatmap_a_on_wb_server.git'
To prevent you from losing history, non-fast-forward updates were rejected
Merge the remote changes before pushing again.  See the 'Note about
fast-forwards' section of 'git push --help' for details.
[k6o@doserate heatmap_a]$ git status
# On branch master
# Untracked files:
#   (use "git add <file>..." to include in what will be committed)
#
#       all_active_accouns_geo_formated_no_none.txt
nothing added to commit but untracked files present (use "git add" to track)
[k6o@doserate heatmap_a]$ git add
Nothing specified, nothing added.
Maybe you wanted to say 'git add .'?
[k6o@doserate heatmap_a]$ git add all_active_accouns_geo_formated_no_none.txt 
[k6o@doserate heatmap_a]$ git status
# On branch master
# Changes to be committed:
#   (use "git reset HEAD <file>..." to unstage)
#
#       new file:   all_active_accouns_geo_formated_no_none.txt
#
[k6o@doserate heatmap_a]$ git commit -m "2nd Commit" 
[master 0609f05] 2nd Commit
 1 files changed, 4462 insertions(+), 0 deletions(-)
 create mode 100644 all_active_accouns_geo_formated_no_none.txt
 
