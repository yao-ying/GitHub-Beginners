## 使用评论框   Comment Box

---

#### 评论发送之前  Before Publishing Comment

在任何一个议题`issue`或者代码提交合并请求`pull request`中均可见用于评论的输入框（如下图）

You can expect comment box in any `issue`or `pull reuqest` \(as screenshot below\)

![](/assets/comment.png)

点击`Leave a comment`处输入文本（可以直接粘贴系统剪切板中的图片），支持Markdown标记

当你看到下图所示的提示时，除项目所有人`Owner`和合作人`collaborator`之外均不可在当前页面发言（项目所有人的锁帖权限，见[管理个人项目](/repo-management.md)一章）

![](/assets/locked.png)

Click `Leave a comment` to type \(and you are allowed to paste image from system clipboard\) with Markdown tags support

①②切换输入或预览

③④⑤为此行文字应用标题、加粗、斜体、格式  add text formatting

⑥将此段标记为引用    mark the paragraph as quotation

⑦将文字标识为代码     mark word as code

⑧插入链接   Insert link

⑨⑩⑪插入点列表、序号列表或待办列表

⑫插入在[`Settings`页面](/settings.md)`Saved replies`中保存的快速回复短语

⑬@某人，或直接在输入@+用户名即可

![](/assets/reference.png)

⑭将这个`issue`或者`pull request`关联另一个`pull request`，评论发送后，关联的目标`issue`或`pull request`即可看到关联的标题或是否已关闭，如上图中为issue \#2，下图为已关闭的issue \#4

![](/assets/reference 4.png)

⑮点击`selecting them`选择文件插入，或从文件浏览器中拖入到输入框

⑯（你的项目repository中每个issue或pull request可见，他人项目中仅在由你创建的pull request或issue可见）点击即可关闭

⑰发送评论

---

#### 评论发送之后  After Publishing Comment

以下三个按钮可以用于在评论发送之后修改评论  The three following buttons are for modifying comment after it is published

![](/assets/comment buttons.png)

从左到右分别为添加emoji、修改以及删除

* 不可以删除`issue`或者`pull request`创建时的描述；除非你为项目所有人`Owner`，否则你也无权删除除创建描述之外的他人评论

* 使用修改按钮修改过的评论会被标记![](/assets/comment edited.png)

* Description during creating the issue or pull request can NOT be deleted; unless you are repo Owner, you will NOT have right to delete comment from others despite that

* Edited comment will be marked if you did edit it with that button ![](/assets/comment edited.png)



