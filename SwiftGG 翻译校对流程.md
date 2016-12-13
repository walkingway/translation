# SwiftGG 翻译校对流程

译者翻译流程：

1. 首先 fork 这个仓库，请先从 master 分支上 git checkout -b translate 一个新的 translate 分支来翻译文章。
2. 在仓库的主目录中，新建自己负责翻译的 Blog 文件夹。以后关于该 Blog 所有译文都放置在对应的文件夹中。
3. 翻译完成后去主仓库开 **issue**，标题为『翻译文章中文标题』，内容粘贴上相应的 **commit 链接**，将右边的 **Labels** 标签修改为『待校对』，**Assignees** 选择和自己组队校对的小伙伴。
4. 校对的小伙伴校对完成后，根据其修改意见（comment 形式）对译文进行修正，将 issue label 改为『待定稿』。
5. 发送 Pull Request，**注意：发 PR 的时候请注意检查，一个 PR 只能有一篇文章，切勿两篇或多篇 合并到一个 PR**。

校对者流程：

1. 在接收到译者分配的校对任务后，进入主仓库相关 issue，将左侧 label 改为『校对中』。
2. 进入译者的 **commit 链接**，通过添加 comment 的方式对译者内容进行校对。
3. 校对完成后，将 issue label 改为『校对完成』，并把 **Assignees** 重新指定给译者。


