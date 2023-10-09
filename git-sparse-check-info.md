## 使用git sparse 提取数据操作
## 故障-库中出现非.git/info/sparse-checkout规则指定的目录/文件
使用下面命令删除不关心的目录
```bash
git read-tree -mu HEAD
```
