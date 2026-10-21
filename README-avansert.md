# Om meg-nettside: Avansert

Lag en «Om meg»-side med god HTML-struktur, og gi den et eget uttrykk med litt CSS. HTML-strukturen er fortsatt grunnlaget, og CSS skal ligge i en egen fil.

## Om oppgaven

Du skal lage en «Om meg»-nettside som presenterer deg selv. Du starter med å opprette et eget repository på GitHub, og leverer oppgaven ved å lenke til det. Dette nivået har to deler: først bygger du siden med god HTML-struktur, og deretter styler du den med litt CSS.

**Dette gjelder for oppgaven:**

- Startsiden skal hete `index.html`, og alt du lager legges i repository-mappen din.
- Hver side skal ha riktig grunnstruktur: `<!DOCTYPE html>`, `<html lang="no">`, `<head>` med `<meta charset="UTF-8">` og `<title>`, og `<body>`.
- Innholdet skal handle om deg. Ikke legg ut adresse, telefonnummer eller andre opplysninger du ikke vil dele offentlig.
- Koden skal ha riktig innrykk, og du skal bruke minst tre kommentarer som forklarer hva delene av koden gjør (`<!-- -->` i HTML og `/* */` i CSS).
- Test siden i nettleseren etter hver endring, og lagre ofte.

## Kom i gang: lag et repository

Før du skriver kode skal du opprette et eget repository på github.com og åpne det i GitHub Desktop. Derfra åpner du prosjektet i VS Code. Repositoryet er der du lagrer alt du lager i oppgaven, og det er det du leverer inn til slutt.

1. Logg inn på github.com, og trykk **New** for å opprette et nytt repository. Gi det et navn, for eksempel `om-meg-nettside`, og trykk **Create repository**.
2. Trykk den grønne **Code**-knappen på repository-siden og velg **Open with GitHub Desktop**. Alternativt kan du velge **File → Clone repository** i GitHub Desktop og finne repositoryet i listen.
3. Velg en plassering på PC-en under **Local path**, og trykk **Clone**. Husk hvor mappen ligger. Dette blir prosjektmappen din.
4. Trykk **Open in Visual Studio Code** i GitHub Desktop for å åpne prosjektmappen i VS Code. Alle filene til nettsiden skal lages her.
5. Mens du jobber: når du har fått til en del, skriv en kort beskrivelse i **Summary** i GitHub Desktop, trykk **Commit to main** og deretter **Push origin**.

## Oppgaver

### Del 1: HTML-struktur

1. Lag en «Om meg»-side med hovedoverskrift (`<h1>`), et avsnitt om deg selv (`<p>`), minst tre deler med underoverskrifter (`<h2>`) og minst ett bilde med `alt`-tekst.
2. Del siden inn i semantiske elementer: `<header>`, `<nav>`, `<main>` med `<section>` for hver del, og `<footer>`.
3. Lag en navigasjonsmeny i `<nav>` med en liste av lenker som hopper til de ulike delene på siden (interne lenker med `id` og `href="#..."`).
4. Lag en tabell (`<table>`, `<tr>`, `<th>`, `<td>`) med fakta om deg eller for eksempel ukeskjemaet ditt. Tabellen skal ha overskriftsceller (`<th>`).
5. Legg inn et bilde i `<figure>` med bildetekst i `<figcaption>`, og et favorittsitat i `<blockquote>`.
6. Lag minst én ekstra side, for eksempel `interesser.html`, og lenk sidene sammen i begge retninger med relative lenker.
7. Ordne filene i mapper, for eksempel én mappe til bilder, og bruk riktige filstier i `src` og `href`.

### Del 2: CSS

8. Opprett filen `style.css`, og koble den til alle sidene med `<link rel="stylesheet" href="style.css">` i `<head>`.
9. Velg en fargepalett på 3–4 farger, og sett bakgrunnsfarge og tekstfarge på `body` (`background-color`, `color`).
10. Velg en skrifttype for hele siden med `font-family`, og sett en lesbar `font-size` og `line-height`.
11. Gi overskriftene, avsnittene og menyen egen styling med element-velgere (for eksempel `h1`, `p` og `nav a`).
12. Bruk `margin` og `padding` for å gi innholdet luft, og sett `max-width` på `<main>` slik at teksten ikke blir for bred.
13. Gjør navigasjonsmenyen horisontal, og legg til en `:hover`-effekt på lenkene.
14. Style bildet ditt med `width`, `border-radius` og eventuelt `border`.
15. Bruk minst én klasse (`class="..."`) og én `id` i HTML-en, og velg dem i CSS med `.klasse` og `#id`.
16. Valgfri utfordring: bruk Flexbox (`display: flex`) til å legge to deler side om side, og lag en enkel `@media`-regel som endrer layouten på smale skjermer.

## Sjekk før innlevering

- [ ] Siden bruker `<header>`, `<nav>`, `<main>` og `<footer>`
- [ ] Alle lenker mellom sidene fungerer, og alle bilder vises
- [ ] CSS ligger i `style.css`, ikke i HTML-filene
- [ ] Siden har minst åtte CSS-regler
- [ ] Tekst og bakgrunn har god nok kontrast til at teksten er lett å lese
- [ ] Koden har riktig innrykk og kommentarer
- [ ] Du har testet siden i nettleseren, og gjerne også på mobilstørrelse
- [ ] Repositoryet er opprettet på GitHub.com og åpnet i GitHub Desktop, alle endringer er pushet, og lenken fungerer

## Innlevering

Oppgaven leveres som lenken til repositoryet ditt på GitHub:

1. Kontroller i GitHub Desktop at alle endringer er committet, og trykk **Push origin** slik at siste versjon ligger på GitHub.
2. Åpne repositoryet på GitHub.com og sjekk at alle HTML-sider, `style.css` og bildemappen er der.
3. Lever inn lenken til repositoryet innen fristen på Teams. Kontroller at læreren har tilgang til repositoryet (public).
