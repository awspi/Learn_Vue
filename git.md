```shell
git clone git@github.com:awspi/vue.git
git add .
git commit -m "my first commit"
git push
```



git commit -a -m "update" ： 能提交修改过，但是没有添加到缓存区的文件(修改过的就能提交)

```shell
git status
git add -A
git commit -a -m "update"
git push origin main -f
```

