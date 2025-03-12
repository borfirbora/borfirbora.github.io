---
title: NVDA Eğitimi
subtitle: Sıfırdan İleri Düzeye NVDA Öğrenin!
permalink: nvda
layout: minimal
---

## Eğitim Menüsü

* [Eğitim Yazılımını İndirin](https://server.borfirbora.com/EduAppNVDA-1.0.exe)
* [Eğitimi Satın Alın](https://www.shopier.com/ShowProductNew/products.php?id=33046312)

<div class="container mt-5">
    <ul class="nav nav-tabs" id="nvdaTab" role="tablist">
        <li class="nav-item" role="presentation">
            <button class="nav-link active" id="nvda-hakkinda-tab" data-bs-toggle="tab" data-bs-target="#nvda-hakkinda" type="button" role="tab">NVDA Hakkında</button>
        </li>
        <li class="nav-item" role="presentation">
            <button class="nav-link" id="egitim-hakkinda-tab" data-bs-toggle="tab" data-bs-target="#egitim-hakkinda" type="button" role="tab">NVDA Eğitimi Hakkında</button>
        </li>
        <li class="nav-item" role="presentation">
            <button class="nav-link" id="kimler-icin-tab" data-bs-toggle="tab" data-bs-target="#kimler-icin" type="button" role="tab">Eğitim Kimler İçin?</button>
        </li>
        <li class="nav-item" role="presentation">
            <button class="nav-link" id="nvda-mufredati-tab" data-bs-toggle="tab" data-bs-target="#nvda-mufredati" type="button" role="tab">NVDA Eğitim Müfredatı</button>
        </li>
                <li class="nav-item" role="presentation">
            <button class="nav-link" id="satin-alma-tab" data-bs-toggle="tab" data-bs-target="#satin-alma" type="button" role="tab">NVDA Eğitimi Satın Alma</button>
        </li>
    </ul>

    <div class="tab-content mt-3" id="nvdaTabContent">
        <div class="tab-pane fade show active" id="nvda-hakkinda" role="tabpanel">
        {% capture nvda_1 %}{% include nvda-1.md %}{% endcapture %}
{{ nvda_1 | markdownify }}

        </div>
        <div class="tab-pane fade" id="egitim-hakkinda" role="tabpanel">
        {% capture nvda_2 %}{% include nvda-2.md %}{% endcapture %}
{{ nvda_2 | markdownify }}

        </div>
        <div class="tab-pane fade" id="kimler-icin" role="tabpanel">
        {% capture nvda_3 %}{% include nvda-3.md %}{% endcapture %}
{{ nvda_3 | markdownify }}

        </div>
        <div class="tab-pane fade" id="satin-alma" role="tabpanel">
{% capture nvda_4 %}{% include nvda-4.md %}{% endcapture %}
{{ nvda_4 | markdownify }}

        </div>
        <div class="tab-pane fade" id="nvda-mufredati" role="tabpanel">
{% capture nvda_5 %}{% include nvda-5.md %}{% endcapture %}
{{ nvda_5 | markdownify }}

        </div>
    </div>
</div>


<!-- <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script> -->
