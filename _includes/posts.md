<h2 id="posts" style="margin: 2px 0px 10px;">Posts</h2>

<style>
.post-title a {
    color: #39c;
    font-weight: bolder; 
}
</style>

<ol class="post_content">
  {% for post in site.posts %}
  <li>
  <div class="pub-row">
    <div class="col-sm-9" style="position: relative; padding-right: 15px; padding-left: 20px; padding-bottom: 10px;">
      <div class="post-title"><a href="{{ post.url }}">{{ post.title }}</a></div>
  </div>
  </li>
  {% endfor %}
  <br>
</ol>
