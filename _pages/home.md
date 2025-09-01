---
layout: splash
title: ""
permalink: /
---

<div id="intro">
  <h1 id="intro-title">Hello, I'm Amir Hossain Raj</h1>
  <h2 id="intro-subtitle">I'm a PhD student at George Mason University studying AI and Robotics</h2>
  <div id="intro-description">
    <div id="intro-text-wrapper">
      <p>
        I work with <a href="https://cs.gmu.edu/~xiao/">Dr. Xuesu Xiao</a> in the <a href="https://cs.gmu.edu/~xiao/RobotiXX/lab.html">RobotiXX Lab</a> at <a href="http://gmu.edu/">George Mason University</a>.
      </p>
      <p>
        My research focuses on <b>Generative AI, Reinforcement Learning, Computer Vision and Robotics</b>. I'm particularly interested in computer vision and machine learning methods for robotic perception, locomotion, and manipulation in complex and constrained environments.
      </p>
      <p>
        I earned my MS in Computer Science from GMU and graduated with a B.Sc. degree in Computer Science and Engineering from Ahsanullah University of Science & Technology (AUST), Dhaka, Bangladesh.
      </p>
    </div>
    <div id="intro-headshot-wrapper">
      <img id="intro-headshot" src="{{ base_path }}/images/profile_v2.jpg" alt="Amir Hossain Raj headshot" />

            <div class="row intro-links">
        <a class="button" href="{{ base_path }}/files/AmirHossainRajCV.pdf">
          <div><b>CV</b></div>
        </a>
        <a class="button" href="{{ site.author.googlescholar }}">
          <div><i class="fa-solid fa-graduation-cap"></i></div>
        </a>
        <a class="button" href="https://github.com/{{ site.author.github }}">
          <div><i class="fa-brands fa-github"></i></div>
        </a>
        <a class="button" href="https://www.linkedin.com/in/{{ site.author.linkedin }}">
          <div><i class="fa-brands fa-linkedin-in"></i></div>
        </a>
        <a class="button" href="https://twitter.com/{{ site.author.twitter }}">
          <div><i class="fa-brands fa-x-twitter"></i></div>
        </a>
      </div>
      <div class="intro-email">
        <a href="mailto:{{ site.author.email }}">{{ site.author.email }}</a>
      </div>
    </div>
  </div>
</div>

  <div id="news" class="section">
    <h2 class="section-title">News</h2>
    <div class="news">
    <div class="news-date">August 08, 2025</div>
    <div class="news-text">Poster paper accepted at VL/HCC.</div>
  </div>
    <div class="news">
    <div class="news-date">June 15, 2025</div>
    <div class="news-text">Two papers accepted at IROS.</div>
  </div>
  <div class="news">
    <div class="news-date">November 21, 2024</div>
    <div class="news-text">Paper accepted at RA-L. <a href="https://arxiv.org/abs/2404.00210">link</a></div>
  </div>
  <div class="news">
    <div class="news-date">October 7, 2024</div>
    <div class="news-text">A workshop paper got accepted at IROS 2024. <a href="https://arxiv.org/pdf/2309.12568">link</a></div>
  </div>
  <div class="news">
    <div class="news-date">January 29, 2024</div>
    <div class="news-text">Two conference papers & a workshop paper got accepted at ICRA 2024.</div>
  </div>
  <div class="news">
    <div class="news-date">August 22, 2022</div>
    <div class="news-text">Joined as a Graduate Teaching Assistant at GMU.</div>
  </div>
</div>

  <div id="publications" class="section">
    <h2 class="section-title">Selected Publications</h2>
  {% assign sorted_publications = site.publications | sort: 'date' | reverse %}
  {% for publication in sorted_publications limit:5 %}
  <div class="publication">
    {% if publication.image %}
    <div class="publication-image">
      <a href="{{ publication.paperurl | default: publication.links[0].url }}">
        <img class="publication-img" src="{{ base_path }}{{ publication.image }}" alt="{{ publication.title }}" />
      </a>
    </div>
    {% endif %}
    <div class="publication-info">
      <div class="publication-detail">
        <p class="publication-title">{{ publication.title }}</p>
        <p class="publication-authors">
          {% for author in publication.authors %}
            {% if author == "Amir Hossain Raj" %}
              <a class="publication-author" style="font-weight: bold;">{{ author }}</a>
            {% else %}
              <a class="publication-author">{{ author }}</a>
            {% endif %}
            {% unless forloop.last %} • {% endunless %}
          {% endfor %}
        </p>
        <p class="publication-venue">{{ publication.venue }}</p>
        {% if publication.award %}
        <p class="publication-award"><i class="fa-solid fa-award"></i> {{ publication.award }}</p>
        {% endif %}
      </div>
      {% if publication.links %}
      <div class="publication-links">
        {% for link in publication.links %}
        <div class="button">
          <a class="publication-link" href="{{ link.url }}">
            <i class="{{ link.icon }}"></i> {{ link.text }}
          </a>
        </div>
        {% endfor %}
      </div>
      {% endif %}
    </div>
  </div>
  {% endfor %}
</div>


