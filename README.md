# Git 练习仓库

> 本仓库是配套视频的练习仓库，帮助大家学会提PR和Issues
>
> 此README文件由AI生成，我对文件又进行了一定修改

## 🎯 任务目标
1. Fork 仓库
2. 创建个人分支
3. 体验 Pull Request (PR) 流程
4. 尝试提交 Issues 反馈

## 💡 配套学习资源

1. **教学视频**：[https://www.bilibili.com/video/BV14tr5BREqf](https://www.bilibili.com/video/BV14tr5BREqf)
2. **讲义**：[点此查看](docs/Git入门教程.md)

## 📝 操作流程

### 第一步：Fork 仓库
1. 点击右上角 **Fork** 按钮，将本仓库复制到你的 GitHub 账号下  

### 第二步：创建个人分支
1. 进入你 Fork 后的仓库
2. 点击分支下拉菜单 → 输入你的 **GitHub 用户名** 作为分支名（示例：`zhangsan`）→ 点击 **Create branch**  ， 避免使用，中文/空格/特殊符号

### 第三步：添加学习笔记
1. 在仓库中进入 `notes` 文件夹
2. 新建文件：**`你的用户名.md`**（推荐）或 **`你的用户名.txt`**  
3. 在文件中写下你的 Git 学习心得（至少 3 行），例如：
```markdown
# 我的 Git 学习笔记
- 今天学会了 fork 仓库，原来这就是协作的起点！
- 分支命名很重要，要用英文用户名避免错误
- PR 是向别人项目贡献代码的标准方式
```

### 第四步：提交 Pull Request
1. 完成修改后，点击 **Add file** → **Create new file** 保存文件
2. 点击 **Contribute** → **Open a pull request**  
3. 检查信息后点击 **Create pull request**
4. 在描述框中简单说明（例如：`添加xxx的 Git 学习笔记`）→ 提交

## ❓ 常见问题
### Q：可以修改别人的笔记文件吗？
A：**不可以！** 每人只允许操作自己的文件，否则 PR 会被拒绝。

### Q：分支命名有要求吗？
A：**必须使用你的 GitHub 用户名**

### Q：PR 什么时候会被合并？
提交后 ，GitHub Actions会检查格式是否符合要求：
- ✅ 正确分支名
- ✅ 在 `notes/` 目录
- ✅ 文件名 = 用户名.md/txt
- ✅ 包含至少 3 行学习内容

符合要求后会自动合并到main分支

你可以在notes目录下寻找你的笔记文件

## 🌟 额外挑战
1. 在 Issues 区提交一个文档改进建议
2. 评论别人的 PR 给予鼓励
3. 尝试本地操作：用 Git 命令完成整个流程

---

**仓库维护者**：[@Mecamodore](https://github.com/Mecamodore)  
**最后更新**：2026 年 1 月 18 日  
*本仓库遵循 [MIT 许可证](LICENSE)，欢迎用于教学场景*
