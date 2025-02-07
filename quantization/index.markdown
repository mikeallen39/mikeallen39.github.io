---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: 我的博客首页
---

# 欢迎来到我的技术博客！

这里是关于人工智能、机器学习和深度学习的技术分享平台。以下是最新发布的文章：

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date_to_string }}
    </li>
  {% endfor %}
</ul>

---

### 关于我
我是 [Mike Allen]，一名专注于人工智能和深度学习的研究者。欢迎关注我的博客，了解更多技术干货！