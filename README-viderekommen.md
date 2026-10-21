# Om meg-nettside: Viderekommen

Lag en oversiktlig «Om meg»-side med semantiske elementer, tabell og flere sider som henger sammen. Du bruker fortsatt kun HTML, og skal ikke bruke CSS.

## Om oppgaven

Du skal lage en «Om meg»-nettside som presenterer deg selv. Du starter med å opprette et eget repository på GitHub, og leverer oppgaven ved å lenke til det. Dette nivået handler om semantisk HTML, tabeller og å få flere sider til å henge sammen.

**Dette gjelder for oppgaven:**

- Startsiden skal hete `index.html`, og alt du lager legges i repository-mappen din.
- Hver side skal ha riktig grunnstruktur: `<!DOCTYPE html>`, `<html lang="no">`, `<head>` med `<meta charset="UTF-8">` og `<title>`, og `<body>`.
- Innholdet skal handle om deg. Ikke legg ut adresse, telefonnummer eller andre opplysninger du ikke vil dele offentlig.
- Koden skal ha riktig innrykk, og du skal bruke minst tre kommentarer (`<!-- -->`) som forklarer hva delene av koden gjør.
- Test siden i nettleseren etter hver endring, og lagre ofte.

## Kom i gang: lag et repository

Før du skriver kode skal du opprette et eget repository på github.com og åpne det i GitHub Desktop. Derfra åpner du prosjektet i VS Code. Repositoryet er der du lagrer alt du lager i oppgaven, og det er det du leverer inn til slutt.

1. Logg inn på github.com, og trykk **New** for å opprette et nytt repository. Gi det et navn, for eksempel `om-meg-nettside`, og trykk **Create repository**.
2. Trykk den grønne **Code**-knappen på repository-siden og velg **Open with GitHub Desktop**. Alternativt kan du velge **File → Clone repository** i GitHub Desktop og finne repositoryet i listen.
3. Velg en plassering på PC-en under **Local path**, og trykk **Clone**. Husk hvor mappen ligger. Dette blir prosjektmappen din.
4. Trykk **Open in Visual Studio Code** i GitHub Desktop for å åpne prosjektmappen i VS Code. Alle filene til nettsiden skal lages her.
5. Mens du jobber: når du har fått til en del, skriv en kort beskrivelse i **Summary** i GitHub Desktop, trykk **Commit to main** og deretter **Push origin**.

## Oppgaver

1. Lag en «Om meg»-side med hovedoverskrift (`<h1>`), et avsnitt om deg selv (`<p>`), minst tre deler med underoverskrifter (`<h2>`) og minst ett bilde med `alt`-tekst. Dette er grunnlaget for resten av oppgavene.
2. Del siden inn i semantiske elementer: `<header>`, `<nav>`, `<main>` med `<section>` for hver del, og `<footer>`.
3. Lag en navigasjonsmeny i `<nav>` med en liste av lenker som hopper til de ulike delene på siden (interne lenker med `id` og `href="#..."`).
4. Lag en tabell (`<table>`, `<tr>`, `<th>`, `<td>`) med fakta om deg eller for eksempel ukeskjemaet ditt. Tabellen skal ha overskriftsceller (`<th>`).
5. Legg inn et bilde i `<figure>` med bildetekst i `<figcaption>`.
6. Legg inn et favorittsitat i `<blockquote>`, og oppgi hvem det er fra.
7. Lag en beskrivelsesliste (`<dl>`, `<dt>`, `<dd>`) med for eksempel «Favorittmat», «Favorittfag» og «Drømmejobb».
8. Lag minst én ekstra side, for eksempel `interesser.html`, og lenk sidene sammen i begge retninger med relative lenker.
9. Ordne filene i mapper, for eksempel én mappe til bilder, og bruk riktige filstier i `src` og `href`.
10. Valgfri utfordring: lag et kontaktskjema med `<form>`, `<label>`, `<input>` og `<textarea>`. Skjemaet trenger ikke å fungere, men hvert felt skal ha en `<label>` knyttet til seg.

## Sjekk før innlevering

- [ ] Siden bruker `<header>`, `<nav>`, `<main>` og `<footer>`
- [ ] Menyen hopper til riktig del av siden
- [ ] Alle lenker mellom sidene fungerer, og alle bilder vises
- [ ] Tabellen har overskriftsceller (`<th>`)
- [ ] Koden har riktig innrykk og kommentarer
- [ ] Repositoryet er opprettet på GitHub.com og åpnet i GitHub Desktop, alle endringer er pushet, og lenken fungerer

## Innlevering

Oppgaven leveres som lenken til repositoryet ditt på GitHub:

1. Kontroller i GitHub Desktop at alle endringer er committet, og trykk **Push origin** slik at siste versjon ligger på GitHub.
2. Åpne repositoryet på GitHub.com og sjekk at alle HTML-sider og bildemappen er der.
3. Lever inn lenken til repositoryet innen [frist] via [innleveringssted]. Kontroller at læreren har tilgang til repositoryet.
