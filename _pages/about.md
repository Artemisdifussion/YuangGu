---
permalink: /
title: "关于我"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<p>您好，欢迎访问我的个人网站。</p>

<p>我是顾宇昂，一名对探索前沿技术充满热情的生物医学工程专业学生。我即将在帝国理工学院继续深造，攻读医学物理硕士学位。</p>

<p>我致力于将工程技术应用于医疗领域，以创新的解决方案改善人们的健康。在本科期间，我不仅取得了优异的学业成绩，还积极投身于科研项目和企业实习，在深度学习、医学影像处理和软件开发方面积累了宝贵的实践经验。</p>

<div style="display: flex;">
  <div style="flex: 1; padding-right: 1em;">
    <h2>技能</h2>
    <ul>
    {% for skill in site.data.cv.skills %}
      <li><b>{{ skill.name }}</b>: {{ skill.keywords | join: ', ' }}</li>
    {% endfor %}
    </ul>
  </div>
  <div style="flex: 1; padding-left: 1em;">
    <h2>教育背景</h2>
    <ul>
    {% for education in site.data.cv.education %}
      <li>
        <b>{{ education.area }}</b>, {{ education.endDate }}<br>
        <i>{{ education.institution }}</i>
      </li>
    {% endfor %}
    </ul>
  </div>
</div>

<p>我热衷于迎接挑战，并相信技术能够为医疗健康带来革命性的变革。如果您对我的经历感兴趣，或是有任何合作机会，请随时通过 <strong>guyuang364@gmail.com</strong> 与我联系。</p>
