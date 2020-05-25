# Let's Git Coding!
  That's an intentional pun, but the meaning is to use git while coding. I wish I knew how to use Github years ago when I started learning how to code because this would have helped me in not only documenting but in improving my skills over the years. Using Git is helpful to get back to where you left, and it is helpful to make use of your college projects and assignments or even the codes you wrote for fun. Using Github is helpful for teams even if they weren't all programmers, it is still helpful for them be part of the project. I find Github very helpful and I can't wait to contribute through this platform. Let's git coding! :D

# Contact Information
  <a href="https://github.com/{{site.github_username}}"> Contact me on Github</a>

# My Projects
  Although all of my older projects weren't developed while using Github, I intend to make this update. Additionally, I intend to make my future projects on Github.
  <ul>
    {% for post in site.posts %}
      <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
      </li>
    {% endfor %}
  </ul>
