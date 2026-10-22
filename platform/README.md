# Generative AI Engineering — platformë studimi

Platformë statike, dygjuhëshe, e ndërtuar mbi materialet e kursit që u dërguan në `Generative_AI_Engineering_Coursera-main.zip`.

## Publikimi në Netlify

1. Zgjidh **Add new site → Deploy manually**.
2. Ngarko vetëm këtë dosje `platform` (ose cakto `platform` si *Publish directory* kur lidh repository-n).
3. Lëre komandën e build bosh; faqja nuk ka proces build-i.

## Përdorimi lokalisht

Hap `index.html` për hyrjen dhe përdor fjalëkalimin e caktuar në `app.js`. Për testim lokal me server statik, nga dosja `platform` ekzekuto `npx serve .`.

## Përmbajtja

- 16 kurse me 2 module dhe nënndarje teorike shqip/anglisht.
- Butoni SQ/EN ndërron gjuhën; zgjedhja ruhet në shfletues.
- Ushtrime shpjeguese, pyetje me alternativa, flashcards, fjalor dhe progres lokal.
- Secili prej 32 moduleve ka tri detyra kodimi në Python (të lehta, mesatare dhe të vështira), gjithsej 96 ushtrime, me editor bosh dhe kontroll kundrejt zgjidhjes referente. Nëse kodi nuk përputhet pas normalizimit të hapësirave, faqja shfaq zgjidhjen model; zgjidhjet alternative mund të jenë të sakta edhe nëse shënohen si të ndryshme.
- Fletoret Jupyter dhe përmbledhjet PDF të përzgjedhura nga ZIP-i gjenden te `resources/`.

Përparimi ruhet vetëm në `localStorage` të shfletuesit dhe nuk sinkronizohet mes pajisjeve. Hyrja me fjalëkalim është portë në anën e shfletuesit për organizim personal; nuk e mbron përmbajtjen nga persona që mund të shohin kodin e faqes. Mos e përdor si kontroll sigurie për informacion konfidencial.

## Kredite dhe licenca

Materialet burimore i atribuohen kursit të IBM në Coursera, sipas emërtimeve në arkivin e dorëzuar. Përmbajtja e platformës është për studim personal. Skedarët e kursit ruajnë të drejtat dhe kushtet e tyre origjinale; kontrollo kushtet e përdorimit përpara rishpërndarjes publike. Kodi i ri i platformës nuk merr licencë të veçantë këtu.
