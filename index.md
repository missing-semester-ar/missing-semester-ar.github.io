---
layout: page
title:  الفصل الدراسي المفقود من تعلمك لعلوم الكمبيوتر
nositetitle: true
---


<p dir="rtl">
تعلمك الفصول الدراسية كل شيء عن الموضوعات المتقدمة في علوم الكمبيوتر ، من أنظمة التشغيل إلى تعلم الآلة ، ولكن هناك مواضيع مهمة نادرًا ما يتم تغطيتها، وبدلاً من ذلك يُترك الطلاب لمعرفة ذلك بأنفسهم: الكفاءة في استخدام أدواتهم. سنعلمك كيفية إتقان سطر الأوامر، واستخدام محرر نصوص قوي ، واستخدام ميزات رائعة لأنظمة التحكم في الإصدار ، وأكثر من ذلك بكثير!
</p>

<p dir="rtl">
يقضي الطلاب مئات الساعات في استخدام هذه الأدوات على مدار فترة تعليمهم (والآلاف على مدار حياتهم المهنية) ، لذلك من المنطقي جعل التجربة سلسة قدر الإمكان. إن إتقان هذه الأدوات لا يمكّنك فقط من قضاء وقت أقل في اكتشاف كيفية استخدام أدواتك وفقًا لإرادتك ، ولكنه يتيح لك أيضًا حل المشكلات التي كانت تبدو في السابق معقدة بشكل مستحيل.</p>

<p dir="rtl"> اقرأ مزيدا حول <a dir="rtl" href="/about/">الدافع وراء هذا الدرس.</a> </p>


{% comment %}
# Registration

