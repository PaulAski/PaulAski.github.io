# A-SCI Paweł Adamski - strona firmowa

Wersja pakietu: **2026-10-17-r8**

Pakiet jest gotowy do publikacji jako statyczna strona GitHub Pages pod adresem `https://paulaski.github.io/`.

## Publikacja

1. Rozpakuj archiwum.
2. Umieść całą zawartość rozpakowanego katalogu w głównym katalogu repozytorium `paulaski.github.io` (zastąp dotychczasowe pliki).
3. W GitHub otwórz **Settings -> Pages**.
4. W sekcji **Build and deployment** wybierz **Deploy from a branch**.
5. Wskaż branch `main` i katalog `/ (root)`.

Nie przesyłaj samego archiwum ZIP. Strona nie wymaga Node.js, Reacta ani procesu budowania.

Arkusz stylów i skrypt mają w adresie dopisek `?v=r8`, więc odwiedzający od razu dostaną nową wersję. Jeśli po publikacji widzisz starą wersję, odśwież stronę klawiszami Ctrl+F5 (Mac: Cmd+Shift+R).

## Nowości w r8 – strona główna, warstwy

- sekcja Kompetencje wjeżdża na nagłówek strony jak karta (zaokrąglone rogi, cień); nagłówek w tym czasie lekko się oddala i przyciemnia,
- Proces: 5 etapów układa się w talię; każdy kolejny nachodzi na poprzedni tylko dolnym marginesem, więc nazwy i opisy zostają widoczne; tekst po lewej stoi w miejscu, pasek postępu wypełnia się do ✓, licznik pokazuje etap (01–05), a cała talia odjeżdża razem,
- na telefonie 4 karty Kompetencji układają się w talię; przykryte karty lekko się oddalają,
- Yearborne: telefon, karty „Wybór” i „Historia” oraz okręgi przesuwają się z różną prędkością (głębia); na komputerze telefon pochyla się za kursorem; liczby 78 / 64 / 91 odliczają się przy pierwszym pokazaniu,
- czytelność: tekst nie jest zasłaniany, zanim da się go przeczytać; na zbyt niskich ekranach talia wyłącza się sama i etapy są zwykłą listą,
- przy ustawieniu „ogranicz ruch” i bez JavaScriptu układ jest statyczny,
- obciążenie przeglądarki przy przewijaniu na poziomie poprzedniej wersji.

## Nowości w r7 – polityka prywatności

- pasek nawigacji taki sam jak na stronie głównej: granatowy, z animowanym logo, linią światła, menu i wyborem języka; przy przewijaniu w górę wraca jako szklany pasek,
- animowany nagłówek strony: ikona Yearborne bez czarnej ramki, z poświatą, obracającymi się orbitami, złotymi świetlikami, połyskiem i delikatnym pochyleniem za kursorem,
- informacje o dokumencie w formie etykiet: data obowiązywania, liczba sekcji, czas czytania,
- przyciski „Spis treści” i „Wróć na stronę A-SCI”,
- spis treści z numeracją i podświetleniem sekcji, którą właśnie czytasz,
- pasek postępu czytania u góry ekranu,
- karta z danymi dokumentu (data, aplikacja, wydawca, kontakt), wyróżnione numery sekcji, płynne pojawianie się treści przy przewijaniu,
- stopka jak na stronie głównej: logo przenoszące na górę, linki, kontakt i wybór języka,
- przy systemowym ustawieniu „ogranicz ruch” animacje są wyłączone, a cała treść jest widoczna od razu.

## Nowości w r6 – strona główna

- animowane logo A-SCI PROJECTS w lewym górnym rogu: wektorowe, ostre na każdym ekranie, z delikatnym falowaniem i przebiegającym połyskiem, bez białej ramki,
- animowany pasek nawigacji: linia ze światłem, płynne wejście menu, połysk na przycisku „Poznaj A-SCI”,
- przy przewijaniu w górę pasek wraca jako szklany pasek przyklejony do góry ekranu, przy przewijaniu w dół chowa się,
- przycisk „na górę” w prawym dolnym rogu (także w polityce prywatności): falujące logo A-SCI na granatowej karcie; po najechaniu płynnie wysuwa się strzałka w górę i napis „Na górę”; na telefonie strzałka jest widoczna stale,
- logo w stopce również przenosi na początek strony i pokazuje strzałkę po najechaniu,
- poprawione nachodzenie nagłówka i opisu na „Mapę dostarczania produktu” na laptopach (szerokość ok. 1180–1440 px) oraz przycisku na tę grafikę na telefonach,
- „Mapa dostarczania produktu”: napisy mieszczą się w kafelkach przy każdej szerokości ekranu, etykiety między kafelkami nie są ucinane,
- lżejsza ikona Yearborne: 58 KB zamiast 2,7 MB (szybsze ładowanie strony),
- przy systemowym ustawieniu „ogranicz ruch” oraz na urządzeniach bez WebGL wyświetla się statyczne logo.

## Nowe pliki

- `assets/a-sci-premium.js` – animacja logo, pasek nawigacji, przycisk „na górę” i animacje polityki prywatności,
- `assets/a-sci-logo-white.svg` – logo wektorowe,
- `assets/yearborne-icon-384.jpg` – lekka ikona Yearborne (strona główna),
- `assets/yearborne-icon-hero.jpg` – ikona Yearborne bez czarnej ramki (polityka prywatności).

Pliki `assets/a-sci-logo-cropped.png` i `assets/yearborne-icon.png` nie są już używane przez strony. Zostały w pakiecie na wypadek linków zewnętrznych; można je usunąć.

## Zawartość

- kompletna strona firmowa w języku polskim, angielskim i francuskim,
- prezentacja software, aplikacji mobilnych, project managementu oraz testów i QA,
- sekcja Yearborne: Life Simulator z właściwą ikoną gry,
- statyczna polityka prywatności Yearborne w trzech językach, w tym samym stylu co strona główna,
- zbalansowana sekcja Testy i QA z wyraźną hierarchią treści,
- animowane, wektorowe logo A-SCI Projects w nagłówku, stopce i przycisku „na górę”,
- odświeżona prezentacja Yearborne z nowym hasłem oraz poświatą pod telefonem,
- favicon A-SCI czytelny w karcie przeglądarki,
- responsywny wygląd dla komputerów, tabletów i telefonów,
- metadane SEO i odnośniki wersji językowych.
