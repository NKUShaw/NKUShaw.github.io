---
permalink: /
title: "Personal Page"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
My name is Yang Xiao (肖扬). a Ph.D. student in Computer Science at the University of Tulsa, Tulsa, Oklahoma, USA. I come from China and graduated from Nankai University, Tianjin, China. Now, my research interests are trustworthy artificial intelligence and AI for Science.

News
======

<div id="news-section">
  <ul id="news-list">
    <li>[2025.09.23] Our paper was accepted by NIPS 2026 RegML workshop.</li>
    <li>[2025.08.05] Our paper was accepted by CIKM 2025.</li>
    <li>[2025.07.10] Our paper was accepted by ECAI 2025.</li>
    <li>[2025.06.25] Our papers were accepted by ICCV 2025.</li>
    <li>[2025.06.16] I am interning at Mayo Clinic, Rochester, MN until August. 23, 2025.</li>
    <li class="hidden-news" style="display: none;">[2025.06.09] Our paper was accepted by ICML 2025 CFAgentic Workshop <strong>Oral</strong>.</li>
    <li class="hidden-news" style="display: none;">[2025.03.06] Our paper was accepted by ICLR 2025 Bi-Align Workshop.</li>
    <li class="hidden-news" style="display: none;">[2024.11.29] Our paper was accepted by COLING 2025.</li>
    <li class="hidden-news" style="display: none;">[2024.11.16] Our paper was accepted by LoG 2024.</li>
    <li class="hidden-news" style="display: none;">[2024.07.15] Our paper was accepted by CIKM 2024.</li>
    <li class="hidden-news" style="display: none;">[2024.06.07] Our paper was accepted by ICIP 2024.</li>
  </ul>
  <button onclick="toggleNews()" id="toggle-button">Show more</button>
</div>

<script>
function toggleNews() {
  const hiddenItems = document.querySelectorAll('.hidden-news');
  const btn = document.getElementById('toggle-button');
  const isHidden = hiddenItems[0].style.display === 'none';
  hiddenItems.forEach(item => {
    item.style.display = isHidden ? 'list-item' : 'none';
  });
  btn.textContent = isHidden ? 'Show less' : 'Show more';
}
</script>
<br>

CCF Paper Statistics 
======
<table id="ccf-table" style="width:80%; text-align:center; border-collapse: collapse;" border="1">
  <thead>
    <tr style="background-color:#f2f2f2;">
      <th>Category</th>
      <th>2024</th>
      <th>2025</th>
      <th>2026</th>
      <th>2027</th>
      <th>2028</th>
      <th>Total</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>CCF-A</strong></td>
      <td>0</td>
      <td>2</td>
      <td>Unknown</td>
      <td>Unknown</td>
      <td>Unknown</td>
      <td>2</td>
    </tr>
    <tr>
      <td><strong>CCF-B</strong></td>
      <td>1</td>
      <td>2</td>
      <td>Unknown</td>
      <td>Unknown</td>
      <td>Unknown</td>
      <td>3</td>
    </tr>
    <tr>
      <td><strong>CCF-C</strong></td>
      <td>1</td>
      <td>0</td>
      <td>Unknown</td>
      <td>Unknown</td>
      <td>Unknown</td>
      <td>1</td>
    </tr>
    <tr>
      <td><strong>Citation</strong></td>
      <td>7</td>
      <td>18</td>
      <td>Unknown</td>
      <td>Unknown</td>
      <td>Unknown</td>
      <td>25</td>
    </tr>
  </tbody>
</table>
<br>

屡败屡战
=======
[2025.05] ACL reject

[2025.05] ICML reject

[2024.12] AAAI reject

[2024.07] ACL desk reject for stupid reason (don't ask me)

[2024.05] UAI withdrawn

<!-- 自我介绍
====== -->
<!-- 本人注意力涣散，应试教育成绩差，长期失眠，如果哪天不幸猝死，用此文当作遗言——当然现在它只是一个自我介绍。

中学时代期望从政，实现报国理想，高考入南开大学周恩来政府管理学院应用心理学专业（后该专业并入社会学院，目前只保留研究生授业），后经历各种变故，逐渐将从政目标暂且放下，却又不喜欢本专业，而绩点、排名拉跨，不再有机会转专业，于是自学计算机，机器学习，深度学习，医学影像等领域的技术（主要这玩意确实赚钱），加入本校一团队，经一年的打磨，心态强大，技术成熟，脸皮宽厚，又鼓起勇气套磁成功，终于来到美国一所末流学校念计算机的博士（因为没有钱读海外硕士，没有能力考研本国研究生，也不是科班生去top校，感谢博导的收留）。

我常有拖延、启动困难的现象，这是制约我做事的一大阻碍，因此常常三天打鱼，两天晒网，但是运气不错，大四一年到赴美前还是发了不少文章，学校排名低，导师新AP，自觉没有靠山、没有能力走太远，现在只想做好眼下的工作，走一步看一步，虽然现在qualify都还没过，但初步打算是博士毕业后能有一份互联网企业的工作，若有机会，还想去最一流的院校找找博士后的机会。

中学前一直觉得天赋重要，现在看来，其实大多数工作内容并没有那么多智力门槛，到处都是重复操作的dirty work，越来越觉得勤奋和不气馁的心态是进步的必要条件，回过头来看，世界终究还是一个草台班子，其实高位低位，富人穷人，正国副科的能力差异有很多因素，勤奋并不是充分条件，**沛县黑社会能开两汉四百年，凤阳一伙人能兴皇明三百岁，金田一队人能杀清妖千千万，红安一个县能养开国二百将**。人的命运不仅要看个人的奋斗，更要看发挥的平台与历史的进程，出身贫寒不是耻辱，但个人奋斗终究不是全部，就像历史中的无数例子——出身贫寒者成大业者有之，寒门难出贵子者亦多。

希望自己能够放下奋斗比的牛马思维，用坦然的心态去面对曲折，也许这样，顺其自然，我能走得更远。 -->
<!-- The Exploration during my undergraduate stage
====== -->
<!-- During my undergraduate studies, I pursued a Bachelor's degree of Science in Applied Psychology. A lot of people thought I should be a humanities or social science student. But actually, the psychology education I received covered very hardcore knowledge of mathematics, statistics, and computer science. Many things happened and many people got acquainted with me during this experience, which gradually changed my cognition and helped me find my current life goal. TBH, I am a trash student under the evaluation standards of universities in Mainland China, so I have been trying to break through this evaluation standard and become the person I want to be. I am also very grateful for the help and opportunities of teachers and students along the way. After four years of summarizing, I believe that zuoti (做题, which means examination-oriented education) is not a fixed path, and education has become more of a screening tool. I was eliminated, but I gained more from the education path outside of zuoti than in the first twenty years of my life. the novel path is practice. Setting aside the threshold set by humans, many things can be done by hardworking, and tasks or jobs that require talent are only a few of them. Therefore, 'Identify and solve problems, summarize and learn theories from practice, validate and strengthen theories in practice' are my core methodology for understanding the world at present. -->


