## Hi
- 👋 Hi, I’m @ibenitez
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

## Bitcoin
- [2026 purchasing plan](bitcoin-2026.md)

## Posts
{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}

## Tags
{% for tag in site.tags %}
- {{ tag[0] }}
  {% for post in tag[1] %}
  * [{{ post.title }}]({{ post.url }})
  {% endfor %}
{% endfor %}


<!---
ibenitez/ibenitez is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
