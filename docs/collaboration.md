# 协作使用说明

## 分支命名
功能修改使用 feature/名称，文档修改使用 docs/名称。完成后通过 PR 合并到 main。

## 提交前检查
先运行 git status 和 git diff，确认修改范围，再执行 git add 和 git commit。

## 冲突处理
查看冲突文件，保留需要的内容并删除冲突标记，再运行 git add 和 git commit。

## 同步修改
合并 PR 后切回 main，运行 git pull --ff-only origin main。
