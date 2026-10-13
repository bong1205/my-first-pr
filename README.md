# my-first-pr

练习提交第一个 Pull Request（PR）。

## 这个仓库是做什么的

这是一个练习用的仓库，用来熟悉在 GitHub 上协作的基本流程：从新建分支到合并修改。

## 提交 PR 的基本步骤

1. **新建分支**：`git switch -c 分支名`，在副本上修改，不影响主分支 `main`。
2. **修改文件**：做一处小而清楚的改动。
3. **提交修改**：`git add` 选中改动，`git commit -m "说明"` 记录这次修改。
4. **推送分支**：`git push -u origin 分支名`，把分支上传到 GitHub。
5. **创建 PR**：`gh pr create`，或在 GitHub 网页上点 **Compare & pull request**。
6. **审阅并合并**：在 PR 页面查看 **Files changed**，确认无误后点 **Merge pull request**。
