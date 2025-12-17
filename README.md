# Dagens Uppgifter: HTML Forms

Målet är att bygga formulär som inte bara fungerar, utan som är **tillgängliga**, **användarvänliga** och **robusta**.

Ni har fått en fil som heter style.css. Den innehåller CSS-variabler (färger, typsnitt) och en grundläggande "reset". Använd denna för att snabbt få ett snyggt utseende så att ni kan fokusera på HTML-strukturen.

## Uppgift 1: Det grundläggande kontaktformuläret

Skapa en ny HTML-sida och bygg ett klassiskt kontaktformulär. Fokusera på att få **semantiken** (HTML-taggarna).

**Krav:**

1.  [x] Skapa en form med method="POST".
2.  [x] Formuläret ska innehålla fält för:

    - [x] **Namn** (Ska stödja autocomplete).
    - [x] **E-post** (Ska visa rätt tangentbord i mobilen + autocomplete).
    - [x] **Ämne** (En dropdown/select med alternativ för olika avdelningar t.ex. "Support", "Försäljning").
    - [x] **Meddelande** (Ska vara en textarea).

3.  [x] Alla fält ska ha en **tydlig koppling** mellan label och input (använd for och id).
4.  [x] Lägg till validering (required) på namn och e-post.
5.  [x] Avsluta med en riktig button type="submit".

> **Tips:** Använd klasserna från style.css (t.ex. .card och .btn-primary) för att styla formuläret.

## Uppgift 2: Det avancerade formuläret (Frivillig)

Vill du utmana dig själv? Försök att återskapa utvärderingsformuläret vi gjorde på föreläsningen, eller hitta på ett eget scenario (t.ex. bordsbokning eller anmälan till ett event).

**Försök få med:**

- [x] En **Modal** () som öppnas med en knapp.
- [ ] **Checkboxes** För frågor där man kan välja fler svar
- [x] **Range slider** Gärna kopplad till en datalist för att visa markeringar
- [x] **Grupperingar** med **fieldset** och **legend** (t.ex. för Radio buttons).
- [x] Avancerade input-typer som type="date", type="range" (gärna med ) eller .\* Hjälptext kopplad med aria-describedby.

## Uppgift 3: Implementera på din Receptsida

Nu är det dags att applicera kunskapen på ditt pågående projekt! Gå till din **Receptsida** som du jobbat med i kursen.

**Gör följande:**

1.  Skapa en ny sektion eller en helt ny undersida för **"Kontakt"** eller **"Skicka in ditt recept"**. (frivillig implementering)
2.  Bygg ett formulär som passar in i din sidas design (du behöver inte använda den utdelade style.css här, utan använd dina egna variabler/stilar).
3.  Se till att formuläret uppfyller WCAG-kraven vi gått igenom (tydliga labels, tangentbordsnavigering, autocomplete).

## Checklista för godkänt formulär

Innan du känner dig klar, dubbelkolla detta:

- [x] Kan jag klicka på texten i en för att aktivera rutan? (Koppling for + id)
- [x] Har jag använt type="email" eller andra där det passar?
- [x] Har jag lagt till autocomplete="..." på namn och e-post?
- [x] Kan jag tabba mig igenom hela formuläret och skicka det med tangentbordet (Enter)?
- [x] Har jag använt och inte en button och inte en div för knappen?
