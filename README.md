# K204-Desktop-App-Final

<article class="markdown-body entry-content p-5" itemprop="text">
<p>C# Desktop Final Project</p>
<h1><a id="user-content-futbol-sahəsi" class="anchor" aria-hidden="true" href="#futbol-sahəsi"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Futbol Sahəsi</h1>
<h3><a id="user-content-açıqlama" class="anchor" aria-hidden="true" href="#açıqlama"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Açıqlama:</h3>
<pre><code>Yazılacaq programda bir Futbol sahəsinin iş prinsiplerini idarə etməlidir.
Sahə idarəçisi hansı sahələr olduğunu yazır, ona görə müştərilərini əlavə edir.
Müştəri istəyinə görə tarixə, saat və meydan seçimi edilərək rezerv olunduqdan sonra
soyunub-geyinmə otağı təyin olunmalıdır.
</code></pre>
<h3><a id="user-content-sistem-funksyanalıqları" class="anchor" aria-hidden="true" href="#sistem-funksyanalıqları"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Sistem Funksyanalıqları</h3>
<ul>
<li>Müştəri CRUD - Müştərilərin idarə ediləməsi. Ad, Soyad, Telefon olaraq üç məlumat saxlanmalıdır</li>
<li>Meydanca CRUD - Meydancaların idarə edilməsi. Meydanca adı, Nömrəsi olaraq iki məlumat saxlanmalıdır.</li>
<li>Hesabatlar - Sistemdə olan rezervlərin məlumatı aylıq olaraq çıxmalıdır. nə qədər gəlir olduğu çıxmalıdır.</li>
<li>Otaqlar - Sahədə olan otaqların idarə edilməsi, Nömrəsi və neçə nəfərlik olduğu qeyd olunmalıdır.</li>
<li>Rezerv Crud - Müştəri, tarix və meydanca seçməlidir və rezerv olunmalıdır. Ama seçimlər ancaq boş olan vaxt seçim etmə bilməlidir ancaq,
Rezerv vaxtı bunun oyunun hansı otaq və ya otaqlardan istifadə edəcəyidə yazılmalıdır. Otaqın tutumuna görə 12 nəfərlik otaq sayı ayrılmalıdır. əgər bi otağa sığmırsa iki otaq təyin oluna bilər</li>
<li>Dashboard - Şəxsi yaradıçılığınıza buraxıram</li>
</ul>
<h1><a id="user-content-crm" class="anchor" aria-hidden="true" href="#crm"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>CRM</h1>
<h3><a id="user-content-açıqlama-1" class="anchor" aria-hidden="true" href="#açıqlama-1"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Açıqlama:</h3>
<pre><code>Yazılacaq programda bir Şirkətin müştəriləri ilə münasibətlərini idarə etmək üçündür.
İstifadəçi girib bir müştəri yaradıb o müştəri ilə əlaqəli rəy və xatırlatmalar əlavə edə bilməlidir.
Hər bir müştərinin bi profilini yaranır və indiyə kimi yazılmış bütün rəylər və tapşırıqlar orada görünür.
</code></pre>
<h3><a id="user-content-sistem-funksyanalıqları-1" class="anchor" aria-hidden="true" href="#sistem-funksyanalıqları-1"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Sistem Funksyanalıqları</h3>
<ul>
<li>Müştəri CRUD - Müştərilərin idarə ediləməsi.Ad, Telefon, Ünvan, Məhsul şəxs</li>
<li>Hesabatlar -  Sistemdə olan rəylər və tapşırıqlar məlumatı aylıq olaraq çıxmalıdır. hər birində ne qədər olduğu çıxmalıdır</li>
<li>Müştəri Profili - Hər bir müştərinin profili olmalıdır. Profildən rəy və tapşırıq yazıla bilinməlidir.</li>
<li>Tapşırıq - Tapşırıqların bitmə vaxtıda qeyd olunmalıdır. Və tamamlana bilinməlidir.</li>
<li>Dashboard - Şəxsi yaradıçılığınıza buraxıram</li>
</ul>
<h1><a id="user-content-qiymətləndirmə" class="anchor" aria-hidden="true" href="#qiymətləndirmə"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Qiymətləndirmə</h1>
<ul>
<li>Programın normal halda işləməsi - 50 bal</li>
<li>Githubın düzgün istifadə olunması - 15 bal</li>
<li>Kod-ların düzgün şəkildə commentlənməsi - 15 bal</li>
<li>Dashboardin rahatlığı və program gözəl yazılmış olunması - 20 bal</li>
</ul>
<h1><a id="user-content-təhvil" class="anchor" aria-hidden="true" href="#təhvil"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Təhvil</h1>
<ul>
<li>Hər birinizin öz github profilində repo olmalıdır.</li>
<li>22.10.2020 13:00 qədər bitirmə vaxtınız var.</li>
</ul>
</article>
