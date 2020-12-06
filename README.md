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
# On branch master
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
 
 
 
