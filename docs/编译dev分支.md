```bash
# 编译Platypus的dev分支
# 文件web/ttyd/package.json中修改"node-sass": "^5.0.0"为"node-sass": ">=5.0.0"
find . |grep "\.go$" | xargs sed -i "s/github.com\/WangYihang\/Platypus/Platypus/g"
make release
```

