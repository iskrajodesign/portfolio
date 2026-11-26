# IskraJoDesign портфолио

Статичен веб-сајт од една страница. Нема build, нема зависности и нема надворешни скрипти или CSS.

## Структура

    index.html          целата страница: HTML, CSS, JavaScript и вградени фонтови
    img/                146 слики (.webp, плус og.jpg и apple-touch-icon.png)
    robots.txt          правила за пребарувачи
    sitemap.xml         мапа на сајтот
    README.md           овој опис

Влезна точка е `index.html`. Нема други страници.

## Јазици

Македонски (стандарден), англиски и српски (кирилица). Јазикот се менува без освежување на страницата, преку МК / EN / SR во врвот.

## Објавување на GitHub Pages

Репозиториум: `iskrajodesign/iskrajodesign.portfolio`, гранка `main`, папка `/ (root)`.
Адреса: https://iskrajodesign.github.io/iskrajodesign.portfolio/

1. Качи ги `index.html`, `robots.txt`, `sitemap.xml` и целата папка `img/` во коренот на репозиториумот.
2. Settings, Pages, Source: "Deploy from a branch", Branch: `main`, папка `/ (root)`.
3. По 1 до 2 минути сајтот е онлајн.

Забелешка: GitHub дозволува најмногу 100 датотеки по едно качување преку веб-страницата. Затоа фонтовите се вградени во `index.html`. Ако качуваш рачно, подели ја папката `img/` на два дела.

## Адреса во `<head>`, sitemap и robots

`canonical`, `og:url`, `og:image`, JSON-LD, `sitemap.xml` и `robots.txt` во моментов покажуваат на https://iskrajodesign.vercel.app/. Тие не се менуваат додека не се потврди конечната адреса на сајтот. Кога ќе се потврди, адресата се менува на тие места.

## Формулар

Формуларот праќа преку FormSubmit на iskrajodesign@gmail.com. Првиот пат FormSubmit праќа е-маил за потврда, а пораките стигнуваат дури откако ќе се потврди. Ако праќањето не успее, се нуди врска за испраќање преку е-пошта.

## Фонтови

Old Standard TT, Spectral, JetBrains Mono и Unbounded (латиница и кирилица) се вградени во `index.html`. Нема повици кон Google. Лиценца OFL (Fontsource).

## Надворешни врски

Проектите се отвораат на `iskrajodesign.github.io/...` страници. Закажувањето води до Calendly (https://calendly.com/iskrajodesign/30min).
