---
layout: default
title: "Ubytování v apartmánech nebo u rybníka"
description: "Ubytování v jednom ze dvou apartmánů se dvěmi ložnicemi a plně vybavenou kuchyní, nebo v maringotce u rybníka."
imgs_jednicka: [
    {alt: "ložnice", src: "/img/booking_jedn_lozn_small.webp"},
    {alt: "kuchyně", src: "/img/booking_jedn_kuch_small.jpg"},
    {alt: "pokoj", src: "/img/booking_jedn_poko_small.jpg"},
    {alt: "koupelna", src: "/img/booking_jedn_koup_small.jpg"},
    {alt: "podkroví", src: "/img/booking_jedn_leti_small.webp"},
]
imgs_dvojka: [
    {alt: "ložnice", src: "/img/booking_dvoj_lozn_small.webp"},
    {alt: "kuchyně", src: "/img/booking_dvoj_kuch_small.webp"},
    {alt: "kuchyně", src: "/img/booking_dvoj_kuc2_small.webp"},
    {alt: "pokoj", src: "/img/booking_dvoj_poko_small.jpg"},
    {alt: "záchod", src: "/img/booking_dvoj_zach_small.jpg"},
]
imgs_maringotka: [
    {alt: "maringotka z venku", src: "/img/booking_mari_venk_small.webp"},
    {alt: "vnitřek maringotky", src: "/img/booking_mari_vnit_small.webp"},
]
---

# Ubytování v penzionu

Penzion je určen pro klienty, kteří preferují vlastní přípravu jídla v plně vybavené kuchyni. Není zařízen pro pobyt s domácími mazlíčky.

<a href="{{ site.asset_server }}/docs/ubytovaci_rad_2022.pdf" class="hero-link">Ubytovací řád</a>
<a href="{{ site.asset_server }}/docs/prijezdovy_formular_2022.pdf" class="hero-link">Příjezdový formulář</a>

<br>

<h2 id="jednicka">Apartmán Jednička</h2>

Apartmán je umístěn v 1. patře a pro maximum soukromí se do něj vchází samostatným vchodem. Skládá se ze dvou ložnic (celkem 4 lůžka + možnost až dvou přistýlek), koupelny a plně vybavené kuchyně. Z apartmánu jsou výhledy jedním směrem do luk a polí, v opačném směru do dvorku usedlosti.

Lze domluvit i využití prostorného podkrovního „Letiště“ až pro 5 nocležníků ve spacích pytlích, které zvyšuje jeho ubytovací kapacitu.

<div class="owl-carousel owl-theme">
{%- for img in page.imgs_jednicka -%}
    <div><img class="carousel-img" alt="{{ img.alt }}" src="{{ site.asset_server }}{{ img.src }}" /></div>
{%- endfor -%}
</div>

Apartmán pro 4 osoby za 2 400,- Kč za noc. Možnost max. dvou přistýlek za 450,- Kč za osobu a noc. Lze domluvit i využití půdy pro až pět nenáročných nocležníků za 450,- Kč za osobu a noc.

<a href="#trevlix" class="hero-link">Rezervovat</a>

<br>

<h2 id="dvojka">Apartmán Dvojka</h2>

Apartmán je umístěn v přízemí, má samostatný vchod. Skládá se ze dvou ložnic (celkem 4 lůžka + možnost až dvou přistýlek), koupelny a kuchyně. Z apartmánu jsou výhledy jedním směrem do zahrady, luk a polí, v opačném směru do dvorku usedlosti, ve které se apartmán nachází.

<div class="owl-carousel owl-theme">
{%- for img in page.imgs_dvojka -%}
    <div><img class="carousel-img" alt="{{ img.alt }}" src="{{ site.asset_server }}{{ img.src }}" /></div>
{%- endfor -%}
</div>

Apartmán pro 4 osoby za 2 400,- Kč za noc. Možnost max. dvou přistýlek za 450,- Kč za osobu a noc.

<a href="#trevlix" class="hero-link">Rezervovat</a>

<br>

<h2 id="maringotka">Maringotka</h2>

Maringotka pro rybáře na břehu rybníka. Maringotka je vybavená dvojpostelí a kuchyňkou s lednicí, plynovým vařičem a kamny na dřevo. Součástí je terasa s posezením a možností rybolovu. K dispozici je Wi-Fi připojení. Možnost až dvou přistýlek na nafukovacích matracích. Na hranici lesa jsou dva suché záchody.

<div class="owl-carousel owl-theme">
{%- for img in page.imgs_maringotka -%}
    <div><img class="carousel-img" alt="{{ img.alt }}" src="{{ site.asset_server }}{{ img.src }}" /></div>
{%- endfor -%}
</div>

Maringotka pro 2 osoby za 1000 Kč za noc s možností stanování u maringotky za 300 Kč, případně dle telefonické dohody.

<a href="#trevlix" class="hero-link">Rezervovat</a>

<br>
<hr>
<br>

<iframe id="trevlix" loading="lazy" src="https://book.trevlix.com/book/app/?cid=7149256" name="trevlix-book-app" scrolling="auto" style="height: 857px;" width="100%" height="1100" frameborder="0"></iframe>

<script>
const fab = document.querySelector('#fab-booking');
fab.style.visibility="hidden";
</script>