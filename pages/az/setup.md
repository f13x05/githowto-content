---
view: page
title: "1. Hazırlıq"
---

<h3>Məqsədlər</h3>

<ul><li>Git vasitəsilə işləməyə tam hazır olmaq.</li></ul>

<h2><em>01</em> E-mail ünvanı və adın ayarlanması</h2>

<p>Əgər siz heç vaxt git istifadə etməmisinizsə əvvəlcə e-mail ünvanını və adı qurmaq lazımdır. Git sizin ad və e-mail ünvanını bilsin deyə aşağıdakı komandaları icra edin, əgər git hazırdısa sətir sonluqları bölümünə keçin</p>

<h4 class="h4-pre">İcra et:</h4>

<pre class="instructions">git config --global user.name "Your Name"
git config --global user.email "your_email@whatever.com"</pre>

<h2><em>02</em> Sətir sonluqlarının ayarlanması</h2>

<p>Həmçinin, Unix/Mac istifadəçiləri üçün:</p>

<h4 class="h4-pre">İcra et:</h4>

<pre class="instructions">git config --global core.autocrlf input
git config --global core.safecrlf true</pre>

<p>Windows istifadəçiləri üçün:</p>

<h4 class="h4-pre">İcra et:</h4>

<pre class="instructions">git config --global core.autocrlf true
git config --global core.safecrlf true</pre>