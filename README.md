Table of Contents
==================

<ul>
  {% for post in site.posts %}
    <li>
      <a href=".{{ post.url }}">{{ post.title }}</a>
      <!-- post.url 的链接是 / 根目录 -->
      <!-- 但是 github.io 是带有 deepinss 前缀的 -->
      <!-- 所以这里加了个点, 表示相对路径 -->
    </li>
  {% endfor %}
</ul>

SSS [![first-timers-only](http://img.shields.io/badge/first--timers--only-friendly-blue.svg?style=flat-square)](http://www.firsttimersonly.com/)
=========================

This project begins on December 12, 2017. Committed to making everyone understand shadowsocks source code. The project was named SSS. Understand into shadowsocks study, or study shadowsocks can be.

This project is my goal to be completed by 2018.