Sign up for the IAP 2020 class by filling out this [registration form](https://forms.gle/TD1KnwCSV52qexVt9).
{% endcomment %}

<h1 dir="rtl"> جدول الدروس </h1>

<div dir="rtl">



{% comment %}
**Lecture**: 35-225, 2pm--3pm<br>
**Office hours**: 32-G9 lounge, 3pm--4pm (every day, right after lecture)
{% endcomment %}

<ul>
{% assign lectures = site['2020'] | sort: 'date' %}
{% for lecture in lectures %}
    {% if lecture.phony != true %}
        <li>
        <strong>{{ lecture.date | date: '%-m/%d/%y' }}</strong>:
        {% if lecture.ready %}
            <a href="{{ lecture.url }}">{{ lecture.title }}</a>
        {% else %}
            {{ lecture.title }} {% if lecture.noclass %}[no class]{% endif %}
        {% endif %}
        </li>
    {% endif %}
{% endfor %}
</ul>

</div>




<p dir="rtl">تسجيلات المحاضرات متوفرة <a  href="https://www.youtube.com/playlist?list=PLyzOVJj3bHQuloKGG59rS43e29ro7I57J">على اليوتيوب </a>.</p>


<h1 dir="rtl"> حول هذه الدروس </h1>
<p dir="rtl">
<b>طاقم العمل:</b> 
درست هذه الدروس بالتشارك بين كل من
<a dir="rtl" href="https://www.anishathalye.com/"> Anish </a>
و
<a dir="rtl" href="https://thesquareplanet.com/"> Jon </a>
و
<a dir="rtl" href="http://josejg.com/"> Jose </a>.
<br>
<b>للأسئلة:</b> 
 راسلنا بالانجليزية على 
 <a dir="rtl" href="mailto:missing-semester@mit.edu"> missing-semester@mit.edu </a>.
</p>

<h1 dir="rtl"> ما بعد معهد MIT</h1>
<p dir="rtl">
قمنا أيضا بنشر هذا الدروس الى ما بعد معهد MIT على امل ان يستفيد الجميع من هذه المصادر.
يمكنك ان تجد المنشورات والمقاشات المتختلفة على:
</p>

<ul dir="rtl">
  <li><a href="https://news.ycombinator.com/item?id=22226380">  Hacker News</a></li>
  <li><a href="https://lobste.rs/s/ti1k98/missing_semester_your_cs_education_mit"> Lobsters</a></li>
  <li><a href="https://www.reddit.com/r/learnprogramming/comments/eyagda/the_missing_semester_of_your_cs_education_mit/"> /r/learnprogramming</a></li>
  <li><a href="https://www.reddit.com/r/programming/comments/eyagcd/the_missing_semester_of_your_cs_education_mit/"> /r/programming</a></li>
  <li><a href="https://twitter.com/jonhoo/status/1224383452591509507"> Twitter</a></li>
  <li><a href="https://www.youtube.com/playlist?list=PLyzOVJj3bHQuloKGG59rS43e29ro7I57J"> YouTube</a></li>
</ul>

{% comment %}
Some more URLs:

- https://news.ycombinator.com/item?id=27154577
- https://news.ycombinator.com/item?id=34934216
- https://www.reddit.com/r/learnprogramming/comments/nca1v3/mit_the_missing_semester_of_your_cs_education/
- https://www.reddit.com/r/compsci/comments/eyywv8/the_missing_semester_of_your_cs_education_from_mit/
- https://www.reddit.com/r/programming/comments/io7nq3/the_missing_semester_of_your_cs_education_mit/
- https://twitter.com/MIT_CSAIL/status/1349766980413263873
- https://twitter.com/MIT_CSAIL/status/1481676163491659780
- https://twitter.com/MIT_CSAIL/status/1581313961093484545
{% endcomment %}


<h1 dir="rtl"> الترجمات</h1>
<ul dir="rtl">
  <li><a href="https://missing.csail.mit.edu/"> الإنجليزية (المصدر الأصلي)</a></li>
  <li><a href="https://missing-semester-cn.github.io/"> الصينية (المبسطة)</a></li>
  <li><a href="https://missing-semester-zh-hant.github.io/"> الصينية (التقليدية)</a></li>
  <li><a href="https://missing-semester-jp.github.io/"> اليابانية</a></li>
  <li><a href="https://missing-semester-kr.github.io/"> الكورية</a></li>
  <li><a href="https://missing-semester-pt.github.io/"> البرتغالية</a></li>
  <li><a href="https://missing-semester-rus.github.io/"> الروسية</a></li>
  <li><a href="https://netboxify.com/missing-semester/"> الصربية</a></li>
  <li><a href="https://missing-semester-esp.github.io/"> الإسبانية</a></li>
  <li><a href="https://missing-semester-tr.github.io/"> التركية</a></li>
  <li><a href="https://missing-semester-vn.github.io/"> الفياتنامية</a></li>
</ul>
<p dir="rtl">
  تنبيه: هذه الترجمات (بما فيها هذه الترجمة التي تقرأها الان) هي ترجمات مجتمعية ولم نقم بفحصها ومراجعتها.
</p>
<p dir="rtl">
هل قمت بكتابة ترجمة لهذه الدروس؟ أرسل لنا طلب 
<a href="https://github.com/missing-semester/missing-semester/pulls"> pull request</a>
حتى نضيفها الى القائمة!
</p>

<h1 dir="rtl"> شكر و تقدير</h1>

<p dir="rtl">
نشكر كل من Elaine Mello, Elaine Mello و 
<a href="https://openlearning.mit.edu/"> MIT Open Learning </a>
لجعل هذه الفيديوهات ممكنة.
Anthony Zolnik و 
<a href="https://aeroastro.mit.edu/"> MIT AeroAstro </a>
من اجل اجهزة ال A/V.
<br> Brandi Adams و 
<a href="https://www.eecs.mit.edu/"> MIT EECS </a>
لدعم هذه الدروس.

</p>

---

<div class="small center">
<p><a href="https://github.com/missing-semester-ar/missing-semester-ar.github.io">المصدر</a>.</p>
<p>.CC BY-NC-SA مرخصة تحت رخصة</p>
<p>اضغط <a href="/license/">هنا</a> من اجل تعليمات المساهمة والترجمة</p>
</div>
