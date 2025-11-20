# Whack-A-Mole

Wack-A-Mole-spel byggd i JavaScript. Spelet går ut på att samla poäng genom att klicka på "mullvadar" som slumpmässigt dyker upp och försvinner.
Poäng, antal missar och tid räknas.

## Hur man kör spelet

1. Öppna index.html
2. Tryck på "Starta"-knappen för att börja spelet.
3. "Slå" mullvadar genom att klicka på de bruna cirklarna eller trycka på space på tangentbordet.
4. Klicka på "Återställ" för att starta om spelet och nollställa poäng/tid.

## Val som har gjorts

- **Moduler**: Game och Mole i separata filer med import/export.
- **Eventdelegering**: En lyssnare för alla celler.
- **Flexbox**: för layout.
- **Tillgänglighet**: aria-labels, role="status", fokusmarkering.
