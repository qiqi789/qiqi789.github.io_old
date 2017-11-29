### Welcome!
 
 <img src="/images/Qi_photo.png" style="display: block; width: 270px; height: 220px; float:left; margin-right:7px; margin-top:2%"  alt="That's me!" class="avatar" />
 
我的研究领域是机器学习和人工智能。我在美国密苏里大学哥伦比亚分校获得计算机科学博士学位，现任教于海南大学计算机科学系。

<div id="posts">
    <h2>Recent posts</h2>

    <ul class="posts">
    {% for post in site.posts limit:12 %}
    <li> <a href="{{ post.url }}">{{ post.title }}</a> <abbr>{{ post.date | date_to_string }}</abbr> </li>
    <!-- <li><span>{{ post.date | date_to_string }}</span> <span class="seperator">  </span> <a href="{{ post.url }}">{{ post.title }}</a></li> -->
    {% endfor %}
    </ul>



    <img class="inline-image" style="vertical-align: middle" alt="tags" src="/images/Book2.png" /> <a href="/posts">Archive of posting</a>

</div>


<a href="http://twitter.com/qiziqi" target="_blank">Follow me on twitter</a> <br>

<a href="https://www.goodreads.com/qiziqi" target="_blank">GoodReads' reading list</a> <br>

<a href="http://www.quora.com/reading_list" target="_blank">Quora reading list</a>

