---
view: page
title: "3. Layihə yaratmaq"
---

<h3>Məqsədlər</h3>

<ul><li>Sıfırdan git repozitoriya yaratmağı öyrənmək</li></ul>

<h2><em>01</em> “Hello, World” səhifəsini yaradın</h2>

<p>Təmiz işçi qovluqda işləməkdən başlayın (məsələn, əgər əvvəlki mərhələdə dərs materialını yükləmişdinizsə, “Work” qovluğunda) və bu qovluğda “hello” adında qovluq yaradın, daha sonra isə  <code>hello.html</code> faylını yaradın və içini aşağıda göstərilən kontentlə doldurun.</p>

<h4 class="h4-pre">İcra et:</h4>

<pre class="instructions">mkdir hello
cd hello
touch hello.html</pre>

<h4 class="h4-pre">Fayl: <em>hello.html</em></h4>

<pre class="file">Hello, World</pre>

<h2><em>02</em> Repozitoriya yaradın</h2>

<p>Hazırda bizim içində bir fayl olan qovluğumuz var. Bu qovluqdan git repozitoriya yaratmaq üçün git init əmrini icra edin.</p>

<h4 class="h4-pre">İcra et:</h4>

<pre class="instructions">git init</pre>

<h4 class="h4-pre">Nəticə:</h4>

<pre class="sample">$ git init
Initialized empty Git repository in /Users/alex/Documents/Presentations/githowto/auto/hello/.git/
</pre>

<h2><em>03</em> Səhifəni repozitoriyaya əlavə edin</h2>

<p>Gəlin bu dəqiqə “Hello, World” səhifəsini repozitoriyaya əlavə edək.</p>

<h4 class="h4-pre">İcra et:</h4>

<pre class="instructions">git add hello.html
git commit -m "First Commit"</pre>

<p>Hər şey göz qabağında...</p>

<h4 class="h4-pre">Nəticə:</h4>

<pre class="sample">$ git add hello.html
$ git commit -m "First Commit"
[master (root-commit) 911e8c9] First Commit
 1 files changed, 1 insertions(+), 0 deletions(-)
 create mode 100644 hello.html</pre>