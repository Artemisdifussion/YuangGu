---
permalink: /
title: "关于我"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<p>欢迎访问我的个人网站。</p>

<p>我是顾宇昂，目前就读于帝国理工学院的医学物理专业。我熟悉多种医疗器械原理，有基本的解剖学和生理学知识，曾参与智慧医疗监测平台和欠采样4d cbct重建算法开发，积累了扎实的医疗器械和软件方面的经验。</p>

<p>我致力于将工程技术应用于医疗领域，以创新的解决方案改善人们的健康。在本科期间，我不仅取得了优异的学业成绩，还与沈阳航空航天大学的实验室合作进行过项目，负责其开发的柔性传感器的软件部分，并获得发明型专利和软著。曾担任过电视台部长，为学校公众号宣传做出过贡献。</p>

<div style="display: flex;">
  <div style="flex: 1; padding-right: 1em;">
    <h2>技能</h2>
    <ul>
    {% for skill in site.data.cv.skills %}
      <li>{{ skill.name }}</li>
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

<p>我热衷于迎接挑战，并相信技术能够为医疗健康带来革命性的变革。如果您对我的经历感兴趣，或是有任何合作机会，请随时通过 <strong>yg3924@ic.ac.uk</strong> 与我联系。</p>
