**My Blog**
1.修改主页：config/default_/params
    [sidebar]
    emoji    = "🍥" 修改状态标签
    subtitle = "我还要和生活再死磕几年。" 修改个性签名
    avatar   = "img/new-avatar.jpg" 修改头像
2.
3.写文章：
    每次写文章在content/post新建一个文件夹
    图片，文章都放在该文件夹中，文章正文建议固定命名index.md

    title: 文章标题
    date: 日期
    image: 文章封面
    description: 文章描述
    draft: false
    weight: 1 添加权重以排序
    categories:
        - 分类
    tags: 
        - 标签一
        - 标签二
    ---

    markdown开始写正文

    超链接： [chiy‘s blog](https://chiy5218-sys.github.io/my-blog/)

    其他写作相关格式详见 https://stack.cai.im/