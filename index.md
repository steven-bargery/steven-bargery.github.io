# Steve's website

## About Me

I am a certified IT Technician with over 10 years experience and comprehensive knowledge of technical support, hardware deployment, network configurations and web development.

I enjoy keeping fit whether it be visiting the local kickboxing gym or hiking in one of America's National Parks.

## My Projects
Here is a list of my GitHub projects I have been working on:
<ul>
  <li><a href="https://steven-bargery.github.io/HelloWorld/">Hello World Project</a></li> <li><a href="https://github.com/steven-bargery/Grand-National-Sweepstake">Grand National Sweepstake Repo</a></li>
</ul>

## My Blog
I am blogging my journey of learning GitHub
<ul>  
  {% for post in site.posts %}    
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>  
  {% endfor %}
</ul>

## Get in Touch
<ul>
  <li><a href="https://twitter.com/{{ site.twitter_username }}">Twitter</a></li>
  <li><a href="https://github.com/{{ site.github_username }}">GitHub</a></li>
</ul>
