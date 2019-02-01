#### gitment

Gitment 是基于 GitHub Issues 的评论系统。支持在前端直接引入，不需要任何后端代码。可以在页面进行登录、查看、评论、点赞等操作，同时有完整的 Markdown / GFM 和代码高亮支持。尤为适合各种基于 GitHub Pages 的静态博客或项目页面。想了解具体效果，可以点击查看官方Demo Page：[Gitment Demo](https://imsun.github.io/gitment/), 参考文档 [gitment-introduction](https://imsun.net/posts/gitment-introduction/)


## 欢迎简化的 jekyll 主题

这个 jekyll 主题的目的是使一个简化的主题。

## 使用

首先，请阅读 [Jekyll • Simple, blog-aware, static sites - Transform your plain text into static websites and blogs](http://jekyllrb.com/) 让你安装 Jekyll 。

---

然后，参见 `_config.yml` 

    # Site settings
    encoding: utf-8
    title: LuckFairy 
    description: LuckFairy的个人博客
    baseurl: "http://LuckFairy.github.io" 
    # baseurl: ''
    github_username:  LuckFairy
    paginate: 5
    paginate_path: "/page:num"
    footer_books: "书旅"
    footer_github: "GitHub"
    footer_resume: "简历"
    footer_resume_site: "http://LuckFairy.github.io/resume/index.html"
    port: 8070
    gems: [jekyll-paginate]

需要你去更改的配置

    * `title` as your site's title
    * `description` as your site's description
    * `baseurl` is empty when you are running localhost with the `port` and the long baseurl is your site's url
    * `github_username` is your github's name
    * `paginate` as the number of blog every page
    * `paginate_path` as the format of the paginate
    * `footer_*` as the description of the footer link
    * `port` as the prot when you are running localhost
    * `gems` as an array contains some plugins you are using
    
## 许可证
麻省理工学院执照 (mit)
版权所有 (c) 2015 ~ 2019 LuckFairy
在此, 任何人免费获得本软件的副本和相关文档文件 (以下简称 "软件"), 不受限制地处理本软件, 包括但不限于使用、复制、修改、合并、发布、分发、再许可和/出售本软件的副本, 并允许本软件所提供的人这样做, 但须符合以下条件:
上述版权声明和本许可声明应包含在本软件的所有副本或大部分内容中。
本软件按 "原样" 提供, 不附带任何形式的担保, 包括或暗示的, 包括但不限于可扩展性义务的担保, 适合特定的采购和不担保。在任何情况下, 作者或版权持有人都应就任何索赔行为承担责任, 损害或其他责任, 无论是在合同、酷刑或其他行为中, 从软件、使用本软件或与软件中的使用或其他不相关的情况下, 从软件、软件中退出或与软件或其他不符合本软件。
