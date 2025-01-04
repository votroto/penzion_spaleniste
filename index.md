---
layout: index
title: "Penzion Spáleniště: Místo s historií"
description: "Penzion s vlastním rybníkem v Orlických horách u Dobrušky. Pro milovníky soukromí, klidu a rybaření."
imgs_intro: [
    {alt: "vchod do penzionu", src: "/cimg/index_vcho_small.webp"},
    {alt: "venkovní gril v pergole", src: "/cimg/index_gril_small.webp"},
    {alt: "klouzačka, houpačky a pískoviště pro děti", src: "/cimg/index_houp_small.webp"},
    {alt: "rybník", src: "/cimg/index_rybp_small.webp"},
]
imgs_fishing: [
    {alt: "značka u rybníku", src: "/cimg/index_znac_small.webp"},
    {alt: "pohled na rybník", src: "/cimg/index_rybn_small.webp"},
    {alt: "loďka na rybníku", src: "/cimg/index_lodr_small.webp"},
]
imgs_booking: [
    {name: "Apartmán Dvojka", src: "/cimg/index_dvoj_small.webp", description: "Apartmán se dvěmi ložnicemi v přízemí.", alt: "dvojka"},
    {name: "Apartmán Jednička", src: "/cimg/index_jedn_small.webp", description: "Apartmán se dvěmi ložnicemi v prvním patře.", alt: "jednicka"},
    {name: "Maringotka", src: "/cimg/index_mari_small.webp", description: "Maringotka přímo na břehu rybníka.", alt: "maringotka"}
]
---

## Místo s historií

Můj prapředek koupil pozemky, na nichž penzion stojí, od hraběte Colloredo Mansfelda z Opočna. Zúrodnil je, postavil statek, vybudoval rybník. Nyní je statek po rekonstrukci, v rámci které byly v jeho části vytvořeny dva apartmány.

<div class="owl-carousel-wrapper">
    <div class="owl-carousel owl-theme">
    {%- for img in page.imgs_intro -%}
        <div><img class="carousel-img" alt="{{ img.alt }}" src="{{ site.asset_server }}{{ img.src }}" height="520"/></div>
    {%- endfor -%}
    </div>
</div>

Nabízíme parkování za uzamykatelnou bránou, venkovní posezení s možností grilování, pípu s vynikajícím místním pivem Rampušákem. Dalé také houpačky, pískoviště a klouzačku pro děti; stolní tenis, i pokrytí Wi-Fi signálem.

<a href="/about.html" class="hero-link">Více o penzionu</a>

<br>

## Ubytování
Penzion je ideální pro rodiny nebo skupiny přátel, kteří preferují vlastní přípravu jídla v plně vybavené kuchyni. Není zařízen pro pobyt s domácími mazlíčky.

<div class="owl-carousel owl-theme">
{%- for img in page.imgs_booking -%}
    <div>
        <div class="carousel-card">
            <img class="carousel-img" alt="{{ img.alt }}" src="{{ site.asset_server }}{{ img.src }}" height="520"/>
            <h5>{{ img.name }}</h5>
            <p>{{ img.description }}</p>
            <a href="/booking.html#{{ img.alt }}" class="hero-link">Detail</a>
        </div>
    </div>
{%- endfor -%}
</div>

<br>

## Rybářská dovolená
Rybářská dovolená, sportovní rybolov, prostě chytání ryb, je u našeho rybníku intimní záležitost. Váš koníček zde nebude nikým a ničím rušen. A všechny ryby v rybníce Vám budou k dispozici.

<div class="owl-carousel-wrapper">
    <div class="owl-carousel owl-theme">
    {%- for img in page.imgs_fishing -%}
        <div><img class="carousel-img" alt="{{ img.alt }}" src="{{ site.asset_server }}{{ img.src }}" height="520"/></div>
    {%- endfor -%}
    </div>
</div>

Můžete si zarybařit v našem rybníku o rozloze cca 1 ha, hned vedle usedlosti. Klid, soukromí, z jedné strany olšiny, z druhé strany louky, dobrý přístup k vodě a v ní 20 metráků ryb.

<a href="/fishing.html" class="hero-link">Informace k rybolovu</a>