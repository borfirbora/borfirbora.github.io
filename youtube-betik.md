---
---

<!DOCTYPE html>
<html xmlns="http://www.w3.org/1999/xhtml" lang="" xml:lang="">
<head>
  <meta charset="utf-8" />
  <meta name="generator" content="pandoc" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes" />
  <meta name="author" content="Bora FIRLANGEÇ borafirlangec@gmail.com" />
  <title>Youtube-DL İle İndirme Betikleri</title>
  <style>
    html {
      line-height: 1.5;
      font-family: Georgia, serif;
      font-size: 20px;
      color: #1a1a1a;
      background-color: #fdfdfd;
    }
    body {
      margin: 0 auto;
      max-width: 36em;
      padding-left: 50px;
      padding-right: 50px;
      padding-top: 50px;
      padding-bottom: 50px;
      hyphens: auto;
      word-wrap: break-word;
      text-rendering: optimizeLegibility;
      font-kerning: normal;
    }
    @media (max-width: 600px) {
      body {
        font-size: 0.9em;
        padding: 1em;
      }
    }
    @media print {
      body {
        background-color: transparent;
        color: black;
        font-size: 12pt;
      }
      p, h2, h3 {
        orphans: 3;
        widows: 3;
      }
      h2, h3, h4 {
        page-break-after: avoid;
      }
    }
    p {
      margin: 1em 0;
    }
    a {
      color: #1a1a1a;
    }
    a:visited {
      color: #1a1a1a;
    }
    img {
      max-width: 100%;
    }
    h1, h2, h3, h4, h5, h6 {
      margin-top: 1.4em;
    }
    h5, h6 {
      font-size: 1em;
      font-style: italic;
    }
    h6 {
      font-weight: normal;
    }
    ol, ul {
      padding-left: 1.7em;
      margin-top: 1em;
    }
    li > ol, li > ul {
      margin-top: 0;
    }
    blockquote {
      margin: 1em 0 1em 1.7em;
      padding-left: 1em;
      border-left: 2px solid #e6e6e6;
      color: #606060;
    }
    code {
      font-family: Menlo, Monaco, 'Lucida Console', Consolas, monospace;
      font-size: 85%;
      margin: 0;
    }
    pre {
      margin: 1em 0;
      overflow: auto;
    }
    pre code {
      padding: 0;
      overflow: visible;
    }
    .sourceCode {
     background-color: transparent;
     overflow: visible;
    }
    hr {
      background-color: #1a1a1a;
      border: none;
      height: 1px;
      margin: 1em 0;
    }
    table {
      margin: 1em 0;
      border-collapse: collapse;
      width: 100%;
      overflow-x: auto;
      display: block;
      font-variant-numeric: lining-nums tabular-nums;
    }
    table caption {
      margin-bottom: 0.75em;
    }
    tbody {
      margin-top: 0.5em;
      border-top: 1px solid #1a1a1a;
      border-bottom: 1px solid #1a1a1a;
    }
    th {
      border-top: 1px solid #1a1a1a;
      padding: 0.25em 0.5em 0.25em 0.5em;
    }
    td {
      padding: 0.125em 0.5em 0.25em 0.5em;
    }
    header {
      margin-bottom: 4em;
      text-align: center;
    }
    #TOC li {
      list-style: none;
    }
    #TOC a:not(:hover) {
      text-decoration: none;
    }
    code{white-space: pre-wrap;}
    span.smallcaps{font-variant: small-caps;}
    span.underline{text-decoration: underline;}
    div.column{display: inline-block; vertical-align: top; width: 50%;}
    div.hanging-indent{margin-left: 1.5em; text-indent: -1.5em;}
    ul.task-list{list-style: none;}
    .display.math{display: block; text-align: center; margin: 0.5rem auto;}
  </style>
  <!--[if lt IE 9]>
    <script src="//cdnjs.cloudflare.com/ajax/libs/html5shiv/3.7.3/html5shiv-printshiv.min.js"></script>
  <![endif]-->
