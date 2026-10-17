# A-SCI Paweł Adamski - strona firmowa

Wersja pakietu: **2026-10-16-r6**

Pakiet jest gotowy do publikacji jako statyczna strona GitHub Pages pod adresem `https://paulaski.github.io/`.

## Publikacja

1. Rozpakuj archiwum.
2. Umieść całą zawartość rozpakowanego katalogu w głównym katalogu repozytorium `paulaski.github.io` (zastąp dotychczasowe pliki).
3. W GitHub otwórz **Settings -> Pages**.
4. W sekcji **Build and deployment** wybierz **Deploy from a branch**.
5. Wskaż branch `main` i katalog `/ (root)`.

Nie przesyłaj samego archiwum ZIP. Strona nie wymaga Node.js, Reacta ani procesu budowania.

Arkusz stylów i skrypt mają w adresie dopisek `?v=r6`, więc odwiedzający od razu dostaną nową wersję. Jeśli po publikacji widzisz starą wersję, odśwież stronę klawiszami Ctrl+F5 (Mac: Cmd+Shift+R).

## Nowości w r6

- animowane logo A-SCI PROJECTS w lewym górnym rogu: wektorowe, ostre na każdym ekranie, z delikatnym falowaniem i przebiegającym połyskiem, bez białej ramki,
- animowany pasek nawigacji: linia ze światłem, płynne wejście menu, połysk na przycisku „Poznaj A-SCI”,
- przy przewijaniu w górę pasek wraca jako szklany pasek przyklejony do góry ekranu, przy przewijaniu w dół chowa się,
- przycisk „na górę” w prawym dolnym rogu: falujące logo A-SCI na granatowej karcie; po najechaniu płynnie wysuwa się strzałka w górę i napis „Na górę”; na telefonie strzałka jest widoczna stale,
- logo w stopce również przenosi na początek strony i pokazuje strzałkę po najechaniu,
- polityki prywatności: logo wektorowe w kolorze granatowym oraz ten sam przycisk „na górę”,
- poprawione nachodzenie nagłówka i opisu na „Mapę dostarczania produktu” na laptopach (szerokość ok. 1180–1440 px) oraz przycisku na tę grafikę na telefonach,
- „Mapa dostarczania produktu”: napisy mieszczą się w kafelkach przy każdej szerokości ekranu, etykiety między kafelkami nie są ucinane,
- lżejsza ikona Yearborne: 58 KB zamiast 2,7 MB (szybsze ładowanie strony),
- przy systemowym ustawieniu „ogranicz ruch” oraz na urządzeniach bez WebGL wyświetla się statyczne logo.

## Nowe pliki

- `assets/a-sci-premium.js` – animacja logo, pasek nawigacji i przycisk „na górę”,
- `assets/a-sci-logo-white.svg`, `assets/a-sci-logo-navy.svg` – logo wektorowe,
- `assets/yearborne-icon-384.jpg` – lekka ikona Yearborne.

Pliki `assets/a-sci-logo-cropped.png` i `assets/yearborne-icon.png` nie są już używane przez strony. Zostały w pakiecie na wypadek linków zewnętrznych; można je usunąć.

## Zawartość

- kompletna strona firmowa w języku polskim, angielskim i francuskim,
- prezentacja software, aplikacji mobilnych, project managementu oraz testów i QA,
- sekcja Yearborne: Life Simulator z właściwą ikoną gry,
- statyczna polityka prywatności Yearborne w trzech językach,
- zbalansowana sekcja Testy i QA z wyraźną hierarchią treści,
- animowane, wektorowe logo A-SCI Projects w nagłówku, stopce i przycisku „na górę”,
- odświeżona prezentacja Yearborne z nowym hasłem oraz poświatą pod telefonem,
- favicon A-SCI czytelny w karcie przeglądarki,
- responsywny wygląd dla komputerów, tabletów i telefonów,
- metadane SEO i odnośniki wersji językowych.
