# First Blog Post

## Introduction Cakes

Hello Welcome to my Blog. Cakes can hold a special place in our hearts and on our tables. Lets delve into the enchanting world of cakes anddiscover the secrets to baking and discover the secrets to baking irresistible creations right in your own kitchen.

![picture of cakes](/assets/cakewithrose.webp)

<ul>
    {% for post in site.posts%}
    <li>
        <a href="/blog{{ post.url }}">{{ post.title }}</a>
    </li>
     {% endfor %}
<ul>