</head>
<body>
<header id="title-block-header">
<h1 class="title">Youtube-DL İle İndirme Betikleri</h1>
<p class="author">Bora FIRLANGEÇ <a href="mailto:borafirlangec@gmail.com" class="email">borafirlangec@gmail.com</a></p>
<p class="date">5 Eylül 2021</p>
</header>
<nav id="TOC" role="doc-toc">
<ul>
<li><a href="#youtube-dl-nedir">Youtube-DL Nedir?</a></li>
<li><a href="#arşiv-ile-neler-yapabilirim">Arşiv ile Neler Yapabilirim?</a></li>
<li><a href="#genel-bakış">Genel Bakış</a>
<ul>
<li><a href="#kanal-indirme">1. Kanal İndirme</a></li>
<li><a href="#çalma-listesi-indirme">2. Çalma Listesi İndirme</a></li>
<li><a href="#video-indirme">3. Video İndirme</a></li>
</ul></li>
<li><a href="#olası-sorunlar-ve-çözümleri">Olası Sorunlar ve Çözümleri</a>
<ul>
<li><a href="#neden-linkleri-yapıştıramıyorum">Neden Linkleri Yapıştıramıyorum?</a></li>
<li><a href="#neden-betikler-hızlıca-kapanıyor">Neden Betikler Hızlıca Kapanıyor?</a></li>
</ul></li>
<li><a href="#son-notlar">Son Notlar</a></li>
</ul>
</nav>
<blockquote>
<p>Önemli Not!</p>
<p>Bu doküman, arşivin içerisinde verilen betiklerin kullanımına ve olası sorunların çözümlerine ilişkin yönergeler içermektedir. Bu betiklerin kullanımından doğabilecek tüm hasar, sizin sorumluluğunuzdadır. Betikleri kullanmak, bunu kabul ettiğiniz anlamına gelmektedir.</p>
</blockquote>
<hr />
<p><strong>Youtube-DL İle İndirme Betikleri</strong>’ne hoşgeldiniz. Bu arşiv, <strong>Youtube-DL</strong> komut satırı aracını kullanarak, <strong>Youtube</strong> üzerinden kanal, çalma listesi ve video gibi içerikleri indirmenize yardımcı olacak küçük araçlar sunuyor olacak. Bu belge de, bu araçlardan verimli bir şekilde yararlanmanız için gerekli tüm bilgileri bünyesinde barındırmakta.</p>
<hr />
<h2 id="youtube-dl-nedir">Youtube-DL Nedir?</h2>
<p><a href="http://ytdl.org/">Youtube-DL</a>, kendi sitesindeki açıklamasında şu şekilde tanımlanıyor:</p>
<blockquote>
<p>youtube-dl, YouTube.com’dan ve birkaç başka siteden video indirmek için kullanılan bir komut satırı programıdır. Python yorumlayıcısını (2.6, 2.7 veya 3.2+) gerektirir ve platforma özel değildir. Ayrıca Python içeren bir Windows yürütülebilir dosyası da sağlıyoruz. youtube-dl, Unix kutunuzda, Windows’ta veya Mac OS X’te çalışmalıdır. Kamuya açık olarak yayınlanmıştır; bu, onu değiştirebileceğiniz, yeniden dağıtabileceğiniz veya istediğiniz gibi kullanabileceğiniz anlamına gelir.</p>
</blockquote>
<p>Kaba bir tabirle Youtube-dl, Youtube ve benzeri sitelerden video indirmemizi sağlayan açık kaynak kodlu bir uygulamadır. Bu uygulama, <strong>komut satırı</strong> üzerinden çalıştığı için, normal bir bilgisayar kullanıcısının videolar indirmesini biraz daha zor h’ale getirmektedir. Bu problemin önüne geçebilmek için de, bu programı kullanarak video indirmeyi tek tıkla halleden programcıklar barındıran bu küçük arşivi sizlere sunuyoruz. Aşağıda da bu arşivin kullanım talimatları yer almaktadır.</p>
<hr />
<h2 id="arşiv-ile-neler-yapabilirim">Arşiv ile Neler Yapabilirim?</h2>
<p>Arşivdeki dosyalar üç ana başlıkta oluşturulmuştur. Her bir başlık kendi içinde iki dosyaya ayrılmaktadır. Bu durumda arşivimizde toplam <strong>altı</strong> betik bulunmaktadır.</p>
<p>Ayrıca arşivimizde dört adet uygulama dosyası da bulunmaktadır. Bu dosyalar, betiklerin tam anlamıyla görevlerini yapabilmeleri için olmazsa olmaz dosyalardır. Dilerseniz gelin önce arşivimizdeki dosyaların adlarına ve ne işe yaradıklarına bir tabloyla göz atalım, ardından da her birini tek tek inceleyerek ne olduğunu kavramaya çalışalım:</p>
<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th style="text-align: left;">Dosya Adı</th>
<th style="text-align: right;">Kısa Açıklaması</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;">1.1. kanal video indir.bat</td>
<td style="text-align: right;">Kanalı video olarak indirir.</td>
</tr>
<tr class="even">
<td style="text-align: left;">1.2. kanal ses indir.bat</td>
<td style="text-align: right;">Kanalı ses olarak indirir.</td>
</tr>
<tr class="odd">
<td style="text-align: left;">2.1. çalma listesi video indir.bat</td>
<td style="text-align: right;">Çalma listesini video olarak indirir.</td>
</tr>
<tr class="even">
<td style="text-align: left;">2.2. Çalma listesi ses indir.bat</td>
<td style="text-align: right;">Çalma listesini ses olarak indirir.</td>
</tr>
<tr class="odd">
<td style="text-align: left;">3.1. tek video indir.bat</td>
<td style="text-align: right;">Videoyu, video olarak indirir.</td>
</tr>
<tr class="even">
<td style="text-align: left;">3.2. tek ses indir.bat</td>
<td style="text-align: right;">Videoyu, ses olarak indirir.</td>
</tr>
<tr class="odd">
<td style="text-align: left;">ffmpeg.exe</td>
<td style="text-align: right;">Ses ve video kaydetmek, dönüştürmek ve yayınlamak için eksiksiz, platformlar arası bir çözüm.</td>
</tr>
<tr class="even">
<td style="text-align: left;">ffplay.exe</td>
<td style="text-align: right;">FFmpeg kitaplıklarını ve SDL kitaplığını kullanan çok basit ve taşınabilir bir medya oynatıcı.</td>
</tr>
<tr class="odd">
<td style="text-align: left;">ffprobe.exe</td>
<td style="text-align: right;"><strong>ffmpeg.exe</strong> dosyasının kullandığı bir çeşit bağımlılık.</td>
</tr>
<tr class="even">
<td style="text-align: left;">youtube-dl.exe</td>
<td style="text-align: right;">Bütün işlemlerimizi yürütecek ve yukarıdaki dosyalarla birlikte çalışarak videolarımızı işleyecek olan ana dosya.</td>
</tr>
</tbody>
</table>
<hr />
<h2 id="genel-bakış">Genel Bakış</h2>
<p>Yukarıda, arşivin üç ana başlıkta toplandığından bahsetmiştik. Bunlar <strong>kanal</strong>, <strong>çalma listesi</strong> ve <strong>video</strong> idi.</p>
<p>Arşivdeki betiklere başvuruda bulunmadan önce karar vermeniz gereken şey de aslında burada devreye giriyor. İndirmek istediğiniz şey bir kanalın tüm içeriği mi, bir çalma listesinin tamamı mı yoksa tek bir video mu? Bu sorunun cevabını çoğunlukla getirdiğiniz <em>URL</em> belirler.</p>
<ol type="1">
<li>Eğer elinizdeki URL, <a href="https://youtube.com/c/babaprogramlar" class="uri">https://youtube.com/c/babaprogramlar</a> şeklindeyse bu, indirmeniz gerekenin bir kanal olduğunu gösterir.</li>
<li>Eğer elinizdeki URL, <a href="https://www.youtube.com/playlist?list=PLzD2mZ6wwf1TaYIjUNgxzN-HV1Cw6tDTX" class="uri">https://www.youtube.com/playlist?list=PLzD2mZ6wwf1TaYIjUNgxzN-HV1Cw6tDTX</a> şeklindeyse bu, indirmeniz gerekenin bir çalma listesi olduğunu gösterir.</li>
<li>Eğer elinizdeki URL, <a href="https://www.youtube.com/watch?v=aXEoMjoZ81I" class="uri">https://www.youtube.com/watch?v=aXEoMjoZ81I</a> şeklindeyse bu, indirmeniz gerekenin bir video olduğunu gösterir.</li>
</ol>
<p>Ana başlığımıza karar verdiğimize göre şimdi de indirmek istediğimiz formatı seçmemiz gerek. İstediğimiz videonun, Youtube’taki en kaliteli görüntülü hali mi yoksa isteğimiz sadece söz konusu videonun sesi mi? Buna da kendimiz karar vermeliyiz çünkü bunu, şahsi ihtiyaçlarımız belirler.</p>
<p>Şimdi gelin, her bir betiğin işlevini tek tek inceleyelim. Böylece arşivimizden tam anlamıyla yararlanmak için neler yapmamız gerektiğini kavramış oluruz.</p>
<blockquote>
<p>Önemli Notlar!</p>
<ol type="1">
<li>Dosya adlarındaki ilk rakam başlığı, ikinci rakam ise türü temsil eder. Örneğin <em>1.1. kanal video indir.bat</em> dosyasında ilk <em>1</em>, içeriğin kanal olduğunu, ikinci <em>1</em> ise türün video olduğunu anlatmak için kullanılmaktadır. Kafa karıştırıcı olmaması açısından dosya adının devamında ne olduğu açıkça belirtilmiştir.</li>
<li>Aşağıda yer alan metotlarla indirme gerçekleştirildiğinde, <em>indirmeler</em> klasörü, betik dosyalarının bulunduğu klasörde oluşturulacaktır. Alan sorunu yaşamamak için bu betik arşivini, yer sıkıntısı yaşamadığınız diskinizde kullanmayı düşünmelisiniz.</li>
</ol>
</blockquote>
<hr />
<h3 id="kanal-indirme">1. Kanal İndirme</h3>
<p>Bu başlıkta iki adet dosyamız var. Bu dosyalar, verdiğimiz linkin ait olduğu kanalın tüm içeriklerini indirir.</p>
<h4 id="kanal-video-indir.bat">1.1. kanal video indir.bat</h4>
<p>Dosya çalıştırıldığında sizden kanal URL’si isteyecektir. URL’yi yapıştırıp <code>ENTER</code> tuşuna bastığınızda kanaldaki tüm içerik, <em>indirmeler</em> klasörünün içindeki <em>kanallar</em> klasöründe oluşturulacak <em>“kanal adı” video</em> isimli klasöre, en son yüklenen video en üstte olacak şekilde indirilecektir.</p>
<p>Diyelim ki <a href="https://youtube.com/c/babaprogramlar">Baba Programlar</a> kanalındaki tüm içerikleri indirmek için <code>https://youtube.com/c/babaprogramlar</code> URL’sini yapıştırdınız ve <code>Enter</code>’a bastınız. Tüm indirmeler tamamlanıp da pencere kapandığında <em>indirmeler</em> klasörünün içinde <em>kanallar</em> klasörünü, onun içinde de <em>baba programlar video</em> klasörünü bulacaksınız. Bu klasöre de girdiğinizde de en son videoyu en üstte bulacaksınız.</p>
<h4 id="kanal-ses-indir.bat">1.2. kanal ses indir.bat</h4>
<p>Dosya çalıştırıldığında sizden kanal URL’si isteyecektir. URL’yi yapıştırıp <code>ENTER</code> tuşuna bastığınızda kanaldaki tüm içerik, <em>indirmeler</em> klasörünün içindeki <em>kanallar</em> klasöründe oluşturulacak <em>“kanal adı” ses</em> isimli klasöre, en son yüklenen video en üstte olacak şekilde indirilecektir.</p>
<p>Diyelim ki <a href="https://youtube.com/c/babaprogramlar">Baba Programlar</a> kanalındaki tüm içerikleri indirmek için <code>https://youtube.com/c/babaprogramlar</code> URL’sini yapıştırdınız ve <code>Enter</code>’a bastınız. Tüm indirmeler tamamlanıp da pencere kapandığında <em>indirmeler</em> klasörünün içinde <em>kanallar</em> klasörünü, onun içinde de <em>baba programlar ses</em> klasörünü bulacaksınız. Bu klasöre de girdiğinizde de en son videonun ses hâlini en üstte bulacaksınız.</p>
<h3 id="çalma-listesi-indirme">2. Çalma Listesi İndirme</h3>
<p>Bu başlıkta iki adet dosyamız var. Bu dosyalar, verdiğimiz linkin ait olduğu çalma listesinin tüm içeriklerini indirir.</p>
<h4 id="çalma-listesi-video-indir.bat">2.1. çalma listesi video indir.bat</h4>
<p>Dosya çalıştırıldığında sizden çalma listesi URL’si isteyecektir. URL’yi yapıştırıp <code>ENTER</code> tuşuna bastığınızda çalma listesindeki tüm içerik, <em>indirmeler</em> klasörünün içindeki <em>listeler</em> klasöründe oluşturulacak <em>“çalma listesi adı” video</em> isimli klasöre, listenin en üstündeki video en üstte olacak şekilde indirilecektir.</p>
<p>Diyelim ki <a href="https://youtube.com/c/babaprogramlar">Baba Programlar</a> kanalındaki <strong>Discord</strong> çalma listesindeki içerikleri indirmek için <code>https://www.youtube.com/playlist?list=PLzD2mZ6wwf1TaYIjUNgxzN-HV1Cw6tDTX</code> URL’sini yapıştırdınız ve <code>Enter</code>’a bastınız. Tüm indirmeler tamamlanıp da pencere kapandığında <em>indirmeler</em> klasörünün içinde <em>listeler</em> klasörünü, onun içinde de <em>Discord video</em> klasörünü bulacaksınız. Bu klasöre de girdiğinizde de listedeki ilk videoyu en üstte bulacaksınız.</p>
<h4 id="çalma-listesi-ses-indir.bat">2.2. çalma listesi ses indir.bat</h4>
<p>Dosya çalıştırıldığında sizden çalma listesi URL’si isteyecektir. URL’yi yapıştırıp <code>ENTER</code> tuşuna bastığınızda çalma listesindeki tüm içerik, <em>indirmeler</em> klasörünün içindeki <em>listeler</em> klasöründe oluşturulacak <em>“çalma listesi adı” ses</em> isimli klasöre, listenin en üstündeki video en üstte olacak şekilde indirilecektir.</p>
<p>Diyelim ki <a href="https://youtube.com/c/babaprogramlar">Baba Programlar</a> kanalındaki <strong>Discord</strong> çalma listesindeki içerikleri indirmek için <code>https://www.youtube.com/playlist?list=PLzD2mZ6wwf1TaYIjUNgxzN-HV1Cw6tDTX</code> URL’sini yapıştırdınız ve <code>Enter</code>’a bastınız. Tüm indirmeler tamamlanıp da pencere kapandığında <em>indirmeler</em> klasörünün içinde <em>listeler</em> klasörünü, onun içinde de <em>Discord ses</em> klasörünü bulacaksınız. Bu klasöre de girdiğinizde de listedeki ilk videoyu en üstte bulacaksınız.</p>
<h3 id="video-indirme">3. Video İndirme</h3>
<p>Bu başlıkta iki adet dosyamız var. Bu dosyalar, verdiğimiz linkin ait olduğu videoyu indirir.</p>
<h4 id="tek-video-indir.bat">3.1. tek video indir.bat</h4>
<p>Dosya çalıştırıldığında sizden video URL’si isteyecektir. URL’yi yapıştırıp <code>ENTER</code> tuşuna bastığınızda video, <em>indirmeler</em> klasörünün içindeki <em>videolar</em> klasöründe oluşturulacak <em>“kanal adı</em> isimli klasörün de altında oluşturulacak <em>video</em> klasörüne, içeriğin başlığını isim alacak şekilde indirilecektir.</p>
<p>Diyelim ki <a href="https://youtube.com/c/babaprogramlar">Baba Programlar</a> kanalındaki <strong>Youtube-dl Kullanımı</strong> videosunu indirmek için <code>https://www.youtube.com/watch?v=aXEoMjoZ81I</code> URL’sini yapıştırdınız ve <code>Enter</code>’a bastınız. Tüm indirmeler tamamlanıp da pencere kapandığında <em>indirmeler</em> klasörünün içinde <em>videolar</em> klasörünü, onun içinde de <em>Baba Programlar</em> klasörünü bulacaksınız. Bu klasörün de içinde bulacağınız <em>video</em> klasörüne de girdiğinizde videoyu indirilmiş olarak bulacaksınız.</p>
<h4 id="tek-ses-indir.bat">3.2. tek ses indir.bat</h4>
<p>Dosya çalıştırıldığında sizden video URL’si isteyecektir. URL’yi yapıştırıp <code>ENTER</code> tuşuna bastığınızda video, <em>indirmeler</em> klasörünün içindeki <em>videolar</em> klasöründe oluşturulacak <em>“kanal adı</em> isimli klasörün de altında oluşturulacak <em>ses</em> klasörüne, içeriğin başlığını isim alacak şekilde indirilecektir.</p>
<p>Diyelim ki <a href="https://youtube.com/c/babaprogramlar">Baba Programlar</a> kanalındaki <strong>Youtube-dl Kullanımı</strong> videosunu indirmek için <code>https://www.youtube.com/watch?v=aXEoMjoZ81I</code> URL’sini yapıştırdınız ve <code>Enter</code>’a bastınız. Tüm indirmeler tamamlanıp da pencere kapandığında <em>indirmeler</em> klasörünün içinde <em>videolar</em> klasörünü, onun içinde de <em>Baba Programlar</em> klasörünü bulacaksınız. Bu klasörün de içinde bulacağınız <em>ses</em> klasörüne de girdiğinizde videoyu indirilmiş olarak bulacaksınız.</p>
<hr />
<h2 id="olası-sorunlar-ve-çözümleri">Olası Sorunlar ve Çözümleri</h2>
<p>Bu son bölümde ise, içerikleri indirirken yaşayabileceğiniz sorunlara, ve bu sorunları nasıl çözebileceğinize değineceğiz.</p>
<h3 id="neden-linkleri-yapıştıramıyorum">Neden Linkleri Yapıştıramıyorum?</h3>
<p>Betiklerin çalışacağı alan <em>Komut Satırı Arayüzü</em> olduğu için, böyle bir problem yaşamanız normal. <code>CTRL+V</code> tuş kombinasyonunu kullanarak yapıştırmayı denediğinizde, URL’nizin yerine farklı bir karakter yerleşiyor ya da hiç bir etkileşim olmuyorsa aşağıdaki adımları uygulayın:</p>
<ol type="1">
<li>Dosyanızı çalıştırır çalıştırmaz, herhangi bir bilgi girişinde bulunmadan <code>Alt+Boşluk</code> kısayolu yardımıyla <em>sistem</em> menüsünü etkinleştirin;</li>
<li><code>Aşağı ok / Yukarı ok</code> yardımıyla <em>Düzenle</em> alt menüsünü bulun ve <code>Sağ ok</code> ile etkinleştirin;</li>
<li>Buradaki menüde, <code>Yukarı / Aşağı ok</code> tuşları yardımıyla <em>Yapıştır</em> ibaresini duyduğunuzda <code>Enter</code> tuşuna basın.</li>
</ol>
<p>Bu adımlardan sonra tekrar <code>Enter</code> tuşuna basın ve dosyanızı sorunsuz bir şekilde indirmeye başlayın.</p>
<h3 id="neden-betikler-hızlıca-kapanıyor">Neden Betikler Hızlıca Kapanıyor?</h3>
<p>Bu sorun, <em>Youtube-DL</em> uygulamasının güncellenmesi gerekmesi sebebiyle ortaya çıkıyor. Güncellemeyi, betik arşivinizi bozmadan yapabilmek için aşağıdaki adımları uygulayın:</p>
<ol type="1">
<li>Betik dosyalarının bulunduğu klasöre girin;</li>
<li><code>F4</code> tuşuna basarak <em>Adres Çubuğu</em>’nu etkinleştirin;</li>
<li><code>CTRL+A</code>, ardından <code>Delete</code> tuşlarına basarak oradaki içeriği temizleyin;</li>
<li>Bulunduğunuz yere küçük harflerle <code>cmd</code> yazın ve <code>Enter</code> tuşuna basın;</li>
<li>Açılan pencereye aşağıdaki kodu yazıp <code>Enter</code> tuşuna basın. Dilerseniz bu kodu buradan kopyalayabilirsiniz:</li>
</ol>
<p>
<input type="text" readonly="readonly"value="youtube-dl -U" />
</p>
<p>Arşivdeki <em>youtube-dl.exe</em> dosyası güncellenmiş olacağından, sorunsuz indirmeye devam edebilirsiniz. Dilerseniz bu betik klasörünü sıkıştırarak, en güncel ^hâli ile arşivleyebilirsiniz.</p>
<hr />
<h2 id="son-notlar">Son Notlar</h2>
<p>Umarız yukarıdaki bilgilerle sorunsuz bir içerik indirme deneyimi yaşarsınız. İçeriği faydalı bulduysanız, Aşağıdaki platformlardan bizleri takip etmeyi ve sevdiklerinizle paylaşmayı unutmayınız.</p>
<table>
<thead>
<tr class="header">
<th style="text-align: left;">Platform</th>
<th style="text-align: right;">Bağlantı</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;">Youtube</td>
<td style="text-align: right;"><a href="https://youtube.com/c/babaprogramlar">Baba Programlar</a></td>
</tr>
<tr class="even">
<td style="text-align: left;">Telegram</td>
<td style="text-align: right;">@<a href="https://t.me/borfirbora">borfirbora</a></td>
</tr>
<tr class="odd">
<td style="text-align: left;">Facebook</td>
<td style="text-align: right;"><a href="https://www.facebook.com/bora.firlangec/">Bora FIRLANGEÇ</a></td>
</tr>
<tr class="even">
<td style="text-align: left;">Twitter</td>
<td style="text-align: right;">@<a href="https://twitter.com/firbora">firbora</a></td>
</tr>
</tbody>
</table>
<hr />
</body>
</html>
